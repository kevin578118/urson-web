# urson-web

Pages publiques d'**Urson**, servies par GitHub Pages sur <https://ursonapp.fr>.

Urson est une application mobile qui aide les parents de la région de Bourges à
trouver des activités adaptées à leurs enfants le week-end.

## Ce que ce dépôt contient

Des pages statiques, sans dépendance ni script tiers — pas de police distante,
pas d'outil de mesure d'audience, aucun appel réseau en dehors de l'API de
suppression de compte :

- `index.html` — la page d'accueil : ce que fait l'application, ce qu'on y trouve,
  ce qu'elle ne fait pas.
- `aide/` — l'aide et les conseils d'utilisation, et comment nous joindre.
  C'est l'adresse de support déclarée aux stores.
- `confidentialite/` — ce que l'application enregistre, où, et ce qu'elle
  n'enregistre pas. Exigée par l'App Store et par Google Play.
- `conditions/` — les conditions d'utilisation : contenus déposés par les parents,
  règles de contenu, signalement et blocage.
- `suppression-de-compte/` — permet à un parent de demander la suppression de son
  compte Urson sans avoir l'application installée (exigence Google Play).
- `404.html` — servie par GitHub Pages sur toute adresse inconnue.

`CNAME` porte le domaine et **ne doit jamais être supprimé** : sans lui, GitHub
Pages perd `ursonapp.fr` et toutes les adresses déclarées aux stores tombent.

## Ce dépôt est une cible de publication, pas une source

Les fichiers sont écrits, relus et versionnés dans le dépôt applicatif (privé),
sous `web/`, puis copiés ici pour publication. **Toute correction se fait là-bas** —
une modification faite directement ici serait écrasée à la publication suivante.

La plupart des pages y sont d'ailleurs **générées** (`scripts/build-web-pages.mjs`) :
les textes de « Confidentialité » et d'« Aide » sont ceux-là mêmes qu'affichent les
écrans de l'application, pour qu'aucune des deux versions ne puisse dériver de l'autre.
