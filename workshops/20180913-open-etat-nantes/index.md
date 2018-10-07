---
date: 2018-09-13
location: Nantes
attendees: 15
event: https://www.etalab.gouv.fr/opengov-forum-open-detat-4-cuisinez-les-algorithmes-un-outil-de-mediation-numerique
---
# Forum Open d’État 4

## Médiation autour des données

À partir des usages de data.gouv.fr, quelles fonctionnalités à ajouter, à garder, à améliorer, à abandonner.

## Comment ils utilisent data.gouv.fr

### Bénédicte

Son profil :

* met quelques données en ligne ;
* terme service public de la donnée à éviter alors ce qu’il y a sur la page est intéressant.

### Service des retraites de l’État

Leur profil :

* met des données en ligne ;
* habitude à naviguer dans plein de sites.

### MESRI

Leur profil :

* en charge des données ouvertes ;
* scant’R : plateforme synchronisée avec data.gouv.fr via moissonnage pour référencer automatiquement les jeux de données ;
* recherche de jeu de données via un moteur de recherche classique.

### Open data France

Leur profil :

* fouille de data.gouv.fr sur les données publiques ouvertes par les territoires ;
* problématique de moissonnage ;

### Start-up qui utilise l’open data et les cartes IGN

Leur profil :

* moissonnage de data.gouv.fr et téléchargement. Consommation quotidienne de data.gouv.fr ;
* diffusion et traitement d’autres bases de données via réutilisations.

### EPN et MEAE

* productrice de données, question sur la structuration des données ;
* projets et animations sur la donnée ;
* accompagnement collectivités dans leurs démarches autour des données (question : toutes les données sur data.gouv.fr ou plateforme territoriale ?) ;
* dépose des données sur data.gouv.fr via un moissonneur (perte d’informations, données perdues) + problème de téléchargement de données ;
* cherche des données marrantes.

## Cas d’usage

### Cas 1 : commentaires sur la page d’accueil de data.gouv.fr

**Tâche demandée aux utilisateurs** : rechercher des données sur les élections présidentielles sur data.gouv.fr.

#### Choses à ajouter

* **exploration aléatoire par l’aspect ludique** : faire sortir du contenu autre que la recherche et le mettre en mode aléatoire (comme Wikipédia) ;
* **ajouter une carte interactive** : avec les données organisées par région (filtre géographique) ;
* filtre par objet (« tout sur : une école, un département) ;
* **plus de filtres de recherche dès la landing page** : « que les CSV » ou lien vers la recherche avancée ;
* **profil par usage** : la page d’accueil s’adresse beaucoup aux contributeurs et aux utilisateurs avertis (réflexion sur les parcours) ;
* **pictogramme par thématique** : pour une UX plus simple avec un survol pour du texte ;
* visualisation attractive ;
* **liste des producteurs dans le menu** : ex mettre en valeur les plus gros contributeurs ;
* **accessibilité pour les enfants** : datakids.gouv.fr, cela permettrait de faire de la médiation et de la pédagogie.

#### Choses à garder

* **domaine en gouv.fr** : côté institutionnel, à accentuer ;
* moteur de recherche ;
* mise en valeur des réutilisations ;
* valoriser les jeux du SPD et/ou les jeux de données certifiés.

#### Choses à améliorer

* structurer la page par public ;
* pouvoir naviguer d’une thématique à l’autre (s’inspirer de wikipédia) ;
* **thématiques** : on ne sait pas si elles sont incluantes ou excluantes ;
* remettre les thématiques dans la version mobile ;
* le moteur de recherche (le mettre plus gros) ;
* la barre de recherche en plus gros au centre ;
* raconter une histoire, c’est trop sérieux ;
* **bouton contribuer** : on ne sait pas à quoi cela correspond, clarifier les calls to action ;
* mieux mettre en valeur l’API.

#### Choses à laisser tomber

* abandonner les thématiques (sur google il n’y a pas de thématique) ;
* trop de blocs sur les réutilisations, et ils cachent un peu les données présentées sur la page d’accueil ;
* **clarifier le hiatus** : données publiques françaises vs. contribuez ;
* abandonner le slider (le carrousel de l’en-tête).

#### Choses entendues

> Si je suis citoyenne, je veux voir les résultats des élections, par de l’open data.

### Cas 2 : commentaires sur la page des résultats de recherche

**Tâche demandée aux utilisateurs** : passage à la recherche « élections présidentielles ». _Design review_ sur la page qui présente les résultats de recherche.

Problèmes avec l’auto-complétion et la suggestion : les utilisateurs ne lancent pas la requête jusqu’au bout

#### Choses à ajouter

* données moissonnées ou déposées qui n’y sont pas : montrer si un jeu de données vient de data.gouv.fr ou est moissonné ;
* **filtrer par date** : on ne sait pas vraiment ce que l’on cherche ;
* traçabilité des fichiers lorsque par exemple il s’agit d’un jeu de donnée qui vient d’un jeu de donnée de base ;
* ajouter le nom du producteur si le logo n’est pas visible : mieux afficher les producteurs ;
* tri par petite étoile ou par réutilisé (en fait cela existe mais ce n’est pas visible) ;
* classement par couverture spatiale et temporelle (les + gros en premier).

#### Choses à garder

* Les 3 onglets (jeux de données, réutilisations, réutilisations).

#### Choses à améliorer

* recherche avancée textuelle dans les filtres (pouvoir ajouter des mots à la recherche) ;
* **évaluation** : voir les commentaires en plus des étoiles dans les résultats ;
* filtres à gauche dans le sens de la lecture ;
* gestion des noms des bases de données identiques ;
* mettre les données les plus récentes en premier.

#### Choses à abandonner

* Le filtre mots-clés.

### Cas 3 : commentaire sur la présentation des datasets

**Tâche demandée aux utilisateurs** : cliquez sur le premier résultat qui figure sur la page des résultats de recherche et commentez ce que vous voyez.

#### Choses à ajouter

* pré-visualisation du fichier ;
* exploitation/visualisation ;
* taille du fichier.

#### Choses à garder

* formulaire de contact ;
* dans l’ensemble, ça marche bien.

#### Choses à améliorer

* **premier résultats de recherche** : ajouter fonctionnalité pour définir l’usage (citoyen/collectivité/entreprise) ;
* mieux mettre en valeur le format ;
* mieux documenter et présenter le jeu de données (éditorialisation) ;
* clarifier les termes « accès au téléchargement » et télécharger (le bouton télécharger charge directement) ;
* **les formats de téléchargement** : interrogations sur le fichier FTP !
* mettre en dessous du jeu de données des boutons vers la zone de discussion et de réutilisations ;
* contacter le producteur : ce n’est pas clair on pense qu’on envoie un mail et on va en bas de page ;
* **présenter pédagogiquement le format** : comment il s’utilise, il s’ouvre il s’exploite ;
* présenter plusieurs formats de téléchargement, dont des simples/mécanismes de conversion automatique des fichiers ;
* pas d’XML mais du CSV ;
* présenter l’URL originale si les jeux sont moissonnés.

## Conclusions

* Datastories à reprendre ?
* Recommandations éditoriales quand on présente les jeux de données (mettre des idées de _à quoi pourrait vous servir ce jeu de données_).
* Remontée d’issues publiques ?
* FAQ améliorée ?
* Leur montrer le forum ?
* Une grande question expliquée en données (cf. Perica).
* Expliciter l’algorithme du moteur de recherche.
