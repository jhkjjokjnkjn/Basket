# Basket — Suivi Ventes

Cette application est une single-page HTML (`index.html`) de suivi de ventes avec sauvegarde automatique (`localStorage`).

## Déploiement sur GitHub Pages

Le dépôt contient déjà le workflow GitHub Actions `.github/workflows/deploy-pages.yml`.

### Étapes

1. Pousser le dépôt sur GitHub.
2. Aller dans **Settings → Pages**.
3. Dans **Build and deployment**, choisir **Source: GitHub Actions**.
4. Vérifier que le workflow **Deploy static site to GitHub Pages** s’exécute après un push.

### URL publique

Une fois déployé, le site sera disponible à l’URL :

`https://<ton-username>.github.io/<nom-du-repo>/`

Exemple : `https://alex.github.io/Basket/`

Pour ton cas (username `jhkjjokjnkjn`, repo `Basket`) :

`https://jhkjjokjnkjn.github.io/Basket/`

## Si le lien ne marche pas (404)

1. Vérifier que le repo est bien public (ou que GitHub Pages est autorisé sur ton plan).
2. Vérifier dans **Actions** que le job **Deploy static site to GitHub Pages** est vert.
3. Vérifier dans **Settings → Pages** que la source est bien **GitHub Actions**.
4. Attendre 1 à 3 minutes après le premier déploiement (propagation GitHub Pages).
5. Faire un hard refresh du navigateur (`Ctrl+F5`).
