Eres un desarrollador web frontend experto en landing pages de alta conversión. Necesito que crees una landing page completa tipo "página puente" (pre-sell page) para promocionar un curso online de accesorios en resina. La landing page se alojará en GitHub Pages.

## OBJETIVO

La página NO vende directamente. Su función es calentar al visitante, generar deseo y curiosidad, y derivarlo al enlace de afiliado donde se realiza la compra.

## ENLACE DE AFILIADO (todos los botones CTA apuntan aquí)

https://hotm.io/ZBCgFAu

## STACK TÉCNICO

- HTML5 + CSS3 puro (sin frameworks ni librerías)
- CSS Grid + Flexbox para layout responsive
- Mobile-first con breakpoints en 768px (tablet) y 1024px+ (desktop)
- Variables CSS para paleta de colores
- Google Fonts: "Playfair Display" (títulos) + "Inter" (cuerpo)
- Animaciones sutiles con CSS (fade-in al hacer scroll usando IntersectionObserver con vanilla JS mínimo)
- Scroll suave (smooth scroll)
- Las imágenes se enlazan directamente desde la web original del curso (no se descargan localmente)
- Todos los enlaces externos se abren con target="\_blank" rel="noopener"

## PALETA DE COLORES

- Primario (botones/acentos): #D4467E (rosa intenso)
- Secundario: #F5A623 (dorado)
- Fondo claro: #FFF9F5 (crema cálido)
- Texto principal: #2D2D2D (gris oscuro)
- Texto secundario: #6B6B6B
- Blanco: #FFFFFF

## ESTRUCTURA DE ARCHIVOS

/
├── index.html
├── css/
│ └── styles.css

## ESTRUCTURA DE LA PÁGINA (de arriba a abajo)

### 1. HEADER (Navegación Fija Sticky)

- Logo textual: "✨ Resina Creativa"
- Un único botón en el header: "Quiero Empezar" → enlace de afiliado
- Sticky al hacer scroll, fondo semitransparente con backdrop-filter blur
- Compacto, limpio

### 2. HERO SECTION

- Fondo con gradiente diagonal (rosa suave → dorado claro)
- Badge superior: "🔥 50% de descuento — Solo por hoy"
- Titular principal (h1): "Convierte la Resina en Tu Negocio Desde Casa"
  - La palabra "Resina" con efecto gradiente de texto (rosa a dorado)
- Subtítulo: "Aprende paso a paso a crear accesorios únicos y véndelos por redes sociales. Sin experiencia previa. En solo 30 días."
- Botón CTA grande: "Quiero Acceder al Curso con 50% OFF" → enlace de afiliado
- Imagen hero al costado derecho (en desktop, dos columnas; en mobile, imagen debajo del texto): usar la imagen principal del curso desde https://academiadigitaldye.com/accesorios-de-resina-para-emprender/

### 3. SECCIÓN "¿TE IDENTIFICAS?" (El Problema)

- Título de sección: "¿Te identificas con esto?"
- 4 cards con emojis como iconos y texto:
  - 💡 "Quieres emprender pero no sabes por dónde empezar"
  - 🏠 "Buscas algo creativo que puedas hacer desde casa"
  - 💰 "Necesitas un negocio con baja inversión y alta ganancia"
  - 🌱 "No tienes experiencia pero tienes muchas ganas de aprender"
- Grid: 1 columna en mobile, 2 en tablet, 4 en desktop
- Cierre emocional debajo: "Si dijiste SÍ a al menos una… este curso fue creado para ti."
- Cada card con fondo blanco, border-radius, sombra suave

### 4. SECCIÓN "LA SOLUCIÓN" (Qué es el Curso)

- Título: "Un Programa Completo Para Emprender con Resina"
- Párrafo descriptivo: "Un curso 100% online y en video donde aprenderás desde cero a elaborar más de 12 tipos de accesorios en resina, con técnicas profesionales, paso a paso y a tu propio ritmo. Diseñado especialmente para mujeres que quieren crear su propio negocio desde casa."
- 3 cifras destacadas en tarjetas/cajas grandes centradas:
  - "+85 Clases"
  - "+12 Horas de Video"
  - "+12 Proyectos"
- Texto inferior: "Acceso de por vida · Desde cualquier dispositivo · Sin experiencia previa"

### 5. SECCIÓN "PROYECTOS QUE APRENDERÁS" (Galería Visual)

- Título: "Mira Todo lo que Aprenderás a Crear"
- Grid responsive de cards con imagen + nombre del proyecto
- Usa las imágenes directamente de la web original del curso. Los proyectos son:
  1. Llaveros — https://academiadigitaldye.com/wp-content/uploads/2023/10/LLAVEROS-1.png
  2. Placas para mascotas — https://academiadigitaldye.com/wp-content/uploads/2023/10/PLACAS-PARA-MASCOTAS.png
  3. Posavasos — https://academiadigitaldye.com/wp-content/uploads/2023/10/POSA-VASOS.png
  4. Bandejas — https://academiadigitaldye.com/wp-content/uploads/2023/10/BANDEJAS.png
  5. Aretes y collares — https://academiadigitaldye.com/wp-content/uploads/2023/10/ARETES-Y-COLLARES.png
  6. Cofres — https://academiadigitaldye.com/wp-content/uploads/2023/10/COFRE.png
  7. Organizadores de maquillaje — https://academiadigitaldye.com/wp-content/uploads/2023/10/MAKE-UP-MOSTRADORES.png
  8. Marca páginas — https://academiadigitaldye.com/wp-content/uploads/2023/10/MARCA-PAGINAS.png
  9. Pirámides — https://academiadigitaldye.com/wp-content/uploads/2023/10/PIRAMIDE.png
  10. Cuadernos — https://academiadigitaldye.com/wp-content/uploads/2023/10/CUADERNOS.png
  11. Lapiceros — https://academiadigitaldye.com/wp-content/uploads/2023/10/LAPICEROS.png
  12. Ceniceros — https://academiadigitaldye.com/wp-content/uploads/2023/10/CENICERO.png
- Grid: 2 columnas en mobile, 3 en tablet, 4 en desktop
- Cada card: imagen con object-fit cover, border-radius, sombra, nombre del proyecto debajo
- Efecto hover: leve zoom en la imagen + sombra más pronunciada

### 6. SECCIÓN "BONOS INCLUIDOS" (Valor Agregado)

- Título: "Y Además Recibirás Estos Bonos GRATIS"
- Cards con los bonos. Cada card tiene emoji/icono, título del bono, y valor tachado:
  1. 🎨 "Personaliza tus piezas en resina" — Valor: $25
  2. 🌸 "Cómo secar flores naturales" — Valor: $25
  3. 💎 "Cómo encapsular recuerdos especiales" — Valor: $25
  4. 🎭 "Sombras de ojos como pigmento" — Valor: $25
  5. 🎄 "Figuras navideñas en resina" — Valor: $25
  6. 📦 "Módulo: Crea la marca de tu negocio" — GRATIS
  7. 🏅 "Certificado personalizado con tu nombre" — Incluido
- Debajo un texto destacado: "Más de $125 en bonos totalmente GRATIS con tu inscripción hoy"
- Grid: 1 columna en mobile, 2 en tablet, 3 en desktop

### 7. SECCIÓN PRECIO + CTA FINAL (Cierre de Venta)

- Fondo con gradiente (similar al hero pero más intenso)
- Texto superior: "¿Cuánto vale para ti aprender todo esto?"
- Precio tachado grande: "$60 USD" (con línea tachada)
- Precio real grande y destacado: "$30 USD"
- Badge: "50% DE DESCUENTO — SOLO POR HOY"
- Botón CTA muy grande y llamativo con efecto pulse/glow: "¡SÍ, QUIERO EMPEZAR HOY!" → enlace de afiliado
- Debajo del botón: ícono de escudo (emoji 🛡️) + texto: "Garantía de 7 días · Si no cumple tus expectativas, te devuelven el 100% de tu dinero. Respaldado por Hotmart."
- Iconos visuales de pago (se pueden hacer con texto/emojis): 💳 Tarjetas · PayPal · Mercado Pago

### 8. FOOTER

- Fondo oscuro (#2D2D2D)
- Texto disclaimer: "Esta página contiene enlaces de afiliado. Al comprar a través de ellos, puedo recibir una comisión sin costo adicional para ti. El curso es vendido y distribuido por Hotmart."
- Copyright: "© 2026 Resina Creativa — Todos los derechos reservados"
- Texto secundario con enlace: "Curso ofrecido por Academia Digital DYE"

## REQUISITOS DE DISEÑO Y UX

- Diseño moderno, limpio, elegante, femenino pero no recargado
- Espaciado generoso entre secciones (padding amplio)
- Tipografía grande y legible
- Los botones CTA deben ser muy visibles y tener efecto hover (escala + sombra)
- El botón CTA final debe tener una animación sutil tipo "pulse" o "glow" para llamar la atención
- Secciones alternas: fondo crema (#FFF9F5) y fondo blanco (#FFFFFF) para dar ritmo visual
- Las imágenes de los proyectos deben verse bien recortadas y uniformes (usar aspect-ratio o height fija con object-fit cover)
- Transiciones suaves en hover (0.3s ease)
- El header sticky debe tener una sombra sutil cuando se activa el scroll
- Incluir animación fade-in-up cuando los elementos entran al viewport usando IntersectionObserver en un pequeño bloque <script> al final del HTML

## REQUISITOS RESPONSIVE

- Mobile first
- En mobile (<768px): todo apilado en 1 columna, tipografía adaptada, botones full-width, padding reducido
- En tablet (768px-1023px): grids de 2 columnas, hero con imagen debajo del texto
- En desktop (1024px+): grids completos (3-4 columnas), hero en 2 columnas lado a lado, container max-width 1200px centrado

## NOTAS IMPORTANTES

- NO usar ningún framework CSS (ni Bootstrap, ni Tailwind, nada)
- NO usar jQuery ni librerías JS
- El JS debe ser mínimo (solo para: header sticky con sombra al scroll, smooth scroll, y animaciones fade-in con IntersectionObserver)
- El código debe estar limpio, bien comentado y organizado
- Semántica HTML correcta (section, header, footer, nav, main, etc.)
- Optimizado para carga rápida (es solo HTML + CSS + mínimo JS)
- Compatible con GitHub Pages (estático, sin backend)

Genera el código completo de ambos archivos: index.html y css/styles.css
