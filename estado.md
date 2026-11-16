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
- **Fase B tiene documento oficial, prácticamente cerrado** (
  `fase-b-plataforma-marca.md` v3, a partir de
  `documentos-fuente/MOOD_TABLE_Identidad_de_Marca_v03.docx`). De las 6
  reconciliaciones que señalé al recibirlo, Andrea resolvió 5 en el acto:
  eslogan (español sustituye al inglés), tarta de queso de cabra confirmada
  en invierno, 6 criterios de desarrollo (Creatividad nueva + Proximidad
  recuperada), cuarto verbo (propuse "Compartir", pendiente que lo
  confirme), calçots/romesco se mantiene sin narrativa especial. **Sigue
  abierto solo el B2B** ("Organiza una experiencia Mood").
- **Novedad importante, no pedida por mí — Mood Moments vuelve.** Andrea
  revirtió la resolución de esta misma tarde: el ritual desbloqueable por
  QR de Mood Cookies **sí** se mantiene, "de la misma forma que antes". Qué
  significa eso para un catálogo que ya no tiene 4 "moods" como taxonomía
  es una pregunta de diseño abierta — ver `fase-b-plataforma-marca.md`
  sección 12.
- Eslogan oficial, único: **"Conectar con lo que nos alimenta."**
- La identidad visual ya tiene dirección (sección 09 del documento: paleta
  avena/verde oliva/terracota/avellana/salvia/vino, DM Serif Display + DM
  Sans, dirección fotográfica, packaging) — Fase C ya no arranca de cero.
- Este repositorio es nuevo (creado 2026-11-16) y está separado del repo de
  TBNB (`Agentes`) porque Mood Table no es un cliente de la consultoría.

## Fases

- [x] **Fase A · Investigación de mercado** — **hecha (2026-11-16)**, ver
      `fase-a-investigacion-mercado.md`. Investigó Vereda, Oz Bakery, Origo
      (referencias de Andrea) + 6 competidores más, con fuentes citadas.
      Riesgo señalado (La Cantonada con un croissant de calçots y romesco)
      resuelto por Andrea: la tartaleta se mantiene, no es pieza
      identitaria de marca, es rotacional — no hace falta narrativa de
      diferenciación. Limitaciones declaradas: sin visita física, sin
      precios de carta oficiales de ningún competidor.
- [x] **Fase B · Plataforma de marca** — **v3, documento oficial,
      prácticamente cerrado**, ver `fase-b-plataforma-marca.md`. Único
      punto real sin responder: estado del B2B ("Organiza una experiencia
      Mood"). Punto nuevo a diseñar (no a decidir, Andrea ya confirmó que
      Mood Moments vuelve): cómo encaja el mecanismo de QR/ritual en un
      catálogo organizado por Siempre/Rotacional/Cookies en vez de por
      "mood".
- [ ] **GATE 1 · ¿Es correcta esta lectura del mercado?** — pendiente de que
      Andrea confirme la Fase A (sobre todo: visita física pendiente).
- [~] **GATE 2 · ¿Es esta la plataforma de marca que Andrea quiere?** —
      prácticamente sí; falta solo B2B y la forma concreta de Mood Moments.
- [~] **Fase C · Diseño del ecosistema** — pilar web en `web-copy-v1.md` →
      `v4` (voz corregida, separación marca/producto), **pendiente una v5**
      que alinee con el documento oficial de Fase B (eslogan único,
      catálogo de invierno actualizado, 6 criterios, cuarto verbo, nueva
      arquitectura de ecosistema Mood Kitchen/Journal/Experiences/Goods/
      Moments, voz con reglas explícitas, y el paso 3 de "Cómo funciona"
      que vuelve a tener contenido real aunque falte fijar su forma).
      Identidad visual: dirección de arte ya no arranca de cero — la
      sección 09 del documento oficial de Fase B la da casi entera
      (paleta, tipografía, fotografía, packaging); falta solo que
      `mood-table-direccion-arte` la desarrolle en sistema de identidad
      concreto (logo, aplicaciones).

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

1. Que Andrea responda B2B y la forma concreta de Mood Moments (único
   diseño real pendiente de Fase B).
2. Reescribir el copy de la web (v5) alineado al documento oficial —
   puedo arrancarlo ya con lo que hay, dejando Mood Moments como la única
   pieza a falta de forma final.
3. Arrancar `mood-table-direccion-arte` sobre la sección 09 ya dada
   (paleta, tipografía, fotografía) para llegar a sistema de identidad
   (logo concreto, aplicaciones).
