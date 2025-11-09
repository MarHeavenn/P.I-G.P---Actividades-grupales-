# reporte del sprint — control de valor ganado (evm)

## 1. contexto del proyecto
- equipo: Gisee
- sprint #: 2   período: 2025-21-10 / 2025-7-11
- meta del sprint: Implementar el módulo RAG con almacenamiento vectorial, gestión de embeddings y conexión con modelo Gemini.

## 2. resumen ejecutivo (al corte)
- estado general: ☑ verde — criterio: se cumplieron todas las historias planificadas dentro del presupuesto.
- principales riesgos/bloqueos: carga del modelo Gemini generó lentitud al inicio del sprint.
- decisiones tomadas: optimizar la conexión con Gemini y paralelizar el preprocesamiento de embeddings en el siguiente sprint.

## 3. métricas clave
- BAC total: 5822  |  PV: 4586 |  EV: 3846,285714  |  AC: 4270
- SV = EV - PV: -739,7142857  |  CV = EV - AC: -423,7142857
- SPI = EV/PV: 0,838701639  |  CPI = EV/AC: 0,900769488
- EAC = BAC/CPI: 6941,681919  |  ETC = EAC - AC: -4269,099231

> Fuente: archivo **Plantilla-EVM-Sprint.xlsx** (hojas *WBS*, *Costos*, *Métricas*).

## 4. WBS y definición de hecho (DoD)
- regla de ganancia por entregable: ☑ 50/50
- evidencia mínima de DoD por tipo:
  - feature: código funcional en rama principal + pruebas unitarias + validación en entorno staging
  - bug: issue documentado + test reproducible + commit del fix + verificación del QA
  - tech: configuración Docker y entorno validada con despliegue exitoso

## 5. gráficos sugeridos (opcional)
- curva S (PV/EV/AC) al corte
- burnup/burndown de historias o puntos

## 6. enlaces de evidencia
- repositorio: (https://github.com/MarHeavenn/P.I-G.P---Actividades-grupales-)
- ambiente staging/producción: ______________________
- tablero (jira/linear/openproject): (https://gisee.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog)

## 7. acuerdos para el siguiente sprint
- mejoras de proceso: incluir revisión técnica cruzada antes de mergear PRs.
- cambios de alcance/prioridad: incorporar pipeline de conversación completo y conexión con memoria contextual.
---
