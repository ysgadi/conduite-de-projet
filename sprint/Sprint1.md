# Sprint 1

## User stories

| ID us | Stories | Difficulté | Priorité | État |
|-------|:--------|:-----------|:---------|:-----|
|      | **En tant qu'utilisateur**              |
| u0   | je souhaite créer un compte (ID utilisateur, nom, mdp) |5 | 1 |TODO|
|      | **En tant que développeur**             |
| u1   | je souhaite pourvoir me connecter à mon espace pour pouvoir participer au projet | 2 | 4|TODO|
| u2   | je souhaite créer/modifier un projet (nom, description, URL du dépot Git et du cahier des charges) | 1 | 1 |TODO|
| u10  | je souhaite avoir accès à une liste de tous les projets afin de choisir les projets auquel je veux participer | 3 | 4 | TODO |
| u12  | je souhaite avoir accès aux listes des US | 3 | 4 | TODO |
| u13  | je souhaite pouvoir ajouter/modifier des issues (en dehors des périodes de sprints) pour m'adapter à l'avancement du projet. | 3 | 2 |TODO|

## Tâches

| ID tâche | Issue ID | Objectif | Artefacts | Dev | Dépendance | Coût j/h |État |
|----|:--------|:-----------|:---------|:-----|:--------|:------| :------|
| 0 | u1 | Réaliser la view de la page d'acceuil | html | shervin | 18 | 0.2 |TODO |
| 1 | u0 | Réaliser la view de la connexion | html | shervin | 18 | 1 |TODO |
| 3 | u12, u13 | Réaliser la view de la page du backlog | html | shervin | 18 | 0.2 |TODO |
| 4 | u10, u2 | Réaliser la view de la page qui liste les projets | html | shervin | 18 | 0.2 |TODO |
| 5 | u10 | Réaliser la view de la page de description d'un projet| html | shervin | 18 | 0.2 |TODO |
| 6 | u12 | Gérer la navigation dans la view | html | shervin | 13 | 0.2 |TODO |
| 7 | u2  | Définir la table des projets | SQL | antoine | 13 | 0.2 |DONE |
| 8 | u2  | Définir la table des Issues | SQL | antoine | 13 | 0.2 |DONE |
| 12 | u1  | Définir la table des Users | SQL | antoine | 13 | 0.2 |DONE |
| 13 | /  | Définir l'interface entre BD et Backend | txt | antoine | / | 0.5 |DONE |
| 14 | u0 | Mettre en place le systeme de création de compte | Node | younes | 18 13 | 5 |DONE |
| 15 | u1 | Mettre en place le systeme de connexion | Node | younes | 18 13 | 2 |DONE |
| 16 | u2 | Mettre en place le systeme de création de projet | Node | younes |  18 13 | 2 |DONE |
| 17 | u2 | Mettre en place le systeme de création d'issue | Node | antoine |  18 13 | 2 |DONE |
| 18 | u0, u1, u2, u12, u10, u12, u13 | Définir interface entre frontend et backend | Fichier Txt décrivant routes et modèles JSON | Mathieu | / | 0.5 |DONE |
| 19 | / | Implementer les routes avec les requetes vers la base de données | nodejs | antoine | 13 | 1 | DONE|
| 20 | u2 | Configurer docker pour avec les requetes vers la base de données | docker-compose.yml | mathieu | / | 1 | DONE|
