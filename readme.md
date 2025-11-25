# Seafiro Export (sitio estático)

Pequeño sitio estático de ejemplo para una empresa exportadora especializada en cadena de frío y logística.

## Qué hay en este repositorio

- `index.html` — Página principal con secciones: Quiénes somos, Servicios, Aduana, Transporte, Guía para productores, Galería, Productos más transportados, Equipo de contacto, Formulario y Testimonios.
- `style.css` — Estilos principales, paleta verde y diseño responsive.
- Imágenes de ejemplo en `img/` (puedes reemplazarlas por tus propias imágenes).

## Cómo ver la página

1. Abre `index.html` en tu navegador (doble clic o desde VS Code: `Open with Live Server`).

```powershell
ii .\index.html
```

## Cambios recomendados / cómo personalizar

- Reemplaza las imágenes demo (`blue.jpg`, `fresa.jpg`, `mango.jpg`, `aguacate.jpg`, etc.) en la carpeta del proyecto por fotos reales.
- Actualiza los correos y teléfonos en la sección de contacto (`index.html`) si necesitas otros destinatarios.
- Para enviar el formulario a un servicio real, reemplaza la acción del `mailto:` por una integración con un backend o servicio de formularios (Formspree, Netlify Forms, etc.).

## Agregar más contactos

Edita la lista `<select id="recipient">` en el formulario para añadir o cambiar destinatarios.

## Notas técnicas

- El menú es responsive y se abre con el botón de hamburguesa en pantallas pequeñas.
- El formulario abre el cliente de correo por defecto con los datos (utiliza `mailto:`). Para producción conviene integrar un backend.

Si quieres, puedo:
- Añadir validación avanzada del formulario (JS).
- Conectar el formulario a un servicio (Formspree, EmailJS, o un pequeño endpoint).
- Integrar iconos SVG locales y optimizar las imágenes.

Dime qué prefieres que haga a continuación.
