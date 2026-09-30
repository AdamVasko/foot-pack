# Foot Pack

Jeu de collection et de progression par clic : 96 vrais joueurs photographiés, six raretés, neuf packs, index et événements d'évolution. Notes et raretés conçues uniquement pour ce jeu. Aucune affiliation à EA, FIFA ou aux joueurs.

## Jouer

Servir ce dossier avec un serveur HTTP statique puis ouvrir `index.html`. Aucun outil de compilation ni dépendance. Les photos sont fournies localement ; les polices Google sont facultatives.

- Départ identique : Scott Carson bronze 40 GEN, zéro pièce, une carte et zéro amélioration. 1 pièce par clic.
- Aide affichée au premier lancement, accessible avec « Comment jouer ».
- Dix clics rapides activent un bonus +25 %, arrondi au supérieur. Aucun auto-click ni revenu hors ligne.
- Packs : bronze (150), argent (1 500), or (6 500), rare (15 000), épique (45 000), légendaire (160 000), rainbow (500 000), all-star (90 000), ultime (1 500 000). Trois cartes par pack. Prix, probabilités et conditions de déblocage visibles.
- Argent garanti tous les 20 packs bronze ; or garanti tous les 15 packs argent ; épique garanti après 40 packs or ou supérieurs sans épique. Le bronze n'alimente jamais cette dernière garantie.
- Doublons : +2 % de puissance, maximum +20 %. Meilleure carte sélectionnée pour les clics. Revenus liés à la note plutôt qu'à un multiplicateur exponentiel de rareté.
- Améliorations de clic, entraînements, sponsors et quatre défis.
- Équipe personnalisable de onze cartes, sans doublon. Emplacements vides comptés à zéro dans la note.
- Draft débloquée après 30 packs et 1 500 clics. Ticket : 2 000 pièces. Onze choix, trois matchs, 300 à 2 400 pièces, 2 à 8 jetons et une carte bronze, argent ou or. Tactiques en opposition et note influencent les chances. Récompense unique.
- Index de tous les joueurs : recherche, rareté, obtenus/manquants et pagination.
- Trois événements tournants par semaine (lundi, heure de Paris). Objectifs récompensés en jetons une seule fois par objectif et semaine active. Les jetons restent disponibles entre les semaines.
- Évolution d'une carte bronze, argent ou or : inscription de 20 jetons et 5 000 pièces, puis 400 nouveaux clics, 6 nouveaux packs et 5 cartes alignées. +5 GEN permanent, jusqu'à trois évolutions par carte. La rareté monte quand un seuil de note est atteint. Abandon sans remboursement.

## Sauvegarde

Sauvegarde locale dans le navigateur sur l'appareil, clé `foot-pack-v2`, schéma 3. Pièces, cartes, équipe et progression sont conservées lors de la migration du schéma 2. Les niveaux d'amélioration sont limités aux nouveaux plafonds ; une ancienne draft gratuite en cours est arrêtée. Jetons, événements et évolutions sont sauvegardés. Les anciennes parties de Pack ton paff restent sous leur ancienne clé.

Exporter et importer avec les boutons en bas de page pour transférer une partie. Une sauvegarde Foot Pack valide est requise. Effacer les données du navigateur efface la sauvegarde ; exporter avant. Chaque nouvel appareil ou navigateur commence une nouvelle partie.

## Photos

Voir [PHOTO-CREDITS.md](PHOTO-CREDITS.md) et `photo-credits.json` pour les auteurs, sources et licences des 96 photographies Wikimedia Commons. Photos affichées recadrées par CSS. Fond de stade créé avec ImageGen.

## GitHub Pages

Publier le contenu du dossier à la racine d'un dépôt puis activer GitHub Pages sur `main`. Les fichiers sont statiques et sans secrets.
