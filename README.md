# Repolex Knowledge Graph of scikit-hep/uproot-browser

RDF knowledge graph data for [scikit-hep/uproot-browser](https://github.com/scikit-hep/uproot-browser), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/uproot-browser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 99a0e2106e478633bd518a4e78bbae3dd6ddb7e7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 99a0e2106e478633bd518a4e78bbae3dd6ddb7e7
│           └── chunk-001.nq.gz
├── blob
│   ├── 0364eed3b3a589bbf4132477fe66c1fcf3c4d82a.nq.gz
│   ├── 07305d56935867bcab20bdffe3dd1603c7d05cec.nq.gz
│   ├── 08baae56fc2f3c32ba8ad19a4c689179a15cde5b.nq.gz
│   ├── 0967ef878ddd8817209d2673874115f75c875227.nq.gz
│   ├── 12c70a1a87ea8d036f5ee28faaba63e5bf01cb0a.nq.gz
│   ├── 1916849336912d215246cceab5720fdf6f8e92e7.nq.gz
│   ├── 1974bcd637687facb83a79c42ef22fd07cbd22b1.nq.gz
│   ├── 33df0aec15ee25befd3361cd986a1a8b8d9e6359.nq.gz
│   ├── 3712fd3e4c6db695fbc0317df4b821edb3cde836.nq.gz
│   ├── 3c640950fb6d524ef9baf58f2c059b7d6fe039f0.nq.gz
│   ├── 3fd9bf86d7dc81b9f3856d83391bff07cf9070d7.nq.gz
│   ├── 4910c68040d3d7ae06112494c88bd89febb419a8.nq.gz
│   ├── 4d89f2f3751c24cedf92c4df1e736bf8fc5f7b3d.nq.gz
│   ├── 4e03f63ca1b8286c6b7dd26f5909bb52f8e706c2.nq.gz
│   ├── 52c923e6252676c8c5201428a160d51be7c4a4d4.nq.gz
│   ├── 5bb2b22f78faec68eeed9a623c15cad2747c9eba.nq.gz
│   ├── 71397054ed8a7718cc7ef2f2f70fdce94b6f18d4.nq.gz
│   ├── 7503510d64e524be55303b4b1366b7c93a458751.nq.gz
│   ├── 83f4f773687b9ce94986711fca2d2265970f3149.nq.gz
│   ├── 84c94704d2fcbe2ae7a24316d84bacf299156015.nq.gz
│   ├── 8ef33a7c491e931dc0146f9dd5ab73cc5968d944.nq.gz
│   ├── 919ccedf65f8b3be150fca4192b2190b57d86e4f.nq.gz
│   ├── 943109b9a95cc3ebf8cac6a3b16a5595dafcfeac.nq.gz
│   ├── 98049c99bf4faac2045ae8559cf8951499149803.nq.gz
│   ├── 981787c360e0f54b7595c741d0131d062e231040.nq.gz
│   ├── 9d1e0987bfc323000b570d680343f00c53ddbc3d.nq.gz
│   ├── b8779146647d298ee751205c9d96a2538e98b467.nq.gz
│   ├── c343deb29f463773ebc2d7205f17934f65011e4d.nq.gz
│   ├── c73c380cb4fccc3a6d44a056fd8e7508509d4ad4.nq.gz
│   ├── cc95cf22bde9371ee2a0e4975963fb53f3b9984c.nq.gz
│   ├── ccdb523f1d11e9afb4ddb1d8182d97b8e24d9b98.nq.gz
│   ├── cfd7a5784833cdff39e9f68d30a9fde133bca251.nq.gz
│   ├── d2ab679ce288f160c2d9d42fa4c42c52ad518406.nq.gz
│   ├── d45a98baffe2a3fa9ef1e484d7a8a5642a89b5f2.nq.gz
│   ├── d511fc147c61469982202cb5a8a2ef2398ce155a.nq.gz
│   ├── d82eb3f94e78b4a096ec1b270ae1bf1a0910f670.nq.gz
│   ├── de4478ac822229371b2639281c17707886a0409e.nq.gz
│   ├── e36b22db2fd9ea28c54fc251680916189191d46e.nq.gz
│   ├── e39fc9f7f36b9fff9bda5b69f73aeaaefc7ba3c6.nq.gz
│   ├── e4d0001b85e468d1ecd48f495d582c98a173cb70.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee76bc4eb733c7dc1740b7aad23a3910fea9eaf2.nq.gz
│   ├── f133ca87ea435254fe4b8fa4ad0b3e9491d8ac24.nq.gz
│   ├── f879236863b4400a0f5aa17b3832536b9efef938.nq.gz
│   ├── fc097daa692c37fac88055484338e6e40f18439b.nq.gz
│   ├── fc0d51751710e7935ada5fd8e3a9d10e5fc97cd6.nq.gz
│   └── ff295e0009b050f19dbb85a3b78eaa2d1dee560f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 99a0e2106e478633bd518a4e78bbae3dd6ddb7e7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[scikit-hep/uproot-browser](https://github.com/scikit-hep/uproot-browser)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
