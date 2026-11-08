# Slowform — Bento Grid

Pequeña web editorial responsive construida con HTML5 y CSS moderno.

## Cómo ejecutarla

1. Descomprime la carpeta.
2. Abre `index.html` en un navegador moderno.
3. Para editar el tema, modifica las variables de `css/variables.css`.

No necesita JavaScript ni dependencias de npm.

## Requisitos del ejercicio incluidos

- Grid principal de tres columnas para pantallas mayores de 700 px.
- En `@media (max-width: 700px)`, las tres columnas principales se apilan.
- Cada columna contiene un grid anidado independiente.
- Hay elementos que ocupan dos columnas (`.span-cols-2`) y otros que ocupan dos filas (`.span-rows-2`). El resto ocupa una celda.
- `css/variables.css` se importa desde `css/styles.css` mediante `@import`.
- Variables CSS para colores, fuentes, radios, espacios, sombras y transiciones.
- Tema claro/oscuro mediante `@media (prefers-color-scheme: dark)`.
- CSS anidado en selectores como `.bento-column` y `.bento-card`.
- Animaciones de entrada, transiciones hover y respeto a `prefers-reduced-motion`.

## Personalización

- Cambia las imágenes editando los `src` de los elementos `<img>` de `index.html`.
- Cambia la tipografía desde los enlaces de Google Fonts de `index.html` y las variables `--font-body` / `--font-display`.
- Cambia la paleta en `css/variables.css`.

Las fotografías se cargan desde Unsplash y las fuentes desde Google Fonts, por lo que se necesita conexión a Internet para ver esos recursos externos.
