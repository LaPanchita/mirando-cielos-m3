# Mirando Cielos 🌥️

Aplicación frontend de clima desarrollada como parte del **Módulo 3 – Interfaz y Estilos**.
La app presenta el clima de distintas ciudades de Chile con una estética suave y
fantástica, inspirada en la observación del cielo y la atmósfera.

## 🌈 Temática
Clima de fantasía para ciudades reales de Chile.
La aplicación busca transmitir una sensación calmada y visualmente amable,
manteniendo datos climáticos simples y claros.

## 🧱 Tecnologías utilizadas
- HTML5 semántico
- Bootstrap 5 (grid y componentes)
- SASS (preprocesador CSS)
- Metodología BEM para organización de estilos
- JavaScript básico (interacción mínima)

## 🎨 Metodología de estilos
Se utiliza la metodología **BEM (Block, Element, Modifier)** para mantener
los estilos organizados, escalables y fáciles de mantener.

Ejemplos de clases:
- `.weather-app`
- `.weather-app__header`
- `.place-card`
- `.place-card__temp`
- `.place-card--sunny`

## 🗂️ Estructura SASS

/scss
  /base
    _variables.scss
    _mixins.scss
  /layout
    _layout.scss
  /components
    _place-card.scss
  main.scss

- `variables`: colores, tipografías y tamaños
- `mixins`: estilos reutilizables
- `layout`: estructura general de la app
- `components`: estilos de componentes individuales

El archivo `main.scss` importa todos los parciales y se compila a `css/main.css`.

## 📱 Responsividad
- En pantallas pequeñas (≤ 420px): cards apiladas en una columna
- En pantallas grandes (≥ 1024px): múltiples cards por fila usando Bootstrap Grid

## 🚀 Cómo ejecutar el proyecto
1. Clonar o descargar el repositorio
2. Abrir `index.html` en el navegador
3. Para estilos:
   - Ejecutar `sass scss/main.scss css/main.css --watch`

## 🔗 Repositorio
https://github.com/LaPanchita/mirando-cielos-m3git