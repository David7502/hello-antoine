# Hello Antoine

Petite page colorée qui affiche « Hello Antoine » : fond en dégradé animé, lettres arc-en-ciel qui ondulent, et un petit survol. Le tout est en HTML et CSS, et respecte `prefers-reduced-motion`.

Le projet est un Worker Cloudflare minimal. Wrangler sert le dossier `public/` comme assets statiques (pas de script Worker).

## Lancer en local

```bash
npm install
npm run dev
```

Ouvre ensuite l’adresse affichée par Wrangler, en général [http://localhost:8787](http://localhost:8787).

## Déployer

Connecte-toi d’abord à Cloudflare, puis publie le Worker `hello-antoine` :

```bash
npx wrangler login
npm run deploy
```
