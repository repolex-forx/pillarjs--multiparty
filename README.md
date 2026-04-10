# Repolex Knowledge Graph of pillarjs/multiparty

RDF knowledge graph data for [pillarjs/multiparty](https://github.com/pillarjs/multiparty), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pillarjs/multiparty
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd8dd7acd416c4fbaf0161f27136bbfcb5fab764
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dd8dd7acd416c4fbaf0161f27136bbfcb5fab764.nq.gz
│   └── repolex
│       └── dd8dd7acd416c4fbaf0161f27136bbfcb5fab764
│           └── chunk-001.nq.gz
├── blob
│   ├── 050cdd9de54c97bf4a7834cdb0859bf9aa0859ef.nq.gz
│   ├── 060eac29e5933a12e2b76bfbf4b99bbacda1ffa1.nq.gz
│   ├── 0bae449442a8068036bba85cdb98d47206edf190.nq.gz
│   ├── 2b985981dc871f0740567a7e847370e0d7685159.nq.gz
│   ├── 2e2c61c7f30cf9d7407380b5a705848725fe3006.nq.gz
│   ├── 3c9dbe3dd070075fd84fe51ef81f11c739c04725.nq.gz
│   ├── 45032a13e52a2d9db3c5c4ace8fef7d6f8402d31.nq.gz
│   ├── 479e46d62d8fc866cef1b1b47f8d08c0434736f7.nq.gz
│   ├── 4d94297b10be0615e322f302451977f99ca9186b.nq.gz
│   ├── 4ef3917292429c9d558d422c43f035617d07a3a2.nq.gz
│   ├── 4fbabb338d76e901e446d836d19cc2890e9d8bd0.nq.gz
│   ├── 50b236102785523e4dee79373850b7cbd77ec8d9.nq.gz
│   ├── 52ceedb425d8fd48bc25ae7fd39cab31ad092e2b.nq.gz
│   ├── 54d3e2d55d9c3a27c6c615c1a9a41ca9935864ac.nq.gz
│   ├── 6379ac017f4c1638f1d01ea8d3c5a008dadcf257.nq.gz
│   ├── 63f109ec7cbff3aad1d6c887e4430ab5d069a69f.nq.gz
│   ├── 66ad259ef3ff704fdeae454268acec4ed02fa013.nq.gz
│   ├── 75232aa43b73953a4886b6656198c15af8002019.nq.gz
│   ├── 7a6e3e1097c15cb35ba7c556972a38e41f7ee984.nq.gz
│   ├── 84de439e54799ecf304a6ed7a1a80d31f50f711c.nq.gz
│   ├── 8945872410e45ef62f46942fc8da5ebdfad196bf.nq.gz
│   ├── 9b6903e26fc05e4a6f439f2fe551cafa3e7ab17f.nq.gz
│   ├── 9c82ba3661ffd71eb0cf2d9690639c45c4ddf1bc.nq.gz
│   ├── 9ca567cd4fe07cdb96ae853d4c0f9ac2b5f9adb0.nq.gz
│   ├── 9f1cef86fadd0bb6568bbab561543c82fcf92e28.nq.gz
│   ├── a4761699e9c938f4c703ae8de0dd294021924ed5.nq.gz
│   ├── a5ca104b942dd6be00fd09740877c1c107de7267.nq.gz
│   ├── be4103252c8151251637766f6e52bd9d35213fac.nq.gz
│   ├── bf49f85f93358c7b340a40d78012552c788d3287.nq.gz
│   ├── bff41f15c694acd2ffabf13cbd8fa8fd73693825.nq.gz
│   ├── d8dc968cf2b5402a30b6fcc8b420a5d27280bc46.nq.gz
│   ├── dad8d5f7193b79781368dae0ed5585d49c51c5a2.nq.gz
│   ├── e0dee27c0e63d132775252fef9009815ae3b8f42.nq.gz
│   ├── e1107f2a55fc0a0256fc75a039d64f42e30019a7.nq.gz
│   ├── e2b94fae255ff35524d695a963ddab32789f8d11.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a4785e00cd37146a070fdcf072f6af8d067e06.nq.gz
│   ├── e9493e9baf3e96e386e05e92f3f1e98895592618.nq.gz
│   ├── eb432ad62ed954118dc2dcaa637964a4b26b9203.nq.gz
│   ├── eb76fdc147d1dd01803c70607c8f73b93a9d0d14.nq.gz
│   ├── f0fc533a45b9f2a946c293b075b057e763c81a58.nq.gz
│   ├── f1d0f13c8a54d0f8d78f86a1f9348f3c59750694.nq.gz
│   ├── f6c15a64c682c21c840c336c90af4cc9d12247bf.nq.gz
│   ├── fe2ac1c6cd431e4ef7485ff8d056653056055a50.nq.gz
│   └── ff158a43cb4129517a78471041e8996882d3fc09.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dd8dd7acd416c4fbaf0161f27136bbfcb5fab764.nq.gz
├── filetree
│   └── dd8dd7acd416c4fbaf0161f27136bbfcb5fab764.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 55 files
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

## Source repository

[pillarjs/multiparty](https://github.com/pillarjs/multiparty)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
