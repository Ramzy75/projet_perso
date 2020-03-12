
-

# 1/ Descprition du projet :


    Créer en 1997 Netflix est une entreprise multinationale, opérant a distribution et l'exploitation d'œuvres cinématographiques et télévisuelles par le biais d'une plateforme.
        Ce projet consiste examiner le produit proposer par le service de vidéo à la demande par un abonnement qui a commence en 2007.
        Cet ensemble de données se compose des séries télévisées et des films disponibles sur Netflix entre 2010 et 2019.
        L'ensemble de données est collecté auprès de Flixable qui est un moteur de recherche Netflix tiers.

# 2/ La problématique : 


    Dans ce projet nous exposons notre problématique de recherche en présentant d'abord à travers ce jeux de données un survol de l'entreprise Netflix et du mode de fonctionnement de son service. Puis nous présentons notre questionnement de recherche centré sur la configuration des données disponible, à partir de la création d'un modèle de recherche et de recommandation. Nous terminons en formulant une interpretation et en justifiant la pertinence de notre recherche. 
 

3/ Processus technique :

    1. Identifier les sources de données / Expliciter la collecte :

    * L’organisme ayant publié la source > Kaggle est une plateforme web organisant des compétitions en science des données. Sur cette plateforme, les entreprises proposent des problèmes en science des données et offrent un prix aux datalogistes obtenant les meilleures performances.  https://stackoverflow.com/questions/59724560/neither-atom-or-visual-code-shows-dataset-output
    
    * Le format de la source > (.CSV)

2. Comprendre les modèles des sources
    • Tâche :
    > Examiner le•s jeu•x de données pour décrire les différents concepts dont ils rendent compte et qui seront utiles pendant l’enquête.
    • Livrable : Modèle conceptuel 
    > Des schémas du style « Entité-Association », permettant de comprendre l’organisation conceptuelle des données. (En option) Dans la mesure du possible, ces schémas retraceront les aspects “sémantiques” des associations et les contraintes s’exerçant
    sur elles.

3. Examiner les données
    •     Le jeu de données présent sur cette page possède trop de défauts pour être utilisé. La visualisation réalisée vous permettra de comprendre pourquoi : Mal formaté structuré avec des virgules comme séparateur, mais aussi dans certaines chaînes de champs de colonnes et des listes contenant des virgules. j'ai décidé donc de séparer les champs qui contiennent des virgules dans des nouveaux champs des colonnes ['director'], ['cast'], ['contry'], ['listed_in'].
    •     J'ai aussi mis en forme les colonnes :
            - L'action consiste à rajouter une nouvelle colonne ['month'] à travers la colonne ['date_added'].
            - L'action consiste à transformer la colonne ['duration'] en format numbre. 

    • Livrable : Etat des lieux des données 
    > Une synthèse des problèmes rencontrés sur ces données : 
     > * Une estimation de la qualité des données.
     > * Une liste des problèmes rencon-trés.
     > * Les décisions prises pour pallier ces problèmes.
     > * La description d’un processus automatique de correction des données.

4. Produire un modèle de sortie pour l’enquête
    • Tâche > Sélectionner parmi les données disponibles celles qui auront une importance dans les traitements ultérieurs.
    • Livrable:
    > Une fois le modèle établi, on rendra : 
    > * Un schéma représentant le « modèle conceptuel » 
    > * Un schéma représentant le « modèle logique », c’est-à-dire le précédent converti en termes opérationnels (classes, objets typés, etc.).

5. Aligner les modèles
    • Tâche 
        > Comparer les (éventuelles) différentes sources pour harmoniser leurs descriptions en vue de l’enrichissement du modèle de sortie avec des données fiables.
    • Livrable 
        > Un processus technique permettant d’harmoniser les sources vers le modèle de sortie.
    

- Etudier le contenu de jeux de données :
    * Statistiques :
        - Comprendre le contenu disponible dans différents pays
        - Identifier un contenu similaire en faisant correspondre des fonctionnalités textuelles
        - Analyser le réseau des acteurs / réalisateurs et trouver des informations intéressantes
        - Est-ce que Netflix se concentre de plus en plus sur la télévision plutôt que sur les films ces dernières années
        
    '''
    Tirez parti de jeux de données 
    Rester simple :
    Recherche flexible : Une fois les données exposées, il devrait être facile de les interroger régulièrement et de les rendre disponibles
    '''
    * Création du moteur de recherche et de recommandation : 
        - Comprendre les logiques prescriptives des systèmes de recommandation.
        - Fournissez une recherche unifiée
        - Proposer une recommandation via un moteur de recherche
-
-------------------------------------------------------------------------------------------------------------------------------------------------------
4/ Interprétation :
-------------------------------------------------------------------------------------------------------------------------------------------------------
Comment Cinematch a-t-il évolué depuis 2009, année de la fin du concours Netflix Prize et de la divulgation des solutions d'amélioration des algorithmes ?
Quelles sont les stratégies employées par Netflix pour «enseigner» son programme d'action aux usagers, sur le site web de l'entreprise ? 

Les analyses de ces trois actants nous ont permis de conclure que la configuration des usages par le service de vidéo à la demande Netflix découle de quatre aspects principaux :
    a - la personnalisation.
    b - la création de catégories comme mode de consommation encouragé.
    c-  l' adaptation 
    d-  les feedbacks 