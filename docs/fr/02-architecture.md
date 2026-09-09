# 2. Un contrat, plusieurs marchés

Morpho.sol centralise les opérations dans un seul contrat.
market associe chaque identifiant aux totaux d’actifs, de parts et à la dernière actualisation.
position associe le marché et le compte aux parts prêtées, parts empruntées et garanties.
Les positions de prêteur sont des écritures internes, pas des ERC-20 transférables émis par Blue.
L’oracle et le modèle de taux sont des contrats externes propres au marché.
Une adresse de token identique ne rend pas deux marchés interchangeables.

Source : [code du dépôt](../../src/interfaces/IMorpho.sol).

Suite : [Créer un marché](03-creation.md).
