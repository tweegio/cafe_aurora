# Café Aurora — Sitio Web

Maqueta web completa para una cafetería ficticia. Proyecto de desarrollo frontend que abarca el ciclo completo de un sitio para un negocio gastronómico: identidad visual, múltiples páginas, sistema de reservas, menú interactivo y formulario de contacto con backend en PHP.

🔗 **Demo en vivo:** [tweegio.github.io/cafe_aurora](https://tweegio.github.io/cafe_aurora/)

---

## Vista previa

![Café Aurora Preview](img/carousel-1.jpg)

---

## Sobre el proyecto

Café Aurora es una maqueta funcional orientada a demostrar la capacidad de desarrollar un sitio web completo para un cliente del rubro gastronómico. Incluye todas las secciones típicas de un negocio de este tipo — presentación, menú, reservas, testimonios y contacto — con un diseño responsivo, carousel animado y flujos de usuario pensados para conversión.

---

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Landing principal con hero carousel, servicios, menú destacado y cupón de cumpleaños |
| `nosotros.html` | Historia y visión de la cafetería |
| `menu.html` | Carta completa — cafés calientes y fríos |
| `servicio.html` | Detalle de servicios: delivery, granos frescos, reservas |
| `reservas.html` | Sistema de reserva de mesa online con selector de personas |
| `testimonio.html` | Reseñas de clientes |
| `contacto.html` | Formulario de contacto con envío por PHP |

---

## Tecnologías utilizadas

- **HTML5** — estructura semántica multi-página
- **CSS3 + SCSS** — estilos con preprocesador, variables y componentes reutilizables
- **JavaScript** — carousel, interacciones del menú y validaciones de formulario
- **PHP** — backend mínimo para el envío del formulario de contacto vía email
- **GitHub Pages** — deploy del sitio estático

---

## Funcionalidades

- **Carousel hero** animado con imágenes y textos bilingües (ES/EN)
- **Menú de cafés** categorizado (calientes / fríos) con imágenes y descripción
- **Sistema de reservas** con selector de cantidad de personas y confirmación
- **Cupón de descuento** — 35% OFF para cumpleaños mediante formulario de suscripción
- **Promoción de reserva online** — 20% OFF integrado en la sección de reservas
- **Sección de testimonios** con carrusel de reseñas de clientes
- **Formulario de contacto** con envío real vía PHP (`/mail/`)
- **Newsletter** — suscripción de novedades en el footer
- **Diseño responsivo** — adaptado a mobile, tablet y desktop
- **Menú de navegación** con submenú desplegable para páginas secundarias

---

## Estructura del proyecto

```
cafe_aurora/
├── index.html
├── nosotros.html
├── menu.html
├── servicio.html
├── reservas.html
├── testimonio.html
├── contacto.html
│
├── css/
│   └── styles.css          ← CSS compilado
├── scss/
│   └── styles.scss         ← Fuente SCSS con variables y componentes
├── js/
│   └── main.js             ← Carousel, interacciones, validaciones
├── lib/                    ← Librerías externas (carousel, etc.)
├── img/                    ← Imágenes del sitio
└── mail/                   ← Script PHP para envío de formulario
```

---

## Decisiones técnicas

**SCSS como sistema de estilos.** En lugar de CSS plano, se usó SCSS para organizar los estilos por componentes, aprovechar variables de color y tipografía, y facilitar el mantenimiento. Esto refleja un flujo de trabajo más cercano al desarrollo profesional real.

**Sitio multi-página con navegación consistente.** Cada sección es una página HTML independiente, con nav y footer compartidos. Elegí esta arquitectura en lugar de un SPA para mantener compatibilidad total con GitHub Pages y URLs semánticas por sección.

**PHP para el formulario de contacto.** El formulario de contacto usa un script PHP en `/mail/` para el envío real de emails. Aunque el hosting en GitHub Pages no ejecuta PHP, la integración demuestra conocimiento del flujo completo cliente-servidor en proyectos reales.

**Carousel implementado con librería.** En lugar de codear el carousel desde cero, se integró una librería externa desde `/lib/`, priorizando el resultado visual y la estabilidad sobre la reinvención de una funcionalidad estándar.

---

## Cómo correrlo localmente

```bash
git clone https://github.com/tweegio/cafe_aurora.git
cd cafe_aurora
# Abrí index.html en tu navegador o usá Live Server en VS Code
```

> Para que el formulario de contacto funcione, necesitás un servidor con soporte PHP (XAMPP, WAMP, o hosting compartido).

---

## Autor

**Sergio Pereira** — Desarrollador Front-End & Técnico Informático

- 🌐 [Portfolio](https://tweegio.github.io/Portafolio_sergio_pereira/)
- 💼 [LinkedIn](https://www.linkedin.com/in/sergio-pereira-development/)
- 🐙 [GitHub](https://github.com/tweegio)

---

*© 2024 Tweegio*
