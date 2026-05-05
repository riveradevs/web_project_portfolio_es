🧑‍💻 Personal Portfolio – Responsive Website

Proyecto de portafolio personal desarrollado con HTML y CSS puro, enfocado en buenas prácticas de layout responsivo, estructura modular y diseño limpio.

🚀 Descripción

Este proyecto consiste en una landing page tipo portafolio con las siguientes características:

Diseño totalmente responsivo
Estructura adaptable para:
Desktop (1440px)
Tablet (768px)
Mobile (320px)
Layout basado en Flexbox y Grid
Uso de tipografía fluida (clamp)
Organización modular del CSS
Enfoque en alineación, proporciones y consistencia visual
🧱 Estructura del proyecto
project/
├── index.html
├── style/
│ ├── styles.css # Archivo principal (fonts + base + imports)
│ ├── header.css # Header y hero section
│ ├── skills.css # Skills section
│ ├── projects.css # Projects grid y cards
│ ├── footer.css # Footer
│ └── responsive.css # Media queries
└── fonts/
🎯 Funcionalidades clave
🔹 Header
Imagen y texto en layout horizontal hasta 528px
Cambio a layout vertical en mobile
Ajuste progresivo de márgenes
🔹 Skills
Distribución horizontal en desktop
Reducción progresiva de spacing
Reflow a múltiples filas en pantallas pequeñas
Íconos con tamaño responsivo
🔹 Projects
Grid de 2 columnas en desktop
Cambio a 1 columna en tablet/mobile
Imágenes con aspect-ratio (no se deforman)
Cards flexibles según contenido
🔹 Footer
Ajustes específicos para mobile
Espaciado fluido entre íconos
Tipografía optimizada
📱 Responsive Design

Breakpoints principales:

1440px → layout base
768px → cambios en grid y spacing
528px → cambio estructural del header
480px → ajustes finos mobile
🧠 Decisiones técnicas
Uso de clamp() para escalado fluido
Separación de CSS por secciones
Evitar valores fijos innecesarios
Control preciso de márgenes laterales
Uso de aspect-ratio en imágenes
⚙️ Cómo usar
Clona el repositorio:
git clone https://github.com/tu-usuario/tu-repo.git
Abre el proyecto:
cd tu-repo
Abre index.html en el navegador o con Live Server.
📦 Tecnologías
HTML5
CSS3
Flexbox
CSS Grid
🏁 Estado del proyecto

✅ Completo
✅ Responsive validado
✅ Estructura modular implementada

📌 Posibles mejoras futuras
Migración a SCSS
Animaciones avanzadas
Integración con JavaScript
Optimización de assets
👤 Autor

Ignacio Rivera
