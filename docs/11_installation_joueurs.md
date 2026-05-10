# 11 - Installation joueurs

## Objectif

Ce document explique comment installer le modpack Conan Exiles Enhanced / UE5 côté joueur.

Il est destiné aux amis qui veulent rejoindre la partie sans devoir gérer toute la partie technique du projet.

Objectifs :

- installer les bons mods ;
- respecter le bon ordre de chargement ;
- éviter les erreurs de connexion ;
- pouvoir rejoindre la partie hébergée par Fabien.

## Important avant de commencer

Le modpack est prévu pour **Conan Exiles Enhanced / UE5**.

Chaque joueur devra avoir :

- Conan Exiles installé via Steam ;
- le jeu lancé au moins une fois sans mod ;
- les mêmes mods que l'hôte ;
- le même ordre de chargement des mods.

Si les mods ne sont pas identiques, ou pas dans le même ordre, la connexion à la partie peut échouer.

## Étape 1 - Lancer Conan Exiles Enhanced une première fois

Avant d'installer les mods, lancer le jeu une première fois sans mod.

But :

- vérifier que le jeu démarre correctement ;
- laisser le jeu créer ses dossiers de configuration ;
- éviter de confondre un problème vanilla avec un problème de mod.

Une fois le menu principal atteint, quitter le jeu.

## Étape 2 - S'abonner aux mods Steam Workshop listés

La majorité des mods seront, si possible, pris depuis le Steam Workshop.

Pour chaque mod Workshop :

1. ouvrir le lien fourni dans la liste du modpack ;
2. cliquer sur **S'abonner** ;
3. laisser Steam télécharger le mod ;
4. attendre que tous les téléchargements soient terminés.

Ne pas lancer la partie tant que Steam télécharge encore des mods.

## Étape 3 - Télécharger les éventuels mods Nexus indiqués

Certains mods peuvent venir de Nexus Mods ou d'une autre source externe.

Dans ce cas, ils seront indiqués clairement dans la documentation.

Pour chaque mod Nexus :

1. ouvrir le lien fourni ;
2. télécharger la bonne version ;
3. vérifier qu'il s'agit bien de la version demandée ;
4. conserver le fichier téléchargé dans un endroit facile à retrouver.

Si aucun mod Nexus n'est utilisé, cette étape peut être ignorée.

## Étape 4 - Copier les fichiers .pak Nexus dans le dossier Mods

Les mods Conan externes sont généralement fournis sous forme de fichiers `.pak`.

Ils doivent être placés dans le dossier suivant :

```text
<SteamLibrary>\steamapps\common\Conan Exiles\ConanSandbox\Mods
```

Exemple courant :

```text
C:\Program Files (x86)\Steam\steamapps\common\Conan Exiles\ConanSandbox\Mods
```

Si le jeu est installé sur un autre disque, le chemin peut être différent.

Important :

- copier uniquement les fichiers `.pak` demandés ;
- ne pas renommer les fichiers `.pak` ;
- ne pas ajouter d'anciens mods personnels ;
- ne pas mélanger avec une ancienne installation modée.

## Étape 5 - Vérifier ou remplacer le fichier modlist.txt

Conan utilise un fichier appelé `modlist.txt` pour savoir quels mods charger et dans quel ordre.

Ce fichier se trouve normalement ici :

```text
<SteamLibrary>\steamapps\common\Conan Exiles\ConanSandbox\Mods\modlist.txt
```

La documentation du modpack fournira une version de référence du fichier `modlist.txt`.

Chaque joueur devra vérifier que son fichier correspond bien à la version indiquée.

Attention :

- l'ordre des lignes est important ;
- ne pas ajouter de mods personnels ;
- ne pas supprimer de ligne ;
- ne pas modifier le fichier au hasard.

## Étape 6 - Relancer le jeu

Une fois les mods installés et le fichier `modlist.txt` vérifié :

1. relancer Conan Exiles Enhanced ;
2. laisser le jeu charger les mods ;
3. vérifier qu'aucun message d'erreur bloquant n'apparaît ;
4. arriver au menu principal.

Si le jeu demande un redémarrage après activation des mods, accepter et relancer.

## Étape 7 - Rejoindre la partie

Quand tout est prêt :

1. lancer Conan Exiles Enhanced ;
2. aller dans le menu multijoueur ou coop selon la méthode utilisée ;
3. rejoindre la partie hébergée par Fabien ;
4. signaler immédiatement toute erreur de connexion ou tout message de mod manquant.

## En cas de problème

Vérifier dans cet ordre :

1. Steam a-t-il fini de télécharger tous les mods ?
2. Le joueur est-il bien abonné à tous les mods Workshop listés ?
3. Les fichiers `.pak` Nexus sont-ils bien dans `ConanSandbox\Mods` ?
4. Le fichier `modlist.txt` correspond-il à la version de référence ?
5. L'ordre des mods est-il identique ?
6. Le jeu a-t-il été relancé après installation des mods ?
7. Aucun ancien mod personnel ne traîne-t-il dans le dossier Mods ?

## Règle simple pour les joueurs

- Ne pas ajouter de mods personnels.
- Ne pas modifier l'ordre de chargement.
- Ne pas renommer les fichiers.
- Ne pas supprimer de ligne dans `modlist.txt`.
- En cas de doute, demander avant de modifier quelque chose.

## Statut

Document initial créé.

À compléter lorsque la liste réelle des mods sera validée.
