---
icon: paintbrush
title: Monde Créatif
description: "Le monde créatif de DecaCraft : obtiens ta parcelle de 100x100 et construis en mode créatif. Commandes /plot, partage avec des amis et avantages VIP et Master."
order: 3
---

# Le Monde Créatif

Le plugin du monde créatif te donne une **parcelle personnelle** pour construire en **mode créatif**. Chaque parcelle fait **100x100 blocs**, et tu peux y faire ce que tu veux, en respectant le [règlement](/rules/) bien entendu !

## Pour bien débuter

1. Rends-toi dans le monde créatif : par le portail directement sur la gauche au `/spawn`.
2. Tape `/plot auto` pour **revendiquer** la première parcelle disponible.
3. Tape `/plot home` pour t'y **téléporter** quand tu veux.
4. Construis, puis invite tes amis avec `/plot add` ou `/plot trust`.

## Les commandes de base

| Commande | Effet |
|---|---|
| `/plot auto` | Revendique la première parcelle disponible |
| `/plot home` | Te téléporte à ta parcelle |
| `/plot visit [joueur]` | Te téléporte sur le plot d'un autre joueur |
| `/plot add [joueur]` | Autorise un joueur à construire **si le propriétaire est en ligne** |
| `/plot trust [joueur]` | Autorise un joueur à construire **même si le propriétaire est hors ligne** |
| `/plot remove [joueur]` | Retire un joueur de ta parcelle |
| `/plot clear` | Efface la parcelle sur laquelle tu te trouves |

> **⚠️ Attention :** `/plot clear` efface la parcelle où tu te trouves. Vérifie bien que tu es sur la bonne avant de l'utiliser.

## Les avantages des grades

Les grades apportent plus de confort dans le monde créatif.

| Avantage | Joueur | VIP | Master |
|---|:---:|:---:|:---:|
| Nombre de parcelles | 1 | 2 | 3 |
| Météo de la parcelle | ❌ | ✅ | ✅ |
| Heure de la parcelle | ❌ | ✅ | ✅ |
| Biome de la parcelle | ❌ | ❌ | ✅ |

### Avec le grade VIP

Tu peux avoir une **deuxième parcelle** : refais la commande `/plot auto` pour en revendiquer une nouvelle.

| Commande | Effet |
|---|---|
| `/plot home 2` | Te téléporte à ta deuxième parcelle |
| `/plot flag set weather [clear/rain]` | Retire (`clear`) ou met (`rain`) la pluie sur ta parcelle |
| `/plot flag set time [0-24000]` | Choisit le jour ou la nuit sur ta parcelle (voir le tableau ci-dessous) |

Valeurs courantes pour `/plot flag set time` (cycle jour/nuit de Minecraft, en ticks) :

| Valeur | Moment de la journée |
|---:|---|
| 0 | Lever du soleil |
| 6000 | Midi |
| 12000 | Coucher du soleil |
| 18000 | Minuit |

Pour aller plus loin, consulte la [correspondance des ticks sur le wiki Minecraft](https://minecraft.fandom.com/fr/wiki/Tick).

### Avec le grade Master

En plus des avantages du grade VIP, tu peux avoir une **troisième parcelle**, et choisir le biome de ta parcelle.

| Commande | Effet |
|---|---|
| `/plot setbiome` | Choisit le biome de ta parcelle |

## Pages liées

- [Règlement](/rules/) : ce qui est permis dans les constructions
- [Les Mondes](/world/) : les autres mondes du serveur
- [Les Grades](/grades/) : tous les avantages VIP et Master
