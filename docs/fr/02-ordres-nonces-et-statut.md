# 02 — Ordres, nonces et statuts

Prix, taille, reduce-only et type d ordre font partie de l intention signee.
Les nonces doivent etre coordonnes entre processus pour eviter collision et rejet.
Chaque statut d un lot doit etre associe a sa requete d origine.
Apres timeout, relire ordres et fills avant toute resoumission.
Une annulation peut croiser une execution deja survenue.
Source : [`src/exchange`](https://github.com/hyperliquid-dex/hyperliquid-rust-sdk/tree/master/src/exchange).

[Suite](03-websocket-et-reconciliation.md)
