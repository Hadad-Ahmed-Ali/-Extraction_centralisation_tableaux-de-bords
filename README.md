                   Type de poste : CDD étudiant, Rémunéré, Temps plein (Présenciel)
                   Date : 05/08/2024 jusqu'au 20/09/2024
                   Lieu : Univesité de Lille 1, centre administartif
                   

### Extraction et centralisation des données de l'université de Lille 1 pour la création de tableaux de bord stratégiques

##### Contexte 

L’Université de Lille, riche de nombreux départements académiques et administratifs, gère une volumétrie importante de données. Ces données sont dispersées dans des bases hétérogènes et sous-utilisées pour des analyses globales. Ma mission vise à extraire, centraliser et exploiter ces données pour créer des tableaux de bord interactifs, permettant un pilotage efficace des performances et une amélioration des processus décisionnels.

##### Description des missions

### Phase 1 : Extraction et centralisation des données

Objectif : Construire une base de données unifiée et fiable pour intégrer et préparer les données nécessaires à l’analyse.

      1. Identification des sources de données :

**Bases couvertes :** données issues des départements de Mathématiques, Informatique, Sciences économiques, Sciences biologiques, et Physique-chimie.

**Origines des données :**
- Logiciels d’inscription des étudiants
- Bases de gestion des examens et notes
- Données des ressources humaines (emploi du temps, budgets).       

      2. Audit et qualité des données :

- Réaliser un audit initial des sources pour évaluer la disponibilité, la fiabilité et la complétude des données.
- Identifier les éventuelles incohérences ou lacunes susceptibles de limiter l’exploitation des données.

      3. Extraction des données :

- Des requêtes SQL spécifiques et optimisées appliquant des techniques de filtrage, de jointures et d'agrégation, pour extraire les informations nécessaires des différentes bases de données
- Configuration des procédures stockées dans les bases de données pour automatiser les extractions semestrielles régulières
- Application des fonctionnalités **SQL Server** pour exécuter automatiquement ces requêtes pour chaque semestre.

      4. Nettoyage et transformation :

- Uniformiser les formats des données (types de variables, etc.) pour garantir leur cohérence.
- Corriger les anomalies comme les doublons, les valeurs erronées.

      5. Centralisation dans un Data Warehouse :

- Construire une base de données centralisée pour regrouper toutes les informations extraites.

      Mise à jour automatique des visualisation

L'outils **Power BI** est connecté directement à la **bases Data Warehouse** extraite via des requêtes configurées. Ce processus permet d'automatiser les mises à jour des données affichées sur les tableaux de bord une fois la **bases Data Warehouse** est mise à jours.

### Phase 2 : Création des tableaux de bord interactifs

Objectif : Fournir des outils d’analyse visuelle et dynamique aux décideurs de l’Université pour suivre les performances clés.

      1. Indicateurs clés sur les étudiants :

- Taux d’inscription : Par filière, niveau d’études et année universitaire.
- Taux de réussite et d’échec : Par département et semestre.
- Suivi des abandons et interruptions de parcours : Identifier les tendances selon l'origine géographique, genre et tranche d’âge.
- Caractéristiques démographiques : Répartition des étudiants par origine géographique, genre et tranche d’âge.

      2. Indicateurs budgétaires :

- Suivi des budgets : Analyse des allocations budgétaires par département et filière.
- Comparaison prévisionnel vs. réalisé : Identifier les écarts et les ajustements nécessaires.

### Livrables attendus :

- Un Data Warehouse opérationnel regroupant toutes les données pertinentes.
- Un ensemble de tableaux de bord interactifs répondant aux besoins spécifiques des décideurs.
- Une documentation claire sur le processus de collecte, d’intégration et d’analyse des données.








   
