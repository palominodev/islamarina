# Isla Marina - Sitio Web del Restaurante

Este proyecto es el sitio web para el restaurante de comida peruana "Isla Marina". Ha sido desarrollado utilizando Astro y Tailwind CSS para crear una experiencia web moderna, rápida y responsiva.

El sitio web ha sido desarrollado por [PIXEL CEVICHE](https://pixelceviche.vercel.app).

## ✨ Características Principales

*   **Diseño Responsivo:** Adaptado para visualizarse correctamente en dispositivos móviles, tablets y de escritorio.
*   **Componentes Reutilizables:** Construido con componentes de Astro para una mejor organización y mantenimiento (`Header`, `Dialog`).
*   **Navegación Intuitiva:** Encabezado fijo con enlaces a las secciones principales (Carta, Ubicación, Historia) y menú desplegable para móviles.
*   **Modal de Créditos:** Un diálogo modal que aparece al cargar la página, indicando el desarrollador del sitio (PIXEL CEVICHE).
*   **Estilizado con Tailwind CSS:** Utilización del framework de CSS Tailwind para un diseño rápido y consistente.
*   **Optimización de Imágenes:** Uso de `astro:assets` para optimizar las imágenes del sitio.

## 🚀 Estructura del Proyecto

El proyecto sigue la estructura estándar de Astro:

```text
/
├── public/             # Archivos estáticos (favicon, etc.)
│   └── ...
├── src/
│   ├── assets/         # Imágenes y otros recursos
│   │   └── images/
│   ├── components/     # Componentes reutilizables de Astro (.astro)
│   │   ├── sections/   # Componentes de secciones (Header, etc.)
│   │   └── Dialog.astro
│   ├── layouts/        # Layouts base de las páginas (.astro)
│   │   └── Layout.astro
│   ├── pages/          # Páginas del sitio (.astro)
│   │   └── index.astro
│   └── styles/         # Archivos de estilos globales (.css)
│       └── global.css
└── package.json        # Dependencias y scripts del proyecto
└── tailwind.config.mjs # Configuración de Tailwind CSS
└── tsconfig.json       # Configuración de TypeScript
```

Para más detalles sobre la estructura, consulta la [guía de estructura de proyectos de Astro](https://docs.astro.build/es/basics/project-structure/).

## 🧞 Comandos Disponibles

Todos los comandos se ejecutan desde la raíz del proyecto en una terminal:

| Comando             | Acción                                                     |
| :------------------ | :--------------------------------------------------------- |
| `npm install`       | Instala las dependencias del proyecto.                     |
| `npm run dev`       | Inicia el servidor de desarrollo local en `localhost:4321`. |
| `npm run build`     | Compila el sitio para producción en la carpeta `./dist/`.   |
| `npm run preview`   | Previsualiza la compilación de producción localmente.      |
| `npm run astro ...` | Ejecuta comandos CLI de Astro (`astro add`, `astro check`). |

## 💻 Tecnologías Utilizadas

*   **Framework:** [Astro](https://astro.build/)
*   **Estilos:** [Tailwind CSS](https://tailwindcss.com/)
*   **Despliegue:** (Especificar plataforma si se conoce, ej. Vercel, Netlify)

## 📄 Licencia

(Especificar tipo de licencia si aplica, ej. MIT, reservado, etc.)

## 👨‍💻 Créditos

Desarrollado con ❤️ por [PIXEL CEVICHE](https://pixelceviche.vercel.app).
