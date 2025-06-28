+++
date = '2025-06-18T08:02:05+02:00'
draft = false
title = 'Conférences DataFrogs'
+++

DataFrogs est une conférence communautaire gratuite sur Microsoft SQL Server.

<!--more-->

## Samedi 28 juin 2025, en ligne

DataFrogs est une conférence communautaire gratuite sur Microsoft SQL Server.

La session 2025.06 aura lieu le samedi 28 juin en virtuel (Les liens pour les sessions Microsoft Teams seront disponibles quelques jours avant la conférence).

Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogs2025-067322990104753471488) pour obtenir les informations pratiques.

Il y aura cette fois-ci cinq sessions, la conférence se tiendra du matin jusqu'en fin d'après-midi. La dernière session sera une session _Questions/Réponses_ où vous pourrez poser vos questions, partager vos expériences, etc. à micros ouverts. Profitez-en !

Les sessions seront disponibles pour tous, et les enregistrements seront ensuite posés sur [la chaîne YouTube de DataFrogs](https://www.youtube.com/@datafrogs).

## Programme

| Heure | Session | Qui | Lien |
| -------- | ------ | ------ | ------ |
| 09h00 | [Retour d'expérience client sur le change data capture et la gestion des opérations DDL]({{< relref path="#cdc" >}}) | [Clément Hugé](https://www.linkedin.com/in/clementhuge/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_ZTU5OGU2ODctMzI0NS00ZGM4LTk0NjMtMDI3MjQyODQ1OWFj%40thread.v2/0?context=%7b%22Tid%22%3a%22c6f8f5e5-ffac-4e60-83b0-a40c7405938d%22%2c%22Oid%22%3a%22adacf689-b9a1-4dcb-9aa9-5b5d04d1496f%22%7d) |
| 10h15 | [Les Nouveautés dans SQL Server 2025, IA ready !]({{< relref path="#sql2025" >}}) | [Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) et [Stéphane Scherrer, Microsoft](https://www.linkedin.com/in/stephanescherrer/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_Mzk2MWMyMjYtMjdjNC00MzFiLWFmMjAtN2E4NDkyODI1Yjc3%40thread.v2/0?context=%7b%22Tid%22%3a%22c6f8f5e5-ffac-4e60-83b0-a40c7405938d%22%2c%22Oid%22%3a%22adacf689-b9a1-4dcb-9aa9-5b5d04d1496f%22%7d) |
| 13h30 | [Les synonymes dans SQL Server + Projet SQL Server dans Visual Studio]({{< relref path="#synonymes" >}}) | [Sébastien Kobenan](https://www.linkedin.com/in/sebastien-kobenan/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_OWRlN2I2MDYtZTU1Yi00NjJhLWFjOGQtYTA0MzQ0MDJjYTMz%40thread.v2/0?context=%7b%22Tid%22%3a%22c6f8f5e5-ffac-4e60-83b0-a40c7405938d%22%2c%22Oid%22%3a%22adacf689-b9a1-4dcb-9aa9-5b5d04d1496f%22%7d) |
| 15h15 | **CHANGEMENT** [Verrouillage optimiste vs pessimiste… Les implémentations dans les SGBDR]({{< relref path="#verrouillage" >}}) | [Frédéric Brouard, SQL Spot](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_ZDA3ZmEyZDQtMTQ0MS00ODEyLWE1YjgtOTQxM2Q2Mzk1NzI1%40thread.v2/0?context=%7b%22Tid%22%3a%22c6f8f5e5-ffac-4e60-83b0-a40c7405938d%22%2c%22Oid%22%3a%22adacf689-b9a1-4dcb-9aa9-5b5d04d1496f%22%7d) |

## Programme détaillé

### 09h00 &#10148; Retour d'expérience client sur le change data capture et la gestion des opérations DDL {#cdc}

[_Clément Hugé_](https://www.linkedin.com/in/clementhuge/)

Après une rapide présentation de la fonctionnalité et des avantages et inconvénients, nous nous attarderons sur un cas client où CHDS LLC a implémenté une solution élégante pour synchroniser les événements capturés avec les changements de structure. Nous verrons les avantages et inconvénients et comment cette implémentation a permis de réduire les régressions de performance dans un contexte de déploiement CICD.

### 10h15 &#10148; Les Nouveautés dans SQL Server 2025, IA ready ! {#sql2025}

[_Julien Pierre, Microsoft_](https://www.linkedin.com/in/julien-pierre-15782127/) et [_Stéphane Scherrer, Microsoft_](https://www.linkedin.com/in/stephanescherrer/)

SQL Server 2025 : l’IA s’invite au moteur

SQL Server 2025 est bientôt là, et il est prêt pour l'IA ! Découvrez les dernières avancées du moteur SQL Server, avec une attention particulière sur les nouvelles fonctionnalités d'IA générative. Julien Pierre et Stéphane Scherrer (Microsoft) vous guideront à travers les nouveautés majeures, y compris les améliorations de performance, la gestion des données vectorielles, et les optimisations du Query Processor. Préparez-vous à explorer comment SQL Server 2025 transforme la gestion des données et ouvre de nouvelles perspectives pour les développeurs, les DBA et les architectes de données.

### 13h30 &#10148; Les synonymes dans SQL Server + Projet SQL Server dans Visual Studio {#synonymes}

[_Sébastien Kobenan_](https://www.linkedin.com/in/sebastien-kobenan/)

**Sujet 1 : Les synonymes dans SQL Server**

Vous avez une ou plusieurs bases de données SQL Server. 

Vous avez plusieurs applications clientes qui utilisent ces bases de données

Vous venez d'adopter une nouvelle convention de nommage pour les objets (tables, procédures stockées, fonctions, etc.) de vos bases de données 

Comment modifier les noms de vos objets sans impacter les applications clientes ?

C'est ce que je vous propose de voir aux travers des synonymes dans SQL Server.

**Sujet 2 : Projet SQL Server dans Visual Studio**

Vous développez une base de données SQL Server et vous souhaitez pouvoir versionner le code via git ? Cette session est  faite pour vous.

Nous allons voir comment créer un projet de base de données dans Visual Studio, versionner et déployer le code sur un ou plusieurs serveurs de base de données.

### 15h15 &#10148; Verrouillage optimiste vs pessimiste… Les implémentations dans les SGBDR {#verrouillage}

[_Frédéric Brouard, SQL Spot_](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761)

**Optimiste ou pessimiste ? Le vrai visage du verrouillage selon votre SGBD**

Oracle, PostgreSQL, SQL Server : chacun a sa philosophie du verrou. Frédéric Brouard (alias SQLPro) vous propose un tour d’horizon comparé des stratégies de verrouillage optimiste et pessimiste, avec un focus approfondi sur SQL Server. Parce que comprendre les choix du moteur, c’est déjà optimiser vos transactions.

Dans cette session, Frédéric Brouard explore les mécanismes de gestion de la concurrence dans les principaux SGBDR du marché. Vous verrez comment Oracle, PostgreSQL et SQL Server mettent en œuvre les stratégies de verrouillage optimiste et pessimiste, aussi bien au niveau des transactions que du moteur.
Un focus détaillé sur SQL Server permettra d’illustrer les subtilités des niveaux d’isolation, du snapshot isolation, du row versioning, des verrous explicites et implicites, et des impacts sur les performances. Une session indispensable pour tous ceux qui conçoivent des applications transactionnelles robustes.
