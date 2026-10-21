# Repolex Knowledge Graph of ibis-project/ibis-ml

RDF knowledge graph data for [ibis-project/ibis-ml](https://github.com/ibis-project/ibis-ml), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download ibis-project/ibis-ml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4a3b55b1554b395fe030df8bdfe8a2f68f16230
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4a3b55b1554b395fe030df8bdfe8a2f68f16230
│           └── chunk-001.nq.gz
├── blob
│   ├── 0119d623e03c95ab84d110f88e48a5924248a3a5.nq.gz
│   ├── 0192a57c3d415f7ba730be80ff26c388947d069a.nq.gz
│   ├── 02751fb3ae46400bf525dce1881d523bd29d8c71.nq.gz
│   ├── 033b85d4edd9d494ab41beaf0636d964db2c33f3.nq.gz
│   ├── 0a45f7f9a484c9e9e750b84477ae230a7ca33931.nq.gz
│   ├── 11c6cece64367b09080d9c83ba0b383223122304.nq.gz
│   ├── 140e18ad9dc803d8381422e97b163e332c6525ad.nq.gz
│   ├── 18600cbb760f3ef16f32ad32a8247e910b58a4e7.nq.gz
│   ├── 1f560a6ae07d7ba8c9c7b8ae419c55fc54a308f2.nq.gz
│   ├── 24a55a409cf2f7e75f07f47447f0681c74ca1e2e.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 29fdd1c6cef674db20896722d3614eb39367fa33.nq.gz
│   ├── 2cf44aeba44417ba064de48ef7b8f61e1654acf2.nq.gz
│   ├── 2f9b4196ea224dcea5c988bd464f87392e5ab82a.nq.gz
│   ├── 3034b489898e5de98c4cc2ae76cefbde6dfc61aa.nq.gz
│   ├── 30f19588e08002535ce927db82379795ca439bfa.nq.gz
│   ├── 39189f3b98773dddbe17a8d1f7b73f06544910c1.nq.gz
│   ├── 41509025f98560c56a547c0266f37c564cf2480b.nq.gz
│   ├── 4b9f1c30ae38a457decec78b1f14e339a061ba3a.nq.gz
│   ├── 4db4a254eda6acdfbef9d366fed01f1d87c465c5.nq.gz
│   ├── 4ec77ad07d6405590a33cfa2420cd87e261ae8ed.nq.gz
│   ├── 4fda66f8b7e7b953453398b294ec211176aa6774.nq.gz
│   ├── 5290637948c6ed1d2b10ce527752c99dd8e8466c.nq.gz
│   ├── 562c431d863977107f27ed30b3a7cc4f4cb3b2c3.nq.gz
│   ├── 5bb2c0f490bf897e0701db3cf70a182046a062d5.nq.gz
│   ├── 67fbb5df666a0b497653aee3845d6ac17f0c19da.nq.gz
│   ├── 68bc17f9ff2104a9d7b6777058bb4c343ca72609.nq.gz
│   ├── 70291a588f0bdc9b17f44e0a14f4328c49de3d69.nq.gz
│   ├── 73c5d72683f513c8775f4fc270a6ca363b9150cc.nq.gz
│   ├── 742e31a89fdff55130ad39e8b75d351f2ff507cb.nq.gz
│   ├── 749b76fe70be0c83c0744f7ad73e17f092e36215.nq.gz
│   ├── 757bc2cd0e1af3c347e7121d0268d89924ba3666.nq.gz
│   ├── 77ba10714e411320911161e997ea060aaf9b0c61.nq.gz
│   ├── 7df080f1dfdae96be8faae55747240501f3e45f3.nq.gz
│   ├── 7e79a127535ace6f50f3ac2b9635f5cb9de5f4e9.nq.gz
│   ├── 80199321c30979ca9c06452e0fa95c04c64f8305.nq.gz
│   ├── 83e7a8c53b12f13c48e84c419f70a7c2a16a2dad.nq.gz
│   ├── 8488b0be80ab45f04e8f69254117cc65f6b732bb.nq.gz
│   ├── 932d418672034c63eacd17e5fa7e1da4a7257e7a.nq.gz
│   ├── 93a11a558b2127eb2ca43930e97548a62ae58a8c.nq.gz
│   ├── 96d5d2db40ef2197940b93b36280ede5673bc5ed.nq.gz
│   ├── 9a6ef3861a6a8fd7c47ee2393cf566213bd19763.nq.gz
│   ├── 9b6ecf348d4d7bc4f06e12ec6ee23ce73b538d91.nq.gz
│   ├── 9dcafc39af21f74d9eac70d3950a76e1b2eb80ba.nq.gz
│   ├── 9eaa7d2431facb5342bcfae94cd9ddd5e59fca74.nq.gz
│   ├── aaec499bc26893df720af7ae9e34f431ca18cbfd.nq.gz
│   ├── ad3521776537ce3525922aca38efcd29ae57c66c.nq.gz
│   ├── adf15041678f235c1103ebb30afb91e01276daa3.nq.gz
│   ├── af0fdb712308cd07a64689afcae7203607662d3c.nq.gz
│   ├── af63b7f109d15f3ad936156b5fdf46eda38f42c6.nq.gz
│   ├── b81ffdf1f2c6ebcc8c7ef36bebe5f6bb229c2841.nq.gz
│   ├── b897a44d44a9051c7f493fd79d44c5da49d49a50.nq.gz
│   ├── c3ea057f320d57739a5bb0699e8a06ad59a91393.nq.gz
│   ├── c5ff6637c7b8ea1f3ab7f2aa96d01b8f85c31333.nq.gz
│   ├── cd96c38b100be48cd483842e2824f7d8ac5d6538.nq.gz
│   ├── cf56cd69283616af9a5efc313ca3fea9b3284991.nq.gz
│   ├── d1529edc533b3675ced4ca1864ade25219fec187.nq.gz
│   ├── d534d689eeef320a36444e01a2fc31b3691327c6.nq.gz
│   ├── d889805214df31d68d30d0a44a95d5e2fcb34c15.nq.gz
│   ├── d96ccd99d495aea13aac556fd6cd36b168747d04.nq.gz
│   ├── def1612d36a6bdb4fc6ab101e7c27b4547bdb8c3.nq.gz
│   ├── e29812f80187e524f628717e52a0a04624367cd0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec8ef591f1f9bcf5b4a641ef18cb24f52e82d493.nq.gz
│   ├── f0d450826cfc9d87c54ebd16cdfbac51dfeeead5.nq.gz
│   ├── fc3cb40cc648cb4190b1b51deb86b5e1af29179a.nq.gz
│   └── ffee9510b2e064f2d1f8a3605880cd6919efd380.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e4a3b55b1554b395fe030df8bdfe8a2f68f16230.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[ibis-project/ibis-ml](https://github.com/ibis-project/ibis-ml)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
