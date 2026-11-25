# Síntesis

> Síntesis redactada con Claude a partir de las fuentes de `fuentes.md` (no se usó NotebookLM; ver `05-ia/prompts.md`).

**Pregunta de mi módulo:** ¿Qué riesgos hay en el proceso de la planta de Yerbatera Tres Fronteras y cómo se previenen?

## Síntesis
La planta (12 operarios, 1 turno) está alcanzada por la Ley 19.587 y su Decreto 351/79, que obligan al empleador a identificar riesgos, proveer EPP adecuado y contar con servicio de higiene y seguridad, y por la Ley 24.557, que exige ART y un plan de prevención. Los riesgos más graves se concentran en dos procesos: el **secado** (incendio de la cinta/secanza y quemaduras por calor) y la **molienda** (ruido, polvo orgánico inflamable y atrapamiento en partes móviles). En recepción y depósito predominan los riesgos ergonómicos (levantamiento de bolsas y carga del camión mensual) y los golpes con vehículos o estibas. En envasado los riesgos son de menor gravedad (movimientos repetitivos, cortes). La prevención combina controles de ingeniería (aspiración de polvo, encerramiento de molinos, resguardos, detección y extinción de incendios) con medidas administrativas (capacitación, orden y limpieza, rotación de tareas) y EPP entregado con constancia según Res. SRT 299/2011.

## Hallazgos clave
1. **[VERIFICADO]** Ley 19.587 art. 8 y 10: el empleador debe proveer equipos de protección individual y el trabajador debe usarlos y cuidarlos (texto oficial en InfoLEG).
2. **[VERIFICADO]** Res. SRT 299/2011 crea la "Constancia de entrega de ropa de trabajo y EPP", de uso obligatorio (página oficial de la SRT).
3. **[VERIFICADO]** Res. SRT 85/2012 aprueba el protocolo obligatorio de medición de ruido en el ambiente laboral (argentina.gob.ar).
4. **[VERIFICADO]** Incendio en un secadero de Misiones (20/11/2026) que afectó la cinta de secado y ~30 t de hoja verde (nota periodística).
5. **[REVISAR]** El polvo de yerba mate en particular puede ser explosivo: la fuente habla de polvos orgánicos en general; no encontré un ensayo específico para yerba mate.
6. **[REVISAR]** Nivel de ruido real de los molinos de la planta: hay que medirlo con el protocolo de la Res. 85/2012; en la matriz se asumió > 85 dB(A).

## Datos que voy a usar en la planilla
- Dotación por proceso (de `datos_base.md`): Recepción 2, Secado 3, Molienda 2, Envasado 3, Depósito y carga 2 → total 12.
- Escala de evaluación: probabilidad 1–5 × gravedad 1–5 = nivel (1–25). Alto ≥ 15, Medio 8–14, Bajo ≤ 7.
- Peligros por proceso según las búsquedas 2 y 3 (incendio, polvo, ruido, ergonómicos, atrapamiento).
- EPP por puesto según Dec. 351/79 cap. 19 y Res. SRT 299/2011.
