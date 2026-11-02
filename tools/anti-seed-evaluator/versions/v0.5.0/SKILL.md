# SKILL: anti-seed-evaluator
Version: 0.5.0 portable
Purpose: Evitar autoconfirmación sometiendo cada tesis favorita al caso que la derrota, antes de enamorarse de ella. Correr el sistema contra sí mismo.

Dependencies: Mechanics Library Sec 9 (MS-04 NEGATIVE FIXTURE), Sec 10 (MS-01 TOOL ROTATION), Sec 11 (ABLATION / INDISPENSABILITY), Sec 8 (DIENTES).

Procedure — para la tesis T, fabricar:
1. Mundo donde T falla — por física, por costo o por permiso. Si T no puede fallar en ningún mundo construible, T es tautología: CUT.
2. Mundo donde ¬T funciona mejor — el opuesto no solo sobrevive: prospera. Si ¬T prospera, T era preferencia, no necesidad.
3. Mundo donde T daña — a otra historia, a un personaje, al lector, a la corriente (dientes, Sec 8). Tesis que solo se evalúa en su propio jardín es invernadero.
4. Mundo donde T es irrelevante — no representado ≠ irrelevante, pero tampoco al revés: si nada cambia cuando T falta, T es decoración.
5. Mundo donde T y ¬T fallan — indica que la oposición es falsa y se necesita dimension lift (nueva variable independiente), no un ganador.
6. COMMON-MODE DETECTOR — ¿T y ¬T comparten una dependencia oculta? Ejemplo: ambos dependen de un dispensario abierto. Si sí, no es oposición real: es la misma tesis con dos sombreros. Nombrar la dependencia compartida.
7. NEGATIVE FIXTURE — producir el casi-caso idéntico donde el mecanismo NO debe aplicar. Si no puedes construirlo, el mecanismo explica demasiado: recortar su alcance hasta que el negativo exista.

Verdictos: KEEP (sobrevive los 7), ROTATE (sobrevive cambiando carrier/dominio), CUT (falla 1–5 sin recuperación). Todo veredicto lleva common-mode flag.

Tests:
- ¿El mundo 2 (¬T prospera) es honesto o es hombre de paja? Si ¬T está construido para perder, repetir.
- ¿El negative fixture es casi-idéntico o es otro caso? Casi-idéntico o no cuenta.

STOP: evaluar solo los mundos cómodos; declarar KEEP sin pasar por el 5; usar el evaluator para confirmar en vez de para derrotar.

Output: tabla de 7 mundos + veredicto + common-mode flag + negative fixture. Receipt: citar líneas de evidencia fuente (no basta "mundo 3 falla": decir dónde).
