# 06 - Mods Building & Décoration

## Objectif

Documenter les mods liés à la construction, aux pièces de bâtiment, aux décorations et aux placeables.

## Statut

**En cours.**

Packs Building & Décoration actuellement validés :

- **Étape 10.8 - Pack visuel / déco / building léger** ;
- **Étape 10.13 - Pack building / décoration avancée**.

Attention : **Lisas Building Stone Age est rejeté définitivement** après apparition d'une erreur de parsing du fichier `.pak` et affichage explicite en `<corrupted>` dans le menu Mods.

## Critères de sélection

Les mods de cette catégorie devront :

- être compatibles Conan Exiles Enhanced / UE5 ;
- ne pas provoquer d'instabilité en host local / mode Coop ;
- éviter les empilements massifs de dépendances ;
- apporter un vrai intérêt en construction ou décoration ;
- rester raisonnables pour un groupe de 3 à 4 joueurs ;
- être suffisamment stables pour ne pas risquer de casser la modlist.

## Mods candidats

À compléter.

## Mods validés

### Panda's Bloody Mess

- Catégorie : visuel / ambiance gore.
- Source : Steam Workshop.
- Workshop ID : `3723576515`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3723576515
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé dans le pack 10.8.
- Fonctionnement validé ingame.

---

### More Clan Emblems Enhanced

- Catégorie : clans / emblèmes / personnalisation.
- Source : Steam Workshop.
- Workshop ID : `3723546665`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3723546665
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé dans le pack 10.8.
- Fonctionnement validé ingame.

---

### SH - Decorations v1.0.0 (Enhanced)

- Catégorie : décoration / placeables.
- Source : Steam Workshop.
- Workshop ID : `3723606644`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3723606644
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé dans le pack 10.8.
- Objets de décoration visibles / testés.
- Fonctionnement validé ingame.

---

### Ancient Civilization - Enhanced

- Catégorie : building / décoration avancée.
- Source : Steam Workshop.
- Workshop ID : `3721996090`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3721996090
- Statut : **validé en mode Coop**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en mode Coop dans le pack 10.13.
- Pièces de construction testées.
- Jeu stable.
- Aucune erreur signalée.

#### Conclusion

**Ancient Civilization - Enhanced est validé pour le modpack.**

---

### Desert Town

- Catégorie : building / décoration avancée.
- Source : Steam Workshop.
- Workshop ID : `3721019326`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3721019326
- Statut : **validé en mode Coop**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en mode Coop dans le pack 10.13.
- Pièces de construction testées.
- Jeu stable.
- Aucune erreur signalée.

#### Conclusion

**Desert Town est validé pour le modpack.**

---

### Enhanced Builder 2026.5.9

- Catégorie : building / construction avancée.
- Source : Steam Workshop.
- Workshop ID : `3720763208`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3720763208
- Statut : **validé en mode Coop**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en mode Coop dans le pack 10.13.
- Pièces de construction testées.
- Jeu stable.
- Aucune erreur signalée.

#### Note mineure

Après ajout du pack 10.13, l'intro du jeu ne peut plus être passée au clic souris.

Cette anomalie est considérée comme **mineure et non bloquante**, car :

- le jeu reste stable ;
- aucun message d'erreur n'est signalé ;
- le gameplay n'est pas compromis ;
- les pièces de construction fonctionnent correctement.

#### Conclusion

**Enhanced Builder 2026.5.9 est validé pour le modpack.**

## Mods rejetés ou différés

### Lisas Building Stone Age

- Catégorie : building / pièces de construction.
- Source : Steam Workshop.
- Workshop ID : `3723560519`.
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3723560519
- Statut : **rejeté définitivement**.

#### Historique

Le mod avait été validé une première fois en jeu :

- pièces de construction visibles ;
- builds testés ;
- fonctionnement initial OK.

Cependant, lors d'un lancement ultérieur, Conan Exiles Enhanced a affiché une erreur :

```text
Corrupted Mods Detected
failed to parse mod info
Lisas_Building_Stone_Age.pak
```

Après désabonnement du mod, le jeu a réinitialisé la modlist.

Fabien a reconstruit et testé la base jusqu'au mod 22 : **tout est OK jusqu'au mod 22 sans Lisas Building Stone Age**.

Une nouvelle vérification dans le menu Mods a ensuite confirmé que le mod apparaît explicitement comme :

```text
<corrupted - Lisas_Building_Stone_Age.pak>
```

Le mod est en version bêta et venait juste d'être mis à jour.

#### Décision

Lisas Building Stone Age est exclu définitivement du modpack.

Raison : mod instable / fichier Workshop corrompu / risque trop élevé pour une base coop propre.

Il ne doit plus être proposé dans les packs de test futurs, sauf changement majeur et nouvelle version stable explicitement confirmée.

---

### Pickup+

Statut : **différé**.

Raison : non visible via le filtre Workshop Enhanced au moment de la recherche.

### Less Building Placement Restrictions

Statut : **différé**.

Raison : non visible via le filtre Workshop Enhanced au moment de la recherche.

### LBPR - Additional Features

Statut : **différé**.

Raison : non visible via le filtre Workshop Enhanced au moment de la recherche.

## Notes de test

Le pack 10.8 a été testé une première fois avec succès.

Conclusion initiale : **test OK, builds OK**.

Conclusion après incident : **base validée jusqu'au mod 22 sans Lisas Building Stone Age**.

Conclusion finale : **Lisas Building Stone Age rejeté définitivement pour instabilité**.

Le pack 10.13 a été testé en mode Coop.

Conclusion pack 10.13 : **test validé, jeu stable, aucune erreur, pièces de construction testées et OK**.

Anomalie mineure observée après le pack 10.13 : **l'intro ne peut plus être passée au clic souris**. Non bloquant.
