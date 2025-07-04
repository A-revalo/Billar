🎱 Página Web Temática de Billar
Una elegante galería de productos con diseño responsive inspirado en la temática del billar, utilizando una paleta de colores azul y verde que evoca la atmósfera clásica de las mesas de billar.
🎨 Características del Diseño
Paleta de Colores

Azul Principal: #2563eb - Color base para elementos principales
Verde Mesa: #16a34a - Inspirado en el fieltro de las mesas de billar
Verde Claro: #22c55e - Acentos y destacados
Fondo Azul: #dbeafe - Fondo suave y elegante
Superficie Verde: #dcfce7 - Superficies de tarjetas y elementos

Tipografía Responsive

Sistema de fuentes nativo para máximo rendimiento
Escalado fluido con clamp() para todos los tamaños de pantalla
Jerarquía visual clara y legible

📱 Diseño Responsive
Breakpoints

Mobile: < 768px - 1 columna
Tablet: 768px - 1023px - 2 columnas
Desktop: 1024px - 1439px - 3 columnas
Large Desktop: ≥ 1440px - 4 columnas

Características Responsive

Espaciado fluido que se adapta al viewport
Tipografía escalable automáticamente
Grid system flexible para productos
Indicador visual del dispositivo actual

🏗️ Estructura del CSS
Variables CSS Personalizadas
css:root {
    --azul-principal: #2563eb;
    --verde-mesa: #16a34a;
    --verde-claro: #22c55e;
    /* ... más variables */
}
Componentes Principales
Header

Fondo degradado verde
Logo destacado en verde claro
Navegación breadcrumb

Galería de Productos

Grid responsive: Se adapta automáticamente al tamaño de pantalla
Tarjetas interactivas: Efectos hover suaves
Imágenes responsive: Aspect ratio 4:3 mantenido
Badges de producto: Etiquetas destacadas
Botones de acción: Primarios y secundarios

Footer

Fondo degradado azul
Layout en grid responsive
Enlaces con efectos hover
Separación visual clara

🎯 Área de Trabajo - Imágenes de Productos
Contenedor de Imagen
css.product-image-container {
    position: relative;
    aspect-ratio: 4/3;
    overflow: hidden;
    /* Área lista para personalización */
}
Imagen del Producto
css.product-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    /* Responsive y mantiene proporción */
}
🚀 Características Técnicas
Rendimiento

Variables CSS: Fácil mantenimiento y personalización
Fuentes del sistema: Carga rápida sin descargas externas
Transiciones optimizadas: Efectos suaves sin impacto en rendimiento
Grid CSS nativo: Layout moderno y eficiente

Accesibilidad

Contraste de colores adecuado
Espaciado táctil apropiado para móviles
Transiciones respetan prefers-reduced-motion
Estructura semántica clara

Compatibilidad

CSS Grid: Soporte completo en navegadores modernos
Custom Properties: IE11+ (con fallbacks si es necesario)
Clamp(): Soporte nativo en navegadores recientes
Aspect-ratio: Soporte creciente, con fallback en flex

🛠️ Personalización
Cambiar Colores
Modifica las variables en :root para cambiar toda la paleta:
css:root {
    --azul-principal: #tu-color;
    --verde-mesa: #tu-color;
    /* ... */
}
Ajustar Espaciado
Las variables de espaciado son fluidas y personalizables:
css--xs: clamp(0.5rem, 2vw, 1rem);
--sm: clamp(1rem, 3vw, 1.5rem);
/* ... */
Modificar Breakpoints
Ajusta los media queries según tus necesidades:
css@media (min-width: 768px) {
    /* Tablet styles */
}
📦 Estructura de Archivos Recomendada
proyecto/
├── css/
│   └── styles.css
├── images/
│   └── productos/
├── index.html
└── README.md
🎮 Temática de Billar
El diseño captura la esencia del billar a través de:

Colores: Azul profundo del marco y verde del fieltro
Elegancia: Líneas limpias y transiciones suaves
Profesionalismo: Layout organizado y jerárquico
Interactividad: Efectos hover que simulan el movimiento

🔧 Próximas Mejoras

 Modo oscuro automático
 Animaciones de entrada con Intersection Observer
 Filtros de productos dinámicos
 Lazy loading para imágenes
 PWA capabilities


