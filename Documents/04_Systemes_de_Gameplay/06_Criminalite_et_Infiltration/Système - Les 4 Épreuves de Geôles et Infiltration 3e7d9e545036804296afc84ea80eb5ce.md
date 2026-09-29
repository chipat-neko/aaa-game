# Système - Les 4 Épreuves de Geôles et Infiltration

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🏰 Système - Les 4 Épreuves de Geôles & Infiltration (Incarcérations Spécifiques)

Ce document technique détaille les boucles de gameplay exclusives activées lorsque le joueur se fait capturer vivant par l'une des 4 forces majeures du jeu. Chaque incarcération suspend le système de mort et applique une épreuve sur-mesure basée sur vos métiers et votre arbre de compétences.

---

## 🏛️ 1. L’Ordre du Sceptre d’Or : La Forteresse d'État (Infiltration Classique)

- **Atmosphère :** Cellule en pierre froide, rats, bruits de patrouilles lourdes de la Garde Royale.
- **Le Mini-Jeu : Le Crochetage Acoustique (Vue FPS obligée)**
    - *Mécanique :* Le joueur utilise un outil de fortune trouvé au sol. L'écran zoome sur le mécanisme de la serrure. Le joueur doit faire tourner ses sticks analogiques ou sa souris pour aligner les goupilles en se basant sur le son (Spatialisation 3D). Un clic aigu indique la bonne position.
    - *La Friction de l'IA Isolée :* Si le joueur force trop vite, l'outil se brise. Le bruit alerte le Maître de Phalange du couloir (Page 17). La sécurité est renforcée et votre cellule est verrouillée par un verrou magique inviolable, vous forçant à attendre l'aide asynchrone du **Joueur 2** depuis l'extérieur.

---

## 🕳️ 2. Le Cartel de la Brume : Les Mines Clandestines (L'Épuisement Physique)

- **Atmosphère :** Grottes poussiéreuses sous haute chaleur dans les Canyons, bruits de pioches, mercenaires du Cartel surveillant les esclaves depuis des passerelles en bois.
- **Le Mini-Jeu : Le Sabotage Structurel (Métier de Minage — Page 24)**
    - *Mécanique :* Le joueur n'est pas enfermé, il est enchaîné à un filon de fer. Il doit vider sa jauge d'Endurance (🟢) en minant pour le Cartel afin de purger sa dette financière de crime.
    - *L'Évasion Pratique :* Si le joueur possède un niveau de Minage élevé, il peut choisir de frapper discrètement les piliers de soutènement en bois de la mine plutôt que le fer. Un mini-jeu de rythme s'active : frapper au moment exact où un prisonnier pousse un cri ou au moment où un wagonnet passe pour masquer le bruit.
    - *Le Climax :* Au bout de 5 sabotages réussis, le plafond de la mine s'effondre partiellement. Une immense poussière aveugle l'IA collective des mercenaires. Le joueur a 45 secondes pour briser ses chaînes, voler les coffres de saisie et s'enfuir à dos de *Lion des Canyons* (Page 25).

---

## 🩸 3. Le Culte du Premier Sang : L'Autel du Sacrifice (L'Action Chronométrée)

- **Atmosphère :** Catacombes éclairées aux bougies de sang, incantations murmurées par une IA de Nuée, le héros est attaché sur un autel en pierre au centre d'un cercle sacrificiel.
- **Le Mini-Jeu : La Surtension de Chair (Arbre de Compétences — Branche 8)**
    - *Mécanique :* Une jauge de temps de 5 minutes s'affiche à l'écran. C'est le temps qu'il reste avant que le Grand Prêtre orthodoxe ne plonge sa dague dans votre cœur pour extraire Malak-Gath. Le combat physique est impossible.
    - *Le Sacrifice :* Le joueur doit maintenir les gâches élémentaires pour forcer la magie brute de l'Ange Déchu à traverser ses veines sans arme forgée (Page 32). Chaque seconde de charge détruit les chaînes magiques du Culte mais consume 10% de la jauge de PV maximum du joueur.
    - *La Résolution :* Le joueur brise ses chaînes au dernier moment. Il se retrouve au milieu de la clairière ou de la crypte avec seulement 15% de sa vie, forcé de massacrer les fanatiques à mains nues en utilisant le système de posture (Page 32) avant d'être submergé par les renforts.

---

## 🧪 4. Le Conclave du Voile : La Bulle de Stase (Le Puzzle Logique)

- **Atmosphère :** Laboratoire magique aseptisé de haute technologie, le joueur flotte dans une sphère d'énergie bleue suspendue au plafond d'une Forteresse Volante.
- **Le Mini-Jeu : Le Court-Circuit Optique (Vue FPS / Précision)**
    - *Mécanique :* La bulle de stase siphonne passivement 100% de votre Mana (🔵). Impossible de lancer le moindre sort. Le joueur doit observer l'environnement à 360° en passant en **Vue FPS**.
    - *Le Puzzle :* Le joueur doit repérer les 3 cristaux de focalisation qui projettent les rayons laser bleus maintenant la bulle. En utilisant des objets physiques trouvés dans ses poches (débris, boutons métalliques), le joueur doit viser manuellement et lancer l'objet avec une trajectoire parabolique parfaite pour briser les lentilles des cristaux.
    - *La Conséquence :* Briser les 3 cristaux désactive la stase et provoque une **Anomalie Magique de Zone** (Météo artificielle en intérieur, gravité inversée). L'IA collective des érudits est prise de panique face aux dysfonctionnements, vous offrant une fenêtre parfaite pour vous faufiler vers les hangars de montures.

---

## 👥 5. Matrice Réactive de la Coopération Asynchrone (Le Rachat vs L'Assaut)

Si un joueur se fait enfermer dans l'une de ces geôles, le **Joueur 2** (resté libre) reçoit instantanément une mise à jour de ses objectifs sur sa propre carte de monde ouvert :

| Lieu de Capture | Action Initiale du Joueur 2 | Alternative Économique / Faction | Conséquence en cas de Trahison en Coop |
| --- | --- | --- | --- |
| **Forteresse de l'Ordre** | Infiltration discrète par les égouts ou les toits (Page 29). | Payer la caution officielle au poste de garde via la `Branche 10` (Diplomatie). | Le Joueur 2 utilise le laissez-passer pour entrer dans la cellule, mais vole le dossier secret du Joueur 1 (Page 12) avant de fuir. |
| **Mines du Cartel** | Lancer un assaut frontal sous une *Tempête de Sable* pour masquer les bruits de tir (Page 26). | Déposer une rançon de 8 000 pièces d'or dans le coffre secret de La Faille (Page 23). | Le Joueur 2 laisse le Joueur 1 miner pendant 2 heures pour purger sa dette, profitant de ce temps pour vider les filons rares en solo. |
| **Autel du Culte** | Intercepter le convoi de rituels dans la forêt profonde à l'aide de votre *Loup Nommé* (Page 22). | S'allier temporairement au camp des *Éveillés* pour déclencher un schisme armé (Page 10). | Le Joueur 2 attend la fin des 5 minutes. Le Joueur 1 meurt définitivement de la quête. Le Joueur 2 récupère les artefacts sur son cadavre. |
| **Bulle du Conclave** | Saboter les générateurs d'ancrage de la Forteresse Volante depuis le Quartier Nord (Page 16). | Revendre des secrets militaires à l'Inquisition pour qu'ils bombardent le laboratoire. | Le Joueur 2 infiltre la salle des coffres, pille les armures runiques de niveau 90 du Joueur 1, et le laisse enfermé. |