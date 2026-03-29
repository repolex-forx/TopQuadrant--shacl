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
    ├── 0117f14eefa2376d3ae6710269ccc41913697dfc.nq.gz
    ├── 011af99cc07f2d6833e8f3bd1ed5a31ddbf77bad.nq.gz
    ├── 01b5fd6c9e8942b4c9df569abe0a9c157b79f0c8.nq.gz
    ├── 01b9bb1c9f8b58a658fe76d513e1f2000c972fc5.nq.gz
    ├── 02004c916f43f7266a96783f29c62c512d62a945.nq.gz
    ├── 0209dceb728289c34a6de66e63bcec631de5d14a.nq.gz
    ├── 0259a0cc6d3b0f5c84bf3429d00cf4289a780232.nq.gz
    ├── 027e21243e154213244fa9d3f66ce6b4ee8f5d2f.nq.gz
    ├── 02b085ac16b9f76064727c53dc459e3b5cc34225.nq.gz
    ├── 02d20b71faf65b98f5394670d0a5adf3d7cd6488.nq.gz
    ├── 0319b804a7dc81ab02406bab018c7f15b15aac9a.nq.gz
    ├── 031d13447b9d28c9cd53dcc839c84d5c7c6a1f26.nq.gz
    ├── 03d7bb1b28253e857c42e06b85bbd80ce36307a8.nq.gz
    ├── 03fcd883fc089ab48ab2b0d8f98dc170f1336b7f.nq.gz
    ├── 040b595d0fe1a05d883ba6049a7522df5366b27e.nq.gz
    ├── 044224ba1f5dbb32cd2d344d217a462ff89f8fdc.nq.gz
    ├── 045b207ee53aaa85438504ce975d06fedaa24538.nq.gz
    ├── 045e0f585a2d5cc5ba4b3eb7d711acc968736aba.nq.gz
    ├── 047d415e2ce3bf7979f07d75d9681a32e8a96f66.nq.gz
    ├── 04b1ecfde5c1c06d238906d8dfc59327c4b48a00.nq.gz
    ├── 04cfa2c1a8566d64dd12fcf7a8e895fe02e1856f.nq.gz
    ├── 04d7d2021d159a7d965ddeddb56746bbdc919bb4.nq.gz
    ├── 050a4a80f5d3f2c200fe61d02bfbf7db9ba961f9.nq.gz
    ├── 054fee9fdcb5bb9d692a0f5c558636fbc7b868ef.nq.gz
    ├── 05580e8e421b7eaf6f5aad9e7c6d46ab6f9d7940.nq.gz
    ├── 05d78766bacefcda1f169df287b24daeb755f8c4.nq.gz
    ├── 05f936e4f4e5fbf75d291aa59796d123f051b1c8.nq.gz
    ├── 061a55991c0700588f063168268816d97c572f8e.nq.gz
    ├── 069ad950c2c34c2570edc38ff211694630cb12ab.nq.gz
    ├── 06ce96628a5dbeb17e2c095c92ab93951cdf02e5.nq.gz
    ├── 06dea52d27ff43548db9cceeb1d4e3e4e883d659.nq.gz
    ├── 07131290036d967363ad78f3de2a4d45a5ee9d28.nq.gz
    ├── 0757ef726bec810e32d5d30fcb83170be1ec857b.nq.gz
    ├── 07c49d0f3048c6dc5c17990617cfc3495f230dce.nq.gz
    ├── 07f119754613eed5a6e9d449ec2d1c2831cdc773.nq.gz
    ├── 080f23e9351f2ca73b46d1e88edef771c2348d58.nq.gz
    ├── 08cf25e9bf77a8f4e1b182b1205691224995088a.nq.gz
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
    ├── 0b2c9da6b3719ba890cbeb76e477623c51d7c583.nq.gz
    ├── 0b32a567ecc27b52d90c2b2958cafac879c90eee.nq.gz
    ├── 0b8871776f19838ccdfeac10bf11a81fe69e4b19.nq.gz
    ├── 0bcafb0d22c4ae4cf596308d31caf095964f2c41.nq.gz
    ├── 0c5e194d39c3df25dcbc04a1b970f4a6baaad6b3.nq.gz
    ├── 0ccb4e27f7f11e166ed498e98992cbc67486edb9.nq.gz
    ├── 0d01012327bc5cbfa6028c4efd1d21f0882263b0.nq.gz
    ├── 0d6e7c6d0b7d1de2e0b0b572a0c9b7ad10e93f2e.nq.gz
    ├── 0e58560ee87626c29d221075bcfa6be39edc2892.nq.gz
    ├── 0e687deaa1262df335dd25a8180fb2f9ba8ea0ba.nq.gz
    ├── 0e71c84eb15b4665e14515a7e69e60486f4c2f1a.nq.gz
    ├── 0e7740039b382f5b3d9c1659c8dd7bd8b5e67a4e.nq.gz
    ├── 0ee68bd9e36369520063cdca36014f1058ec6c90.nq.gz
    ├── 0f7028a18327cd126d25e65f64d16fca6ca140d4.nq.gz
    ├── 103c7ab589e32f836dab5832b7a02287eee8a48e.nq.gz
    ├── 1080e3409f6c5cb89c6b4e77b5a6f4fd4b38f594.nq.gz
    ├── 108eeaaf7f09bec444e9376e7d2c4bc7096baacd.nq.gz
    ├── 10f643965dbd5649f58079726e3698fa64f47abc.nq.gz
    ├── 11bfd53b8101cc4019cc5d0c14586d87de0cb9e9.nq.gz
    ├── 126abb328f631456b73f52364a8a86ddffbb2c7d.nq.gz
    ├── 12acd1f35677cdbb8f307536dcd0f42734f70db4.nq.gz
    ├── 12c41048cb50ce6f14a8f0783756833deab37770.nq.gz
    ├── 13132f343aaea6adef97a5fea045ecea915adcec.nq.gz
    ├── 133d88e93ad5cb48f770d7c0c5ddc7f723a489e0.nq.gz
    ├── 13532f4806c5b7933980f21415870f4e9a38111c.nq.gz
    ├── 137e4a904fdefde0604e9f37aa2d1a81808aff0e.nq.gz
    ├── 137f6e37629f8108b1265752c935bd33f2da8f13.nq.gz
    ├── 138af2003c519ee21df9f666aca93f2b3cf800f3.nq.gz
    ├── 13c518fd7b9df962304e04a1ab03ca76dbdded08.nq.gz
    ├── 14308e09df5df41bd48cf9e79b96ac834dc36f5b.nq.gz
    ├── 143afd2bde103dbd1bd03b4a6c168aded4f98067.nq.gz
    ├── 1446f27f900371ef3553799c7ade56b7c5d082b2.nq.gz
    ├── 147c08d4ac812186ddf925d9fc403a6b45b51f72.nq.gz
    ├── 14988d5acea87c5b4c235992a29a6d74f9e7c878.nq.gz
    ├── 14b697b7bbb0d85e8d8ee19141a2a92d9ce211be.nq.gz
    ├── 14f51d525df90b7dc0bee62576ac33cca8eeb5c8.nq.gz
    ├── 1504de65eeef162cce25a3af92a2aaedac230698.nq.gz
    ├── 150519f1521a2509f7e39eb7691cd9b3b3e6623a.nq.gz
    ├── 15714858e646d563bffcf3718ff675f2c6a5ecac.nq.gz
    ├── 15c4c5f79184de3e0673cebb33e63b7a3778428e.nq.gz
    ├── 16055f2d80e43fc4764d9bb4dbd53fde2ad0b3c2.nq.gz
    ├── 163499efca87b600f56fcbe8b73a0bdcda1487df.nq.gz
    ├── 16486a918c25a14e66cb5b1586580869b509e983.nq.gz
    ├── 168d7779f3840b6784aec8b8eb151dd34ea7c1ba.nq.gz
    ├── 16935625991038210bced04fbbabb3cc034ca24b.nq.gz
    ├── 16c89cc13733da44a37aa705233e6704c91106ef.nq.gz
    ├── 16dad16cb8a3bb56df42bc2732d14b9094bc0e4b.nq.gz
    ├── 1710b1d96b8e6688419edb211b5fe0fbe246548f.nq.gz
    ├── 17926aed3c9f26d1b72fd174165edab2892f2ff9.nq.gz
    ├── 17b0cc01456dce801c8fbcd31b4ca14feb9cb1fb.nq.gz
    ├── 17e04ce55b5eb5af7ef290ec5c7f54dec77b380a.nq.gz
    ├── 17ecbdace189f8d19bffbc3d5ffe7121c8588803.nq.gz
    ├── 17ff836a2eb55b9f65106e86e389357083690ff4.nq.gz
    ├── 18acfb45d04bf584cd9ccd68c73416568b3ad1c0.nq.gz
    ├── 1a0f13d029210f836f57a2831119a4f874f8dce0.nq.gz
    ├── 1a38df2271c1a6a8b8cbd744118ece14aa1d06d5.nq.gz
    ├── 1a8ea9a48592a018722c3bab0d45563f65828b9f.nq.gz
    ├── 1b7114d69cfbc2b257d6fa6fe1228dc31571c067.nq.gz
    ├── 1bafe1ece1dd5b1a46e2eccabde78c2e1311c6fe.nq.gz
    ├── 1c0ed2246f698da0213a179e03a78888aca743a4.nq.gz
    ├── 1c684fe9cd4b5ea7c22a5cd950215d022ae36fb2.nq.gz
    ├── 1c71845caf654d083a786758d559a4ad8003f559.nq.gz
    ├── 1c88f2a56027e6a9987858acd2d99196f3961456.nq.gz
    ├── 1cc02ab6a81bad651dc02f61ff59a1451d6a3651.nq.gz
    ├── 1cd6178f9251f70ed2c2cb0fac83009409afb422.nq.gz
    ├── 1d1d11e0ca2c267d367f0f7624e4aac9269515a6.nq.gz
    ├── 1d9a20821cc7fb64f6108175b6fefd6a6f76b462.nq.gz
    ├── 1dbe73a3b828e672f97073e0ee95cab930803a0b.nq.gz
    ├── 1dc097f7dd4c0ba3309a503c8e68242bdaa5f4be.nq.gz
    ├── 1dc13cb2df870d2b15990d2d7891839eac0cc520.nq.gz
    ├── 1dec0e24ada539530d3cd09a4fbd6327398a74b0.nq.gz
    ├── 1df2aadffbaffa81d8db450d76bacad671fb4c8d.nq.gz
    ├── 1e45315bbbf8e4ab6f96a61f0cf5294cf8bdd418.nq.gz
    ├── 1e9cb591ce70791507c25ee5bf880ccdf3235437.nq.gz
    ├── 1edc81dd0a0ae80f13d4a732910e3be382159b03.nq.gz
    ├── 1f3a3b5f322f73c85723194595dcebcb72558a1a.nq.gz
    ├── 1f655df86aa5e5c38d6dfea030760183d31da306.nq.gz
    ├── 203b4764edfff965024da4c8b5b6007516e6e406.nq.gz
    ├── 20704fe21b48ea6533acc04de048740168fa57d7.nq.gz
    ├── 207185d57b317ea3513481d07680328d6236c008.nq.gz
    ├── 20db9d9fa230d3c20fd420c49d04532fd10cd89b.nq.gz
    ├── 20f80de5be81d8d49277bf54719480e6d9441321.nq.gz
    ├── 211fbf9e3e8051135f0b47458738839faf63f12c.nq.gz
    ├── 213b916d99d5bb30293e9d1cb1577949d6190eff.nq.gz
    ├── 2160245aa495ef3d9c42c6bf9818f50e3e6e4004.nq.gz
    ├── 21bcbcc1f0c353c1791980048a5192a57af84219.nq.gz
    ├── 221123f1e3b7551f8dc3b052248de5b80d72cfe7.nq.gz
    ├── 22d904bdaf50e467b534ec2a4d158bd74515683e.nq.gz
    ├── 2325e224cb5613f75cce7d4c6095da4f95117ef5.nq.gz
    ├── 234153ac28c44b892275c9378f11f626fd6f52a7.nq.gz
    ├── 235df9e7d5068c403ea4aed453ba86aca0c4ea67.nq.gz
    ├── 2365834e57891655c18221c09713d5546ee404ca.nq.gz
    ├── 23d3114b217ac8516fbc7d615809019ab3fd980b.nq.gz
    ├── 23d70f14a399e905164255195f0c7e4e2d554bcc.nq.gz
    ├── 24643cc37449b4bde54411a80b8ed61258225e34.nq.gz
    ├── 24ad14e7282ff86967d322d04ee4ba44c01f045c.nq.gz
    ├── 24d155d7f7d4c6de4513da5325ed607785f8ef49.nq.gz
    ├── 24df64e5667ceb231a857d38b9581ebb3f8f7bb9.nq.gz
    ├── 256190854eab965b9706a05e7d730c0f8afd66e4.nq.gz
    ├── 258c97dcde2dd562aed2b1f56a37bddf2120edfa.nq.gz
    ├── 258d207205c44e4484d1d46e93961f22a628a0e7.nq.gz
    ├── 25f7041460e30619156f276ae2cc7d4f8bdf7ddc.nq.gz
    ├── 26a35733f6812a41484f9b05a72f2939ddf53ed9.nq.gz
    ├── 26f1564d08caf8d3f59b886108a13e8f864170fd.nq.gz
    ├── 27243d2584c7600fbe5d06b04be5ad8dec3becb9.nq.gz
    ├── 272bbccb32c664a0e44adc4f12144080df213694.nq.gz
    ├── 2784701f65c6ef49a21dc6e1d33239ee6d02df09.nq.gz
    ├── 280f07c8a10a7ec70938d4d95f626e37ca989e10.nq.gz
    ├── 284fa1173deda36580c8324cb2f90bac00d4ade6.nq.gz
    ├── 285c1ca7ec3bb1c85c3a1dbeb72e149de7b1f1b6.nq.gz
    ├── 28676f6a9bcc04312f0812f4fa63bae5cf8dbaed.nq.gz
    ├── 28c9c8bafa645ad4a6601bebdc7acfa13cd9e44a.nq.gz
    ├── 28c9cc2e551faed619f20aa14b5025aca6d39ed7.nq.gz
    ├── 28eeca992eb5b7428db3ee9aeb118736fb708af4.nq.gz
    ├── 2911a48233cfb8914bb0f9c7c10c9bcd25ba0eb4.nq.gz
    ├── 2943f13af09fea2dc776bd550f829845297d8139.nq.gz
    ├── 29494d9ad8a8f98574295a6208c32abbdef16459.nq.gz
    ├── 299d25a17310e6d321792d261063c174865ac094.nq.gz
    ├── 29db7d7c8c1495cbe17b0bf596e87e4b05872d0f.nq.gz
    ├── 2a3297539bdf055539aa1229eb4767213742c195.nq.gz
    ├── 2a7dabd6f7ba998fdfd8beaad20a8371fa16a1ae.nq.gz
    ├── 2aaf8527a2f88ffcbced4f4734354178dacdb88b.nq.gz
    ├── 2b483a4d8e4a265d30f63ba5640a0b351e3f9a65.nq.gz
    ├── 2bad59b6bd30aa833da7ccc9bb57be9a7ed7ba5e.nq.gz
    ├── 2bcd3e98e92e01a8aa7372925eef4bcdb168ba27.nq.gz
    ├── 2be57634008c8f6062574658c2896802534559fc.nq.gz
    ├── 2bf164997406e4145fb2d032cd27742d69da3ff0.nq.gz
    ├── 2c16e1628b27af7feec542ca25adbb79addf0b97.nq.gz
    ├── 2c267a5ff3e6d13e9b7a5557b92df7550304900d.nq.gz
    ├── 2c870f61ef8c37b0ff83e9dd050c89378d90cddf.nq.gz
    ├── 2c931497440932230bf36109a3ebf8732c441702.nq.gz
    ├── 2c9db6333a5e208a4a0bf46a99bc9efc9acadbc5.nq.gz
    ├── 2c9dfa888268e13bdde453b7c952d61a0d85f209.nq.gz
    ├── 2cee2888adb44a2253c6e4df4dd0489d2d3c42c8.nq.gz
    ├── 2e10a6483655745c56381a48afa7b6d4ae9cb5b3.nq.gz
    ├── 2eb694a94093e21ead81e7688d7a4e51a5802fc2.nq.gz
    └── 2efcbfb35372a902d6b4e4b6140109c4f0cf2e43.nq.gz

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
*Parsed on 2026-03-29 by [repolex](https://repolex.ai)*
