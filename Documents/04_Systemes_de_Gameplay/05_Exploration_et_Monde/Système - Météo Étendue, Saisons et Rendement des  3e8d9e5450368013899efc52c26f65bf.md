# Système - Météo Étendue, Saisons et Rendement des Métiers

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⛈️ Système - Météo Étendue, Saisons & Rendement des Métiers

Ce document technique définit l'impact du Cycle des Saisons sur la physique du monde ouvert, la migration de la faune, l'accessibilité des filons et les multiplicateurs de taux de drop (butin) des métiers de récolte.

---

## 📅 1. Le Cycle des Saisons (La Mutation Temporelle AAA)

Le monde ouvert alterne de manière diégétique entre deux saisons majeures tous les 30 jours de jeu *In-Game*. Ce cycle modifie la géographie des biomes sans aucun écran de chargement.

- **🍂 La Saison Sèche / La Brûlure (Canyons & Plaines) :**
    - *Géographie :* Les rivières de la Plaine Royale s'assèchent partiellement, révélant des gués secrets. Le biome des Canyons subit des vagues de chaleur extrême.
    - *Impact Joueur & Monture :* La jauge d'Endurance (🟢) des chevaux s'épuise 20% plus vite en plein soleil. Les *Lions des Canyons* gagnent un bonus de sprint de +15%.
- **🌨️ La Saison Flétrie / Le Grand Gel (Pics Célestes & Forêts) :**
    - *Géographie :* La neige descend des Pics Célestes pour recouvrir la Forêt Sauvage. Les fleuves gèlent en surface, permettant aux montures lourdes comme l'*Ours des Montagnes* de traverser sans ponts.
    - *Impact Joueur & Monture :* La visibilité en vue FPS subit un effet de givre sur les bords de l'écran. Le *Sanglier Géant* s'épuise deux fois plus vite dans la poudreuse.

---

## ⛏️ 2. Impact sur le Rendement des Métiers (Taux de Drop)

La nature des ressources et la générosité des gisements dépendent entièrement du climat et de la saison en cours, forçant le joueur à planifier son grind (Page 24).

### ⛏️ A. Le Métier de Minage (L'Effet des Saisons)

- **Pendant le Grand Gel (Hiver) :** La roche est durcie par le gel. Extraire du minerai classique demande 3 coups de pioche supplémentaires. En contrepartie, le taux de drop des **Cristaux du Vide et de l'Obsidienne** (Niveaux 70 à 98) augmente de **+40%** dans les failles souterraines, la stase magique stabilisant les cristaux.
- **Pendant la Brûlure (Été) :** Les gisements de Soufre Volcanique entrent en fusion. Frapper un filon sans gants de forge légendaires inflige des dégâts de feu au joueur, mais le taux de drop des pépites pures est doublé.

### 🏹 B. Le Métier de Chasse & Traque (Les Migrations)

- **Pendant la Tempête de Neige (Page 53) :** Le Petit Gibier (lapins, oiseaux) disparaît totalement des plaines (rendement à 0%). Les Prédateurs Alphas (Loups, Ours) quittent la forêt pour chasser en meute de 6 près des villages, augmentant le taux de drop de **Fourrures Parfaites** de +50% pour les chasseurs équipés d'arcs de précision.
- **Pendant la Tempête de Sable :** Les animaux se terrent. Cependant, le vent déterre des ossements géants de créatures mythiques dans les Canyons, permettant de récolter des composants de craft de niveau 99 introuvables le reste du temps.

---

## 🔄 3. Matrice des Rendements Climatiques et Fusions de Métiers

Le tableau suivant récapitule les coefficients de butin appliqués en temps réel par le moteur de jeu :

| Métier de Récolte | Événement Climatique Actif | Ressource Ciblée | Coefficient de Drop (Butin) | Modification du Comportement de l'IA |
| --- | --- | --- | --- | --- |
| **⛏️ Minage** | ⛈️ Pluie Battante (Forêt) | Minerai de Fer brut | `x1.5` (Sol meuble) | Les monstres de Ruche souterrains migrent à la surface. |
| **⛏️ Minage** | ❄️ Tempête de Neige (Nord) | Cristaux du Vide | `x2.0` (Surtension) | Les Sentinelles du Conclave doublent leurs rondes de stase. |
| **🏹 Chasse** | 🏜️ Tempête de Sable (Ouest) | Cuir de Lion des Canyons | `x0.5` (Bêtes cachées) | Les lions chassent à l'affût dans les brumes d'ocre. |
| **🏹 Chasse** | 🍂 Saison Sèche (Plaines) | Gibier Traditionnel | `x2.0` (Points d'eau) | Le gibier se rassemble exclusivement autour des rivières sèches. |

---

## 👥 4. Coopération Asynchrone : La Guerre des Saisons

En mode multijoueur, le cycle des saisons s'applique de manière uniforme, mais affecte les joueurs différemment selon leurs spécialisations d'arbre de compétences.

- **Le Partage des Ressources Saisonnières :** Si le **Joueur 1** (Maître Mineur) profite du Grand Gel pour extraire des Cristaux du Vide à haut rendement au Nord, il doit affronter l'IA du Conclave renforcée par le blizzard. Il a besoin du **Joueur 2** (Maître Traqueur) pour éliminer les sentinelles magiques en vue FPS à distance, créant un besoin constant de collaboration pour maximiser les profits économiques de la saison.
- **Le Sabotage Climatique :** Un joueur allié au *Conclave du Voile* peut pirater un *Relais de Stase* (Page 45) pour forcer une anomalie climatique locale (déclencher une mini-tempête de neige artificielle). Cela fait fuir le gibier que son ami (Joueur 2) était en train de traquer pour le Cartel, provoquant l'échec de son contrat de subsistance de manière totalement systémique.