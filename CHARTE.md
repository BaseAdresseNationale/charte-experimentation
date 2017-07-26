# Charte d'expérimentation

## Finalité de l'API de gestion

L'API de gestion a pour but d'organiser la production collaborative de la Base Adresse Nationale, pour la France métropolitaine et la France d'outre-mer.

Elle est destinée aux contributeurs de la base et non aux consommateurs des données.

Les consommateurs de données doivent utiliser les fichiers diffusées via le site [adresse.data.gouv.fr](https://adresse.data.gouv.fr)

## Objet de la charte

Ce document définit le cadre et les conditions d'utilisation de l'API de gestion pendant la phase d'expérimentation.

La phase d'expérimentation couverte par la présente charte démarre le 1er juillet 2017 et se termine le 15 octobre 2017.
Elle pourra être prolongée sur décision du Comité de Pilotage de la Base Adresse Nationale.

Cette phase est opérée en environnement de production et permet des évolutions accélérées.

## Contributeurs de plein droit

Les organismes suivants, de par leur statut de membres fondateurs de la Base Adresse Nationale, sont contributeurs de plein droit :

* l'[IGN][4]
* [La Poste][5]
* [Etalab](https://www.etalab.gouv.fr)
* [OpenStreetMap France](http://openstreetmap.fr/)

## Contributeurs signataires

Pendant la phase d'expérimentation, les types d'entités suivants peuvent demander à devenir des contributeurs de la Base Adresse Nationale, au travers de l'API de gestion :

* communes ;
* communautés de communes ;
* communautés d'agglomération ;
* communautés urbaines ;
* métropoles ;
* services départementaux d'incendie et de secours (SDIS) (limité à un participant) ;
* services d'aide médicale urgente (SAMU) (limité à un participant) .

Tout envoi d'une demande par une entité vaut acceptation et engagement à respecter la présente charte.

Les demandes sont étudiées par la communauté technique de la Base Adresse Nationale.

## Engagements

### Engagements des contributeurs signataires

Les signataires de la présente charte s'engagent à :

* contribuer à l'amélioration de la Base Adresse Nationale, sur leur périmètre géographique de compétence ;
* ne pas porter atteinte à l'intégrité de l'environnement de production ;
* ne déposer que des données éligibles à la [Licence Ouverte][1] ;
* ne pas moissonner la base de données de l'API de gestion.

### Engagements de la communauté technique

La communauté technique s'engage vis-à-vis des contributeurs signataires à :
* prendre en considération leurs remarques et suggestions ;
* leur apporter du support technique.

## Perte du statut de contributeur signataire

La communauté technique est habilitée à retirer unilatéralement le statut de contributeur signataire à toute entité ne respectant pas ses engagements.

## Accès à l'API par les contributeurs signataires

### Jetons

Tout contributeur signataire peut demander à obtenir des jetons d'accès à l'API en environnement de production.

Un jeton peut être fourni pour chaque dispositif client de l'API du contributeur.

Un jeton peut être révoqué unilatéralement par la communauté technique en cas de suspicion d'anomalie technique ou d'incident de sécurité.

### Droits d'accès

Les contributeurs signataires peuvent :
* Créer, modifier ou supprimer des numéros d'adresses
* Créer, modifier ou supprimer un ensemble d'adresses (voies, lieux-dits, résidences, zones commerciale, etc.)
* Créer, modifier ou supprimer les positions géographiques des adresses et leurs descriptions (type de position, source d'acquisition, etc.)

Les identifiants techniques de l'[IGN][4] et de [La Poste][5] ne peuvent pas être modifiés.

### Traçabilité, audit

Toutes les interactions d'un client disposant d'un jeton d'accès avec l'API sont tracées par le biais d'un outil d'analyse de l'API et auditables sur demande : nombre et type d'accès, objets de la BAN recherchés, communes de recherche, etc.

### Limitations techniques

Le gestionnaire de l'API est habilité à mettre en oeuvre des limitations techniques sur l'API. Ces limitations peuvent prendre la forme d'un nombre d'appel maximum par client et/ou par IP, sur une période donnée.

Ces limitations ont vocation à protéger l'environnement de production.

## Licence des données

### Données entrantes

Les _données Adresse_ déposées par les contributeurs via l'API de gestion doivent être libres de toute contrainte à la réutilisation.

### Données sortantes

Les données et métadonnées collectées via l'API de gestion ne peuvent être utilisées que dans le cadre de la contribution à la Base Adresse Nationale. Elles ne peuvent être diffusées.

Les _données Adresse_ réutilisables et diffusables sont celles diffusées via le site [adresse.data.gouv.fr](https://adresse.data.gouv.fr), sous [Licence Gratuite de Repartage][2] ou [Open Database Licence 1.0][3].

[1]: https://www.etalab.gouv.fr/wp-content/uploads/2017/04/ETALAB-Licence-Ouverte-v2.0.pdf
[2]: http://adresse.data.gouv.fr/pdf/licence-gratuite-repartage.pdf
[3]: https://vvlibri.org/fr/licence/odbl/10/fr
[4]: http://www.ign.fr
[5]: http://www.laposte.fr/entreprise/produits-et-services/sna-normalisation-des-adresses
