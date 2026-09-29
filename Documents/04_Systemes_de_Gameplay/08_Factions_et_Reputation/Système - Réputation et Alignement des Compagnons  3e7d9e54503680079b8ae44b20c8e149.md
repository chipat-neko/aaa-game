# Système - Réputation et Alignement des Compagnons Animaux

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🐺 Système - Réputation & Alignement des Compagnons Animaux

Ce document technique définit la jauge d'alignement et de fidélité de votre animal adopté (ex: Loup Nommé). L'animal n'obéit pas aveuglément : sa loyauté, son comportement au combat et sa santé mentale fluctuent selon vos choix moraux, votre alignement de faction et votre Stade de Symptômes démoniaques.

---

## 📈 1. La Jauge de Loyauté Animale (L'Échelle d'Affection)

La relation avec votre compagnon nommé (Page 7) est régie par une jauge cachée allant de **0 (Rupture/Terreur) à 1 000 points (Dévouement Absolu)**.

[0] ────────── [250] ────────── [500] ────────── [750] ────────── [1000]Sauvage/Sauvage  Méfiance/Instable   Neutre/Docile    Fidèle/Protecteur  Âme Sœur

### 🍖 Comment faire monter la Loyauté ?

- **La Subsistance (Cuisine/Chasse) :** Nourrir régulièrement l'animal avec de la viande fraîche de qualité issue du métier de Chasse (Page 24).
- **La Protection Mutuelle :** Intervenir pour soigner l'animal avec des remèdes d'Alchimie s'il est blessé au combat, ou tuer l'ennemi qui l'attaquait.
- **Le Repos au coin du feu (Page 20) :** Prendre le temps de caresser l'animal et de se reposer avec lui près du feu de camp.

---

## 🩸 2. L'Aura de Noirceur et la Fissure du Lien (L'Impact du Démon)

Les prédateurs (loups, lions) possèdent une intuition sauvage. Ils ressentent instantanément l'énergie du Vide et de la Magie de Sang issue de l'Ange Déchu qui habite le héros.

### 🔴 L'Effet du Stade 3 des Symptômes (La Terreur Animale)

Lorsque le joueur abuse de la magie démoniaque et atteint le **Stade 3 des Symptômes (L'Illusion Physique)**, son corps dégage des veines noires permanentes et une odeur de soufre/sang.

- **Le Stress de l'Animal :** La jauge de loyauté de l'animal subit un **malus passif de -5 points par minute** tant que le joueur reste enveloppé de cette aura noire.
- **Les Symptômes au combat :** L'animal commence à gémir, refuse de regarder le héros dans les yeux, et sa jauge d'Endurance Max (Page 25) baisse de 20%, terrifié par la présence invisible de l'Ange Déchu qui marche à vos côtés.

---

## 🔀 3. Les 3 Voies d'Évolution de l'Animal (Suivant vos Choix AAA)

Selon vos alliances de faction (Page 27) et vos compétences, la personnalité de votre animal va muter de trois manières distinctes :

### A. La Voie Protectrice (Héros Lumineux / Alignement Ordre-Marches)

- **Condition :** Haute loyauté, joueur utilisant principalement la `Branche 1 (Armes)` et la `Branche 10 (Diplomatie)`.
- **Comportement :** L'animal atteint le palier **Âme Sœur**. Il gagne la compétence passive *Sacrifice de Meute* : si les PV du joueur tombent à zéro, l'animal charge le Boss, détourne l'attention et offre une fenêtre de 5 secondes au joueur pour se soigner, évitant ainsi le système de mort punitive (Page 20).

### B. La Voie de la Corruption Enragée (Héros Sombre / Alignement Culte)

- **Condition :** Haute loyauté, mais joueur utilisant intensivement la `Branche 8 (Magie de Sang)`.
- **La Mutation Visuelle :** L'animal ne vous abandonne pas, mais il est contaminé par votre magie noire. Les yeux de votre Loup Nommé deviennent injectés de sang, son pelage tombe par endroits, révélant des runes de sang.
- **Comportement au Combat :** Il devient un **Molosse enragé**. Ses dégâts d'attaque augmentent de +50%, mais il est pris de folie : il n'écoute plus vos ordres, attaque de manière anarchique, et peut accidentellement mordre le joueur ou ses alliés en mode Coopération Asynchrone.

### C. La Rupture et le "Némésis Sauvage" (L'Abandon Réaliste)

- **Condition :** La loyauté tombe à **0** parce que le joueur a multiplié les massacres de civils innocents ou abusé des rituels du Culte sous ses yeux.
- **La Scène Déchirante (La Fuite) :** Au milieu de la nuit, pendant une phase de repos au feu de camp, une cinématique se déclenche. L'animal pousse un dernier hurlement de dégoût et de peur, montre les crocs au joueur, et s'enfuit à toute vitesse dans la forêt.
- **Le Retour du Némésis :** L'animal n'est pas effacé du code du jeu. Il retourne dans son biome d'origine. Si le joueur retourne dans la forêt 10 heures plus tard, son ancien compagnon est devenu le **Maître de Meute Alpha (Mini-Boss)** de la zone. Il a conservé le **Nom** que vous lui aviez donné, mais son IA a appris toutes vos habitudes de combat (Page 15). Il vous attaquera à vue avec une haine féroce, menant sa meute de loups pour se venger du monstre que vous êtes devenu.