# World Design - Le Biome du Nord : Les Pics Célestes

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🗺️ World Design - Le Biome du Nord : Les Pics Célestes

Ce document technique et narratif cartographie la région gelée d'Aethelgard. C'est le biome le plus complexe et vertical de la carte, conçu pour exploiter le Système d'IA du Conclave, le vol de montures, le blizzard à occlusion visuelle et les puzzles de stase.

---

## ⛰️ 1. Structure Géologique, Glace & Lévitation (Level Design AAA)

Les Pics Célestes poussent la verticalité de l'univers à son paroxysme absolu. Le terrain est fracturé entre des montagnes enneigées au sol et des îles de marbre blanc suspendues dans le ciel par inversion magnétique.

- **La Toundra Inférieure (Les Plaines Gelées) :** Un désert de glace et de neige balayé par les vents. C'est le biome des mines d'Obsidienne du Néant (Page 47). Le froid y est si intense que la régénération de l'Endurance (🟢) y est ralentie de 30%.
- **Les Pics Verticaux (Les Cols de l'Inquisition) :** Des falaises de glace glissantes et des sentiers escarpés. L'escalade libre classique y consomme deux fois plus d'endurance, forçant le joueur à tracer des itinéraires intelligents ou à utiliser une monture adaptée comme l'**Ours des Montagnes** (Page 25).
- **La Couronne Céleste (Les Îles en Lévitation) :** Des blocs de marbre et de ruines antiques flottant entre 50 et 200 mètres au-dessus du sol. Inaccessibles à pied, ces îles exigent l'utilisation d'une monture volante ou le piratage des ascenseurs à flux d'arcane du Conclave.

---

## 📍 2. Les Points d'Intérêt Majeurs (POI du Nord)

La région d'Aethelgard est divisée en 4 complexes technologiques majeurs régis par la "Conscience Réseau" du Conclave :

### 🧪 POI A : La Forteresse Zénith (Hub du Conclave)

- **Démographie :** 600 habitants (Mages, Érudits et Golems connectés, Page 44).
- **Lore :** La plus grande forteresse volante du **Conclave du Voile**. Elle lévite directement au-dessus du pic central et siphonne le mana de la région pour mener des expériences sur le Vide.
- **Utilité :** Centre névralgique pour obtenir les parchemins d'**Apprentissage Théorique** de haut niveau. C'est ici que se cache l'herboriste renégat, **Maître Enseignant d'Alchimie & Cuisine (Niveaux 1 à 99, Page 39)**. En cas d'arrestation, vous y subissez l'épreuve de la *Bulle de Stase* (Page 37).

### 🕳️ POI B : Les Portails Brisés (Le Sanctuaire des Murmures)

- **Lore :** Une chaîne de monolithes antiques que le Conclave tente de forcer. La zone est protégée au sol par la faction mineure des **Murmures du Passé**.
- **Mécanique :** Les archéologues vous confient des missions de sabotage pour couper les lignes d'alimentation de la Forteresse Zénith afin de stabiliser le climat.

### 🏔️ POI C : L'Abri des Veilleurs (Le Refuge des Glaces)

- **Lore :** Un monastère fortifié taillé dans la roche d'un col montagneux, géré par les **Veilleurs de l'Aube**.
- **Utilité :** C'est le seul point de repos sécurisé (Auberge, Page 20) de la région inférieure. Il sert de hub pour ravitailler les réfugiés qui fuient les purges magiques du Nord.

### 💀 POI D : Les Crevasses de l'Obsidienne (La Mine de Fin de Jeu)

- **Lore :** Des failles souterraines gelées d'où émerge de l'Obsidienne du Néant et des Cristaux du Vide (Niveaux 70 à 98).
- **Utilité :** Zone d'extraction ultime pour le métier de **Minage**. Elle est infestée de monstres de Ruche de glace utilisant des tactiques de harcèlement en réseau.

---

## 👑 3. Algorithme des 3 Boss Flottants des Pics Célestes

Conformément à la grille de non-chevauchement (Page 48), le Nord possède 15 nœuds de spawn répartis entre les pics et les îles volantes. Le code y injecte aléatoirement 3 Boss Alphas de fin de jeu :

1. **Le Golem de Givre Absorbant :** Un titan de glace connecté au Réseau de Mana Partagé (Page 44). Il télécharge l'historique de vos combats. Si vous abusez des feintes de Feu, il génère une barrière thermique inversée qui absorbe les flammes pour régénérer ses PV.
2. **Kratos le Dévoreur (Monstre Unique — IA Prédictive) :** Le Béhémoth du Néant (Page 34). Il apparaît de manière 100% aléatoire. Si vous l'attaquez depuis les îles en vue FPS, il utilise la gravité pour vous attirer au sol. Sa capture possède un taux de réussite de 0,01% et provoquera la mort de votre loup.
3. **La Chimère des Cimes :** Un prédateur volant qui traque le joueur dans les airs. Ses attaques lourdes peuvent projeter le joueur en bas d'une île flottante, déclenchant le système de blessures permanentes (Page 43) en cas de chute.

---

## ⛈️ 4. Réaction Climatique Spécifique (La Tempête de Neige / Whiteout)

Lorsque la météo de la **Tempête de Neige** s'active sur les Pics Célestes :

- **L'Occlusion Visuelle :** La visibilité à l'écran tombe à **15%** (effet de brouillard blanc total). L'interface de la mini-carte et le curseur de position du joueur sont désactivés (Page 49).
- **Le Verrouillage Logique :** La Grille de Mana du Conclave sature à cause des interférences. Tous les *Relais de Stase* (Voyage Rapide, Page 45) de la région Nord se verrouillent automatiquement, bloquant le joueur dans le biome.
- **La Friction Tactique :** Le vent et le givre éteignent vos **Feintes Élémentaires de Feu** (perte de 50% de dégâts), mais doublent la durée de congélation de vos flèches de Glace en vue FPS. Le joueur doit naviguer à l'aveugle en vue FPS pour repérer les balises lumineuses des abris.