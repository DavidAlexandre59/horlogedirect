# Horloge de studio radio

Page unique (`index.html`), sans serveur ni compte. À héberger gratuitement avec GitHub Pages.

## Mise en ligne
1. Crée un dépôt GitHub et envoie `index.html` à la racine.
2. Settings > Pages > Deploy from a branch > `main` / `(root)`.
3. L'adresse sera `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## ON AIR synchronisé
- Le canal de synchro est intégré dans le code (`const CH`) : toutes les copies de la page partagent le même ON AIR, sans rien régler.
- Canal actuel : `studio-beab37d70e509eaf15b1`. Pour en changer, modifie cette ligne dans `index.html`.
- Attention : si le dépôt est public, le canal est lisible par tous, donc n'importe qui peut commander ton ON AIR. Garde un dépôt privé ou change de canal si besoin.
- Adresse de la télécommande (tablette, Steam Deck) : l'adresse de la page suivie de `#remote`. Le bouton « Copier le lien télécommande » du menu la copie.
- Touche Espace = ON AIR (réattribuable via le menu), P = orientation, F = plein écran.
- Le service utilisé est ntfy.sh (gratuit, sans compte). Il garde l'état 12 h. Pour ton propre serveur ntfy, ajoute `?srv=https://ton-serveur` à l'adresse.
