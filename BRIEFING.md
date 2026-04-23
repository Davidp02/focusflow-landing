# Proyecto 1 — Landing Page "FocusFlow"

## Contexto

Vas a construir la landing page de un producto SaaS ficticio llamado **FocusFlow**: una app que ayuda a profesionales a gestionar su tiempo usando técnicas como Pomodoro, bloqueo de distracciones y análisis de hábitos.

Este proyecto te va a obligar a dominar las tres tecnologías base (HTML semántico, CSS moderno y JavaScript vanilla) en un escenario realista.

---

## Objetivos de aprendizaje

Al terminar este proyecto debes dominar:

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`, `aside`).
- Accesibilidad básica (labels, alt, roles, contraste).
- CSS Grid y Flexbox combinados.
- Variables CSS (custom properties) y diseño con tokens.
- Media queries y diseño responsive (mobile-first).
- Transiciones y animaciones CSS.
- JavaScript: manejo del DOM, eventos, IntersectionObserver.
- Git: commits atómicos, mensajes claros.
- Publicación en GitHub Pages.

---

## Alcance funcional

### Secciones obligatorias

1. **Navbar** fijo con logo + links + botón CTA. Menú hamburguesa en mobile.
2. **Hero** con titular, subtítulo, dos botones (primario y secundario) y una imagen/ilustración.
3. **Features** con 3–6 tarjetas usando Grid, cada una con ícono, título y descripción.
4. **How it works** con 3 pasos numerados, idealmente con ilustración.
5. **Pricing** con 3 planes en tarjetas (Free, Pro, Team), donde "Pro" está destacado.
6. **Testimonials** con 3 testimonios en formato carrusel o grid.
7. **CTA final** full-width con fondo de color y botón.
8. **Footer** con columnas: producto, empresa, recursos, legal + redes sociales.

### Interacciones con JavaScript

- Menú hamburguesa que abre/cierra en mobile.
- Scroll suave al hacer click en los links del navbar.
- Navbar cambia de estilo (sombra / fondo) al hacer scroll.
- Animación de entrada de secciones al aparecer en viewport (IntersectionObserver).
- Toggle de tema claro/oscuro (bonus).

---

## Reglas del juego

1. **Mobile-first.** Diseña para móvil primero, luego desktop.
2. **Cero frameworks.** Nada de Bootstrap, Tailwind ni librerías JS. Todo vanilla.
3. **Semántica real.** Nada de `<div>` para todo. Cada sección con su tag correcto.
4. **Accesible.** Contraste decente, `alt` en imágenes, focus visible.
5. **Commits atómicos.** Mínimo 10 commits, cada uno con propósito claro.
6. **README.md** explicando qué hace la landing, qué tecnologías usa, capturas y cómo correrla.
7. **Deploy en GitHub Pages** al terminar.

---

## Estructura de archivos sugerida

```
proyecto-01-landing/
├── index.html
├── styles/
│   ├── reset.css
│   ├── variables.css
│   ├── base.css
│   ├── layout.css
│   ├── components.css
│   └── responsive.css
├── scripts/
│   └── main.js
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

---

## Criterios de aprobación

Para pasar a la Fase 2 este proyecto debe cumplir:

- [ ] Se ve bien en móvil (320px), tablet (768px) y desktop (1280px).
- [ ] HTML pasa validación de https://validator.w3.org/.
- [ ] No hay errores en consola.
- [ ] Las animaciones no marean ni rompen el layout.
- [ ] El menú hamburguesa abre y cierra.
- [ ] El scroll suave funciona.
- [ ] El código CSS está organizado en archivos separados, sin repetición obvia.
- [ ] Está en GitHub con README y desplegado en GitHub Pages.

---

## Cómo vamos a trabajar este proyecto

1. **Tú escribes el HTML semántico** de todas las secciones (sin estilos aún). Me lo muestras, yo reviso.
2. **Defines las variables CSS** (colores, tipografía, espaciados). Revisamos que sea un sistema coherente.
3. **Maquetas sección por sección.** Al terminar cada una, me la muestras.
4. **Agregamos el responsive** con media queries.
5. **Agregamos el JavaScript** (menú, scroll, animaciones).
6. **Review final + deploy.**

---

## Tu tarea ahora

Antes de escribir una línea de código, haz un **wireframe** (boceto en papel, Figma o incluso en texto) de cómo se va a ver la landing en mobile y en desktop. Esto evita que programes a ciegas.

Luego, crea el `index.html` con la estructura semántica completa (todas las secciones con sus tags correctos), sin ningún estilo. Solo el esqueleto.

Cuando lo tengas, me dices y lo revisamos juntos antes de pasar al CSS.
