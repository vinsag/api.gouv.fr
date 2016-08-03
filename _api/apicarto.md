---
title: GéoAPI
tagline: Interrogez les référentiels géographiques plus facilement
contract: OUVERT
openapi_definition: https://apicarto.sgmap.fr/apidoc/cadastre.yml
doc_tech: https://apicarto.sgmap.fr/apidoc
contact: apicarto@ign.fr
clients:
  - collectivités
  - ministères
  - entreprises
  - particuliers
partners:
  - IGN
  - INAO
owner: IGN
category: reference
keywords:
  - Communes
  - Cadastres
  - Géométrie
  - Intersection
  - Surface
---

APICARTO est une boîte-à-outils facile à prendre en main utilisant les flux wfs IGN(pour la partie cadastre).
Le service d'interrogation du cadastre permet :
   
    * Obtenir les géométries pour une commune
    
    * Obtenir les divisions parcellaires d'une commune
    
    * Obtenir la géométrie d'une parcelle cadastrale
    
    * Obtenir les parcelles cadastrales avec les surfaces d'intersection à partir d'une géométrie
    
    * Obtenir le centroid d'une parcelle ou d'une commune(localisants)

Grâce à elle vous pouvez également :

* Connaître les groupements auxquels appartient une commune, ainsi que leurs compétences _(bientôt)_
* Savoir si une parcelle appartient à certains zonages en récupérant les tables métiers nécessaires

Les différentes fonctionnalités arrivant progressivement, restez informés en suivant cette page, en visitant le site http://apicarto.ign.fr/ ou [en nous contactant](mailto:apicarto@ign.fr).


## Informations complémentaires

#### Couverture du territoire

France métropolitaine et [DROM](https://fr.wikipedia.org/wiki/D%C3%A9partement_et_r%C3%A9gion_d%27outre-mer).

#### Coordonnées géographiques

Cette API utilise exclusivement des coordonnées géographiques.
Elle peut renvoyer des données au format JSON ou  [GeoJSON](http://geojson.org).

#### Qui peut utiliser cette API ? Demande de clé IGN

Tout le monde peut utiliser l'api mais une demande de clé IGN est indispensable.

#### Comment obtenir une clé IGN ?
Pour obtenir une clé geoportail, vous devez vous connecter au site : http://professionnels.ign.fr/ ou http://api.ign.fr/accueil (pour une clé de développement)


#### Contact

apicarto@ign.fr
