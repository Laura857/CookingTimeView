# CookingTimeView
> Projet de 4 jours A5
> 
> Découverte de NodeJS + d'un framework front au choix (VueJs)

NodejsProject est un projet qui permet de gérer des recettes. 
Une fois connecté, l'utilisateur à la possibilité d'ajouter des recettes (titre, description, ingrédients, image). Il peut aussi gérer son profil en modifiant ses données personnelles et son mot de passe, ainsi que se déconnecter.


# Stacks
- Vue.Js 3
- Express.Js

# Fonctionnalités développés
- Authentification (inscription, déconnexion, appel d'api possible uniquement via token)
- CRUD (get, put, delete, post pour la gestion des recettes)
- Web Socket (pour notifiés l'utilisateur lors de l'ajout d'une recette)
- Utilisation de Three.Js (un carré qui tourne lors de l'ajout d'une recette)

# Lancer l'application en local
Cloner le repository

```
git clone git@github.com:Laura857/NodejsProject.git
```

Lancer les commandes suivantes: 

```
npm install
npm run dev
```
Le server se lance et l'application est accessible depuis:  http://localhost:8080/#/

# Environnement
[CookingTimeView local](http://localhost:8080/#/)

[CookingTimeView Qual](https://cooking-time-view.herokuapp.com)
