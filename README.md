# Pioche !

Un site web statique réalisé avec [Hugo](https://gohugo.io/)

## Mise en route

Pour mettre en route ce site, il vous siffira d'installer [Hugo](https://gohugo.io/) sur votre machine.

Il vous suffira de lancer la commande `hugo` pour regénérer les fichiers statiques dans un dossier `/docs`.

Tappez `hugo serve` pour voir le résultat final en direct sur votre navigateur en local.

Si vous souhaitez faire des modifications, et pour éviter de regénérer des builds dans `/docs` utilisez `hugo --config config-dev.yaml serve`

## Configuration

Pour changer le titre de la page d'accueil, rendez-vous dans les fichiers `config.yaml` et `config-dev.yaml`, et changez la valeur de `titleHomepage` par celle qui vous convient.

Pour ajouter une nouvelle page, imaginons un nouvel article dans la rubrique `Qu'en dites-vous ?`, il vous suffira d'utiliser la commande `hugo new qu-en-dites-vous/culture.md` et de modifier le fichier correspondant dans `/content/qu-en-dites-vous/culture.md`. N'hésitez pas à vous inspirer des articles déjà présents pour la mise en forme.
