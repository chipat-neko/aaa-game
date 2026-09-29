# Système - IA Collective et Réactivité des PNJ

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🤖 Système - IA Collective et Réactivité des PNJ

Ce document technique définit la structure de l'Intelligence Artificielle Collective du jeu. Le comportement, la mémoire et l'hostilité des PNJ ne sont pas gérés individuellement, mais par des "Noeuds de Conscience Commune" interconnectés, dont la complexité augmente selon la taille de la zone habitée.

---

## 🏡 1. Le Hameau / Petit Village (50 à 150 habitants)

- **Structure de l'IA :** Une seule "Conscience Collective" unique pour tout le hameau.
- **Mécanique :** Les habitants partagent à 100% la même opinion et les mêmes informations. Le village est un vase clos, ignorant de la géopolitique extérieure.
- **Impact du Joueur :** Si le joueur aide un seul villageois ou accomplit une quête locale, la réputation maximale est instantanément appliquée à tout le village (les prix baissent partout, les PNJ sourient). À l'inverse, si le joueur commet un crime ou est vu en train d'utiliser la magie démoniaque par un seul habitant, tout le village devient hostile ou terrifié en quelques secondes.
- **Événement Externe :** La conscience collective ne se met à jour sur le reste du monde que lorsqu'un marchand du *Cartel de la Brume* vient leur rendre visite.

## 🏘️ 2. Le Village Moyen (150 à 300 habitants)

- **Structure de l'IA :** 2 à 3 "Consciences Collectives" distinctes (Divergence locale).
- **Mécanique :** Les habitants commencent à se diviser selon des intérêts locaux (ex: les fermiers vs les mineurs vs les gardes). Principalement neutres face aux factions mondiales.
- **Impact du Joueur :** Aider les mineurs améliorera votre réputation auprès d'eux, mais pourra rendre les fermiers méfiants s'ils s'opposaient pour l'utilisation de l'eau. Le joueur doit naviguer entre maximum 3 micro-opinions.

## 🏰 3. La Ville Régionale (300 à 1 000 habitants)

- **Structure de l'IA :** 5 "Consciences Collectives" (Une IA par Faction Majeure présente).
- **Mécanique :** La population est polarisée par la grande guerre politique. Chaque habitant appartient à un bloc idéologique lié aux Factions Majeures.
- **Impact du Joueur :** Le monde réagit en temps réel à vos accomplissements extérieurs. Si le joueur a détruit un avant-poste de *L'Ordre du Sceptre d'Or* dans une autre région, les PNJ affiliés à l'Ordre dans cette ville refuseront de lui parler ou appelleront la garde, tandis que les PNJ affiliés à la *Coalition des Marches* lui offriront des réductions secrètes.

## 🏙️ 4. La Grande Ville (5 villes max dans le monde — 1 000 à 5 000 habitants)

- **Structure de l'IA :** 8 "Consciences Collectives" (Factions Majeures + Mineures) + **Système de Priorisation Temporelle (Ordre des Actions)**.
- **Mécanique Avancée (AAA) :** Ajout d'une mémoire chronologique des dialogues. Le jeu traque l'ordre dans lequel vous résolvez les problèmes de la ville.
- **Matrice d'Impact :**
    - *Scénario :* Le PNJ "X" (Chasseur de monstres) et le PNJ "Y" (Mage du Conclave) demandent votre aide en même temps.
    - *Si vous parlez à X puis à Y, mais résolvez le problème de Y en premier :* Le PNJ X se sentira trahi ou estimera que vous avez priorisé la magie au détriment de la sécurité physique de la ville. L'IA collective de la *Loge des Chasseurs de Monstres* se fermera partiellement à vous dans cette ville, modifiant les quêtes disponibles.

## 👑 5. La Capitale Unique (+ 10 000 habitants)

- **Structure de l'IA :** Système Matriciel Hyper-Complexe (8 Factions x 6 Zones géographiques) + 1 IA Spécifique pour le Château.
- **Mécanique :** La ville est un melting-pot géant, mais elle est découpée en 6 quartiers étanches : **Nord, Sud, Ouest, Est, Centre, et le Château**. Chaque quartier possède sa propre grille d'IA par faction.
- **Fonctionnement Systémique :** Un membre du *Culte du Premier Sang* habitant dans les bas-fonds (Quartier Sud) n'aura pas les mêmes informations ni la même agressivité qu'un membre du Culte infiltré parmi les érudits du Quartier Centre.
- **L'IA du Château :** Totalement isolée. Elle représente le cerveau de la faction dirigeante actuelle. Elle ne réagit pas aux rumeurs de la rue, mais uniquement aux preuves physiques apportées par le joueur ou aux changements d'États du Monde majeurs (perte d'une forteresse, mort d'un général).