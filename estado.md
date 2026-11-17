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
- **Sigue sin cerrar:** si los sub-nombres del ecosistema (Mood Journal,
  Mood Moments, Mood Kitchen, Mood Goods, Mood Table Experiences) pierden
  "Mood" también o lo mantienen.
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
2. **Home publicado (2026-11-17)** —
   https://claude.ai/artifact/Gbyciaj2i2xJsoUA3JHquZ (también en
   `web/home.html`). HTML/CSS real, con Libre Caslon Display + Lora +
   Special Elite cargadas, los 3 colores del sistema, copy literal de
   `web-copy-v5.md`, y distinción visual entre Siempre/Rotacional/Cookies.
   Corregido antes de publicar: usaba botones y pestañas en píldora
   (`border-radius: 999px`), contradecía "sin círculos ni nada" — ya en
   ángulo recto. **3 dudas reales del diseñador, sin resolver:** (a) si el
   catálogo vive entero en el Home o pasa a tener página propia; (b) si
   "El problema" (bloque invertido) pesa visualmente más de lo que debería
   frente a "Nuestra mirada creativa"; (c) newsletter sin copy de marca
   todavía (solo rótulo funcional, no hay texto decidido en Fase B).
3. Que Andrea responda: estado del B2B, si los sub-nombres de ecosistema
   pierden "Mood", y si confirma o cambia el cuarto verbo propuesto
   ("Compartir") — los tres únicos puntos de Fase B que siguen abiertos.
