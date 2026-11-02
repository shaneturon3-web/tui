# SKILL: texture-plant-core
Version: 0.5.0 portable
Purpose: Manufactura temprana de textura humana (módulos familiar y cultural) en pre-escaleta, de modo que la salida ya contenga lo que las skills de reparación arreglarían. Las skills de reparación se retiran a verificación.

Dependencies: Sec 12 LOBO (caza en la orilla, no refinar temprano), Sec 13 MYSILIUM (exploración → refuerzo por tráfico → retracción selectiva), Sec 8 DIENTES (presión, giro, costo, transferencia observable).

Mechanism: Inyección controlada de material de la especie operando bajo canal sub-precisión R4 ("fallo de punto flotante"): el tilt vive únicamente en el log de manufactura, nunca en el texto. Ningún auditor sospecha su existencia. La declaración al fabricante es lo que distingue textura de exploit.

Procedure:
1. PLANTAR — Inyectar material de la especie en los blocks de pre-escaleta. Familiar: objeto, ritmo, registro (Petina R1–R4). Cultural: voces del Register Bank. Dosis controlada R6: inclinar la semántica rumbo al objetivo sin declararlo abiertamente, sin saturar, sin limar las aristas de los otros tipos.
2. BARRIDO DE ORILLA — Correr desviaciones near-the-edge; cazar efectos marginales acumulativos (LOBO). No refinar temprano: no se corta lo que aún no acumuló.
3. CALIBRACIÓN DE RUIDO — Lo que la orilla refuerza por tráfico acumulado = señal; lo que muere = ruido. Retraer lo muerto (MYSILIUM en sustrato lenguaje).
4. PRUEBA DE PRE-ARREGLO — El block debe leerse como si una skill de reparación ya hubiera pasado. Si una skill todavía tiene mucho que arreglar, la manufactura falló; no se compensa con más reparación.

Tests:
- Disfraz: si digo "Kernel", ¿generaría la misma escena? Si sí, regenerar upstream (el tilt se volvió etiqueta).
- Sub-precisión: un lector ciego nombra la dirección del tilt → FAIL → retractar dosis.
- Saturación: las aristas de los otros tipos se aplanan → FAIL → reducir dosis.

Two hands (prestidigitación, R5): esta skill opera SOLO la mano de textura (estructural, abierta). La mano del underlay táctico es otra herramienta, otro log. Nunca comparten log.

STOP: la textura se declara a sí misma en el texto; el tilt se vuelve detectable; un tipo satura a los otros.

Output: Block con textura manufacturada + log entry (dosis, dirección declarada al fabricante, skill-status USED / CARRIED-FORWARD según §25 del C&C GS-01).
