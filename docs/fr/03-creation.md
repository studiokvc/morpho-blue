# 3. Créer un marché

Les paramètres comprennent loanToken, collateralToken, oracle, irm et lltv.
Leur identifiant est calculé à partir de cet ensemble.
createMarket exige un IRM et un LLTV préalablement autorisés.
La création elle-même est ouverte et refuse un identifiant déjà créé.
Le marché conserve ces paramètres ; changer l’oracle signifie choisir un autre marché.
L’ouverture de la création ne valide pas la qualité économique des actifs ni de l’oracle.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Parts, actifs virtuels et arrondis](04-parts.md).
