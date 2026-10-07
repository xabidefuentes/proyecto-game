# Proyecto GAME · Gestor de almacén

Interfaz web estática (solo HTML y CSS) para gestionar el stock de las tiendas GAME.

## Integrantes del grupo (Grupo 1)

- Ibai García
- Iker Murias
- Xabier de Fuentes
- David San Martin

## Web publicada

<https://TU-USUARIO.github.io/proyecto-game/>  *(sustituir por el enlace real de GitHub Pages)*

## Páginas

| Página | Contenido |
|---|---|
| `index.html` | Panel de inicio: banner de novedades, resumen, destacados y ofertas |
| `catalogo.html` | Catálogo completo, con una variante por categoría (`catalogo-videojuegos.html`, `catalogo-consolas.html`, `catalogo-tarjetas-regalo.html`, `catalogo-informatica.html`, `catalogo-promociones.html`, `catalogo-seminuevos.html`, `catalogo-merchandising.html`, `catalogo-cine-comics.html`, `catalogo-electronica.html`) |
| `inventario.html` | Tabla de stock (responsive, sin desbordar en móvil) |
| `alta.html` | Formulario de alta de producto |
| `guia-estilo.html` | Miniguía de estilo |

## Dónde se aplica cada requisito (para la demo)

| Requisito | Dónde |
|---|---|
| HTML semántico | `header`, `nav`, `main`, `section`, `article`, `footer` en todas las páginas; un solo `h1` por página; todas las imágenes con `alt` |
| Clases e IDs | `.tarjeta`, `.boton`, `.etiqueta-stock`...; IDs solo para anclas (`#contenido`) y enlaces `for`/`id` de formularios |
| CSS externo | `css/estilos.css`, sin `style=""` en línea |
| Variables CSS | Bloque `:root` al inicio de `estilos.css` (colores, fuentes, espaciados) |
| Flexbox | Menú y cabecera (`.menu-lista`, `.cabecera-fila`), pie (`.pie-contenido`, `.redes`), interior de tarjetas (`.tarjeta`, `.tarjeta-pie`) |
| Grid | Rejilla del catálogo (`.rejilla-productos`), panel de inicio (`.panel-inicio`) y maquetación general de todas las páginas con `grid-template-areas` en `body` |
| Transiciones | Hover en botones (`.boton`), tarjetas (`.tarjeta`), menús, enlaces y filas de tabla |
| `@keyframes` | `aparecer` (entrada de tarjetas) y `parpadeo` (stock bajo) |
| Responsive | `meta viewport`, mobile first, 5 `@media (min-width)` + `prefers-reduced-motion`, `max-width: 100%` en imágenes, unidades `rem`, `%` y `fr` |

## Estructura

```
proyecto-game/
├── index.html
├── catalogo.html (+ 9 variantes por categoría)
├── inventario.html
├── alta.html
├── guia-estilo.html
├── css/estilos.css
├── img/
└── README.md
```

## Cómo publicar en GitHub Pages

1. Sube el repositorio a GitHub.
2. En **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`.
3. Copia el enlace generado y pégalo en este README.
