# TON ESPACE — première version fonctionnelle

## Contenu
- `index.html` : application responsive.
- `manifest.webmanifest` : configuration d'installation PWA.
- `sw.js` : cache hors connexion.
- `icon-192.png` et `icon-512.png` : icônes.

## Fonctionnalités
- Tableau de bord et modules : finances, projets, carrière, immobilier, animaux, sport et organisation.
- Ajout, modification et suppression d'éléments.
- Stockage local dans le navigateur de l'appareil.
- Export et import d'une sauvegarde JSON.
- Accès externe à ChatGPT (aucune donnée n'est envoyée automatiquement).
- Cache hors connexion après le premier chargement.

## Installation sur iPhone
Une PWA installable et utilisable hors connexion doit être servie en HTTPS. Le HTTPS peut être fourni gratuitement par un hébergeur statique, par exemple GitHub Pages. Aucun serveur de données ni abonnement payant n'est nécessaire.
1. Décompresser le ZIP.
2. Publier le contenu du dossier sur un hébergeur statique gratuit compatible HTTPS.
3. Ouvrir l'adresse du site dans Safari sur l'iPhone.
4. Appuyer sur Partager > Sur l'écran d'accueil > Ajouter.

## Important
Les données sont locales au navigateur/appareil. Elles ne sont pas synchronisées entre téléphones. Exporter régulièrement une sauvegarde JSON. Effacer les données du navigateur peut supprimer les données de l'application.
