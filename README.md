# Application Météo

Il s'agit d'une application Express.js permettant de recueillir les données météos d'une ville. 

## Configuration

- Installez les dépendances en utilisant `npm install`.
- Variables d'environnement :
   - `WEATHER_API_KEY` : Votre clé d'API  (clé disponible après inscription sur weatherapi.com)
   - `PORT` : Numéro de port pour le serveur (facultatif, par défaut 3000).
4. Lancez le serveur en utilisant `npm start`.
5. Accédez à l'API à l'adresse `http://localhost:3000 `.


### Si besoin, vérifiez les requêtes via POSTMAN:

- URL :`/weather/{ville}`
- Méthode : `GET`
- Description : Récupère les informations météorologiques pour la ville spécifiée.
- Paramètres :
  - `ville` : Nom de la ville 
-  Les trois types de réponses possibles:
  - `200 OK` : Retourne les données météorologiques pour la ville.
  - `400 Requête incorrecte` : Requête incorrecte. Vérifiez les paramètres.
  - `500 Erreur interne du serveur` : Erreur de l'API météorologique.

- URL :`/location/{ville}`
- Méthode : `GET`
- Description : Nous renvoie les informations générale par rapport à la ville sélectionnée.
- Paramètres :
  - `ville` : Nom de la ville 
-  Les trois types de réponses possibles:
  - `200 OK` : Retourne les données météorologiques pour la ville.
  - `400 Requête incorrecte` : Requête incorrecte. Vérifiez les paramètres.
  - `500 Erreur interne du serveur` : Erreur de l'API météorologique.


## Dépendances utilisées:

- Express.js : Cadre d'application Web pour Node.js.
- Axios : Client HTTP basé sur les promesses pour effectuer des requêtes vers l'API météorologique.
- Swagger : Outil de documentation d'API pour décrire et visualiser les API RESTful.
- Autres dépendances diverses pour la configuration et la gestion des erreurs.

## Utilisation

1. Effectuez une requête GET vers le point d'accès `/weather/{ville}` avec le nom de la ville désirée.
2. Recevez les informations météorologiques au format JSON, y compris le nom de la ville, le pays, la température, la condition et l'icône.

## Contribution

##  Le projet est libre de source, toute les contributions sont fortements bienvenues !! ##
