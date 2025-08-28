# Mapa Interactivo de Colombia con HTML
### Paula Andrea Viviescas Jaimes

Este proyecto es un mapa interactivo de Colombia creado únicamente con HTML. Permite a los usuarios hacer clic en departamentos específicos para obtener información turística detallada.

## 🗺️ Descripción

La página principal muestra una imagen del mapa de Colombia. Usando la etiqueta `<map>` de HTML, se han definido áreas poligonales sobre los departamentos de **Santander, Caquetá y Vichada**. Al hacer clic en estas áreas, el usuario es redirigido a una página separada que contiene información relevante sobre dicho departamento.

## 🎯 Objetivo del Proyecto

El propósito principal de este proyecto es la práctica y demostración del uso de diversas etiquetas fundamentales de HTML5. Se enfoca en la estructuración de contenido, la creación de interactividad básica y la inserción de multimedia sin el uso de JavaScript o frameworks externos.

## ✨ Características

- **Mapa Interactivo**: Imagen de un mapa con áreas clicables.
- **Navegación**: Redirección a páginas de detalle para cada departamento seleccionado.
- **Contenido Detallado**: Las páginas de destino incluyen información sobre:
  - Sitios turísticos.
  - Comida típica.
  - Información económica y laboral.
- **Maquetación**: Se utiliza `div` con `display: flex` para la estructura principal de la página.

## 🛠️ Etiquetas HTML Utilizadas

Este proyecto fue una oportunidad para practicar con las siguientes etiquetas:

- **Estructura y Semántica**: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<div>`
- **Metadatos**: `<meta>`, `<title>`
- **Texto**: `<h1>`, `<h2>`, `<h3>`, `<p>`, `<strong>`, `<br>`, `<hr>`
- **Multimedia e Interacción**: `<img>`, `<map>`, `<area>`, `<video>`, `<source>`
- **Enlaces**: `<a>`
- **Estilos**: Se utiliza el atributo `style` para aplicar CSS directamente en los elementos (inline CSS) como parte del ejercicio de aprendizaje.

## 🚀 Cómo Ejecutar el Proyecto

1.  Clona o descarga el repositorio en tu máquina local.
2.  Abre el archivo `index.html` en tu navegador web preferido (como Chrome, Firefox, etc.).
3.  ¡Navega por el mapa!

## 📂 Estructura de Archivos

```
.

├── css
│   └── .gitkeep
├── images
│   ├── barichara.png
│   ├── catedral.png
│   ├── chicamocha.png
│   ├── dalias.png
│   ├── danubio.png
│   ├── florencia.png
│   ├── macarena.png
│   ├── mapa.png
│   ├── puerto_carreno.png
│   ├── quebrada-las-gachas.png
│   ├── rio_orinoco.png
│   ├── san_gil.png
│   └── tuparro.png
├── js
│   └── .gitkeep
├── pages
│   ├── caqueta.html
│   ├── santander.html
│   └── vichada.html
├── videos
│   ├── comida_caqueta.mp4
│   ├── comida_santander.mp4
│   └── comida_vichada.mp4
├── index.html
└── README.md
```

---
*Proyecto realizado como práctica de las bases de HTML.*