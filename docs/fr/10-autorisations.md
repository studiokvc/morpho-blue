# 10. Délégation et signatures

setAuthorization permet à un compte de déléguer la gestion de ses positions.
Cette autorisation vaut pour ce couple de comptes, sans être limitée à un seul marché.
La variante signée contrôle une deadline, un nonce et un domaine EIP-712.
Les opérations qui retirent des actifs ou créent une dette vérifient le délégataire.
Une autorisation Morpho est distincte de l’allowance permettant de prélever des ERC-20.
Révoquer une délégation ne rembourse pas les dettes déjà ouvertes.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Callbacks et flash loans](11-callbacks.md).
