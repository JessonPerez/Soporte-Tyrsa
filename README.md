# Portal de tickets de soporte IT

Prototipo de una página donde los usuarios crean tickets de soporte y consultan su estado.

## Qué hace

- **Vista pública:** el usuario crea un ticket y recibe su número. Con ese número puede consultar únicamente el estado.
- **Panel de técnicos:** lista completa, búsqueda, filtros y cambio de estado. Se abre agregando `#tecnicos` a la dirección de la página.

## Cómo usarlo

Es un solo archivo, sin dependencias ni instalación. Abre `index.html` en el navegador.

## Publicarlo con GitHub Pages

1. Sube `index.html` a la raíz del repositorio.
2. En GitHub, ve a **Settings → Pages**.
3. En **Source**, elige la rama `main` y la carpeta `/ (root)`.
4. Guarda. En un par de minutos tendrás una dirección pública.

## Limitaciones del prototipo

- Los tickets se guardan en `localStorage`, es decir, en el navegador de cada persona. No se comparten entre dispositivos ni usuarios.
- El panel de técnicos no tiene autenticación.

## Próximos pasos

- Base de datos compartida y API (por ejemplo, Node.js con PostgreSQL, o un servicio como Supabase o Firebase).
- Inicio de sesión con roles (usuario y técnico).
- Asignación de tickets, comentarios, adjuntos y notificaciones por correo.
