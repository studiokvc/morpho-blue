# 11. Callbacks et flash loans

Les callbacks permettent de composer les opérations avec un autre contrat.
Le callback supply est optionnel et précède le prélèvement des actifs.
flashLoan transfère les tokens, appelle onMorphoFlashLoan puis récupère le même montant.
Cette fonction ne calcule pas de commission de flash loan.
Le contrat appelant doit autoriser le prélèvement de retour et terminer dans la même transaction.
Un échec annule les écritures et transferts de cette transaction.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Limites du parcours](12-limites.md).
