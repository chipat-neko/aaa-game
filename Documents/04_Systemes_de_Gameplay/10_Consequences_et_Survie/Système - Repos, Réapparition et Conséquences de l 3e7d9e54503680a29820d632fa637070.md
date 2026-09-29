# Système - Repos, Réapparition et Conséquences de la Mort

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🛌 Système - Repos, Réapparition & Conséquences de la Mort

Ce document technique définit les mécaniques de repos (sécurisation de la progression) et le système de mort systémique. La mort du héros n'entraîne pas un écran de "Game Over" classique : le monde continue d'évoluer, le temps s'écoule et l'IA collective réagit à votre résurrection.

---

## ⛺ 1. Les Points de Repos et d'Ancrage (Spawn Points)

Le joueur peut choisir de se reposer dans différents endroits pour restaurer ses jauges d'Endurance (🟢) et de Mana (🔵), et fixer son point de réapparition.

- **Auberges (Villes, Villages) :** Le moyen le plus sûr. Payant (en pièces du Cartel). Offre un repos complet et réinitialise l'agressivité des monstres de la zone.
- **Feux de Campement (Monde ouvert) :** Gratuit, mais risqué. Le joueur doit utiliser du bois récolté.
    - *Risque d'embuscade :* Pendant le repos, il y a 15% de chances qu'une meute de prédateurs (loups, lions) ou des éclaireurs de l'Ordre attaquent le camp.
    - *Compagnon animal :* Si un **Loup Adopté** est présent, le risque d'embuscade tombe à 0%, car l'animal monte la garde et réveille le héros.
- **Le Stade 3 au coin du feu :** C'est durant ces moments de repos que l'illusion physique de l'Ange Déchu s'assoit à vos côtés pour déclencher des dialogues psychologiques profonds et négocier l'achat de compétences Ultimes.

---

## 🩸 2. La Résurrection par le Démon (Le Lore de la Mort)

Lorsque les PV du héros tombent à zéro, il ne meurt pas définitivement. L'Ange Déchu piégé en lui refuse de perdre son réceptacle. L'entité utilise une quantité massive de magie noire pour recoudre les chairs du héros et le ramener à la vie au dernier point de repos utilisé.

- **Le Coût Psychologique :** Chaque mort augmente artificiellement la **Jauge de Synchronicité** du Démon, accélérant l'apparition des **Stades de Symptômes** (le joueur entendra la voix se moquer de sa mort dès son réveil).

---

## 🌍 3. Les Répercutions Systémiques de la Mort (AAA)

### A. L'Impact sur les Quêtes Secondaires (Échec Contextuel)

Contrairement aux quêtes principales qui se réinitialisent au checkpoint, **les quêtes secondaires échouent définitivement si le joueur meurt en cours de route**.

- *Le facteur Temps :* Pendant que le Démon reconstitue votre corps au campement, des heures se sont écoulées dans le monde ouvert.
- *Exemple :* Si un villageois vous demande de sauver sa fille attaquée par un *Sanglier Alpha (Mini-boss)* et que vous mourez pendant le combat, vous vous réveillez à l'auberge. La quête est un **Échec**. En retournant sur place, la fille est morte ou a disparu, et l'**IA Collective** du village bascule en mode "Deuil/Colère" contre vous.

### B. Le Témoignage des PNJ (L'IA Collective Horrifiée)

Si le joueur meurt au milieu d'une rue de la Capitale ou d'un village sous les yeux des habitants, et qu'il réapparaît (Respawn) à l'auberge locale quelques heures plus tard, le monde se souvient.

- **La Rumeur Visuelle :** L'IA Collective met à jour les dialogues des PNJ témoins.
    - *Dialogue d'un villageois terrorisé :* "Par les Dieux... Je vous ai vu. Je vous ai vu vous faire transpercer par l'épée de la garde royale sur la place du marché. J'ai vu votre cadavre ! Qu'est-ce que vous êtes... un spectre ? Arrière !"
- **L'Impact Politique :** Mourir publiquement et ressusciter prouve à l'Inquisition du Château que vous êtes l'hôte d'une entité hérétique. L'IA Isolée du Château peut instantanément émettre un *Décret de Purge* dans la zone, transformant les gardes ordinaires en chasseurs de démons agressifs à vue.

### C. La Réactivité en Mode Coopération Asynchrone

Si le **Joueur 1** meurt mais que le **Joueur 2** survit au combat :

- Le Joueur 1 réapparaît à l'auberge la plus proche et doit chevaucher pour revenir.
- Le Joueur 2 peut décider de terminer la quête secondaire seul et de garder 100% du butin.
- Les PNJ du village diront au Joueur 2 : *"Votre ami a péri au combat... du moins c'est ce qu'on croyait. On l'a vu courir près de l'auberge avec des marques noires sur le visage. Rompez vos liens avec lui avant qu'il ne vous maudisse."*