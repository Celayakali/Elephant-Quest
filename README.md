<p align="center">
  🐘
</p>
<h1 align="center">Elephant Quest</h1>
<p align="center">
  <b>Un juego de plataformas 2D protagonizado por un elefante a dos patas</b><br>
  5 mundos · 3 niveles por mundo · 100% HTML5 · Sin instalación
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Canvas-API-orange?style=for-the-badge" alt="Canvas API">
</p>

---

## 🎮 ¿Qué es Elephant Quest?

**Elephant Quest** es un juego de plataformas 2D inspirado en los clásicos de *Super Mario*, pero con un giro único: en lugar de un fontanero, controlas a un **adorable elefante que camina sobre dos patas**.

Tu misión es guiarlo a través de **5 mundos temáticos**, cada uno con **3 niveles**, físicas distintas, enemigos por derrotar y coleccionables que suman puntos. Todo dibujado con código, sin imágenes externas, y listo para jugar en cualquier navegador.

> ⚡ **Zero dependencias. Zero instalación. Solo abre y juega.**

---

## 🌍 Los 5 Mundos

| Mundo | Nombre | Dificultad | Física especial |
|:-----:|--------|:----------:|-----------------|
| 🌿 | **Pradera Verde** | Fácil | Gravedad normal |
| 🏜️ | **Desierto Dorado** | Media | Enemigos más rápidos |
| ❄️ | **Nieve Helada** | Media | Hielo resbaladizo, gravedad ligera |
| 🌋 | **Volcán Ardiente** | Difícil | Gravedad pesada, salto potente |
| 🌌 | **Espacio Estelar** | Experto | Gravedad lunar baja |

Cada mundo tiene su propia paleta de colores, efectos de partículas (nieve, brasa, estrellas), enemigos únicos y mecánicas de plataformas diseñadas para retarte de forma diferente.

---

## 🚀 Cómo jugar

### Opción 1: Abrir localmente
1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` con tu navegador (Chrome, Firefox, Edge...).
3. Selecciona un mundo en el menú principal.
4. ¡Pulsa **ESPACIO** o toca la pantalla para empezar!

### Opción 2: GitHub Pages (si lo activas)
Si publicas este repo con GitHub Pages, podrás jugar directamente desde cualquier dispositivo con un enlace web.

---

## 🕹️ Controles

| Acción | Teclado | Móvil / Tablet |
|--------|---------|----------------|
| Mover izquierda | `←` o `A` | Botón `←` |
| Mover derecha | `→` o `D` | Botón `→` |
| Saltar | `ESPACIO`, `↑` o `W` | Botón `↑` |

&gt; 💡 **Truco:** ¡Puedes eliminar enemigos saltando encima de ellos! Si caes sobre un enemigo desde arriba, lo derrotas y ganas **+50 puntos**. Pero si chocas por los lados, perderás una vida.

---

## 📁 Estructura del proyecto


Cada archivo `.html` es **completamente autónomo**: contiene el HTML, CSS y JavaScript necesarios para funcionar. No requiere conexión a internet ni bibliotecas externas.

---

## ✨ Características

- 🎨 **Gráficos vectoriales 100% código** — sin imágenes externas, carga ultrarrápida.
- 🎵 **Sonidos generados proceduralmente** — saltos, monedas, daño y victoria.
- 📱 **Controles táctiles automáticos** — se detectan dispositivos móviles y aparecen botones en pantalla.
- 💾 **Progreso guardado** — usa `localStorage` para recordar qué niveles has completado.
- 🎯 **Físicas distintas por mundo** — cada entorno se siente diferente.
- 🖥️ **Cámara dinámica** — sigue al personaje con suavidad.
- ✨ **Sistema de partículas** — efectos visuales al saltar, recolectar y derrotar enemigos.

---

## 🛠️ Tecnologías utilizadas

- **HTML5 Canvas** — renderizado de gráficos 2D.
- **JavaScript (ES6)** — lógica del juego, físicas, colisiones y estados.
- **CSS3** — interfaz de usuario, controles táctiles y diseño responsive.
- **Web Audio API** — generación de sonidos en tiempo real.

---

## 📸 Capturas de pantalla

> *(Próximamente: añade aquí tus propias capturas de pantalla del juego para que luzca aún mejor en GitHub)*

---

## 📝 Notas para desarrolladores

- El juego está diseñado para ser lo más **sencillo y portable** posible: un solo archivo HTML por mundo.
- Las físicas (gravedad, fricción, velocidad) se definen como constantes al inicio de cada script, facilitando el ajuste de dificultad.
- Los niveles se almacenan como objetos JSON dentro de cada archivo, por lo que añadir nuevas plataformas, monedas o enemigos es tan fácil como editar un array.

---

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de modificarlo, ampliarlo o usarlo como base para tu propio juego.

---

<p align="center">
  <b>¡Gracias por jugar Elephant Quest!</b> 🐘✨<br>
  Si te gusta el proyecto, no olvides dejar una ⭐ en el repositorio.
</p>
