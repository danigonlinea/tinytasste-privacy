# Pequenos Mordiscos — Sitio web, Privacidad y Terminos

Sitio publico para la app **Pequenos Mordiscos** (TinyTasste, `com.danigonlinea.tinytasste`).

Repo: https://github.com/danigonlinea/tinytasste-privacy (rama `main`, GitHub Pages desde `/ (root)`).

## URLs para Google Cloud (OAuth consent screen) y Play Console

| Campo | URL |
|---|---|
| Application home page | `https://danigonlinea.github.io/tinytasste-privacy/` |
| Application privacy policy link | `https://danigonlinea.github.io/tinytasste-privacy/privacy/` |
| Application Terms of Service link | `https://danigonlinea.github.io/tinytasste-privacy/terms/` |

Contacto: tinytasste@gmail.com

## Estructura

```
index.html          # landing / home
privacy/index.html  # politica de privacidad
terms/index.html    # terminos del servicio
```

## Desarrollo local

```bash
npx serve .
# o
python3 -m http.server 8080
```

## Despliegue

Push a `main` → GitHub Pages publica automaticamente (1-2 min).
