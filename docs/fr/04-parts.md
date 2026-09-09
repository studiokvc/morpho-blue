# 4. Parts, actifs virtuels et arrondis

SharesMathLib convertit les montants entre actifs et parts.
La conversion ajoute 1 actif virtuel et 1 000 000 de parts virtuelles.
Ces valeurs fixent le rapport initial et atténuent certaines manipulations du prix des parts.
Elles ne représentent pas un dépôt récupérable par un utilisateur.
Les variantes Up et Down rendent le sens de l’arrondi explicite.
Comparer un nombre de parts de dette à un nombre de tokens sans conversion est incorrect.

Source : [code du dépôt](../../src/libraries/SharesMathLib.sol).

Suite : [Déposer et retirer la liquidité](05-preter.md).
