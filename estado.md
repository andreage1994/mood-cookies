# Estado del proyecto — Arrel

**Flujo:** Concepto y Narrativa de Marca (misma lógica de fases que usa TBNB,
aplicada aquí a un proyecto propio de Andrea, no a un cliente).
**Última actualización:** 2026-11-17

## Resumen

- **Tres pivotes de nombre:** Mood Cookies (cookies funcionales, 4 "moods",
  rituales por QR) → Mood Baker (2026-11-16) → Mood Table (2026-11-16,
  mismo día) → **Arrel** (2026-11-17, confirmado tras brainstorming de
  equipo). "Arrel" ("raíz", catalán) corta el hilo de "Mood" a propósito —
  el concepto ya no gira en torno al estado de ánimo, gira en torno a
  origen/territorio.
- **Fase B tiene documento oficial, prácticamente cerrado**
  (`fase-b-plataforma-marca.md` v3, a partir de
  `documentos-fuente/MOOD_TABLE_Identidad_de_Marca_v03.docx`). El pivote de
  nombre a Arrel **no reabre estrategia** — propósito, visión, misión,
  valores, voz y tagline ("Conectar con lo que nos alimenta") siguen
  igual. Único punto real sin cerrar: el **B2B** ("Organiza una experiencia
  Mood").
- **Identidad visual, revisión de agencia (2026-11-17):** Andrea mandó un
  primer moodboard (logo sello/máquina de escribir, paleta fría tipo
  apotecario, fotografía "especimen botánico") y luego pidió "algo más
  pulido... cuestiona los colores también si hace falta". Convoqué
  dirección de diseño gráfico + dirección de estrategia de marca (dos
  informes independientes) — ambos llegaron, por caminos distintos, al
  mismo diagnóstico: la estética de especimen/laboratorio venía calcada de
  las referencias de perfumería y **reproducía el villano de la marca**
  (distancia/catalogación) en vez de resolverlo (calidez/mesa compartida).
  **Nueva dirección recomendada**, pendiente de confirmación de Andrea —
  ver `identidad-visual/README.md`: paleta nueva (Almond Cream, **Fig
  Jam**, **Toasted Wheat**, **Honey Gold**, **Warm Ink** — sustituye
  Mahogany Jam/Charcoal Grey), Fraunces limpio sin textura por defecto
  (el sello pasa a ser detalle físico de packaging, no digital), cuerpo de
  texto en **Lora** en vez de Courier Prime, fotografía en contexto de
  mesa en vez de ingrediente aislado. El moodboard original queda en el
  documento como historial, no como vigente.
- **Resuelto (2026-11-17):** las referencias de perfumería/skincare eran
  solo inspiración de tono, confirmado. "Cake de llimona i llavors de
  rosella" era solo ejemplo de maquetación, no producto real — confirmado,
  no se suma al catálogo.
- **Sigue sin cerrar:** si los sub-nombres del ecosistema (Mood Journal,
  Mood Moments, Mood Kitchen, Mood Goods, Mood Table Experiences) pierden
  "Mood" también o lo mantienen, y si Andrea confirma la nueva dirección
  de identidad visual o prefiere ajustarla.
- **`web-copy-v5.md`** ya renombrado a Arrel en el cambio masivo de hoy —
  sigue siendo el copy vigente de la web, con Hero reescrito (menos
  robótico) y "El problema" reescrito con StoryBrand real (ver
  `story-brand-arrel.md`).
- Este repositorio es nuevo (creado 2026-11-16) y está separado del repo de
  TBNB (`Agentes`) porque Arrel no es un cliente de la consultoría.

## Fases

- [x] **Fase A · Investigación de mercado** — **hecha**, ver
      `fase-a-investigacion-mercado.md`. Riesgo señalado (La Cantonada con
      un croissant de calçots y romesco) resuelto: la tartaleta se
      mantiene, no es pieza identitaria, es rotacional. Limitaciones
      declaradas: sin visita física, sin precios de carta oficiales.
- [x] **Fase B · Plataforma de marca** — **v3, documento oficial,
      prácticamente cerrado**, ver `fase-b-plataforma-marca.md`. Único
      punto real sin responder: estado del B2B. El pivote de nombre a
      Arrel no toca nada de esta fase salvo el nombre y la identidad
      visual.
- [ ] **GATE 1 · ¿Es correcta esta lectura del mercado?** — pendiente de que
      Andrea confirme la Fase A (visita física pendiente).
- [~] **GATE 2 · ¿Es esta la plataforma de marca que Andrea quiere?** —
      prácticamente sí; falta solo el B2B.
- [~] **Fase C · Diseño del ecosistema** — pilar web: `web-copy-v1.md` →
      `v5` (vigente, ya renombrado a Arrel). Identidad visual: ya no
      arranca de cero — `identidad-visual/README.md` da logo, paleta,
      dirección fotográfica y packaging reales del moodboard de Andrea;
      falta que `arrel-direccion-arte`/`arrel-diseno-identidad` lo
      desarrollen en sistema concreto (tipografías de producción sin
      confirmar todavía, ver pendiente en ese documento).

## Equipo de agentes

`.claude/agents/`: `arrel-direccion-arte`, `arrel-diseno-identidad`,
`arrel-diseno-aplicado`, `arrel-web`, `arrel-revision-coherencia-marca`,
`arrel-estrategia-marca`, `arrel-direccion-creativa`, `arrel-redaccion`.
**Nota técnica:** estos agentes no aparecen en la lista de "Available agent
types" del entorno de Claude Code cuando la sesión está anclada al repo de
TBNB — solo se pueden invocar por nombre cuando la sesión trabaja con este
repo como principal. Mientras tanto, se han ejecutado briefeando a
`general-purpose` con el contenido del rol copiado literalmente.

## Próximo paso

1. Que Andrea confirme o ajuste la nueva dirección de identidad visual
   (paleta Fig Jam/Toasted Wheat/Honey Gold/Warm Ink, Lora para cuerpo,
   fotografía de mesa en vez de especimen) — `identidad-visual/README.md`.
2. Que responda: estado del B2B, si los sub-nombres de ecosistema pierden
   "Mood", y si confirma o cambia el cuarto verbo propuesto ("Compartir").
3. Con eso, `arrel-direccion-arte`/`arrel-diseno-identidad` desarrollan
   sistema de identidad concreto (logo, aplicaciones).
