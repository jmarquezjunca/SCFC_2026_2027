# Sant Cugat FC 2026/2027 · App de minutos

Un solo repositorio de GitHub con todo: la app (`index.html`) y los datos (`data.json`).

## 1. Crear el repositorio y publicar la app
1. En GitHub: New repository → nombre `scfc-app` → Public → Create.
2. «uploading an existing file» → arrastra **todo el contenido de esta carpeta** (`index.html`, `data.json`, `manifest.webmanifest`, `.nojekyll` y la carpeta `icons`) → Commit.
3. Settings → Pages → Source: «Deploy from a branch» → rama `main`, carpeta `/ (root)` → Save.
4. En un par de minutos la app está en `https://TU-USUARIO.github.io/scfc-app/`.

## 2. Token de acceso (para poder guardar cambios)
GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token.
- Repository access: *Only select repositories* → `scfc-app`.
- Permissions → Repository → **Contents: Read and write**.
- Copia el token (empieza por `github_pat_`).

## 3. Conectar cada dispositivo (una vez)
Abre la app → Copia de seguridad → «Conectar con GitHub». El usuario y el repositorio ya vienen rellenados: pega el token y pulsa Conectar.
Móvil y ordenador verán los mismos datos. En el móvil, añade la app a la pantalla de inicio.

El token se guarda solo en ese dispositivo. Si lo pierdes, bórralo en GitHub y crea otro.
