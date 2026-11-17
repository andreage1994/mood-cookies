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
- **Identidad visual real, con moodboard propio (2026-11-17):** Andrea
  mandó el moodboard de Arrel — logo (wordmark con tratamiento de sello/
  máquina de escribir), paleta nueva (Almond Cream, Golden Chamomile,
  Mahogany Jam, Charcoal Grey — sustituye la de 6 colores del documento
  oficial), dirección fotográfica tipo "especimen botánico", packaging con
  fichas de producto numeradas (Nº + peso). Ver `identidad-visual/README.md`
  — sustituye la sección 09 de Fase B.
- **Dos preguntas nuevas sin cerrar (2026-11-17):** (1) si los sub-nombres
  del ecosistema (Mood Journal, Mood Moments, Mood Kitchen, Mood Goods,
  Mood Table Experiences) pierden "Mood" también o lo mantienen; (2) si
  "Cake de llimona i llavors de rosella" (aparece en una ficha de ejemplo
  del moodboard) es un producto real o solo un ejemplo de maquetación.
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

1. Que Andrea responda: estado del B2B, si los sub-nombres de ecosistema
   pierden "Mood", y si el "Cake de llimona" es producto real.
2. Que confirme o cambie el cuarto verbo propuesto ("Compartir").
3. Que confirme si quiere exactamente el efecto de tipografía de sello/
   máquina de escribir del moodboard, o si era solo dirección de mood —
   antes de que `arrel-diseno-identidad` elija fuentes reales de
   producción.
4. Con eso, `arrel-direccion-arte` desarrolla sistema de identidad
   concreto (logo, aplicaciones) sobre `identidad-visual/README.md`.
