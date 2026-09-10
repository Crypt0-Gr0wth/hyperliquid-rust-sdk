# 01 — Lecture, signature et transport

Le SDK separe les lectures Info, les actions Exchange et les flux websocket.
Les clefs privees ne sont necessaires que pour les actions signees.
Cette frontiere doit rester visible dans l architecture de l application.
Les endpoints, la chaine et le domaine de signature doivent etre figes ensemble.
Une reponse reseau reussie ne signifie pas execution de l ordre.
Source : [`src`](https://github.com/hyperliquid-dex/hyperliquid-rust-sdk/tree/master/src).

[Suite](02-ordres-nonces-et-statut.md)
