# Système - Criminalité, Chasseurs de Primes et Contrats de Traque

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⚖️ Système - Criminalité, Chasseurs de Primes & Contrats de Traque

Ce document technique définit la gestion des crimes, le calcul de la Prime de Recherche (Bounty), l'apparition des Chasseurs de Primes et le système de quêtes de traque asymétriques via les Postes de Garde.

---

## 🩸 1. Le Système de Criminalité et Génération de la Prime

Chaque action illégale commise et observée par un témoin (civil ou garde) met à jour la mémoire de l'**IA Collective** de la zone et augmente votre **Prime** (en pièces d'or).

- **Paliers de Crime :**
    - *Vol à la tire / Crochetage de serrure raté :* +200 pièces. L'IA collective passe en mode `Méfiance`.
    - *Agression de PNJ civile / Utilisation de la magie noire (Stade 3) :* +1 500 pièces. L'IA collective passe en mode `Terreur`.
    - *Meurtre de garde / Sabotage de faction :* +5 000 pièces. Déclenchement de la chasse à l'homme.
- **Les Chasseurs de Primes à IA Prédictive :** Si votre prime dépasse 5 000 pièces dans une région, le jeu déploie des **Traqueurs d'Élite** qui apparaissent de manière aléatoire dans le monde ouvert. Ils analysent votre style de combat (Page 15) pour contrer vos *Feintes Élémentaires* préférées, vous forçant à vous cacher ou à payer votre prime au marché noir du *Cartel de la Brume*.

---

## 🎯 2. Les Panneaux de Primes des Postes de Garde (Quêtes Annexes Traque)

Chaque grand poste de garde ou relais de chasse possède un Panneau d'affichage. Les quêtes de traque qui y apparaissent dépendent de votre **Voix choisie et de votre Alignement de Faction** (Page 27).

- **Si vous êtes allié à L'Ordre :** Vous traquez des espions du Cartel, des déserteurs ou des hérétiques du Culte.
- **Si vous êtes allié à la Coalition :** Vous traquez des collecteurs de taxes corrompus ou des inquisiteurs.
- **La Règle AAA du Butin (Mort ou Vif) :**
    - **🎯 Option A : Ramener la cible VIVANTE (Gain maximal : 100% de l'or + Bonus d'XP)**
        - *Mécanique :* Le joueur doit vider la jauge d'Endurance (🟢) de la cible en vue TPS, utiliser une feinte de Glace pour l'immobiliser, puis l'assommer. Il faut ensuite charger le corps inerte sur le dos de votre **Monture Évolutive** (Page 25) et chevaucher jusqu'au poste de garde sans que la monture ne meure ou ne stresse sous la tempête (Page 26).
    - **💀 Option B : Ramener la cible MORTE ou une Preuve (Gain réduit : 40% de l'or, zéro bonus)**
        - *Mécanique :* Plus simple. Vous abattez la cible à distance à l'arc en **Vue FPS**. Vous fouillez le cadavre pour récupérer une preuve diégétique (une bague, un insigne militaire d'officier, une oreille) à ramener au commandant.

---

## 👥 3. Le Climax Coopératif Asynchrone : La Traque de votre Ami (PvP Systémique)

En mode Coopération, si les deux joueurs prennent des chemins opposés dans leur progression ou leurs alliances, le système de Panneau de Primes génère le scénario ultime de l'enfer.

### 🎭 Scénario Type : "Le Contrat sur la Marionnette"

1. **Le Crime du Joueur 1 :** Le Joueur 1 a abusé de la Magie de Sang (Stade 3) et a massacré un capitaine du Château lors d'une infiltration ratée (Page 17). Sa prime s'élève à 10 000 pièces d'or. Il est l'ennemi public de l'Ordre.
2. **La Quête du Joueur 2 :** Le Joueur 2, qui est resté loyal à l'Ordre ou qui a maximisé sa `Branche 10 (Diplomatie)`, entre dans un poste de garde de la Capitale. Sur le panneau, **la tête de son propre ami (Joueur 1) s'affiche comme cible prioritaire de la quête**.
3. **Le Choix des Scénarios Possibles :**
    - *Scénario 1 (La Protection) :* Le Joueur 2 accepte le contrat pour empêcher un chasseur de primes IA de prendre la quête. Il utilise les informations de la quête pour guider en secret le Joueur 1 à travers les égouts du Quartier Sud en évitant les patrouilles (Mouchardage inversé).
    - *Scénario 2 (La Trahison Mortelle) :* Le Joueur 2 décide de toucher la prime. Il traque le Joueur 1 dans le monde ouvert. Un combat PvP s'engage au milieu des bois sous une *Tempête de Pluie* (Page 26).
    - *Si le Joueur 2 tue le Joueur 1 :* Il coupe l'insigne du Joueur 1, le ramène au poste de garde pour toucher 40% de la prime. Le Joueur 1 subit le système de mort punitive et ressuscite à l'auberge (Page 20), furieux.
    - *Si le Joueur 2 capture le Joueur 1 VIVANT :* Le Joueur 2 assomme le Joueur 1, le ligote, le pose sur son *Lion des Canyons* (Page 25) et le livre aux geôles de l'Ordre. Le Joueur 2 touche 100% de la récompense et débloque un titre honorifique AAA. Le Joueur 1 se réveille en prison, ouvrant une quête de jailbreak (évasion) obligatoire pour la suite de sa partie.