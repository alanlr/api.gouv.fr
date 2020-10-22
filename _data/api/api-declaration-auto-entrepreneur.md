---
title: API Tierce Déclaration auto-entrepreneur
tagline: Connectez-vous directement à l’Urssaf pour déclarer les chiffres d’affaires pour le compte d’un auto-entrepreneur en tant que tiers déclarant
external_site: https://open.urssaf.fr/explore/?sort=modified
producer: urssaf
is_open: -1 # 1 means API is fully open
contact_link: contact.tiercedeclaration@urssaf.fr
doc_tech_link: https://portailapi.urssaf.fr/index.php?option=com_apiportal&view=definition&managerId=1&menuId=181&format=raw&stateReturn=L2ZyLz9JdGVtaWQ9MTgxJmFwaUlkPWNiNTUwNDk4LWMyOGItNGJiMS05MGUwLTliYjlkMjdlMTI0NCZhcGlOYW1lPUFQSSUyMFRpZXJjZSUyMERlY2xhcmF0aW9uJTIwYXV0by1lbnRyZXByZW5ldXImYXBpVmVyc2lvbj0xLjIuMCZhcGl0YWI9dGVzdHMmbWFuYWdlcklkPTEmbWVudUlkPTE4MSZvcHRpb249Y29tX2FwaXBvcnRhbCZyZW5kZXJUb29sPTImdHlwZT1yZXN0JnVzYWdlPWFwaSZ2aWV3PWFwaXRlc3Rlcg==&path=%2Fdiscovery%2Fswagger%2Fapi%2Fid%2Fcb550498-c28b-4bb1-90e0-9bb9d27e1244%3FswaggerVersion%3D2.0%26filename%3DAPI%2520Tierce%2520Declaration%2520auto-entrepreneur.json%26extensions%3Dfalse
doc_tech_external: https://portailapi.urssaf.fr/images/Documentation/ACOSS-Documentation-API-TDAEV1_v12.pdf
keywords:
  - Urssaf
  - Auto
  - entreprise
  - tiers
  - déclarant
themes:
  - Entreprise
last_update: 16/10/2020
---

L’API Tierce Déclaration auto-entrepreneur facilite l’accès aux éditeurs de logiciels, aux plateformes collaboratives et de services en ligne, aux données et aux démarches relatives à l’Urssaf pour le compte d’un auto-entrepreneur.

### A quoi sert l’API Tierce Déclaration auto-entrepreneur ?

L’API Tierce Déclaration auto-entrepreneur permet, pour le compte d'un auto-entrepreneur, d’accéder aux services de déclaration, d’obtention des montants des cotisations et contributions sociales des organismes de recouvrement concernés et d’ordonner le paiement desdites cotisations et contributions.

L’API Tierce Déclaration auto-entrepreneur permet en outre la consultation, l’ajout et la suppression de mandats Sepa avec l’Urssaf.

Du point de vue de l'usager, l'API TD Pajemploi permet au tiers déclarant de :

- Notifier l’Urssaf d’une autorisation de déclaration d’un auto-entrepreneur en son nom (mandat)
- Déclencher les démarches de déclarations et de paiements auprès de l’Urssaf, directement depuis son site Internet ou l’application mobile

### Fonctionnalités disponibles

Liste des fonctionnalités à titre d’exemple (liste non exhaustive) :

| Donnée       | Lien vers le jeu de données                                                                                                                                                                       |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Comptes      | Déterminer si un compte auto-entrepreneur est éligible à la tierce déclaration ainsi que de connaître sa périodicité déclarative.                                                                 |
| Mandats      | Notifier l'Urssaf de l'enregistrement ou de l’annulation d'un mandat de tiers déclarant obtenu par la plateforme pour cet individu.                                                               |
| Estimer      | Effectuer une estimation des cotisations sociales dues à l'URSSAF pour un auto-entrepreneur en fonction de chiffres d’affaires passés en paramètre.                                               |
| Declarer     | Effectuer la déclaration de chiffres d’affaires pour le compte de l’auto-entrepreneur identifié par son NIR ou son SIRET, et retourne les montants des cotisations sociales dues pour la période. |
| Payer        | Initialiser un télépaiement SEPA par l'Urssaf sur l'IBAN référencé en paramètre.                                                                                                                  |
| SEPA Mandats | Lister les mandats SEPA connus et d'enregistrer ou révoquer un mandat SEPA pour un auto-entrepreneur.                                                                                             |

### En savoir plus

#### Qu'est ce qu'un tiers déclarant ?

Un tiers déclarant est une personne physique ou morale qui assure, à titre professionnel, les déclarations sociales pour le compte de plusieurs entreprises clientes (cabinets d'expertise comptable, …).

#### A propos de l’API Tierce Déclaration auto-entrepreneur

L’API Tierce Déclaration auto-entrepreneur est une API REST gratuite avec un accès restreint qui utilise la cinématique d’authentification Oauth2 Client Credentials.

Pour accéder à cette API gratuite, il faut en faire la demande via le formulaire de demande de souscription ou via email et signer la licence d’utilisation.

Une fois le dossier validé, un accès API bac à sable puis un accès API production sont fournis.

En ayant recours à cette API, le Cocontractant est considéré comme tiers-déclarant au sens des articles L.133-11, R133-43 et R133-44 du Code de Sécurité sociale, et a obtenu mandat de la part des utilisateurs pour ce faire.