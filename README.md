Ce projet comprend :
    Une API REST en Node.js/Express pour gérer des produits et des commandes
    Un client Dart (Flutter) pour interagir avec l'API

 Fonctionnalités
API (Backend)

Gestion des produits

    GET /api/produits : Lister tous les produits
    POST /api/produits : Ajouter un nouveau produit

 Gestion des commandes

    GET /api/commandes : Lister toutes les commandes
    POST /api/commandes : Créer une nouvelle commande

Persistance des données

    Stockage dans des fichiers JSON (produits.json, commandes.json)

Client Dart (Frontend)

 Interface Flutter pour :

    Afficher la liste des produits
    Ajouter de nouveaux produits
    Voir l'historique des commandes
    Créer des commandes
