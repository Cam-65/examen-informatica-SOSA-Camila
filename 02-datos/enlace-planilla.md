# Planilla del módulo

- **Enlace a Google Sheets (cualquier persona con el enlace puede ver):** (PENDIENTE: subir `planilla.xlsx` a Google Drive → Abrir con Google Sheets → Compartir → "Cualquier persona con el enlace" → pegar acá)
- **Archivo subido:** `02-datos/planilla.xlsx`

## Hojas incluidas
1. **Matriz de riesgos:** 12 riesgos en los 5 procesos (proceso, peligro, riesgo, probabilidad, gravedad, nivel, clasificación, medida de control) + resumen por nivel y gráfico.
2. **EPP:** EPP por puesto, operarios tomados de la tabla de dotación de `datos_base.md` y cantidad total de EPP.
3. **Plan de acción:** 8 medidas con riesgo que controlan, responsable y plazo (corto/mediano/largo) + conteo por plazo.

## Fórmulas principales utilizadas
- Nivel: `=D2*E2` (probabilidad × gravedad)
- Clasificación: `=SI(F2>=15;"Alto";SI(F2>=8;"Medio";"Bajo"))`
- Resumen por nivel: `=CONTAR.SI($G$2:$G$13;A17)`
- Operarios por puesto: `=BUSCARV(A2;$G$3:$H$7;2;FALSO)` · Total EPP: `=C2*D2` y `=SUMA(E2:E18)`
- Medidas por plazo: `=CONTAR.SI($E$2:$E$9;D12&"*")`

## Gráfico
Qué muestra: columnas con la cantidad de riesgos por nivel (Alto 3, Medio 7, Bajo 2), en la hoja "Matriz de riesgos".
