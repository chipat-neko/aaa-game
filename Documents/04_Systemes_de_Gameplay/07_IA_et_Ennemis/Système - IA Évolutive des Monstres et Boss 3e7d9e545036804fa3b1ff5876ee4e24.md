# Système - IA Évolutive des Monstres et Boss

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🔮 Système - IA Évolutive des Monstres et Boss

Ce document détaille l'écosystème d'apprentissage des créatures surnaturelles. L'IA n'est pas statique : elle analyse les faiblesses, les patterns et les habitudes de combat du joueur pour s'adapter dynamiquement.

---

## 🦠 1. Les Monstres de Zone : L'IA Collective de Ruche

- **Mécanique d'apprentissage :** Partagée à l'échelle de la région.
- **Fonctionnement :** Si le joueur traverse une région en éliminant tous les monstres à l'aide de combos à l'épée, la "mémoire de ruche" de la zone enregistre cette information.
- **Adaptation :** Au bout de quelques combats, les nouveaux monstres qui apparaissent dans cette zone vont adapter leurs patterns : ils vont garder leurs distances, prioriser les esquives arrière, ou faire pousser des plaques de cuir rigide sur leur corps pour réduire les dégâts de lame. Le joueur est alors forcé de basculer sur l'arc ou la magie pour briser cette adaptation.

---

## 👑 2. Les Boss Régionaux (Maximum 3 par Zone) : L'IA Absorbante

Chaque grande région du monde ouvert abrite un maximum de **3 Boss Majeurs**. Leurs compétences dépendent de l'histoire du joueur dans la zone.

- **Mécanique d'absorption :** Au moment où le joueur engage le combat contre l'un de ces 3 Boss, l'IA du Boss télécharge l'intégralité des données de la zone (**Données de la Faune + Données des Monstres**).
- **Comportement AAA :**
    - *Si le joueur a beaucoup chassé le gibier (sangliers/loups) :* Le Boss copie leurs tactiques de meute (charges lourdes, feintes de contournement).
    - *Si le joueur a affronté les monstres à la magie :* Le Boss développe instantanément une barrière de résistance magique élémentaire et renvoie les sorts. Le Boss devient le reflet parfait des habitudes de combat du joueur dans cette région.

---

## 👻 3. Les Monstres Uniques (3 au total dans tout le jeu) : L'IA Prédictive (Machine Learning)

Ces 3 monstres sont des anomalies mythiques de l'Ange Déchu. Leur apparition est **100% aléatoire** n'importe où dans le monde ouvert. Ils possèdent l'IA la plus avancée du jeu.

- **Mécanique d'analyse en temps réel :** Ils n'attendent pas la fin d'un combat pour apprendre. Ils analysent le joueur **pendant** l'affrontement en cours.
- **Variables traquées par l'IA :**
    - *Le timing de parade du joueur :* Si le joueur fait trop de parades parfaites, le monstre unique va feinter ses attaques (annuler son animation au dernier moment) pour briser le timing du joueur.
    - *L'attaque ou le sort favori :* Si le joueur abuse du même combo, le monstre unique va mémoriser le pattern et appliquer un contre parfait (ex: attraper la lame au vol ou absorber le sort pour se soigner).
- **Conséquence :** Chaque combat contre un Monstre Unique est une partie d'échecs mortelle. Le joueur doit constamment changer d'arme, alterner entre vue FPS et TPS, et mélanger ses magies pour induire l'IA en erreur.

 Visualiser le flux d'apprentissage dans le jeu

[Actions du Joueur]
├──> Tue à l'épée ──> [IA de Ruche (Zone)] ──> Les monstres de la zone esquivent les lames
└──> Chasse le gibier ──> [IA Absorbante (Boss)] ──> Le Boss de fin de zone utilise des charges de sanglier
└──> Abuse du même sort ──> [IA Prédictive (Monstre Unique)] ──> Le monstre unique contre le sort en temps réel