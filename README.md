# Repolex Knowledge Graph of scverse/gatac

RDF knowledge graph data for [scverse/gatac](https://github.com/scverse/gatac), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/gatac
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 87575e865c288c70d577112949b6dfb65b309ef9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 87575e865c288c70d577112949b6dfb65b309ef9
│           └── chunk-001.nq.gz
├── blob
│   ├── 005e844fdafcc22b6704d62d77a3ff80af7ce05b.nq.gz
│   ├── 01da12fa9dd858dbd1a3f87064434d1713af0c6e.nq.gz
│   ├── 057ee487a911ce0c2c83d182e67c68e6f8b0fd80.nq.gz
│   ├── 0622763e7e52475e98ab528f75341db8af054e3b.nq.gz
│   ├── 091475d5394edeed5279b64c56cec0930b15bc95.nq.gz
│   ├── 09943c656e9aff60314d6b5bd1c1f1ff8bbb2370.nq.gz
│   ├── 0aff1dfc0b24eb1b228f41f7b5c57400a01c58db.nq.gz
│   ├── 0b9b2f57e08d3c31085045d58214145f4c5027c4.nq.gz
│   ├── 0bb60fdea8b180d05740ae42f9eaba44e965e277.nq.gz
│   ├── 0cc251dff0d69a3f0b6593918612a4f49d55b2f4.nq.gz
│   ├── 10af0bbb867468f95dee0ad9ab77e5858dca484d.nq.gz
│   ├── 11ff7d177530f602eece1572336886939a143dc6.nq.gz
│   ├── 12b95f45f7c60597f2b19a7532e9a78c9720b452.nq.gz
│   ├── 12e528f12595d2a5c22399686f3b827bf7bca2e1.nq.gz
│   ├── 14a6e8fbf8fcd0ebdc5335ece0c5804e9f282b3d.nq.gz
│   ├── 14cdf12e042563e23ceb0a533162424969a93105.nq.gz
│   ├── 185dcee81875ecbc9f7b26e4c07a0bc9540d125b.nq.gz
│   ├── 1a3328e8f12a50b936f876da6d4cd738257b08dd.nq.gz
│   ├── 1a665d15b8a293e17022117d46fd15ca71c23967.nq.gz
│   ├── 1b1afd7728947c913e95ebbac8c3109d24e6da41.nq.gz
│   ├── 24b19aff2b7418c9dc1c7d769013a464a97fc1c6.nq.gz
│   ├── 260a5a22b20a659e4752619c5c50131613d9114f.nq.gz
│   ├── 279cd0d9ca702b428efc55202c1eb8a7b7af6afa.nq.gz
│   ├── 2c883b8b222bbc64a2d5fed0c3ff8147886da8b3.nq.gz
│   ├── 304372773e4058d775c18b944ff8fd7332f22810.nq.gz
│   ├── 31ec6c21e941e7a78a2d418c48456f5a149ba0aa.nq.gz
│   ├── 320a820c7b3c8b331fe3c8f86baa3679c86583c3.nq.gz
│   ├── 32a6c0b4aec2db979765d0eb2e0557d7c956a2cf.nq.gz
│   ├── 332161781416835a622c262d2a1efecd1268c4bf.nq.gz
│   ├── 3321fd2b3a5272436e6ec187f8f93ed80f4f2861.nq.gz
│   ├── 334e0a625aa3b16c98cfe5d5b0f2832956b7ea89.nq.gz
│   ├── 346d7ba445d8cf4018cb8602ddd30cc4ec9d8141.nq.gz
│   ├── 35c2f53545dd18fdc31728206c24a73051f2bfb8.nq.gz
│   ├── 35e57ae63b71c0f8486d138a234954d6e4edd90f.nq.gz
│   ├── 360d3c39bb70a77ed8c5d0e5dd33e40b4840d5e0.nq.gz
│   ├── 36b61e7a90199c578587f6ab675cf9582ea56f99.nq.gz
│   ├── 37d7f373e6ad08224bd80833164376c7b5559795.nq.gz
│   ├── 39443b3c0afdd43c9ad19064ce72b21040e31926.nq.gz
│   ├── 398a04ceccf09dcaa480dcb311b92b552fa62509.nq.gz
│   ├── 3c6614be4311419f08abf23900d5af3f2d90d40c.nq.gz
│   ├── 3cd9ab5d8ac34a1430905a40155144769a479866.nq.gz
│   ├── 3d2fb5888560dbd906d22e1c344aa9b63dd3d750.nq.gz
│   ├── 423d54a223663bb756fbd1ccce970465c4d0144b.nq.gz
│   ├── 4453a6436b4c6d58334318c5de02bf2c40e041c5.nq.gz
│   ├── 4971195bd50ca942f21b0bda2748c397f1613dd5.nq.gz
│   ├── 4cdded5acfa9b99bdcf54d31646909ac99bd4fa3.nq.gz
│   ├── 4ce6d554a2860c8642c60b7e6ab9a36833646bbf.nq.gz
│   ├── 5010ff6d852f624f44b99407548d1e954ac5d961.nq.gz
│   ├── 50d983ece9cba8a3fe068c17dda51e272b3e696b.nq.gz
│   ├── 519e51f13ab9f4aaa349a50a8f0a26ed3ec5aaf8.nq.gz
│   ├── 52ca333c461dadaa082fa84d1e1f9cc406ff36a6.nq.gz
│   ├── 539df5ed5c3e6522a4306900efa572756189074d.nq.gz
│   ├── 556d3fe0001f87ad653675da74b45b241eeda538.nq.gz
│   ├── 584b1623f77b80000c71a9a61de7d7461d8fd076.nq.gz
│   ├── 59cb392145b85cb7055b40991fcb92eb18b08652.nq.gz
│   ├── 621cbcd8e28a4d4008d0ab557de3cdf0761a099b.nq.gz
│   ├── 63a1a4160ff07281dfe8a6ba5b8aa7c16609e950.nq.gz
│   ├── 65ccb94c3d96edca3c2aa234bc433622e006a32f.nq.gz
│   ├── 71e6284ced1ae0fbd407b71c406db45255316fde.nq.gz
│   ├── 72957f770b0eb221b53311ddef38f1cc217938b3.nq.gz
│   ├── 732d8cda1e2e651991b119d1e436d425fcc65578.nq.gz
│   ├── 7502651544eebaabeff061f0c176a46d259b4a99.nq.gz
│   ├── 7587d65f8374015f87491870cae98f4bd7874896.nq.gz
│   ├── 7893f92fe8cd13190c1ed9ead0988fe7a55e9491.nq.gz
│   ├── 79a75160e3e74e3ed1ebcc001a384018bf69421a.nq.gz
│   ├── 7b2b1b56d4a4d4cc5dd24fff3685b8c24c722ffe.nq.gz
│   ├── 7bd5820383fe5b33eabf05f7867ccabbb4b02c19.nq.gz
│   ├── 7c7f1e82d38499e5e864585b717b8892b50b5a5b.nq.gz
│   ├── 7cb0ad755d70425b333fcb3fd74c6337e82904b7.nq.gz
│   ├── 7d62950239c4df3c7231240b81f73588c26af8b5.nq.gz
│   ├── 8115ccf456194d4f028000bd28dd7ff2954aac27.nq.gz
│   ├── 81b8b57b1e4ed9ff87dd69066bc2269f732ebe2b.nq.gz
│   ├── 825960814eb096975fb80a87d7e9973a4c88db07.nq.gz
│   ├── 84a609a1d785db79facbf1e4d208b54cc3910d8e.nq.gz
│   ├── 85d6edb2f481da18d63b41fc34be5690dce96088.nq.gz
│   ├── 8885e4c45cb2e8fbc9a1a52ed7913951c664f038.nq.gz
│   ├── 89ea1db1cefe913ba475f0fcc89033c1d45ee182.nq.gz
│   ├── 8a1bbc6b8d835a7735d4c40e3b8a41de780267bc.nq.gz
│   ├── 8d2c2e307e64531bc431151124ffda50d1c323f4.nq.gz
│   ├── 901764a41251d3c01f018289140c29cab7697e9a.nq.gz
│   ├── 90e3bc065d47e447595bf5976a074aef941f31c4.nq.gz
│   ├── 90f92c3701e082dfc84a2933b9cda16d6bf1bb83.nq.gz
│   ├── 925b2d3a8ae03b0fa7c6e79ce2535be4293f9b7a.nq.gz
│   ├── 927aebe699b3e8e11aeeab6028f9afae6a69f9fe.nq.gz
│   ├── 9499c145c4f4c7d00942f3f7a2874b1bae7de6c6.nq.gz
│   ├── 968465072e3107390c0d8503fe49b8301b6eb603.nq.gz
│   ├── 9754a68173c44c6a936b1eb8a60b1472a651d76c.nq.gz
│   ├── 98e5475d1f2c215cb4c0b9d456af974abe4b6116.nq.gz
│   ├── 9a20bbea3ee7baf20d09a45f54eedf9b3ec7e81a.nq.gz
│   ├── 9a7fe571e1d56462ba9d7fa7518ecef2071e8a2a.nq.gz
│   ├── 9bdda8fdacb487e98c438e3e26fc8fb607455c3f.nq.gz
│   ├── 9ffdd71d8da8b8ebc1e97731dbaa03b0875161a1.nq.gz
│   ├── a047cdef49558cebe4c0691f449ff5fd76ef972c.nq.gz
│   ├── a350993ac98cc9c3b81da9d570e092b453201247.nq.gz
│   ├── a515fb6351c7d1710e7f88d3b3f01573c921b8e9.nq.gz
│   ├── a6a021128d13bbd4f64a63e3218b5199611a6a28.nq.gz
│   ├── a8e988e7c27be95d6ff7576523cef83b269a694c.nq.gz
│   ├── a96f7b803b1771c38b853a37bce6de7cb75df29d.nq.gz
│   ├── ab5564ef69e911f1d9174a67f7f62cbe9a355197.nq.gz
│   ├── adb83af2337468606780be72d618ae2318579bf1.nq.gz
│   ├── b0b1a1656f65af1f6ed819b40d66c1642a5fd992.nq.gz
│   ├── b182a54c95adba4f2517726fa15af72316dce763.nq.gz
│   ├── b596a588732273de98c5e887ec8cd43ea5e0a036.nq.gz
│   ├── b5bd92d9bfb13ed49dcb43db7ff7e6b3eafe5e8b.nq.gz
│   ├── ba15cadfc02a4531ddfa4bff4c20092d46a02a3c.nq.gz
│   ├── bc9e1d44943a120121ea8e087aa7afbd8716ac89.nq.gz
│   ├── bfab80bd1469f1bc9439817da9a093f30098b402.nq.gz
│   ├── c2c6f32acc774cb562b0a5c089bd84211bd8aac1.nq.gz
│   ├── c8718fddf47f06bbe7d557ef2ac5e2746a373cef.nq.gz
│   ├── cb7b7044ddda272c457e1fa72fb849d613c172d3.nq.gz
│   ├── d144d3aca8fdb0f82fdc9f2c899a1b66f108837e.nq.gz
│   ├── d32c36fb822d4cc6505e7ec988b4fa98be2e90a7.nq.gz
│   ├── d6f5e286b8434059d7b757207c020a02e9aa0632.nq.gz
│   ├── d8fd4567bd18f0117cb6dd38526715cb5470aaf2.nq.gz
│   ├── da23c5856cee18133d973cbe0f955d898d29d681.nq.gz
│   ├── dc2ab73c9bcfb52cbe633e707dc8c6107f9b492f.nq.gz
│   ├── dd14ad7b79f4f42ba6b6738daf64fc2c91bfea4a.nq.gz
│   ├── e2a03a4cffd17f775bbed9181062d269bd58ca4e.nq.gz
│   ├── e32d5d3694bbbe289d7345774563ff12e3efa7af.nq.gz
│   ├── e3a845ee20186f2ea1c652b3bd3dd56e2c3bf013.nq.gz
│   ├── e4c0abe39c87ad70ccaeb3b120a2fb1716431e5f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80642408e4e47f6eb2346b16f911820258aaa4f.nq.gz
│   ├── e91971b3d53fe3d00146059782f1ea2977a037b7.nq.gz
│   ├── ef5976a45f46cfee5995baf5bbd30fb6671f9089.nq.gz
│   ├── f03438757592a70b9472452c14367c1f4eeb13cc.nq.gz
│   ├── f0ac9fb74c4a27679f6f1266d485fd5ceba20dcf.nq.gz
│   ├── f2adf8561cb0baefdccae1036c57820cb3787d66.nq.gz
│   ├── f32cb373a001440410f9f01adcc2a1d44d461d39.nq.gz
│   ├── f36081bd9874b01e0d91ca590fa0d570204cbf12.nq.gz
│   ├── f37c90b2deafbd319a66d9b584bd0fe1b9c0b4da.nq.gz
│   ├── f60da0243d637fe83c41b5a5b7e0523c78e6ce4c.nq.gz
│   ├── f7912ce7193c7b6cbd2634fd5956a623bff5b241.nq.gz
│   ├── f9684dee065c7182720dc6e8e957ebb6f9cd1396.nq.gz
│   ├── fbf4b4ea8e00cb11325a84da1c5f24f7cda41e44.nq.gz
│   └── fc771f715ef967a540e0b765c5ef301a99b7d27b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 87575e865c288c70d577112949b6dfb65b309ef9.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 143 files
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

[scverse/gatac](https://github.com/scverse/gatac)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
