# Système - Factions et Jauges de Réputation

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⚖️ Système - Factions & Jauges de Réputation

Ce document technique définit la structure mathématique des jauges de réputation, les 7 paliers d'alignement, et la mécanique des vases communicants géopolitiques régissant les 8 factions du jeu.

---

## 📈 1. Structure Mathématique de la Jauge (La Grille de Points)

Chaque joueur possède une jauge de réputation indépendante pour chacune des 8 factions. La jauge évolue sur une échelle allant de **-10 000 points (Haine Absolue)** à **+10 000 points (Allégeance Totale)**.

[-10k] ─── [-5k] ─── [-2k] ─── [0] ─── [+2k] ─── [+5k] ─── [+10k]Traqué     Hostile   Méfiant   Neutre  Favorable  Allié    Champion

### 📋 Les 7 Paliers d'Alignement AAA

1. **👑 [+5 001 à +10 000] : Champion Légendaire**
    - *Gameplay :* Les gardes de la faction vous saluent militairement. Les marchands vous accordent un **rabais fixe de 40%**. Accès aux armes expérimentales de niveau 99 (Page 24).
2. **🤝 [+2 001 à +5 000] : Allié de Confiance**
    - *Gameplay :* Accès libre aux zones restreintes (Garnisons, Académies). Débloque les **Quêtes ++ régionales**.
3. **🟢 [+1 000 à +2 000] : Favorable**
    - *Gameplay :* Les PNJ de la faction vous partagent des rumeurs exclusives. Petites réductions économiques (-10%).
4. **⚪ [-999 à +999] : Neutre / Inconnu**
    - *Gameplay :* Statut initial du jeu. Comportement standard basé sur la taille de la zone (Page 13).
5. **🟡 [-1 000 à -2 000] : Méfiant**
    - *Gameplay :* Les PNJ ferment leurs dialogues plus vite. Les prix en boutique augmentent de +25%.
6. **🔴 [-2 001 à -5 000] : Hostile**
    - *Gameplay :* Les marchands légaux refusent de commercer (Page 23). Des checkpoints physiques se dressent pour bloquer vos montures aux frontières de leurs biomes.
7. **💀 [-5 001 à -10 000] : Traqué / Ennemi Public**
    - *Gameplay :* L'Inquisition ou les chasseurs de primes déploient des **Traqueurs à IA prédictive** pour vous assassiner de manière aléatoire dans le monde ouvert. Les PNJ civils fuient en hurlant à votre approche (**IA Collective de Terreur**).

---

## 🔄 2. La Matrice des Vases Communicants (Impact Géopolitique)

Dans un monde ouvert systémique, il est impossible de plaire à tout le monde. Valider une quête pour une faction applique automatiquement un bonus sur sa jauge, mais génère des **malus proportionnels** sur les jauges de ses rivaux historiques.

| Action de Quête Validée | Faction Bénéficiaire | Bonus Points | Faction(s) Impactée(s) | Malus Points |
| --- | --- | --- | --- | --- |
| **Sécuriser un Checkpoint** | L’Ordre du Sceptre d’Or | `+500` | Coalition des Marches<br>Cartel de la Brume | `-400`<br>`-200` |
| **Livrer un Artefact Antique** | Le Conclave du Voile | `+600` | Murmures du Passé<br>L’Ordre du Sceptre d’Or | `-500`<br>`-200` |
| **Saboter une Forge Royale** | La Coalition des Marches | `+400` | L’Ordre du Sceptre d’Or | `-500` |
| **Financer un Réseau de Contrebande** | Le Cartel de la Brume | `+300` | L’Ordre du Sceptre d’Or | `-300` |
| **Purifier une Zone de Ruche** | Les Veilleurs de l'Aube | `+400` | Le Culte du Premier Sang | `-500` |
| **Abattre un Boss Régional** | Loge des Chasseurs | `+800` | *(Aucun - Neutre)* | `0` |

---

## 👥 3. Application en Coopération Asynchrone (La Friction des Profils)

La réactivité des PNJ en mode Coop repose entièrement sur le calcul des deltas de réputation entre les deux joueurs présents dans la même pièce.

- **Le Mouchardage de Faction :** Si le **Joueur 1** est aligné comme *Champion* chez les *Éveillés (Culte)* et que le **Joueur 2** est *Allié* de *L'Ordre*, le PNJ de l'Ordre s'adressera uniquement au Joueur 2.
    - *Dialogue de l'IA Collective :* "Capitaine [Joueur 2], vos états de service sont exemplaires. Mais l'homme qui marche dans votre ombre porte les marques noires de l'hérésie. Nos sentinelles s'affolent (Page 17). S'il fait un pas de plus vers la cour du Château, mes chevaliers vous abattront tous les deux."
- **La Scission de Fin de Quête (La Trahison en Direct) :** Si une quête de faction demande de détruire un laboratoire du Conclave, le Joueur 1 (allié au Conclave) peut décider de se retourner contre le Joueur 2 au milieu du combat pour protéger l'académie, faisant basculer la partie de la coopération vers un affrontement PvP immédiat et systémique.

---

## 🩸 4. Le Syndrome de Fusion et la Réputation Fantôme

L'Ange Déchu qui habite l'esprit du joueur possède sa propre "Réputation Interne", appelée la **Jauge de Synchronicité**.

- **La Corruption de l'Image :** Plus le joueur débloque de compétences Ultimes magiques (Page 15) ou plus il **meurt en boucle** (Page 20), plus la jauge de l'Ange Déchu augmente.
- **Le Malus Passif Universel :** Une fois le Stade 3 des symptômes atteint, la jauge démoniaque applique un **malus passif de -2 000 points automatique** sur les factions de *L'Ordre*, des *Veilleurs de l'Aube* et des *Murmures du Passé*. Votre simple présence physique (aura noire, veines sombres) court-circuite vos efforts diplomatiques, vous forçant à sombrer définitivement dans la criminalité ou à chercher des alliances secrètes chez les hérétiques du Culte.