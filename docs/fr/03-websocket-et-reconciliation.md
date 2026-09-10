# 03 — Websocket et reconciliation

Un flux websocket est une source d evenements, pas une base de donnees definitive.
Les deconnexions imposent un curseur ou une relecture de l etat courant.
Ordres ouverts, fills et positions doivent etre reconcilies periodiquement par API.
Les doublons et messages hors ordre doivent etre toleres sans doubler un effet.
Le client doit exposer retard, derniere sequence et etat de reconnexion.
Source : [`src/websocket`](https://github.com/hyperliquid-dex/hyperliquid-rust-sdk/tree/master/src/websocket).

[Suite](04-checklist-defensive.md)
