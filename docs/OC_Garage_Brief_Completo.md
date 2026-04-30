# OC Garage — Brief Completo del Proyecto
**Fecha de creación:** Abril 2026  
**Propietario:** Dex (agencia) para Claudio (cliente)  
**Estado:** En desarrollo — landing lista, logo y fotos pendientes

---

## 1. Datos del Negocio

| Campo | Valor |
|---|---|
| Nombre | OC Garage |
| Propietario | Claudio Orallo |
| Rubro | Taller de chapa y pintura automotriz |
| Ciudad | Mar del Plata, Buenos Aires, Argentina |
| Dominio | ocgaragemdq.com |
| Email | ⚠️ PENDIENTE — irá con el dominio (ej: claudio@ocgaragemdq.com) |
| Instagram | ⚠️ PENDIENTE — confirmar @ |
| Teléfono | +54 9 2236 85-6543 |
| Dirección | ⚠️ PENDIENTE — completar con dirección real |

### Público objetivo (doble mercado)

**Aseguradoras y sector asegurador (prioritario)**
Claudio tiene una trayectoria sólida trabajando con compañías de seguros. Este es el canal principal y debe estar al frente del posicionamiento. Peritos, responsables de siniestros y liquidadores son la audiencia clave.

**Clientes particulares (secundario)**
Particulares que buscan calidad, prolijidad y un taller de confianza en Mar del Plata.

### Contexto de lanzamiento
El taller aún no está operando de forma formal/pública. El objetivo de la web y la identidad es preparar la presencia digital antes del lanzamiento oficial. Por eso hay datos placeholder que deben actualizarse antes de publicar.

---

## 2. Identidad de Marca

### Posicionamiento
> "Taller de referencia en chapa y pintura para el sector asegurador y particulares en Mar del Plata."

**Tagline:** *Calidad técnica que respalda cada trabajo*  
(El tagline original propuesto "El más prolijo de la ciudad" quedó descartado por ser demasiado informal para el posicionamiento con aseguradoras.)

### Valores de marca
- Precisión
- Confianza
- Calidad
- Oficio

### Voz de marca
**Prolijo. Confiable. Experto.** Tono profesional, directo, sin vueltas. No es un taller de barrio — es un operador del sector. El copy debe sonar a alguien que conoce el lenguaje de las aseguradoras y habla de igual a igual con un perito.

### Paleta de colores (3 variantes — elegida: V1 Rojo)

| Token | Color | Hex |
|---|---|---|
| Negro base | ██ | `#0C0C0C` |
| Dark 1 | ██ | `#141414` |
| Dark 2 | ██ | `#1E1E1E` |
| Dark 3 | ██ | `#2A2A2A` |
| Gris medio | ██ | `#7A7A7A` |
| Blanco/Claro | ██ | `#EFEFEF` |
| **Acento V1 — Rojo ✅** | ██ | `#C01820` |
| Acento V2 — Naranja | ██ | `#D95B00` |
| Acento V3 — Dorado | ██ | `#C48B0A` |

**Regla de color:** 60% negro · 30% acento · 10% blanco  
**Variante elegida para la landing:** V1 Rojo (`#C01820`)

### Tipografía

| Rol | Familia | Peso |
|---|---|---|
| Display / Títulos | Big Shoulders Display | 700 Bold · 900 Black |
| Cuerpo / UI | Work Sans | 400 Regular · 500 Medium · 600 SemiBold |

Ambas disponibles en Google Fonts (gratis, sin licencia).

---

## 3. Brand Kits (PDF)

Se generaron 3 brand kits completos, uno por variante de color. Cada PDF tiene 2 páginas:
- Página 1: lockup del logo (placeholder), paleta de 5 colores y muestra tipográfica.
- Página 2: tarjeta de presentación anverso/reverso, logo sobre los 3 fondos, regla de uso 60/30/10, voz de marca y patrón diagonal para usar como textura en redes.

**Archivos en la carpeta del proyecto:**
- `OC_Garage_Brandkit_V1_Rojo.pdf` ← versión principal
- `OC_Garage_Brandkit_V2_Naranja.pdf`
- `OC_Garage_Brandkit_V3_Dorado.pdf`

---

## 4. Logo — Prompts para Generación

Aún no hay logo definitivo. Se intentó generarlo con Claude Design + Canva con resultados parciales. Los siguientes prompts están listos para usar en **Midjourney** (`--ar 1:1 --style raw --v 6.1`) o **DALL-E 3**.

### V1 — Rojo (variante principal)
```
Vector logo design for "OC GARAGE" auto body and paint shop. Bold condensed 
sans-serif wordmark, "OC" large and dominant above "GARAGE" in smaller text. 
Minimal geometric icon: abstract spray gun silhouette or diamond shield badge. 
Black and deep crimson red color scheme (#C01820). Americana industrial aesthetic, 
garage culture vibe similar to Gas Monkey Garage but professional and clean — 
NOT biker/motorcycle culture. High contrast, timeless, works at small sizes. 
White background. Vector quality, isolated. No gradients.
```

### V2 — Naranja
```
Logo mark for "OC GARAGE" professional auto body shop. Vintage americana workshop 
style. Bold industrial typography — "OC" as dominant monogram, "GARAGE" set below 
in tight condensed lettering. Simple icon element: stylized paint drop, star burst 
or angled chevron. Color palette: near-black (#0C0C0C) and burnt orange (#D95B00). 
Craftsmanship feel, not edgy. No motorcycles. Works as horizontal lockup and 
badge/emblem. Isolated on white. Clean vector illustration, strong silhouette.
```

### V3 — Dorado
```
Brand logo for "OC GARAGE" auto bodywork and painting workshop, Mar del Plata 
Argentina. Strong geometric design. "OC" oversized bold condensed letterforms, 
"GARAGE" beneath. Optional icon: mechanical gear segment, wrench negative space, 
or angular shield. Color scheme: charcoal black and golden amber (#C48B0A). 
Serious, trustworthy, skilled-trades aesthetic. Inspired by American workshop 
culture, NOT motorcycle brand. Timeless badge design. Isolated on white, 
vector quality, high contrast.
```

**Nota:** Una vez generado el logo, vectorizarlo en Illustrator o Vectornator. El logo placeholder en la landing actual es solo el texto "OC" en un cuadrado rojo.

---

## 5. Landing Page

### Archivo
`index.html` — en la carpeta del proyecto. Un solo archivo, todo autocontenido (HTML + CSS + JS).

### URL
`https://ocgaragemdq.com/`

### Stack técnico
- HTML5 semántico (sin frameworks)
- CSS custom con variables (sin Tailwind ni Bootstrap)
- **GSAP 3.12.5** + **ScrollTrigger** para todas las animaciones
- Google Fonts: Big Shoulders Display + Work Sans
- Sin dependencias de backend — página completamente estática

### SEO implementado
- `<title>` optimizado para búsqueda local
- Meta description con keywords de intención de búsqueda
- Keywords: `chapa y pintura aseguradoras Mar del Plata`, `taller autorizado aseguradoras MDP`, `perito aseguradora Mar del Plata`
- Open Graph completo (Facebook/WhatsApp)
- Twitter Card
- Schema.org `AutoBodyShop` con servicios, dirección y área de cobertura
- `<link rel="canonical">`
- `lang="es-AR"`, robots `index, follow`

### Estructura de secciones

**Navbar fija**
- Logo (marca "OC" + "Garage / Chapa · Pintura · MDP")
- Link a Instagram `@ocgarage.mdp`
- CTA "Presupuesto" → WhatsApp (rojo)
- Glassmorphism al hacer scroll

**Hero**
- Eyebrow: *"Aseguradoras · Particulares · Mar del Plata"*
- Título principal: *"Excelencia en chapa y pintura"* (Big Shoulders Display, ~120px, blanco + rojo)
- Subtítulo: *"Taller de referencia para aseguradoras y clientes particulares en Mar del Plata. Más de una década de trayectoria, calidad técnica comprobada y plazos que se cumplen."*
- CTAs: [Pedir presupuesto → WhatsApp] [Llamar al taller → tel:]
- Stats animados (contador en scroll):
  - 10+ años de trayectoria profesional
  - 500+ siniestros reparados
  - 15+ aseguradoras con las que trabajamos
- Fondo: grid decorativo, glow rojo, watermark "OC", línea diagonal roja

**Ticker de valores** (banda roja ancho completo, animación infinita)  
Precisión · Confianza · Calidad · Oficio · Mar del Plata · Taller de Referencia · Aseguradoras & Particulares

**Servicios** (3 cards)
1. **Chapa** — Reparación de abolladuras (PDR), enderezado de carrocería, soldadura y reemplazo de paneles, preparación de superficie.
2. **Pintura** — Pintura de piezas y sectores, pintura completa, igualación de color computerizada, pulido y abrillantado.
3. **Peritaje y Siniestros** — Atención de siniestros con aseguradoras, presupuestos técnicos para peritos, documentación fotográfica del proceso, garantía en materiales y mano de obra.

**El proceso** (4 pasos horizontales)
1. Diagnóstico — Revisión sin compromiso, evaluación del daño, explicación clara.
2. Presupuesto — Claro y detallado, sin letras chicas. Precio acordado = precio final.
3. Trabajo — Chapa, preparación y pintura bajo los más altos estándares.
4. Entrega — En el plazo prometido, revisión final y garantía.

**CTA Final**
- Título: *"Pedí tu presupuesto"*
- Copy: *"Aseguradoras, peritos y clientes particulares: trabajamos con seriedad, documentación y tiempos reales."*
- Botones: [WhatsApp] [Llamar]

**Footer** (3 columnas)
- Columna 1: Logo + descripción del taller
- Columna 2: Servicios (links internos)
- Columna 3: Contacto (dirección, teléfono, Instagram, dominio)

### Efectos y animaciones (GSAP)

| Elemento | Animación |
|---|---|
| Hero H1 | Text reveal con clip (`yPercent: 110`), stagger por línea |
| Eyebrow hero | Fade + slide desde izquierda |
| Stats | Fade + slide al entrar en viewport |
| Contador de stats | Animación numérica de 0 al valor objetivo |
| Ticker de valores | Scroll infinito de izquierda a derecha |
| Sección títulos | Text reveal con ScrollTrigger |
| Cards de servicios | Stagger fade+slide al entrar en viewport |
| Pasos del proceso | Stagger fade+slide |
| Footer | Fade al entrar en viewport |
| Hero glow + watermark | Parallax scrub al hacer scroll |
| Cursor | Custom cursor: dot rojo + ring que se expande en interactivos |
| Progreso de scroll | Barra roja fija en top de página |
| Navbar | Glassmorphism al hacer scroll (backdrop-filter) |
| WhatsApp FAB | Entrada animada con spring (delay 1.4s) |

**Nota:** Todas las animaciones respetan `prefers-reduced-motion`. Si el usuario tiene reducción de movimiento activada, todo se muestra directamente sin animaciones.

### Responsive
- `900px`: layout hero pasa a 1 columna, stats en fila, cards en 1 columna, footer en 1 columna
- `600px`: tipografía reducida, botón de la navbar oculto, pasos en 1 columna

### Datos placeholder a reemplazar antes del lanzamiento
- ~~**Teléfono:** placeholder reemplazado~~ ✅ `+54 9 2236 85-6543` ya cargado en toda la landing
- **Dirección:** Completar la dirección real en footer y Schema.org
- **Imagen OG:** Subir imagen real a `https://ocgaragemdq.com/og-image.jpg`
- **Aseguradoras:** Agregar logos o lista de aseguradoras reales (potencial sección de confianza)

---

## 6. Formulario de Onboarding del Cliente

Este fue el cuestionario usado para relevar la información del proyecto con Claudio. Puede reutilizarse para proyectos similares.

### Información del negocio
- ¿Cuál es el nombre exacto del taller?
- ¿Quién es el propietario / responsable?
- ¿Cuál es la dirección física?
- ¿Tienen teléfono de contacto? ¿WhatsApp o línea fija?
- ¿Tienen Instagram, Facebook u otras redes? ¿Cuál es el @?
- ¿Ya tienen dominio registrado? ¿Cuál?

### Servicios
- ¿Qué servicios ofrecen exactamente? (Listado detallado)
- ¿Tienen algún servicio diferencial que los distinga de la competencia?
- ¿Trabajan con aseguradoras? ¿Con cuáles? ¿Cuántos siniestros hacen por mes aprox.?
- ¿Trabajan con peritos directamente?

### Experiencia y credenciales
- ¿Cuántos años lleva el propietario en el rubro?
- ¿Tienen alguna certificación o habilitación municipal?
- ¿Tienen fotos de trabajos anteriores? ¿Antes/después?
- ¿Tienen testimonios o reseñas de clientes?

### Público y posicionamiento
- ¿A quién le quieren vender principalmente? (Aseguradoras, particulares, flotas, etc.)
- ¿Cuáles son sus clientes ideales?
- ¿Cómo consiguen clientes hoy?
- ¿Qué dicen sus clientes que valoran de ellos?

### Identidad visual
- ¿Tienen logo actual? ¿Les gusta o quieren cambiarlo?
- ¿Tienen colores de marca o preferencias visuales?
- ¿Hay algún estilo visual que admiren o que quieran evitar?
- ¿Palabras con las que quieren que asocien el taller?

### Objetivos del proyecto web
- ¿Qué quieren que haga la web? (Generar consultas, mostrar trabajos, aparecer en Google, etc.)
- ¿Tienen presupuesto para publicidad (Google Ads / Meta)?
- ¿Quién va a mantener la web después del lanzamiento?
- ¿Cuándo quieren lanzar?

---

## 7. Pendientes y Próximos Pasos

### Urgente (antes de publicar)
- [ ] Confirmar número de teléfono real y reemplazar placeholder en `index.html`
- [ ] Confirmar dirección física del taller
- [ ] Crear imagen OG (`og-image.jpg`, 1200×630px) — foto del taller o car wrap
- [ ] Subir el sitio al hosting en `ocgaragemdq.com`

### Mejoras recomendadas (post-lanzamiento)
- [ ] **Galería de trabajos** — sección antes/después con fotos reales. Impacto brutal para la conversión.
- [ ] **Sección de aseguradoras** — logos o lista de las compañías con las que trabajan. Señal de confianza decisiva para nuevas aseguradoras.
- [ ] **Logo final** — usar los prompts de la sección 4 en Midjourney/DALL-E 3 y reemplazar el placeholder "OC" del navbar.
- [ ] **Google Business Profile** — alta en Google Maps con dirección, teléfono, horarios y fotos. Fundamental para SEO local.
- [ ] **Reseñas de Google** — pedirle a los primeros clientes que dejen una reseña.
- [ ] **WhatsApp Business** — activar perfil de empresa con horario y respuesta automática.
- [ ] **Instagram activo** — publicar al menos 3-4 posts antes del lanzamiento (`@ocgarage.mdp`).

### Ideas adicionales identificadas en el proceso
- Sección de "Aseguradoras con las que trabajamos" — puede hacerse con logos en escala de grises (elegante y profesional)
- CTA alternativo: formulario de contacto embebido para cotización con campos: nombre, vehículo, tipo de daño, aseguradora (sí/no)
- Sección de FAQs para aseguradoras (¿Hacen presupuestos sin compromiso? ¿Coordinan con el perito? ¿Cuáles son los plazos?)
- Video corto del proceso de trabajo (reel para Instagram + embed en la web)

---

## 8. Archivos del Proyecto

| Archivo | Descripción |
|---|---|
| `index.html` | Landing page completa (HTML+CSS+JS, una sola página) |
| `OC_Garage_Brandkit_V1_Rojo.pdf` | Brand kit versión roja (principal) |
| `OC_Garage_Brandkit_V2_Naranja.pdf` | Brand kit versión naranja |
| `OC_Garage_Brandkit_V3_Dorado.pdf` | Brand kit versión dorada |
| `ideas logo/` | Carpeta con intentos y referencias de logo |
| `OC_Garage_Brief_Completo.md` | Este documento |

---

## 9. Notas de Producción

- La landing fue iterada en dos rondas principales: primero con foco en clientes particulares ("el más prolijo de la ciudad"), luego reposicionada para el sector asegurador a pedido del cliente.
- El código CSS usa custom properties (`--c-red`, `--f-disp`, etc.) que hacen trivial cambiar el color de acento si el cliente finalmente elige la versión naranja o dorada.
- GSAP se carga desde CDN (Cloudflare). Si en el futuro el sitio crece, conviene instalarlo vía npm.
- El sitio no tiene ninguna dependencia de backend, base de datos ni CMS. Hosting estático (Netlify, Vercel, o hosting compartido) es suficiente.
- El Schema.org `AutoBodyShop` está configurado para aparecer como rich result en Google Search cuando alguien busca el taller por nombre.

---

*Brief generado en Cowork · Abril 2026 · ocgaragemdq.com*
