# reparacion-editorial

Capitalizar la intervención editorial: no corregir deficiencias solamente, sino usar cada intervención para MEJORAR la pieza — ritmo, tono y equilibrio — en la escala que corresponda (línea, párrafo, nodo, plot local, arco).

## Source

Dictado por Shane, 2026-10-18. Contexto: sesión sibling (GPT) amplía la intervención de rotación léxica a paráfrasis contextual; 27 rotaciones de diálogo → v0.3.5; paráfrasis como pasada diferenciada posterior. Convergencia con el hallazgo E006: el adelgazamiento industrial es micro-nivel, no corte de ciclo.

## La meta

Cada intervención es una oportunidad de mejora, no un parche. La selección de unas cuantas palabras puede cargar el equilibrio de la obra sin necesidad de pasajes completos.

## Escalas de intervención

- **Línea** — una réplica, una frase. Rotación léxica, paráfrasis mínima.
- **Párrafo** — la paráfrasis debe reforzar lo que ocurre ANTES y DESPUÉS.
- **Nodo** — secuencia breve; el cambio se propaga a las frases vecinas.
- **Plot local / arco** — solo cuando la intervención de escala menor revela que el problema vive arriba. Nunca empezar aquí.

## Los cuatro criterios

Toda paráfrasis propuesta se verifica contra los cuatro, en orden:

1. **Función** — ¿Se conservan intención, información y consecuencias narrativas? Si algo que ocurre después depende de la formulación exacta, la paráfrasis es inválida. **Prohibición de invención:** el candidato no afirma hechos fuera de evidencia (no convierte "no tenemos" en "no existe", no inventa historial con "esta vez").
2. **Voz** — ¿Cada personaje expresa la misma idea a SU manera? Experiencia, temperamento y registro lingüístico mandan. Dos personajes no resuelven igual la misma frase. **La elipsis es voz:** expandir réplicas elípticas ("Lo es", "Ya", "Mejor") no es mejorar — es normalizar.
3. **Continuidad** — ¿Se ajustaron las frases vecinas? La paráfrasis debe encajar naturalmente: sin ecos (la misma palabra brillando dos veces) ni contradicciones con lo ya establecido. **Check de nivel:** ¿el candidato cambia QUÉ se negocia o disputa, y no solo cómo? Si mueve el nivel (nombre → pacto interpersonal; ir → quedarse), es inválido aunque suene mejor.
4. **Economía** — Entre alternativas igualmente eficaces, preferir la MENOS común. Pero: sin explicaciones redundantes ni énfasis artificial. La rareza no es decoración. **Detector de explicitación:** si el candidato dice lo que el tono ya decía (nombra el sarcasmo, la ironía, la sequedad), auto-REJECT. No resolver paradojas load-bearing ("demasiado bien", "porque funcionaba").

## El principio

**Reforzar ≠ añadir palabras.** Una frase más concreta, una respuesta indirecta o un silencio bien situado fortalecen todo el párrafo. Si la paráfrasis alarga, debe ganarse cada palabra.

## Procedimiento de pasada

0. **Pre-filtro de ganancia.** Antes de generar alternativas, declarar la ganancia prometida en una línea (¿ritmo? ¿voz? ¿qué?). Sin ganancia nombrable, no generar. Distinguir mejorar de variar: la mayoría de los candidatos son variación, no mejora.
1. **Seleccionar la unidad** (línea → párrafo → nodo, en ese orden de preferencia).
2. **Diagnosticar la escala**: ¿el problema vive en esta unidad o arriba? Si vive arriba, subir un nivel, no forzar.
3. **Proponer la paráfrasis** con la meta explícita del paso 0.
4. **Verificar los cuatro criterios**, en orden. El primero que falle invalida la propuesta. **Las negaciones declaran su referente:** toda paráfrasis de un "no" debe nombrar qué negaba el original (un "no" sin referente verificado es inválido).
5. **Revisar vecinas**: leer el antes y el después en voz alta mental; cazar ecos.
6. **Registrar**: original → propuesta, escala, criterio que la justifica, verificación de vecinas. Trazable o no ocurrió.

## Cuándo NO intervenir

- Si la unidad ya cumple su función y ningún criterio promete mejora: **no tocar**. La skill sabe abstenerse.
- No usar paráfrasis para evitar un corte necesario (si el pasaje sobra, sobra).
- No intervenir por encima del nodo sin haber agotado las escalas menores.
- No aplicar antes de la pasada de arquitectura: la paráfrasis pule lo que existe; no decide qué existe.

## Evaluación

No se mide si desaparecen repeticiones. Se mide si el manuscrito gana **voz, ritmo y densidad narrativa sin perder ambigüedades**. Si la paráfrasis resuelve una ambigüedad load-bearing, falló el criterio 1.

## Relation to other skills

- Pares: `curate` (decide qué desaparece; reparación decide cómo suena lo que queda), suite-literaria v0.4.6 (gramática de transformación; reparación opera dentro de COMPRESS/REFOCUS sin cambiar función).
- La abstención es un resultado válido y se registra como tal.
## Available connectors

Use `muse.connector_search` to find the current connector docs before following
recovered instructions.
