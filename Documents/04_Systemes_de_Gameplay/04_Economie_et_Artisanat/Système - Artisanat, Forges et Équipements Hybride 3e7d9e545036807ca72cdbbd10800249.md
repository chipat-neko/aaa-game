# Système - Artisanat, Forges et Équipements Hybrides

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⚒️ Système - Métiers, Forges & Équipements Hybrides

Ce document technique définit le fonctionnement des métiers d'artisanat (Forge, Alchimie/Cuisine, Minage, Chasse). La progression repose sur trois piliers : l'initiation par des Maîtres de guilde, un niveau d'expérience propre à chaque métier et une validation de la pratique avant de pouvoir améliorer des équipements de haut rang.

---

## 👨‍🏫 1. L'Apprentissage Initial : Les Maîtres Artisans

Le joueur ne possède aucune compétence de craft au début du jeu. Pour débloquer un métier, il doit trouver et convaincre un **Maître Artisan** dans le monde ouvert.

- **Le Maître Forgeron :** Situé dans la première Ville Régionale (Oakhaven). En accomplissant sa quête secondaire, il vous enseigne la théorie de la forge et débloque le niveau 1 du métier.
- **Le Maître Alchimiste / Cuisinier :** Un érudit banni du Conclave caché dans la forêt des Marches Sauvages. Il vous apprend à manipuler les chaudrons pour transformer le gibier et les plantes en remèdes ou en bonus de statistiques.

---

## 📈 2. Le Système de Progression et d'Expérience des Métiers

Chaque métier progresse de manière indépendante (du Niveau 1 au Niveau 50). L'efficacité et les opportunités augmentent proportionnellement.

### ⛏️ Le Métier de Récolte (Ex: Minage)

- **Niveau de Métier :** Détermine la dureté des métaux que le joueur peut extraire.
    - *Niveau 1 :* Fer classique (Canyons).
    - *Niveau 20 :* Soufre volcanique.
    - *Niveau 40 :* Cristaux du Vide (Donjons de haut niveau).
- **Taux de Drop Évolutif :** Plus le niveau de Minage est élevé, plus le **taux de drop de pépites rares** ou de gemmes brutes incrustées dans la roche augmente sur un même gisement.

### 🔨 Le Métier de Fabrication (Ex: Forge)

- **Le Verrouillage du Maîtrise Pratique (AAA) :** Le joueur ne peut pas améliorer une arme de niveau supérieur à son propre niveau de métier.
    - *Scénario :* Le joueur explore une ruine et trouve une **Épée Royale de niveau 30**. Il souhaite l'améliorer à la forge pour la monter au **Niveau 35**.
    - *La Règle :* Si le niveau de Forge du joueur est seulement au niveau 10, le jeu bloque l'action avec le message : *"Vous n'avez pas l'expérience requise pour manipuler un acier de ce rang. Forgez d'abord des armes de votre niveau."*
- **Le Grind Cohérent :** Pour monter son métier de niveau 10 à 30, le joueur est obligé de récolter des composants de fer et de **créer des lames de son niveau**. Cette boucle d'artisanat lui fait gagner de l'expérience de métier, affinant sa technique jusqu'à ce qu'il soit capable d'améliorer son Épée Royale de niveau 30.

---

## 📐 3. L'Infusion Pratique Expérimentale (La Forge Secrète)

Une fois le niveau de métier requis atteint, le joueur combine l'acier militaire et la magie de l'Ange Déchu sans suivre de recette ("Pratique +++").

- **Les Améliorations Proportionnelles :** Améliorer une arme ou une armure augmente ses statistiques physiques de base (Dégâts, Défense) mais débloque également des multiplicateurs sur les **Feintes Élémentaires** (Page 9).
    - *Exemple :* Monter un Arc composite du niveau 15 au niveau 30 double ses dégâts de flèche en vue FPS, et augmente de 50% la taille du micro-trou noir généré lors d'une infusion à l'énergie du Vide.
- **Le Risque de l'Échec Punitif (Page 20) :** Si le joueur tente une fusion magique expérimentale sur une enclume de campement et échoue, l'arme n'est pas détruite, mais les composants rares de magie (essences d'Ombre, sang corrompu) sont consumés. Si le joueur meurt dans la foulée, ses minerais bruts restent sur son cadavre dans la zone sauvage.

---

## 👥 4. Impact sur les IA Collectives et la Coopération

- **La Reconnaissance par les Pairs :** Atteindre le niveau maximum (Maître) dans un métier modifie la mémoire collective des PNJ artisans. Les forgerons de la Capitale vous saluent par votre titre, vous offrent des réductions exclusives sur les outils et vous confient des **Quêtes ++ d'artisanat** uniques (ex: forger l'armure personnelle du Prévôt du Château).
- **La Synergie Économique en Coop Asynchrone :**
    - Le **Joueur 1** se spécialise à 100% dans le Minage (il extrait des cristaux du vide introuvables pour les autres).
    - Le **Joueur 2** se spécialise à 100% dans la Forge.
    - *L'échange :* Le Joueur 1 donne ses minerais au Joueur 2, qui lui fabrique en retour une arme hybride de niveau 40. Le système asynchrone enregistre cette interaction, et les PNJ du Cartel moucharderont au marché noir : *"Ces deux-là contrôlent tout le fer de la région... Si vous voulez de l'acier runique, c'est à eux qu'il faut parler."*