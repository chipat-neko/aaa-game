# Système - Coopération et Réactivité Individualisée

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 👥 Système - Coopération et Réactivité Individualisée (Coop Asynchrone AAA)

Ce document définit les règles de réactivité du monde ouvert lorsque le jeu est joué en coopération (2 à 4 joueurs). Le monde ne réagit pas au "groupe", mais analyse les actions de chaque joueur de manière indépendante, modifiant les dialogues et la vision des PNJ au cas par cas.

---

## 🧬 1. Le Système d'Historique par Joueur (Player ID Tracking)

Le moteur de jeu attribue un identifiant unique à chaque joueur (Joueur 1, Joueur 2, etc.). Toutes les actions (quêtes validées, PNJ tués, vol, utilisation de la magie démoniaque) sont enregistrées sur le profil du joueur qui a commis l'action, et non sur l'Hôte de la partie.

- **Variables de Réputation Multi-Couches :** Un même PNJ ou une même IA collective peut être **Allié** avec le Joueur 1 et **Hostile/Méfiant** envers le Joueur 2 au même moment.

---

## 💬 2. Les Dialogues Croisés et la "Dénonciation" des PNJ

Lorsqu'un joueur interagit avec un PNJ, l'IA du PNJ vérifie d'abord les actions accomplies par *l'ami* du joueur dans la zone avant de formuler ses lignes de dialogue.

### 🎭 Scénario Type (Application de la mécanique) :

1. **L'Action du Joueur 1 :** Le Joueur 1 accepte et valide en secret une quête pour le *Cartel de la Brume* (ex: voler les plans d'armure de la garnison d'Oakhaven).
2. **L'Interduction du Joueur 2 :** Le Joueur 2 entre dans la garnison et va parler au Sergent de *L'Ordre du Sceptre d'Or* pour prendre une quête de chasse de monstres.
3. **La Réaction Systémique de l'IA :** Le Sergent de l'Ordre s'adresse au Joueur 2, mais l'IA collective détecte que le Joueur 1 (son ami) vient de commettre un méfait contre l'Ordre.
    - *Dialogue du PNJ au Joueur 2 :* "Je veux bien vous faire confiance, l'ami... Mais votre compagnon de route traîne un peu trop près des coffres du Cartel ces derniers temps. À votre place, je garderais un œil sur lui. S'il nous trahit, vous paierez pour lui."

---

## 🌍 3. La Vision de la Map et l'Instabilité Visuelle en Coop

Puisque chaque joueur progresse à son rythme dans son utilisation de la magie de l'Ange Déchu, le **Syndrome de Fusion (Les Stades de Symptômes)** est rendu de manière purement individuelle (côté client).

- **Décalage Visuel des Joueurs :**
    - Si le Joueur 1 abuse de la magie démoniaque (Stade 3 des symptômes), il verra l'environnement se distordre, le ciel changer de couleur et l'illusion physique de l'Ange Déchu marcher à ses côtés dans les rues.
    - Le Joueur 2, s'il joue un style purement physique (Stade 1), verra la ville d'Oakhaven de manière totalement normale et lumineuse. Il verra simplement son ami (Joueur 1) faire des mouvements étranges dans le vide ou parler tout seul devant le feu de camp.
- **Les Quêtes Invisibles :** L'illusion de l'Ange Déchu peut donner une quête principale exclusive au Joueur 1 en plein milieu de la rue. Le Joueur 2 verra le Joueur 1 s'arrêter et parler à un espace vide, renforçant l'effet de folie et de maturité du scénario.

---

## ⚖️ 4. Les Choix de Fin de Quête en Coopération

Lors de quêtes majeures (comme la Quête Principale 2 avec le Schisme du Culte), si les joueurs ne sont pas d'accord, le jeu n'impose pas un vote à la majorité. Il laisse la liberté systémique agir.

- **Scission du Groupe :** Si le Joueur 1 choisit de s'allier aux *Éveillés* et que le Joueur 2 refuse et attaque les hérétiques, le combat se déclenche. Les joueurs peuvent se retrouver à devoir combattre dans deux camps opposés en plein cœur de la quête, brisant temporairement leur alliance jusqu'à la résolution du conflit local.