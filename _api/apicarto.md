---
title: API CARTO
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

__API Carto__ est une boîte-à-outils __facile à prendre en main__ , proposant des briques logicielles qui visent à simplifier les démarches administratives dématérialisées.

La première brique mise à disposition utilise les flux WFS IGN de la BD PARCELLAIRE®.
Le service d'interrogation permet d’obtenir les éléments suivants :
   
    * géométries pour une commune
    
    * divisions parcellaires d'une commune
    
    * géométrie d'une parcelle cadastrale
    
    *  parcelles cadastrales avec les surfaces d'intersection à partir d'une géométrie saisie.
    
    * centroïde d'une parcelle ou d'une commune(localisants)

Grâce à l'__API Carto__ vous pouvez également :

* Connaître les groupements auxquels appartient une commune, ainsi que leurs compétences _(bientôt)_
* Savoir si une parcelle appartient à certains zonages en utilisant vos données ou des données openData

L’API Carto s’enrichissant progressivement, restez informés en suivant cette page, en visitant le site: http://apicarto.ign.fr/  ou [en nous contactant](mailto:apicarto@ign.fr).


## Informations complémentaires

#### Couverture du territoire

France métropolitaine et [DROM](https://fr.wikipedia.org/wiki/D%C3%A9partement_et_r%C3%A9gion_d%27outre-mer).

#### Coordonnées géographiques

Cette API utilise exclusivement des coordonnées géographiques.
Elle peut renvoyer des données au format JSON ou  [GeoJSON](http://geojson.org).

#### Qui peut utiliser cette API ? Demande de clé IGN

Tout le monde peut utiliser l'api mais une demande de clé IGN est indispensable.

#### Comment obtenir une clé IGN ?
Pour obtenir une clé permettant l’accès aux ressources du Géoportail, vous devez vous connecter au site : http://professionnels.ign.fr/  ou  http://api.ign.fr/accueil (pour une clé de développement)


#### Contact

apicarto@ign.fr
