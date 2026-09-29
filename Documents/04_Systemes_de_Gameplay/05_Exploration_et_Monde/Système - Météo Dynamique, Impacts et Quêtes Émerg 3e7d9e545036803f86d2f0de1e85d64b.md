# Système - Météo Dynamique, Impacts et Quêtes Émergentes

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⛈️ Système - Météo Dynamique, Impacts & Quêtes Émergentes

Ce document technique définit le fonctionnement de la météo dynamique et ses répercussions physiques, visuelles et narratives sur le joueur, la faune, les monstres et l'apparition de quêtes contextuelles en monde ouvert.

---

## 🌪️ 1. Matrice des Biomes et Effets Climatiques

Le système météo génère des événements climatiques aléatoires ou scriptés selon le biome où se trouve le joueur. Chaque météo modifie les statistiques de tout le monde (Joueurs + IA).

### ❄️ A. La Tempête de Neige (Biome de Montagne)

- **Impact Visuel :** Réduction de la visibilité de **85%** (effet de "Whiteout" total). L'affichage de la mini-carte et des repères visuels est désactivé.
- **Impact Physique :** L'endurance (🟢) du joueur se régénère 30% moins vite à cause du froid extrême. Les mouvements en vue TPS sont ralentis de 20%.
- **Impact IA & Combat :** La faune passive se cache (Chasse impossible). Les Monstres de Ruche de glace gagnent un bonus de +30% de dégâts. Vos **Feintes Élémentaires de Feu** fondent instantanément et perdent 50% d'efficacité, tandis que les feintes de Glace congèlent les ennemis deux fois plus vite.

### 🏜️ B. La Tempête de Sable (Biome des Canyons)

- **Impact Visuel :** Réduction de la visibilité de **50%** (brume orange/rouge constante).
- **Impact Physique :** Impossible de courir ou de sprinter à dos de monture en ligne droite face au vent sous peine de vider instantanément la jauge d'Endurance de l'animal.
- **Impact IA & Combat :** La visée de précision à l'arc en **Vue FPS** subit une forte friction (le vent fait dévier les flèches). L'IA collective des gardes de l'Ordre voit sa portée de détection réduite de moitié, ouvrant une fenêtre parfaite pour l'infiltration furtive (`Branche 2`).

### 🌧️ C. La Pluie Battante & Orage (Biome de la Forêt / Plaines)

- **Impact Visuel :** Visibilité légèrement réduite (20%). Reflets dynamiques sur les armures lourdes.
- **Impact Physique (Le Ralentissement Général) :** Le sol devient boueux. La vitesse de déplacement de tous les personnages (Joueurs, Gardes, Prédateurs, Montures) est **réduite de 15%**.
- **Impact Électrique (Pratique +++) :** Tous les êtres vivants sous la pluie reçoivent l'état "Trempé". Si le joueur déclenche le combo secret **Surcharge Cardiaque** ou un sort de Foudre (`Branche 7`), l'électricité se propage sur un rayon trois fois plus grand, électrocutant des meutes entières de loups ou de soldats d'un seul coup.

---

## 🛒 2. L'Émergence Narrative : Les Quêtes Émergentes de Météo

La météo modifie les flux économiques (Page 23) et fait apparaître des PNJ exclusifs dans le monde ouvert qui n'existent nulle part ailleurs.

### 🎭 Scénario : Le Marchand Naufragé de la Brume

- **Le Déclencheur :** Une violente **Pluie Battante** ou une **Tempête de Neige** éclate alors que le joueur explore une route isolée des Marches Sauvages.
- **L'Émergence :** L'IA collective de la zone génère un événement aléatoire. Un **Marchand Ambulant du Cartel de la Brume** s'est embourbé avec son chariot. Sa monture (un Sanglier géant) est blessée, et des brigands ou des prédateurs locaux encerclent le convoi, profitant du ralentissement général.
- **La Quête Émergente ++ :** Le joueur intervient pour sauver le marchand.
    - *Si vous l'aidez avec l'Adoption (`Branche 9`) :* Vous pouvez utiliser les compétences de votre propre **Loup Nommé** pour pister la cargaison tombée dans le ravin à cause de la visibilité réduite.
    - *La Récompense Économique :* Reconnaissant, le marchand ouvre sa boutique spéciale sous sa tente de fortune. Il vous vend des plans de forge théoriques uniques de niveau 50 (Page 24) ou des composants alchimiques interdits à moitié prix, disponibles **uniquement pendant la durée de la tempête**. Une fois le soleil revenu, le marchand reprend sa route et disparaît de la zone.

---

## 💀 3. Coopération Asynchrone et Mort sous la Tempête

- **Le Piège Climatique en Coop :** Si le **Joueur 1** (Stade 3 des symptômes) déclenche une tempête de magie noire via l'Ange Déchu au même moment où une tempête de neige naturelle éclate, le jeu cumule les distorsions visuelles. Le **Joueur 2** se retrouve dans un blizzard classique, tandis que le Joueur 1 subit des hallucinations cauchemardesques au milieu de la tempête, augmentant la désorientation du groupe.
- **La Mort Punitive (Page 20) :** Si le joueur meurt gelé ou déchiqueté par un boss de zone pendant une tempête, son cadavre reste sur place avec ses minerais précieux. S'il attend trop longtemps à l'auberge que la tempête se calme avant de retourner chercher son butin, l'**IA Évolutive de Zone** peut faire migrer une meute de prédateurs opportunistes directement sur le lieu du crash pour dévorer les restes, vous obligeant à combattre dans la boue ou le givre pour récupérer votre sac de craft.