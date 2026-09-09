# 6. Garantie, emprunt et remboursement

supplyCollateral immobilise des tokens de garantie sans les prêter aux autres comptes.
borrow augmente les parts de dette, puis contrôle la santé et la liquidité du marché.
Le montant empruntable dépend du prix de l’oracle multiplié par le LLTV.
withdrawCollateral refait ce contrôle après la réduction de garantie.
repay réduit les parts de dette et prélève les tokens de remboursement.
Rembourser toutes les parts évite de laisser une dette résiduelle due aux intérêts.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Actualisation des intérêts](07-interets.md).
