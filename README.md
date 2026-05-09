# 🕹️ Neon Snake Arcade - Retro Synthwave Edition

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

Una reinterpretación moderna y con estética **Neon/Synthwave** del clásico juego "Snake" (culebrita), desarrollada puramente con **Vanilla JavaScript** y **HTML5 Canvas API**. Este proyecto demuestra el uso de lógica de videojuegos, manipulación de estados y renderizado de alto rendimiento sin librerías externas.

---

## 🚀 Demo En Vivo

Puedes jugar directamente en tu navegador aquí:
👉 **[INSERTAR_AQUÍ_TU_LINK_DE_GITHUB_PAGES]**

---

## ✨ Características Principales

- **Gráficos de Alto Rendimiento:** Renderizado optimizado a 60 FPS mediante `requestAnimationFrame`.
- **Estética Cyberpunk:** Efectos de resplandor (Glow), líneas de escaneo CRT y paleta de colores neón.
- **Sistema de Partículas:** Explosiones visuales al recolectar comida para mejorar la experiencia de juego (Juiciness).
- **Dificultad Progresiva:** La velocidad aumenta automáticamente conforme aumenta la puntuación.
- **Persistencia de Datos:** Guardado de High Score local mediante `localStorage`.
- **Diseño Responsive:** Adaptable a diferentes tamaños de pantalla.

---

## 🛠️ Stack Tecnológico

- **Frontend:** HTML5 (Canvas) & CSS3 (Flexbox, CSS Variables).
- **Lógica:** Vanilla JavaScript (ES6+).
- **Arquitectura:** Patrón de diseño *Game Loop* funcional-orientado a objetos.

---

## 🎮 Cómo Jugar

1.  **Iniciar:** Haz clic en el botón "INSERT COIN" o "START".
2.  **Movimiento:** 
    - ⬆️ / **W**: Arriba
    - ⬇️ / **S**: Abajo
    - ⬅️ / **A**: Izquierda
    - ➡️ / **D**: Derecha
3.  **Objetivo:** Come los orbes rosas para crecer y ganar puntos. Evita chocar contra las paredes o contra tu propio cuerpo.

---

## 🧠 Detalles Técnicos (Nivel Senior)

El motor del juego se basa en tres pilares fundamentales:

1.  **El Sistema de Grillas:** El tablero se divide en unidades lógicas (tiles) de 20px, permitiendo una detección de colisiones AABB (Axis-Aligned Bounding Box) simplificada y eficiente.
2.  **Gestión de Memoria:** El cuerpo de la serpiente es un `Array` de coordenadas. En cada frame, se añade una nueva cabeza (`unshift`) y se elimina la cola (`pop`), optimizando el uso de memoria.
3.  **Efectos Visuales:** El resplandor se logra mediante la propiedad `shadowBlur` del contexto 2D de Canvas, aplicada selectivamente para no comprometer el rendimiento.

---

## ⚙️ Instalación Local

Si deseas modificar o estudiar el código:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/neon-snake-arcade.git# JuegoArcade
juego arcade culebrita
