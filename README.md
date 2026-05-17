# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS (Flexbox)
- Mobile-first responsive design

### What I learned

Aprendí cómo usar **Flexbox para centrar elementos** correctamente. El punto clave fue entender que:

```css
.pattern {
  display: flex;
  align-items: center;      /* Centra verticalmente */
  justify-content: center;  /* Centra horizontalmente */
  height: 100vh;           /* Altura completa de la pantalla */
}
```

- `justify-content` centra el contenido en el eje horizontal
- `align-items` centra el contenido en el eje vertical
- El contenedor padre debe tener una altura definida (como `100vh`) para que el centrado vertical funcione
- `gap` es útil para espaciar elementos hijos
- Usar `max-width` ayuda a mantener el diseño responsive

### Continued development

En futuros proyectos quiero:
- Practicar más con Flexbox y Grid para layouts complejos
- Agregar animaciones y transiciones CSS
- Mejorar el diseño responsive para más puntos de corte (tablets, móviles)
- Explorar más sobre accesibilidad (contrast, focus states)
- Trabajar con variables CSS (custom properties) para temas reutilizables

### Useful resources

- [MDN - Flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout) - Referencia completa sobre Flexbox
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Guía visual excelente
- [Frontend Mentor - Learning Paths](https://www.frontendmentor.io/learning-paths) - Ruta de aprendizaje estructurada

### AI Collaboration

- **Herramienta:** GitHub Copilot
- **Cómo la usé:**
  - Guía conceptual sobre Flexbox y centrado de elementos
  - Explicación del problema (por qué el centrado no funcionaba sin altura)
  - Feedback mientras trabajaba en el proyecto
- **Qué funcionó bien:**
  - Las explicaciones paso a paso ayudaron a entender el concepto
  - Me permitió aprender sin que me dieran la solución directa
- **Lecciones:** Trabajar con AI es mejor cuando haces las preguntas correctas y entiendes los conceptos, no solo copias código

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [Your GitHub](https://www.github.com/yourusername)

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io) - Por el desafío y el diseño
- GitHub Copilot - Por la guía y mentoring durante el desarrollo
