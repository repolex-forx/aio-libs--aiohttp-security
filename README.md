# Repolex Knowledge Graph of aio-libs/aiohttp-security

RDF knowledge graph data for [aio-libs/aiohttp-security](https://github.com/aio-libs/aiohttp-security), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-security
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b9378635fdb02d8e8a557d6e014cc38a78abe2a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b9378635fdb02d8e8a557d6e014cc38a78abe2a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 04342287d4b3092cc40a251e6294d71cb68dae84.nq.gz
│   ├── 0b9cd2072fb6b6cd5c11f36a8b217c9cab6d1e9c.nq.gz
│   ├── 0d162a46042dea0006947a3441b1a762d7ad72ce.nq.gz
│   ├── 0ee16157a4992b44c0109e0d0d4b63d9ba756fd3.nq.gz
│   ├── 0f6c017b37855cd7b5f4625fff18b7ebffd1670c.nq.gz
│   ├── 1112c816114d42a634a7e112f7bdf1e328637ba2.nq.gz
│   ├── 14bfa8aecd24cdae7679451860e844ce4e62c1d8.nq.gz
│   ├── 175910415ac0327bb7cd242f4ce0dac26b3bb576.nq.gz
│   ├── 1f4ef78b1995a5cc8e984ccfe9466f0ab3ecff9a.nq.gz
│   ├── 25649705ae1ae83e36242e74699280503c824f8d.nq.gz
│   ├── 2affd9799f5ef58ee2aa842c23760caeaba84b74.nq.gz
│   ├── 3671773eecb53abbcbd827671042e72fb269d002.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 3700499313ee321572be627bef5b3792e8bbe6d7.nq.gz
│   ├── 3983a99b5657735ac7110dc70d39bb0e842fd361.nq.gz
│   ├── 4050838dec5bb22868bfed10c92dcb3fcf446c70.nq.gz
│   ├── 41f542b51ba563b97c1f838372dcfd003ad65452.nq.gz
│   ├── 4b0885f442ef3a01d4ca146a0eb54410976c0a2b.nq.gz
│   ├── 4fb2a7fa3bb70f7f09d26dcf0a797bbea554cfba.nq.gz
│   ├── 5adbcf0efe4f8a294642aaa5aa1f45f787c52c4b.nq.gz
│   ├── 5c2d373731bdc16fe381f12eb975871e435ceb1b.nq.gz
│   ├── 5fe671ded55c065d7abd369ddad3d4184442d585.nq.gz
│   ├── 65673e4d1b3c12beb067c5df4f412166fcc2edc0.nq.gz
│   ├── 677623f25d7592ac9c9b7c0b71d9b30a4dd5403f.nq.gz
│   ├── 6974a3d37e2140804ae92f98b5350d3ddb06a033.nq.gz
│   ├── 73040cbc5ccafc2430437c2d86e6b34b92ec2bba.nq.gz
│   ├── 76ddaa85129911ed04a2da0b224e7849bbfe4d56.nq.gz
│   ├── 7ab241d929e3654401d451c670344ce2badeaab6.nq.gz
│   ├── 80ada1160c49a424d96203f36f60df4d0876b79e.nq.gz
│   ├── 945d386a499b4d867528262d1746efc7dc3a5d4b.nq.gz
│   ├── 97d9d8ec7aa29a3e42667267d3185b3e61dee586.nq.gz
│   ├── 99f2477f71671fc4a42c1942b14f79cdf7d8eab8.nq.gz
│   ├── 9e41185ce706b2d98c4a9f757c15b2271db0d5c2.nq.gz
│   ├── 9e9a545a8099f5bb1f5f7774eaacb93d128c46bf.nq.gz
│   ├── a13c682299311633a12a427cee5fc8dae3f98e91.nq.gz
│   ├── a264813fe7442601901efcde62d9e8f270f19ba6.nq.gz
│   ├── a4400769ead748fb286c7dc22aab4c10573f136c.nq.gz
│   ├── a772a4b307be1daa7d85f791eaa2fc8418e37c16.nq.gz
│   ├── a99795b219bcba4eb60d5c4debb1744ae58aa289.nq.gz
│   ├── aac3ea2dbfd7b8ae043b856e9d923caa2756e1bd.nq.gz
│   ├── b322cda988e0bee7abad451f0ebb00575d3a373f.nq.gz
│   ├── be121f4442834256244f177fdf8dd273317dff5d.nq.gz
│   ├── be830bd8c9db7dc10140b9b8c7516ebba82dd8e8.nq.gz
│   ├── c126c2d79286e27e58baec4eeac73242bf19b2ad.nq.gz
│   ├── c7a36b954d0497ef979d630e78e41d6a4895e4d2.nq.gz
│   ├── c8e3a470b8a2690f5cc634abacf6bbe84b677a64.nq.gz
│   ├── d1f004ddc0c415ba4160e5dcd77f90e57a9d1578.nq.gz
│   ├── d8384ecf1bba882322e3c20ad06149e6e98d963e.nq.gz
│   ├── d94c885667df0ae712d066c9b8a825a7cd756740.nq.gz
│   ├── d9c85baea764ee1d95608ff760a93ab414fb51e4.nq.gz
│   ├── e5ddba111ef6b8f7a647e46d77cafa6a63e58ff8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea0822990055bf29ba14dcf08c47107d864d60f1.nq.gz
│   └── f09f50f6a6d43250aaf28f4874ecb7775c52d490.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b9378635fdb02d8e8a557d6e014cc38a78abe2a2.nq.gz
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

[aio-libs/aiohttp-security](https://github.com/aio-libs/aiohttp-security)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
