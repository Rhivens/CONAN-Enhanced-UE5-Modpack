# 00 - Résumé de l'état actuel

## Projet

Construction progressive d'un modpack pour **Conan Exiles Enhanced / UE5**.

## Objectif final

Obtenir un modpack stable, propre et agréable à jouer en **host local privé** pour un groupe de **3 à 4 joueurs**.

## État validé

### Base propre

- Tous les anciens abonnements Workshop Conan Exiles ont été supprimés.
- Objectif : repartir d'une base vanilla UE5 propre, sans pollution héritée de l'ancienne version UE4.
- ReShade n'est pas réinstallé pour le moment.
- L'ancien fichier Better Graphics Settings UE4 n'est pas réutilisé tel quel.

### Ancienne modlist UE4

L'ancienne modlist UE4 a été analysée.

Conclusion :

- bonne philosophie générale ;
- besoins utiles conservés comme référence ;
- pas de reprise directe sur Enhanced / UE5 ;
- reconstruction propre nécessaire.

### Base vanilla UE5

- Lancement du jeu validé.
- Base propre fonctionnelle.
- Host local solo testé pendant environ 30 minutes sans problème.

### Graphismes et performances

Réglages testés :

- résolution : 1920x1080 ;
- preset Ultra ;
- DLSS Qualité ;
- génération d'images DLSS activée ;
- Nvidia Reflex activé ;
- Lumen Ultra ;
- ombres, textures, feuillages et effets en Ultra ;
- gamma ajusté à 1.8.

Résultat :

- jeu fluide ;
- image propre ;
- ombres satisfaisantes ;
- végétation au loin correcte ;
- 90 FPS capés volontairement ;
- aucun stutter constaté ;
- températures normales.

### Hébergement

- PC hôte : i9, 64 Go RAM, RTX 4070 12 Go.
- Connexion : Free 8 Gb/s stable.
- Historique d'hébergement : parties coop/multi régulières, jusqu'à 7 joueurs sur Windrose.
- Objectif Conan : 3 à 4 joueurs.

## Statut du test multijoueur Conan UE5

Le test multijoueur réel avec un ami est actuellement différé faute de joueur disponible.

Il n'est pas bloquant grâce aux éléments suivants :

- host local solo Conan UE5 validé ;
- ancien historique Conan UE4 en hébergement local ;
- connexion Internet très solide ;
- expérience récente d'hébergement jusqu'à 7 joueurs sur Windrose ;
- objectif Conan limité à 3 ou 4 joueurs.

## Prochaine phase

Définir et remplir progressivement l'architecture du modpack, en commençant par les catégories les moins risquées : interface, QoL, puis building et décoration.
