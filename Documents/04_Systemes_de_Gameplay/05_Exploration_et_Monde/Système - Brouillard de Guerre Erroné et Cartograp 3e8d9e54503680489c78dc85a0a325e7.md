# Système - Brouillard de Guerre Erroné et Cartographie

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🗺️ Système - Brouillard de Guerre Erroné & Cartographie

Ce document technique définit le fonctionnement de l'interface de la carte en parchemin (Page 45). Le système rejette le dévoilement automatique passif pour devenir un simulateur de cartographie réaliste, instable et asynchrone.

---

## 🗺️ 1. La Nature Visuelle : La Carte Erronée (Ultra-Réalisme)

Lorsque le joueur ouvre son interface de carte pour la première fois, les zones non explorées ne sont pas masquées par un simple calque noir. Elles affichent une **topographie volontairement fausse ou imprécise**, dessinée à l'encre par d'anciens cartographes du royaume.

- **L'Illusion Visuelle :** La carte non explorée montre de faux tracés de rivières, des montagnes mal positionnées, ou des illustrations de monstres mythologiques fictifs à la place des vrais reliefs.
- **La Rectification Diégétique :** C'est en s'aventurant physiquement dans la zone que le héros "redessine" la carte. L'encre ancienne et erronée s'efface en direct à l'écran, remplacée par le tracé topographique exact et chirurgical du relief réel, révélant les véritables routes et défilés rocheux.

---

## 🔀 2. La Double Mécanique de Dévoilement (Exploration & Commerce)

Pour corriger et mettre à jour la carte en parchemin, le joueur combine l'action physique sur le terrain et l'opportunisme économique.

### A. L'Exploration Pure (Le Trait de Plume)

- **Mécanique :** Le brouillard de la fausse carte se dissipe uniquement autour du héros et de sa **Monture Évolutive** (Page 25) dans un rayon de 100 mètres. Le joueur doit physiquement arpenter les falaises ou les forêts pour valider la topographie.

### B. Le Métier de Cartographie (L'Achat de Fragments)

- **Mécanique :** Le joueur peut court-circuiter l'exploration en achetant des fragments de cartes authentiques auprès de PNJ éclaireurs de la *Coalition des Marches* ou de cartographes corrompus du *Cartel de la Brume*.
- **La Friction Économique (Page 23) :** Ces parchemins authentiques coûtent très cher. De plus, si l'IA collective d'une faction vous est **Hostile**, ses éclaireurs refuseront de vous vendre leurs relevés topographiques, vous forçant à infiltrer leurs camps en vue TPS pour crocheter le coffre aux cartes (`Branche 4`).

---

## 👥 3. L'Impact de la Coopération Asynchrone (Le Partage de Notes)

En mode multijoueur (2 à 4 joueurs), la progression de la carte reste strictement **individuelle et asynchrone** pour renforcer l'indépendance du groupe.

- **Les Cartes Étanches :** Si le **Joueur 1** explore les Canyons à l'Ouest pendant que le **Joueur 2** s'infiltre dans les Académies du Nord, la carte du Joueur 2 reste inchangée et erronée pour la zone de l'Ouest. Ils ne partagent pas leur vision à distance.
- **L'Action "Échanger les Notes" :** Pour synchroniser leurs cartes, les joueurs doivent obligatoirement se retrouver physiquement autour d'un **Feu de Campement (Page 20)** ou dans une auberge. Une option de menu contextuel s'active : `[Échanger les notes de cartographie]`. Une animation montre les deux héros penchés sur le parchemin, et les zones découvertes par l'un s'impriment instantanément sur la carte de l'autre.

---

## ⛈️ 4. L'Interaction avec la Météo Dynamique (La Perte de Repères)

Le climat extrême (Page 26) perturbe la liaison métaphysique entre le héros et son interface de navigation.

- **Le Verrouillage Temporel :** Lorsqu'une **Tempête de Neige** (Pics Célestes) ou une **Tempête de Sable** (Canyons) éclate, le héros perd le nord. Ouvrir l'interface affiche une carte instable : le parchemin subit des distorsions visuelles (glitches liés au Stade 3 des symptômes, Page 42) et la position exacte du joueur (le curseur) disparaît.
- **La Boussole Folle :** Le joueur ne peut plus se fier à son écran. Il est contraint de fermer sa carte, de passer en **Vue FPS** pour chercher des points de repère physiques dans la brume (une torche, une falaise), ou de s'abriter en attendant la fin de la tempête sous peine de marcher à l'aveugle vers le repaire d'un *Monstre Unique à IA prédictive*.