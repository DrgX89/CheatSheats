
# CSS Cheatsheet

## Selectores Básicos
```css
/* Selecciona todos los elementos */
* {
    margin: 0;
    padding: 0;
}

/* Selecciona por etiqueta */
h1 {
    color: blue;
}

/* Selecciona por clase */
.intro {
    font-size: 18px;
}

/* Selecciona por ID */
#main-header {
    background-color: yellow;
}
```

## Modelo de Caja (Box Model)
```css
div {
    width: 100px;
    height: 100px;
    padding: 10px;
    border: 1px solid black;
    margin: 10px;
}
```

## Colores
```css
/* Colores por nombre */
p {
    color: red;
}

/* Colores en HEX */
p {
    color: #ff0000;
}

/* Colores RGB */
p {
    color: rgb(255, 0, 0);
}

/* Colores RGBA */
p {
    color: rgba(255, 0, 0, 0.5);
}
```

## Tipografía
```css
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5;
    text-align: center;
}
```

## Fondos
```css
body {
    background-color: #f0f0f0;
    background-image: url('imagen.jpg');
    background-size: cover;
    background-position: center;
}
```

## Bordes y Sombras
```css
div {
    border: 2px solid black;
    border-radius: 10px;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
}
```

## Flexbox
```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.item {
    flex: 1;
    padding: 10px;
}
```

## Grid Layout
```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 10px;
}

.item {
    background-color: lightblue;
}
```

## Transiciones
```css
button {
    background-color: blue;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: green;
}
```

## Media Queries
```css
@media (max-width: 600px) {
    body {
        background-color: lightcoral;
    }
}
```
