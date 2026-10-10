---
name: diagnostico-ensayos
description: Usar cuando un ensayo de laboratorio, invernadero o campo da resultados inesperados o negativos (p. ej. un bioinsumo sin efecto, baja viabilidad, contaminación, resultados no reproducibles, alta variabilidad), antes de proponer cambios en la cepa, la formulación o el protocolo.
---

# Diagnóstico sistemático de ensayos

Adaptado de la skill `systematic-debugging` de obra/superpowers (licencia MIT).

## Regla de hierro

```
NINGÚN CAMBIO SIN INVESTIGAR PRIMERO LA CAUSA RAÍZ
```

Cambiar la dosis, la cepa o el formulado "a ver si funciona" quema una temporada.
Si no completaste la Fase 1, no propongas soluciones.

## Fase 1: Investigar la causa

1. **Describir el resultado con precisión**: qué se esperaba, qué se obtuvo, con qué
   magnitud y variabilidad. Pide los datos crudos, no solo el promedio.
2. **¿Es real?** Revisa el diseño: testigos (absoluto, comercial, formulado sin
   microorganismo), réplicas, aleatorización, n, poder estadístico. Un "sin efecto"
   con CV del 40 % y 3 réplicas no demuestra ausencia de efecto.
3. **¿Qué cambió?** Respecto a ensayos que sí funcionaron: lote de inóculo, medio,
   proveedor de insumos, operador, fecha, clima, suelo, variedad.
4. **Recorrer la cadena, eslabón por eslabón**, con evidencia en cada punto:

   | Eslabón | Evidencia a pedir |
   |---|---|
   | Cepa | Identidad confirmada (16S/ITS, MALDI-TOF), pureza, número de subcultivos, pérdida de fenotipo |
   | Producción | Curva de crecimiento, UFC/mL al cosechar, contaminantes |
   | Formulación | Compatibilidad portador/aditivos, pH, actividad de agua, UFC al formular |
   | Almacenamiento | Temperatura, tiempo, UFC al momento de aplicar |
   | Aplicación | Dosis real, mezcla en estanque (fungicidas, cobre, cloro del agua, pH), método, horario, radiación UV |
   | Ambiente | Temperatura, humedad, riego, tipo de suelo, pH, CE, MO, microbiota nativa |
   | Establecimiento | Recuento/qPCR en rizosfera o filoplano tras la aplicación |
   | Respuesta | Variable medida, momento de muestreo, método de medición |

   Ubica **dónde se rompe la cadena** (p. ej. UFC correctas al formular pero 10² veces
   menores al aplicar → problema de almacenamiento o de mezcla, no de la cepa).

## Fase 2: Comparar con lo que funciona

- Ensayos propios exitosos, literatura, ficha técnica de productos similares.
- Lista **todas** las diferencias, aunque parezcan irrelevantes.

## Fase 3: Hipótesis y prueba

1. Formula **una** hipótesis: "Creo que X es la causa porque Y".
2. Diseña la prueba **mínima** que la confirme o descarte, cambiando **una sola
   variable** (p. ej. recuento de UFC en el caldo de aplicación con y sin el fungicida).
3. ¿Se confirmó? → Fase 4. ¿No? → nueva hipótesis. No acumules cambios.
4. Si no sabes, dilo y propone qué medir o qué buscar en la literatura.

## Fase 4: Corregir y validar

- Corrige la causa, no el síntoma.
- Valida con un ensayo con testigos que demuestre la mejora.
- Documenta la causa y la corrección (protocolo, ficha técnica, control de calidad).

**Si tres correcciones seguidas fallan**, detente: probablemente la premisa está mal
(la cepa no tiene el modo de acción supuesto, el cultivo no responde en esas
condiciones). Discútelo con el usuario antes de seguir.

## Señales de alerta

| Pensamiento | Realidad |
|---|---|
| "Subamos la dosis" | Sin saber dónde se rompe la cadena, es adivinar. |
| "Fue el clima" | Puede ser; demuéstralo con datos y el testigo comercial. |
| "La cepa perdió actividad" | Compruébalo con el banco de cepas original. |
| "No hubo diferencias, la cepa no sirve" | Revisa primero el poder estadístico del ensayo. |
