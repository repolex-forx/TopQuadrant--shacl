# Repolex Knowledge Graph of TopQuadrant/shacl

RDF knowledge graph data for [TopQuadrant/shacl](https://github.com/TopQuadrant/shacl), parsed by [repolex](https://repolex.ai).

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
lexq download TopQuadrant/shacl
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│   ├── lsp
│   │   └── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│   └── repolex
│       └── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
└── blob
    ├── 0087b5bdfb4e0e10470dcb5b8657cefc9a2c7ed9.nq.gz
    ├── 00f6d4a0ea1e635b119271dbbe5b6edaa38e0039.nq.gz
    ├── 01135b34e6ef6c18cbdf2134f5745e260993e33c.nq.gz
    ├── 031d13447b9d28c9cd53dcc839c84d5c7c6a1f26.nq.gz
    ├── 040b595d0fe1a05d883ba6049a7522df5366b27e.nq.gz
    ├── 045b207ee53aaa85438504ce975d06fedaa24538.nq.gz
    ├── 050a4a80f5d3f2c200fe61d02bfbf7db9ba961f9.nq.gz
    ├── 05580e8e421b7eaf6f5aad9e7c6d46ab6f9d7940.nq.gz
    ├── 05f936e4f4e5fbf75d291aa59796d123f051b1c8.nq.gz
    ├── 061a55991c0700588f063168268816d97c572f8e.nq.gz
    ├── 069ad950c2c34c2570edc38ff211694630cb12ab.nq.gz
    ├── 06dea52d27ff43548db9cceeb1d4e3e4e883d659.nq.gz
    ├── 07131290036d967363ad78f3de2a4d45a5ee9d28.nq.gz
    ├── 07c49d0f3048c6dc5c17990617cfc3495f230dce.nq.gz
    ├── 080f23e9351f2ca73b46d1e88edef771c2348d58.nq.gz
    ├── 0907c83f782a7a1cd6b01a681b0d7371412a87d7.nq.gz
    ├── 09294263297b6124bd13b50db17dd82437f9e743.nq.gz
    ├── 094781ab3e7ab799a2ee3b697fdac9e38c032191.nq.gz
    ├── 09535eb1583c1ad2fc03d0b8f515d5df4cf90ec8.nq.gz
    ├── 095981c5a6af8c68af1c472fec9f6636586d2072.nq.gz
    ├── 09b3e045c87fbfc3eb780c85413e0415cdec259e.nq.gz
    ├── 0a7a43abdcc7543dc6c1ce03b63988e85b3a37c8.nq.gz
    ├── 0b2021ab79ca493a356df407849da6f8bdb9a3d3.nq.gz
    ├── 0c5e194d39c3df25dcbc04a1b970f4a6baaad6b3.nq.gz
    ├── 0e58560ee87626c29d221075bcfa6be39edc2892.nq.gz
    ├── 1080e3409f6c5cb89c6b4e77b5a6f4fd4b38f594.nq.gz
    ├── 108eeaaf7f09bec444e9376e7d2c4bc7096baacd.nq.gz
    ├── 10f643965dbd5649f58079726e3698fa64f47abc.nq.gz
    ├── 126abb328f631456b73f52364a8a86ddffbb2c7d.nq.gz
    ├── 12c41048cb50ce6f14a8f0783756833deab37770.nq.gz
    ├── 13c518fd7b9df962304e04a1ab03ca76dbdded08.nq.gz
    ├── 1446f27f900371ef3553799c7ade56b7c5d082b2.nq.gz
    ├── 147c08d4ac812186ddf925d9fc403a6b45b51f72.nq.gz
    ├── 14f51d525df90b7dc0bee62576ac33cca8eeb5c8.nq.gz
    ├── 15c4c5f79184de3e0673cebb33e63b7a3778428e.nq.gz
    ├── 168d7779f3840b6784aec8b8eb151dd34ea7c1ba.nq.gz
    ├── 16dad16cb8a3bb56df42bc2732d14b9094bc0e4b.nq.gz
    ├── 17926aed3c9f26d1b72fd174165edab2892f2ff9.nq.gz
    ├── 17b0cc01456dce801c8fbcd31b4ca14feb9cb1fb.nq.gz
    ├── 1a8ea9a48592a018722c3bab0d45563f65828b9f.nq.gz
    ├── 1b7114d69cfbc2b257d6fa6fe1228dc31571c067.nq.gz
    ├── 1c88f2a56027e6a9987858acd2d99196f3961456.nq.gz
    ├── 1d9a20821cc7fb64f6108175b6fefd6a6f76b462.nq.gz
    ├── 1dc097f7dd4c0ba3309a503c8e68242bdaa5f4be.nq.gz
    ├── 1df2aadffbaffa81d8db450d76bacad671fb4c8d.nq.gz
    ├── 1edc81dd0a0ae80f13d4a732910e3be382159b03.nq.gz
    ├── 20704fe21b48ea6533acc04de048740168fa57d7.nq.gz
    ├── 20db9d9fa230d3c20fd420c49d04532fd10cd89b.nq.gz
    ├── 20f80de5be81d8d49277bf54719480e6d9441321.nq.gz
    ├── 213b916d99d5bb30293e9d1cb1577949d6190eff.nq.gz
    ├── 2325e224cb5613f75cce7d4c6095da4f95117ef5.nq.gz
    ├── 234153ac28c44b892275c9378f11f626fd6f52a7.nq.gz
    ├── 235df9e7d5068c403ea4aed453ba86aca0c4ea67.nq.gz
    ├── 256190854eab965b9706a05e7d730c0f8afd66e4.nq.gz
    ├── 258c97dcde2dd562aed2b1f56a37bddf2120edfa.nq.gz
    ├── 258d207205c44e4484d1d46e93961f22a628a0e7.nq.gz
    ├── 25f7041460e30619156f276ae2cc7d4f8bdf7ddc.nq.gz
    ├── 27243d2584c7600fbe5d06b04be5ad8dec3becb9.nq.gz
    ├── 280f07c8a10a7ec70938d4d95f626e37ca989e10.nq.gz
    ├── 285c1ca7ec3bb1c85c3a1dbeb72e149de7b1f1b6.nq.gz
    ├── 28c9cc2e551faed619f20aa14b5025aca6d39ed7.nq.gz
    ├── 28eeca992eb5b7428db3ee9aeb118736fb708af4.nq.gz
    ├── 29494d9ad8a8f98574295a6208c32abbdef16459.nq.gz
    ├── 299d25a17310e6d321792d261063c174865ac094.nq.gz
    ├── 2a3297539bdf055539aa1229eb4767213742c195.nq.gz
    ├── 2aaf8527a2f88ffcbced4f4734354178dacdb88b.nq.gz
    ├── 2b483a4d8e4a265d30f63ba5640a0b351e3f9a65.nq.gz
    ├── 2bad59b6bd30aa833da7ccc9bb57be9a7ed7ba5e.nq.gz
    ├── 2bf164997406e4145fb2d032cd27742d69da3ff0.nq.gz
    ├── 2c9dfa888268e13bdde453b7c952d61a0d85f209.nq.gz
    ├── 309114059abddb855f94b20bc1785948758763b4.nq.gz
    ├── 30c690eb23228765954c52deeac0c4020dc2531c.nq.gz
    ├── 30f73eca502cb419d8fe93b6dc5f12a769cf4200.nq.gz
    ├── 3205698263b4399f07d945102b0566dcbf35b1bb.nq.gz
    ├── 325fe57a8807bd59ddb9128be9862e937aa7aac0.nq.gz
    ├── 32fb596a3a006c4185ea334fb230cf9ef65ceb25.nq.gz
    ├── 3461ce50e43a10ae39f3639927ce194ade32fbf0.nq.gz
    ├── 34e88356e5e47a43c8f077884c8e16c508ba597b.nq.gz
    ├── 3523fdf8ca98a90d172b1f88fd8f83dee32423e4.nq.gz
    ├── 35272f2d5072b754da34d246fa4048e3c39ad8e7.nq.gz
    ├── 3542857fddabcd65b41e9480e6593aeaa8f5930c.nq.gz
    ├── 359d3e3bfc0412850b0fb026d51ab63fb87de458.nq.gz
    ├── 36d181ed803f82193dca78a7196dd0dfe014abb0.nq.gz
    ├── 37bd5547b831e8c966154b61e5cbb3dc9cf2b383.nq.gz
    ├── 38ad098fc27f1e4f20317fdc04a06a63d34d4fd1.nq.gz
    ├── 38d496fd69cf77accfa7bdc4414e94f1659b0ece.nq.gz
    ├── 39e9810a60470f3ffda727fc01207cbd0d424155.nq.gz
    ├── 3a6beb4f00f90a50b479c759f0c2445790a498eb.nq.gz
    ├── 3b0575f3c65b7421aaaf622d11ddbe8ac72c3605.nq.gz
    ├── 3b3401c6c1efbac6c44c05705ee64b9576b13780.nq.gz
    ├── 3b7184f23d76bcda08b7cedc4c00b7878a600004.nq.gz
    ├── 3c2b1fa3e2d72af56151cce80bf1b4794b98f906.nq.gz
    ├── 3cc0ba0f255ee850a852283a52e7eb1f3fd83bda.nq.gz
    ├── 3d20dca0a0876f92fa36e1af0be4deb6b7d7f844.nq.gz
    ├── 3d5c04f00df3a18f1b9c170623a17853ef700415.nq.gz
    ├── 3d8067e841f63e4cda63ad2286aeb089a7ba4b11.nq.gz
    ├── 3e0666d20dd1cf1ba666a97e91655c909dfce32b.nq.gz
    ├── 3e92aabfacf75203d0ac752ad1ac52b3c339507a.nq.gz
    ├── 3fe36677d3cf5463a8559f434d9f0aef329a800e.nq.gz
    ├── 406263f58237fbb1e3fb9c0c826ba6750b4079d5.nq.gz
    ├── 40e6833f4b3ee50eda8a1faa3b80f5e03fd02140.nq.gz
    ├── 410233f42437996a2e920241316bde43230de8c1.nq.gz
    ├── 4103f6f4f4a9d053f5dfac46f29b8bbfe9800b79.nq.gz
    ├── 411a66ef66ab780adc72449e8fdac303e6450fd5.nq.gz
    ├── 41d4087940000ab39521c49ad7ba1f19dbb60bfc.nq.gz
    ├── 41ee2903b8d80d27f73199a78125b6e9e389b4c7.nq.gz
    ├── 421f34b9876148574cacfacf927f80798d4f86ed.nq.gz
    ├── 4282bbc1069981b930cc4b30274c0c2b30803f04.nq.gz
    ├── 428dd2d9e7f82ef44062e11e0d27bfe4fd3acc8d.nq.gz
    ├── 43d628df90186b733fad9e07c8c69325909383ca.nq.gz
    ├── 43f5e6cef086353892ed7f5c4b375733be857f35.nq.gz
    ├── 442d23ddd7963879710dadb594dfd6b510a3b53a.nq.gz
    ├── 44eedb1dd3f098f1cd1a772d587a6b2bd08806dd.nq.gz
    ├── 455810e1c0c36bb3e7cc13c24e6b0df88d1ef973.nq.gz
    ├── 461e775449720ad9af810cb876cd42e58e1e551a.nq.gz
    ├── 469ebbadb8af5a5c74176a4e501ee2b210151521.nq.gz
    ├── 478999a15589dcc842bef763f915c97b80b5144b.nq.gz
    ├── 48e2fdeef11bda248180fd7b6f64dc9318d40ad4.nq.gz
    ├── 4acd177de21991f1335558b944650493a2951e6f.nq.gz
    ├── 4b6e1595743900af31c8d2bb68a637f7e5d0abfd.nq.gz
    ├── 4bae3ed0bd855033f158675965c5e09d10ecb9a8.nq.gz
    ├── 4ccd76efe5bb4ff41aeb74f9b1fd7b48a985f9b9.nq.gz
    ├── 4cea48453a81f8754648a1580a2d6f0a5fe8f51f.nq.gz
    ├── 4d816980edb9f1e8390fc09a85c770d612a38094.nq.gz
    ├── 4e9cf64dbf8a5241dafd139d2e81fd47d52459fe.nq.gz
    ├── 4f58ca91cc09e0d97d78daecd4df5fc02d1a9d94.nq.gz
    ├── 4f593ef9a36246afeb67fb0cf7a7f45c8e5e72d9.nq.gz
    ├── 4f63f0ab054908a4ef0e03ac8bdb3d8b478b3883.nq.gz
    ├── 4fccb17931616a2b366a35e57a4fb3a1b0af152a.nq.gz
    ├── 50a8756a2c989a81353bc28111f6629c3656411a.nq.gz
    ├── 50c3df0e38eabacfb917fa86f0309237d4665946.nq.gz
    ├── 510f776b58c3be36bd5e2e8408bf125efed313cd.nq.gz
    ├── 5158898a7287d4811794efdf04dbc6606f818416.nq.gz
    ├── 51860d16d091bd9463dc78c593853691b457c229.nq.gz
    ├── 5208733585a338d7315dab2954da38af106bda73.nq.gz
    ├── 534ac3715bc958699ac1499c912224e1632fd939.nq.gz
    ├── 53d088625f85493ef77f933b57c2dd05b32b294e.nq.gz
    ├── 5401a61d044a3fc90c830792fe04c63ae8980858.nq.gz
    ├── 542f5f1a5fa90e193f200cee179c6be7115495f9.nq.gz
    ├── 543f90986e8bfa8313c4557f8fbe54f50ef8f961.nq.gz
    ├── 545de9157c03a5acbc3d4ce559429f2153e64ccc.nq.gz
    ├── 547b22d9864aadbda59535f8a5573fc952ce135f.nq.gz
    ├── 5512ce591a8517bfb3f6e1166b32cf8f9e531c10.nq.gz
    ├── 552ff1efb31fca4113ab02ddb104c454c017900f.nq.gz
    ├── 560dbc9e6a70b4b49c416ccf7f906e811743afca.nq.gz
    ├── 5641707645a0c2a35e65ccd8e31cf4d20098e908.nq.gz
    ├── 565d20f4a043908fba5270d495b6927e45d861ed.nq.gz
    ├── 569f31fc1b4dd91a78aeeab3724d30e4edc056e2.nq.gz
    ├── 56cc09f1a0732ec6cdbfe579c342454b49eeadc7.nq.gz
    ├── 587fa5c63e39e797fae13d7880f846ed64b47319.nq.gz
    ├── 58f187b59925e136dfb9c1c2c879c1d35f55d42e.nq.gz
    ├── 5936f8f3c3c3f768e3223199df90e94bdd5cf15f.nq.gz
    ├── 5a3ec5b4166c6cc9ba6404e000d0db8796f3776c.nq.gz
    ├── 5aff66e2f0ec3c9936db079abc9da60ccbe35f85.nq.gz
    ├── 5b919318993ec0da03725eb661ca65fc9702d689.nq.gz
    ├── 5bb3235242812556ac26b5a2a8008d6a91931d55.nq.gz
    ├── 5dcb5373e17c05cf822d639da51a90606c41808f.nq.gz
    ├── 5e852a35ab784756fa9db3b1e24f86c6f3f09731.nq.gz
    ├── 5e8aaa331bdb40f120cf3ea1ac1536ff12347333.nq.gz
    ├── 5eb69f0105d63ad0fd4de66fba082ebb5c36ec6b.nq.gz
    ├── 5f7b8f18e3c70c46d4f155042f1043e127ce7536.nq.gz
    ├── 603e495b9a04962bc7750ebd80e05950807f0e5a.nq.gz
    ├── 60d3a476a2d668f86e63a58d53efeecdf954295a.nq.gz
    ├── 614ff7825f4c99d98a7ce2e0fa413ac9b93190c3.nq.gz
    ├── 62e2bbd9e3013e6ed5e3f3bf8c4b7859a3c2caac.nq.gz
    ├── 62f47670ce55e242bf455e0160ca2a394741c366.nq.gz
    ├── 6419948c6896d8b95287461632baff4aa8d527ea.nq.gz
    ├── 649e73d961f79d7569de8d4faa70483dedb90a86.nq.gz
    ├── 66a60c0856254970646dac0a98640a7701e81683.nq.gz
    ├── 67931f9cc27b2ad6af54ad94b26985ef9b6d0c12.nq.gz
    ├── 67d751b8f8da483e4c39e47281a8b9330b3087f7.nq.gz
    ├── 68e75d64158e59c6322eeda11606018fbdcb333c.nq.gz
    ├── 692b0e3704032487afcc1a686515e6a9d7c8d8cf.nq.gz
    ├── 69cad2330a338be0c118e95442065644cd59bc32.nq.gz
    ├── 6a0f6e1f1bc2e1cac79c01f6c2f2329f2f4471d8.nq.gz
    ├── 6aca77d50f77478aab00c1d436cfbe255319eab2.nq.gz
    ├── 6b45ede08bcea410be8c010ff7dae153fed4c87a.nq.gz
    ├── 6c2fc1af95632881dbe8ae768ae474643f3356bf.nq.gz
    ├── 6c3d9805fc625702b66df6782c58db4a18bfd5bb.nq.gz
    ├── 6c6f3a29ab6cb3a0c78148af56db4e50c71c089d.nq.gz
    ├── 6d4fb463677e6c22087ae39da86880b7f6d95fd3.nq.gz
    ├── 6deb3340bb6424cacaa6031139b6e13438f85010.nq.gz
    ├── 6f97e482b64fbac34af44839f53678eea896ae07.nq.gz
    ├── 703a792b578b7e842955d59255999821758e04c8.nq.gz
    ├── 7086a8ea7f0738fe9e5e80a00a85595bf0753cda.nq.gz
    ├── 71aa71cbb40685b84c35f2b25fcf919a4012d72a.nq.gz
    ├── 71ab8c6525458af8b0e0f7ee2d1db36a2f85a387.nq.gz
    ├── 724ff77998909c5c4a8dc745903cbd7c74cb914e.nq.gz
    ├── 7272e48efa683d542d9d622f181eef0574e6a37a.nq.gz
    ├── 730acc1a4e55a3d81932846f3288552ede1c7f24.nq.gz
    ├── 7353e2793c2fd8ece564671c27dab0bb7ab4f7c7.nq.gz
    ├── 7363c6cdfd8c340fadba866f0641a5ce64289461.nq.gz
    ├── 73c10f051267eafe9a14216641bae6cf65376c7f.nq.gz
    ├── 73f71c419a1b525e3cfe3f13ef52017e6c006c13.nq.gz
    ├── 745fef493dc1fcab5db504e59942a13b29df91bb.nq.gz
    ├── 74d40cd57178666463a4f2e8d25e299448e7d2ad.nq.gz
    └── 74fd921b5627c360ea8b7ffd840acbe9db1de305.nq.gz

6 directories, 200 files
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

[TopQuadrant/shacl](https://github.com/TopQuadrant/shacl)

---
*Parsed on 2026-03-26 by [repolex](https://repolex.ai)*
