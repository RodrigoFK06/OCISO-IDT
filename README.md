# OCISO-IDT

Sitio institucional de la Oficina de Compensaciones Industriales y Sociales Offset
para la Innovación y el Desarrollo Tecnológico — Facultad de Ingeniería Mecánica,
Universidad Nacional de Ingeniería.

## Estado

Página placeholder ("Próximamente"). Su propósito actual es establecer el
subdominio institucional y validar la configuración DNS antes del desarrollo
del micrositio completo.

## Stack

HTML estático, un solo archivo (`index.html`). Sin dependencias, sin build.

## Despliegue

Vercel (estático). Para conectar el subdominio:

1. Vercel → Settings → Domains → agregar el subdominio (ej. `ociso.uni.edu.pe`).
2. Vercel devuelve el registro `CNAME` exacto a configurar.
3. El área de sistemas de la UNI crea ese registro en el DNS de `uni.edu.pe`.
