# Repolex Knowledge Graph of canonical/opensearch-operator

RDF knowledge graph data for [canonical/opensearch-operator](https://github.com/canonical/opensearch-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/opensearch-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3148defe3948404791cbe96a2ef261a5925374e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3148defe3948404791cbe96a2ef261a5925374e5
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d2358916406abb45c55a3fe3e19530701a9e04.nq.gz
│   ├── 03ff40dbc2229ff95dd110d31b73d4ceeaad1286.nq.gz
│   ├── 065ceb5d0155bd744581c54cdb83497541093591.nq.gz
│   ├── 07147d636129b3048545ff09371cf03e718cebca.nq.gz
│   ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
│   ├── 091422b20aa103b92e8fc9ab4899928318ea4900.nq.gz
│   ├── 092d7d05c7b8fecab3c8ab9a333a131aa4c78b77.nq.gz
│   ├── 0ab5bcb63895b9b415ecc0b45a152ea93ad1c7a9.nq.gz
│   ├── 0b6719d4e4bb8286f081ecae25c8f5b85f423244.nq.gz
│   ├── 0c2958d2cd1a885f2590ac56995bb792eb0d753d.nq.gz
│   ├── 0fbe418867af69c8d5c738d0b333f3448dd645b8.nq.gz
│   ├── 0fc73e204eeb2dba82745b39cfe72d63c26fa8f4.nq.gz
│   ├── 10c7ce51b798e8965ae0ed1e71534761c5f566c2.nq.gz
│   ├── 1104995208d902f26e7992982b6fe4b9d6240ac3.nq.gz
│   ├── 12a7bca161df19a5dcab99febbd6826ec385ea5f.nq.gz
│   ├── 12f557ffcb6a91ff4ed02adfed74e50abb624899.nq.gz
│   ├── 13f811377cacbba0098e42e0156a832d126c05f9.nq.gz
│   ├── 15a78cc947068237f94cfd374a6ba7cda9d4e798.nq.gz
│   ├── 1636a9d097b0e47583b9005de7ecbe5ce975f1e1.nq.gz
│   ├── 1652fa5e7d417d6e1b4c54329828be9d8e0f8a5d.nq.gz
│   ├── 1667b6ee5d0f9b07e8fda2b919e5046ab35ff2e5.nq.gz
│   ├── 1714ca8ff72434f4381d88e95fdbe666638ac2df.nq.gz
│   ├── 1736be35378ec8510cf6ff206c7862e67f1a41db.nq.gz
│   ├── 1773e1f53e36fd982a84f8142a9b258b247f1d5c.nq.gz
│   ├── 1a3f3789c10ae63a6114401f1167395efd25a3f6.nq.gz
│   ├── 1b0f3f295cba9692ca514797cf32459d0f911318.nq.gz
│   ├── 1d4cc7dc4e14969349666e1af7db8c45e5928c38.nq.gz
│   ├── 1e605befe9c78e0a141ca42b7c7784d0baa85a3f.nq.gz
│   ├── 21b28ad37dd127505e7f18a4bcb429f1014556d4.nq.gz
│   ├── 26facfe885e25deff270e7fd14700a2c8888c3ce.nq.gz
│   ├── 2bffd2d31754ba6ec54064c392d7d6f9f5195720.nq.gz
│   ├── 2e68412daf3423f5c4d2c11d7afdcdd2f08969fb.nq.gz
│   ├── 3006f13e199b573708dde2114878ca4fa8071aeb.nq.gz
│   ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
│   ├── 307b5f2ec4afd37039c61500decced8f538bc94d.nq.gz
│   ├── 31d4cd40887f6b6581ebb0d7a865fdd005d535f5.nq.gz
│   ├── 338ab4842bdd23361bb4c9a91c2f5b8b87574948.nq.gz
│   ├── 36c2c6f27672ca8da82c73e43598aedb3b8f2147.nq.gz
│   ├── 376701493e3a99ebfe393ac507063e3890b744bc.nq.gz
│   ├── 38b4939cac08682cd0d844a0abc68ec3db93fbce.nq.gz
│   ├── 390c3a0bcce25ae62b527b06d3ad5ec3f0f2edf1.nq.gz
│   ├── 3ae7cb0059225a2c57fc3c7147761312a8465be8.nq.gz
│   ├── 3b403bc30dcafcfca1f35e9e1f69214d23c7674d.nq.gz
│   ├── 3c9c5ebed0810e28a60b1fe1748f989ff5c0b4d2.nq.gz
│   ├── 415b19fc3623413817e5ad457fcd8f530c06047a.nq.gz
│   ├── 417faf235824826d647f5358ae68e02ab5e71d52.nq.gz
│   ├── 428e6a4b5be287c31c496b72ae2c98b31b1ce07d.nq.gz
│   ├── 4892df051dd87a931602ffc2c34abf5b88f42f6c.nq.gz
│   ├── 495611296d495bb8f294b2ec7cdf6aa50c8fc666.nq.gz
│   ├── 49b78af15d7afc57b65794b05319f2b6ab8279b9.nq.gz
│   ├── 4c654f7953266676bb238678a7c9cac95c2a3871.nq.gz
│   ├── 4db53dfd8d45be940cdd0f9bbdd1e78688691788.nq.gz
│   ├── 4dccecd3e99246342dd9096d4c9bd993ebb9bb41.nq.gz
│   ├── 4e782f9155fbb4f489951b8980e8aba462e1f145.nq.gz
│   ├── 4e88d73f38392a91f3f4068fe10dee7e9d7f069b.nq.gz
│   ├── 4f33cd70edebb15368ca437f04414ff820fde9b7.nq.gz
│   ├── 509a722536f7c13e7b21bd1d32583fbb56c82384.nq.gz
│   ├── 529fb85b9b04bb3ace8a97f66114b0aea4c48c36.nq.gz
│   ├── 56be7042a6a06a6a0773201b435eca27aedb1593.nq.gz
│   ├── 57b945ebceb47df75cc6a8d56477b0cf14ed07f1.nq.gz
│   ├── 58063f56ef267bff0996b78b791f2c14154f6f58.nq.gz
│   ├── 5a15145e4d56fcb861307fa205960a5e6f185908.nq.gz
│   ├── 5b631f5f2d198be1bcaa73568d94aa96ea7041cc.nq.gz
│   ├── 5d8c7c0e4fc04569ef0844337b7934a9ac6572fd.nq.gz
│   ├── 5edeb42478021d5ee67671bdfd36ace024cfb712.nq.gz
│   ├── 62119fe3166cbad16466b2262cb214bdf144ffe6.nq.gz
│   ├── 648d94ee269efd5ed105ead1501dd9b0a975ca2b.nq.gz
│   ├── 64c835512bdac7fbb68bce17163722bbe01b5db4.nq.gz
│   ├── 65bdd5c91d6186e447dc5d318a0b135b61fc0a9b.nq.gz
│   ├── 6610de985be2d63ddda10ba307a126d56433f65f.nq.gz
│   ├── 67990443519d06976746da90913f53b9ff0ba754.nq.gz
│   ├── 689bedd6b8f660ac80bcdf19f8187ae774533d6e.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6cff940e985ae987b3fab5a3e6039ff8851f15bf.nq.gz
│   ├── 6f538f46eac0b71024a3dca430fc44dbbfab8f15.nq.gz
│   ├── 701ef829e6581cd46d70ad91c0cdb0c83c2b3ffb.nq.gz
│   ├── 7207cb8f22df74b9424a5a9a7a4a5cf5e742521c.nq.gz
│   ├── 7287e43afbe43afc6cb4c39b2993543355df7289.nq.gz
│   ├── 72cc5fccd06a94cac20b0ddd27054b7947c84c44.nq.gz
│   ├── 738011e88726a3a81b5acf2c09039d5fa678553c.nq.gz
│   ├── 7577cb45eceb4943bfbc23e29839b0a3ba3e3bea.nq.gz
│   ├── 76154b85647ed01268bc45d0cafe859a11e135ee.nq.gz
│   ├── 76624132be8a380c96572ab32dac1b40cc005134.nq.gz
│   ├── 77b3dc1dc9ef23524b3f34db93389e5ee8c79e7f.nq.gz
│   ├── 7a7970e0e939d4cabdc93d985ab33c294d4b40ee.nq.gz
│   ├── 7c15436e9a927d259753b7a1c14ab58f651625fa.nq.gz
│   ├── 80a77d165ff7ea6ef4a91d792f18ca4c4efd9b93.nq.gz
│   ├── 80bab4b025dead24f54dffd926012cc51f00d5bb.nq.gz
│   ├── 80f8d3c3109f6d71ad039ef2dd970c10833066bc.nq.gz
│   ├── 830fb37aa73fcddd058b3f11b15916fe022a4b47.nq.gz
│   ├── 83638f364c618b8887bdc69a70a317b8bd4d01fd.nq.gz
│   ├── 851267e7057887664e2573c64b383ce640e17376.nq.gz
│   ├── 880f29cc184105c371f2f36d0297b10647ccb82e.nq.gz
│   ├── 88327b4f768565768b04c66571099e2fe92a9b1f.nq.gz
│   ├── 88841c9ac85758443222f15770d200115e292e0b.nq.gz
│   ├── 8a12d5c466d9b0ae1d76be4312077fee888dacb5.nq.gz
│   ├── 8b7ad17f2c23848c46a13f4c55ac32c88acb5b56.nq.gz
│   ├── 8f6eed89b9fa4f913f61bafc79a480c10c9befe8.nq.gz
│   ├── 9129d38f5d378a2584c5a81ebd8ad6f1fe38da89.nq.gz
│   ├── 93472e589b3e514c0cea4f3fb9af13ffce2220cc.nq.gz
│   ├── 9381fc8c35786301e7f4f97de4b35d49898bf004.nq.gz
│   ├── 965e17bedff61376b7f48d661dd711a209a6e23e.nq.gz
│   ├── 9ad50e3098219bb1d69cb66bda562994c8628ece.nq.gz
│   ├── 9bcfcb443da2c160ea38c32c025b02aed2c59d1b.nq.gz
│   ├── 9d4c6ef4948e5e036d24af8bf00698c044191d8d.nq.gz
│   ├── 9d796c6d3e848dcb095b8bfb2c11d246c1724d63.nq.gz
│   ├── 9dd07ef86f9d4c11d8e6430abcf1f943af16eca4.nq.gz
│   ├── 9e5179f4c101979bdfe728d1a7157f3fa2f1c939.nq.gz
│   ├── 9f0cb45574349d1f27ed7a644de7d1e2ac887029.nq.gz
│   ├── a099082afab2bbc02b727a2cb92087b414a698b7.nq.gz
│   ├── a0ebb60a18900d4d95043ab4b362e7368ba2e082.nq.gz
│   ├── a1102bf6f55868428af6d7035f7d674b2fe73033.nq.gz
│   ├── a1591a6720e9ec4b9d898265f976722c22383742.nq.gz
│   ├── a5b6a704ef8fbdd86e48625952fba5992723a0ec.nq.gz
│   ├── a5b9fb0d321467fafa36e8bdf4eb287ddedfc1ba.nq.gz
│   ├── a7650a2f8b11628fce5e69139f6ee4fd65745030.nq.gz
│   ├── a9305679f3e29e644480d7f96da04b091f57d1d1.nq.gz
│   ├── a9c8fc567687c127e72fa29080113646202eb7e5.nq.gz
│   ├── aa7c1c5217513f0204c3dee1dae9908a093de230.nq.gz
│   ├── ac9aa2374f552c83061ae1385e391fff208c77b2.nq.gz
│   ├── ad90bfede67ed548533e3141dc07d95c78f34e74.nq.gz
│   ├── af01fec84e5dc7d8e3eb1b5184db45e224a36b88.nq.gz
│   ├── afa5e093050b8edf192b627ad9480a6d3d3da20d.nq.gz
│   ├── afab36a1490c48e7337a1fd5ea581dd9b820f92a.nq.gz
│   ├── b09404ae6f93e66ea326ea68268b6c34c7a62fa8.nq.gz
│   ├── b096ee2cde556c3ceea5c01d4fc8ff3823ce9101.nq.gz
│   ├── b3059f169b7262aa0e8681e234820d462dca8e47.nq.gz
│   ├── b322a7efcd8dc741ab701934a1d64bf28d7e3b3d.nq.gz
│   ├── b405982b24885a83ba91e6ceaf39aef5c20a2260.nq.gz
│   ├── b4cfc1c5d132b87a71438ca70f5880820ea072e3.nq.gz
│   ├── b6651738efcc01d62e108b2f9987d7ecf6def294.nq.gz
│   ├── b6edd01bd7259a1dbb9dd93beefd1ab32e4409be.nq.gz
│   ├── b8064bd27bed111a1c02e408626d7e290bfa9fda.nq.gz
│   ├── b9174af6ccbcb25fa8b1cc6da09ace98d3dcc63c.nq.gz
│   ├── ba1be5e3685aa0ddbdf0e7295fc344f3a220c873.nq.gz
│   ├── bcfd7c87b111638a753c3f92c36b17572dee4624.nq.gz
│   ├── bea518e2b29566642b256d42e714d9b546049b1f.nq.gz
│   ├── bfb32681f3710a78f81c4528f76b7d0389bb6107.nq.gz
│   ├── c2f241544cd9a796a7e05e7338d930228c465f31.nq.gz
│   ├── c33445cfe19cf7ea8a02ac338213a24c362e36ec.nq.gz
│   ├── c35d9e155da9eb29b3bac8f8fc4a1cbdc4c7f3ac.nq.gz
│   ├── c61632ddb0628629561a82afeca6550e4214d352.nq.gz
│   ├── c6a7d96b03fd52bdd8029d7ccea7bbc1024a2075.nq.gz
│   ├── c823dbc3578b14aa5c87adece1fcc9c6a4893d46.nq.gz
│   ├── c84ef4d4c2afbf2bcc5d88c14431070bc4cbeac8.nq.gz
│   ├── cb269c62f1102087540f264191c2a135798cca74.nq.gz
│   ├── cb3832e0c6c7c9a464efee2926a1531ef9781067.nq.gz
│   ├── cb81f33587c097decf7e47b84b2858705cad85f0.nq.gz
│   ├── cc2af0128cf5e6bb3c1401851ddd08d7851a9329.nq.gz
│   ├── cc8df2e8f3e7d50fa59b124c47ee66c62bb9c1e2.nq.gz
│   ├── d00491fd7e5bb6fa28c517a0bb32b8b506539d4d.nq.gz
│   ├── d0f27acd3c5af66d22902603d02e09cbeeb4435f.nq.gz
│   ├── d28630d08fd607ef621345fdfe899a9d53e12c11.nq.gz
│   ├── d386166c318426c75374719d1a3cce3015f8e300.nq.gz
│   ├── d489bd49db69b099970e9c6b575e7913f2b5c2a2.nq.gz
│   ├── d58527d445d81f7be5b8f74c7cbf1938476a0a32.nq.gz
│   ├── d5bdae6e6981eeaebcdeaf1fe714daa77b0de443.nq.gz
│   ├── d6c20854927b2d61e3f893f2ccc8627a667f7528.nq.gz
│   ├── d767c2be8de461bcaef454de2d0ef9ee3fa4f25c.nq.gz
│   ├── d9cd9316c10abfd645eed0c4a5b20dfede90956e.nq.gz
│   ├── daa468e4cf5ce54294538df29b53e1a3d26c0fc7.nq.gz
│   ├── dbe07563f1f27847c0a39132a51abb31292617d9.nq.gz
│   ├── e05cb4073e1935b41385de2e5eb55aeddc5936f2.nq.gz
│   ├── e24f9af0f071dff481f35ac77f85f52eb86c3448.nq.gz
│   ├── e3e37c0d20ee3d263a3a3949b84b0d6a246df9d3.nq.gz
│   ├── e6007ad17ab527fccb700a8d94071104d6856cd0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a1b06e637f756ff1f30a970d12ce2ba0304bdf.nq.gz
│   ├── efbef60e6269b1733b90c3f893e4fdd66c2c350c.nq.gz
│   ├── f094be4a34baf5a20f67e30e3b313f049353f65d.nq.gz
│   ├── f0b536aedd445d8862ce33268fc9733c37cfcb57.nq.gz
│   ├── f1ec304c9e148fea7b953db78f903ffe0538be81.nq.gz
│   ├── f285f599dfad4bb2623a75a3538884a2f41fa442.nq.gz
│   ├── f2ce50d960443bd737ad65b0988dbb9104bebdf8.nq.gz
│   ├── f3d28caf89081a6f2ce32ff4b634e2aa726c8355.nq.gz
│   ├── f4a095867e0afcde5c991d992d9bbbf88b40ea46.nq.gz
│   ├── f722f50a2a5783f3022bc7cba5b24bf213d9b3b7.nq.gz
│   ├── fa89e9d7f0a34f12feec51eb28b9208c96d0494e.nq.gz
│   ├── facb66819af7ce1aa6d4a697626f5dcbad76b204.nq.gz
│   ├── fb82a1ab57cf32c81e7461ebcd73605bd9e7018f.nq.gz
│   ├── fbc5867d8c420961a6027bc432a3b873998fa76b.nq.gz
│   ├── fd11616b550860faf477976b2cfa47db71c58bd7.nq.gz
│   ├── fdeb94efcbbb8c566643ef286410eaa00b932b17.nq.gz
│   └── fef743e2717b01179faa06ee4e306244c0ff63f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3148defe3948404791cbe96a2ef261a5925374e5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 192 files
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

[canonical/opensearch-operator](https://github.com/canonical/opensearch-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
