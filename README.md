# FitBegin — Clon local

Clon estático del template **FitBegin** de DesignHub:
`https://designhub.pixelwibes.in/fitbegin/index.html`

## Contenido

- `index.html` — página principal (la URL solicitada).
- `about.html`, `blog.html`, `blog-details.html`, `service.html`, `service-details.html`,
  `team.html`, `team-detail.html`, `contact.html`, `privacypolicy.html`, `term-condition.html`
  — páginas internas enlazadas desde la home, clonadas para que la navegación funcione.
- `assets/` — CSS (`css/style.css`), JS (`js/`, `bundles/`), fuentes e imágenes/vídeos del tema.

Las rutas originales `../assets/...` y `../fitbegin/...` se reescribieron como rutas
relativas locales (`assets/...` y `./...`), por lo que los archivos se pueden servir
directamente desde esta carpeta como raíz del sitio.

## Cómo verlo

Con un servidor local (recomendado, para que vídeos y fuentes carguen correctamente):

```bash
cd fitbegin
python3 -m http.server 8000
```

Abrir <http://localhost:8000/index.html>.

## Dependencias externas

Bootstrap, Bootstrap Icons, Font Awesome, Line Awesome, Simple Line Icons, Swiper,
LightGallery, GSAP y Google Fonts se cargan desde CDN, igual que en el sitio original,
por lo que se necesita conexión a internet para esos recursos. Las imágenes, vídeos,
CSS y JS propios del tema están guardados localmente.
