# Tarjetas con Efecto Morfismo de Vidrio

## 1) Descripción del Proyecto

Proyecto de ejemplo que muestra un conjunto de tarjetas con efecto "glassmorphism" (morfismo de vidrio) y microinteracciones al pasar el cursor. Está implementado con HTML y CSS.
Las tarjetas usan fondos semitransparentes, desenfoque de fondo y animaciones sencillas para lograr una apariencia moderna y elegante.

## 2) Conceptos CSS aplicados

- **background: rgba(...)**: crea fondos semitransparentes que permiten ver elementos detrás de la tarjeta.
- **backdrop-filter / -webkit-backdrop-filter**: aplica un desenfoque (blur) al contenido que queda detrás del elemento, clave para el efecto de vidrio.
- **box-shadow**: añade sombras alrededor de las tarjetas para generar profundidad (elevación visual).
- **border-radius**: redondea las esquinas de las tarjetas y las imágenes para un aspecto suave.
- **transition**: suaviza los cambios (por ejemplo transformaciones al hacer hover) para una interacción agradable.
- **transform (translate, scale, rotate)**: mueve o escala elementos en hover y en animaciones (por ejemplo, elevar la tarjeta o aumentar la imagen de portada).
- **overflow: hidden**: recorta el contenido (como imágenes) dentro de contenedores con bordes redondeados.
- **position (absolute, fixed, relative)**: posiciona elementos decorativos (triángulos) y centra el layout.
- **display: flex / flex-wrap / justify-content**: organiza las tarjetas responsivamente en filas y centra su contenido.
- **@keyframes / animation**: define y aplica animaciones continuas a los elementos decorativos del fondo.
- **background: linear-gradient(...)**: genera degradados de color usados en las formas de fondo para mayor contraste visual.
- **@media queries**: ajustan la disposición y el posicionamiento para pantallas más pequeñas (responsive).

---
