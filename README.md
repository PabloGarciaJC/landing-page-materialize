# Landing Page (Materialize)

Landing Page desarrollada con **HTML5**, **CSS3** y **Materialize CSS**, usando **Material Icons** y estilos personalizados para una experiencia visual moderna y responsive.

## Demo del Proyecto

[https://landing-page-materialize.com/](https://landing-page-materialize.pablogarciajc.com/)

| ![Imagen 1](https://pablogarciajc.com/wp-content/uploads/2025/11/landing-page-materialize-1.webp) | ![Imagen 2](https://pablogarciajc.com/wp-content/uploads/2025/11/landing-page-materialize-2.webp) |
|-----------|-----------|

---

## Funcionalidades principales

- Menú de navegación adaptable para dispositivos móviles y escritorio usando **Sidenav** de Materialize.  
- Secciones: Inicio, Nosotros, Servicios, Portafolio, Contacto y Footer.  
- Hero con imagen de fondo full-screen y botones destacados.  
- Cards para mostrar servicios y portafolio.  
- Formulario de contacto estilizado con Materialize inputs y botones.  
- Footer centrado y compacto usando **page-footer**.  
- Comportamiento responsive en todas las secciones (desktop, tablet y móvil).  

---

## Tecnologías utilizadas

- **HTML5 semántico**  
- **CSS3**  
- **Materialize CSS**  
- **Material Icons**  
- **JavaScript Vanilla (ES6+)**  
- **M.AutoInit()** para inicializar componentes interactivos automáticamente  

---

## Estructura de la landing

### Navbar

- `nav` con clase `z-depth-1` para sombra y `container` para centrar.  
- Menú responsive usando `sidenav-trigger` y `<ul class="sidenav">`.  

### Hero

- Imagen de fondo con `object-fit: cover` y `height: 100vh` en desktop.  
- Texto y botones centrados con `.hero-content` y `z-index` sobre la imagen.  
- Responsive: altura y texto ajustables en tablet y móvil.  

### Servicios

- `row` + `col s12 m4` para grid responsive.  
- Cards con `card`, `card-content` y `card-title`.  
- Iconos de Material Icons a la izquierda con clase `left`.  

### Portafolio

- Grid de proyectos con `card-image` y `card-content`.  
- Texto y títulos estilizados con clases de Materialize.  

### Contacto

- Formulario con `input-field` y `materialize-textarea`.  
- Botones grandes con `btn-large` y colores personalizados.  

### Footer

- `page-footer` centrado.  
- Texto sin márgenes usando `no-margin`.  

---

## Responsividad

- Mobile: hero más pequeño (`60vh`), texto y botones reducidos.  
- Tablet: hero ajustado (`80vh`), tamaño de texto intermedio.  
- Desktop: hero completo (`100vh`), botones grandes y centrados.  

---

## Instalación

> ⚠️ No es necesario usar Docker ni Make, ya que este proyecto es completamente estático.

---

## Contáctame / Sígueme en mis redes sociales

| Red Social   | Descripción                                              | Enlace                   |
|--------------|----------------------------------------------------------|--------------------------|
| **Facebook** | Conéctate y mantente al tanto de mis actualizaciones.    | [Presiona aquí](https://www.facebook.com/PabloGarciaJC) |
| **YouTube**  | Fundamentos de la programación, tutoriales y noticias.   | [Presiona aquí](https://www.youtube.com/@pablogarciajc)     |
| **Página Web** | Más información sobre mis proyectos y servicios.        | [Presiona aquí](https://pablogarciajc.com/)              |
| **LinkedIn** | Sigue mi carrera profesional y establece conexiones.     | [Presiona aquí](https://www.linkedin.com/in/pablogarciajc) |
| **Instagram**| Fotos, proyectos y contenido relacionado.                 | [Presiona aquí](https://www.instagram.com/pablogarciajc) |
| **Twitter/X**  | Proyectos, pensamientos y actualizaciones.                | [Presiona aquí](https://x.com/PabloGarciaJC?t=lct1gxvE8DkqAr8dgxrHIw&s=09)   |

---
> _"La única forma de hacer un gran trabajo es amar lo que haces." - Steve Jobs_
