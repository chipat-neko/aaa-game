# Le Système d'Interface des Quêtes

Type: Draft
État: Pas commencé
Projet: Création de jeux video AAA (https://app.notion.com/p/Cr-ation-de-jeux-video-AAA-134ac8b42ba84956ba0e23244229789c?pvs=21)

# 📜 Système - Interface du Journal de Quêtes Diégétique

Ce document technique définit l'ergonomie, la structure visuelle et la logique de tri du Journal de Quêtes à l'écran. L'interface rejette les menus modernes rigides et s'affiche sous la forme d'un carnet de notes de cuir et de parchemin écrit à la main, s'adaptant dynamiquement à l'état mental du héros et au mode Coop.

---

## 🎨 1. Esthétique AAA et Parité d'Accès (Layout de l'UI)

L'ouverture du journal se fait par la touche `Tactile/Options` à la manette ou la touche `J` au clavier. Le jeu passe en pause en mode Solo, mais le temps continue de s'écouler en temps réel en mode Coopération Asynchrone.

- **Le Rendu Visuel :** Le journal se présente sous la forme des pages gauches de votre carte en parchemin (Page 45). Les textes sont rédigés à la main à l'encre noire. L'écriture change selon le profil du héros : si le joueur a un haut niveau en `Branche 10` (Diplomatie), l'écriture est soignée et calligraphiée. Si sa *Jauge de Synchronicité* est au maximum, l'écriture devient nerveuse, tremblée, tachée de sang noir.
- **La Navigation Fluide :**
    - *À la manette :* Navigation par onglets horizontaux via `L1/R1` et défilement vertical via le stick gauche.
    - *Au clavier/souris :* Clic direct sur les intercalaires en parchemin ou défilement à la molette.

---

## 🗂️ 2. L'Architecture du Tri : Les 4 Intercalaires de Quêtes

Le journal sépare strictement les quêtes pour permettre au joueur de gérer ses priorités géopolitiques sans surcharge d'informations.

### ⚔️ Onglet I : Les Chroniques d'Alistair (Trame Principale)

- *Contenu :* Les 7 quêtes principales (du Didacticiel jusqu'au Climax de la Tour, Page 35).
- *Mécanique :* Cet onglet affiche également la **Jauge de Synchronicité** cachée et le Stade actuel des Symptômes sous forme de croquis anatomiques du héros qui se corrompt.

### 📜 Onglet II : Les Rumeurs des Biomes (Quêtes Secondaires de Zone)

- *Contenu :* Les quêtes de subsistance et les conflits locaux des 5 biomes (Page 19).
- *Le Suivi du Statut :* Si une quête secondaire est en cours et que le joueur subit une **Mort Punitive** (Page 20), la ligne de texte de la quête est barrée d'un trait rouge à l'écran avec la mention écrite à la main : `[ÉCHEC - Le temps a manqué]`.

### ⚡ Onglet III : Les Décrets et Quêtes ++ (Les Mutations Mondiales)

- *Contenu :* Cet onglet s'allume en doré uniquement après la signature d'un décret au Château (Page 18). Il liste les **Quêtes ++** générées à l'extérieur.
- *Mécanique :* Chaque quête ++ active affiche le blason de la Faction Majeure qui a émis le décret (L'Ordre, Le Conclave, Le Cartel) et applique un indicateur visuel sur les régions précédentes qui ont muté.

### 🎯 Onglet IV : Les Avis de Traque (Panneaux de Primes & Contrats corrompus)

- *Contenu :* Les contrats "Mort ou Vif" acceptés dans les postes de garde (Page 30).
- *L'Option Double-Jeu :* Si le joueur a accepté une **Sur-Quête de Corruption** (tuer au lieu de capturer vivant pour doubler l'or), le texte de la sur-quête est griffonné à l'encre rouge dans la marge de la page, masqué aux yeux des PNJ officiels.

---

## 🧠 3. La Corruption de l'Interface par Malak-Gath

Fidèle au ton psychologique mature de votre GDD, l'interface du journal subit les hallucinations du **Stade 3 des Symptômes** (Page 36) [health].

- **Les Annotations du Démon :** Lorsque le joueur ouvre son journal au Stade 3, la voix en audio 3D de Malak-Gath ricane. De nouvelles lignes de texte écrites dans une encre noire luisante et mouvante (le Vide) apparaissent par-dessus vos objectifs humains.
- *Exemple visuel :* Si l'objectif officiel de la quête secondaire est : `[Sauver la fille du trappeur des griffes du loup]`, le texte démoniaque se superpose et affiche : `[Laisse le loup la dévorer. Son sang nourrira notre puissance.]`. Si le joueur obéit aux notes de Malak-Gath, la quête humaine échoue mais il valide un objectif caché de corruption débloquant un Ultime magique (Page 15).

---

## 👥 4. Le Suivi Coopératif Asynchrone (Le Journal Partagé)

En mode multijoueur (2 à 4 joueurs), le journal gère le décalage d'objectifs de manière asymétrique (Page 11).

- **Les Objectifs Individualisés (Player ID) :** Le journal affiche deux colonnes ou deux pages distinctes s'il y a deux joueurs.
    - La page gauche affiche les objectifs du **Joueur 1**.
    - La page droite affiche les objectifs du **Joueur 2**.
- **Le Suivi des Trahisons :** Si le Joueur 2 accepte un contrat de traque secret sur la tête du Joueur 1 (Page 30), cet objectif s'affiche uniquement sur l'écran du Joueur 2. Sur l'écran du Joueur 1, le journal affiche une alerte mystique de Malak-Gath sous forme de brûlure sur le parchemin : `[Attention... Ton compagnon de route regarde ton cou.]`.