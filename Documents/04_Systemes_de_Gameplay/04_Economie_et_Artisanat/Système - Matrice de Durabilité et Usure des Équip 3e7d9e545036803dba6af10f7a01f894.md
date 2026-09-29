# Système - Matrice de Durabilité et Usure des Équipements

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# ⚒️ Système - Matrice de Durabilité & Usure des Équipements

Ce document technique définit les règles d'usure des armes et armures. La durabilité influence directement les statistiques de combat (Dégâts, Posture, Protection) et interagit avec la météo, les feintes élémentaires et le métier de Forge.

---

## 📉 1. Les 3 États de Dégradation des Équipements

Chaque pièce d'équipement possède une jauge de durabilité (allant de 0 à 100 points). L'usure n'entraîne pas la destruction magique ou la disparition de l'objet, mais modifie ses propriétés physiques à travers 3 paliers distincts :

[100 - 51] ─────────────── [50 - 11] ─────────────── [10 - 0]Intact                     Ébréché / Abîmé           Émoussé / Brisé(Stats 100%)               (Stats -25%)              (Friction AAA / Risque)

1. **⚔️ [100 à 51] : Équipement Intact**
    - *Effet :* Toutes les statistiques physiques et magiques sont à 100%. Les multiplicateurs de *Feintes Élémentaires* (Page 9) fonctionnent à leur plein potentiel.
2. **⚠️ [50 à 11] : Équipement Ébréché (Armes) / Abîmé (Armures)**
    - *Effet :* Les dégâts de l'arme ou l'indice de protection de l'armure baissent de **25%**.
    - *Friction :* La consommation d'Endurance (🟢) augmente de 15% pour compenser la perte d'équilibre de l'objet.
3. **❌ [10 à 0] : Équipement Émoussé (Armes) / Brisé (Armures)**
    - *Effet Arme :* L'arme n'inflige plus aucun dégât de bris de posture. Si le joueur tente une parade parfaite (`L1` / `Clic Droit`) avec une arme à 0 de durabilité, l'impact le fait tressaillir (Stagger), le laissant sans défense.
    - *Effet Armure :* La défense physique tombe à zéro. Le héros subit l'intégralité des saignements et des attaques lourdes des meutes de prédateurs (Page 15).

---

## 🧠 2. Les Facteurs Systémiques d'Usure (Pratique +++)

La perte de points de durabilité dépend exclusivement de la qualité de vos actions de jeu et des environnements traversés.

### A. La Physique de l'Impact

- **La Parade Réussie vs Ratée :** Réussir une parade parfaite ne consomme que 0,5 point de durabilité sur votre bouclier ou votre lame. En revanche, bloquer une attaque lourde de *Goliath de Soufre* (Page 14) avec un mauvais timing (parade simple) arrache instantanément **15 points de durabilité** à votre arme.
- **L'Impact sur les Structures :** Frapper les armures de fer de l'Ordre ou les peaux de pierre des Abominations Magiques (Page 15) sans utiliser de *Feinte Élémentaire* émousse vos lames deux fois plus vite que de frapper du petit gibier.

### B. La Surchauffe Moléculaire des Feintes Élémentaires

Utiliser la magie brute de Malak-Gath directement dans l'acier sans catalyseur adapté génère un stress thermique violent (Page 32) :

- *Le Choc Thermique Volontaire :* Enchaîner une feinte de *Glace* immédiatement suivie d'une feinte de *Feu* sur la même lame applique le **Choc Thermique sur l'arme elle-même**. Elle inflige des dégâts monstrueux au monstre, mais perd **10 points de durabilité d'un coup** à cause de la micro-fissuration du métal.

### C. La Corrosivité des Biomes et de la Météo (Page 26)

- *La Pluie Battante (Forêt) :* Si le joueur court ou combat sous l'orage avec des armures de fer classiques, l'oxydation s'active. L'équipement perd passivement 1 point de durabilité toutes les 5 minutes, sauf s'il est protégé par une huile alchimique imperméable.
- *La Tempête de Sable (Canyons) :* La poussière de soufre et le sable s'infiltrent dans les articulations des armures lourdes, augmentant l'usure de protection lors des roulades et des esquives.

---

## 🛠️ 3. L'Entretien et la Boucle du Métier de Forge

Pour réparer ses équipements, le joueur doit s'investir dans le **Guide Complet des Métiers** (Page 24). Il ne suffit pas d'appuyer sur un bouton de menu.

- **Le Repos au Feu de Camp (La Forge de Fortune) :** Le joueur s'assoit au feu de camp (Page 20). S'il possède le niveau requis en métier de Forge, il peut dépenser des lingots de fer ou des clous pour réparer son arme à l'aide d'une meule ou d'un marteau de voyage.
- **Le Verrouillage par le Niveau d'Objet :** Impossible de réparer une armure expérimentale de niveau 60 si votre niveau de métier de Forge est seulement au niveau 20. Vous devrez confier votre équipement légendaire à un **Maître Forgeron** dans la Capitale et payer une somme astronomique en pièces du Cartel (Page 23).

---

## 👥 4. Coopération Asynchrone : Le Sabotage d'Acier

En mode Coop, la durabilité devient un outil de négociation ou de trahison silencieuse.

- **Le Sabotage d'Enclume :** Si le **Joueur 1** (Parrain du Cartel) veut ralentir le **Joueur 2** (Fidèle à l'Ordre) avant une quête de traque (Page 30), il peut profiter d'une phase de repos au feu de camp pour interagir avec l'enclume de son compagnon. En utilisant sa compétence de *Sabotage (Branche 4)*, il applique une micro-fissure invisible sur l'épée du Joueur 2.
- **La Rupture en plein Vol :** Lors du combat suivant face à un *Monstre Unique prédictif*, au premier choc lourd, l'arme du Joueur 2 va perdre 50 points de durabilité d'un coup et passer à l'état `Émoussé`, le laissant désarmé au milieu de l'arène. Malak-Gath ricanera dans la tête du Joueur 1 : *"Regarde sa lame se briser... Il est sans défense. C'est le moment de lui planter ton surin dans le dos et de toucher la prime."*