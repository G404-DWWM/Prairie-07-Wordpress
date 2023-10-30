# Prairie-07-Wordpress

## Exercices Les Bases De Données




## 👪️Exercice de groupe

Pour comprendre SQL vous allez imaginer la BDD du centre de formation.

Ensuite avec les connaissances acquises, vous allez imaginer le **schéma **de cette BDD :



* Combien de tables créer ?
* Quelles colonnes dans ces tables ?
* Quel type de données ?
* Quelles relations peut-il y avoir entre les différentes tables ? 

 
Une fois ce schéma réalisé (sur [draw.io](https://app.diagrams.net/) ou [drawSQL](https://drawsql.app) par exemple) vous allez créer cette BDD dans PhpMyAdmin en utilisant uniquement des commandes SQL !  
 



# 📃Ressources :

[Cours et Tutoriels sur le Langage SQL](https://sql.sh/)



# 🤷Exercice individuel ou en groupe

Un cours sur le langage SQL n’est vraiment utile que si on essaye de le mettre en pratique dans un contexte d’usage réel.

Prérequis

Télécharger les bases de données d’exemples, qui seront utilisées au sein des exercices.

Pour cela créez une base de données et ajoutez ces 2 tables :



* Table “[villes de France](https://sql.sh/ressources/sql-villes-france/villes_france.sql)” (8.4Mo)
* Table “[départements de France](https://sql.sh/ressources/sql-departement-france/departement.sql)” (7.9Ko)

_Astuces : gardez une sauvegarde de ces tables avant d’effectuer les exercices._

**Le but de cette exercice est de trouver les requêtes SQL permettant d’effectuer chacune des demandes suivantes :**



1. Obtenir la liste des 10 villes les plus peuplées en 2012
2. Obtenir la liste des 50 villes ayant la plus faible superficie
3. Obtenir la liste des départements d’outres-mer, c’est-à-dire ceux dont le numéro de département commencent par “97”
4. Obtenir le nom des 10 villes les plus peuplées en 2012, ainsi que le nom du département associé
5. Obtenir la liste du nom de chaque département, associé à son code et du nombre de commune au sein de ces département, en triant afin d’obtenir en priorité les départements qui possèdent le plus de communes
6. Obtenir la liste des 10 plus grands départements, en terme de superficie
7. Compter le nombre de villes dont le nom commence par “Saint”
8. Obtenir la liste des villes qui ont un nom existants plusieurs fois, et trier afin d’obtenir en premier celles dont le nom est le plus souvent utilisé par plusieurs communes
9. Obtenir en une seule requête SQL la liste des villes dont la superficie est supérieur à la superficie moyenne
10. Obtenir la liste des départements qui possèdent plus de 2 millions d’habitants
11. Remplacez les tirets par un espace vide, pour toutes les villes commençant par “SAINT-” (dans la colonne qui contient les noms en majuscule)


# 🏆️ Objectifs



* j'ai compris l'utilité d'une base de données
* je sais utiliser les commandes de base de SQL
