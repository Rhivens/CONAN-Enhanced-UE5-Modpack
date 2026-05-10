# 04 - Architecture du modpack

## Objectif

Définir une structure claire pour reconstruire le modpack Conan Exiles Enhanced / UE5 sans reprendre brutalement l'ancienne modlist UE4.

## Structure validée

1. Core / Frameworks
2. Interface & QoL
3. Construction / Building
4. Décoration / Placeables
5. Navigation / Carte / Exploration
6. Gameplay léger
7. Compagnons / Thralls / Animaux
8. Cosmétique personnage
9. Armures / vêtements
10. Ambiance visuelle / météo / lumière
11. Administration / host local
12. Mods à surveiller / différés

## Philosophie

La structure doit permettre :

- une installation progressive ;
- des tests par petits blocs ;
- une identification rapide des problèmes ;
- une documentation claire des décisions ;
- une séparation entre mods validés, mods rejetés et mods différés.

## Ordre conseillé de travail

1. Interface & QoL.
2. Building et décoration.
3. Navigation et exploration.
4. Gameplay léger.
5. Thralls, compagnons et animaux.
6. Cosmétiques et armures.
7. Ambiance visuelle.
8. Administration et host local.
9. Tests multijoueur intermédiaires.

## Statut

**Architecture validée.**
