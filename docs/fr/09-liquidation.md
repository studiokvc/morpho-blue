# 9. Liquidation et dette irrécouvrable

liquidate exige que la position ne respecte plus son seuil de santé.
Le liquidateur rembourse de la dette et reçoit une quantité de garantie avec une incitation bornée.
Il spécifie soit les actifs saisis, soit les parts remboursées.
La garantie est transférée avant le callback éventuel et le prélèvement du remboursement.
Si toute la garantie disparaît, la dette restante est déduite des actifs prêtés du marché.
L’isolation limite cette comptabilisation au marché concerné ; elle ne supprime pas la perte des prêteurs.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Délégation et signatures](10-autorisations.md).
