# Repolex Knowledge Graph of sunpy/sunkit-image

RDF knowledge graph data for [sunpy/sunkit-image](https://github.com/sunpy/sunkit-image), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunkit-image
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1effa5d75687caef34e58dd96ef8489c411bfa25
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1effa5d75687caef34e58dd96ef8489c411bfa25
│           └── chunk-001.nq.gz
├── blob
│   ├── 00589591554cea4688f315da7745b4fab2d9fcb5.nq.gz
│   ├── 047c6b5ad931626222e80f46755fb792b2f24daa.nq.gz
│   ├── 065fba13059d9cc52b12a04d76e13dafcd3cf7cf.nq.gz
│   ├── 06c60a050a78e5e3431ba30478844ff995650160.nq.gz
│   ├── 09c5b461db66bffa3da4784f9203edcd8fc8ff5e.nq.gz
│   ├── 0b2af96ff104564deae10a599080aeb41b5db93f.nq.gz
│   ├── 0b8728abfcb2c62ffd2652473301b4f8f4bb3705.nq.gz
│   ├── 0cb778c16c846e4bb9ce10e14ba306ae8a9e43be.nq.gz
│   ├── 0ea8c1114b450be1c8f113d77adae2f69ad6927d.nq.gz
│   ├── 125005edcad6caa1f2fc7d94bffe6868ac61606b.nq.gz
│   ├── 147292462a62305d28840c5975541fdbc12dd79d.nq.gz
│   ├── 15f5b35f7f499a7ac9e8c8d8e1222aad1c2f8b4f.nq.gz
│   ├── 1845b1fe9a327341aec2b77e54f2610f4b5d2851.nq.gz
│   ├── 18ad95647e1f241abd6815950a06f96f15ec7bd7.nq.gz
│   ├── 19e9ff290c2b8528c6facce6d6fcba17958939eb.nq.gz
│   ├── 1e5e47a278d5447632591ca0875b91b10ea9435f.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 25476411db2148e478488847d6a95b9c2211cc9c.nq.gz
│   ├── 2566954ae0aa660a7b7fcc85d1290cbf36077e2c.nq.gz
│   ├── 26a580d3d04fd04bd476e4b23c4fe7f85986c828.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 2abffaaf504232b079205c124aecefd4a14b4b18.nq.gz
│   ├── 2b2b65e3efeb03dcabe20b009e9d44116d43c495.nq.gz
│   ├── 2c365ae8c251852ae3a3659ff70a105e76ff4d40.nq.gz
│   ├── 2d6e91c7f0eb1466fcd1bc631d6c3f3833fcc3c7.nq.gz
│   ├── 2ed0fb42c2a6440ff61343cd412936609e105b59.nq.gz
│   ├── 2efb8c384ab2a997dcaed13bd5efe6cd78d63669.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 39b25e77c0f5038d757c854a5c6470812006bbf5.nq.gz
│   ├── 3c5908a51033d319e9b6561b8ab3cddb8c285021.nq.gz
│   ├── 3c6729044c5e1a36f1f1ae859be2991b386fbf91.nq.gz
│   ├── 3c6b29a7dc146af7b746dfe0d1af65e68af05a02.nq.gz
│   ├── 4140f81cb90d8a80e6796147867fc4f1a32df8e0.nq.gz
│   ├── 42ee92ed0c8770e29575f4b3a2abc241f48c6f34.nq.gz
│   ├── 482d4a81ec39a9061d57e22e4f466f70773aeeb5.nq.gz
│   ├── 4df69be9a4e82fccc8357d9c5548cd1072aa69e4.nq.gz
│   ├── 500f397a23aa245f949b81ac22177973a53b7e6b.nq.gz
│   ├── 5225cc0c9d9ccdbb4de3e36a1011ff3fa060bb6a.nq.gz
│   ├── 5293956754435e0f95314665ab83485f6367baf2.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 56ffa9fe8bee2cd341f6edb806423184eddbb4d1.nq.gz
│   ├── 58574cc4aeb44a629a424fed7f7386a6dc37a252.nq.gz
│   ├── 591d65a0a5d97578474755a0b91e795c10051a0f.nq.gz
│   ├── 5ada68e3c926976b418041ff90f98bd916e0aeae.nq.gz
│   ├── 5b1a1128b31e228b12aa7d8e7b192cff565cebd0.nq.gz
│   ├── 5f3b19e45b2d6ac127147cc6c3123e880ffcf338.nq.gz
│   ├── 600e8c0a24a4150be96c9c447de46119280a8e2e.nq.gz
│   ├── 61b2d1b7069c8f53f6217056588535dbc4e6c611.nq.gz
│   ├── 6435319ded375988f17cf5aa485fbe0166372f36.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6890bc29b654e742c8ef0455cc88b9b0fc379c00.nq.gz
│   ├── 6a85aeaa37557d37d190edb0bf480852c9dcbd7d.nq.gz
│   ├── 70fc16d5121cf2d34517092608cb47f640e42d24.nq.gz
│   ├── 77631cfe874f2f4c6ca64c569fbc4aadd5fceca8.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7cfffbc5b867567d71d4e4ce7e9f67b63873b7f2.nq.gz
│   ├── 7eff63c7038fb3d8e1c3b8582007419f1c6e7913.nq.gz
│   ├── 80a0dcce282be15137c86017d7fff8067b53de78.nq.gz
│   ├── 833a0447a914e629c4faef637c41ab8598015cbf.nq.gz
│   ├── 873a150055b6b7ade615e5fd6cd753f94ab14b8d.nq.gz
│   ├── 89d4dd8a3ba6313e95500048da00594ac66f05c2.nq.gz
│   ├── 8ade76c62ea06d4cc8cda57fd8a111da48df9350.nq.gz
│   ├── 8b47f3567f74a47ee5e30c38bc23a1b6c12800f3.nq.gz
│   ├── 8db7cdb2b5d711fc90b38119df51a2c46b43ebd7.nq.gz
│   ├── 8fcd3990bbb17a8aa989df41f20490f53dfb3e0c.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 920b7f4b0538d48e0f78ab9fc9b9414cd2d154f8.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 97216a5fd517a65fada6b6ed373c8740c2ab1541.nq.gz
│   ├── 98a1fb4180f4ba0bd0064095092a7a3bbc5e5729.nq.gz
│   ├── 9ab89ccc97ad384c3c2dfaf6a21575987591f66b.nq.gz
│   ├── a16f14cbe02dbb22bcd33c8a95e24b0dd6db9fd3.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── a3744108e145943a8e88e66c39e8594996b67e56.nq.gz
│   ├── a5c6d69d174d2be981f0f87bf0fa886105b66864.nq.gz
│   ├── a63081cb65e675001cbf8ad0c0c3799bf8596ae1.nq.gz
│   ├── a6782492448da4330c4d9296641fe6f750896df4.nq.gz
│   ├── a69bd9549d8208f3f63e2600e5d5d7f4bb26b585.nq.gz
│   ├── a9ff69b6b17e854bc5f64fe72f712977a5b4fadc.nq.gz
│   ├── b2503eaa484636db40afd62f90d1ec11da2886c1.nq.gz
│   ├── b4895e2aa7b893ff73e44871bd5e8bfc9fb7d324.nq.gz
│   ├── b4936d960deaa399a1442d2e7a9afdbe75b135b5.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── b7abaad4dff3a1cb0bc27a7c4f2a2ade26111727.nq.gz
│   ├── bb16210c70bef4e012e9aaa25df006d9508e5285.nq.gz
│   ├── c30a58c48c8ecb6164c6dbf8b4f1d101abc4f145.nq.gz
│   ├── c31dec5f5b96e15b942be99251f6c7bd2a91f633.nq.gz
│   ├── c404117bcd61b6288ffbdf20a36e1bfd95699d9a.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── c8d7e11a4afb03b0f6bba22e190a51366732fe0c.nq.gz
│   ├── d0c4c1f13174282ebcd4b1fcd189e1938f154179.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d569c5a8807513f7ca48edbb81c19c1c0eb8fffe.nq.gz
│   ├── d56dcfc8572a7e120411cae5543506e2119b22c2.nq.gz
│   ├── d620fc83f95055da7aed20d8acb2e37263292823.nq.gz
│   ├── d6fa55441e898bd68b2c7d0ecf29263a7d1595fb.nq.gz
│   ├── d9bc2d35aacf7f116d56aed1b9f3c53389e20374.nq.gz
│   ├── daf6ba58bf79d7f8d34464a6a4d95a1dcdefcce7.nq.gz
│   ├── df810cf3bbb11db37d98c7343a37ca237d9edfbc.nq.gz
│   ├── e06e19ae8ad7b49fa4d8653d09640ac228cacfcc.nq.gz
│   ├── e0ac518a029e1894f8624f6772b45fced6511535.nq.gz
│   ├── e34203973e28138ae4b6f18601402813a25a48b5.nq.gz
│   ├── e38b3a8dc183cbe2b71aedbaf793b8192981ce43.nq.gz
│   ├── e4cadb9903081161a3e72c61c32cd41c954adfc5.nq.gz
│   ├── e556a9aac5e0f9c5a2c2a97c1853ac534b28c6fb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f28489a12a02fd7b0ea0dbd002c8085dd84b93.nq.gz
│   ├── e81a213b19531713d6fe7eb7a3dc635b372397c9.nq.gz
│   ├── e986ee94be6f00d6217f97aa1df1ae1772cdf669.nq.gz
│   ├── ea6c37402c25aba3e178567ca65078459df33671.nq.gz
│   ├── eca5530b35537dee60366085d375c6021df36edb.nq.gz
│   ├── eec9052d74e588e2a6ecf5c230b869b6aa5757a6.nq.gz
│   ├── f3e64615fd285f7c0c75544db01b3f23e8ac0d2e.nq.gz
│   ├── f4c74ad11971c0b3625b17053ac7094768850fd6.nq.gz
│   └── f6be0171b1d3d92edb5d51f85fd2d22d578b1712.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1effa5d75687caef34e58dd96ef8489c411bfa25.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[sunpy/sunkit-image](https://github.com/sunpy/sunkit-image)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
