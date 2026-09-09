# 7. Actualisation des intérêts

Les intérêts sont comptabilisés lors d’une interaction ou d’un appel à accrueInterest.
_accrueInterest mesure le temps écoulé depuis lastUpdate.
Il demande le taux à l’IRM puis utilise une approximation de capitalisation.
Le même intérêt augmente totalBorrowAssets et totalSupplyAssets.
Les parts ordinaires restent constantes ; leur valeur en actifs change.
Un IRM nul ne produit pas d’intérêts dans cette branche du code.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Frais du protocole](08-frais.md).
