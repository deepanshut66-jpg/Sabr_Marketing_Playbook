# SABR — Render-ready website

All files are in one folder. There are no nested folders.

Extract this ZIP and upload its contents directly into your GitHub repository root. Keep all webpages, images, videos and render.yaml together.

## Render deployment

Create a Blueprint connected to your GitHub repository. The included render.yaml supplies the settings and clean URL rewrites.

For manual Static Site setup:
- Build command: `test -f index.html`
- Publish directory: `.`

No npm build, environment variables, database or start command is needed.

## Local preview

Run `python3 -m http.server 8080` from the extracted folder. Open http://localhost:8080 and use the HTML navigation links.

Six HTML pages contain their own styles and JavaScript. All media references match the flat folder layout. Google Fonts requires internet access.
