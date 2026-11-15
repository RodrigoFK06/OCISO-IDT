# OCISO-IDT

Sitio institucional de la Oficina de Compensaciones Industriales y Sociales Offset
para la Innovación y el Desarrollo Tecnológico — Facultad de Ingeniería Mecánica,
Universidad Nacional de Ingeniería.

## Estado

Base del sitio institucional con contenido real y pendientes marcados para
revisión de la oficina (botón "Pendientes" con modo de resaltado). Tiene
`noindex` en `index.html` y en `vercel.json` hasta el lanzamiento.

## Stack

HTML estático (`index.html` + `img/`). Sin build. GSAP 3.13 y Google Fonts
se cargan desde CDN.

## Despliegue

Vercel (estático). Para conectar el subdominio:

1. Vercel → Settings → Domains → agregar el subdominio (ej. `ociso.uni.edu.pe`).
2. Vercel devuelve el registro `CNAME` exacto a configurar.
3. El área de sistemas de la UNI crea ese registro en el DNS de `uni.edu.pe`.
