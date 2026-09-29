# Système - Navigation et Voyages Rapides Diégétiques

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 🗺️ Système - Navigation & Voyages Rapides Diégétiques

Ce document technique définit les mécaniques de déplacement rapide et de téléportation à travers le monde ouvert. Aucun voyage rapide n'est passif : ils exigent des ressources diégétiques, dépendent de vos alliances de factions et réagissent aux conditions climatiques.

---

## 🔮 1. Les Relais de Stase du Conclave (La Téléportation Magique)

*Focus : Déplacement instantané de haute technologie magique.*

- **Le Lore :** À travers les 5 biomes, le **Conclave du Voile** (Page 44) a implanté des monolithes de stase capables de dématérialiser la matière pour la projeter à travers les flux du Vide.
- **La Friction Mécanique (Le Coût en Mana) :** Utiliser un Relais de Stase consomme instantanément 100% de la jauge de Mana (🔵) du joueur. Le héros réapparaît à destination épuisé magiquement, sa jauge vide, le rendant vulnérable si la zone d'arrivée est hostile.
- **Le Verrouillage par le Syndrome (Stade 3) :** Si le joueur a atteint le **Stade 3 des Symptômes** (L'Illusion Physique de Malak-Gath, Page 36), sa surtension de magie noire fait grésiller le Relais. L'activation de la téléportation a 15% de chances de saturer la grille et de provoquer un crash spatial, réveillant le joueur amnésique au milieu d'un donjon inconnu au lieu de sa destination prévue.

---

## 📦 2. Les Caravanes de la Brume (Le Voyage Sécurisé du Cartel)

*Focus : Déplacement passif, économique et sécurisé pour les criminels.*

- **Le Lore :** Aux abords des tavernes et des bas-fonds (Page 23), le **Cartel de la Brume** gère un réseau de chariots cachés sous des cargaisons de marchandises.
- **Le Coût Financier :** Le voyage rapide est payant en pièces d'or. Le prix fluctue selon la **Loi de Rareté Régionale** et le niveau de votre **Jauge d'Infamie Criminelle** (Page 40). Un *Parrain de la Brume* voyage gratuitement, tandis qu'un *Voleur de Bas Étage* subit une lourde taxe de transport.
- **L'Avantage Coopératif (Le Voyage de Groupe) :** C'est le seul moyen en **Coopération Asynchrone** (Page 11) de déplacer tout le groupe simultanément vers un biome éloigné. Les joueurs s'installent à l'arrière du chariot, déclenchant une phase de dialogue contextuelle où ils peuvent s'échanger des composants de craft ou des plans de forge.

---

## 🚫 3. L'Impact de la Météo Dynamique et des Décrets sur le Voyage

Le voyage rapide n'est pas un droit acquis, c'est une opportunité climatique et politique que le monde ouvert peut vous retirer à tout moment.

### A. Les Blocs Climatiques (La Météo Punitive — Page 26)

- **Pendant une Tempête de Neige (Pics Célestes) :** L'alignement des flux magiques est rompu par le blizzard. Tous les Relais de Stase du Conclave de la région montagnarde se verrouillent automatiquement. Le message système s'affiche : **"Interférences climatiques : Flux du Vide instables."**
- **Pendant une Tempête de Sable (Canyons) :** Les Caravanes de la Brume refusent de prendre la route. Les conducteurs de chariots s'enferment dans les tavernes pour attendre la fin de la tempête, forçant le joueur à utiliser ses **Montures Évolutives** (Page 25) comme le *Lion des Canyons* pour franchir la zone par ses propres moyens.

### B. Le Blocus des Factions (La Prime de Recherche — Page 30)

- **Si votre statut est "Traqué" par L'Ordre du Sceptre d'Or :** Les routes principales reliant les grandes villes sont coupées par des checkpoints militaires suite au *Décret de Loi Martiale* (Page 18). Si vous tentez d'utiliser une Caravane du Cartel pour franchir une frontière vers la Capitale, l'IA collective des gardes va intercepter le chariot. Une cinématique de transition s'interrompt brutalement : le chariot est fouillé, le combat s'engage en direct sur la route, et en cas de défaite, vous subissez le **Système d'Arrestation par Faction** (Page 33).

---

## 👥 4. Décalage de Voyage en Mode Coopération Asynchrone

Le voyage rapide respecte l'indépendance de chaque Player ID en session multijoueur.

- **Le Voyage Individuel :** Le **Joueur 1** peut décider de dépenser son mana pour utiliser un Relais de Stase et se téléporter instantanément à la Capitale pour forger une arme de niveau 99 (Page 35). Le **Joueur 2** peut choisir de rester dans la forêt sauvage pour continuer à chasser le gibier avec son *Loup Nommé* (Page 22). Le streaming continu du moteur de jeu AAA gère la distance entre les deux joueurs sans jamais forcer de téléportation automatique de regroupement.
- **Le Mouchardage de Frontière :** Si le Joueur 1 (Traqué par l'Ordre) tente de prendre un relais magique près d'une garnison, l'IA collective des mages connectés au réseau (Page 44) va moucharder au Joueur 2 situé à l'autre bout de la carte : *"Votre associé [Joueur 1] vient de saturer un de nos monolithes avec sa magie noire. Nos sentinelles l'ont localisé. Rompez votre alliance avec lui avant que le Conclave ne condamne votre accès au réseau."*