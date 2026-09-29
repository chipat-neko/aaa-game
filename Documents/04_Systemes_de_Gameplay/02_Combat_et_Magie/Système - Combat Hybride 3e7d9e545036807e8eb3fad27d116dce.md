# Système - Combat Hybride

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⚔️ Système - Combat Hybride (Magie + Armes)

Ce document technique détaille les mécaniques de combat en temps réel, la gestion des deux perspectives (TPS/FPS) et la synergie "Sans Classe" permettant de contrer l'apprentissage des IA ennemies.

---

## 🎮 1. La Flexibilité des Perspectives (TPS vs FPS)

Le joueur peut basculer instantanément de vue à tout moment d'une simple pression sur le stick analogique (R3). Le jeu adapte sa visée de manière invisible pour garantir l'équilibre.

- **Vue TPS (Troisième Personne) — Spécialité : Gestion de l'Espace**
    - *Avantage :* Idéale pour le combat de mêlée (Épée, Bouclier) et l'esquive. Elle offre une vision à 360° essentielle pour repérer les prédateurs qui tentent de vous contourner ou les monstres à IA de harcèlement.
    - *Verrouillage (Lock-on) :* Système de ciblage classique qui maintient la caméra centrée sur un ennemi précis.
- **Vue FPS (Première Personne) — Spécialité : Précision Chirurgicale**
    - *Avantage :* Idéale pour le tir à l'arc et les sorts de précision à longue distance.
    - *Visée des Points Faibles :* Obligatoire pour détruire les plaques de protection des IA de Ruche ou toucher les cristaux lumineux des Boss Régionaux. Le ciblage automatique est désactivé en FPS pour laisser place au "Skill" pur du joueur.

---

## ⚡ 2. Les Piliers du Combat & Gestion des Ressources

Pour éviter que le joueur n'abuse d'une seule mécanique, le gameplay est régi par deux jauges interdépendantes qui forcent l'alternance.

- **🟢 Jauge d'Endurance (Physique) :** Consommée par les attaques à l'épée, les tirs à l'arc tendus, les esquives et les parades. Si elle tombe à zéro, le joueur est étourdi (Staggered).
- **🔵 Jauge de Mana (Magique) :** Consommée par les sorts de l'Ange Déchu.
- **🔄 La Mécanique de Vase Communicant (Le Core Loop AAA) :**
    - Frapper un ennemi avec des attaques physiques à l'épée régénère rapidement votre Mana.
    - Toucher un ennemi avec de la magie affaiblit sa posture physique, rendant vos prochains coups d'épée dévastateurs.
    - *Conséquence :* Ce système force le joueur à utiliser l'hybridation, ce qui perturbe l'apprentissage de l'IA.

---

## 🔮 3. Le Système d'Infusion Dynamique (Les Combos)

Il n'y a pas de boutons de sorts séparés qui coupent le rythme. La magie de l'Ange Déchu vient s'injecter directement *dans* vos armes de manière fluide.

### A. L'Infusion de Lame (Mêlée)

Le joueur maintient une gâchette magique tout en effectuant ses attaques physiques :

- *Épée + Feu :* Chaque coup de lame applique une brûlure continue. Le coup lourd final déclenche une explosion de zone renversant les petits gibiers/monstres agressifs.
- *Bouclier + Glace :* Une parade parfaite congèle instantanément l'assaillant, brisant le pattern d'attaque synchrone des meutes de prédateurs (ex: loups).

### B. L'Infusion de Projectile (Distance)

Le joueur bascule en vue FPS et charge son arc :

- *Flèche + Magie de Sang (Culte) :* La flèche sacrifie une portion de vos points de vie pour se transformer en projectile téléguidé qui cherche le point faible du monstre unique ou du boss.
- *Flèche + Énergie du Vide :* Crée un micro-trou noir à l'impact qui attire tous les monstres d'une meute au même endroit, ouvrant une fenêtre parfaite pour un combo d'épée en zone.

---

## 🧠 4. Contrer l'IA Prédictive : La Feinte Magique

Puisque les Monstres Uniques analysent vos habitudes en temps réel (ex: ils prédisent votre timing de parade ou esquivent votre sort favori), le jeu intègre une commande de **Feinte**.

- **Mécanique :** Le joueur commence l'animation d'un sort puissant (le monstre unique se prépare alors à le contrer). À la moitié de l'incantation, le joueur appuie sur la touche d'esquive pour annuler le sort et enchaîne instantanément avec un coup d'épée lourd dans le dos du monstre.
- **Résultat :** L'IA est induite en erreur, son algorithme de prédiction est court-circuité pendant 3 secondes, infligeant des dégâts critiques.

## 🔄 5. Le Système de Feinte Élémentaire et d'Infusion à la Volée

Pour briser la prédiction des IA de Ruche et des Monstres Uniques, le joueur ne se contente pas de feinter un mouvement : il peut modifier la nature moléculaire de son arme au millième de seconde près en plein combo.

### A. La Mécanique de Transition Fluide (À la Volée)

- **Fonctionnement :** Le joueur commence un enchaînement d'attaques physiques à l'épée. L'IA ennemie commence à calculer son algorithme de parade pour une lame physique.
- **La Feinte Élémentaire :** Juste avant que le coup ne touche l'ennemi, le joueur presse une touche élémentaire (ex: Feu, Glace, Foudre). L'arme s'enflamme ou se glace instantanément *pendant* l'animation du coup.
- **Impact IA :** L'algorithme de parade de l'IA échoue car le type de dégâts et le timing d'impact ont changé. Le monstre subit le coup de plein fouet avec un bonus de dégâts de surprise.

### B. Le Système d'Apprentissage : Théorie vs Pratique

Le joueur n'achète pas ses compétences dans un simple menu. Il doit vivre l'évolution de son personnage.

1. **L'Apprentissage Théorique (Quêtes Secondaires) :**
    - En aidant un érudit banni du *Conclave du Voile* ou un vieux forgeron de la *Coalition*, le joueur débloque des parchemins ou des enseignements.
    - *Exemple :* Une quête secondaire vous apprend la théorie de la "Magie de Givre appliquée aux métaux". Cela débloque la possibilité d'utiliser l'élément Glace dans votre arbre de compétences.
2. **L'Apprentissage Pratique (Découverte et Expérimentation) :**
    - Le jeu pousse à l'expérimentation ("Pratique +++"). Si le joueur tente de combiner deux éléments appris théoriquement (ex: attaquer une cible gelée avec une feinte de feu), il découvre par lui-même un combo secret non documenté : le **Choc Thermique**, qui fait exploser la posture du monstre. Le jeu valide alors cette action et l'ajoute définitivement au grimoire du joueur.

---

## 🎮 6. Ergonomie AAA : Parité Manette et Clavier/Souris

Le jeu est conçu pour offrir exactement le même niveau de performance, de rapidité et d'accès aux touches "quasi-simultanées", peu importe le périphérique choisi par le joueur.

- **Gestion des Touches en Simultané :** Le système d'infusion élémentaire utilise des raccourcis ultra-sensibles.
    - *Sur Clavier/Souris :* Les touches `1`, `2`, `3`, `4` (ou les boutons latéraux de la souris) injectent instantanément le feu, la glace ou le vide dans la lame.
    - *Sur Manette :* Utilisation des gâchettes combinées aux boutons d'action (ex: Maintenir `L2` + presser `Triangle` enflamme la lame au milieu d'une attaque initiée avec `R1`).
- **Aucun désavantage mécanique :** La réactivité des sticks pour la vue TPS et de la souris pour la précision FPS est équilibrée par une friction de visée (Aim Assist légère et invisible) à la manette pour garantir que les deux communautés de joueurs profitent de la même fluidité face aux monstres ultra-rapides.