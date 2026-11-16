# Estado del proyecto — Mood Table

**Flujo:** Concepto y Narrativa de Marca (misma lógica de fases que usa TBNB,
aplicada aquí a un proyecto propio de Andrea, no a un cliente).
**Última actualización:** 2026-11-16 (noche)

## Resumen

- Pivote de Mood Cookies (cookies funcionales, 4 "moods", rituales por QR) a
  **Mood Table** (obrador de creatividad gastronómica, dulce y salado,
  proximidad y temporada). Dos pasos de nombre el mismo día: Mood Cookies →
  Mood Baker → Mood Table. La idea de fondo (comer como conexión/momento, no
  como trámite) sobrevive a los dos pivotes.
- **Fase B tiene ya documento oficial** (`fase-b-plataforma-marca.md` v3):
  Andrea mandó `documentos-fuente/MOOD_TABLE_Identidad_de_Marca_v03.docx`,
  un documento estratégico completo (propósito, visión, misión,
  posicionamiento, público, valores, voz, tagline, identidad visual,
  arquitectura de producto, ecosistema de marca, manifiesto). Sustituye el
  borrador v1/v2 construido turno a turno en esta conversación. Quedan 6
  puntos de reconciliación sin cerrar por mi cuenta — ver
  `fase-b-plataforma-marca.md`, sección final "Reconciliación".
- Eslogan oficial: **"Conectar con lo que nos alimenta."** (En
  reconciliación: su relación con el tagline en inglés que Andrea dio antes
  del documento, "A little more connected to what we eat...".)
- La identidad visual ya tiene dirección (sección 09 del documento: paleta
  avena/verde oliva/terracota/avellana/salvia/vino, DM Serif Display + DM
  Sans, dirección fotográfica, packaging) — Fase C ya no arranca de cero.
- Este repositorio es nuevo (creado 2026-11-16) y está separado del repo de
  TBNB (`Agentes`) porque Mood Table no es un cliente de la consultoría.

## Fases

- [x] **Fase A · Investigación de mercado** — **hecha (2026-11-16)**, ver
      `fase-a-investigacion-mercado.md`. Investigó Vereda, Oz Bakery, Origo
      (referencias de Andrea) + 6 competidores más, con fuentes citadas.
      **Riesgo real detectado:** La Cantonada ya vende un croissant de
      calçots y romesco — mismo ingrediente/gesto que la tartaleta de Mood
      Table. El documento oficial de Fase B confirma mantener esa
      tartaleta sin nombrar el precedente — ver reconciliación nº6.
      Limitaciones declaradas: sin visita física, sin precios de carta
      oficiales de ningún competidor.
- [x] **Fase B · Plataforma de marca** — **v3, documento oficial**, ver
      `fase-b-plataforma-marca.md`. Resuelve prácticamente todo lo que
      estaba abierto en v1/v2 (Visión, valores, voz, tagline, arquitectura
      de catálogo, ecosistema de marca Mood Kitchen/Journal/Experiences/
      Goods). **6 puntos de reconciliación pendientes** antes de dar el
      GATE 2 por bueno — ver sección final de ese documento: tagline
      ES/EN, tarta de queso de cabra ausente de "la mesa de temporada",
      cambio de los 5 criterios (Proximity desaparece, Creatividad entra),
      "los cuatro verbos" solo lista tres, estado del B2B, y si se nombra
      el precedente de La Cantonada en la narrativa de calçots/romesco.
- [ ] **GATE 1 · ¿Es correcta esta lectura del mercado?** — pendiente de que
      Andrea confirme la Fase A (sobre todo: visita física pendiente).
- [ ] **GATE 2 · ¿Es esta la plataforma de marca que Andrea quiere?** —
      pendiente solo de las 6 reconciliaciones de Fase B.
- [~] **Fase C · Diseño del ecosistema** — pilar web en `web-copy-v1.md` →
      `v4` (voz corregida, separación marca/producto), **pendiente una v5**
      que alinee con el documento oficial de Fase B (nuevo eslogan, nueva
      arquitectura de ecosistema, voz ya con reglas explícitas). Identidad
      visual: dirección de arte ya no arranca de cero — la sección 09 del
      documento oficial de Fase B la da casi entera (paleta, tipografía,
      fotografía, packaging); falta solo que `mood-table-direccion-arte` la
      desarrolle en sistema de identidad concreto (logo, aplicaciones).

## Equipo de agentes

`.claude/agents/`: `mood-table-direccion-arte`, `mood-table-diseno-identidad`,
`mood-table-diseno-aplicado`, `mood-table-web`, `mood-table-revision-coherencia-marca`,
`mood-table-estrategia-marca`, `mood-table-direccion-creativa`, `mood-table-redaccion`.
**Nota técnica:** estos agentes no aparecen en la lista de "Available agent
types" del entorno de Claude Code cuando la sesión está anclada al repo de
TBNB — solo se pueden invocar por nombre cuando la sesión trabaja con este
repo como principal. Mientras tanto, se han ejecutado briefeando a
`general-purpose` con el contenido del rol copiado literalmente.

## Próximo paso

1. Que Andrea responda las 6 reconciliaciones de `fase-b-plataforma-marca.md`.
2. Con eso, reescribir el copy de la web (v5) alineado al documento oficial.
3. Arrancar `mood-table-direccion-arte` sobre la sección 09 ya dada
   (paleta, tipografía, fotografía) para llegar a sistema de identidad
   (logo concreto, aplicaciones).
