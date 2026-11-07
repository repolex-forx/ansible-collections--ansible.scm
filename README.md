# Repolex Knowledge Graph of ansible-collections/ansible.scm

RDF knowledge graph data for [ansible-collections/ansible.scm](https://github.com/ansible-collections/ansible.scm), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.scm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5389892b95b8f90584ba38032212f6d141cf5400
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5389892b95b8f90584ba38032212f6d141cf5400
│           └── chunk-001.nq.gz
├── blob
│   ├── 114b5fc80ed14572211570f5d863d14d593f7da3.nq.gz
│   ├── 192c19e0f2218d71677d405cb7fb5638abbd596d.nq.gz
│   ├── 24c09b33d30ac1c34325da430789fe98d3990a4b.nq.gz
│   ├── 29b863a6dc3395d80dd4143030f593dd84d7c7e5.nq.gz
│   ├── 2e2ff47c87a88c72254c7af6bcabbde0244c873c.nq.gz
│   ├── 3034ef4fd66a246bd4abfccdd7e3beae1e0108ef.nq.gz
│   ├── 30b8aa8fce47b5596fedd29572e210b0f4532aa8.nq.gz
│   ├── 32cefc1745a81faf913378eb41b2cff70797c330.nq.gz
│   ├── 34e289fd31405e8fd2970343e53eb7c8e2459e16.nq.gz
│   ├── 34fceced42c262a3a79526e66287a03366be40a4.nq.gz
│   ├── 3bbc3e442d5582fa2051464b36becaea5bfebb87.nq.gz
│   ├── 3f7d1e18ed211fbb7ccd165e5e70e7a2f73b19ea.nq.gz
│   ├── 402f69edf78f353687ae47fe334c6690cd0cc50f.nq.gz
│   ├── 42d6b17c685c88451e232d6a01c74b61c97a439c.nq.gz
│   ├── 4623169ee38a6f1c4307234cf7733d5eb5592132.nq.gz
│   ├── 4d4455b75d42245d64fdfff88e0a292a9233b8be.nq.gz
│   ├── 4dbb5458f8b9b6a885fe7c606cf6065c2f70c0c5.nq.gz
│   ├── 4dd47db7c48f31d3fba961fac95c3c59f91e8cdc.nq.gz
│   ├── 563a652f6b9116049fc2b7c88b8997a1299a026d.nq.gz
│   ├── 5b32d4c1097ae6224bc65d88f0406972563164da.nq.gz
│   ├── 5e1f4b36a5aa011a027476d595be88415427a912.nq.gz
│   ├── 612e939ac9ff5bb0328b824c7bf10ac2617698be.nq.gz
│   ├── 6187e7c58066a6c54926496668a52faa1f99dcc1.nq.gz
│   ├── 63b109cd549c1f91c74a6698f2492e310f0d4e8a.nq.gz
│   ├── 6563af9ff41f6726f18636f98dfd9805d0a5ce87.nq.gz
│   ├── 6c36cce8df90125853356e942ed685519c735d60.nq.gz
│   ├── 7021de7c96106f5353dd253414289c9d80085afb.nq.gz
│   ├── 7465d3eb38ddd99bdaaa2693dfe76674be2c3c93.nq.gz
│   ├── 775aec6231f7b7f7b7b5c94f5f9fc82896c74b32.nq.gz
│   ├── 7822bf0c31239f0c7f63fc6bd75e2ac162b31029.nq.gz
│   ├── 82104ddb985d92e1037a9caa86e4aed93663f6d2.nq.gz
│   ├── 830779564b5603c1c34df19a09b0465bd29d8960.nq.gz
│   ├── 8d9bb70b834cffd1056efa08377df15e82928036.nq.gz
│   ├── 8e68aa3ec801b174874ea29f387635ce82446cc0.nq.gz
│   ├── 92bf41f1d9234679a8d6c199db3968a1b1a283b0.nq.gz
│   ├── 990d024e357208919190942ab35da1daf6b28329.nq.gz
│   ├── 9f1d1944182e68a74d876c20ccc949c5ecf8f026.nq.gz
│   ├── a0a90047a94352008f53eb109c2037022b517683.nq.gz
│   ├── a226f499fd0d3b3b941e927d416a1386b268d90f.nq.gz
│   ├── ae7460ed2472c20775fb72b9cfa19e79e80f7f38.nq.gz
│   ├── ba5803adc5c4ad40320994a76cce6c148a7c0701.nq.gz
│   ├── be83ba636d7955589bdedf866a0222951c6761d1.nq.gz
│   ├── c72963f53fe4cbe819f6de2e806f4128ba7884a9.nq.gz
│   ├── cada0c0b2786c276103b72278fa5ad0c6edc3c4b.nq.gz
│   ├── d5b3255ab4cf3ae2dcd813f67a056a06c17a4185.nq.gz
│   ├── d5daa153044f969cabc6c6dfd2b7de0b34d444fa.nq.gz
│   ├── dd3d56d0570c935f7b4c0899605f7056eb29849f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef12980ba754d5ee07ee7bda6cf4378fa1ff4e6c.nq.gz
│   ├── f28622baf0056374294f247c32c8eac82aa13496.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f315769e302067e5f39ddc01129e517e50c91857.nq.gz
│   ├── f8f9ba228ca9de17893be90cd708384dec50bb72.nq.gz
│   └── fb82793db645b1602c6e96ff448119c7dbf0e931.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5389892b95b8f90584ba38032212f6d141cf5400.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[ansible-collections/ansible.scm](https://github.com/ansible-collections/ansible.scm)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
