# JoCaps-TV · relais des bandes-annonces

Page publique qui sert de relais au lecteur YouTube pour l'app TV JoCaps-TV
(usage personnel). L'app, installée sur la TV, n'a pas d'adresse web : YouTube
refuse alors de lire la vidéo intégrée (« Erreur 153 »). L'app charge donc
cette page, qui intègre le lecteur à sa place.

- Paramètre : `?v=<identifiant de la vidéo YouTube>`
- Aucune donnée personnelle, aucun suivi.
- L'app envoie pause / lecture / saut par `postMessage` ; la page signale la
  fin de la vidéo ou une erreur.

## Mise en ligne (GitHub Pages)

Dépôt public `jocaps-gif/jocaps-tv-trailer`, avec ce dossier à la racine, puis
GitHub Pages sur la branche `main`. Adresse attendue par l'app :
`https://jocaps-gif.github.io/jocaps-tv-trailer/`.
