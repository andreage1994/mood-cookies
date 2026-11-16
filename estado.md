# Estado del proyecto — Mood Table

**Flujo:** Concepto y Narrativa de Marca (misma lógica de fases que usa TBNB,
aplicada aquí a un proyecto propio de Andrea, no a un cliente).
**Última actualización:** 2026-11-16

## Resumen

- Pivote de Mood Cookies (cookies funcionales, 4 "moods", rituales por QR) a
  **Mood Table** (repostería creativa de proximidad y temporada). El pivote
  es de categoría de producto — la idea de fondo (comer como ritual/momento,
  no como trámite) sobrevive y aquí se llama **Ritualizar**, resuelta ya
  como speech de marca, no como mecánica de QR.
- Nombre de marca: **Mood Table** (segundo pivote de nombre el mismo día,
  2026-11-16 — antes fue Mood Baker). Nuevo tagline: "A little more
  connected to what we eat, where it comes from and the moments we share
  around it." Sin conflictos encontrados en búsqueda (Barcelona ni general);
  "Table" además cierra, en vez de dejar abierta, la pregunta de lectura
  persona/categoría que tenía "Baker" — ver `fase-b-plataforma-marca.md`
  sección 0.
- Voz editorial corregida dos veces (2026-11-16): no es wellness (Mood
  Cookies), tampoco es oficio/técnica puro — es la reflexión de
  recibir/agradecer/compartir/cuidar/conectar del brief original. Ver
  `direccion-editorial-voz.md` v2 y `web-copy-v3.md`.
- Categoría corregida (2026-11-16): Mood Table es **obrador**, no
  "pastelería de autor" — la Fase A original lo categorizaba junto a
  Benévola/La Cantonada (técnica, montajes, cremas). Andrea lo corrigió:
  rústico, reconocible a simple vista, con 5 referencias visuales guardadas
  en `referencias-visuales/`. De paso, precisó origen de producto: avellanas
  **de Reus**, nueces **de Tarragona** (antes "de proximidad" en genérico).
  Ver `fase-a-investigacion-mercado.md` (corrección al inicio) y
  `fase-b-plataforma-marca.md` sección 0 y 7.
- Este repositorio es nuevo (creado 2026-11-16) y está separado del repo de
  TBNB (`Agentes`) porque Mood Table no es un cliente de la consultoría.

## Fases

- [x] **Fase A · Investigación de mercado** — **hecha (2026-11-16)**, ver
      `fase-a-investigacion-mercado.md`. Investigó Vereda, Oz Bakery, Origo
      (referencias de Andrea) + 6 competidores más, con fuentes citadas.
      Hallazgo clave: el mercado empuja hacia la dirección C de Visión
      (sorpresa reconocible dulce+salado con discurso de Ritualizar) — A y B
      tienen más competencia de la esperada. **Riesgo real detectado:** La
      Cantonada ya vende un croissant de calçots y romesco — mismo
      ingrediente/gesto que la tartaleta propuesta en Fase B sección 7b.
      Limitaciones declaradas: sin visita física, sin precios de carta
      oficiales de ningún competidor.
- [~] **Fase B · Plataforma de marca** — **v2, en construcción activa**, ver
      `fase-b-plataforma-marca.md`. Resuelto hoy: Ritualizar (speech, no
      mecánica), valores de alimento (temporada/proximidad/whole foods, no
      plant-based/sin gluten), patrón de Identity (ingrediente conocido +
      sorpresa, no cruce dulce-salado), por qué existen Siempre y Rotacional,
      mantra v2, categoría (obrador), nombre (Mood Table), tarta de queso de
      cabra y remolacha confirmada en Rotacional de invierno. **Sigue
      abierto:** Visión (3 direcciones propuestas, C respaldada por la Fase
      A), confirmación final del mantra, si cookies entra en "Siempre", test
      de la tienda, Experiencias Mood/B2B en persona.
      **Pendiente de recibir (2026-11-16): Andrea va a mandar un documento
      con todo mejor estructurado.** Cuando llegue, lo reconcilio contra este
      documento y señalo cualquier conflicto en vez de sobrescribir en
      silencio — no asumo que cierra los abiertos de arriba hasta verlo.
- [ ] **GATE 1 · ¿Es correcta esta lectura del mercado?** — pendiente de que
      Andrea confirme la Fase A (sobre todo: visita física pendiente, y si
      mantiene la tartaleta de calçots/romesco sabiendo del precedente de
      La Cantonada).
- [ ] **GATE 2 · ¿Es esta la plataforma de marca que Andrea quiere?** — pendiente.
- [~] **Fase C · Diseño del ecosistema** — arrancada parcialmente en el pilar
      web: `web-copy-v1.md` → `v2` (giro de voz-de-oficio, insuficiente) →
      `v3` (voz corregida, recibir/compartir/cuidar) → `v4` (2026-11-16:
      separa marca de producto — las secciones de marca ("Por qué Mood
      Table", pilar "Ingredientes con origen") ya no nombran ingrediente
      concreto; eso es solo del Catálogo. Añade sección pública nueva
      "Principios" con los 5 criterios de receta). Renombrado a Mood Table
      en todo el repo (2026-11-16, segundo pivote de nombre) — v1-v4 ya
      dicen "Mood Table"; **pendiente real:** ninguna versión integra
      todavía el tagline nuevo ("A little more connected to...") en el
      Hero, solo lo tiene Fase B (sección 1, Propósito). Identidad visual
      (dirección de arte → sistema de identidad → diseño aplicado) no
      arrancada todavía.

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

1. Que Andrea elija/mezcle una dirección de Visión (la C viene respaldada
   por la Fase A) y confirme o reescriba el mantra v2.
2. Que confirme si mantiene la tartaleta de calçots/romesco sabiendo del
   precedente de La Cantonada.
3. Que revise `web-copy-v3.md` y diga si la voz ya es la correcta.
4. Con eso, arrancar identidad visual (dirección de arte primero).
