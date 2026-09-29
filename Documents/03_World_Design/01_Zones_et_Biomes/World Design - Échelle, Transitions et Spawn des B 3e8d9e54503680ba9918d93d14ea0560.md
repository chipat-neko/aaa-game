# World Design - Échelle, Transitions et Spawn des Boss

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🗺️ World Design - Échelle, Transitions & Spawn des Boss

Ce document technique corrige les défauts géométriques de la carte mondiale afin d'assurer une immersion réaliste de niveau AAA, et définit les règles de spawn asynchrones des Boss Régionaux.

---

## 📐 1. Règles d'Échelle et Zones de Transition Organiques

Pour éviter l'effet "découpage artificiel" de la carte visuelle, le moteur de jeu applique des zones tampons géantes entre les biomes.

- **Mise à l'Échelle Globale (Scale AAA) :** Le diamètre de la Pangée circulaire est fixé à **50 kilomètres de rayon**. Traverser la carte du Sud (Hameau de départ) au Centre (Capitale) nécessite 30 minutes de chevauchée ininterrompue en ligne droite à dos de cheval militaire.
- **La Zone Tampon Ouest (Les Plaines Arides) :** Zone de friction de 5 km entre la Plaine et les Canyons. L'herbe émeraude jaunit, le sol se craquelle et la pierre rouge des canyons émerge sous forme de monolithes isolés et de petites crevasses.
- **La Zone Tampon Est (Les Bois Murmurants) :** Zone de friction de 6 km entre la Plaine et la Forêt Sauvage. La densité des arbres augmente de manière exponentielle, la lumière du jour diminue et la brume violette commence à stagner au sol.

---

## 👑 2. Algorithme de Spawn Aléatoire des 3 Boss Régionaux (L'IA Absorbante)

Chaque grand biome abrite 3 Boss Régionaux à l'IA Absorbante (Page 24). Leurs emplacements ne sont jamais fixes sur la carte du joueur pour forcer l'exploration pure.

- **Le Système de Nœuds Flottants :** Le Level Design implante 15 arènes contextuelles par biome. Au chargement de la région, l'algorithme sélectionne aléatoirement 3 arènes pour y injecter les Boss. Les 12 autres arènes deviennent des zones de récolte de minerais rares (Page 39) ou des nids de prédateurs Alphas.
- **Algorithme d'Anti-Chevauchement (No-Stacking Grid) :**
    - *Règle 1 :* Un nœud de spawn ne peut accueillir qu'une seule entité de boss à la fois.
    - *Règle 2 :* Distance de sécurité de 5 000 mètres minimum entre deux boss actifs.
    - *Règle 3 :* Si le joueur est engagé dans un combat contre le Boss A, le code verrouille les déplacements du Boss B et C dans la région pour empêcher toute collision d'IA massives simultanées au même endroit.