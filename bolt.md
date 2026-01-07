---
title: Protections
icon: book
order: 290
---
# Les Protections

Ce plugin vous permet d'avoir tous vos conteneurs protégés par défaut : *coffres, coffres piégés, fours, haut fourneaux, fumoirs, distributeurs, droppers, barrils, composteurs, pupitres, boîtes de shulker, entonnoirs, balises, etc...*

Des conteneurs peuvent être protégés mais ne le sont pas par défaut. En voici une liste : *pancartes, pancartes suspendues, portes, trappes, portillons, bannières, bibliothèques sculptées, cadres, portes armure.*

### Commande de protection
---

``/lock`` : Créer une protection privée.  
``/lock public`` : Créer une protection publique. (Le coffre vous appartient toujours mais tout le monde peut déposer et prendre dedans. Les autres joueurs ne peuvent pas le casser.)  
``/lock display`` Permet de voir le contenu d'un conteneur sans pouvoir prendre ou déposer les objets à l'intérieur.  
``/lock private`` Permet de rendre privé une protection publique.  
``/lock deposit`` Permet à tous d'ouvrir le coffre et d'uniquement déposer des objets dedans.  
``/unlock`` : Supprimer la protection privée.  
``/bolt mode nolock`` Permet de rendre le conteneur directement lock/unlock au moment de la pose.  

### Ajouter un joueur à vos protections
---

``/bolt edit add <pseudo>`` : Clique droit sur le conteneur, permet d'ajouter un joueur à cette protection.  
``/bolt edit remove <pseudo>`` : Clique droit sur le conteneur, permet de retirer un joueur à cette protection.  
``/bolt trust add player <pseudo>`` : Ajouter le joueur en tant que membre de confiance, il a donc accès à toutes vos protections.  
``/bolt trust remove player <pseudo>`` : Retirer le joueur en tant que membre de confiance.  

### Autre
---
``/bolt info`` : Clique droit sur la protection, permet d'avoir les informations de celle-ci.  
``/bolt mode persist`` Permet de garder la dernière commande liée aux protections en persistance. (Refaire la commande pour désactiver)  
``/bolt mode nospam`` : Permet d'activer/réduire au silence les notifications au moment de la pose d'un conteneur.  
