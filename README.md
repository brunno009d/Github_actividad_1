# Mi Proyecto

## Descripción
[Descripción breve del proyecto]

## Requisitos
- Node.js >= 18
- npm >= 9

## Instalación

\```bash
git clone <url-del-repo>
cd mi-proyecto
npm install
\```

## Uso

\```bash
npm start         # modo desarrollo
npm run build     # build de producción
npm test          # ejecutar pruebas
\```

## Contribuir

Lee nuestras reglas del repo antes de contribuir:

- Trabajamos con `main` (estable) y `dev` (integración).
- Las ramas de trabajo salen **siempre desde `dev`**.
- Todo cambio entra por **Pull Request** (no push directo).
- Commits con formato **Conventional Commits**.
- `main` y `dev` requieren al menos **1 aprobación** para merge.

### Flujo básico

\```bash
git checkout dev && git pull
git checkout -b feature/PROJ-XXX-descripcion
# ... trabajas ...
git add .
git commit -m "feat: descripción del cambio"
git push -u origin feature/PROJ-XXX-descripcion
# Abre un Pull Request hacia dev en GitHub
\```