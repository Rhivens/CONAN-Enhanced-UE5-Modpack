# CONAN Enhanced UE5 Modpack

Documentation de construction progressive d'un modpack pour **Conan Exiles Enhanced / UE5**.

## Objectif

Construire un modpack propre, stable et cohérent pour une utilisation en **host local privé**, principalement pour un groupe de **3 à 4 joueurs**.

Le projet repart d'une base vanilla UE5 propre, sans reprise brute de l'ancienne modlist UE4.

## Philosophie du modpack

- stabilité avant quantité de mods ;
- progression étape par étape ;
- tests réguliers avant ajout de nouveaux blocs ;
- confort de jeu, qualité de vie et interface améliorée ;
- construction et décoration enrichies ;
- gameplay légèrement amélioré, sans transformer le jeu en usine à gaz ;
- compatibilité Conan Exiles Enhanced / UE5 prioritaire.

## Contexte matériel

- PC hôte principal : i9, 64 Go RAM, RTX 4070 12 Go ;
- résolution utilisée : 1920x1080 ;
- connexion Internet : Free 8 Gb/s stable ;
- historique d'hébergement : parties coop/multi régulières, jusqu'à 7 joueurs sur Windrose ;
- objectif Conan : 3 à 4 joueurs.

## État actuel

- base vanilla UE5 propre : validée ;
- anciens abonnements Workshop supprimés ;
- ancienne modlist UE4 analysée, mais non reprise telle quelle ;
- ancien fichier Better Graphics UE4 analysé, mais non réutilisé ;
- ReShade non réinstallé pour l'instant ;
- réglages graphiques UE5 testés en Ultra avec DLSS Qualité, Frame Generation et Nvidia Reflex ;
- gamma ajusté à 1.8 ;
- performances validées à 90 FPS capés ;
- host local solo validé ;
- test multijoueur réel Conan UE5 différé, mais non bloquant.

## Structure documentaire

Les fichiers principaux sont dans `docs/`.

Les notes d'analyse, anciennes références et éléments à surveiller sont dans `notes/`.

## Règle de travail

Chaque ajout de mod ou bloc de mods devra être documenté, testé et validé avant de passer à la suite.

Le barbare peut manier la hache, mais le moddeur, lui, garde un changelog.
