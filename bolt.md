# Les Protections

Le plugin **Bolt** protège automatiquement tes conteneurs dès que tu les poses : personne d'autre que toi ne peut les ouvrir ni les casser. Tu n'as rien à faire pour être protégé.

## Ce qui est protégé

### Protégé par défaut

Tous ces blocs sont verrouillés dès leur pose :

- coffres et coffres piégés
- fours, hauts fourneaux et fumoirs
- distributeurs et droppers
- barils
- composteurs
- pupitres
- boîtes de shulker
- entonnoirs
- balises
- etc.

### Protégeables, mais pas par défaut

Ces blocs peuvent être protégés, mais **tu dois le faire toi-même** avec `/lock` :

- pancartes et pancartes suspendues
- portes, trappes et portillons
- bannières
- bibliothèques sculptées
- cadres
- portes-armures

## Démarrage rapide

1. **Pose** un conteneur : il est protégé automatiquement.
2. Pour **partager** une protection avec un ami, utilise `/bolt edit add <pseudo>`, puis fais un clic droit sur le conteneur.
3. Pour **retirer** une protection, utilise `/unlock`, puis fais un clic droit sur le conteneur.

> **⚠️ En cas de vol ou de grief,** ouvre un **ticket sur le Discord** : le staff peut intervenir (voir le [règlement](/rules/)).

## Commandes de protection

Après avoir tapé la commande, **fais un clic droit sur le conteneur** concerné.

| Commande | Effet |
|---|---|
| `/lock` | Crée une protection **privée** |
| `/lock public` | Crée une protection **publique** : le conteneur t'appartient toujours, mais tout le monde peut y déposer et y prendre des objets. Les autres joueurs ne peuvent pas le casser |
| `/lock display` | Permet de **voir** le contenu du conteneur sans pouvoir prendre ni déposer d'objets |
| `/lock deposit` | Permet à tous d'**ouvrir** le conteneur et d'y **déposer** des objets, sans pouvoir en prendre |
| `/lock private` | Rend **privée** une protection publique |
| `/unlock` | **Supprime** la protection |

## Partager tes protections

### Pour une protection précise

| Commande | Effet |
|---|---|
| `/bolt edit add <pseudo>` | Ajoute un joueur à cette protection (clic droit sur le conteneur) |
| `/bolt edit remove <pseudo>` | Retire un joueur de cette protection (clic droit sur le conteneur) |

### Pour toutes tes protections

| Commande | Effet |
|---|---|
| `/bolt trust add player <pseudo>` | Ajoute le joueur comme **membre de confiance** : il a accès à **toutes** tes protections |
| `/bolt trust remove player <pseudo>` | Retire le joueur de tes membres de confiance |

> **💡 Astuce :** ne mets en confiance que des joueurs sur qui tu peux compter, car ils auront accès à tous tes conteneurs protégés.

## Autres commandes

| Commande | Effet |
|---|---|
| `/bolt info` | Affiche les informations d'une protection (clic droit dessus) |
| `/bolt mode persist` | Garde la dernière commande de protection active en continu. Refais la commande pour désactiver le mode |
| `/bolt mode nospam` | Réduit au silence (ou réactive) les notifications au moment de la pose d'un conteneur |
| `/bolt mode nolock` | Pose un conteneur sans qu'il soit protégé automatiquement `[À VÉRIFIER]` |

## Pages liées

- [Règlement](/rules/#article-3--le-grief) : les règles sur le grief
- [Boisson et Alcool](/alcool/) : un tonneau non protégé est partagé entre joueurs
- [Master SDC](/mastersdc/) : le tri automatique de tes coffres
