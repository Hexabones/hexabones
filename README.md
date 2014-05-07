Hexabones
=========

![codeship status](https://www.codeship.io/projects/03864540-b767-0131-a9db-16d3760ea832/status)

Hexabones is a beautifully handcrafted framework for building brand new e-commerce PrestaShop themes.
Our goal is to provide an efficient tool for designers & developers to build high quality themes from scratch.
Hexabones is for PrestaShop themes like Bootstrap is for websites.

## Concept (fr)

Hexabones est un framework dont l'objectif est d'accélerer la création d'une boutique professionnelle sous PrestaShop.
Le projet s'insprire des dernières best pratices et solutions en matière de developpement web front-end.
De fait, Hexabones s'adresse plus particulièrement aux experts qui souhaitent partir d'une fondation puissante pour commencer leur propre travail.
L'experience utilisateur est au coeur de toute les décisions et les choix dans la conception du template squelette respectent pour le mieux les lignes directrices des sites de e-commerce les plus performants.

## Comment ça fonctionne ?

Hexabones ne se comporte pas comme un thème PrestaShop standard.
Sa principale particularité est de passer par le webservice de la boutique pour afficher son contenu.

 - Le thème n'utilise pas le moteur de template Smarty.
 - Le thème fonctionne de mannière déportée et il n'est pas nécessaire de le placer sur le même serveur que la boutique.
 - Toutes les vues sont en .html et peuvent être affichées sans que PHP ne soit installé. En fait il fonctionne même à partir du bureau.
 - L'affichage des données est traité côté client via javascript à l'aide d'Angular.js. Le contenu est récupéré au format JSON à l'aide de requêtes AJAX vers le webservice de la boutique.
 - SaSS et Compass sont utilisés pour fournir de la souplesse lors de la conception et de la maintenabilité à long terme.
 - Hexabones s'appuie sur le framework Bootstrap de Twitter pour le responsive design, les excellentes bases et la large communauté qu'il propose.
 - La structure est adaptée à la webanalyse et offre une granularité soignée pour interpreter les comportements des utilisateurs via les données de Google Analytics.
 - Un grand soin est apporté à la sémantique du markup et les préconisation SEO sont prises très au serieux ici :)
 - Fait avec passion par et pour la communauté. Tout profil 'webdev' orienté 'e-commerce' peut participer au projet pour l'améliorer avec ses connaisances.
