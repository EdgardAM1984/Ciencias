---
name: revisar-postulacion
description: Usar cuando el usuario pide revisar, evaluar o mejorar una postulación o propuesta de proyecto (Corfo, FIA, ANID u otro fondo) antes de enviarla. Revisión crítica como lo haría un evaluador, según los criterios del fondo, con hallazgos priorizados y propuestas concretas.
---

# Revisar una postulación

Adaptado de las skills `requesting-code-review` y `receiving-code-review` de
obra/superpowers (licencia MIT).

**Principio:** revisa como un evaluador exigente, no como un coautor complaciente.
Una revisión que solo elogia no sirve. Cada observación debe apoyarse en el texto
de la propuesta o en las bases.

## Antes de revisar

1. Identifica el **fondo e instrumento** y consigue las **bases y la pauta de
   evaluación** (criterios y ponderaciones). Si no están, pídelas u ofrece buscarlas.
   Sin pauta, usa los criterios genéricos de abajo y dilo.
2. Lee la propuesta **completa**, incluidos anexos, presupuesto y Gantt.

## Criterios genéricos (si no hay pauta)

- **Pertinencia**: ¿el problema calza con el foco del instrumento y la convocatoria?
- **Problema y evidencia**: ¿está cuantificado y respaldado con fuentes?
- **Grado de innovación**: ¿se demuestra contra el estado del arte, productos
  registrados y literatura? ¿TRL inicial y final explícitos?
- **Mérito técnico**: objetivos medibles; metodología capaz de lograrlos; diseño
  experimental válido (testigos, réplicas, aleatorización, n suficiente, análisis
  estadístico definido); temporadas agrícolas realistas.
- **Coherencia interna**: objetivos ↔ actividades ↔ resultados ↔ indicadores ↔
  Gantt ↔ presupuesto.
- **Equipo**: capacidades demostradas para cada rol; dedicación horaria razonable.
- **Presupuesto**: cumple topes y aportes; ítems justificados; sin ítems no financiables.
- **Riesgos**: identificados y con mitigación realista (incluido registro SAG).
- **Impacto y escalamiento**: modelo de negocio, mercado, transferencia, PI.
- **Forma**: límites de caracteres, campos obligatorios, anexos y cartas de compromiso.

## Formato del resultado

Clasifica cada hallazgo:

- 🔴 **Crítico**: puede causar inadmisibilidad o un puntaje bajo (incumplimiento de
  bases, incoherencia presupuestaria grave, objetivo inalcanzable con la metodología).
- 🟡 **Importante**: baja puntaje en un criterio (evidencia débil, indicador no medible).
- ⚪ **Menor**: redacción, formato, claridad.

Para cada hallazgo: **sección**, **qué dice el texto** (cita breve), **por qué es un
problema** (criterio afectado) y **propuesta concreta** (texto alternativo si aplica).

Termina con: puntaje estimado por criterio (si hay pauta), las 3 mejoras de mayor
impacto y lo que está bien hecho (breve, solo si es real).

## Al recibir observaciones de evaluadores

Si el usuario trae observaciones de una evaluación anterior: verifica cada una contra
el texto; no la aceptes ni la rechaces sin revisarla. Si una observación es incorrecta,
dilo con argumentos técnicos. Si es correcta, propón el cambio concreto.

## Señales de alerta

| Pensamiento | Realidad |
|---|---|
| "Se ve bien en general" | Busca activamente la incoherencia; casi siempre hay alguna. |
| "No tengo las bases, asumo" | Dilo explícitamente y marca lo que depende de las bases. |
| "Es un detalle de forma" | Un anexo faltante puede dejar la postulación fuera de bases. |
