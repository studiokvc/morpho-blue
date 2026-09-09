# 8. Frais du protocole

Le propriétaire peut définir un pourcentage de frais dans la limite MAX_FEE.
setFee comptabilise d’abord les intérêts au précédent taux de frais.
À l’actualisation, une fraction des intérêts est convertie en parts de prêt.
Ces parts sont créditées au feeRecipient.
Ce mécanisme partage le rendement en diluant la participation des autres prêteurs.
Les frais ne sont pas un prélèvement direct de garantie sur chaque emprunteur.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Liquidation et dette irrécouvrable](09-liquidation.md).
