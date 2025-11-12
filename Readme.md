# EAR Marketing App

Demo app per servizi e community EAR Marketing.

## Deploy su Vercel

### Opzione 1: Deploy da GitHub (Consigliata)

1. Crea un repository su GitHub
2. Pusha il codice:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/TUO-REPO.git
git push -u origin main
```

3. Vai su [vercel.com](https://vercel.com)
4. Clicca "Add New Project"
5. Importa il tuo repository GitHub
6. Vercel rileverà automaticamente Vite
7. Clicca "Deploy"

### Opzione 2: Deploy con Vercel CLI

```bash
# Installa Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## Setup Locale

```bash
# Installa dipendenze
npm install

# Avvia dev server
npm run dev

# Build per produzione
npm run build

# Preview build
npm run preview
```

## Struttura File

```
ear-marketing-app/
├── src/
│   ├── App.jsx          # Componente principale (copia da Claude)
│   ├── main.jsx         # Entry point
│   └── index.css        # Stili Tailwind
├── index.html           # HTML template
├── package.json         # Dipendenze
├── vite.config.js       # Config Vite
├── tailwind.config.js   # Config Tailwind
├── postcss.config.js    # Config PostCSS
├── vercel.json          # Config Vercel
└── .gitignore          # Git ignore

```

## Note

- Il componente principale va in `src/App.jsx`
- Copia il codice React dall'artifact "EAR Marketing App" e incollalo in `src/App.jsx`
- L'export deve essere: `export default function EARMarketingApp()`
