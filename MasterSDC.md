---
title: Master SDC
icon: book
order: 2
---

# Master SDC

Ce plugin vous permet de trier vos items simplement. 
Chaque objet placé dans le coffre **Alpha** est envoyé vers le coffre **Bêta** correspondant, selon les filtres que vous avez définis.

---

### Le Coffre “Alpha” (Coffre d’Entrée)
---
Le coffre **Alpha** est le point de départ de votre salle des coffres.  
C’est dans ce coffre que vous déposerez les objets à trier.
Pour créer ce coffre alpha, placez un coffre simple ou double puis executez cette commande :
``/sdc create alpha <nom de votre salle des coffres>``  Exemple : _/sdc create alpha salledescoffres_  ->
Faites ensuite un clic droit sur le coffre.  
Attention, un seul coffre alpha peut etre créer par joueur.

### Le Coffre “Beta” (Coffre de Sortie)
---
Les coffres Bêta sont les coffres de sortie, ceux où les items seront triés.
Ces coffres peuvent contenir un ou plusieurs filtres de tri.
Pour créer un coffre Bêta, deux solutions s’offrent à vous :
1. Placez un coffre simple ou double puis executez cette commande:
Placez un coffre simple ou double, puis exécutez cette commande :
``/sdc create beta <nom de votre salle des coffres> <item>``
(Possibilité d’ajouter plusieurs filtres en même temps en les séparant par un espace.)
Exemple : _/sdc create beta salledescoffres COBBLESTONE COBBLESTONE_SLAB_  ->
Faites ensuite un clic droit sur le coffre.

2. Placez un coffre simple ou double, puis exécutez cette commande :
``/sdc create beta <nom de votre salle des coffres>``
Prenez en main l’item que vous souhaitez trier et faites un clic droit sur le coffre avec cet item.
Si vous ne tenez aucun item au moment du clic, ce coffre aura un filtre “Default”, ce qui aura pour conséquence d’envoyer tous les items non triés dans ce coffre.


### Ajouter un filtre
---
Vous pouvez ajouter un filtre à un coffre Bêta possédant déjà un ou plusieurs filtres.
Pour cela, exécutez cette commande :
``/sdc addFilter <item>``  
Vous pouvez aussi ne pas préciser d’item et faire comme lors de la création du coffre Bêta, en cliquant sur le coffre avec l’item souhaité dans votre main.

### Supprimer un filtre ou un coffre
---
Vous pouvez supprimer tous les filtres d’un coffre Bêta avec une seule commande :
``/sdc remove``

Vous pouvez supprimer un seul filtre appliqué à un coffre Bêta avec cette commande :
``/sdc removeFilter <item>``

À noter : vous ne pouvez pas supprimer votre coffre Alpha tant que tous les coffres Bêta ne sont pas supprimés.

### Ajouter ou supprimer un membre
---
Vous pouvez ajouter ou supprimer un membre de votre salle des coffres.
Celui-ci pourra modifier votre salle des coffres.

Pour ajouter un membre, exécutez cette commande :
``/sdc share add <pseudo>``  
Pour supprimer un membre, exécutez cette commande :
``/sdc share remove <pseudo>``

### Foire aux questions
---

- **Est-ce que je peux avoir plusieurs salles des coffres ?**
Non, vous pouvez créer une seule salle des coffres, car un seul coffre Alpha par joueur est autorisé.

- **Quel est le rayon d'action du coffre alpha ?**
Le coffre Alpha peut trier des items jusqu’à 250 blocs autour de lui.

- **Il y a t'il une limite de coffre beta ?**
Oui, le nombre de coffres Bêta est limité.
Vous débloquez 20 coffres Bêta par niveau de joueur.
Le grade VIP permet de débloquer 250 coffres directement, et le grade Master permet d’en avoir 1000.
C’est la limite maximale.

- **Puis-je supprimer mon coffre Alpha ?**
Non, pas tant qu’il reste des coffres Bêta associés à la même salle des coffres.

- **Puis-je avoir plusieurs coffres avec les même filter ?**
Oui, le coffre Alpha enverra les items en priorité vers le premier coffre créé.
Lorsque celui-ci sera plein, il enverra les items vers le second.

- **Puis-je trier des items avec des noms personnalisés (via anvil ou plugin) ?**
Oui, le tri se fait selon l’ID de l’item, donc un papier renommé ira tout de même dans le coffre à papier.

- **Puis-je retrouver ces informations en jeu ?**
Oui, grâce à la commande suivante :
``/sdc help``

- **Puis-je connaitre les filtres et information d'un coffre de la salle des coffres ?**
Oui, pour connaitres les informations lié à un coffre beta vous pouvez executez la commande suivante:
``/sdc info`` suivi d'un clic-droit.

  Vous retrouvez les informations suivante sur les coffres alpha:
  - À qui appartient la salle des coffres
  - Le nom de la salle des coffres  

  Vous retrouvez les informations suivante sur les coffres beta:
  - Le filtre du coffre 
  - Ou se situe le coffre alpha
  - À qui appartient la salle des coffres
