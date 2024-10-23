# PADIVAR
Solution didactique de diagnostique automobile

## Description du domaine
Dans le cadre de ses formations, la fondation Maison de l'Homme et des Sciences est amenée à faire effectuer à ses apprentis des diagnostiques automobiles. Ces diagnostiques se font électroniquement via un connecteur présent sur tous les véhicules depuis les années 2000. Bien que tous répondent au protocole OBD (On-Board Diagnosis) qui est opensource, chaque constructeur est resté libre de l'implémenter à sa façon. Cette liberté a engendré différentes "versions" (ou flavors, littéralement saveurs) du protocole, ce qui rend le déchiffrage de ses informations très difficile, voir quasi exclusif aux utilisateurs possédant des mallettes de diagnostique officielles. Ces mallettes permettent de communiquer avec les véhicules du constructeur qu'il a réalisé et coutent facilement plusieurs dizaines de milliers d'euros pour celles permettant le diagnostique de plusieurs marques différentes de véhicules. Ce cout s'explique principalement par l'achat des licences (des tables de code d'erreur diagnostique propriétaires ou DTC). L'objectif de PADIVAR est de développer une solution logicielle permettant un diagnostique complet du véhicule de façon dématérialisée à un utilisateur n'ayant pas ou peu a priori de connaissances techniques particulières.

## Specification du projet
| ID Fonctionnalité | Fonctionnalité | Description | Developeur |
| --- | --- | --- | --- |
| F001 | Sélection de l'interface de connexion | Le système permettra à l'utilisateur de choisir manuellement l'interface de connexion : USB, WIFI, Bluetooth, RJ45 ou Port Série (DB9).Une fois l'interface sélectionnée, le système effectuera une détection des périphériques disponibles pour cette connexion  | / |
| F002 | Connexion à l'outils OBD | Le système permettra à l'utilisateur de se connecter au véhicule via le port OBD avec le matériel choisi. Les types de matériels compatibles incluent : RawCan, ELM327, DS150 (Delphi), et WOW (Wurth Online World)  | / |
| F003 | Informations courantes | Le système permettra à l'utilisateur de visualiser les informations permises par le Mode 1  | / |
| F004 | Affichage des anomalies | Le système permettra, une fois connecté à la voiture, d'afficher les anomalies présentes de la voiture | / |
| F005 | Compatibilité OBD |Le système permettra à l'utilisateur de savoir quelle version du protocole OBD le véhicule utilise ET il lui permettra de sélectionner manuellement la version qu'il souhaite utiliser.  | / |
| F006 | Journal des défaillances | Le système permettra à l'utilisateur de consulter l'état du véhicule à un instant donné comme prévu par le Mode 2 | / |
| F007 | Liste des défaillances | Le système permettra à l'utilisateur de lister la liste des codes défauts enregistrés, comme prévu par le Mode 3 | / |
| F008 | Effacer les erreurs | Le système permettra à l'utilisateur d'effacer les codes d'erreurs et d'éteindre les voyants, comme prévu par le Mode 4 | / |
| F009 | Autodiagnostics sur les sondes à oxygène | Le système permettra à l'utilisateur de consulter les résultats de tests sur les sondes à oxygène, comme prévu par le Mode 5 | / |
| F010 | Données de diagnostic occasionnel | Le système permettra à l'utilisateur de consulter les données de diagnostic des système dits occasionnels, comme prévu par le Mode 6 | / |
| F011 | Liste des défaillances non confirmées | Le système permettra à l'utilisateur de consulter la liste des codes défauts enregistrés non-confirmés, comme prévu par le Mode 7 | / |
| F012 | Informations constructeur | Le système permettra à l'utilisateur de visualiser les informations concernant le véhicule tel que le numéro de série et les valeurs de calibration de base accessible par le Mode 9. | / |
| F013 | Défauts permanents | Le système permettra à l'utilisateur de consulter l'historique de ses erreurs avec le Mode 10. | / |
| F014 | Connectivité | Le système permettra à l'utilisateur de mettre ses données de diagnostique en ligne ET d'y accéder ultérieurement. | / |
| F015 | Visualisation des données | Le système permettra à l'utilisateur de visualiser d'un seul coup d'œil toutes les informations récoltées par le interrogations OBD. | / |
| F016 | Autodiagnostique systèmes divers | Le système permettra à l'utilisateur de consulter l'historique de diagnostique des systèmes auxilliaires prévus par le Mode 8 | / |


## Ressources
