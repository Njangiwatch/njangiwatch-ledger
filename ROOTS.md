# Registre des racines de Merkle — Njangi Watch

Deux portees : **complet** engage l'integralite de l'archive a cet instant ; **incremental** engage les fichiers ajoutes ou modifies dans les 24 heures precedentes.
Toute modification retroactive d'une capture change la racine et devient donc detectable.

| Horodatage (UTC) | Portee | Racine de Merkle (SHA-256) | Fichiers | Octets |
|---|---|---|---|---|
| 2026-08-23-full | complet | `b08f7ba9b1f0b649a25566e02031b3f8c3006d245121847f720bd99c6f752d79` | 800 | 632801674 |
| 2026-08-26T1948Z-full | complet | `99508f4109cb9d1499866a2e6b912b24b10a62e9ccababc02ae5127984f2622f` | 1866 | 1193180852 |
| 2026-08-26T1949Z | incremental | `821c6fa4f24a99f01e041b09c58f9d7d42a79181dbf97628364fa78c0c334747` | 249 | 119360533 |
| 2026-08-28T0644Z | incremental | `0fa7559dea63ffa4310a1111f0ed67adf5c52619863418cd0167e820afae5901` | 247 | 112064975 |
| 2026-08-29T0645Z | incremental | `71a70613c5d61acce0130245a7840c6d11ea8c01bda921cfb44e9819a4d5e1b7` | 270 | 116161489 |
| 2026-08-30T0645Z | incremental | `299d2b8cd43233398308679bba3282563ba06e5ee2bb692b6fde0100b04f16ec` | 178 | 111217500 |
