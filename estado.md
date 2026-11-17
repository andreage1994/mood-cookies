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
- **Identidad visual — sistema cerrado (2026-11-17), ver
  `identidad-visual/README.md` sección "Sistema vigente".** Pasó por 5
  rondas de corrección el mismo día: moodboard original de Andrea
  (estética sello/máquina de escribir + paleta fría tipo apotecario) →
  revisión de agencia (dirección de diseño gráfico + estrategia de marca,
  independientes, mismo diagnóstico: esa estética reproducía el villano
  de la marca en vez de resolverlo) → paleta de 5 colores rechazada por
  Andrea ("veo mucho color") → logo con Fraunces rechazado ("no me
  convence la tipografía") → formatos sin círculos, confirmados. Estado
  final: paleta Almond Cream + Warm Ink + Fig Jam (acento puntual); una
  sola familia de display, **Libre Caslon Display** (logo y titulares de
  web), + Lora (cuerpo); 4 formatos de logo sin círculos ni cajas
  (wordmark, monograma suelto, lockup vertical, sello puntual de esquina
  con la "A"); fotografía de mesa, no especimen aislado.
- **Resuelto (2026-11-17):** las referencias de perfumería/skincare eran
  solo inspiración de tono, confirmado. "Cake de llimona i llavors de
  rosella" era solo ejemplo de maquetación, no producto real — confirmado,
  no se suma al catálogo.
- **Resuelto (2026-11-17) — catálogo y ecosistema, del todo:** las
  cookies ya no son tercera línea — una (chocolate, avellana y sal
  marina) se suma a **Siempre**; las otras dos rotan dentro de
  **Rotacional**. Los ejemplos de qué producto va en cada estación
  (calabaza en otoño, calçots en invierno, etc.) eran solo para que yo
  entendiera el concepto — **no se publican en la web**, solo las 4
  estaciones como estructura. El catálogo pasa a tener **página propia**
  (`web/catalogo.html`), el Home solo lleva un teaser con enlace.
  Ecosistema: **todo pierde "Mood"** — Kitchen, Journal, La Mesa (fusión
  de Mood Moments + Mood Table Experiences), Goods. Cuarto verbo
  **Compartir, confirmado**.
- **Fase B queda cerrada salvo un único punto: el B2B** ("Organiza una
  experiencia Mood") — encaja en La Mesa, sin confirmar todavía.
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
      punto real sin responder en toda la fase: estado del B2B.
- [ ] **GATE 1 · ¿Es correcta esta lectura del mercado?** — pendiente de que
      Andrea confirme la Fase A (visita física pendiente).
- [~] **GATE 2 · ¿Es esta la plataforma de marca que Andrea quiere?** —
      prácticamente sí; falta solo el B2B.
- [~] **Fase C · Diseño del ecosistema** — pilar web: `web-copy-v1.md` →
      `v5` (vigente, ya renombrado a Arrel, pendiente de una pasada que
      aplique Libre Caslon Display/Lora en vez de las tipografías viejas
      de Fase B). Identidad visual: **sistema cerrado** —
      `identidad-visual/README.md` da logo, paleta, tipografía,
      dirección fotográfica y packaging ya confirmados; falta que
      `arrel-direccion-arte`/`arrel-diseno-identidad` lo desarrollen en
      arte final (archivos vectoriales, aplicaciones reales).

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

1. **Manual de marca publicado (2026-11-17):** reúne plataforma de marca +
   identidad visual completa en un solo documento —
   https://claude.ai/artifact/GgzGAs2i1RK76SkEsHwPnV (Design System de
   claude.ai; copia de trabajo en `manual-de-marca/manual-de-marca.md` y
   `tokens.json`). Es privado — hay que compartirlo desde el propio enlace
   si alguien más (ej. un diseñador externo) necesita abrirlo.
2. **Home + Repostería publicados (2026-11-17)** —
   https://claude.ai/artifact/Gbyciaj2i2xJsoUA3JHquZ (`web/home.html` +
   `web/catalogo.html`, dos páginas del mismo Artifact, enlazadas entre
   sí). El catálogo pasó a tener su propia página (pedido de Andrea), el
   Home ahora solo lleva un teaser con enlace. Corregido antes de publicar
   la primera versión: botones/pestañas en píldora que contradecían "sin
   círculos ni nada", ya en ángulo recto. Aplicadas las correcciones de
   catálogo (cookies repartidas Siempre/Rotacional, sin productos pinned
   por estación) y de nomenclatura (Journal, La Mesa).
   **2 dudas reales del diseñador, sin resolver:** (a) si "El problema"
   (bloque invertido) pesa visualmente más de lo que debería frente a
   "Nuestra mirada creativa"; (b) newsletter sin copy de marca todavía
   (solo rótulo funcional, no hay texto decidido en Fase B).
3. **Único punto de Fase B sin cerrar: el B2B.**
4. Antes de construir Journal y La Mesa como páginas propias (como ya
   pasó con Repostería): decidir si de verdad necesitan página propia ya,
   o si el teaser del Home basta por ahora.
5. Idioma de las fichas de producto (catalán/español/bilingüe) — abierto
   desde el moodboard, nunca respondido.
6. Fase A (GATE 1) sigue sin el visto bueno formal de Andrea — visita
   física pendiente.
