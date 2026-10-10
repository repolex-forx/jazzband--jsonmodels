# Repolex Knowledge Graph of jazzband/jsonmodels

RDF knowledge graph data for [jazzband/jsonmodels](https://github.com/jazzband/jsonmodels), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/jsonmodels
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0770de53806f00cb9a668cee690c3e247aeed4fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0770de53806f00cb9a668cee690c3e247aeed4fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 01842fa99c2195cf5365d53dfc25596f64e5f554.nq.gz
│   ├── 0790acb84300f145474e225b96f3910b4fa9c155.nq.gz
│   ├── 0d0cff59e7a5b38b31d0fa8cf5bba986d28cbaad.nq.gz
│   ├── 1005e265973ba976766d336b6c043d066e663d6e.nq.gz
│   ├── 1839c7be338c934dda81581fb5cf670c364a4331.nq.gz
│   ├── 189ad5a7d4843ef86495ae0ea6c133563893e077.nq.gz
│   ├── 1d0e44f0cf49ab16eb81bb47e1b9ec231e409e14.nq.gz
│   ├── 20abd3ec3141766c5e4bd2253cc9acb295b36198.nq.gz
│   ├── 212023c452636310e05844a3c4bb90079303a171.nq.gz
│   ├── 2a2a1b733f517e8dbdc5b3c3f9b2167364a2d328.nq.gz
│   ├── 2b4476477fe314cdf9e221f94cecc0727f32d8c9.nq.gz
│   ├── 33c2e1fbf44895babf17876dccaae4390ec6cf95.nq.gz
│   ├── 34a65cb791b625c0481aa7ef2835cf0886cbf34f.nq.gz
│   ├── 3bdd7dc21ab8a25854b5fd89f2eeae8a3af657d6.nq.gz
│   ├── 3f4b86a07d081221c530d3ef5e4a70f483f8b5b6.nq.gz
│   ├── 417f37b7e6d7daf17235cea16951c0dab8fcd8d4.nq.gz
│   ├── 43c6b0b9dd2d769b6e9719c26602f56df911b79b.nq.gz
│   ├── 467feb0013a134c4af794228125ff68e0191d2a8.nq.gz
│   ├── 46ab17b90cfc6e2d2276f3ca5e25b8d748cc0e2c.nq.gz
│   ├── 475891480caed7f48d859a684d14bd15d88bd722.nq.gz
│   ├── 4c7b3e6553ee0da03f35ca501255dcd29a379e5d.nq.gz
│   ├── 5f0991b0129a021277f6ab62e51f0796a5e77100.nq.gz
│   ├── 631feb4aa4f4c84e5f66f27a024ac1b17a1122ba.nq.gz
│   ├── 645161af3428fbf1bc00afa88dea81377cdfe8df.nq.gz
│   ├── 64e67fc660bc9c9961270e9772e2bc7e0e66ce76.nq.gz
│   ├── 659914f9ae53c257aa079fea329f638cbf9db212.nq.gz
│   ├── 6b2b3ec68c627e4cbbf773eb34269d5b8b703cd5.nq.gz
│   ├── 6be6a5107422080c96bd85ab8dec6039d64bcb0a.nq.gz
│   ├── 6fd5f0023216ada810729d00f5271f81ad1ae424.nq.gz
│   ├── 723f7189047374b4919a91c2ec41c468d4cb8513.nq.gz
│   ├── 77d3ba97c63c3629f1e13aa4d7d86e361a03eac9.nq.gz
│   ├── 7ae17880e9904d498260738509130a0469eb7935.nq.gz
│   ├── 7ba415df8a5da1a38763e6d50096bcee3fff2451.nq.gz
│   ├── 7db8e7a4374cfda1b996ea6c489775d6e99ae1b9.nq.gz
│   ├── 7fd02ba41dfed880c6289d0d441677bdb61059c2.nq.gz
│   ├── 820b4473b89896b32f30f9228d6687ff1fd7d68d.nq.gz
│   ├── 92e9fa904b4597d79764a075e7794ba8f7b7ebc8.nq.gz
│   ├── 9337172a03ac1f93e96affa74a4db41710d6980e.nq.gz
│   ├── 94292d017cf692423bca025d38aae6a7773a3936.nq.gz
│   ├── 953e77300e89b85cdc01af18feb27e374638fc08.nq.gz
│   ├── 96078819f2082e1b78808653c30f1b2ce8cc57e6.nq.gz
│   ├── 98c9c3433e4614d4ee81222cf7d2e8a128505996.nq.gz
│   ├── 9900d5c422a2ee3264e9da49e507206f39a7c29c.nq.gz
│   ├── 9c7d2c5bc10103800343a218a518625218900080.nq.gz
│   ├── 9e8055841dff5bd6876aa821e56890b382ba5e9b.nq.gz
│   ├── a0310238deaf8a65e25c424a8e6786d6a16b5cbb.nq.gz
│   ├── a12229f8844be9cbf7f0759bc6e206f120c2552b.nq.gz
│   ├── a2c839e1186e4ca3af42a6d4ae32eee7fc86612c.nq.gz
│   ├── a2cd43f9d4caaeb57ba823373d9f45fc93b789a8.nq.gz
│   ├── a3c6da2e1a6f6674fb9cbfc5b02a84a937e75aa3.nq.gz
│   ├── a3ce15bb07e78f068ef4ce0529c852dbfd989116.nq.gz
│   ├── a71b86f389a7077dff684505d3516b723a9b0eab.nq.gz
│   ├── adeb5203bda9ee86557d18086fa6e51777650ed9.nq.gz
│   ├── b4fa668739cfd375a9995d94032036679683e938.nq.gz
│   ├── b72b7ddc640d18ae8039d851b4df5a87c1840cc3.nq.gz
│   ├── b73cc86075651b3f8f05960417f2e680ed669a8b.nq.gz
│   ├── bc6f4f23cd771ebf0fb6d98bfe2d57e3211aefd9.nq.gz
│   ├── bd0b274405185cc587caa3c5d8795957c2b3027c.nq.gz
│   ├── bec23d82d4d863a4d5d6033ad975386be811e6ce.nq.gz
│   ├── c27f7b57547e750611c77b1ee9240509a0855666.nq.gz
│   ├── c89e3887ce5b4db75f20d219c4eb567e2031fb5a.nq.gz
│   ├── c8a2e74a043b5f16ccb52ae2bdc2461347f889ed.nq.gz
│   ├── cd545473da57b641f892b7338c52840203c1c62d.nq.gz
│   ├── d44fbca8c86abd5c24be086cce252bcd7ffceea9.nq.gz
│   ├── d961b9649be8cfe5249036e4907dc5b7ca6987a9.nq.gz
│   ├── deb560dd20bfa214b4110baef4b9b7ac62c9af0c.nq.gz
│   ├── dfd770e01ff06e84fdf14f11934e07f59c523e3a.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e116604bb3222ae4e4c429e81d10c5738e6bf9da.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a8207afa40d15fa9ada97d32d8871f6285d6a5.nq.gz
│   ├── ee31db891a234dd342581b287f4476a214ed8950.nq.gz
│   ├── f04ad035fec5d58fccb6586efbb4034d16c7c115.nq.gz
│   ├── f2241423af69286b164e8f1a0bf5a8e631c03e39.nq.gz
│   ├── f2b69004139a55f9b8c1287e41fa0efc354f986e.nq.gz
│   ├── f4f828c76e1410424528dc3621742d0454ec7d1c.nq.gz
│   └── f814a38f5a93dd78868e42e5e58d49dbb57f1df6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0770de53806f00cb9a668cee690c3e247aeed4fd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[jazzband/jsonmodels](https://github.com/jazzband/jsonmodels)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
