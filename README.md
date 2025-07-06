# Proyecto: Página Web con Metodología BEM

Este proyecto consiste en el desarrollo de una página web estática con un diseño. El objetivo principal es aplicar la metodología BEM (Block, Element, Modifier) para estructurar el código HTML y CSS de manera clara, mantenible y escalable.

## Objetivos Cumplidos

El proyecto cumple con los siguientes requisitos:

### 1. Estructura Básica de la Página Web

Se ha creado una estructura HTML semántica y bien organizada en `index.html`:

-   **Header**: Incluye un logo (realizado con SVG) y un menú de navegación principal.
-   **Contenido Principal**: Contiene una sección de artículo (`<article>`) con un título, párrafos de texto descriptivo y una imagen.
-   **Formulario de Contacto**: Se ha añadido una sección con un formulario de contacto funcional, siguiendo la metodología BEM para sus clases.
-   **Pie de Página**: Un `<footer>` con información de copyright y enlaces a redes sociales.

### 2. Aplicación de la Metodología BEM

Se ha implementado BEM de forma consistente en todo el documento HTML para definir una arquitectura de componentes clara.

-   **Bloques**: Se identificaron los componentes principales de la interfaz como bloques.
    -   `header`
    -   `nav`
    -   `article`
    -   `contact`
    -   `footer`

-   **Elementos**: Cada bloque se descompuso en sus partes constituyentes (elementos), utilizando la sintaxis `bloque__elemento`.
    -   Ejemplos: `nav__list`, `article__title`, `contact__input`, `footer__link`.

-   **Modificadores**: Se utilizaron modificadores para representar las variaciones de estado o apariencia de los elementos, con la sintaxis `bloque__elemento--modificador`.
    -   Ejemplos: `nav__item--active`, `footer__link--twitter`.

### 3. Codificación y Responsividad

-   **HTML**: El archivo `index.html` está estructurado con clases BEM.
-   **CSS**: El archivo `assets/css/style.css` contiene los estilos que siguen la nomenclatura BEM, asegurando que cada regla de estilo esté correctamente asociada a su componente.
-   **Responsividad**: La interfaz está diseñada para ser funcional y visualmente coherente en diferentes tamaños de pantalla, aplicando principios de diseño responsivo básicos.

## Estructura de Clases BEM Utilizadas

A continuación se detalla la estructura BEM implementada en el proyecto:

```
body

header

nav
└── nav__list
    └── nav__item
        └── nav__item--active

main

article
├── article__title
├── article__text
└── article__image

contact
├── contact__title
├── contact__form
├── contact__input
├── contact__textarea
└── contact__button

footer
├── footer__info
├── footer__social
└── footer__link
    ├── footer__link--twitter
    ├── footer__link--facebook
    └── footer__link--linkedin
```

## Estructura de Archivos

```
.
├── assets
│   ├── css
│   │   └── style.css
│   └── images
│       └── crypto.jpg
├── index.html
└── README.md
```

## Cómo Visualizar el Proyecto

Para ver la página web, simplemente sigue estos pasos:

1.  Clona o descarga este repositorio en tu máquina local.
2.  Navega hasta la carpeta del proyecto.
3.  Abre el archivo `index.html` en tu navegador web preferido (Google Chrome, Firefox, etc.).

---
# Juan Luis Mansilla N.

*Este proyecto fue creado como parte del Bootcamp de Desarrollo de Aplicaciones Front-end.*