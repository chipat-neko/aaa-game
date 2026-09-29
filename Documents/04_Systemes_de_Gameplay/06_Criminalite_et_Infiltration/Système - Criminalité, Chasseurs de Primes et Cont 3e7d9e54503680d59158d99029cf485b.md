# Système - Criminalité, Chasseurs de Primes et Contrats de Traque (bis)

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⚖️ Système - Criminalité, Chasseurs de Primes & Contrats de Traque

Ce document technique définit la gestion des crimes, le calcul de la Prime de Recherche (Bounty), l'apparition des Chasseurs de Primes et le système de quêtes de traque asymétriques via les Postes de Garde corrompus.

---

## 🩸 1. Le Système de Criminalité et Génération de la Prime

Chaque action illégale commise et observée par un témoin (civil ou garde) met à jour la mémoire de l'**IA Collective** de la zone et augmente votre **Prime** (en pièces d'or).

- **Paliers de Crime :**
    - *Vol à la tire / Crochetage de serrure raté :* +200 pièces. L'IA collective passe en mode `Méfiance`.
    - *Agression de PNJ civile / Utilisation de la magie noire (Stade 3) :* +1 500 pièces. L'IA collective passe en mode `Terreur`.
    - *Meurtre de garde / Sabotage de faction :* +5 000 pièces. Déclenchement de la chasse à l'homme.
- **Les Chasseurs de Primes à IA Prédictive :** Si votre prime dépasse 5 000 pièces dans une région, le jeu déploie des **Traqueurs d'Élite** qui apparaissent de manière aléatoire dans le monde ouvert. Ils analysent votre style de combat (Page 15) pour contrer vos *Feintes Élémentaires* préférées.

---

## 🎯 2. Les Panneaux de Primes et le Clivage des Postes de Garde

Chaque grand poste de garde ou relais de chasse possède un Panneau d'affichage. Cependant, les forces de l'Ordre ne sont pas unies : les officiers d'un même poste de garde peuvent appartenir à des courants idéologiques ou des factions différentes en secret (certains sont payés par le *Cartel*, d'autres par le *Culte*).

### 📋 La Règle AAA du Butin Officiel (Mort ou Vif)

Le contrat standard affiché sur le panneau est posé par la faction dirigeante locale :

- **🎯 Option Officielle Vivante (Gain de base : 5 000 pièces + Bonus d'XP) :**
    - *Mécanique :* Vider l'Endurance (🟢) de la cible en vue TPS, l'assommer, la ligoter, la charger sur sa **Monture Évolutive** (Page 25) et la ramener vivante devant les cellules.
- **💀 Option Officielle Morte (Gain réduit : 40% de la prime, soit 2 000 pièces) :**
    - *Mécanique :* Abattre la cible à distance (Vue FPS) et ramener une preuve physique diégétique (bague, insigne, oreille) au guichet.

---

## 🤫 3. La Sur-Quête de Corruption (Le Marché Noir du Garde)

Au moment où le joueur accepte un contrat officiel sur le Panneau pour traquer un individu (ou le **Joueur 2**), un PNJ officier du poste de garde peut s'approcher discrètement et vous glisser une **Sur-Quête clandestine**. Ce PNJ a un intérêt personnel (vengeance, corruption, protection de faction) à ce que les ordres de ses collègues échouent.

Trois scénarios de trahison majeurs s'ouvrent alors à vous :

### A. La Contre-Prime d'Exécution (Le Double de l'Or)

- **Le Marché :** L'officier corrompu murmure : *"Mes collègues veulent le voir vivant pour le faire chanter au Château... Mais s'il parle, je suis un homme mort. Ne le ramène pas vivant. Tue-le au fond du canyon. Je te donnerai 10 000 pièces d'or sous le manteau au lieu des 5 000 officielles."*
- **Le Choix :** Le joueur doit choisir entre la justice de sa faction (5 000 pièces + réputation de faction) ou la corruption pure (10 000 pièces mais gain de suspicion de l'IA collective si le meurtre est découvert).

### B. La Fausse Mort (La Complicité Rémunérée)

- **Le Marché :** L'officier appartient secrètement à la même faction que la cible (ex: *La Coalition des Marches*). Il vous demande de feinter sa mort pour la sauver.
- **Le Choix :** Le joueur localise la cible, refuse de l'attaquer, et utilise le métier d'**Alchimie (Page 24)** pour fabriquer un élixir de "Mort Apparente" (poison qui simule l'arrêt cardiaque). Le joueur ramène la cible "morte" au poste de garde, touche la prime officielle, et l'officier complice réveille la cible en secret dans les geôles pour la faire évader dans la nuit.

---

## 👥 4. Le Climax Coopératif Asynchrone : La Traque de votre Ami (PvP)

Si le **Joueur 1** est la cible et le **Joueur 2** est le Chasseur, cette mécanique de sur-quête de corruption brise définitivement l'alliance :

- L'officier corrompu propose au Joueur 2 de **tuer le Joueur 1 pour 10 000 pièces** au lieu de le ramener vivant aux geôles.
- Si le Joueur 2 cède à l'appât du gain et assassine le Joueur 1 sous la tempête (Page 26), le Joueur 1 subit le système de mort punitive et ressuscite à l'auberge (Page 20), tandis que le Joueur 2 devient riche mais se fige définitivement comme l'ennemi juré du Joueur 1.
- Si le Joueur 2 choisit la fausse mort, les deux amis collaborent pour duper l'IA Isolée du Château, touchant l'or de la garde tout en conservant leur liberté.