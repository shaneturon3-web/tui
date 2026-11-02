# SKILL: mechanics-core-extractor
Version: 0.5.0 portable
Purpose: Extrae y formaliza mecanismos agnósticos separando Carrier (vehículo visible) de Mechanism (operación causal). Produce Mechanism Card reproducible.

Dependencies: ../dependencies/Mechanics_Library_Fórmulas_y_operadores_agnósticos.md — Sec 19 (tres niveles de evidencia), Sec 4-7, Sec 11, Sec 8-9.

Procedure:
1. Identify Surface (Carrier): ¿Qué vemos? Listar objetos, diálogos, lugares literales.
2. Observable Delta: INPUT → OPERATION → OBSERVED DELTA (Sec 42). No definir por intención. Ej: INPUT=mano cortada + linterna rodilla, OPERATION=sutura 5 puntos sin anestesia, OUTPUT=mano cerrada + riesgo infección.
3. Carrier vs Function Test (Sec 5,41): ¿Puedo cambiar carrier y conservar mecanismo? Si no, aún no aislé mecanismo.
4. Ablation (Sec 11): SYSTEM - X → ? Si comportamiento central permanece, X no es indispensable. Clasificar X como carrier/decoration/redundant.
5. Mechanism Card (Sec 43):
   TRIGGER: cuándo entra (condición observable)
   INPUT: qué necesita (material, energía, info, permiso)
   OPERATION: qué transforma (verbo físico)
   OUTPUT: qué produce (estado nuevo verificable)
   STOP: cuándo deja de aplicar (equilibrio, gasto, permiso)
   FAILURE MODE: cómo se corrompe (over-consumption, thermal rupture, etc.)
   NEGATIVE FIXTURE: casi-caso idéntico donde NO aplica (Sec 9)
   ROTATIONS: time, object, magnitude, scale, carrier, observer, entry (Sec 8)
6. Tropicalization Test (Sec 7): Cambiar environment, ¿misma OPERATION? Si cambia OPERATION, fue sustitución no tropicalización.

Output: YAML valid card + one-sentence mechanism name.
Receipt: Include source lines used.

Example from Cap07 (OBSERVED):
TRIGGER: Corte palma izq, sin luz 19:42, dispensario cerrado
INPUT: agua + sal, aguja curva, hilo negro, alicate limado, linterna rodilla, amoxi vet 500
OPERATION: sutura 5 puntos sin anestesia + dosis a ojo 75kg
OUTPUT: mano cerrada, registro "19:57 J.P. corte palma izq. 5 puntos sin anestesia amoxi vet 500"
STOP: Sangre pasa de hilo continuo a goteo lento, nudo cortado con dientes
FAILURE: Grasa negra contenedor → infección, amoxi vet vencimiento
NEGATIVE: Mismo corte pero en quirofano con lidocaína vigente y luz — mecanismo "sutura precaria con costo desigual" NO aplica, aplica "sutura estándar"
