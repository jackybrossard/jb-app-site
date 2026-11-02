# jb-app-site

Site jb-app.fr (GitHub Pages) — JB App, Jacky Brossard.

- `/` et `/en/` : accueil commun JB App (FR / EN)
- `/mesfinances/` : site de l'app MesFinances (FR, `en/`, guides `de/` `it/` `es/`)
- `/scoregolf/` : site de l'app Score Golf (FR, `en/`, `de/`, `it/`, `es/`, modes d'emploi HTML + PDF, `img/`)
- `mentions-legales.html`, `robots.txt`, `sitemap.xml`, `CNAME` : communs à tout le site
- `email-confirme.html` : page de confirmation de compte (MesFinances / Supabase) — ne pas déplacer
- Anciennes adresses MesFinances (`politique-confidentialite.html`, `conditions-utilisation.html`,
  `mode-emploi.html`, `en/privacy-policy.html`, `en/terms-of-use.html`, `en/user-guide.html`) :
  pages de redirection vers `/mesfinances/`, à conserver pour les versions de l'app déjà installées.

Ajouter une app : créer un dossier `/nom-de-l-app/`, ajouter sa carte sur `index.html` et `en/index.html`,
et ses pages dans `sitemap.xml`.
