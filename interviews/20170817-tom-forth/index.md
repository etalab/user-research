---
date: 2017-08-17
location: The Open Data Institute
attendees:
- Tom Forth
- Thomas Parisot
---

# Entretien avec Tom Forth

## Présentation

Tom a récemment publié une étude intitulée "[Measuring tech in the UK and France in 10 steps](http://tomforth.co.uk/measuringtech/)" (en anglais). 

Tom a co-fondé la société [Imactivate](http://imactivate.com/) il y a désormais 5 ans. Elle est composée de 2 personnes, est basée à Leeds et se focalise sur du logiciel et de l'analyse de données.

À ce titre, il fait partie des membres d'[ODI Leeds](https://odileeds.org/), une branche de l'[Open Data Institute](https://theodi.org/) gérée sous licence par des entreprises partenaires.

Tom parle français et a étudié pendant une année à Paris.

## Thématique • Découverte des données

Deux jeux de données ont été principalement été utilisés dans le cadre de la compréhension économique des entreprises en France :

- 🔗 "[Base Sirene des entreprises et de leurs établissements (SIREN, SIRET)
](https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)"
- 🔗 "[BAN - Base Adresse Nationale](https://www.data.gouv.fr/fr/datasets/ban-base-adresse-nationale/)"

> J'ai découvert la Base Adresse Nationale via un [tweet d'Axelle Lemaire](https://twitter.com/axellelemaire/status/807189008023453696). Elle est très vocale sur Twitter.

---

🗣 Je cherchais la **liste des entreprises françaises** sur Google:

🔍 "[french companies database](https://www.google.co.uk/search?q=french+companies+database)"

![](google-search-companies.png)

1. Scan de la liste des résultats
1. 👉 "[List of company registers](https://en.wikipedia.org/wiki/List_of_company_registers#France)"   
![](wikipedia-company-registers-france.png)
1. 🔍 Recherche Google pour "[sirene database](http://google.co.uk/search?q=sirene%20database)"  
![](google-search-sirene-database.png)
1. 👉 "[Download the Sirene database](https://www.sirene.fr/sirene/public/static/acces-donnees?sirene_locale=en)"    
1. 👉 "[data-gouv](https://www.data.gouv.fr/en/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)"     
![](sirene-database-download.png)
1.   🔗 "[Base Sirene des entreprises et de leurs établissements (SIREN, SIRET)](https://www.data.gouv.fr/en/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)"  
🗣 Identification de la mise à jour mensuelle  
C'est plus facile à traiter et c'était **suffisant en terme de précision de données**.

![](dataset-sirene-stock.png)

> Lorsque je renouvelle mes recherches, **je vais sur le site officiel de la base SIRENE** car c'est là que **se trouve la documentation**.

---

🗣 Je cherche de temps en temps du côté des [données SNCF](https://ressources.data.sncf.com/explore/?sort=modified) ou de l'[API SNCF](https://data.sncf.com/api). 

---

🗣 Je regarde aussi du côté du [portail Open Data de Rennes Métropole](https://data.rennesmetropole.fr/). Notamment quand je travaille avec eux.

---

🤔 Je me souviens avoir été sur [data.gouv.fr](https://www.data.gouv.fr/en/) pour récupérer des données liées aux élections.

😤 À ce moment là, les téléchargements étaient lents.

💬 Je suis donc allé les récupérer directement du côté de chez [OpenDataSoft](https://www.opendatasoft.com/) — je connais quelques personnes là bas donc c'était facile.

---

🗣 J'obtiens aussi les données statistiques françaises via le [portail européen Eurostat](http://ec.europa.eu/eurostat/).

---

> **C'est plus fiable d'aller chercher la donnée chez les personnes responsables de leur maintenance**.

> Je sais que les **données sont toujours fraiches** chez les producteurs ou à l'INSEE.
 
> Je n'ai **pas de garantie de fraicheur chez les portails fédérateurs**.

> En plus, l'**interface utilisateur est souvent bien plus cohérente** du côté des portails de données des producteurs.
> Les portails fédérateurs sont sujets à être des fourre-tout.

> J'ai rarement vu un portail fédérateur de données qui fonctionne bien.

➡️ [Data Mill North](https://datamillnorth.org/) (région de Leeds, Angleterre)

--- 

> Pour mes usages, je cherche surtout des jeux de **données locales qui ont une granularité à la ville**.

💬 Si je ne les trouve pas dans Google, il y a peu de chances que je les trouve quelque part.


## Thématique • Compréhension des données

🤔 Je n'ai pas compris la différence entre [BAN](https://www.data.gouv.fr/en/datasets/ban-base-adresse-nationale/) et [BANO](https://www.data.gouv.fr/en/datasets/base-d-adresses-nationale-ouverte-bano/).

---

🤔 Je n'ai jamais trop compris les subtilités des licences d'utilisation.

---

🔗 "[Base Sirene des entreprises et de leurs établissements (SIREN, SIRET)](https://www.data.gouv.fr/en/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)"

Pour comprendre :

1.  Je **lis la description**, j'essaie d'en tirer des informations importantes ;
2.  Je **regarde la licence** — elle est **ouverte** ? Alors tant mieux, je peux utiliser les données.

🙃 La taille de la base Sirene ? Oui c'était une **surprise** d'en télécharger autant.

![](dataset-sirene-licence.png)

> Le moins il y a de contraintes, mieux c'est.

> **La meilleure documentation, ce sont les gens** : des exemples d'utilisation et les billets de blog explicatifs.

👍 Ah, je n'avais pas vu les réutilisations sous les ressources ! C'est super. Si j'avais su plus tôt ça m'aurait donné d'autres idées. J'aurais peut-être passé moins de temps à chercher de la documentation — surtout avec la version géocodée.

![](dataset-sirene-geocodes.png)


👍 Ah il y'a une réutilisation qui documente les colonnes ? Trop bien !

![](dataset-sirene-documentation.png)

👍 La rubrique "Contributions communautaires" ? C'est une très bonne idée.

🤔 C'est dommage par contre qu'elle soit si bas dans la page, et aussi peu visible.


## Thématique • Utilisation des données

> Est-ce que je republie des jeux de données ? Non car ça prend **trop de temps et d'efforts** — un temps pour lequel on n'est pas payé. On ne peut pas se le permettre.

> C'est d'ailleurs souvent peu pertinent (on enlève des colonnes, nettoie et filtre des lignes).    
> Cela incombe qu'on maintienne les mises à jours des jeux de données dérivés. On ne

---

> Entre une licence qui oblige à la redistribution des données et celle qui n'oblige pas à la redistribution des données, **je choisirai toujours la licence qui n'oblige pas à la redistribution des données modifiées**.

💬 Par contre **je partagerai toujours les artéfacts issues de l'analyse des données**.

> Principalement car **je ne _modifie_ pas les données mais les _adapte_ au contexte de mon projet**.

---

😤 Les données sur les entreprises britanniques ne sont pas très complètes et coûtent cher — j'en aurai des bien meilleures auprès de compagnies privées, mais ça me coûtera encore plus cher.

👍 Les données françaises de la base Sirene sont largement bien **plus utiles et plus riches**.

---

😤 La manipulation de données géographiques au Royaume-Uni est un casse-tête sans nom : les lieux sont réaffectés régulièrement (pas de continuité possible entre 2 mises à jour), il n'y a pas de coordonnées GPS et il n'y a pas de base d'adresse nationale _gratuite_.

💬 C'est un **gros plus** si le couple latitude/longitude est présent dans les jeux de données.

💬 La **consistance des identifiants** est primordiale.

➡️ [Classification géographique européenne NUTS](http://ec.europa.eu/eurostat/web/nuts/overview)

---

🔗 "[Base Sirene des entreprises et de leurs établissements (SIREN, SIRET)
](https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)"

> **Je ne pouvais pas trouver la documentation** donc j'ai déblayé à la main, notamment en **supprimant les colonnes qui me sont inutiles**.

🤔 Pourquoi il y a autant de colonnes ?

👍 J'ai découvert qu'il y avait des codes NAF complémentaires pour chaque entreprise, ça permet de gagner en subtilité dans l'analyse.

> Ça nous a permis de voir que les boutiques _Orange_ emploient chacune environ 10 personnes ; tout en sachant combien de salarié·e·s travaillaient en tout pour le groupe.

🛠 Cf. colonnes `LIBTEFEN`, `EFETCENT` et `EFENCENT`.

> **En général on va vite** parce qu'on n'a pas le temps de s'étaler à comprendre la signification de chaque colonne.

---

😊 Un de mes jeux de données favori, c'est le menu des cantines scolaires de Rennes.

🔗 "[Menus des cantines des écoles](https://data.rennesmetropole.fr/explore/dataset/menus-cantines/)"

---

😤 C'est **pénible quand les ressources ne sont pas encodées en UTF-8**, je me retrouve avec des caractères bizarres (j'imagine pour les accents etc.) 

## ROTI • Retour sur le Temps Investi

👍 Cet entretien m'a été utile pour 2 raisons :

1. pour mieux comprendre ce qui se passe en France ;
2. parce que j'ai la chance de pouvoir impulser du changement au Royaume-Uni.

> On peut changer les choses en Angleterre si on dit qu'elles sont mieux faites en France.

🗣 L'**enjeu de la couverture et de la granularité des données** est important :

- les données nationales sans granularité à la commune sont peu utiles ;
- c'est "facile" d'impulser l'ouverture des données au niveau national mais chaque acteur local doit _actionner_ cet effort de lui-même, avec son propre argent ;
- or les données locales sont les plus _utiles_ car elles ont l'impact le plus direct sur nos vies.