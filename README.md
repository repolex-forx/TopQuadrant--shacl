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
│   │   ├── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│   │   └── a40627da5df455535d3519eb6629057ab52a2843.nq.gz
│   ├── lsp
│   │   ├── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│   │   └── a40627da5df455535d3519eb6629057ab52a2843.nq.gz
│   └── repolex
│       ├── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│       └── a40627da5df455535d3519eb6629057ab52a2843.nq.gz
└── blob
    ├── 001a1218b5ad24b6aef344039895c5a661677a19.nq.gz
    ├── 007e23655602b6f699f9ee2696059ae72db488c5.nq.gz
    ├── 0087b5bdfb4e0e10470dcb5b8657cefc9a2c7ed9.nq.gz
    ├── 00f6d4a0ea1e635b119271dbbe5b6edaa38e0039.nq.gz
    ├── 01135b34e6ef6c18cbdf2134f5745e260993e33c.nq.gz
    ├── 01b5fd6c9e8942b4c9df569abe0a9c157b79f0c8.nq.gz
    ├── 01b9bb1c9f8b58a658fe76d513e1f2000c972fc5.nq.gz
    ├── 02004c916f43f7266a96783f29c62c512d62a945.nq.gz
    ├── 0209dceb728289c34a6de66e63bcec631de5d14a.nq.gz
    ├── 02b085ac16b9f76064727c53dc459e3b5cc34225.nq.gz
    ├── 0319b804a7dc81ab02406bab018c7f15b15aac9a.nq.gz
    ├── 031d13447b9d28c9cd53dcc839c84d5c7c6a1f26.nq.gz
    ├── 03fcd883fc089ab48ab2b0d8f98dc170f1336b7f.nq.gz
    ├── 040b595d0fe1a05d883ba6049a7522df5366b27e.nq.gz
    ├── 045b207ee53aaa85438504ce975d06fedaa24538.nq.gz
    ├── 04b1ecfde5c1c06d238906d8dfc59327c4b48a00.nq.gz
    ├── 050a4a80f5d3f2c200fe61d02bfbf7db9ba961f9.nq.gz
    ├── 05580e8e421b7eaf6f5aad9e7c6d46ab6f9d7940.nq.gz
    ├── 05f936e4f4e5fbf75d291aa59796d123f051b1c8.nq.gz
    ├── 061a55991c0700588f063168268816d97c572f8e.nq.gz
    ├── 069ad950c2c34c2570edc38ff211694630cb12ab.nq.gz
    ├── 06dea52d27ff43548db9cceeb1d4e3e4e883d659.nq.gz
    ├── 07131290036d967363ad78f3de2a4d45a5ee9d28.nq.gz
    ├── 0757ef726bec810e32d5d30fcb83170be1ec857b.nq.gz
    ├── 07c49d0f3048c6dc5c17990617cfc3495f230dce.nq.gz
    ├── 080f23e9351f2ca73b46d1e88edef771c2348d58.nq.gz
    ├── 08ebbf2a4ddfe7b409d3455ab5e14d3eef3a96ad.nq.gz
    ├── 0907c83f782a7a1cd6b01a681b0d7371412a87d7.nq.gz
    ├── 09294263297b6124bd13b50db17dd82437f9e743.nq.gz
    ├── 094781ab3e7ab799a2ee3b697fdac9e38c032191.nq.gz
    ├── 09535eb1583c1ad2fc03d0b8f515d5df4cf90ec8.nq.gz
    ├── 095981c5a6af8c68af1c472fec9f6636586d2072.nq.gz
    ├── 09b3e045c87fbfc3eb780c85413e0415cdec259e.nq.gz
    ├── 0a23fec692a8b075394a8c99e03699fb10c85070.nq.gz
    ├── 0a31cf1feb201bdbd5d6a6aa01d5ab6e86333439.nq.gz
    ├── 0a7a43abdcc7543dc6c1ce03b63988e85b3a37c8.nq.gz
    ├── 0a860e23d5098d9e39232f7ef1c424c9487679c7.nq.gz
    ├── 0a8c069b9d914445625e06ac98a1454bf2dcb49d.nq.gz
    ├── 0add8f0781516a2c7d13891a9ead0ff4d123f908.nq.gz
    ├── 0aed7a8ada90bb348ddabebe590eac8dc715fce9.nq.gz
    ├── 0b2021ab79ca493a356df407849da6f8bdb9a3d3.nq.gz
    ├── 0bcafb0d22c4ae4cf596308d31caf095964f2c41.nq.gz
    ├── 0c5e194d39c3df25dcbc04a1b970f4a6baaad6b3.nq.gz
    ├── 0e58560ee87626c29d221075bcfa6be39edc2892.nq.gz
    ├── 103c7ab589e32f836dab5832b7a02287eee8a48e.nq.gz
    ├── 1080e3409f6c5cb89c6b4e77b5a6f4fd4b38f594.nq.gz
    ├── 108eeaaf7f09bec444e9376e7d2c4bc7096baacd.nq.gz
    ├── 10f643965dbd5649f58079726e3698fa64f47abc.nq.gz
    ├── 11bfd53b8101cc4019cc5d0c14586d87de0cb9e9.nq.gz
    ├── 126abb328f631456b73f52364a8a86ddffbb2c7d.nq.gz
    ├── 12c41048cb50ce6f14a8f0783756833deab37770.nq.gz
    ├── 133d88e93ad5cb48f770d7c0c5ddc7f723a489e0.nq.gz
    ├── 137e4a904fdefde0604e9f37aa2d1a81808aff0e.nq.gz
    ├── 138af2003c519ee21df9f666aca93f2b3cf800f3.nq.gz
    ├── 13c518fd7b9df962304e04a1ab03ca76dbdded08.nq.gz
    ├── 143afd2bde103dbd1bd03b4a6c168aded4f98067.nq.gz
    ├── 1446f27f900371ef3553799c7ade56b7c5d082b2.nq.gz
    ├── 147c08d4ac812186ddf925d9fc403a6b45b51f72.nq.gz
    ├── 14f51d525df90b7dc0bee62576ac33cca8eeb5c8.nq.gz
    ├── 15c4c5f79184de3e0673cebb33e63b7a3778428e.nq.gz
    ├── 163499efca87b600f56fcbe8b73a0bdcda1487df.nq.gz
    ├── 16486a918c25a14e66cb5b1586580869b509e983.nq.gz
    ├── 168d7779f3840b6784aec8b8eb151dd34ea7c1ba.nq.gz
    ├── 16935625991038210bced04fbbabb3cc034ca24b.nq.gz
    ├── 16dad16cb8a3bb56df42bc2732d14b9094bc0e4b.nq.gz
    ├── 17926aed3c9f26d1b72fd174165edab2892f2ff9.nq.gz
    ├── 17b0cc01456dce801c8fbcd31b4ca14feb9cb1fb.nq.gz
    ├── 17ecbdace189f8d19bffbc3d5ffe7121c8588803.nq.gz
    ├── 18acfb45d04bf584cd9ccd68c73416568b3ad1c0.nq.gz
    ├── 1a38df2271c1a6a8b8cbd744118ece14aa1d06d5.nq.gz
    ├── 1a8ea9a48592a018722c3bab0d45563f65828b9f.nq.gz
    ├── 1b7114d69cfbc2b257d6fa6fe1228dc31571c067.nq.gz
    ├── 1c684fe9cd4b5ea7c22a5cd950215d022ae36fb2.nq.gz
    ├── 1c88f2a56027e6a9987858acd2d99196f3961456.nq.gz
    ├── 1cd6178f9251f70ed2c2cb0fac83009409afb422.nq.gz
    ├── 1d9a20821cc7fb64f6108175b6fefd6a6f76b462.nq.gz
    ├── 1dc097f7dd4c0ba3309a503c8e68242bdaa5f4be.nq.gz
    ├── 1dec0e24ada539530d3cd09a4fbd6327398a74b0.nq.gz
    ├── 1df2aadffbaffa81d8db450d76bacad671fb4c8d.nq.gz
    ├── 1edc81dd0a0ae80f13d4a732910e3be382159b03.nq.gz
    ├── 20704fe21b48ea6533acc04de048740168fa57d7.nq.gz
    ├── 20db9d9fa230d3c20fd420c49d04532fd10cd89b.nq.gz
    ├── 20f80de5be81d8d49277bf54719480e6d9441321.nq.gz
    ├── 213b916d99d5bb30293e9d1cb1577949d6190eff.nq.gz
    ├── 221123f1e3b7551f8dc3b052248de5b80d72cfe7.nq.gz
    ├── 22d904bdaf50e467b534ec2a4d158bd74515683e.nq.gz
    ├── 2325e224cb5613f75cce7d4c6095da4f95117ef5.nq.gz
    ├── 234153ac28c44b892275c9378f11f626fd6f52a7.nq.gz
    ├── 235df9e7d5068c403ea4aed453ba86aca0c4ea67.nq.gz
    ├── 23d3114b217ac8516fbc7d615809019ab3fd980b.nq.gz
    ├── 24d155d7f7d4c6de4513da5325ed607785f8ef49.nq.gz
    ├── 24df64e5667ceb231a857d38b9581ebb3f8f7bb9.nq.gz
    ├── 256190854eab965b9706a05e7d730c0f8afd66e4.nq.gz
    ├── 258c97dcde2dd562aed2b1f56a37bddf2120edfa.nq.gz
    ├── 258d207205c44e4484d1d46e93961f22a628a0e7.nq.gz
    ├── 25f7041460e30619156f276ae2cc7d4f8bdf7ddc.nq.gz
    ├── 27243d2584c7600fbe5d06b04be5ad8dec3becb9.nq.gz
    ├── 280f07c8a10a7ec70938d4d95f626e37ca989e10.nq.gz
    ├── 285c1ca7ec3bb1c85c3a1dbeb72e149de7b1f1b6.nq.gz
    ├── 28c9cc2e551faed619f20aa14b5025aca6d39ed7.nq.gz
    ├── 28eeca992eb5b7428db3ee9aeb118736fb708af4.nq.gz
    ├── 2911a48233cfb8914bb0f9c7c10c9bcd25ba0eb4.nq.gz
    ├── 29494d9ad8a8f98574295a6208c32abbdef16459.nq.gz
    ├── 299d25a17310e6d321792d261063c174865ac094.nq.gz
    ├── 29db7d7c8c1495cbe17b0bf596e87e4b05872d0f.nq.gz
    ├── 2a3297539bdf055539aa1229eb4767213742c195.nq.gz
    ├── 2aaf8527a2f88ffcbced4f4734354178dacdb88b.nq.gz
    ├── 2b483a4d8e4a265d30f63ba5640a0b351e3f9a65.nq.gz
    ├── 2bad59b6bd30aa833da7ccc9bb57be9a7ed7ba5e.nq.gz
    ├── 2bf164997406e4145fb2d032cd27742d69da3ff0.nq.gz
    ├── 2c9dfa888268e13bdde453b7c952d61a0d85f209.nq.gz
    ├── 2cee2888adb44a2253c6e4df4dd0489d2d3c42c8.nq.gz
    ├── 30592cfc75fe4ec51a1627b82a03fed80988ad87.nq.gz
    ├── 309114059abddb855f94b20bc1785948758763b4.nq.gz
    ├── 30c690eb23228765954c52deeac0c4020dc2531c.nq.gz
    ├── 30f73eca502cb419d8fe93b6dc5f12a769cf4200.nq.gz
    ├── 30fb440271be1c9ef9f44b600f3335c30468ecbc.nq.gz
    ├── 312daea8eafae7d885123b0c6504069c4b5a2a56.nq.gz
    ├── 31321aa265dc498dc1f05b34ad9df7c665f983a2.nq.gz
    ├── 318273dcc820769ad0f59540f3163922bae7d484.nq.gz
    ├── 3205698263b4399f07d945102b0566dcbf35b1bb.nq.gz
    ├── 325fe57a8807bd59ddb9128be9862e937aa7aac0.nq.gz
    ├── 329fb39e610e7b4310ce1f4b73527a8fa857e45f.nq.gz
    ├── 32fb596a3a006c4185ea334fb230cf9ef65ceb25.nq.gz
    ├── 333a315df5801203a2683a6a5f9f57ddd742e82c.nq.gz
    ├── 343b692ec7c2b93daa61eb8aa6b0824b642ee0dd.nq.gz
    ├── 3461ce50e43a10ae39f3639927ce194ade32fbf0.nq.gz
    ├── 34e88356e5e47a43c8f077884c8e16c508ba597b.nq.gz
    ├── 3523fdf8ca98a90d172b1f88fd8f83dee32423e4.nq.gz
    ├── 35272f2d5072b754da34d246fa4048e3c39ad8e7.nq.gz
    ├── 3542857fddabcd65b41e9480e6593aeaa8f5930c.nq.gz
    ├── 359d3e3bfc0412850b0fb026d51ab63fb87de458.nq.gz
    ├── 365ae4a888213cb823b148e3f529c790be9e7741.nq.gz
    ├── 36d181ed803f82193dca78a7196dd0dfe014abb0.nq.gz
    ├── 36f5f052fced8adf7cb8cb974fa85c5c0177887a.nq.gz
    ├── 37bd5547b831e8c966154b61e5cbb3dc9cf2b383.nq.gz
    ├── 38ac459abdaf643bf38c5654f82a7a7e637b245a.nq.gz
    ├── 38ad098fc27f1e4f20317fdc04a06a63d34d4fd1.nq.gz
    ├── 38d496fd69cf77accfa7bdc4414e94f1659b0ece.nq.gz
    ├── 39e9810a60470f3ffda727fc01207cbd0d424155.nq.gz
    ├── 3a6beb4f00f90a50b479c759f0c2445790a498eb.nq.gz
    ├── 3b0575f3c65b7421aaaf622d11ddbe8ac72c3605.nq.gz
    ├── 3b3401c6c1efbac6c44c05705ee64b9576b13780.nq.gz
    ├── 3b4c469579b317338d48d9eb31b92bf2440052d5.nq.gz
    ├── 3b7184f23d76bcda08b7cedc4c00b7878a600004.nq.gz
    ├── 3c2b1fa3e2d72af56151cce80bf1b4794b98f906.nq.gz
    ├── 3cb2e5871653cbab170e4a343212c0e92a8b359a.nq.gz
    ├── 3cc0ba0f255ee850a852283a52e7eb1f3fd83bda.nq.gz
    ├── 3d20dca0a0876f92fa36e1af0be4deb6b7d7f844.nq.gz
    ├── 3d5c04f00df3a18f1b9c170623a17853ef700415.nq.gz
    ├── 3d8067e841f63e4cda63ad2286aeb089a7ba4b11.nq.gz
    ├── 3e0666d20dd1cf1ba666a97e91655c909dfce32b.nq.gz
    ├── 3e92aabfacf75203d0ac752ad1ac52b3c339507a.nq.gz
    ├── 3f634752a448dfd4e61b2a821fcb4c4e93f39cdf.nq.gz
    ├── 3fbcf17d325f88599552e4ecc5111211f7bc538b.nq.gz
    ├── 3fe36677d3cf5463a8559f434d9f0aef329a800e.nq.gz
    ├── 40442ac2fde02d02f35328910a5f5c87f5776979.nq.gz
    ├── 406263f58237fbb1e3fb9c0c826ba6750b4079d5.nq.gz
    ├── 40e6833f4b3ee50eda8a1faa3b80f5e03fd02140.nq.gz
    ├── 410233f42437996a2e920241316bde43230de8c1.nq.gz
    ├── 4103f6f4f4a9d053f5dfac46f29b8bbfe9800b79.nq.gz
    ├── 411a66ef66ab780adc72449e8fdac303e6450fd5.nq.gz
    ├── 41d4087940000ab39521c49ad7ba1f19dbb60bfc.nq.gz
    ├── 41ee2903b8d80d27f73199a78125b6e9e389b4c7.nq.gz
    ├── 41f1f97f6df75dcd568773f02f0c8204beb018f2.nq.gz
    ├── 421f34b9876148574cacfacf927f80798d4f86ed.nq.gz
    ├── 4282bbc1069981b930cc4b30274c0c2b30803f04.nq.gz
    ├── 428c617f00b48092416153e70bf4adc910019643.nq.gz
    ├── 428dd2d9e7f82ef44062e11e0d27bfe4fd3acc8d.nq.gz
    ├── 435cebc9128c8b441b31465b8c762219ccff3d52.nq.gz
    ├── 43d628df90186b733fad9e07c8c69325909383ca.nq.gz
    ├── 43f5e6cef086353892ed7f5c4b375733be857f35.nq.gz
    ├── 442d23ddd7963879710dadb594dfd6b510a3b53a.nq.gz
    ├── 44c2ef723d038226e575faf1ffb8a3fa0432ca1b.nq.gz
    ├── 44c94ad7608efc51c129121f52a3bc4939d6da0e.nq.gz
    ├── 44eedb1dd3f098f1cd1a772d587a6b2bd08806dd.nq.gz
    ├── 4528a11bbc1bbfb72b86830fb936d8f8dcb472e5.nq.gz
    ├── 455810e1c0c36bb3e7cc13c24e6b0df88d1ef973.nq.gz
    ├── 461e775449720ad9af810cb876cd42e58e1e551a.nq.gz
    ├── 469ebbadb8af5a5c74176a4e501ee2b210151521.nq.gz
    ├── 46a316cc85246c558c5c5cabfd54cd21aa9d9ac0.nq.gz
    ├── 472aad573fc74250ebd026434fa1abc8025d401a.nq.gz
    ├── 478999a15589dcc842bef763f915c97b80b5144b.nq.gz
    ├── 48e2fdeef11bda248180fd7b6f64dc9318d40ad4.nq.gz
    ├── 497c0938be78866e8b4b3e1e43af9b4a137ea9e3.nq.gz
    ├── 4ac41e54349278092dc5132e1ab7596f03e22cda.nq.gz
    ├── 4acd177de21991f1335558b944650493a2951e6f.nq.gz
    ├── 4b6e1595743900af31c8d2bb68a637f7e5d0abfd.nq.gz
    ├── 4bae3ed0bd855033f158675965c5e09d10ecb9a8.nq.gz
    ├── 4ccd76efe5bb4ff41aeb74f9b1fd7b48a985f9b9.nq.gz
    ├── 4cea48453a81f8754648a1580a2d6f0a5fe8f51f.nq.gz
    ├── 4cfa7f934f20da9f3d322237e7e621bef50b15d5.nq.gz
    ├── 4d50c61879b1f79d8c7ea6a7a6c1cae38765a88d.nq.gz
    └── 4d816980edb9f1e8390fc09a85c770d612a38094.nq.gz

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
*Parsed on 2026-03-28 by [repolex](https://repolex.ai)*
