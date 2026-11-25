# Registro de uso de IA

Herramienta usada en todo el examen: **Claude (Claude Code)**. No se usaron Perplexity ni NotebookLM: Claude reemplazó ambas etapas, buscando en la web y redactando la síntesis.

## Prompt 1
- **Herramienta:** Claude (Claude Code)
- **Etapa:** 0 a 6 (pedido general)
- **Prompt:** "https://github.com/hcgalvantech/examen-informatica-plantilla hacelo eso que dice en el repositorio de github" (luego elegí la consigna de Higiene y Seguridad)
- **Qué respondió (resumen):** Leyó el README y la consigna, hizo búsquedas web y generó `fuentes.md`, `sintesis.md`, `planilla.xlsx` (3 hojas, fórmulas y gráfico), `informe.pdf` y el texto para Gamma.
- **Qué acepté / qué corregí y por qué:** (COMPLETAR por el estudiante: qué revisaste y qué cambiaste vos)

## Prompt 2
- **Herramienta:** Claude – búsqueda web
- **Etapa:** 1 (investigación)
- **Prompt:** Búsquedas: "Ley 19.587 higiene y seguridad en el trabajo infoleg", "Ley 24.557 riesgos del trabajo infoleg", "riesgos laborales secaderos molinos yerba mate polvo ruido", "secanza yerba mate riesgo incendio explosión polvo", "Resolución SRT 299/2011 EPP", "SRT ruido Resolución 85/2012".
- **Qué respondió (resumen):** Textos oficiales en InfoLEG y argentina.gob.ar, una nota sobre un incendio en un secadero de Misiones (20/11/2026) y un artículo sobre polvos orgánicos inflamables.
- **Qué acepté / qué corregí y por qué:** Acepté solo fuentes oficiales para la normativa. Descarté notas periodísticas sobre trabajo informal en la cosecha porque no se refieren a la planta. El riesgo de explosión del polvo de yerba quedó como [REVISAR] porque la fuente es general.

## Prompt 3
- **Herramienta:** Claude
- **Etapa:** 3 y 4 (planilla e informe)
- **Prompt:** Armar la matriz con probabilidad × gravedad para los 5 procesos de `datos_base.md`, la hoja de EPP con la dotación por puesto, el plan de acción y un informe de 1–2 páginas con tabla y gráfico.
- **Qué respondió (resumen):** 12 riesgos (3 altos, 7 medios, 2 bajos), 53 EPP, 8 medidas; informe en PDF con portada y numeración.
- **Qué acepté / qué corregí y por qué:** El primer borrador del informe decía "5 medidas de corto plazo"; al contrastar con la hoja "Plan de acción" eran 4 (y 3 de mediano plazo), así que se corrigió.

## Reflexión final (3 líneas)
Un dato o afirmación de la IA que tuve que verificar o corregir, y cómo lo hice:
El conteo de medidas por plazo del informe no coincidía con la planilla; se corrigió con la fórmula CONTAR.SI de la hoja "Plan de acción". También quedó sin verificar el nivel real de ruido de los molinos: se asumió > 85 dB(A) y hay que medirlo con el protocolo de la Res. SRT 85/2012.
