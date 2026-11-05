# Blockchain — Página de inicio de sesión

Página web de inicio de sesión para una plataforma de inversiones, con
verificación PIN. Archivo único en HTML/CSS/JS, sin dependencias externas.

## Vista previa

![Login](docs/preview.png)

## Cómo publicarla en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo: `blockchain-login`).
2. Sube el archivo `index.html` a la raíz del repositorio
(arrastra el archivo en la web de GitHub, o usa git):

```bash
   git init
   git add index.html
   git commit -m "Página de login Blockchain"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/blockchain-login.git
   git push -u origin main
```

3. Activa GitHub Pages:

- Ve a **Settings** → **Pages** en tu repositorio.
- En **Source** elige **Deploy from a branch**.
- Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.

4. Espera 1–2 minutos y tu página estará disponible en:

```javascript
   https://TU_USUARIO.github.io/blockchain-login/
```

## Estructura

| Archivo | Descripción |
| --- | --- |
| `index.html` | Página completa (login + PIN) |
| `README.md` | Este archivo |
