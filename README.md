# Cristian — Portfolio

Landing/hero central de mi portfolio como desarrollador frontend. Funciona además como hub de navegación: a medida que voy sumando proyectos, se listan acá mismo.

🔗 **Demo:** https://crissacio.github.io/Portafolio-CristianAlvarenga/

## Sobre este proyecto

Hero con estética cyber/técnica (fondo de nodos conectados tipo red molecular, reactivo al mouse, con headline animado). Diseñado y construido en HTML, CSS y JavaScript puro — sin frameworks ni dependencias que instalar.

## Stack

- HTML5 / CSS3
- JavaScript (Canvas API para el fondo animado)
- Tipografías: Space Grotesk, Inter, JetBrains Mono (Google Fonts)

## Cómo verlo localmente

No requiere instalación. Cloná el repo y abrí `index.html` directo en el navegador:

```bash
git clone https://crissacio.github.io/Portafolio-CristianAlvarenga/
cd NOMBRE-REPO
open index.html   # o doble clic en el archivo
```

## Estructura

```
index.html   → todo el proyecto: HTML, CSS y JS en un solo archivo
```

## Cómo agregar un proyecto nuevo al hub

Dentro de `index.html`, buscar el array `PROJECTS` (dentro del `<script>`) y sumar un objeto:

```javascript
{
  id: '04',
  title: 'Nombre del proyecto',
  desc: 'Una línea corta describiéndolo',
  tag: 'LIVE',
  status: 'live',
  href: 'https://link-al-proyecto.com'
}
```

El listado del hub se genera solo a partir de ese array — no hace falta tocar el HTML ni el CSS.

## Roadmap

- [ ] Proyecto 2 (frontend)
- [ ] Proyecto 3 (datos/API)
- [ ] Migrar estructura a Vite cuando el portfolio tenga más de una página
- [ ] Agregar CV descargable

## Contacto

- GitHub: [tu usuario]
- LinkedIn: [tu perfil]
- Email: [tu email]
