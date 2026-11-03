# FAN · Verdura hidropónica · Web en HTML y CSS

Web de una empresa ficticia de verdura hidropónica, con catálogo de productos, recetas, formulario de presupuesto y página de contacto. Está hecha **solo con HTML y CSS, sin JavaScript**: el carrusel y el menú para móvil funcionan únicamente con CSS.

Proyecto final del módulo de HTML y CSS del ciclo de **Técnico Superior en Desarrollo de Aplicaciones Web**.

## Demo en vivo

**https://drfrodorick.github.io/Marcelino_Ramos_trabajoHTML/**

## Funcionalidades

- **Carrusel sin JavaScript:** usa botones de radio ocultos y el selector `:checked` para cambiar de imagen.
- **Menú hamburguesa sin JavaScript**, con un checkbox oculto que abre y cierra la navegación en móvil.
- **Maquetación con CSS Grid y Flexbox**, incluida una rejilla de productos que se adapta sola al ancho con `repeat(auto-fit, minmax(...))`.
- **Diseño responsive** con media queries para móvil, tablet y escritorio.
- **Formulario de presupuesto con validación HTML5**: campos obligatorios, tipos `email` y `tel`, longitudes mínimas y máximas, y patrones (`pattern`) con expresiones regulares.
- **HTML semántico y accesible:** `header`, `nav`, `main`, `section`, `footer`, etiquetas `label` asociadas a cada campo y textos alternativos en las imágenes.

## Tecnologías

- HTML5
- CSS3 (Grid, Flexbox, media queries y transiciones)
- Publicado con GitHub Pages

## Estructura

```
├── index.html          # Portada: carrusel, productos y recetas
├── views/              # Productos, presupuesto, contacto y aviso legal
├── css/styles.css      # Todos los estilos
└── assets/             # Imágenes y favicon
```

## Ejecutarlo en local

No necesita instalación: basta con abrir `index.html` en el navegador.

## Autor

**Marcelino Ramos Martínez** · Desarrollador Web Junior
[GitHub](https://github.com/DrFrodorick) · [LinkedIn](https://www.linkedin.com/in/marcelino-ramos-martinez-0b4178262/)
