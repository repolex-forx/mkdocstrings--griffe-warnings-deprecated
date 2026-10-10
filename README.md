# Repolex Knowledge Graph of mkdocstrings/griffe-warnings-deprecated

RDF knowledge graph data for [mkdocstrings/griffe-warnings-deprecated](https://github.com/mkdocstrings/griffe-warnings-deprecated), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-warnings-deprecated
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cc3a695b7c1564a58d1d47c051a0637b6a795cad
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cc3a695b7c1564a58d1d47c051a0637b6a795cad
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 045c849f712931020c7c30f2fd040ddc4d392a82.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 0dda90f032de2990cd454a5fca01536cb6e766e7.nq.gz
│   ├── 1267c758dea2ee5b2a5f2d5a7b8838b6db76cfe6.nq.gz
│   ├── 1d4215ebf665270c29f437e07deda840bb5ffe14.nq.gz
│   ├── 2540e583c3f68dec71761f9bc6275d2b4c8c36f6.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 27f5c847122682db9af1f57a63348b425e5e710f.nq.gz
│   ├── 2906766b186e772a054515291344292cb1401383.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2dc679be3d114e525c4fe2b1d3abf3b1a3bbcbb9.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 32340b5bab9a69348a9dd010f1bd6eb7c53c58be.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 3dee7dc58b957d61458b6ff1d211ecc9ce161239.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 4cf590ecd935638284d532a41d063afbcb6d3562.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 5e9b0cef5f2a0e30c85e8c4d9802803865a2fd41.nq.gz
│   ├── 5f42235db9ebc5899ca20605bd10c95ef95c97fc.nq.gz
│   ├── 5fbc5f6d1b7778ebe70e0c95202a3b8689c69b24.nq.gz
│   ├── 618b4c6d3c01551ddaf11e559872ced059172a8d.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 635e370087541afefc1cb14287517dbfae8d798b.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 763942b5200f83eff2683977f0ff56d2ad6a4a88.nq.gz
│   ├── 80e883d7ead24711d034ba77865e0f2bb6f6dd18.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 89661439b96003392850d7e954f23389f091e8d5.nq.gz
│   ├── 90aede9cdd2fda2db168a163703cc9cd41331e8b.nq.gz
│   ├── 9262c220573aa4deac58aa84b0d9faf596f2e6c8.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 975b5155b41e7a36c392dcf7ab0f7d690967de33.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9c08a6a69c749f5b9525a8d0f37c2fbc46a72635.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── aacbe59290f38cae9a3b0f007ee63a5a9942c3fa.nq.gz
│   ├── ac7a3ad58031c9b569f6c81a4e7c0b2402b36b4a.nq.gz
│   ├── b149d0120334ec19001efdbd479598561952c3a9.nq.gz
│   ├── b2a38c79cf943eab2dd85495ba5d5b3566cd71f8.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── d708c3ac80f93ef1f6e0622197ac8431f50ae41b.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e3d28b38c94eeb9fa2ea0a955d3ff31c8c3ef6e6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── eb346e84478be953bb44e536e3a2c2baa987ee98.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   └── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cc3a695b7c1564a58d1d47c051a0637b6a795cad.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[mkdocstrings/griffe-warnings-deprecated](https://github.com/mkdocstrings/griffe-warnings-deprecated)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
