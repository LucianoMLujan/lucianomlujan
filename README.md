# Luciano Luján — Portfolio

Desarrollador Full Stack | Portfolio personal construido con Astro

## Preview

[![Preview](https://img.shields.io/badge/Ver%20Portfolio-en%20línea-blue?style=for-the-badge)](https://tu-url-aqui.vercel.app)

## Stack

- **Framework:** [Astro](https://astro.build/)
- **Estilos:** [Tailwind CSS](https://tailwindcss.com/)
- **Lenguaje:** [TypeScript](https://www.typescriptlang.org/)

## Inicio rápido

```bash
# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev

# Build de producción
pnpm build

# Vista previa del build
pnpm preview
```

El servidor de desarrollo estará disponible en `http://localhost:4321`.

## Estructura del proyecto

```text
/
├── public/
│   └── images/
├── src/
│   ├── components/
│   │   ├── Contact.astro
│   │   ├── Education.astro
│   │   ├── Experience.astro
│   │   ├── Hero.astro
│   │   ├── Navbar.astro
│   │   └── Skills.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
└── package.json
```

## Secciones

| Sección | Descripción |
|---------|-------------|
| **Hero** | Presentación principal con nombre, título y foto de perfil |
| **Experiencia** | Timeline de experiencia laboral |
| **Habilidades** | Grid de tecnologías con iconos e interacciones |
| **Educación** | Formación académica y certificaciones |
| **Contacto** | Información de contacto y enlaces a redes sociales |

## Despliegue

Este proyecto está configurado para desplegarse en [Vercel](https://vercel.com) o [Netlify](https://netlify.com). Simplemente conecta tu repositorio y se desplegará automáticamente.

## Licencia

MIT
