# World Design - Le Biome de l'Ouest : Les Canyons de la Brume

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🗺️ World Design - Le Biome de l'Ouest : Les Canyons de la Brume

Ce document technique et narratif cartographie la région aride de La Faille. C'est un biome profondément labyrinthique, minéral et vertical, conçu pour mettre à l'épreuve le Système de Criminalité Avancée, les montures agiles et le combat face aux Boss de Lave.

---

## ⛰️ 1. Structure Géologique & Labyrinthe Vertical (Level Design AAA)

Les Canyons de la Brume rejettent la progression horizontale classique. La zone est fracturée en gigantesques crevasses rocheuses, forçant le joueur à exploiter la verticalité et la gestion de son Endurance (🟢) sous peine de chute mortelle (Page 43).

- **Le Fond des Failles (Les Terres Rouges) :** Un défilé de pierre ocre et de poussière brûlante. C'est le lit des rivières de soufre et l'emplacement des filons de métaux lourds. La visibilité y est souvent compromise par la chaleur et le vent.
- **Les Parois Troglodytes (Le Hub Commercial) :** Les falaises sont creusées de galeries, de structures en bois suspendues et d'ascenseurs à contrepoids gérés par le Cartel. Le joueur doit y progresser prudemment à dos de *Lion des Canyons* (Page 25) capable de sauter par-dessus les failles.
- **Les Hauteurs (Les Postes de Péage) :** Les sommets des canyons abritent les forteresses de l'Ordre et les garnisons avancées du Cartel. C'est de là-haut que les éclaireurs ennemis tirent en hauteur, obligeant le joueur à basculer en **Vue FPS** pour répliquer chirurgicalement.

---

## 📍 2. Les Points d'Intérêt Majeurs (POI de l'Ouest)

La région de La Faille est découpée en 4 secteurs d'influence géopolitique majeurs :

### 📦 POI A : Le Hameau de La Faille (Hub du Cartel)

- **Démographie :** 300 habitants (IA Collective de Village Moyen, Page 13).
- **Lore :** Le paradis des contrebandiers. Une ville troglodyte construite à flanc de falaise, abritant des tavernes clandestines et des marchés noirs.
- **Utilité :** Centre névralgique pour augmenter votre **Jauge d'Infamie Criminelle (Page 40)**. C'est ici que le joueur s'adresse au Baron local pour manipuler l'économie régionale.

### ⛏️ POI B : Les Veines de Soufre (La Mine Majeure)

- **Lore :** Un immense complexe d'extraction à ciel ouvert exploité de force par le Cartel.
- **Utilité :** Zone de farm essentielle pour le métier de **Minage et de Forge (Niveaux 30 à 69, Page 39)**. C'est ici que se cache *Brutus le Brisé*, le Maître Enseignant de minage. En cas de capture par le Cartel, vous y subissez le **Système de Travail Forcé (Page 37)**.

### 🕳️ POI C : Les Fouilles Interdites (Le Camp des Murmures)

- **Lore :** Un site de ruines antiques excavé en secret par la faction mineure des **Anciens Murmures du Passé**.
- **Mécanique :** Les archéologues éco-terroristes vous proposent des quêtes de sabotage pour détruire les forages technologiques du Conclave du Voile qui déstabilisent les plaques tectoniques du canyon.

### 🛡️ POI D : Le Checkpoint du Prévôt

- **Lore :** Une forteresse impériale massive verrouillant le pont suspendu menant vers le Quartier Ouest de la Capitale.
- **Utilité :** Si le *Décret de Loi Martiale (Page 18)* est actif, ce poste de garde déploie des patrouilles lourdes à l'IA de Phalange Royale. Le Panneau de Primes (Page 30) local propose des contrats de traque à prix d'or.

---

## 👑 3. Algorithme des 3 Boss Flottants des Canyons

Respectant scrupuleusement la grille de non-chevauchement (Page 48), l'Ouest possède 15 nœuds de spawn rocheux et souterrains. Au chargement de la région, l'algorithme y injecte aléatoirement 3 Boss Alphas :

1. **Le Goliath de Soufre (L'Abomination de Pierre) :** Le premier grand Boss Régional à l'IA Absorbante (Page 14). Il déploie des charges similaires aux sangliers géants et une armure de plaques de pierre ultra-lourde. Le joueur doit utiliser le combo secret **Choc Thermique** pour briser son bouclier.
2. **Le Scion du Néant (IA Prédictive Aléatoire) :** Une apparition de l'Ignis Originel (Le Phénix, Page 34) qui feinte ses animations pour briser vos timings de parade parfaite à la manette ou au clavier.
3. **Le Basilic des Sables :** Une créature reptilienne géante camouflée dans la poussière. Ses attaques crachent du soufre corrosif qui réduit instantanément la durabilité de votre armure de 20 points (Page 41).

---

## ⛈️ 4. Réaction Climatique Spécifique (La Tempête de Sable)

Lorsque la météo de la **Tempête de Sable** s'active sur les Canyons de l'Ouest :

- La visibilité générale à l'écran tombe à **50%** (brume orange opaque).
- Le vent violent dévie les flèches en vue FPS et applique un malus de friction sur la visée de précision.
- **L'Opportunité Furtive :** Les particules de poussière bloquent la lumière et réduisent le cône de détection de l'IA collective des gardes de moitié. C'est le moment idéal pour utiliser la `Branche 2 (Camouflage)` et saboter les coffres de saisie du Cartel ou crocheter les cellules de la prison sans déclencher l'alarme de ruche.