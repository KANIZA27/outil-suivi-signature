# Outil de suivi et de signature dématérialisée

Projet de **Kaniza SAINDOU** pour l'aide à domicile à Mayotte.

Une application sur téléphone pour remplacer les feuilles papier qu'on fait signer aux personnes aidées : l'assistante de vie note son passage, coche ce qu'elle a fait, fait signer, et ses heures se comptent toutes seules. L'association envoie ensuite les preuves au Conseil départemental.

> **Version d'essai** : les noms, adresses et heures sont inventés. Les informations s'effacent quand on recharge la page.

## Les pages

| Page | Contenu |
| --- | --- |
| `index.html` | La fiche du projet (page d'accueil) |
| `application.html` | L'application à essayer (intervenante, bureau, Département) |
| `guide.html` | Le guide de test, étape par étape |
| `avis.html` | Le formulaire pour donner son avis |
| `404.html` | Page affichée si un lien est mal écrit |
| `manifest.webmanifest`, `sw.js`, `icons/` | Installation sur téléphone et fonctionnement hors réseau |

## Installer l'application sur un téléphone

Le site est une **application web installable** (PWA) : une fois ajoutée à l'écran d'accueil, elle s'ouvre en plein écran et fonctionne sans réseau après la première ouverture.

- **iPhone (Safari)** : bouton Partager › « Sur l'écran d'accueil ».
- **Android (Chrome)** : menu ⋮ › « Installer l'application ».

## Mettre en ligne avec GitHub Pages

1. Déposer ces fichiers dans un dépôt GitHub (par exemple `outil-suivi-signature`).
2. Dans le dépôt : **Settings › Pages › Build and deployment** : source « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Le site est en ligne à l'adresse `https://<pseudo>.github.io/outil-suivi-signature/`.

## Technique

Pages HTML, CSS et JavaScript, sans serveur. S'adapte aux petits et grands écrans (testé de 320 à 1440 pixels de large). Polices chargées depuis Google Fonts.

© 2026 Kaniza SAINDOU. Tous droits réservés.
