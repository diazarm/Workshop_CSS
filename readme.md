# 📘 Workshop CSS - Teoría y Código

Este documento contiene la teoría básica y ejemplos prácticos de CSS cubiertos en el workshop.

---

## 1. ¿Qué es CSS?

CSS (Cascading Style Sheets) permite aplicar estilos a páginas web.  
Hay 3 formas de usarlo:
- **Inline** (en la etiqueta)
- **Internal** (bloque `<style>` dentro del HTML)
- **External** (referenciando un archivo .css externo)

```html
<!-- Inline -->
<h1 style="color: red;">Hola Mundo</h1>

<!-- Internal -->
<style> h1 { color: blue; } </style>

<!-- External -->
<link rel="stylesheet" href="styles.css">
```

---

## 2. Selectores y Sintaxis

Los selectores permiten aplicar estilos a elementos específicos.

```css
/* Selector por etiqueta */
p { color: gray; }

/* Selector por clase */
.titulo { font-size: 24px; }

/* Selector por ID */
#principal { background-color: lightblue; }

/* Selectores combinados */
h1.titulo { color: green; }
```

---

## 3. Propiedades Comunes

Algunas propiedades clave:
- color
- background-color
- font-family
- font-size
- margin
- padding
- border

```css
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}
.container {
  margin: 20px;
  padding: 15px;
  border: 1px solid #ccc;
  color: #333;
}
```

---

## 4. Box Model

El modelo de caja define cómo se renderiza un elemento:
- content
- padding
- border
- margin

```css
.caja {
  width: 200px;
  padding: 10px;
  border: 5px solid black;
  margin: 20px;
}
```

---

## 5. Display y Position

### Display
```css
.block { display: block; }
.inline { display: inline; }
.flex { display: flex; justify-content: space-between; }
```

### Position
```css
.absoluto {
  position: absolute;
  top: 10px;
  left: 20px;
}
```

---

## 6. Media Queries y Responsividad

Adaptar el diseño a pantallas pequeñas:

```css
@media (max-width: 768px) {
  body {
    background-color: lightgray;
  }
}
```

---

## 7. Buenas Prácticas

- Usar nombres de clases claros
- Evitar código duplicado
- Comentar secciones
- Mantener estructura limpia

```css
/* Nombres claros */
.card-product { /* contenido */ }

/* Comentarios */
/* -- Header Styles -- */
.header {
  background-color: #333;
  color: white;
}
```

Link del [repositorio](https://github.com/diazarm/Workshop_CSS.git)
## Workshop UDD4.0 Chile -   [LinkedIn](https://www.linkedin.com/in/marcelo-a-diaz-6a7926223/) Coach Marcelo A. Diaz


