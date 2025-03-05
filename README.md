Résumé de la structure pour le nain:

gitignore : node modules (à télécharger via packages.json), credentials

auto.bat : terminal lancé automatiquement (chrontab ou equivalent) qui prompte le nom du cours et l'envoie sur le serveur via curl

db: \*\*désuet. Enregistrement des cours ds une database. A remettre au gout du jour si on veut faire un truc plus sophistiqué ?

index.js: serveur node.js, qui tourne en arrière plan au démarrage. Envoie les requêtes à l'api de google calendar

token: le token pour se connecter à l'api

## Rappels biblio

- [ce nain a inventé le FSRS](https://github.com/open-spaced-repetition/fsrs4anki)
- [lien du papier ieee](https://doi.org/10.1109/TKDE.2023.3251721)
- [a l'air pertinent pour nous autres](https://meridian.allenpress.com/aplm/article/147/2/133/490404)

Ressources google calendar:

- [google calendar api nodejs (à changer ?)](https://developers.google.com/calendar/quickstart/nodejs)
- [google calendar api python ](https://developers.google.com/calendar/api/quickstart/python)
