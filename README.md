# Repolex Knowledge Graph of jaraco/pytest-home

RDF knowledge graph data for [jaraco/pytest-home](https://github.com/jaraco/pytest-home), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/pytest-home
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 020ecd5d9be59d062af9e91382f3b16225116555
│   │   │   └── chunk-001.nq.gz
│   │   └── d9d598faec10d525a83dd6a6b6970f9a1855b0ad
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 020ecd5d9be59d062af9e91382f3b16225116555.nq.gz
│   └── repolex
│       ├── 020ecd5d9be59d062af9e91382f3b16225116555
│       │   └── chunk-001.nq.gz
│       └── d9d598faec10d525a83dd6a6b6970f9a1855b0ad
│           └── chunk-001.nq.gz
├── blob
│   ├── 0db3cfcc060b0f0b765f0ab2b32f67cd8c5658e1.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 19db9c00dc127500ae13f4b337f9b96826ff8241.nq.gz
│   ├── 1bb5a44356f00884a71ceeefd24ded6caaba2418.nq.gz
│   ├── 1ec8e5e4b43cd5e01df3ede94e652eded3b5a855.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 32150488de655c2c2ef3b26c0a8519e7365584b3.nq.gz
│   ├── 35b98b1df96093e99fea65bec2187baff3c12514.nq.gz
│   ├── 3ed6b132a5d32fdd98f1555d5ff8c11fb0093ae7.nq.gz
│   ├── 406b8e49c30b0ab34356a14ffa71c692ecebd4c0.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5a4a7e9166ec3143f71b5e3875860802048554f3.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5ce6cb7c29c0b3d211df3b912670773cfd282dba.nq.gz
│   ├── 6fa480e44f38768722368d7a986607adacf41d99.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 706aa3c511587a0fc070b1f908e574146fb7ba19.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7de0f14ef823029e6312d93da85255210936840b.nq.gz
│   ├── 898874589bee918fe9e7d4ac61b56604938b5323.nq.gz
│   ├── 89ff33961ba3d6f9cda89322a1fdbf1ac2e35513.nq.gz
│   ├── 922aa1f19856d5841e80b0a2370e0e5fa7c41512.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── ac0ff69e22507b430cfb9a91d98e2451a3de52d9.nq.gz
│   ├── b09e328d43cc75ea29c9cf6235af31fa56faac9e.nq.gz
│   ├── b6f972769e61a5e65f9f45015b363cc362487e55.nq.gz
│   ├── c1087fa52fdacaf93644b462064da14f722c45be.nq.gz
│   ├── ccc7d949e2577d52c01dbd429a7c932f8e9d82a1.nq.gz
│   ├── dad9e207b5045b874d923f75f4e54d79f1f70ac1.nq.gz
│   ├── dc8516ac20b3d38cf754fe8d804ffdffafc15ef0.nq.gz
│   └── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 020ecd5d9be59d062af9e91382f3b16225116555.nq.gz
├── filetree
│   ├── 020ecd5d9be59d062af9e91382f3b16225116555.nq.gz
│   └── d9d598faec10d525a83dd6a6b6970f9a1855b0ad.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 49 files
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

[jaraco/pytest-home](https://github.com/jaraco/pytest-home)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
