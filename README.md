# Portfolio de Zakaria BAGAYA

En ligne : https://zakiscodes.github.io

## Les fichiers

- `index.html` : toute la page (textes, couleurs, mise en page).
- `photo.jpg` : la photo ronde en haut (carrée, 480 × 480 px conseillé).

## Modifier un texte

1. Ouvre `index.html` dans VS Code.
2. Cherche le texte à changer avec Ctrl+F (par exemple « ARONE » ou « Créneau »).
3. Modifie-le entre les balises, sans toucher aux `<...>` autour.
4. Double-clique sur `index.html` pour voir le résultat dans ton navigateur.

Repères dans `index.html` :

- Couleurs : bloc `:root` tout en haut (`--accent` = le bordeaux).
- Sections : `id="experiences"`, `id="projets"`, `id="competences"`, `id="formation"`, `id="contact"`.
- Ajouter une expérience : copie un couple `<div class="when">…</div>` + `<div class="what">…</div>`.
- Ajouter un projet : copie un bloc `<article class="card">…</article>`.

## Changer la photo

Remplace `photo.jpg` par une autre image carrée portant le même nom.

## Mettre en ligne

Dans un terminal ouvert dans ce dossier :

```
git add -A
git commit -m "Ce que j'ai changé"
git push
```

Le site se met à jour 1 à 2 minutes après.
