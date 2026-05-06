# Portfolio Web — Ignacio Rivera

Portfolio web responsivo desarrollado con HTML y CSS.

El proyecto fue diseñado siguiendo una estructura modular de estilos, buenas prácticas de organización y un enfoque responsive-first para adaptarse correctamente desde desktop hasta mobile.

---

# Vista general

El sitio incluye:

- Header responsive con fotografía dinámica y distribución avanzada de texto.
- Sección de skills con distribución adaptable.
- Sección de proyectos con cards responsivas.
- Footer responsive con espaciado consistente.
- Efectos visuales mediante gradients y ellipses difuminadas.
- Tipografías locales optimizadas mediante `@font-face`.

---

# Tecnologías utilizadas

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- Git
- GitHub Pages

---

# Estructura del proyecto

```text
project/
│
├── index.html
│
├── style/
│   ├── styles.css
│   ├── header.css
│   ├── skills.css
│   ├── projects.css
│   ├── footer.css
│   └── responsive.css
│
├── images/
│
├── fonts/
│
└── README.md
```

---

# Organización de CSS

## styles.css

Contiene:

- Fuentes (`@font-face`)
- Reset global
- Base general del proyecto
- Imports de los demás archivos CSS

## header.css

Contiene:

- Header principal
- Ellipse superior
- Responsive del header
- Distribución dinámica del texto y fotografía

## skills.css

Contiene:

- Layout de skills
- Distribución de iconos
- Ajustes de espaciado responsive

## projects.css

Contiene:

- Grid de proyectos
- Cards
- Imágenes
- Íconos
- Links
- Ajustes de altura responsive

## footer.css

Contiene:

- Footer
- Ellipse inferior
- Redes sociales
- Espaciado inferior fijo

## responsive.css

Contiene:

- Media queries globales
- Ajustes específicos para tablet y mobile

---

# Responsive Design

El proyecto fue desarrollado considerando:

- Desktop: 1440px
- Tablet: 768px
- Mobile: 528px y menores

Características principales:

- Márgenes laterales fluidos.
- Reducción proporcional de tipografías.
- Fotografías responsivas.
- Reorganización de grids.
- Distribución adaptable del texto.
- Ajustes dinámicos de espaciado.

---

# Tipografías

Fuentes utilizadas:

- Archivo Black
- Open Sans

Las fuentes se cargan localmente mediante archivos `.woff2`.

---

# Publicación en GitHub Pages

El proyecto puede visualizarse mediante GitHub Pages.

Configuración recomendada:

```text
Settings → Pages
```

Seleccionar:

```text
Deploy from a branch
```

Branch:

```text
main / root
```

---

# Instalación local

Clonar el repositorio:

```bash
git clone https://github.com/usuario/repositorio.git
```

Abrir el proyecto en VS Code.

Usar Live Server para desarrollo local.

---

# Autor

Ignacio Rivera

Desarrollador Full-Stack Junior
