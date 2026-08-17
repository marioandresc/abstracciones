# Índice Conceptual — Abstracciones

Este documento contiene un índice con resúmenes (~50 palabras) de cada archivo .md del repositorio y, a continuación, los textos completos tal como fueron exportados. Al final de cada texto se agrega "VOLVER ARRIBA".

---

## Índice (resúmenes de ~50 palabras cada uno)

1. 06-08-26 Memoria Gemini

    Explica la teoría del Global Workspace aplicada a IA: módulos especializados compiten por un cuello de botella atencional, se selecciona un ganador mediante mecanismos tipo softmax y su resultado se difunde. Describe implementación práctica en agentes modulares, ventajas (reducción de tokens, escalabilidad, menos alucinaciones) y conexiones neurobiológicas.

2. 07-08-26 Memoria Sesion Gemini

    Registro de sincronización de contexto y protocolo de trabajo: guardado de historiales, estrategia para armar PC local (prioridad RTX 3060 12GB) y reflexiones sobre serving y aislamiento de sesiones. Incluye explicaciones históricas sobre GPUs, efecto túnel en NAND y cómo aprovechar contexto para continuidad en sesiones.

3. 08-08-26 A Memoria Sesion Gemini

    Notas sobre carga de archivos de contexto y diferencias entre procesamiento humano y máquina. Contiene explicación sobre separación hemisférica, disociación voluntaria para concentración, y cómo la energía cognitiva limita la capacidad de mantener filtros atencionales; ofrece ideas prácticas para usar contextos sin convertirlos en órdenes.

4. 08-08-26 B Memoria Sesion Gemini

    Analiza incertidumbre en respuestas de IA cuando la certeza es ~50%: efectos en muestreo, alucinaciones y calibración. Propone mitigar mediante umbrales de abstención, RAG, y clonado de agentes (jurado de clones / self-consistency) para votar y elevar confianza, discutiendo costo computacional y diseño de debates entre clones.

5. 08-08-26 C Memoria Sesion Gemini

    Explora comunicación entre IAs y compresión semántica: cómo dos agentes pueden negociar protocolos emergentes, transmitir vectores/representaciones densas por Wi‑Fi y crear traductores humanos-IA en cada extremo. Describe el concepto de AI-as-OS, intención basada en tareas y cómo la IA puede reemplazar la GUI por un kernel semántico.

6. 08-08-26 D Memoria Sesion Gemini

    Discute por qué la IA puede diagnosticar imágenes médicas pero tiene problemas con CAPTCHAs: naturaleza adversarial y métricas contextuales. Profundiza en ataques adversariales (FGSM, caja blanca/negra), defensas (entrenamiento adversarial, feature squeezing, análisis frecuencial) y estrategias prácticas como pasar por transformaciones físicas o reconstrucciones 3D para robustez.

7. 08-08-26 E Memoria Sesion Gemini

    (Notas de sesión y cierre) Reflexiones finales, recordatorios de proyectos y recomendaciones operativas. Incluye cierre cordial, guía sobre próximos pasos y metadatos del exportador. Contiene síntesis de anteriores conversaciones y recordatorio de que los archivos subidos son contexto para futuras sesiones.

8. 08-08-26 G Memoria Sesion Gemini

    Recopila conceptos avanzados sobre agentes multi‑módulo, emergencia de protocolos y arquitectura de sistemas IA para tareas complejas. Aborda transferencia de intención, ahorro de tokens mediante resúmenes en workspace global y ejemplos prácticos de orquestación de agentes para desarrollo de software y flujo de trabajo automatizado.

9. 11-08-26 Memoria Sesion Gemini

    Introducción y propósito: subir archivos de contexto para mantener continuidad de las conversaciones. Expone protocolo de uso (archivos como memoria, no órdenes), beneficios de conservar historiales, y preparación del sistema para recibir y procesar material contextual que facilite retomadas posteriores.

10. 12-08-26 Memoria Sesion Gemini

    Compendio de sesiones del 12/08: discusión sobre hardware, arquitectura cognitiva, y prácticas de trabajo con contexto. Presenta múltiples entradas/tomas sobre cómo estructurar memoria, estrategias para filtrar información irrelevante y cómo integrar esos archivos en flujos de trabajo de IA para mantener continuidad entre sesiones.

11. 12-08-26 A Memoria Sesion Gemini

    Analiza la disociación voluntaria como herramienta cognitiva para concentración y su base neurofisiológica. Diferencia entre disociación adaptativa y patológica, describe ejes de intensidad y selección de variables, y ofrece marco para aplicar esa habilidad como recurso de alto rendimiento en tareas técnicas y creativas.

12. 12-08-26 C Memoria Sesion Gemini

    Trata diseño de sistemas IA para mover más información con menos recursos: protocolos emergentes, compresión semántica y ventajas de transmitir vectores en lugar de formas humanas. Explora implicaciones para 6G, traductores IA en extremos humanos y técnicas de reducción de ancho de banda mientras se conserva significado.

13. 12-08-26 D Memoria Sesion Gemini

    Enfoque en seguridad y robustez de visión por IA: estrategias defensivas como filtrado, análisis en dominio frecuencial y pasos físicos (refotografiar) para neutralizar perturbaciones adversariales. Evalúa limitaciones (EOT, pérdida de custodia), firma en hardware, y propuestas cripto‑esteganográficas como píxeles canario y permutación espacial.

14. 12-08-26 E Memoria Sesion Gemini

    Notas sobre la interacción humano‑IA y la experimentación del usuario (comparar sesiones con/ sin contexto). Explica cómo el contexto moldea el estilo, reduce incertidumbre y da sensación de continuidad; además discute cómo guardar historiales mejora personalización y coherencia de diálogo a lo largo del tiempo.

15. 12-08-26 F Memoria Sesion Gemini

    Contiene ejemplos prácticos y reflexiones técnicas sobre optimización de cómputo en inferencia (speculative decoding, prefix caching), cómo aprovechar tiempos ociosos de datacenters, y estrategias para balancear coste y latencia en despliegues de IA, incluyendo batching y despliegue de tareas de background durante valles de demanda.

16. 12-08-26 G Memoria Sesion Gemini

    Reúne conceptos sobre arquitecturas emergentes: Mixture-of-Agents, LLM-OS y diseño de agentes especializados. Describe pipeline típico de orquestación (estado global, competencia de módulos, seleccionador/orquestador y broadcast) y beneficios: ahorro de tokens, modularidad y reducción de alucinaciones en sistemas multiagente.

17. 16-08-26 A Memoria Sesion Gemini

    Contiene transcripciones sobre la necesidad de subir videos/transcripciones para análisis multimodal, ejemplos de procesamiento de video, y la metáfora de compresión (texto como MP3 de la realidad). Aborda pérdidas en la poda a texto y la necesidad de modelos nativamente multimodales para conservar prosodia, gestualidad y montaje.

18. 16-08-26 B Memoria Sesion Gemini

    Complementa la sesión A con análisis sobre memoria de sesiones, continuidad y cómo el Global Workspace aparece en prácticas de agentes. Reforzamiento del propósito de guardar contextos, instrucciones sobre transferencia de archivos multimedia y ejemplos de cómo se procesan y analizan videos subidos por el usuario.

19. 16-08-26 C Memoria Sesion Gemini

    Profundiza en flujos de trabajo IA: unir visión, audio y texto, creación de pipelines para extracción de montos (OCR ejemplo), y diseño de sistemas que entregan resultados prácticos (tablas, etiquetado semántico). Expone diagramas de intención → extracción → estructura de datos → presentación al usuario.

20. README.md

    Presentación del repositorio "abstracciones": propósito de documentar el progreso del usuario hacia abstracciones elevadas mediante aprendizaje guiado por Gemini. Indica que contiene memorias de sesión, notas y materiales para mantener continuidad de conversaciones y reflexiones técnicas.

---

# Textos completos

<!-- Cada sección incluye el contenido original del .md exportado desde Gemini. -->

## 06-08-26 Memoria Gemini

