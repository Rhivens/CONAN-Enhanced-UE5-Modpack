# 05 - Mods Interface & QoL

## Objectif

Documenter les mods liés à l'interface, au confort de jeu et à la qualité de vie.

## Statut

**En cours.**

Premier mod Interface & QoL validé : **Simple Minimap (by Xevyr) v5.1.1**.

## Critères de sélection

Les mods de cette catégorie devront :

- être compatibles Conan Exiles Enhanced / UE5 ;
- améliorer le confort sans alourdir inutilement le jeu ;
- éviter les conflits avec les systèmes principaux ;
- être testés rapidement en solo puis, si possible, en host local.

## Mods candidats

À compléter.

## Mods validés

### Simple Minimap (by Xevyr) v5.1.1

- Catégorie : Interface & QoL.
- Source : Steam Workshop.
- Workshop ID : `3719513784`.
- Type : minimap légère et autonome.
- Statut : **validé en jeu**.

### Résultat du test

- Abonnement Steam Workshop effectué.
- Le fichier `.pak` est bien présent dans le dossier Workshop Steam :

```text
C:\JEUX\STEAM\steamapps\workshop\content\440900\3719513784
```

- Le mod n'apparaissait pas dans l'onglet Mods du launcher Funcom.
- Le mod apparaissait correctement dans le menu Mods directement en jeu.
- Le mod a été activé depuis le menu Mods en jeu.
- La minimap fonctionne correctement ingame.

### Conclusion

**Simple Minimap est validé comme premier mod du bloc Interface & QoL.**

Note importante : pour Conan Exiles Enhanced / UE5, le launcher Funcom peut ne pas afficher certains mods Workshop alors qu'ils apparaissent correctement dans le menu Mods du jeu. Pour la suite du projet, le menu Mods en jeu devient la référence principale de vérification.

## Mods rejetés ou différés

À compléter.

## Notes de test

### Règle découverte pendant le test

Le launcher Funcom n'est pas toujours fiable pour vérifier la présence des mods Workshop.

Méthode retenue :

1. vérifier l'abonnement Steam Workshop ;
2. vérifier si le fichier `.pak` existe dans le dossier Workshop ;
3. lancer le jeu ;
4. ouvrir le menu Mods depuis le jeu ;
5. activer le mod depuis ce menu ;
6. redémarrer si le jeu le demande ;
7. tester en host local solo.

Cette règle devra être prise en compte dans la procédure d'installation joueurs.
