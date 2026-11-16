# AGENTS.md — charte de code de `boucheriegabonaise`

Ce fichier est lu par l'IA (et par moi) avant toute modification. Il décrit la façon dont ce dépôt est écrit.

## Statut
Site vitrine statique, **entretien minimal** : on corrige et on met à jour le contenu, on ne change pas de technologie.

## Structure
- `index.html` : la page.
- `main.css` et `styleguide.css` : les styles.
- `public/` : images et logo.
Un fichier, un rôle.

## Écriture du code
- Nouveau code : noms de variables, de fonctions, de classes et de composants en anglais.
- Commentaires en français, qui expliquent le *pourquoi* plutôt que le *quoi*.
- Ne pas réécrire le projet : on corrige ou on étend, on ne remplace pas ce qui existe.

## Git
- Une idée = une branche = une pull request. Jamais de commit direct sur `main`.
- Commits courts, une notion par commit, préfixés d'un gitmoji.
- Tout commit écrit avec l'IA porte la mention `Co-Authored-By`.

## Qualité
- Ouvrir `index.html` dans un navigateur : images, liens et bouton WhatsApp doivent fonctionner.
- Ne pas ajouter de dépendance ni d'outil de construction.

## Dépendances
Aucune : le projet n'utilise ni gestionnaire de paquets ni bibliothèque installée.

## Secrets
- Aucun fichier `.env` versionné. Si une clé devient nécessaire : un `.env.example` sans valeur.

## Contenu du client
Les coordonnées (téléphone, e-mail) affichées sur le site sont publiques. Ne jamais ajouter de données personnelles ou commerciales non publiées.
