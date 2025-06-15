# GSAP Scroll Animation Demo

![Demo del proyecto](./screenshot1.png)
![Animación en acción](./screenshot2.png)

Este proyecto es una demostración del uso de GSAP y ScrollTrigger para crear animaciones avanzadas basadas en el scroll. El objetivo principal fue animar la opacidad y escala de un título (`h1`) y renderizar una secuencia de imágenes sincronizadas con el desplazamiento de la página.

## ¿Qué aprendí?

- **GSAP y ScrollTrigger**: Aprendí a utilizar la librería GSAP junto con su plugin ScrollTrigger para vincular animaciones a la posición del scroll, logrando efectos visuales modernos y fluidos.
- **Importancia del Scroll**: El scroll permite que las animaciones sean interactivas y respondan al usuario, haciendo la experiencia mucho más atractiva.
- **Línea del tiempo (Timeline)**: Usar timelines en GSAP ayuda a coordinar múltiples animaciones y a mantener el control sobre la secuencia de efectos.
- **El parámetro `scrub`**: Descubrí que el parámetro `scrub` es fundamental para que la animación reaccione de forma suave tanto al avanzar como al retroceder el scroll. Sin `scrub`, la animación solo se dispara una vez y no responde igual al volver atrás, perdiendo la sincronización con el desplazamiento.

## Cómo funciona

- El título principal aparece con un efecto de fade-in y luego desaparece al hacer scroll, gracias a GSAP y ScrollTrigger.
- Un canvas renderiza una secuencia de imágenes que simulan una animación fluida, también controlada por el scroll.

## Capturas de pantalla

_Agrega aquí tus propias capturas de pantalla del proyecto en acción:_

- `screenshot1.png`: Vista inicial del título y canvas.
- `screenshot2.png`: Animación avanzada tras hacer scroll.

---
