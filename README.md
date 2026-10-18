# urson-web

**Urson s'est arrêtée le 18 octobre 2026.** Ce dépôt ne sert plus qu'une page, sur
<https://ursonapp.fr> : ce qui a été effacé, ce qui est gardé et jusqu'à quand, comment
écrire à l'éditeur. Les anciennes adresses du site renvoient vers cette page ; toute
adresse inconnue aussi (`404.html`).

Aucun script, aucune police distante, aucun appel réseau : la page est entièrement
statique.

`CNAME` porte le domaine jusqu'à son échéance ; il sera retiré avant, en juillet 2027, et
la page restera lisible à l'adresse GitHub du dépôt.

Ce dépôt est une cible de publication : la page est générée dans le dépôt applicatif
par `scripts/build-web-pages.mjs --fin`, puis copiée ici par
`scripts/publier-site-fin.sh`. Une modification faite directement ici serait écrasée.
