# Journées IDEES

Ce dépôt contient une version Jekyll du site IDEES, avec le contenu éditable en Markdown.

Publié sur https://github.com/journees-idees/journees-idees.github.io

## Mise en ligne sur GitHub Pages

    1. Décompresser l'archive.
    2. Copier **le contenu** du dossier `journees-idees-jekyll` à la racine du dépôt `journees-idees.github.io` (ou remplacer les anciens fichiers après sauvegarde).
    3. Dans GitHub, ouvrir **Settings → Pages**.
    4. Choisir la branche `master` (ou `main`) et le dossier `/ (root)` comme source.
    5. Enregistrer. GitHub Pages détectera Jekyll et construira le site.

Le dépôt utilise le paquet `github-pages` et ne nécessite pas de workflow GitHub Actions personnalisé pour une configuration Pages standard.

## Modifier le contenu

- `index.md` : page d'accueil.
- `_pages/objectifs.md` : objectifs.
- `_pages/themes.md` : thèmes.
- `_pages/programme.md` : programme.
- `_pages/infos-pratiques.md` : informations pratiques.
- `_pages/organisation.md` : organisation.
- `_data/navigation.yml` : libellés et ordre du menu.

Les fichiers HTML des layouts et le CSS définissent la présentation. Pour une mise à jour éditoriale courante, il suffit de modifier les fichiers Markdown.

## Prévisualiser localement (facultatif)

Avec Ruby installé :

```bash
bundle install
bundle exec jekyll serve
```

Puis ouvrir `http://localhost:4000`.

## Notes

- Le contenu reprend les informations visibles sur le site IDEES au moment de la migration.
- Le lieu, les inscriptions et certaines informations restent indiqués comme « à venir », comme sur le site actuel.
- Aucune image n'est incluse, conformément à la demande.
