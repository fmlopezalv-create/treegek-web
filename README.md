# treegek-web

Sitio estático de **app.treegekec.com** (GitHub Pages) con las páginas públicas que exige Google Play.

| URL | Uso en Play Console |
|---|---|
| `/walletgek/privacidad.html` | Política de privacidad de WalletGek |
| `/walletgek/borrar-cuenta.html` | URL de eliminación de cuenta (Seguridad de los datos) |
| `/walletgek/` | Sitio web de WalletGek |
| `/notes/privacidad.html` | Política de privacidad de Treegek Notes |
| `/notes/` | Sitio web de Treegek Notes |

- `.nojekyll` es obligatorio para que se publique `.well-known/`.
- `.well-known/assetlinks.json` está vacío (`[]`) hasta tener las huellas SHA-256 de
  Play Console → Integridad de la app → Firma de apps.
- El formulario de borrado de WalletGek envía a `https://walletgek-api.onrender.com/borrar-cuenta`.
- Sin secretos: este repositorio es público.
