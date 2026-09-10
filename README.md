# Pequeños Mordiscos — Sitio web, Privacidad y Términos

Sitio público para la app **Pequeños Mordiscos** (TinyTasste).

Repo: https://github.com/danigonlinea/tinytasste-privacy (rama `main`, GitHub Pages desde `/ (root)`).

## URLs para la pantalla de consentimiento de Google y Play Console

| Campo | URL |
|---|---|
| Application home page | `https://danigonlinea.github.io/tinytasste-privacy/` |
| Application privacy policy link | `https://danigonlinea.github.io/tinytasste-privacy/privacy/` |
| Application Terms of Service link | `https://danigonlinea.github.io/tinytasste-privacy/terms/` |

Contacto: tinytasste@gmail.com

## Estructura

```
index.html          # landing / home
privacy/index.html  # política de privacidad
terms/index.html    # términos del servicio
```

## Desarrollo local

```bash
npx serve .
# o
python3 -m http.server 8080
```

## Despliegue

Push a `main` → GitHub Pages publica automaticamente (1-2 min).
