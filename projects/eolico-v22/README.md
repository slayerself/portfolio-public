# Materiales de Portafolio

Esta carpeta contiene una version curada del proyecto para uso publico.

## Archivos principales

- `v22_case_study.md`: resumen tecnico para GitHub, Notion o PDF.
- `index.html`: pagina estatica lista para publicar en GitHub Pages, Netlify o un sitio personal.

## Que mostrar

- problema operacional: pronostico eolico day-ahead con emision a las 08:00 `America/Santiago`
- pipeline: calibracion MOS de viento + MOE de potencia
- rigor temporal: validacion por `issue_time`, control anti-leak y horizonte `lead 1..24`
- resultado final: candidato congelado `baseline_soft_cqr`
- benchmark externo: comparacion contra programacion diaria del Coordinador en ventana no-leak

## Que no publicar tal cual

- datos pesados o con restricciones de uso
- artefactos completos de modelos entrenados
- credenciales, rutas internas o scripts auxiliares sin contexto
- detalles operativos que no aporten al caso de estudio

## Uso recomendado

1. Publicar `index.html` como landing tecnica.
2. Enlazar desde la landing a un repo publico curado o a `v22_case_study.md`.
3. Mantener el foco en metodologia, benchmark y aprendizajes, no en listar todos los scripts.
