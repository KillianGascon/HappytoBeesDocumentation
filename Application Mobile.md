# Description : 

Application Mobile de gestion de Rucher pour les apiculteurs. Cette application permettra de gérer les différentes ruches, le matériel utilisé pour celles-ci et les interventions qui ont étés effectuées. 

# Objectif 
- Gestion de plusieures ruches 
- Gestion du matériel utilisé par ruches 
- Gestion des interventions sur les ruches (extraction de cadres, pause de hausse, traitement, ....)
- Création de statistiques (force de la colonie, poid, production en fonction des années, ...)
## Fonctionnalités 
### Fonctionnalités principales 
- Gestion utilisateurs : 
	- Creation de compte 
	- Login 
	- Deconnexion 
	- Suppression de compte 
- Gestion d’une ou plusieurs ruches (en fonction du temps): 
	- CRUD Ruche 
		- photo de la ruche 
		- Numéro de ruche 
		- Nom de la ruche 
		- Nombre de cadre dans le corps 
		- Nombre de hausses 
		- poid 
- Gestion du matériel (cadres hausses corps, toit, ... ) 
- Production
- Interventions effectuées 
- Statistiques de la ruche

### Fonctionnalités Secondaires

- Gestion du rucher (Si on a le time) : 
	- CRUD rucher 
	- Differentes ruches 
	- Materiel 
- Gestion des Taches (Si on a le temps) 
- Si possible de la Oauth (optionnel)

# Figma / Design

## Lien figma : 

https://www.figma.com/design/AIVsGmxq49o7WIuRCmyxrs/Happy2Bee?node-id=29-187&t=VfuTlY5PAzPLuiKf-1

## Design :

On est parti sur un design épuré, on a pas encore trouvé les bonnes couleurs mais on partirait sur des couleurs se rapportant au miel et aux ruches(type bois, jaune, ... etc)

# Technos Utilisées :

## Frontend :

- Flutter : techno pour faire du dev cross-plateform IOS/Android
	- lien de la doc : https://docs.flutter.dev/

## Backend :

- Rust: une technologie multithreadée et qui va nous permettre de faire une API rapide et fiable
	- lien de la doc : https://doc.rust-lang.org/book/

## BDD :

- Postgres SQL : base de données polyvalente qui permet de gérer de grosses quantités de données (mieux que mysql)
	- lien de la doc : https://docs.postgresql.fr/

## Deployment :

- Coolify : techno self-Hosted qui permet de déployer facilement tout les services de notre application que ce soit la bdd, l'API ou autre.
	- lien de la doc : https://coolify.io/docs/
- Neon : techno utilisé pour le developpement pour héberger la bdd sans passer par coolify
	- lien de la doc : https://neon.tech/docs/introduction


# Github :

## Frontend :

https://github.com/KillianGascon/Happy2beesFrontend
## Backend :

https://github.com/KillianGascon/HappytoBeesbackend
## Doc :

https://github.com/KillianGascon/HappytoBeesDocumentation