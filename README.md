# Repolex Knowledge Graph of sphinx-contrib/sphinxcontrib-versioning

RDF knowledge graph data for [sphinx-contrib/sphinxcontrib-versioning](https://github.com/sphinx-contrib/sphinxcontrib-versioning), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/sphinxcontrib-versioning
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b56210959c6b21bbb730072e81876491b4e1371
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b56210959c6b21bbb730072e81876491b4e1371
│           └── chunk-001.nq.gz
├── blob
│   ├── 02353e59d6f12c163dc37dd621f306d3fc620099.nq.gz
│   ├── 0608b27b7d1c8b31b8ed64d0bbf4e53d944c107f.nq.gz
│   ├── 0b6fa21ef58dd81d838d2b21b98e78c1cf504d06.nq.gz
│   ├── 0b9ff7bd7007da19a0b34ef45199b8ec1c9ffa98.nq.gz
│   ├── 12bb93f8c991a6f3ae706bcc1f5ceced037dbad4.nq.gz
│   ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
│   ├── 20184e6b9ed8f29c52700fbceb89504ea7071b71.nq.gz
│   ├── 212aac27d23d285ad1e7db91c8fd2e4867d76d46.nq.gz
│   ├── 285487413c1b26b47c005b99b04de80b2c42b79f.nq.gz
│   ├── 36a8c1f0c96a8557f7b8bc5819928f0c52454792.nq.gz
│   ├── 3748a2411fd971f237ebcff56f000e32a2d19618.nq.gz
│   ├── 382849912e261a6a4549801bc393651b1839f6d6.nq.gz
│   ├── 3f8ca47e103af4de755b857d3bdf5dbc8d50eb25.nq.gz
│   ├── 422cf8c556f1d2081ac6a996028bacba775948e0.nq.gz
│   ├── 44146e681f4ddf3734dbcc8f5eb855dded4eb652.nq.gz
│   ├── 4837edc276d5851f9260eb31a7e17626fd20dd1d.nq.gz
│   ├── 4867db8ab33bb4f5f2645a2d7f8d93e35f01e6da.nq.gz
│   ├── 4bb0dc7f87ff2af3eab7eab7768dcf617f4ec72c.nq.gz
│   ├── 4bed9ba2c241ec7398d43c2edb6268dd2cfaaa09.nq.gz
│   ├── 4cbecf42c98de8c649387235715a3e521a521728.nq.gz
│   ├── 4d789e069f5629d39b6b42344ecb7c7914e2eaf9.nq.gz
│   ├── 4e3e891351a35289e1b5d9a77b2025e0d912611f.nq.gz
│   ├── 50cf74a0328c018b57f45079ff2e156bcfa53ba6.nq.gz
│   ├── 5d2653cd8e65f46c03b3dabafb9c987a218bcbb9.nq.gz
│   ├── 5d623a005e74de589137b52837b5246bcc4de072.nq.gz
│   ├── 5e0c1f358f3db893b3baa23a32b90a82c8493237.nq.gz
│   ├── 5e8dfaf5c26982d0fddbdcac258fbf61cd5a7d4f.nq.gz
│   ├── 6211974deab6729f017461efe2d193ee57a8b723.nq.gz
│   ├── 63a40c22b38956997bbe75897819a3214c0ffafd.nq.gz
│   ├── 6423db7a76ecc0278f9f1f5d05434d3700afcd7e.nq.gz
│   ├── 6d727a0ba2b4634c999c275a68e1a19ac5c45338.nq.gz
│   ├── 6e2cc8dda0940c74b1e9e8da8b27748f3828ca3c.nq.gz
│   ├── 709a390c9ab29b05adc6c3ead8c11ff04af59b0c.nq.gz
│   ├── 7ad94e2578845cef4ce84a92598086250a4b0bfa.nq.gz
│   ├── 7c05293ba38e92217568c996ed93fe1f435401d5.nq.gz
│   ├── 805a9f45d3b93844e54f929e845925ba874f1f86.nq.gz
│   ├── 856852a998f8952247f9711abf1bc7d45e132928.nq.gz
│   ├── 85c7658b6255e07a53d6d4614ada56aca3bb1e6b.nq.gz
│   ├── 868862a35550f7e460f31336edd582446021461b.nq.gz
│   ├── 8cf8947ce400f0ea2c260d722ebf735d37c16efc.nq.gz
│   ├── 8f3766fce33b7b02f47cb1b36a5b90dd76dfbe29.nq.gz
│   ├── 9615721bc041c64b1da81f72b18cf91f8f06f25e.nq.gz
│   ├── 9e7912b6c28aa5fb6fb15ea092331e8463f49e65.nq.gz
│   ├── 9ee2bab94fb32373f88b78be2c8868e09b1a4d5b.nq.gz
│   ├── 9eedcdfa219766afc05f5be57d01401b90e63d5c.nq.gz
│   ├── a90587d4fed10cb53306580fe4813c658e28fc3b.nq.gz
│   ├── aa3800cd89f19d18734d24f2a6cb0b648f5c572e.nq.gz
│   ├── ad6200783a5329bb4116d96d9c73d6aa99920058.nq.gz
│   ├── b1eb01ce1d4b84a74f699f45d032405ba080d09f.nq.gz
│   ├── b2133803781ce4bef1b5b437a5123303d4648244.nq.gz
│   ├── b258ae8804b1f21a96d2f6867696e07da834179b.nq.gz
│   ├── b2db91f43665c5d00a7b52d9ef02474f4d3d390d.nq.gz
│   ├── b7daa4471372d48828474a2c4bd2f4f47e1a3233.nq.gz
│   ├── c160580ac9e36c1bb6514a9227096a64f4eb7a44.nq.gz
│   ├── c607739ddfb8a8cdc6f0da48d92f16f20f93f816.nq.gz
│   ├── c8bf149c24296c8f49c62045d0e83367234319f7.nq.gz
│   ├── cc1807c35a3bed08453ac5614e05bf43ab4d564f.nq.gz
│   ├── d314c3ca24aaaccf7727e2c56bd9ea2413555842.nq.gz
│   ├── dac5f9b6ffc68c57149162ab5d11d4afddd61b97.nq.gz
│   ├── db71c5f99e69c05a6346149a32060c13d13de98f.nq.gz
│   ├── ddb5dbd834ee43304092e6592254688e6e7b92a4.nq.gz
│   ├── e35de39445e6bfa11ff5778fe36c52c0fded18de.nq.gz
│   ├── e52e8d2aed7ddb37c11c7be0db9fda9e3eab70e9.nq.gz
│   ├── ea2013e119a960a31b80867df47a98f2a759fef7.nq.gz
│   ├── ebbdf599fa7c9fb29ecb651d9562e3760ba9cab4.nq.gz
│   ├── ed14a5feab6aa52e18caa01087bc2863178eaa87.nq.gz
│   ├── f0a323cdbed0a7743b0b4c59e252538be3fde9eb.nq.gz
│   ├── f62ea3a366eaecc6270f84a59a112524af8621f6.nq.gz
│   ├── f7a25b3089ebbde51e57c5c46e18075467a73359.nq.gz
│   └── fe91a30ee3d193451d67d1e3725ffb2ab5617616.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0b56210959c6b21bbb730072e81876491b4e1371.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[sphinx-contrib/sphinxcontrib-versioning](https://github.com/sphinx-contrib/sphinxcontrib-versioning)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
