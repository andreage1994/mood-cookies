# Estado del proyecto — Mood Table

**Flujo:** Concepto y Narrativa de Marca (misma lógica de fases que usa TBNB,
aplicada aquí a un proyecto propio de Andrea, no a un cliente).
**Última actualización:** 2026-11-16 (noche)

## Resumen

- Pivote de Mood Cookies (cookies funcionales, 4 "moods", rituales por QR) a
  **Mood Table** (obrador de creatividad gastronómica, dulce y salado,
  proximidad y temporada). Dos pasos de nombre el mismo día: Mood Cookies →
  Mood Baker → Mood Table.
- **Fase B tiene documento oficial, prácticamente cerrado**
  (`fase-b-plataforma-marca.md` v3, a partir de
  `documentos-fuente/MOOD_TABLE_Identidad_de_Marca_v03.docx`). Las 6
  reconciliaciones iniciales están resueltas salvo una. Eslogan único:
  **"Conectar con lo que nos alimenta."**
- **Mood Moments, resuelto del todo:** vuelve, pero solo como eventos de
  comunidad (cenas en reflexión, yoga/pilates, talleres de belleza) — el
  QR/ritual por producto de Mood Cookies se elimina sin excepción. Se
  solapa con "Mood Table Experiences" (su cara gastronómica).
- **Único punto real sin cerrar de Fase B: el B2B** ("Organiza una
  experiencia Mood") — encaja de forma natural en Mood Moments pero no está
  confirmado.
- **`web-copy-v5.md` escrito**, alineado al documento oficial: eslogan
  único, manifiesto real en "Nuestra forma de ver el mundo", catálogo con
  la tarta de remolacha y las cookies como línea propia (3 sabores
  nuevos), "Cómo funciona" sin ningún paso pendiente, sección nueva de
  Mood Moments, y el test "¿qué momento necesitas hoy?" retirado (su
  premisa ya no existe). Propone fusionar Experiences+Moments en una sola
  sección de nav — a confirmar.
- La identidad visual ya tiene dirección (sección 09 del documento: paleta
  avena/verde oliva/terracota/avellana/salvia/vino, DM Serif Display + DM
  Sans, dirección fotográfica, packaging) — Fase C ya no arranca de cero.
- Este repositorio es nuevo (creado 2026-11-16) y está separado del repo de
  TBNB (`Agentes`) porque Mood Table no es un cliente de la consultoría.

## Fases

- [x] **Fase A · Investigación de mercado** — **hecha**, ver
      `fase-a-investigacion-mercado.md`. Riesgo señalado (La Cantonada con
      un croissant de calçots y romesco) resuelto: la tartaleta se
      mantiene, no es pieza identitaria, es rotacional. Limitaciones
      declaradas: sin visita física, sin precios de carta oficiales.
- [x] **Fase B · Plataforma de marca** — **v3, documento oficial,
      prácticamente cerrado**, ver `fase-b-plataforma-marca.md`. Único
      punto real sin responder: estado del B2B.
- [ ] **GATE 1 · ¿Es correcta esta lectura del mercado?** — pendiente de que
      Andrea confirme la Fase A (visita física pendiente).
- [~] **GATE 2 · ¿Es esta la plataforma de marca que Andrea quiere?** —
      prácticamente sí; falta solo el B2B.
- [~] **Fase C · Diseño del ecosistema** — pilar web:
      `web-copy-v1.md` → `v4` (voz corregida, separación marca/producto) →
      **`v5` (hoy): alineado al documento oficial completo**, ver resumen
      arriba. Pendiente de que Andrea lo revise. Identidad visual: la
      sección 09 del documento oficial ya da dirección de arte, paleta,
      tipografía y fotografía — falta que `mood-table-direccion-arte` la
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

1. Que Andrea revise `web-copy-v5.md` y responda el B2B.
2. Que confirme o cambie el cuarto verbo propuesto ("Compartir").
3. Arrancar `mood-table-direccion-arte` sobre la sección 09 ya dada
   (paleta, tipografía, fotografía) para llegar a sistema de identidad
   (logo concreto, aplicaciones).
