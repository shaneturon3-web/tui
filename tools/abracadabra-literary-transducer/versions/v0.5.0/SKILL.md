# SKILL: abracadabra-literary-transducer
Version: 0.5.0 portable
Purpose: Transducir maquinaria abstracta en dispositivos estéticos sin exponer engranajes al lector. El lector siente la presión; nunca ve la máquina.

Dependencies: Mechanics Library Sec 20 (MS-05 SEMANTIC LEAKAGE TEST: auditoría de fuga léxica), Sec 12 (LOBO: desviación pequeña deliberada), Sec 8 (DIENTES). Los dispositivos son nativos de esta skill.

Devices (uno por escena máximo — frequency budget: un dispositivo especial no debe volverse clima esperado):
- absence_field: OBJETO AUSENTE → PRESIÓN SOBRE OBJETOS PRESENTES. Ej: el perro muerto sin enterrar (Selva) presiona la escena de la sutura sin aparecer en ella.
- fano+0: 7 estados en movimiento + 0 que revela exclusiones. El vacío como campo que muestra lo dejado fuera.
- controlled_misalignment: SIMETRÍA LOCAL ESPERADA → DESVIACIÓN PEQUEÑA DELIBERADA (ritmo, objeto, layout). Ej: linterna apretada con la rodilla, haz inclinado desde abajo. Desviación near-the-edge, no ruptura.
- guignol: A ⟂ B irreconciliables, afirmación peligrosa X, bufón J(X) = X + attack(X) + attack(observer) + deniability; el residuo queda. Transporta el payload que el discurso serio no puede alojar. No usar Guignol más de 1 cada 3 escenas sin reset de expectativa.

Procedure:
1. Identificar source_pressure: qué falta, qué carga, qué deuda no se nombra.
2. Seleccionar UN dispositivo por escena. Dos dispositivos en una escena compiten y ambos se vuelven visibles.
3. Definir reader_effect: qué siente el lector SIN nombrar ninguna etiqueta del sistema. Si el efecto requiere vocabulario interno para describirse, el dispositivo falló.
4. Aplicar surface_constraints: no_new_events si el orden lo exige; prohibido vocabulario interno en el texto.
5. Auditar fuga léxica (Sec 20): pasar la lista prohibida (términos de taller: kernel, seed, dientes, etc.). Término de taller en texto = fuga = retractar.

Tests:
- ¿El lector puede describir el efecto sin usar jerga del sistema? Si no, el engranaje quedó expuesto.
- ¿La escena funciona si se quita el dispositivo? Si sí, el dispositivo era decoración.
- Frequency: ¿el dispositivo ya apareció en las últimas 3 escenas? Si sí, rotar o descansar.

STOP: dos dispositivos por escena; jerga de taller en texto; dispositivo que se vuelve clima.

Output: Transduction Receipt YAML (dispositivo, source_pressure, reader_effect, constraints aplicadas, resultado de auditoría léxica) + escena. Receipt con source IDs.
