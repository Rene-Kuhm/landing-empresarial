# 🚀 Landing Empresarial - Agencia de Desarrollo Web

> Landing page profesional y moderna construida con Astro, TypeScript y Tailwind CSS

[![Astro](https://img.shields.io/badge/Astro-5.16-orange?logo=astro)](https://astro.build/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-38BDF8?logo=tailwind-css)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## ✨ Características

### 🎨 **Diseño Moderno**
- Diseño responsive con mobile-first approach
- Animaciones suaves y micro-interacciones
- Gradientes y efectos visuales profesionales
- Sistema de colores consistente

### ⚡ **Performance Optimizado**
- **100/100 Lighthouse Score** (objetivo)
- Lazy loading de imágenes y componentes
- CSS y JavaScript minificados
- Fonts optimizadas con preload

### 🔧 **Tecnologías de Vanguardia**
- **Astro 5.16+** - Framework web moderno
- **TypeScript Strict Mode** - Tipado estricto
- **Tailwind CSS 4.x** - Utility-first CSS
- **Biome** - Linting y formatting moderno

### 📱 **SEO & Accesibilidad**
- Meta tags optimizados para SEO
- Open Graph y Twitter Cards
- Schema.org structured data
- ARIA labels y navegación por teclado
- Canonical URLs y sitemaps

## 🚦 Quick Start

```bash
# Clonar el repositorio
git clone https://github.com/Rene-Kuhm/landing-empresarial.git
cd landing-empresarial

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Previsualizar build
npm run preview
```

## 📂 Estructura del Proyecto

```
📦 landing-empresarial/
├── 📁 public/
│   ├── 🖼️ favicon.svg
│   └── 🖼️ og-image.jpg
├── 📁 src/
│   ├── 📁 components/
│   │   ├── 🧩 Header.astro       # Navegación principal
│   │   ├── 🧩 Hero.astro         # Sección hero
│   │   ├── 🧩 Services.astro     # Servicios ofrecidos
│   │   └── 🧩 Footer.astro       # Pie de página
│   ├── 📁 layouts/
│   │   └── 📄 Layout.astro       # Layout principal con SEO
│   ├── 📁 pages/
│   │   └── 📄 index.astro        # Página principal
│   └── 📁 styles/
│       └── 🎨 global.css         # Estilos globales
├── ⚙️ astro.config.mjs           # Configuración Astro
├── ⚙️ tailwind.config.mjs        # Configuración Tailwind
├── ⚙️ tsconfig.json              # Configuración TypeScript
└── ⚙️ biome.json                 # Configuración Biome
```

## 🧩 Componentes

### 📋 **Header**
- Navegación responsive con menú hamburguesa
- Smooth scroll a secciones
- CTA button prominente
- Estado activo en scroll

### 🦸 **Hero**
- Gradientes de fondo animados
- Texto con gradientes
- Botones CTA con hover effects
- Mock-up de código animado
- Estadísticas destacadas

### 💼 **Services**
- Grid responsive de servicios
- Cards con hover effects
- Iconos de Lucide
- Lista de características
- Colores categorizados

### 🦶 **Footer**
- Enlaces organizados por categorías
- Información de contacto
- Newsletter subscription
- Redes sociales
- Back to top button

## 🎨 Customización

### Colores
```css
/* Paleta principal */
:root {
  --blue-600: #2563eb;
  --purple-600: #9333ea;
  --gray-900: #111827;
}
```

### Tipografía
```css
/* Fuente principal */
font-family: 'Inter', system-ui, sans-serif;
```

### Animaciones
```css
/* Clases de utilidad */
.animate-fade-in-up { /* Fade in desde abajo */ }
.animate-slide-left { /* Slide desde la derecha */ }
.text-gradient { /* Texto con gradiente */ }
```

## 📜 Scripts Disponibles

```bash
# Desarrollo
npm run dev          # Servidor de desarrollo
npm run build        # Build para producción
npm run preview      # Preview del build

# Calidad de código
npm run lint         # Lint con Biome
npm run lint:fix     # Fix automático de lint
npm run format       # Format código
npm run check        # Lint + format
npm run type-check   # Type checking TypeScript
```

## 📈 Performance

### Métricas Objetivo
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **Time to Interactive**: < 3s

### Optimizaciones Implementadas
- ✅ Componentes estáticos por defecto
- ✅ CSS crítico inline
- ✅ Lazy loading de imágenes
- ✅ Preload de fuentes
- ✅ Minificación de assets
- ✅ Compression gzip/brotli

## 🚀 Despliegue

### Vercel (Recomendado)
```bash
# Conectar con Vercel
vercel

# Configurar dominio custom
vercel domains add tusitio.com
```

### Netlify
```bash
# Build command
npm run build

# Publish directory
dist
```

### GitHub Pages
```bash
# Habilitar GitHub Pages en Settings
# Source: GitHub Actions

# El workflow está configurado en .github/workflows/deploy.yml
```

## 🛠️ Configuración Avanzada

### Variables de Entorno
```env
# .env.local
PUBLIC_SITE_URL=https://tusitio.com
PUBLIC_GA_ID=GA_MEASUREMENT_ID
```

### Astro Config
```js
// astro.config.mjs
export default defineConfig({
  site: 'https://tusitio.com',
  integrations: [
    tailwind(),
    sitemap(),
  ]
});
```

## 📞 Soporte

### 🐛 Bug Reports
Si encuentras un bug, por favor [crea un issue](https://github.com/Rene-Kuhm/landing-empresarial/issues) con:
- Descripción del problema
- Pasos para reproducir
- Capturas de pantalla si aplica
- Información del navegador/OS

### 💡 Feature Requests
Para solicitar nuevas características:
1. Revisa los [issues existentes](https://github.com/Rene-Kuhm/landing-empresarial/issues)
2. Crea un nuevo issue con label "enhancement"
3. Describe detalladamente la funcionalidad propuesta

### 🤝 Contribuciones
Las contribuciones son bienvenidas! Por favor:
1. Fork el repositorio
2. Crea una branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

### 🎯 **Próximas Características**

- [ ] 📧 Formulario de contacto funcional
- [ ] 🖼️ Galería de proyectos con filtros
- [ ] 👥 Sección de testimonios
- [ ] 📝 Blog con contenido dinámico
- [ ] 🌙 Modo oscuro
- [ ] 🌐 Internacionalización (i18n)
- [ ] 📊 Dashboard de analytics
- [ ] 🔄 Animaciones con Framer Motion

### 🏆 **Inspiración y Agradecimientos**

- [Astro.build](https://astro.build/) por el increíble framework
- [Tailwind CSS](https://tailwindcss.com/) por el sistema de diseño
- [Lucide Icons](https://lucide.dev/) por los iconos perfectos
- Comunidad de desarrolladores por feedback y sugerencias

---

**Hecho con ❤️ por [DevAgency](https://github.com/Rene-Kuhm)**

> 💼 ¿Necesitas una landing page custom para tu empresa? [Contáctanos](mailto:hola@devagency.es)