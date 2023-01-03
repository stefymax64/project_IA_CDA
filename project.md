# Projet de détection des Fake News
## Résumé du projet
    -> Le phénomène des « fake news » ou « infox », revêt une importance particulière à l’ère digitale. Alors que les informations circulent plus librement que jamais, il est encore difficile de s‘assurer de la fiabilité de leur provenance. Ces fausses informations représentent un enjeu considérable, pouvant à la fois être utilisées dans le cadre de désinformation ou afin d’augmenter le trafic d’un article en devenant viral sur les réseaux sociaux.
## Contexte du projet
    -> L'ensemble de données ISOT Fake News est une compilation de plusieurs milliers de fausses nouvelles et d'articles véridiques, obtenus à partir de différents sites d'information légitimes et de sites signalés comme non fiables par politifact.com.
    -> L'ensemble de données contient deux types d'articles faux et de vraies nouvelles. Cet ensemble de données a été collecté à partir de sources du monde réel ; les articles véridiques ont été obtenus en explorant des articles de Reuters.com (site Web d'actualités). Quant aux faux articles de presse, ils ont été collectés auprès de différentes sources. Les faux articles de presse ont été collectés sur des sites Web non fiables signalés par Politifact (une organisation de vérification des faits aux États-Unis) et Wikipedia. L'ensemble de données contient différents types d'articles sur différents sujets, cependant, la majorité des articles se concentrent sur des sujets d'actualité politique et mondiale. 
    -> Les jeux de données identifient un titre, un texte, un sujet, une date.
## Développer une application d'intelligence artificielle
    -> Analyser un besoin en développement d’application mettant en oeuvre des techniques d'intelligence artificielle afin de produire les éléments de réponses techniques. 
    -> Concevoir une base de données relationnelle à l’aide de méthodes standards de modélisation de données. 
    -> Développer les requêtes et les composants d'accès aux données dans un langage adapté afin de persister et mettre à jour les données issues de l’application en base de données. 
    -> Développer le back-end de l’application d’intelligence artificielle dans le respect des spécifications fonctionnelles et des bonnes pratiques du domaine. 
    -> Développer le front-end de l’ application d’intelligence artificielle à partir de maquettes et du parcours utilisateur⋅rice, dans le respect des objectifs visés et des bonnes pratiques du domaine. 
    -> Améliorer l’application d’intelligence artificielle en développant une évolution fonctionnelle  pour répondre à un besoin exprimé par un client ou un utilisateur. 
    -> Maintenir l’application d’intelligence artificielle à l’aide des techniques de monitorage afin de détecter et corriger les éventuels dysfonctionnements. 
## Le besoin client
    Le client souhaite créer une application "public" qui permettra aux utilisateurs de vérifier la véracité de l'information qui circule sur Internet.
        -> l'utilisateur doit pouvoir rentrer un titre, un texte entier, une partie ou au minimum un mot, un sujet ainsi que la date de son information puis valider en cliquant sur un bouton.
        -> L'application doit pouvoir se connecter au programme de l'intelligence artificielle afin de détecter si l'information fournie par l'utilisateur est vraie ou fausse. Le programme IA renvoi la réponse à l'application qui affiche le résultat à l'utilisateur.
        -> Le client doit pouvoir accéder au panneau administrateur afin de mettre à jour le jeu de données et vérifier que le programme n'ai pas de potentiels dysfonctionnement. Il peut également visualiser des diagrammes visuels sur les mots, informations les plus demandées afin de faire un suivi.