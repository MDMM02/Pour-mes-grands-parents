# Aide numérique — Site pour grands-parents


Application Next.js pour fournir des fiches PDF imprimables (WhatsApp, email, messagerie).

Comment l'utiliser en développement
- Installer les dépendances et démarrer le serveur de développement:

```bash
npm install
npm run dev
```

Pages principales
- `pages/index.js` : page d'accueil
- `pages/fiches.js` : liste des fiches PDF

Ajouter des PDFs
- Placer vos fichiers PDF dans `public/assets/pdfs/` avec les noms : `whatsapp.pdf`, `email.pdf`, `voicemail.pdf`.

Déploiement
- Construire et exporter (site statique) :

```bash
npm run build
npm run export
```

Vous pouvez déployer sur Vercel (recommandé) ou héberger les fichiers statiques exportés.
