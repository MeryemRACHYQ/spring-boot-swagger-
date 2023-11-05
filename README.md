# spring-boot swagger 
# introduction
Ce projet est un Système de Gestion développé avec Spring Boot, Maven, Hibernate, JPA et une base de données SQL.
Il offre des fonctionnalités essentielles pour créer, lire, mettre à jour et supprimer (CRUD) des étudiants,
des rôles et des filières. Le projet garantit une manipulation efficace des données via une API RESTful, 
simplifiant ainsi le développement et la maintenance. L'intégration de Swagger facilite les tests
et offre une documentation interactive pour l'API. En utilisant ces technologies, le projet assure une gestion 
complète et conviviale des informations dans un contexte éducatif ou professionnel.
# les technologies utilisées 
-Spring Boot 
-Maven  
-JPA 
-Swagger 
-JPQL
-Postman
# fonctionnalités du projet 
 -Opérations CRUD (Create , Delete ,update) pour etudiant  
 
 -Opérations CRUD (Create , Delete ,update) pour role
 
 -Opérations CRUD (Create , Delete ,update) pour filiere
# la base de données 
![data base](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/a735d56f-129e-4de3-9e46-ccd73becf8db)
#POSTMAN
# get :
![get](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/b7c62ecc-1b92-49ba-9e93-e06d22afa4f0)
# put:
![put](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/d2fe001f-fed5-4165-ad42-2626d5753d52)
# delete:
![delete](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/a53b29ec-dd9f-4b0f-91b8-a8373d058e58)
# Swagger 
# Get:
![get2 swagger](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/9badf7c5-e5d7-4b38-9278-c190c84edb7a)
![get swagger](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/7cf01be4-e817-45ff-a5d4-f8651fa58fee)
# Post:
![post swagger](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/c08e5387-356a-494e-af80-8df9d8f648bb)
# put:
![put swagger](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/c464c893-2f80-4d0b-8a57-c73306015ec8)
# delete:
![delete swagger](https://github.com/MeryemRACHYQ/spring-boot-swagger-/assets/147452254/00e7ec1d-d686-4c70-8338-fe05834fd89f)
# Structure de projet :
Le projet est divisé en packages qui représentent différents aspects de l'application :

ma.projet.demo : Package principal de l'application. 

ma.projet.controller : Contrôleurs pour la gestion des étudiants, des rôles et des filières.

ma.projet.entities : Classes de modèle pour les étudiants, les rôles et les filières.

ma.projet.repositories : Repositories JPA pour les opérations de base de données.

ma.projet.service : Classes de service pour la logique métier.

ma.projet.dao : Interface IDao.
