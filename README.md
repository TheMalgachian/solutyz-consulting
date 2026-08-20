# Solutyz Consulting — site vitrine

Site vitrine pour **Solutyz Consulting**, cabinet de conseil indépendant en
achat et sourcing de matières premières pour les PME et startups des
filières **bois**, **métallurgie** et **plasturgie**.

Le site est une page statique (HTML/CSS/JS) hébergée via GitHub Pages.

## Structure

```
index.html            Page principale du site Solutyz Consulting
assets/css/styles.css Feuille de style
assets/js/main.js     Menu mobile, FAQ, formulaire de contact, animations
```

## Personnaliser le contenu

- **Coordonnées** : l'email de contact (`julesbouvier5@gmail.com`) est utilisé
  dans le bouton "Nous écrire", le formulaire de contact et le pied de page —
  à mettre à jour dans `index.html` si besoin.
- **Téléphone** : actuellement indiqué comme "sur demande" dans la section
  Contact — ajoutez un numéro directement dans `index.html` si vous souhaitez
  l'afficher.
- **Formulaire de contact** : fonctionne sans backend (ouvre un e-mail
  pré-rempli via `mailto:`). Pour un vrai formulaire qui envoie les messages
  sans passer par le client mail (ex. Formspree), il faudra remplacer le
  script dans `assets/js/main.js`.

## Développement local

Aucune dépendance : ouvrez simplement `index.html` dans un navigateur, ou
lancez un petit serveur local, par ex. :

```bash
python3 -m http.server
```
