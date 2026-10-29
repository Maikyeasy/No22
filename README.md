# No.22 · Online Clothing Store / Tienda de ropa online

🌐 [English](#english) · [Español](#español)

---

<a id="english"></a>
## 🇬🇧 English

Website mockup for an urban fashion store called **No.22**, built with **HTML and CSS only** as a class project (1st year DAM, IES El Rincón).

The page has a full-screen cover with the header on top, a "Novedades" (New arrivals) product gallery and a footer. It is *responsive*: it adapts to mobile, tablet and desktop.

### Project structure

```
/
├── index.html
├── README.md
├── css/
│   └── style.css
└── img/
    ├── logo.png
    ├── moda-urbana.png
    ├── polo-rosa-frente.png
    ├── polo-blanco-frente.jpg
    ├── camiseta-raglan-frente.png
    ├── bota-lateral.png
    └── bolso-cuadros-1.png
```

### Page content

- **Header (`header`)**: link to the collection, centered No.22 logo and search and cart icons. It is placed over the cover image.
- **Cover**: full-screen urban fashion main image.
- **"Novedades" product gallery**: cards with photo, name, price and an "Add to cart" button.
- **Footer (`footer`)**: copyright notice.

### Products

| Product | Price |
|---------|-------|
| Pink Camo Polo | €59.00 |
| No.22 Suede Boots | €129.00 |
| Red Raglan T-shirt | €39.00 |
| No.22 White Polo | €59.00 |
| No.22 Plaid Bag | €99.00 |

### Technologies

- **HTML5** with semantic tags: `header`, `nav`, `main`, `section`, `article`, `footer`.
- **CSS3**:
  - **Flexbox** for the header, the product gallery and the footer.
  - **Media queries** with three sizes: mobile (default), tablet (`min-width: 600px`) and desktop (`min-width: 1024px`).
  - **Hover effect**: soft zoom on the product photo when the mouse passes over it (`transform: scale(1.05)`).
- **Google Material Symbols** for the search and cart icons (used for icons only).

### Responsive design

| Screen | Width | Products per row | Logo |
|--------|-------|------------------|------|
| Mobile | < 600 px | 2 | 70 px |
| Tablet | ≥ 600 px | 3 | 90 px |
| Desktop | ≥ 1024 px | 4 | 110 px |

### Inspiration

Design inspired by the [Cold Culture](https://coldcultureworldwide.com/es) website.

### How to run it

1. Clone the repository:
   ```bash
   git clone <REPOSITORY-URL>
   ```
2. Open `index.html` in your browser. No installation or server needed.

### Author

**Jean Marcos Jaen Arias**, 1st year DAM (Cross-platform Application Development), 2026-2027 school year.

[⬆ Back to top](#no22--online-clothing-store--tienda-de-ropa-online)

---

<a id="español"></a>
## 🇪🇸 Español

Maqueta web de una tienda de moda urbana llamada **No.22**, desarrollada solo con **HTML y CSS** como proyecto de clase (1.º DAM, IES El Rincón).

La página tiene una portada a pantalla completa con la cabecera encima, una galería de productos "Novedades" y un pie de página. Es *responsive*: se adapta a móvil, tablet y escritorio.

### Estructura del proyecto

```
/
├── index.html
├── README.md
├── css/
│   └── style.css
└── img/
    ├── logo.png
    ├── moda-urbana.png
    ├── polo-rosa-frente.png
    ├── polo-blanco-frente.jpg
    ├── camiseta-raglan-frente.png
    ├── bota-lateral.png
    └── bolso-cuadros-1.png
```

### Contenido de la página

- **Cabecera (`header`)**: enlace a la colección, logo de No.22 centrado e iconos de búsqueda y carrito. Se superpone sobre la portada.
- **Portada**: imagen principal de moda urbana a pantalla completa.
- **Galería de productos "Novedades"**: tarjetas con foto, nombre, precio y botón "Añadir al carrito".
- **Pie de página (`footer`)**: aviso de copyright.

### Productos

| Producto | Precio |
|----------|--------|
| Polo Camuflaje Rosa | 59,00 € |
| Botas de Ante No.22 | 129,00 € |
| Camiseta Raglán Roja | 39,00 € |
| Polo Blanco No.22 | 59,00 € |
| Bolso de Cuadros No.22 | 99,00 € |

### Tecnologías utilizadas

- **HTML5** con etiquetas semánticas: `header`, `nav`, `main`, `section`, `article`, `footer`.
- **CSS3**:
  - **Flexbox** para la cabecera, la galería de productos y el pie de página.
  - **Media queries** con tres tamaños: móvil (por defecto), tablet (`min-width: 600px`) y escritorio (`min-width: 1024px`).
  - **Efecto hover**: zoom suave en la foto del producto al pasar el ratón (`transform: scale(1.05)`).
- **Google Material Symbols** para los iconos de búsqueda y carrito (solo se usa para iconos).

### Diseño responsive

| Pantalla | Ancho | Productos por fila | Logo |
|----------|-------|--------------------|------|
| Móvil | < 600 px | 2 | 70 px |
| Tablet | ≥ 600 px | 3 | 90 px |
| Escritorio | ≥ 1024 px | 4 | 110 px |

### Inspiración

Diseño inspirado en la página web de [Cold Culture](https://coldcultureworldwide.com/es).

### Cómo ejecutarlo

1. Clona el repositorio:
   ```bash
   git clone <URL-DEL-REPOSITORIO>
   ```
2. Abre `index.html` en el navegador. No necesita instalación ni servidor.

### Autor

**Jean Marcos Jaen Arias**, 1.º DAM (Desarrollo de Aplicaciones Multiplataforma), curso 2026-2027.

[⬆ Volver arriba](#no22--online-clothing-store--tienda-de-ropa-online)
