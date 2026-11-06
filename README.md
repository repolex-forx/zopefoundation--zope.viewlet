# Repolex Knowledge Graph of zopefoundation/zope.viewlet

RDF knowledge graph data for [zopefoundation/zope.viewlet](https://github.com/zopefoundation/zope.viewlet), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.viewlet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2b8d28559dd3549bc6dc06d8d7257edc71803de
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e2b8d28559dd3549bc6dc06d8d7257edc71803de
│           └── chunk-001.nq.gz
├── blob
│   ├── 00351391db25cadb1a03e8fb38b553d67f5ded90.nq.gz
│   ├── 017e183bbbef2676191efb4d3ac3094a7d291806.nq.gz
│   ├── 1646822ad9b0a656febad544a0f98e03066a435b.nq.gz
│   ├── 1ee53900fbffbdb5754f0348969cf395a93b3a15.nq.gz
│   ├── 21da76d2f5dd3a9008009a2f708240259cd74a4d.nq.gz
│   ├── 2318b4af212b8892c3bf144eb2aec778ac2f499f.nq.gz
│   ├── 2b69c72f7ac08791ddcf17724c8a218d9f74b318.nq.gz
│   ├── 35cd5a807e929eb02ff967cd35b40aa75f2bca0d.nq.gz
│   ├── 44e453420f4a5dce4d4bd83276146c6ce995e8cf.nq.gz
│   ├── 4e45bfe97830d10e46a854febc3d4f9e016bbced.nq.gz
│   ├── 5578a6d749a0168ad40d44211a2d034f6fe24ebf.nq.gz
│   ├── 5c2d0803516fdaf9d454c9858d0c33e969918ce7.nq.gz
│   ├── 5c52f6b0cead2e66b2f2fbe24c8a6aa377fb84b3.nq.gz
│   ├── 5fdac3ef2ec482bf92632be7f61f63923d591465.nq.gz
│   ├── 608bb93dc57be632db49d6ba88042f393a39298a.nq.gz
│   ├── 623fa469a6a921299e79918b06678a76f9042013.nq.gz
│   ├── 632c1a9d3e44f7893461b0cd0ee55a180e5dab3f.nq.gz
│   ├── 6cd5b9fda890cd4b556eb95f9e402d5c65871b4e.nq.gz
│   ├── 6ddb0cee2d4b269f4ffa40b7c7d6885713e4adb3.nq.gz
│   ├── 7aa4a014ea0dfe3f591bf1383a8bb10ce05e8b04.nq.gz
│   ├── 7db7bb0ed2e0bdc2a230985ea550c31670f182da.nq.gz
│   ├── 8bbdd2553444d35afd9c58216ff538565f7f0f2a.nq.gz
│   ├── 8e63bff4c8fdbfb598004a60d38d6da0e42efa04.nq.gz
│   ├── 9b4c65bd403cf9a3a32a2ff49e79ab61e6851812.nq.gz
│   ├── a5e6201f298ffe80c2745e0e41df1186229e5729.nq.gz
│   ├── aa6d125255f3a99f0b4b241892d42ddd0f755dcf.nq.gz
│   ├── add4919579e3765a11205757f1e7aeb3989fa0eb.nq.gz
│   ├── ae4041aafa7fee9a07ba24d275d0bce90b8ffc51.nq.gz
│   ├── b046c4b5ab3c69d26b901430df55cdaef1b5277a.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── c12b157bd7ff5c656c30eadaf8ecedee2a3c71dc.nq.gz
│   ├── c6cfe736a7b7f62b3c8c297e125a009d2520b37f.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cf19f4dcd1f720588cbcaf5bb0354fa0b722747b.nq.gz
│   ├── d9a1005de525a99d7149ae38092c76b0d36dcff3.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── e184fd8f41cbc229060cf69967d916bf6e2ddf2a.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── ec1fd5e4aefe146740b1d4cc9d9688be0985fad2.nq.gz
│   ├── eded24014ec0861b081110912f948427e900453b.nq.gz
│   ├── f507feda73c43de02c9268ef502bc4c3a2ebf32d.nq.gz
│   ├── f6ff81f05844c067f749c093d76d51c0dfe6eb3f.nq.gz
│   └── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e2b8d28559dd3549bc6dc06d8d7257edc71803de.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[zopefoundation/zope.viewlet](https://github.com/zopefoundation/zope.viewlet)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
