# Metodología de investigación

## Principio general

El objeto de estudio es la **trayectoria conceptual** producida durante conversaciones prolongadas entre una persona y un sistema generativo de IA.

El corpus se conserva como registro primario. Las interpretaciones posteriores deben poder regresar al diálogo y señalar qué observación las origina.

## Unidad de análisis

La unidad básica no es una respuesta aislada, sino una secuencia de transformaciones:

`S₀ → IA → S₁ → humano → S₂ → IA → S₃ → …`

Los estados son representaciones descriptivas, no variables matemáticas formalizadas.

## Procedimiento de análisis

Para cada caso se registra, cuando sea posible:

1. **Punto de partida:** pregunta, problema o concepto inicial.
2. **Origen:** qué participante introduce explícitamente cada elemento relevante.
3. **Transformación:** qué cambia después de cada intervención.
4. **Reinterpretación:** qué modificaciones introduce el otro participante.
5. **Recurrencia:** cuándo reaparece un concepto y con qué significado.
6. **Bifurcaciones:** puntos donde existían varias direcciones plausibles.
7. **Resultado:** estructura conceptual alcanzada al final del tramo analizado.
8. **Alternativas:** explicaciones que no requieren emergencia.

## Criterios de evaluación

### Trazabilidad

Una afirmación debe poder vincularse con fragmentos identificables del corpus.

### Novedad

Que una formulación aparezca por primera vez en el registro no demuestra novedad fuerte. Debe distinguirse entre creación, reformulación, combinación, recuperación e inferencia.

### Dependencia de trayectoria

Se pregunta si el resultado depende de la secuencia concreta de intercambios o si probablemente habría aparecido mediante una consulta equivalente y aislada.

### Atribución

Se analiza qué aporta cada participante y se evita atribuir automáticamente el resultado completo a uno solo.

### Robustez

Un fenómeno adquiere mayor interés si puede observarse en más de un caso, conversación, condición o modelo.

### Falsabilidad

La hipótesis debe admitir resultados que la debiliten. Un caso que admite una explicación alternativa simple no debe ocultarse para favorecer la hipótesis.

## Exploración frente a verificación

**Exploración** significa generar asociaciones, preguntas e hipótesis durante la conversación.

**Verificación** significa reconstruir posteriormente el recorrido y separar lo observado de lo inferido.

La conversación puede ser creativamente valiosa aunque una interpretación generada durante ella resulte posteriormente incorrecta.

## Registro recomendado por caso

| Campo | Contenido |
|---|---|
| Caso | Identificador del diálogo |
| Tramo | Ubicación dentro del diálogo |
| Estado inicial | Conceptos relevantes en S₀ |
| Intervención IA | Transformación observable |
| Intervención humana | Reinterpretación observable |
| Estado posterior | Cambios en S₁, S₂… |
| Evidencia | Fragmentos verificables |
| Interpretación | Explicación propuesta |
| Alternativas | Explicaciones competidoras |
| Confianza | Baja / media / alta |

## Limitaciones actuales

Este corpus no constituye por sí solo un experimento controlado. Quedan pendientes, entre otras cuestiones, controles adecuados, definición operacional de novedad e irreductibilidad, comparación sistemática entre modelos y pruebas de reproducibilidad.

Por ello, las páginas del proyecto deben distinguir cuidadosamente entre **casos compatibles con una hipótesis** y **evidencia suficiente para establecerla**.

## Regla metodológica central

> **Primero reconstruir la trayectoria; después interpretar la trayectoria.**

Nunca utilizar la conclusión para seleccionar retrospectivamente solamente los fragmentos que parecen confirmarla.

[← Presentación](Presentacion.md) · [Hipótesis →](Hipotesis.md) · [Estados verificables](Estados-verificables.md)
