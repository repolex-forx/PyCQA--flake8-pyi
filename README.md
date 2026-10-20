# Repolex Knowledge Graph of PyCQA/flake8-pyi

RDF knowledge graph data for [PyCQA/flake8-pyi](https://github.com/PyCQA/flake8-pyi), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/flake8-pyi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ed488c2cdf80ce15b889e7f1a0629363ef3154b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ed488c2cdf80ce15b889e7f1a0629363ef3154b
│           └── chunk-001.nq.gz
├── blob
│   ├── 01861bcb0da87c4fedf76c32c6306985da8e73b4.nq.gz
│   ├── 0c8f984ef96ff1388fe03cdd35a7bb821a06b574.nq.gz
│   ├── 0d45b47e9d9d4a98070ea6e9657b1e77ade681f8.nq.gz
│   ├── 190b8dfabfe231b2733eb131fa4f6489dfebd8be.nq.gz
│   ├── 21c0b1e3cce5da3d2f059b1350a91459ac7a3785.nq.gz
│   ├── 23616cac2fa73213b6d84b5b2233dd42113132ee.nq.gz
│   ├── 23a2d5d9b03d969c4e29db5797677de3c77c6300.nq.gz
│   ├── 26beb5fc11855b4928fe45c1915e7b599bedad0d.nq.gz
│   ├── 26fb67037bf6129a7c8a9bb9137dcb3b4a3bda97.nq.gz
│   ├── 2b176ab8933d57761edf22d1e2df36fa5cd3f8c9.nq.gz
│   ├── 2c225de07b1a941f15f403dd70e28ce82131cc73.nq.gz
│   ├── 2ef5643f198952202ae7c1142a1f73c28ed4d153.nq.gz
│   ├── 311a73462e6621f9d19ca7d7894f54287da14a56.nq.gz
│   ├── 34b4329c9fe9856e076b3f3ff1fdc1813bd3ebc4.nq.gz
│   ├── 4a21f7ef15141db8a786b0a8101060d2e4434468.nq.gz
│   ├── 4bb8d538f255c4da8fc4d07d6232117999667125.nq.gz
│   ├── 4d31cc7d779090d612465b7e66629dd69225d559.nq.gz
│   ├── 50cf7c884fcf709931579b161324104279a17dd1.nq.gz
│   ├── 53452a64437b5dfe7b2fe5e640dd856d72b46b4c.nq.gz
│   ├── 53d9f4e70de045570baa159f07e12de0abf54c7c.nq.gz
│   ├── 546650eac68a0be57fc9efcfe1437dc5034bd8d2.nq.gz
│   ├── 5a83212a492b66d37bb87496add7c93ebcf43e89.nq.gz
│   ├── 5b4ebf6b7081f3acb775dba94b6e4d17a0a6300a.nq.gz
│   ├── 5b9f09d9f361658062c001f4790dd07ecfe786b6.nq.gz
│   ├── 5cada848ffde14141e1bec0d75f03e9a1c1b4e4e.nq.gz
│   ├── 74a87c5ebb2392cbe14bd79053f29318149f46dd.nq.gz
│   ├── 7bdc1f4c888b7d4dfc95027074355cfade31580b.nq.gz
│   ├── 7e0b66b84c101b74c3c7bfe56b853c95fba559c4.nq.gz
│   ├── 84b8dfc19a8bdd6100a48c3e55a6e7bef41bbc6d.nq.gz
│   ├── 896a640bedd03a0bea4574d29949c8c485655878.nq.gz
│   ├── 8e3c1528b18166e68bd7f139bbc95d54a22bf7b6.nq.gz
│   ├── 8efde37a4045c8fca15a22c1a60037baeceb5abd.nq.gz
│   ├── 91338de602e25b4fb0df5518c029c98cdc56d4ad.nq.gz
│   ├── 969ffb1e0bbe63ef129f25f82177dce2b54ccb2f.nq.gz
│   ├── 97ef2d6611105d4d5c077068287288fdd425010e.nq.gz
│   ├── 9bfacc1a099032eab0a9bfee300c4ad708d08d29.nq.gz
│   ├── 9dab31dc53eeb4628dbd72567a9244480a58001b.nq.gz
│   ├── a037974bd90fd7644fc7e1079b391331616a0300.nq.gz
│   ├── a1887c857ba789099dc048f66a8a9d1ce95dac87.nq.gz
│   ├── a8012889ee7e405ce53d426f7c7ac83e092f0974.nq.gz
│   ├── b03f7a2ac8292fe385e2e74ab54b8ca8399b915a.nq.gz
│   ├── b3af78053edd35ee0235ece6f84840860a89daf3.nq.gz
│   ├── ba7f77d6a8f8c77a30216dea6c60e467d101d077.nq.gz
│   ├── c2717ea55c4d6f1ab7138f8eacf0af44a29aa2f8.nq.gz
│   ├── c3199743fd5cbc9a2c98f7731747b2f897b00c78.nq.gz
│   ├── c3c68718b4a1bc17e36144353f9dce61c041e60c.nq.gz
│   ├── c5c58c36357464e48e279d25a8fed99856903acc.nq.gz
│   ├── c6b1357cd78fece565cb1ca60bdfa2826cb9a191.nq.gz
│   ├── d02b37c315dbfb676f70f84df7bffaaebff7c964.nq.gz
│   ├── d5a1e37dbd66062eb9c86630f57e463772f2eb20.nq.gz
│   ├── d9417bead5525dbb9ecde81f3a38872113fe23a7.nq.gz
│   ├── dd616077942454ee3654b4e137a997001b959af4.nq.gz
│   ├── e8c168bf85d8794ea86ebe4ee416192bdd5be71a.nq.gz
│   ├── ea9f9042c7cfa250f949c98ad5cc667595c3380f.nq.gz
│   └── f38b7058c66ac1db3e44b41400a277652d0588c8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2ed488c2cdf80ce15b889e7f1a0629363ef3154b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[PyCQA/flake8-pyi](https://github.com/PyCQA/flake8-pyi)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
