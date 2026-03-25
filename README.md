# Studio Configurator 3D

Aplicación web hecha con React, Vite y Three.js para configurar un vehículo en una vista 3D interactiva.

## Tecnologías

- React
- Vite
- Three.js
- Tailwind CSS

## Desarrollo local

```bash
npm install
npm run dev
```

## Build de producción

```bash
npm run build
npm run preview
```

## Subir a GitHub

Si todavía no existe el repositorio local:

```bash
git init
git add .
git commit -m "feat: initial project setup"
```

Luego conecta tu repositorio remoto y sube la rama principal:

```bash
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
git push -u origin main
```

## Desplegar en Vercel

1. Importa el repositorio desde GitHub en Vercel.
2. Vercel detectará automáticamente que es un proyecto de Vite.
3. Usa esta configuración si te la pide:

```txt
Framework Preset: Vite
Build Command: npm run build
Output Directory: dist
Install Command: npm install
```

4. Pulsa Deploy.

## Notas

- `node_modules`, `dist` y `.vercel` ya están ignorados por Git.
- No hace falta un `vercel.json` para este caso.
