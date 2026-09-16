# Bitácora del proyecto — Taller React API 

## Día 1 - 15 de septiembre 2026

**Qué hice:**
- Cloné el repositorio del proyecto desde GitHub a mi computador.
- Creé el proyecto con Vite usando el template `react-ts`.
- Instalé las dependencias con `npm install`.
- Verifiqué que el proyecto corriera correctamente con `npm run dev` y que compilara sin errores con `npm run build`.
- Configuré el archivo `.gitignore`, agregando la línea `.env` para proteger futuras claves secretas.
- Creé la estructura de carpetas dentro de `src/`: `components`, `services`, `types` y `styles`.
- Creé la rama `develop` a partir de la rama principal (`master`) y la subí a GitHub.

**Con qué me trabé:**
- Al hacer el primer commit, terminé subiendo todo el contenido del proyecto como lo son Vite, gitignore, carpetas en un solo commit, en vez de separarlo en los commits planeados.

**Cómo lo resolví:**
- Usé `git status` y `git show --stat HEAD` para revisar exactamente qué archivos había en ese primer commit.
- Agregué dos commits simbólicos (`--allow-empty`) para marcar de forma correcta  los siguientes puntos importantes del día en el historial, aunque el contenido ya estuviera en el primer commit. Aprendí que para el Día 2 debo usar `git add` de forma más acertada  archivo por archivo o carpeta por carpeta para que cada commit represente un cambio específico.

**Commits de hoy:**
- `aa6fe71` — chore: inicializar proyecto React con Vite
- `9e34ccf` — chore: configurar gitignore y estructura inicial
- `50b4f09` — docs: preparar base del proyecto