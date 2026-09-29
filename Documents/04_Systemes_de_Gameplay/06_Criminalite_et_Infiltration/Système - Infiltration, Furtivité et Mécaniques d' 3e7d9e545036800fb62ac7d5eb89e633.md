# Système - Infiltration, Furtivité et Mécaniques d'Ombre

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 👥 Système - Infiltration, Furtivité & Mécaniques d'Ombre

Ce document technique définit les règles d'infiltration, de détection acoustique/visuelle et de sabotage. Le gameplay repose sur l'exploitation des ombres, la friction des revêtements au sol, l'alternance des perspectives (TPS/FPS) et la gestion de l'IA collective.

---

## 👁️ 1. Les Deux Perspectives de l'Infiltration (TPS vs FPS)

La bascule instantanée via la touche `R3` (Stick droit) ou le bouton central de la souris modifie radicalement les capacités de détection et d'action du joueur.

- **Vue TPS (Troisième Personne) — La Conscience Spatiale :**
    - *Utilité :* Indispensable pour observer les cônes de vision des patrouilles de l'Ordre derrière un mur ou un pilier du Château sans se faire repérer (Corner-peeking).
    - *Gameplay :* Permet d'initier les éliminations silencieuses au corps-à-corps (`Branche 2 : Camouflage`) en arrivant silencieusement dans le dos d'une sentinelle.
- **Vue FPS (Première Personne) — La Précision et le Sabotage :**
    - *Utilité :* Obligatoire pour le tir de précision à l'arc à longue distance et l'analyse technique des systèmes de sécurité.
    - *Gameplay :* Le joueur passe en vue FPS pour utiliser ses flèches de Glace (Page 9) afin d'éteindre discrètement les torches ou les brasiers, créant ainsi des zones d'ombre artificielle. C'est aussi dans cette vue que s'active le mini-jeu mécanique de **Crochetage des Serrures** (`Branche 4`).

---

## 🌙 2. Les Piliers Systémiques : Ombre, Lumière et Acoustique

La jauge de détection des ennemis dépend de deux facteurs environnementaux calculés en temps réel par le code du jeu.

### A. La Visibilité (L'Aura Lumineuse)

- **Les États de Lumière :** Le corps du joueur possède trois états de visibilité : `Plein Jour` (détection instantanée à 30 mètres), `Pénombre` (détection lente), et `Ombre Totale` (détection impossible à moins de 3 mètres, sauf si le joueur fait du bruit).
- **L'Impact du Syndrome de Fusion (Stade 3) :** Si le joueur est corrompu par la magie de sang, son aura noire et ses veines luisantes (Page 15) réduisent l'efficacité du camouflage à l'ombre. Les Sentinelles du Vide du Château (Page 17) détectent les fluctuations de mana et annulent l'effet d'ombre, forçant le joueur à détruire leurs cristaux à l'arc en vue FPS avant de s'infiltrer.

### B. L'Acoustique (Le Bruit des Pas et la Texture du Sol)

Le bruit généré par le joueur dépend de son **poids d'équipement** (Armures lourdes de l'Ordre vs Tenues de Traqueur des Marches) et de la nature de la surface foulée :

- *Tapis, Herbe haute :* Absorption phonique totale. Le joueur peut sprinter accroupi.
- *Dalles de pierre, Parquet (Château) :* Bruit de pas modéré. Le joueur doit marcher lentement.
- *Flaques d'eau (Météo Pluie), Graviers :* Bruit de pas amplifié de +100%. Marcher envoie une onde sonore qui alerte instantanément l'**IA Collective** des gardes dans un rayon de 15 mètres.

---

## 🛡️ 3. Le Comportement de l'IA Collective face à la Furtivité

Les gardes du jeu ne patrouillent pas sur des lignes droites figées de manière stupide. Leurs réactions face à une anomalie sont graduelles.

[État Calme] ➡️ [Suspicion (Onde Sonore/Visuelle)] ➡️ [Enquête Locale] ➡️ [Alerte de Ruche / Combat]

1. **La Suspicion Individuelle :** Un garde repère une flèche qui éteint une torche ou entend un bruit de pas dans l'eau. Sa jauge de détection se remplit. Il quitte sa ronde pour faire une **Enquête Locale**.
2. **Le Mouchardage Acoustique :** Si le garde trouve un cadavre caché dans un buisson ou une porte crochetée à la hâte, il active son *Protocole d'Alerte Silencieux* (Page 17). L'**IA Isolée du Château** ou de la Ville se met en état de siège : les gardes doublent leurs patrouilles, ferment les herses de sécurité, et modifient leurs patterns de ronde pour traquer les intrus.

---

## 👥 4. L'Infiltration en Mode Coopération Asynchrone

Infiltrer une zone à deux ou quatre joueurs est un exercice de synchronisation extrême où le maillon faible peut saboter toute la mission.

- **Le Partage de Conscience :** Si le **Joueur 1** déclenche l'alarme dans le Quartier Est en marchant dans une flaque d'eau avec son armure lourde, l'IA collective de la zone passe en mode Combat. **Le Joueur 2**, bien qu'il soit parfaitement caché dans l'ombre à l'autre bout de la cour (Quartier Ouest), verra instantanément les gardes de sa propre zone quitter leurs postes pour courir prêter main-forte à l'Est, libérant ainsi son accès aux appartements du Général de manière totalement systémique.