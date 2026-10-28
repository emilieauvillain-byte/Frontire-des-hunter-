# Frontière des Hunters — site prêt à publier

## Important
Ce dossier contient un prototype 3D, pas un jeu AAA fini. Il charge Three.js depuis un CDN, donc la première ouverture nécessite Internet. Le service worker met en cache la coque du site, mais ne rend pas la bibliothèque 3D disponible hors ligne.

## Publier gratuitement avec GitHub Pages
1. Sur GitHub, crée un nouveau dépôt public, par exemple `frontiere-des-hunters`.
2. Ajoute les fichiers de ce dossier à la racine du dépôt : `index.html`, `manifest.webmanifest`, `icon.svg`, `sw.js`.
3. Dans le dépôt, ouvre **Settings → Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`, et enregistre.
5. Attends la publication, puis ouvre l'adresse affichée dans Settings → Pages sur Safari.

## Ajouter à l’écran d’accueil sur iPhone/iPad
Une fois l'adresse HTTPS ouverte dans Safari : bouton **Partager** → **Sur l’écran d’accueil** → **Ajouter**.

## Dépannage
Si l'écran reste noir, vérifie que la connexion est active et que le domaine `cdn.jsdelivr.net` n'est pas bloqué. Sur iOS, ouvre le lien HTTPS publié dans Safari plutôt que d'ouvrir `index.html` depuis Fichiers.
