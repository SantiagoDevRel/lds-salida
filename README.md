# lds-salida-web

Sitio estático mínimo para la app **Los Del Sur — Linterna**. Solo aloja la
**política de privacidad** que pide App Store Connect.

- `privacy.html` → política de privacidad (la app no recolecta datos).
- `index.html` → landing mínima con link a la política.
- `vercel.json` → `cleanUrls` para que `/privacy` funcione sin `.html`.

## Deploy

Static, sin build. Importar el repo en Vercel → deploy automático.
URL objetivo: `https://lds-salida.vercel.app/privacy`
