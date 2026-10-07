# Àlex Barrera — Portfolio Web

> Portfolio personal y profesional de **Àlex Barrera Sardà**, desarrollador web y estudiante de 2º de Desarrollo de Aplicaciones Web (DAW) en Stucom Barcelona.

🌐 **Sitio web en vivo:** [https://alexbarrera457.github.io](https://alexbarrera457.github.io)

---

## 🚀 Proyectos destacados

| Proyecto | Stack principal | Descripción |
| :--- | :--- | :--- |
| **[Cal Sardà](https://alexbarrera457.github.io/cal-sarda)** | Angular 22 · SSR · Express · TypeScript | Prototipo de comercio electrónico para una charcutería y colmado centenario fundado en 1930. Catálogo interactivo de productos gourmet, alérgenos, gestión de cestas y pedidos de recogida/entrega. |
| **[EventSportsBCN](https://alexbarrera457.github.io/eventsportsbcn)** | PHP 8 · MySQL · MVC · JavaScript | Plataforma full-stack para el descubrimiento, inscripción y gestión de eventos deportivos en Barcelona con roles diferenciados y control de aforo. |
| **[OMNI // NEXUS](https://alexbarrera457.github.io/omni-nexus)** | Node.js · Express 5 · SQLite · OpenAI API | Capa local de asistencia inteligente con interfaz web reactiva, historial conversacional persistente con WAL y ejecución de herramientas contextuales. |

---

## ✨ Características clave del portfolio

- **🌍 Soporte trilingüe completo (ES / CA / EN):** Cambio instantáneo de idioma sin recarga de página y **detección automática del idioma del navegador** (`navigator.language`) en la primera visita.
- **🔍 Visor interactivo a pantalla completa (*Lightbox*):** Modal accesible con soporte de teclado (<kbd>Esc</kbd>, flechas <kbd>←</kbd> y <kbd>→</kbd>), contador dinámico y sincronización de títulos según el idioma.
- **📄 Currículum vitae integrado ([`/cv`](https://alexbarrera457.github.io/cv)):** Con barra de acciones directa para exportar a PDF en alta resolución (mediante `html2canvas` y `jsPDF`) y estilos adaptados para impresión física o PDF ATS.
- **⚡ Core Web Vitals & Rendimiento:** Dimensiones de imagen explícitas para evitar saltos de diseño (CLS = 0), `fetchpriority="high"` y decodificación asíncrona para maximizar el LCP.
- **🎯 Smart Mailto:** Enlaces de correo con asunto y plantilla de saludo estructurados automáticamente según el idioma del visitante para reducir fricción.
- **🔎 SEO y Datos Estructurados:** Metadatos Open Graph, Twitter Cards, `robots.txt`, `sitemap.xml` y marcado semántico JSON-LD (`schema.org/Person`).
- **🚫 Página 404 personalizada:** Página de error editorial con enlaces de retorno y sugerencias directas a los proyectos.
- **⬆️ Botón "Volver arriba":** Microinteracción flotante con desplazamiento suave (*smooth scroll*).

---

## 🛠️ Stack tecnológico

- **Framework:** [Astro](https://astro.build/) (Static Site Generation · SSG)
- **Lenguajes:** TypeScript, HTML5 semántico y CSS3 nativo (Variables CSS, Flexbox, Grid y animaciones procedurales sin dependencias pesadas).
- **Despliegue y CI/CD:** GitHub Actions + GitHub Pages (`.github/workflows/deploy-gh-pages.yml`).
- **Gestor de paquetes:** `pnpm`.

---

## 💻 Desarrollo local

Si deseas clonar y ejecutar este portfolio en tu entorno local:

```bash
# 1. Clonar el repositorio
git clone https://github.com/alexBarrera457/alexBarrera457.github.io.git
cd alexBarrera457.github.io

# 2. Instalar dependencias
pnpm install

# 3. Iniciar el servidor de desarrollo
pnpm dev

# 4. Validar tipos y diagnósticos de Astro
pnpm check

# 5. Compilar para producción (genera directorio /dist)
pnpm build
```

El servidor local estará disponible en `http://localhost:4321`.

---

## 📬 Contacto

- **LinkedIn:** [Àlex Barrera Sardà](https://www.linkedin.com/in/%C3%A0lex-barrera-sard%C3%A0-35b088397/)
- **Email:** [salexbarrera@gmail.com](mailto:salexbarrera@gmail.com)
- **GitHub:** [@alexBarrera457](https://github.com/alexBarrera457)

---

© 2026 Àlex Barrera Sardà · Desarrollador de Aplicaciones Web · Barcelona
