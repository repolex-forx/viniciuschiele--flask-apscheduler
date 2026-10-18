# Repolex Knowledge Graph of viniciuschiele/flask-apscheduler

RDF knowledge graph data for [viniciuschiele/flask-apscheduler](https://github.com/viniciuschiele/flask-apscheduler), parsed by [repolex](https://repolex.ai).

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
rlex download viniciuschiele/flask-apscheduler
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5b6cdd10415a413b2773b7750d56b7dfed68018
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5b6cdd10415a413b2773b7750d56b7dfed68018
│           └── chunk-001.nq.gz
├── blob
│   ├── 013dd2021de1a5afd414b8f87a273204170a9d5d.nq.gz
│   ├── 0f880eb8a4e93c58ee4fd5280c8b6584945af8ea.nq.gz
│   ├── 13b7a936cc2bc03af81d381fb0ad6d52415306b1.nq.gz
│   ├── 158317e424b66ea2c9f544af91959009c5e456e3.nq.gz
│   ├── 185cdd1ac29dd21c5e65b9f2a8e9654d580179a9.nq.gz
│   ├── 1a0ab0626c7cc1c8a472a07fcf585ed4412a221f.nq.gz
│   ├── 1d873ed967c5352321c11fb4b986fbc5a391d960.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 22460756ff3dffeee28ea5800b3310f57748fafd.nq.gz
│   ├── 259988a8768fb219852a9cdefd64588c979dfaaa.nq.gz
│   ├── 2c8da6324e3cc0810281f5d6292bd3fe18320238.nq.gz
│   ├── 3b10d77c7619da34f4d89ff81a681a83459b9b5b.nq.gz
│   ├── 3c30efbacfd5dd57b9267018bdf6c0f51f2439a8.nq.gz
│   ├── 405a262c89cf68494b2312995991aad362351831.nq.gz
│   ├── 4b41c91ea4f046980788c2e2365deb20b67c7667.nq.gz
│   ├── 50dd46857d386a33d13cdd53dd0d475e2cf85839.nq.gz
│   ├── 57a46857c685e109cac7b41c9eeef2052b33712e.nq.gz
│   ├── 5f441f86bd67e5aa029370223fedf744617e6722.nq.gz
│   ├── 5fb003bde5266f75648704661fbe8d98ca61db52.nq.gz
│   ├── 6562af7ec4404435b208b95accc2231cf337d7e6.nq.gz
│   ├── 68dde7e96885fa4d7365e7ec03accfd963634ca9.nq.gz
│   ├── 81f39f8864ad5babf1df722e13193d18afbc4d57.nq.gz
│   ├── 9073ac4e466aed6fe043c440c444684c20f9411a.nq.gz
│   ├── 9d961880c0b7ec06654f3182e6cd5a9b1f26ce46.nq.gz
│   ├── 9e11a05eaf790b623f9581f053f197e550345982.nq.gz
│   ├── a1c0b2e2e309fd11d9842181d3f91b78e99b344f.nq.gz
│   ├── a399edc223ac59174614008a606a889bc0f38c55.nq.gz
│   ├── a60affbf510573ccd030bb478f3e51f2d22711e7.nq.gz
│   ├── a6cbbc9952d740ffffe70aa3dc4d35e94f13a527.nq.gz
│   ├── a8b202e18857a73ddde3729518e338bb62da1410.nq.gz
│   ├── b4f7171ece201ba52110ef44174f434d99bf40e1.nq.gz
│   ├── b7d5ea804d73c6ca37920996570f17d146cb639e.nq.gz
│   ├── b8201771c00759bc0dbb2612ce498c3b95215222.nq.gz
│   ├── bdfc643f742b17640f8b23267740415f4139682b.nq.gz
│   ├── bfdc9877d9acc165c0342befa33f2e8f769538cf.nq.gz
│   ├── c732c8c4975fb71d3ccbe9d76860853dc995ae8b.nq.gz
│   ├── ccf2f9e2511a7e4fece7fe18c6405d25d0047149.nq.gz
│   ├── ce0d8071601f581daf81f229b990aa3a98a1909d.nq.gz
│   ├── d1e28a847f8b23675552d6f5c8754a20ffa1b449.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── da49d7296d9728000379952cbb9eaeef7992e1b2.nq.gz
│   ├── dda80d01a64607899c41608113a62dd207c2232a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed738adf7197cd2fc58c293c6a8a1cbac205f2fc.nq.gz
│   ├── f0eec33b9dca4881787bc5d9c973f6efc9785eb8.nq.gz
│   ├── f326a01a4abcb4cf22b1382fb42ad5bd69a39566.nq.gz
│   ├── f4a72a9ba504d2041ab89c4a5e006c6cb57d2b55.nq.gz
│   ├── f940876cd59304cb992cb18ce498ae6f1acbe3ab.nq.gz
│   ├── fa5ef052940bfaf15e983c7a70f2f91d3f4502ee.nq.gz
│   └── fc8a8641048961befc7b1edaaf622346556fe0a2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d5b6cdd10415a413b2773b7750d56b7dfed68018.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[viniciuschiele/flask-apscheduler](https://github.com/viniciuschiele/flask-apscheduler)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
