# Repolex Knowledge Graph of block/chalkline

RDF knowledge graph data for [block/chalkline](https://github.com/block/chalkline), parsed by [repolex](https://repolex.ai).

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
rlex download block/chalkline
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7d3b434e9bfd7a412a30ff9ef7750c515e3089da
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7d3b434e9bfd7a412a30ff9ef7750c515e3089da.nq.gz
│   └── repolex
│       └── 7d3b434e9bfd7a412a30ff9ef7750c515e3089da
│           └── chunk-001.nq.gz
├── blob
│   ├── 001745c22b9f3004c52fb611b6f988d90afebc5a.nq.gz
│   ├── 12576d830e83dd6364e0c0b93779f0bc0432ea62.nq.gz
│   ├── 239ba64954ebd6123673f2e7c502dab18f514214.nq.gz
│   ├── 259e604cff7f32de0a4ee963db594736205861d5.nq.gz
│   ├── 277490747366706221e76fba9f256d57e80eaac1.nq.gz
│   ├── 27f0c3a9da7bcf09d017fc9a6f99c1db6dad5ef3.nq.gz
│   ├── 28dd1823e11adf4bb61dfa2b370b5f738a5e96a5.nq.gz
│   ├── 296b248b4729f9cc02d31285d940e52e08382f3b.nq.gz
│   ├── 29bd70a2044e8798e40b4bf83d399804227ee275.nq.gz
│   ├── 331a9337d7ba5be22f875237aef4bbc303673b8b.nq.gz
│   ├── 35022282897e315032aac3113091baffa826ef8f.nq.gz
│   ├── 3576ef09eb3a3d1745f5d95d61cef3d48ea820ea.nq.gz
│   ├── 373f07cceba1b77f9a0da72362bb93d84d30707a.nq.gz
│   ├── 3ad247e7471dde3976a1d95f4e8d1c9d6257afdf.nq.gz
│   ├── 43ae0e2a6c6d8fca34872506ca0f2e64194fec7c.nq.gz
│   ├── 443f42106126eed1813acac0d9f34cc59889532d.nq.gz
│   ├── 4ac6448831b644ca09a35df0267adc3baabe07a2.nq.gz
│   ├── 4d4058340189172dbbb3d573c3aea41fa3b0bc02.nq.gz
│   ├── 529f81c09ef4d379d103f2e2c05f65d94491d32e.nq.gz
│   ├── 53c04828afe68135b7e52bda4fdddf0f1e6bfd88.nq.gz
│   ├── 576fbfe74edca8b764e5ccc79ad1208ae95dbefd.nq.gz
│   ├── 589a526924dbb34587e0198dc86b9051a9caaaad.nq.gz
│   ├── 59e95d6bc8cd41e32e75e0a764a7e6063f1c1a5d.nq.gz
│   ├── 5b3808d4b22c3dc95b5fa6c08f8b70e51ac1aa6e.nq.gz
│   ├── 5b500a05d433cf255850381513b1472554f3c3fe.nq.gz
│   ├── 5f05dee69b7bae7807de15538ff46e842024d19e.nq.gz
│   ├── 61681b621ca8cb126fb6aa4a8d93af8b89ae3854.nq.gz
│   ├── 650892c94b0297a16c8d55a4b30ef8fc267e8470.nq.gz
│   ├── 6d9dcd3bb460604713561604377f18d5e3bc8876.nq.gz
│   ├── 6da85f6222a7d743388b5d90ffcbabe7c105226e.nq.gz
│   ├── 6f2e6f3e9914e877e4877de1930f62fdcb469cae.nq.gz
│   ├── 7e98dedcf4d960bf75303aee1f5e1cd92d97e260.nq.gz
│   ├── 83618c91d4c00365b17d6302ddb0622d23a96307.nq.gz
│   ├── 83c64cc6cc56bfda1e86e34735597c4cce90c9f2.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 887f5acfa4589748bc3d4c4dc10b8903bad6c09d.nq.gz
│   ├── 8a5805e7f5a23202049ca619e5518ab8b895faf1.nq.gz
│   ├── 8c37511dc1fbd79f7d4a9b18ce7f99204d62bc11.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 95bba431f6ba9b757771a54095558fd0f14651a7.nq.gz
│   ├── a4c194ee99e7b0724521d15c54b33051af997b46.nq.gz
│   ├── abcb1911d79b5cf87f96d7be345e028c078c3e18.nq.gz
│   ├── ac3be9f0f8a19bce36301de56f081a68c756cf95.nq.gz
│   ├── b52b143c54abde14e94a535ebc70c8dd21eb6dcb.nq.gz
│   ├── b9d3cd57d3e9f2d08e1291dd01b22d7fb9eb8130.nq.gz
│   ├── c513b8c61ced8250ed62396d741cac5ac18ac425.nq.gz
│   ├── c93452631f3287b5725dbb26fd86034fc90a255f.nq.gz
│   ├── cd3a1da87896f6b886ad6b7b8de3c26bb9d24608.nq.gz
│   ├── cd7b01659a465cbafbd862ddc2173e51f1cfc0a7.nq.gz
│   ├── cf7cd98b70f6ff12b1e78dc4094390b8e41afec9.nq.gz
│   ├── dd013acdab749822fd8d2fce77c086775e7c5135.nq.gz
│   ├── dd8f885da823bbab49cbcb2b75c68660bd2ba9d0.nq.gz
│   ├── df4a10c8cce114f4220626a5a4137b4d01832747.nq.gz
│   ├── e0a25673791a9a05c3e2abead90997b85e36a9a0.nq.gz
│   ├── e45b4901cfa83ebf64f6afd19219784da8ea4c74.nq.gz
│   ├── e4a686b7151d207be0faa8cb84b2c2b8c045d009.nq.gz
│   ├── ea6d13abb4c87b4b95aca7f2b275ab6d28d6d0e2.nq.gz
│   ├── ed41056a25ad96772e04414cc403d65a863971a0.nq.gz
│   ├── f16a2301a0c78b9bdd40d402489e7da59ff1bccd.nq.gz
│   ├── f327c7a905faf7c103ad8e1effc5492ee7cdd59e.nq.gz
│   ├── f50812ef138c2d1c5d81f1837ab2a05875d12e17.nq.gz
│   └── fe7e3476da74b1776d66e63f8668726f08ffd9d3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7d3b434e9bfd7a412a30ff9ef7750c515e3089da.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 71 files
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

[block/chalkline](https://github.com/block/chalkline)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
