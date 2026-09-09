# 5. Déposer et retirer la liquidité

supply accepte soit un montant d’actifs, soit un nombre de parts ; l’autre valeur doit être nulle.
Les intérêts sont actualisés avant la conversion et l’écriture de la position.
Un dépôt peut créditer onBehalf tandis que les tokens viennent de l’appelant.
withdraw vérifie l’autorisation puis réduit les parts du prêteur.
Le retrait échoue si les emprunts restants dépassent les actifs prêtés restants.
Avoir des parts ne signifie donc pas pouvoir retirer immédiatement toute leur valeur.

Source : [code du dépôt](../../src/Morpho.sol).

Suite : [Garantie, emprunt et remboursement](06-emprunter.md).
