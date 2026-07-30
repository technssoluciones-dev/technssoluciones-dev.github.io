# TECHN.S Soluciones Informáticas

Sitio web oficial de **TECHN.S Soluciones Informáticas** — soporte técnico, desarrollo de software a medida y auditoría de seguridad informática en Biobío, Chile (atención presencial, híbrida y remota).

🔗 **Sitio publicado:** https://technssoluciones-dev.github.io

## Contenido del sitio

- **Servicios**: soporte técnico (Windows, redes, impresoras, hardware), desarrollo de software a medida (Python, Node.js, NestJS) y auditoría/seguridad informática.
- **Proyectos**: selección de trabajos propios, enlazados directo a los repositorios de esta organización.
- **Testimonios**: espacio reservado para reseñas reales de clientes.
- **Contacto**: WhatsApp, correo, LinkedIn y GitHub.

## Stack

Sitio estático de una sola página (`index.html`), sin dependencias ni build:

- HTML + CSS puro
- JavaScript vanilla (animaciones de scroll y efecto de escritura en el panel de estado)
- Tipografías: Sora, Inter y JetBrains Mono (Google Fonts)
- Logo embebido como imagen en base64

## Estructura

```
.
└── index.html   # todo el sitio (markup, estilos y scripts en un solo archivo)
```

## Cómo editar

1. Clona el repositorio y abre `index.html` en tu editor.
2. Los datos de contacto (WhatsApp, email) y las descripciones de proyectos están directamente en el HTML — búscalos y edítalos con "Buscar y reemplazar".
3. Guarda, luego:
   ```
   git add index.html
   git commit -m "actualiza contenido"
   git push origin main
   ```
4. Los cambios quedan publicados automáticamente en 1-2 minutos (GitHub Pages sirve directo desde la rama `main`).

## Despliegue

Publicado con **GitHub Pages** — rama `main`, carpeta raíz (`/`).

---

Desarrollado por [Hans Bascur](https://www.linkedin.com/in/hansbascur/) — [github.com/technssoluciones-dev](https://github.com/technssoluciones-dev)
