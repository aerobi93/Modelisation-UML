# <center> class </center>

## Pourquoi ce diagramme

Nous avons décider d'utiliser ce diagramme car il permet de spécifier la structure et les liens entre les objets dont le système est composé : il spécifie **QUI** sera à l'oeuvre dans le système pour réaliser les fonctionnalités décrites par les diagrammes ***use case***.

## Explication du diagramme

Class utilisateur(account) : 
- uuid
- pseudo
- nom
- prénom
- date de naissance
- avatar
- email
- password
- rôle
- favoris
- diets
- newsletter

Class recette : 
- uuid
- nom
- description
- score
- image
- nombre de personnes

Class ingrédients :
- uuid
- nom
- quantité
- types

Class mesures : 
- uuid
- unités

Class types : 
- uuid
- nom

Class instructions : 
- uuid
- étapes

Class fêtes :
- uuid
- nom

Class commentaires : 
- uuid
- commentaires
- date

Class newsletter :
- uuid
- titre
- contenu
- date


## Image du diagramme

Class diagram:

  ![Class diagram](./diagrams-img/classDiagram.png "Class diagram")