# SNCB Image & Reputation Story V3

Infographie web responsive construite à partir des diapositives 11 à 33 du dashboard Q1–Q2 2026, complétée par les rapports Auxipress Q1/Q2 et les rapports de social listening Akkanto T1/T2.

## Déploiement sur GitHub Pages

1. Créez un nouveau dépôt GitHub.
2. Déposez `index.html`, `styles.css` et `script.js` à la racine.
3. Ouvrez **Settings > Pages**.
4. Dans **Build and deployment**, sélectionnez **Deploy from a branch**.
5. Choisissez la branche `main` et le dossier `/root`, puis **Save**.

Le site ne nécessite ni compilation ni serveur. Il fonctionne également en ouvrant `index.html` localement.

## Contenu

- récit vertical avec animations légères ;
- vue express en 60 secondes ;
- données médias, réseaux sociaux et sentiment ;
- mode sombre ;
- version imprimable et export PDF via le navigateur ;
- navigation clavier et prise en charge de `prefers-reduced-motion`.

## Fichiers

- `index.html` : structure et contenu ;
- `styles.css` : identité visuelle, responsive et impression ;
- `script.js` : animations, menu, mode sombre et fenêtre de synthèse.

## Remarque

La police est chargée via Google Fonts. Pour un déploiement totalement autonome, remplacez l'import dans `styles.css` par des polices locales ou système.


## V3 lisibilité renforcée

Cette version conserve le récit vertical initial et ajoute les détails utiles des rapports Auxipress et Akkanto. La taille minimale des textes, les contrastes, les espacements et la hiérarchie des chiffres ont été renforcés pour la lecture sur écran et en projection.
