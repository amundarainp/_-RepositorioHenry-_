# _-RepositorioHenry-_
Homework Módulo 0

# 📘 Guía rápida de HTML, CSS y JavaScript

Este README contiene una tabla resumen con las etiquetas HTML, propiedades CSS y conceptos básicos de JavaScript más usados.  
Sirve como apunte personal y guía rápida durante el desarrollo.

---

## 🏷️ Etiquetas HTML y Atributos Principales

| Etiqueta        | Atributos principales                        | Descripción breve                                   |
|-----------------|---------------------------------------------|-----------------------------------------------------|
| `<html>`        | lang                                        | Idioma del documento                                |
| `<head>`        | -                                           | Contiene metadatos                                  |
| `<body>`        | style, class, id                            | Contenido visible                                   |
| `<h1> - <h6>`   | id, class, style                            | Encabezados de texto                                |
| `<p>`           | id, class, style                            | Párrafos de texto                                   |
| `<span>`        | id, class, style                            | Texto en línea                                      |
| `<a>`           | href, target, title                         | Enlaces a páginas o recursos                        |
| `<img>`         | src, alt, width, height                     | Imágenes                                            |
| `<video>`       | src, controls, autoplay, loop               | Video con opciones de reproducción                  |
| `<audio>`       | src, controls, autoplay, loop               | Audio con opciones de reproducción                  |
| `<form>`        | action, method                              | Formulario para enviar datos                        |
| `<input>`       | type, name, value, placeholder, required    | Campos de formulario                                |
| `<textarea>`    | rows, cols, placeholder, required           | Área de texto                                       |
| `<button>`      | type, disabled                              | Botones de acción                                   |
| `<div>`         | id, class, style                            | Contenedor de elementos                             |
| `<header>`      | id, class, style                            | Encabezado de la página o sección                   |
| `<footer>`      | id, class, style                            | Pie de página o sección                             |
| `<nav>`         | id, class, style                            | Contiene enlaces de navegación                      |
| `<section>`     | id, class, style                            | Agrupa contenido temático dentro de la página       |
| `<article>`     | id, class, style                            | Contenido independiente (ej: post, noticia)         |
| `<aside>`       | id, class, style                            | Contenido lateral o complementario                  |
| `<main>`        | id, class, style                            | Contenido principal de la página                    |
| `<table>`       | border, cellpadding, cellspacing            | Crea tablas                                         |
| `<tr>`          | -                                           | Fila en una tabla                                   |
| `<td>`          | colspan, rowspan                           | Celda en una tabla                                  |
| `<th>`          | colspan, rowspan                           | Celda de encabezado en tabla                        |
| `<ul>`          | type                                        | Lista no ordenada                                   |
| `<ol>`          | type, start, reversed                      | Lista ordenada                                      |
| `<li>`          | -                                           | Ítem de lista                                       |

---

## 🎨 Propiedades CSS más usadas

| Propiedad       | Valores principales / Ejemplo            | Descripción breve                           |
|-----------------|-----------------------------------------|---------------------------------------------|
| color           | red, #ff0000, rgb(255,0,0)              | Color del texto                             |
| background      | red, url(img.jpg), none                 | Fondo de un elemento                        |
| background-color| blue, transparent                       | Color de fondo                              |
| font-size       | 16px, 1.2em, large                      | Tamaño de letra                             |
| font-family     | Arial, "Times New Roman", sans-serif    | Tipo de letra                               |
| font-weight     | normal, bold, 100-900                   | Grosor de la fuente                         |
| text-align      | left, center, right, justify            | Alineación del texto                        |
| text-decoration | none, underline, line-through           | Decoración del texto                        |
| margin          | 10px, auto, 0 5px                       | Márgenes externos                           |
| padding         | 10px, 0 5px                             | Relleno interno                             |
| border          | 1px solid black                         | Borde del elemento                          |
| border-radius   | 10px, 50%                               | Bordes redondeados                          |
| width / height  | px, %, auto                             | Tamaño del elemento                         |
| max-width/min-width | px, %                               | Restricciones de tamaño                     |
| display         | block, inline, flex, grid, none         | Tipo de caja                                |
| position        | static, relative, absolute, fixed, sticky | Posición del elemento                     |
| z-index         | número (ej: 1000)                       | Orden de apilamiento                        |
| flex            | grow shrink basis                       | Control en contenedor flex                  |
| justify-content | flex-start, center, space-between       | Alineación en eje principal flex            |
| align-items     | flex-start, center, stretch             | Alineación en eje secundario flex           |
| grid-template   | rows / columns                          | Define grilla en display:grid               |
| gap             | 10px                                    | Espacio entre elementos flex o grid         |
| overflow        | hidden, scroll, auto                    | Control del desborde de contenido           |

---

## ⚡ Conceptos JavaScript básicos

| Concepto / Sintaxis | Ejemplo                                  | Descripción breve                          |
|---------------------|------------------------------------------|--------------------------------------------|
| Variables           | let x = 10; const y = "hola";            | Guardan datos (let = variable, const = fija)|
| Tipos de datos      | string, number, boolean, array, object   | Diferentes formas de representar valores    |
| Operadores          | +, -, *, /, %, **                        | Operaciones matemáticas                     |
| Comparación         | ==, ===, !=, !==, >, <                   | Comparar valores                            |
| Lógicos             | &&, \|\|, !                             | Operadores lógicos                          |
| Condicionales       | if (...) { ... } else { ... }            | Ejecutar según condición                    |
| Switch              | switch(valor) { case 1: ... }            | Múltiples condiciones                       |
| Bucles              | for, while, do...while                   | Repetir bloques de código                   |
| for...of            | for (let v of arr)                       | Recorrer arrays                             |
| for...in            | for (let k in obj)                       | Recorrer propiedades de objetos             |
| Funciones           | function suma(a,b){ return a+b; }        | Bloques de código reutilizables             |
| Arrow functions     | const suma = (a,b) => a+b;               | Sintaxis corta de función                   |
| Objetos             | let persona = { nombre:"Ana", edad:20 }; | Estructura clave-valor                      |
| Arrays              | let nums = [1,2,3]; nums.push(4);        | Lista de valores                            |
| Métodos de array    | map, filter, reduce, forEach             | Operaciones comunes sobre listas            |
| DOM                 | document.getElementById("id")            | Acceso y manipulación de HTML desde JS      |
| Eventos             | element.addEventListener("click", fn)    | Responder a acciones del usuario            |
| Funciones asincrónicas | async function f() { await ... }      | Manejo de código asincrónico                |
| Promesas            | fetch(url).then(r=>r.json())             | Manejo de resultados futuros                |
| console.log         | console.log("Hola JS")                   | Mostrar datos en la consola                 |

