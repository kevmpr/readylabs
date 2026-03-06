# ReadyLabs Landing Page

ReadyLabs es un hub de contenidos técnicos para mentes inquietas, creado por **Readymind**. Esta landing page está diseñada para presentar la iniciativa, el manifiesto, los artículos semanales, el equipo de arquitectos y próximos eventos interactivos (webinars).

## 🚀 Características Principales

- **Astro**: Framework web ultrarrápido para sitios impulsados por contenido.
- **Tailwind CSS**: Framework de utilidades CSS, configurado mediante el plugin de Vite para Astro.
- **Theming (Dark/Light Mode)**: Soporte completo e integrado para modo claro y oscuro, con persistencia local y soporte para cambio desde la barra de navegación.
- **Animaciones y Efectos Visuales**:
  - Animaciones de *scroll reveal* (Intersection Observer) para que las secciones aparezcan fluidamente.
  - Diseños *glassmorphism*, brillos pulsantes, gradientes animados y orbes de fondo.
  - Menú de navegación fijo con *backdrop-blur*.
  - Desplazamiento suave (smooth scrolling) para enlaces internos.
- **Gestión de Contenidos**:
  - Utiliza colecciones de contenido de Astro (`src/content/`) para renderizar dinámicamente el *roadmap* de artículos.
- **Webinar interactivo**:
  - Temporizador (cuenta regresiva) animado y links directos a Teams y YouTube.

## 📁 Estructura del Proyecto

```text
/
├── public/                 # Archivos estáticos como fuentes (.otf) y favicons
├── src/
│   ├── assets/images/      # Imágenes y recursos estáticos importados directamente (logos, perfiles)
│   ├── components/         # Componentes UI de Astro (Hero.astro, Manifesto.astro, etc.)
│   ├── content/            # Colecciones de contenido (Markdown/MDX para artículos)
│   ├── layouts/            # Layout principal (Layout.astro) - Define la estructura HTML base y SEO
│   ├── pages/              # Rutas de la aplicación (index.astro as the landing page)
│   └── styles/             # Estilos globales (global.css) - Define fuentes, colores CSS y keyframes
├── astro.config.mjs        # Configuración de integraciones de Astro (Tailwind, React)
├── package.json            # Dependencias del proyecto
└── tsconfig.json           # Configuración de TypeScript
```

## 🛠️ Requisitos Previos

- [Node.js](https://nodejs.org/) (versión 18+ recomendada)
- Un manejador de paquetes de Node (`npm`, `yarn`, o `pnpm`)

## 🧞 Comenzando (Comandos y Scripts)

Abre una terminal en la raíz del proyecto y ejecuta los siguientes comandos:

| Comando                   | Acción                                                          |
| :------------------------ | :-------------------------------------------------------------- |
| `npm install`             | Instala todas las dependencias necesarias.                      |
| `npm run dev`             | Inicia el servidor de desarrollo local (usualmente `localhost:4321`). |
| `npm run build`           | Genera el sitio preparado y optimizado para producción en `./dist/`. |
| `npm run preview`         | Sirve localmente los archivos compilados generados en la carpeta `dist`. |
| `npm run astro`           | Ejecutable de la CLI de Astro para tareas adicionales.          |

## 🎨 Diseño y Marca

El sitio respeta firmemente la identidad visual de **ReadyLabs**:
- **Paleta de colores**: Tonos oscuros para los fondos principales (Lab Dark) combinados con acentos vibrantes de Neón (Azure, Spring Green, Rosa Lacerante, Lime Yellow). Adaptación de estos tonos para la versión de "Modo Claro" con contrastes optimizados.
- **Tipografías**: 
  - Primaria: **Aeonik** (moderna y limpia).
  - Secundaria/Acento: **Strokey** (para textos destacados en gradiente).

---
*Curiosidad sobre certeza. 2026 Readymind.*
