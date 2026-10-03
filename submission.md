# A week on the Stacks Vibe Index

Completed 15 paid Vibewatch queries using sBTC across 5 distinct UTC days.

## Qualification summary

- Paid queries: 15/15
- Distinct UTC days: 5
- Distinct paid endpoint types: 2
- Payment: 100 sats sBTC per query
- Endpoint mix: project snapshots and delta queries

## What the paid data was useful for

The paid data was useful for tracking how AIBTC's Stacks Vibe Index changed over time while comparing full project snapshots with incremental delta updates. Varying the project history window and delta 'since' parameter made it possible to observe the index from different time ranges instead of repeating an identical request. The combination of snapshot and delta endpoints also made the paid API useful for monitoring both the current project state and changes between observations.

## Query evidence

| Run | UTC day | Endpoint | as_of | Payment txid |
|---:|---|---|---|---|
| 1 | 2026-09-28 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=8` | 2026-09-28T14:30:04.624195Z | `dde87898f8b82bc9879736312f7eed18140a0afc9841932cc0f9c6775241c5e4` |
| 2 | 2026-09-28 | `/api/v1/public/stacks-index/pro/delta?since=2026-09-28T12%3A34%3A59.341Z` | 2026-09-28T14:35:23.756540Z | `26ed5de515919f231b8f64164d1c8aa45f636a465508539d2c6187863d11b905` |
| 3 | 2026-09-28 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=10` | 2026-09-28T14:36:21.980335Z | `e4c7df00e79e8eb11c11b5ebec0811f19665ba0f58a1be74249d5de8a6d5b025` |
| 4 | 2026-09-28 | `/api/v1/public/stacks-index/pro/delta?since=2026-09-28T09%3A36%3A58.477Z` | 2026-09-28T14:37:22.142131Z | `6fb8ce1ae6f1c5f0cb2f526acfacf3d7df3720b09fedd83064f8da81a35d3fe5` |
| 5 | 2026-09-29 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=12` | 2026-09-29T15:15:48.928684Z | `7a86ce3ea78c6e697362fc53a94c77fa4c5cf5acec61b795b44157192686159d` |
| 6 | 2026-09-29 | `/api/v1/public/stacks-index/pro/delta?since=2026-09-29T08%3A05%3A28.041Z` | 2026-09-29T16:05:44.416922Z | `93f78f09ea2b683d16983008be2843b5fdf895b398119d78359a30c0dab8a43d` |
| 7 | 2026-09-29 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=14` | 2026-09-29T16:08:01.485989Z | `6d9024a24598fbe77c32ced3f24dac8051c57916c440ba2afd224dc24cdddb8e` |
| 8 | 2026-09-29 | `/api/v1/public/stacks-index/pro/delta?since=2026-09-29T04%3A09%3A05.456Z` | 2026-09-29T16:09:28.449492Z | `5d0e6122b0ef3e3ce9a9647624aa02f35b293edf444f9d6c44513e15cec46f12` |
| 9 | 2026-09-30 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=17` | 2026-09-30T00:05:50.283566Z | `20bbf72c7cde24ac299d201527b0505038ae07cd147a5d513f4e522cd831ec9d` |
| 10 | 2026-09-30 | `/api/v1/public/stacks-index/pro/delta?since=2026-09-29T07%3A05%3A25.230Z` | 2026-09-30T01:05:48.885686Z | `cdbc397425414c01954f4a9975a8f7c024234c02f5adc09b3ecc6b449fe8d017` |
| 11 | 2026-10-01 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=21` | 2026-10-01T04:09:33.942203Z | `0c7d7a75166ed2496a619f26228a2761674dee548dcc1c28a3b4c6cf514a89c2` |
| 12 | 2026-10-03 | `/api/v1/public/stacks-index/pro/delta?since=2026-10-02T03%3A12%3A45.561Z` | 2026-10-03T03:04:20.845746Z | `b9e4319a832d6f395cd8236b65e77355e726682d886fd8922852a644f1cbf428` |
| 13 | 2026-10-03 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=24` | 2026-10-03T11:00:52.978419Z | `8e8a1277b559a1ceea26a23143a60b8706440008581e6f706dbad3af6e006565` |
| 14 | 2026-10-03 | `/api/v1/public/stacks-index/pro/delta?since=2026-10-02T06%3A00%3A35.080Z` | 2026-10-03T11:52:23.408842Z | `8a404ea48760e2c6606f64a482260a78584df8ad54162c18db27894c0ae8066a` |
| 15 | 2026-10-03 | `/api/v1/public/stacks-index/pro/projects/aibtc?days=30` | 2026-10-03T13:00:55.729279Z | `a7c5fb4fc26515d39490327c6530af1f448eddbbb76f6aa64ad9fc7766381e1b` |
