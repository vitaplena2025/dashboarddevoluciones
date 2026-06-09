# Egg Market · Dashboard de Devoluciones

## Deploy en Netlify

### Opción 1 – Drag & Drop (más fácil)
1. Ve a https://netlify.com y crea cuenta gratis
2. Arrastra la carpeta `dashboard/` al panel "Sites"
3. ¡Listo! Te da una URL pública automáticamente

### Opción 2 – Netlify CLI
```bash
npm install -g netlify-cli
netlify deploy --prod --dir .
```

## Actualizar datos
- Reemplaza `data.json` con la nueva exportación
- Redeploy en Netlify (sube el archivo o usa CLI)

## Archivos
- `index.html` – Dashboard completo (HTML/CSS/JS)
- `data.json`  – 1,796 registros de devoluciones
- `netlify.toml` – Configuración de headers
