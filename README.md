# Adventor — Landing de Turismo de Aventura

Landing page moderna de turismo de aventura construida con **Astro** y **Tailwind CSS**. Incluye hero a pantalla completa, navbar transparente con menú móvil, sección de actividades y footer profesional.

## 🛠️ Stack

- [Astro](https://astro.build)
- [Tailwind CSS](https://tailwindcss.com)
- TypeScript

## 📁 Estructura del proyecto

```text
/
├── public/
│   ├── favicon.svg
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── ActivityCard.astro   # Tarjeta de actividad (imagen circular, título, descripción, botón)
│   │   ├── Footer.astro         # Footer con enlaces, contacto y redes sociales
│   │   ├── Hero.astro           # Hero full-width con imagen de cascada
│   │   ├── Navbar.astro         # Navbar transparente + menú móvil
│   │   ├── SectionTitle.astro   # Título de sección con texto de acento
│   │   └── WaveDivider.astro    # Divisor ondulado entre secciones
│   ├── layouts/
│   │   └── Layout.astro         # Layout base (Navbar + slot + Footer)
│   ├── pages/
│   │   └── index.astro          # Página principal
│   └── styles/
│       └── global.css           # Estilos globales y Tailwind
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## ✨ Contenido

- **Hero:** Imagen de cascada (Unsplash), overlay oscuro, título "Adventure Travel" y botón "View Adventures".
- **Navbar:** Transparente sobre el hero; al hacer scroll aplica fondo oscuro con blur. Enlaces: Home, About, Tours, Adventures, Blog, Contact. Menú hamburguesa en móvil con overlay a pantalla completa.
- **Adventure Ideas:** Grid responsive de 4 actividades (Zip Lines, Kayaking, Bungee Jump, Canoeing) con imágenes circulares y botón "Explore".
- **Footer:** Brand, Quick Links, Adventures, Contact (email, teléfono, Santiago Chile), iconos de redes (Facebook, Instagram, Twitter, YouTube) y barra de copyright.

## 🚀 Comandos

Desde la raíz del proyecto:

| Comando           | Acción                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Instala dependencias                        |
| `npm run dev`     | Servidor de desarrollo en `localhost:4321`  |
| `npm run build`   | Genera el sitio en `./dist/`                |
| `npm run preview` | Previsualiza el build antes de desplegar   |

## 📄 Licencia

Proyecto de ejemplo. © 2026 Adventor Travel.
