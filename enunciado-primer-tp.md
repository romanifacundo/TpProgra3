# Trabajo Práctico - Parcial 1

**Sitio Web Institucional para una Empresa Ficticia**

---

## Contexto

Una empresa ficticia está lanzando su sitio web institucional y necesita una maqueta visual que represente su identidad, sus productos y una vía de contacto o interacción. Como parte del equipo de diseño, se te encomienda el desarrollo de un prototipo funcional compuesto por **tres páginas** enlazadas entre sí. La prioridad está en el diseño, estructura y estilos, por lo que no se requiere funcionalidad con JavaScript.

---

## Objetivo general

Crear un sitio web estático compuesto por **tres páginas HTML enlazadas**, utilizando exclusivamente **HTML y CSS**, respetando criterios de diseño profesional, limpieza visual y correcta estructura semántica.

---

## Páginas requeridas

### ✅ 1. Página principal

Esta página será la **cara institucional** del sitio. Debe contener:

- Encabezado con el nombre o logo de la empresa y un menú de navegación.
- Una sección descriptiva sobre la empresa (quiénes somos, misión, visión o historia).
- Otra sección que mencione sus servicios o áreas de trabajo.
- Un pie de página con información de contacto.
- Estilo limpio, colores armónicos, uso de grillas o flexbox para organizar la información.

---

### ✅ 2. Página de productos

Esta página muestra productos ofrecidos por la empresa. Debe incluir:

- Encabezado y pie de página similares a los de la página principal.
- Un área de **búsqueda o filtrado visual** (no funcional) con un campo de texto y un ícono (puede ser una imagen o emoji).
- Un listado de al menos **tres productos** en forma de **cards o cajas**, cada una con:
  - Nombre del producto
  - Descripción breve
  - Precio
  - Botón simulado de “Comprar”
- Las cards deben estar ordenadas horizontal o verticalmente con un diseño atractivo.

---

### ✅ 3. Página de formulario

Esta página debe incluir un **formulario** sencillo para completar datos. Puede ser sobre:

- Contratación de un servicio
- Pedido de presupuesto
- Registro para una newsletter
- O cualquier otra idea vinculada a la temática de la empresa

El formulario debe tener:

- Campos de texto con etiquetas asociadas
- Selectores (`<select>`)
- Casillas de verificación (`checkbox`)
- Al menos un campo deshabilitado y uno obligatorio
- Diseño estilizado usando clases CSS, márgenes, paddings y colores

---

## Aspectos comunes a todas las páginas

- Deben compartir una misma estética y estructura general (`header`, `main`, `footer`).
- El **menú de navegación** debe estar presente en las tres páginas y permitir navegar entre ellas.
- Usar etiquetas semánticas apropiadas (`<header>`, `<main>`, `<footer>`, `<section>`, `<article>`, etc.).
- El diseño debe estar contenido en una grilla o estructura centrada y ordenada.
- Se requiere diseño responsive, se valora una estructura adaptable básica.
- Los estilos pueden estar incluidos dentro del mismo archivo HTML (`<style>`) o en un archivo `.css` externo.

---

## Modalidad de entrega

La entrega será a través del grupo de WhatsApp del curso con el siguiente formato:

- Nombre y Apellido
- Link del repositorio (GitHub, GitLab, etc.)
- Link del despliegue (Netlify, GitHub Pages, Vercel, etc.)

Fecha límite de entrega: **Domingo 25/05/2025, 23:59hs**

---

## Recomendación de estructura de carpetas y archivos

```plaintext
/mi-sitio/
│
├── index.html
├── productos.html
├── formulario.html
├── estilos.css
├── /img/
│   └── logo.png
│   └── icono_busqueda.png
└── /assets/
    └── fuentes/
    └── extras/
```

## Criterios de evaluación

- Estructura y uso correcto de etiquetas HTML
- Responsividad básica
- Aplicación coherente y organizada de estilos CSS
- Navegación entre páginas funcional
- Diseño visual limpio, alineado y legible
- Formularios y componentes bien presentados
- Legibilidad y orden del código (indentación, clases)
- Uso de comentarios en el código
