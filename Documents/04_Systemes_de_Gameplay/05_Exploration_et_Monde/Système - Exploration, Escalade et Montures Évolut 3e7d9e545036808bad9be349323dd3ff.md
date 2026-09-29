# Système - Exploration, Escalade et Montures Évolutives

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🐎 Système - Exploration, Escalade & Montures Évolutives

Ce document technique définit les mécaniques de déplacement en monde ouvert, la verticalité sans temps de chargement et le système de montures éphémères (faune locale) versus permanentes (chevaux rares), incluant leurs statistiques d'attaque et de butin.

---

## 🧗 1. La Verticalité et l'Exploration sans Couture (Streaming)

Le monde ouvert est conçu à 100% sans écrans de chargement. Le joueur utilise son endurance physique pour explorer l'environnement de manière horizontale et verticale.

- **L'Escalade Libre (Vue TPS) :** Le héros peut grimper sur n'importe quelle surface rocheuse ou architecture médiévale (falaises des Canyons, remparts de la Capitale) à condition d'avoir de l'Endurance (🟢).
- **La Visée d'Infiltration (Vue FPS) :** En hauteur, le joueur bascule en vue FPS pour scanner la zone à l'arc ou repérer les routes de patrouille des IA collectives avant de redescendre.

---

## 🦌 2. Les Montures Éphémères & Mobs (La Faune Apprivoisée)

Grâce à la `Branche 9 (Empathie Sauvage)` de votre Arbre de Compétences, **chaque prédateur ou gibier de taille moyenne/grande peut être apprivoisé, monté ou utilisé comme compagnon de suivi**.

### 🚫 La Limite de Zone (La Peur de l'Inconnu)

Les animaux sauvages sont physiologiquement liés à leur biome d'origine.

- **La Mécanique :** Lorsque le joueur approche de la frontière invisible d'une nouvelle région (ex: quitter la Forêt pour entrer dans le Désert), l'animal s'arrête net et cabre. Un message système s'affiche à l'écran : **"La bête est terrifiée par le climat aride de cette région et refuse d'avancer."**
- **L'Abandon :** Le joueur est forcé de descendre. L'animal retourne vivre sa vie dans sa forêt d'origine.

---

## 🐎 3. La Rareté Absolue des Chevaux (Montures Permanentes)

Dans cet univers sombre, les chevaux sont une ressource militaire de luxe exclusivement contrôlée par *L'Ordre du Sceptre d'Or*. Ils sont extrêmement rares et chers.

- **L'Avantage Universel :** Le cheval est le seul animal domestiqué capable de traverser **tous les biomes du jeu** sans jamais avoir peur ou faire demi-tour.
- **Comment l'obtenir :** Le joueur doit soit l'acheter à un prix exorbitant au marché de la Capitale, soit en voler un lors d'une infiltration réussie dans une garnison de l'Ordre avec la `Branche 4 (Crochetage/Sabotage)`.

---

## 📊 4. Les 5 Statistiques Évolutives des Montures et Mobs

Tant que le joueur chevauche ou est suivi par un animal, celui-ci accumule de l'**XP de Monture** (jusqu'au niveau 99 bloqué à 99,99%). Chaque niveau permet d'attribuer des points dans ces 5 caractéristiques :

1. **Vitesse de Pointe :** Augmente la vélocité maximale au galop/sprint.
2. **Endurance Max :** Allonge la jauge d'endurance de sprint (🟢) de l'animal.
3. **Points de Vie (PV) :** Permet à la monture de survivre aux flèches ou magies ennemies sans désarçonner le joueur.
4. **Puissance d'Attaque (Nouveau) :** Détermine les dégâts infligés par l'animal lorsqu'il charge ou attaque à vos côtés (voir matrice ci-dessous).
5. **Perception du Butin (Nouveau) :** Augmente passivement le taux de drop (butin) du joueur lors de la récolte ou sur les cadavres ennemis, selon des spécialités propres à chaque espèce.

---

## 🧬 5. Matrice des Capacités et Taux de Drop Spécifiques

Chaque espèce possède un comportement de combat unique et un bonus de drop asymétrique qui oriente le choix du joueur :

| Espèce de Monture / Mob | Type d'Attaque Unique (Mêlée TPS) | Bonus de Taux de Drop Spécifique (Butin) | Utilité Stratégique en Jeu |
| --- | --- | --- | --- |
| **🐗 Sanglier Géant** (Forêt) | **Charge Fracassante :** Fonce en ligne droite, inflige des dégâts lourds et brise instantanément les boucliers et l'IA de Phalange des gardes. | **+30% Drop : Herbes & Racines** (L'animal déterre des plantes rares en fouillant le sol pendant vos arrêts). | Idéal pour le grind d'Alchimie et la destruction des lignes de défense militaires. |
| **🐺 Loup Sauvage** (Forêt) | **Morsure Flanc / Harcèlement :** Attaque les ennemis par-derrière pour détourner leur attention, brisant l'IA prédictive des Monstres Uniques. | **+25% Drop : Viande & Cuir** (Vos dépeçages sur le gibier sont parfaits grâce à son aide). | Le meilleur partenaire pour les combats complexes de boss et la chasse de subsistance. |
| **🦁 Lion des Canyons** (Désert) | **Bond Embusqué :** Saute depuis les falaises sur une cible, mettant l'ennemi au sol (Stagger) et ouvrant une fenêtre de coup critique en vue FPS. | **+20% Drop : Gemmes & Minerai rare** (Ses griffes révèlent des filons cachés dans les parois rocheuses). | Parfait pour la verticalité des Canyons et le farm de composants de forge légendaires. |
| **🐻 Ours des Montagnes** (Montagne) | **Frappe Tellurique :** Frappe le sol de ses pattes avant, générant une onde de choc qui repousse et étourdit tous les monstres de Ruche mineurs. | **+40% Drop : Armes/Armures brisées** (Capable de transporter des sacs de fer lourds sur son dos). | Le tank ultime pour traverser les zones infestées de monstres de nuée sans mourir. |
| **🐎 Cheval Militaire** (Universel) | **Ruade de Recul :** Donne un coup de sabot arrière si vous êtes encerclé, repoussant les soldats à 3 mètres. | **+15% Drop : Pièces de monnaie** (Augmente votre réputation passive auprès des marchands civils). | La seule monture permanente capable de changer de région sans vous abandonner. |

---

## 💀 6. Conséquence de la Mort (Pénitence Diégétique)

- **Pour le Cheval Permanent :** Si vous mourez (Page 20), il s'enfuit et retourne automatiquement aux écuries du dernier village visité, conservant toute son XP.
- **Pour le Mob Éphémère :** Le lien est rompu. L'animal redevient sauvage à l'endroit exact de votre mort. Le joueur devra retourner sur les lieux à pied pour tenter de le ré-apprivoiser avec la `Branche 9`, à condition qu'il n'ait pas été tué par la Ruche de monstres entre-temps.