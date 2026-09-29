# World Design - Le Biome de l'Est : La Forêt Sauvage

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🗺️ World Design - Le Biome de l'Est : La Forêt Sauvage

Ce document technique et narratif cartographie la région sylvestre de Sylvanis. C'est un biome vertical, brumeux et hautement réactif, conçu pour exploiter le Système d'Adoption, le combat contre l'IA de Nuée et le premier grand Schisme de faction.

---

## ⛰️ 1. Structure Géologique & Verticalité (Level Design AAA)

La Forêt Sauvage rejette la planéité. Elle est construite sur un système de "Triple Canopée" sans temps de chargement pour forcer l'utilisation de l'Endurance (🟢) et l'infiltration.

- **Le Sous-sol (Les Cryptes de Sang) :** Un réseau de tunnels étroits, de cavernes humides et de catacombes antiques. C'est ici que l'obscurité est totale (Page 29), obligeant le joueur à utiliser la vue FPS pour progresser à la lueur des champignons luminescents.
- **Le Plancher (La Route des Ombres) :** Couvert de ronces magiques, de boue (Météo Pluie, Page 26) et de racines géantes. La visibilité y est réduite à 30 mètres à cause d'une brume violette stagnante qui perturbe les tirs à l'arc.
- **La Canopée (Les Passerelles Suspendues) :** Les cimes des arbres géants sont reliées par des structures en bois rigide et des cordes. Cette zone offre une visibilité parfaite à 360° pour les attaques chirurgicales en **Vue FPS** et permet d'éviter l'IA de Ruche des monstres restés au sol.

---

## 📍 2. Les Points d'Intérêt Majeurs (POI de l'Est)

La région de Sylvanis est divisée en 4 sanctuaires interconnectés gérés par des IA collectives distinctes :

### 🏹 POI A : Le Repaire de la canopée (Hub de la Coalition)

- **Démographie :** 400 habitants (IA Collective de Ville Régionale, Page 13).
- **Lore :** Le quartier général caché de **La Coalition des Marches** (Rebelles). Construit entièrement dans la Canopée pour être immunisé aux charges lourdes de l'armée impériale.
- **Utilité :** C'est ici que le joueur trouve la Rôdeuse Elfe, **Maître Enseignant du métier de Chasse & Traque (Niveaux 1 à 99, Page 39)**.

### 🩸 POI B : L'Abbaye Flétrie (Le Nid des Purificateurs)

- **Lore :** Une ancienne abbaye de l'Ordre, profanée et occupée par le **Camp A du Culte (Les Purificateurs Orthodoxes)**.
- **Mécanique :** Zone de haute hostilité. C'est le point de départ des assassins à l'IA collective de Ruche qui vous traquent dans le monde ouvert. Si vous vous faites capturer vivant ici, vous basculez dans le **Système d'Arrestation du Culte (L'Autel du Sacrifice, Page 37)**.

### 👁️ POI C : Les Bosquets Susurrants (Le Refuge des Éveillés)

- **Lore :** Un campement clandestin dissimulé derrière des cascades de lierre, abritant le **Camp B du Culte (Les Éveillés Hérétiques)** menés par la Visionnaire (Page 10).
- **Utilité :** Si vous validez leur alliance lors de la Quête Principale 2, ils ouvrent une boutique secrète pour vous enseigner la théorie de la *Magie de Sang*.

### 🕳️ POI D : Les Ruines de Gath (La Fissure Originelle)

- **Lore :** Le lieu exact où **Malak-Gath** a été précipité et enchaîné par les premiers mages (Page 36). La zone subit des fluctuations de gravité permanentes.
- **Utilité :** Hub pour la faction mineure des **Murmures du Passé**. Ils vous offrent des quêtes de sabotage pour sceller les brèches du Conclave.

---

## 👑 3. Algorithme des 3 Boss Flottants de Sylvanis

Conformément à la grille de non-chevauchement (Page 48), la forêt possède 15 nœuds de spawn forestiers et souterrains. Au chargement du biome, le code y injecte aléatoirement 3 Boss Alphas à l'IA Absorbante :

1. **L'Abomination des Racines (Chimère Végétale) :** Un monstre massif fusionné avec le décor. Il arrache les arbres pour les jeter sur le joueur, forçant la bascule en vue FPS pour viser ses cristaux de sève luisants.
2. **La Nuée Blême (Esprit de Famine) :** Un monstre utilisant l'**IA de harcèlement rapide**. Il se téléporte dans l'ombre des arbres. Pour le vaincre, le joueur doit exécuter la fusion secrète **Surcharge Cardiaque** (`Foudre` + `Sang`, Page 38).
3. **L'Ours Balafré (Le Maître de Meute Alpha) :** Un ours des montagnes niveau 75 qui mène une meute de 5 loups sylvains synchronisés (Page 25). Si le joueur possède l'Ultime d'Adoption (`Branche 9`), il a 0,01% de chances de l'apprivoiser, au prix du sacrifice sanglant de son premier loup.

---

## ⛈️ 4. Réaction Climatique Spécifique (L'Orage Sylvanien)

Lorsque la météo de la **Pluie Battante** s'active sur la Forêt de l'Est :

- Le sol boueux réduit la vitesse de sprint des montures de 15%.
- Les esprits et monstres de Ruche gagnent un bonus de camouflage de +30% dans les feuillages sombres.
- **Le Multiplicateur Tactique :** Les feuilles et les PNJ étant "Trempés", déclencher le combo secret **Arc de Surcharge** (Page 38) ou un sort de foudre électrocute instantanément toute la nuée de fanatiques du Culte connectés à la même ligne de vie, simplifiant les embuscades de groupe.