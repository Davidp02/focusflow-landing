# Plan de commits — Proyecto 1 (FocusFlow Landing)

> Convención: `tipo(scope): descripción corta en imperativo`
> Tipos: feat, fix, chore, docs, style, refactor, test

## Fase A — HTML semántico

- [x] `chore: initial project setup with briefing and gitignore`
- [x] `feat(navbar): add semantic header with navbar, hamburger and CTA`
- [x] `feat(hero): add hero section with title, subtitle, CTAs and image`
- [x] `feat(features): add features grid with cards`
- [x] `feat(how-it-works): add three-step process section`
- [x] `feat(pricing): add three-tier pricing section`
- [x] `feat(testimonials): add testimonials section with user quotes`
- [x] `feat(cta): add final call-to-action section`
- [x] `feat(footer): add footer with columns and social links`

## Fase B — CSS base

- [ ] `feat(styles): add css reset and normalization`
- [ ] `feat(styles): add design tokens and css variables`
- [ ] `feat(styles): add base typography and global layout rules`

## Fase C — CSS por componente

- [ ] `feat(navbar): style navbar with mobile-first layout`
- [ ] `feat(hero): style hero with responsive two-column layout`
- [ ] `feat(features): style features grid with cards`
- [ ] `feat(how-it-works): style process steps`
- [ ] `feat(pricing): style pricing tiers with highlighted plan`
- [ ] `feat(testimonials): style testimonial cards`
- [ ] `feat(cta): style final cta section`
- [ ] `feat(footer): style footer columns`

## Fase D — Responsive y animaciones

- [ ] `feat(styles): add responsive breakpoints for tablet and desktop`
- [ ] `feat(styles): add micro-animations and hover transitions`

## Fase E — JavaScript

- [ ] `feat(navbar): add mobile menu toggle with aria updates`
- [ ] `feat(nav): add smooth scroll to anchor links`
- [ ] `feat(navbar): add scrolled state with shadow on scroll`
- [ ] `feat(animations): add intersection observer for section reveals`

## Fase F — Deploy

- [ ] `docs: add readme with project description and tech stack`
- [ ] `chore: configure github pages deployment`

---

## Commits "extra" que aparecen en el camino

Según surjan, úsalos:

- `fix(<scope>): <qué arreglaste>` — cualquier bug arreglado.
- `refactor(<scope>): <qué reorganizaste>` — cambio de estructura sin cambio de comportamiento.
- `style: <qué formateaste>` — cambios puramente de formato (sin lógica).
- `docs: <qué documentaste>` — actualizaciones del README u otros docs.
- `chore: <qué mantuviste>` — config, dependencias, gitignore.

---

## Reglas

1. Un commit = una unidad lógica. Si dudas, divide.
2. Mensajes siempre en imperativo ("add", no "added" ni "adds").
3. Minúsculas excepto para nombres propios.
4. Sin punto al final del mensaje.
5. Usa `--amend` para corregir el último commit si aún no lo pusheaste.
6. `git push` después de cada commit o en grupos pequeños.
