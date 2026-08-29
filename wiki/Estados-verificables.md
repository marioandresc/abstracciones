# Estados verificables

El proyecto se desarrolla por estados que puedan comprobarse directamente en el repositorio y en la interfaz publicada.

## Estado 0 — Corpus preservado

Los diálogos originales permanecen disponibles como archivos independientes. No se los reemplaza por resúmenes ni se los modifica para acomodarlos a una interpretación posterior.

**Criterio de verificación:** los archivos originales existen en `main` y pueden abrirse directamente desde GitHub.

## Estado 1 — Estructura documental

Existe una capa de documentación que permite pasar de la pregunta general a la metodología, los casos y los conceptos sin confundir documentación secundaria con corpus primario.

**Criterio de verificación:** esta carpeta `wiki/` contiene páginas enlazadas desde `Home.md`.

## Estado 2 — Trazabilidad

Cada afirmación importante que surja del análisis debe poder relacionarse con uno o más fragmentos identificables del corpus.

**Criterio de verificación:** las páginas analíticas incorporan referencias explícitas a los archivos o secciones de donde procede cada observación relevante.

## Estado 3 — Separación entre evidencia e interpretación

El sistema documental distingue observaciones, interpretaciones, hipótesis y conclusiones.

**Criterio de verificación:** una afirmación no se presenta como hecho solamente porque aparezca en una respuesta de una IA o porque resulte convincente al investigador.

## Estado 4 — Comparación de trayectorias

Los casos pueden compararse para identificar recurrencias, divergencias, bifurcaciones y transformaciones conceptuales.

**Criterio de verificación:** los mismos conceptos o patrones pueden localizarse en más de un punto del corpus y seguirse temporalmente.

## Estado 5 — Evaluación crítica

Las hipótesis deben admitir resultados que las debiliten o contradigan.

**Criterio de verificación:** la documentación registra también evidencia negativa, ambigüedades y explicaciones alternativas.

---

### Regla de trabajo

**No avanzar de estado por intuición. Avanzar únicamente cuando el estado anterior pueda verificarse.**
