# Système - L'Interface de la Roue des Magies Démoniaques

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🔮 Système - L'Interface de la Roue des Magies Démoniaques

Ce document technique définit l'ergonomie, la disposition à l'écran, les raccourcis de périphériques et les modifications visuelles de l'interface de sélection des 4 éléments du Vide et de la Magie de Sang.

---

## 🎮 1. Ergonomie et Commandes Directes (Zéro Latence)

Pour contrer la vitesse d'apprentissage de l'**IA Prédictive des Monstres Uniques** (Page 34), l'accès aux magies ne doit pas couper le rythme du combat. L'interface s'ouvre sous forme de menu radial transparent au centre de l'écran, ralentissant le temps de 50% uniquement en mode solo (aucun ralentissement en mode Coopération Asynchrone).

### 🕹️ Configuration Manette (Layout PlayStation / Xbox)

- **Ouverture / Maintien :** Maintenir la gâchette basse `L2` (ou `LT`). La caméra s'approche légèrement de l'épaule du héros (focalisation TPS).
- **Sélection :** Incliner le stick analogique droit (`R3`) dans l'une des 4 directions cardinales.
- **Validation Flash (Feinte à la volée, Page 9) :** Presser simultanément `L2` + la touche géométrique dédiée au milieu d'une animation d'attaque physique :
    - `L2 + Triangle` (Haut) ➡️ **🔥 Feu**
    - `L2 + Cercle` (Droite) ➡️ **❄️ Glace**
    - `L2 + Carré` (Gauche) ➡️ **⚡ Foudre**
    - `L2 + Croix` (Bas) ➡️ **🕳️ Vide / Gravité**

### ⌨️ Configuration Clavier / Souris (PC Hardcore)

- **Ouverture / Maintien :** Maintenir la touche `A` (ou bouton latéral `Souris 4`).
- **Sélection :** Glisser la souris de quelques millimètres dans la direction de l'élément, ou utiliser les touches d'accès rapide instantané.
- **Validation Flash :** Presser directement les touches numériques `1`, `2`, `3`, `4` (au-dessus d'AZERTY) pendant une animation de clic gauche pour forcer l'infusion élémentaire sans ouvrir la roue.

---

## 📐 2. L'Écran de la Roue et ses 4 Quadrants Cardinaux

La roue est divisée en 4 sections fixes, chacune liée à une ressource et à des types de fusions secrètes précises (Page 38).

[🔥 FEU] (Haut)│[⚡ FOUDRE] (Gauche) ──┼── [❄️ GLACE] (Droite)│[🕳️ VIDE] (Bas)

1. **🔥 Quadrant Haut : Pyromancie de Destruction**
    - *Ressource :* Consomme du Mana (🔵).
    - *Effet :* Brûlure continue, dégâts de zone. Indispensable pour déclencher le **Choc Thermique**.
2. **❄️ Quadrant Droite : Cryomancie d'Altération**
    - *Ressource :* Consomme du Mana (🔵).
    - *Effet :* Ralentissement de la posture ennemie, gel corporel, augmentation de la durabilité défensive.
3. **⚡ Quadrant Gauche : Électromancie Cinétique**
    - *Ressource :* Consomme du Mana (🔵).
    - *Effet :* Foudre en chaîne, paralysie nerveuse, téléportation de feinte à courte distance.
4. **🕳️ Quadrant Bas : Gravité du Vide**
    - *Ressource :* Consomme du Mana (🔵).
    - *Effet :* Micro-trous noirs, siphonnage de la lumière ambiante pour l'infiltration d'Ombre (Page 29).

### 🩸 L'Extension Centrale : Le Noyau de Sang (Culte du Premier Sang)

Si le joueur a débloqué le Palier Ultime de la `Branche 8 (Magie de Sang)` via la théorie des quêtes secondaires, le centre de la roue s'ouvre, révélant un cinquième élément.

- *Input :* Presser le stick `R3` ou faire un clic molette lorsque la roue est ouverte.
- *Ressource :* **Consomme directement 15% de la jauge de PV maximum** du joueur à la place du Mana. Infuse l'acier de sang hérétique pour propager les courants électriques (Surcharge Cardiaque).

---

## 👁️ 3. L'Instabilité Visuelle de l'UI (L'Impact du Syndrome de Fusion)

Pour respecter la charte de maturité et d'immersion psychologique AAA de votre GDD, l'interface graphique de la Roue des Magies n'est pas un menu figé et propre. Elle subit la corruption de **Malak-Gath** (Page 36).

- **Au Stade 1 des Symptômes :** L'interface est propre, les runes magiques sont bleues et nettes.
- **Au Stade 2 (Visions Intermittentes) :** Lorsque le joueur ouvre la roue avec une jauge de mana vide, les icônes des éléments se mettent à trembler et à grésiller à l'écran. Des artefacts visuels (glitches) apparaissent, et les visages des 3 Monstres Uniques s'affichent de manière subliminale au centre de la roue pendant une frame.
- **Au Stade 3 (L'Illusion Physique) :** Le menu radial est entièrement corrompu. Les lignes géométriques deviennent des veines noires coulantes. La voix en audio 3D de Malak-Gath chuchote le nom de l'élément que vous survolez avec un ton lubrique ou agressif (*"Brûle-les... gèle-les..."*).

---

## 👥 4. Comportement en Mode Coopération Asynchrone

En multijoueur, la Roue des Magies devient un vecteur de communication visuelle diégétique entre les deux joueurs.

- **L'Incantation Visible :** Lorsque le **Joueur 1** maintient sa roue ouverte pour préparer une *Supernova* (Page 38), le temps ne ralentit pas (règle du multijoueur). Cependant, le **Joueur 2** voit une aura magique sphérique se gonfler autour des mains du Joueur 1, indiquant l'élément choisi.
- **Le Sabotage de Roue :** Si les deux joueurs sont en conflit PvP à cause d'un contrat de chasse aux primes (Page 30), le Joueur 2 peut lancer une flèche de vent ou utiliser le combo *Orage Magnétique* pour forcer la fermeture de la Roue des Magies du Joueur 1, le bloquant dans son animation de sélection et annulant sa feinte.