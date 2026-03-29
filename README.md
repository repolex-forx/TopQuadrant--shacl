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
│   │   ├── 0dd76c876a0c85732eeabd4f31e25c5cb52b118a.nq.gz
│   │   ├── 14bca9ff69f6244f2e13e75295a91719a2a599d8.nq.gz
│   │   ├── 4eccdcfc1d93e3742e07facc0132eb9ff7f75032.nq.gz
│   │   ├── 64925637ab08f85850f97bd2841069ef44f5a7a6.nq.gz
│   │   ├── 6703a39182c4996ad23119f96f7f0d52640bbad8.nq.gz
│   │   ├── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│   │   ├── a40627da5df455535d3519eb6629057ab52a2843.nq.gz
│   │   ├── c3dd95eba75f3f5c3c61a0187af349f3dd021602.nq.gz
│   │   ├── c99e79876b062c6544bc23fd87e5e749458348dc.nq.gz
│   │   └── f7b76d75821b9b1851f4d840308718f4883acd55.nq.gz
│   ├── lsp
│   │   ├── 0dd76c876a0c85732eeabd4f31e25c5cb52b118a.nq.gz
│   │   ├── 14bca9ff69f6244f2e13e75295a91719a2a599d8.nq.gz
│   │   ├── 4eccdcfc1d93e3742e07facc0132eb9ff7f75032.nq.gz
│   │   ├── 64925637ab08f85850f97bd2841069ef44f5a7a6.nq.gz
│   │   ├── 6703a39182c4996ad23119f96f7f0d52640bbad8.nq.gz
│   │   ├── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│   │   ├── a40627da5df455535d3519eb6629057ab52a2843.nq.gz
│   │   ├── c3dd95eba75f3f5c3c61a0187af349f3dd021602.nq.gz
│   │   ├── c99e79876b062c6544bc23fd87e5e749458348dc.nq.gz
│   │   └── f7b76d75821b9b1851f4d840308718f4883acd55.nq.gz
│   └── repolex
│       ├── 0dd76c876a0c85732eeabd4f31e25c5cb52b118a.nq.gz
│       ├── 14bca9ff69f6244f2e13e75295a91719a2a599d8.nq.gz
│       ├── 4eccdcfc1d93e3742e07facc0132eb9ff7f75032.nq.gz
│       ├── 64925637ab08f85850f97bd2841069ef44f5a7a6.nq.gz
│       ├── 6703a39182c4996ad23119f96f7f0d52640bbad8.nq.gz
│       ├── 8811f78129a3f3fe0f586610324b60d834944f16.nq.gz
│       ├── a40627da5df455535d3519eb6629057ab52a2843.nq.gz
│       ├── c3dd95eba75f3f5c3c61a0187af349f3dd021602.nq.gz
│       ├── c99e79876b062c6544bc23fd87e5e749458348dc.nq.gz
│       └── f7b76d75821b9b1851f4d840308718f4883acd55.nq.gz
└── blob
    ├── 001a1218b5ad24b6aef344039895c5a661677a19.nq.gz
    ├── 007e23655602b6f699f9ee2696059ae72db488c5.nq.gz
    ├── 0087b5bdfb4e0e10470dcb5b8657cefc9a2c7ed9.nq.gz
    ├── 00f6d4a0ea1e635b119271dbbe5b6edaa38e0039.nq.gz
    ├── 01135b34e6ef6c18cbdf2134f5745e260993e33c.nq.gz
    ├── 0117f14eefa2376d3ae6710269ccc41913697dfc.nq.gz
    ├── 011af99cc07f2d6833e8f3bd1ed5a31ddbf77bad.nq.gz
    ├── 01287fde8334cfd86f8d61e00e53cee274439cf5.nq.gz
    ├── 012b47e90a9569c678b99eca8d94dfd4402fcd1b.nq.gz
    ├── 017b5f1863a73a0bff2ba9db5287e292b4f08c7c.nq.gz
    ├── 0192962b5a921db9ad60fb8805965033f15278bf.nq.gz
    ├── 01b5fd6c9e8942b4c9df569abe0a9c157b79f0c8.nq.gz
    ├── 01b9bb1c9f8b58a658fe76d513e1f2000c972fc5.nq.gz
    ├── 02004c916f43f7266a96783f29c62c512d62a945.nq.gz
    ├── 0203b8253dd696882e1dec7d1a0a71162865fcf9.nq.gz
    ├── 0209dceb728289c34a6de66e63bcec631de5d14a.nq.gz
    ├── 02474c4951d4a4ac4053be3f8cb877a5efa89830.nq.gz
    ├── 0259a0cc6d3b0f5c84bf3429d00cf4289a780232.nq.gz
    ├── 027e21243e154213244fa9d3f66ce6b4ee8f5d2f.nq.gz
    ├── 02b085ac16b9f76064727c53dc459e3b5cc34225.nq.gz
    ├── 02d0e92e607c3b1ab3560428d6c419610d6f79b1.nq.gz
    ├── 02d20b71faf65b98f5394670d0a5adf3d7cd6488.nq.gz
    ├── 02fd3aa47b59a5035a57e8ef90afba08641138ee.nq.gz
    ├── 0302f16aaea1b7629c46fc05e26a110879652cfe.nq.gz
    ├── 0319b804a7dc81ab02406bab018c7f15b15aac9a.nq.gz
    ├── 031d13447b9d28c9cd53dcc839c84d5c7c6a1f26.nq.gz
    ├── 03d7bb1b28253e857c42e06b85bbd80ce36307a8.nq.gz
    ├── 03fcd883fc089ab48ab2b0d8f98dc170f1336b7f.nq.gz
    ├── 040b595d0fe1a05d883ba6049a7522df5366b27e.nq.gz
    ├── 041d084bce67ba00557d8d4c18c366a3c6305fd3.nq.gz
    ├── 044224ba1f5dbb32cd2d344d217a462ff89f8fdc.nq.gz
    ├── 045b207ee53aaa85438504ce975d06fedaa24538.nq.gz
    ├── 045e0f585a2d5cc5ba4b3eb7d711acc968736aba.nq.gz
    ├── 047d415e2ce3bf7979f07d75d9681a32e8a96f66.nq.gz
    ├── 049bada6acdb5713abf242a649a20d770c7f8d57.nq.gz
    ├── 04b1ecfde5c1c06d238906d8dfc59327c4b48a00.nq.gz
    ├── 04cfa2c1a8566d64dd12fcf7a8e895fe02e1856f.nq.gz
    ├── 04d7d2021d159a7d965ddeddb56746bbdc919bb4.nq.gz
    ├── 050a4a80f5d3f2c200fe61d02bfbf7db9ba961f9.nq.gz
    ├── 054fee9fdcb5bb9d692a0f5c558636fbc7b868ef.nq.gz
    ├── 05580e8e421b7eaf6f5aad9e7c6d46ab6f9d7940.nq.gz
    ├── 05b585687914def468b6ff29ed62f884f1642581.nq.gz
    ├── 05d1dfce59729ce26ca6a082683cebee3d4ff869.nq.gz
    ├── 05d78766bacefcda1f169df287b24daeb755f8c4.nq.gz
    ├── 05f936e4f4e5fbf75d291aa59796d123f051b1c8.nq.gz
    ├── 061a55991c0700588f063168268816d97c572f8e.nq.gz
    ├── 0668f24e3518ea694d0e1997bfb2a367b8e9e208.nq.gz
    ├── 06880543e3da2be68fbb5e817b4e1fad919fb1f6.nq.gz
    ├── 068dd28f4d5dda3a62572033d4de11ac2bc670d9.nq.gz
    ├── 069ad950c2c34c2570edc38ff211694630cb12ab.nq.gz
    ├── 06ce96628a5dbeb17e2c095c92ab93951cdf02e5.nq.gz
    ├── 06dea52d27ff43548db9cceeb1d4e3e4e883d659.nq.gz
    ├── 07131290036d967363ad78f3de2a4d45a5ee9d28.nq.gz
    ├── 0728e2457b38966a2cc3c65292ec7df82710d2c2.nq.gz
    ├── 0746e8b6f6a370aec25fd2fdc966be9b02ecb9e3.nq.gz
    ├── 0757ef726bec810e32d5d30fcb83170be1ec857b.nq.gz
    ├── 077cfed9b31f14cca9cae46f61ae8e50c4b4bdd5.nq.gz
    ├── 07c49d0f3048c6dc5c17990617cfc3495f230dce.nq.gz
    ├── 07f119754613eed5a6e9d449ec2d1c2831cdc773.nq.gz
    ├── 080f23e9351f2ca73b46d1e88edef771c2348d58.nq.gz
    ├── 08567a32382441cfef9ba7b3d29e5f43e0a5ea5b.nq.gz
    ├── 0895b235e0bb81004e19cb7d9794bfe7504e7f97.nq.gz
    ├── 08cf25e9bf77a8f4e1b182b1205691224995088a.nq.gz
    ├── 08dc6efd7b6f89f86b3bcaf29ddc47f4a4e98c01.nq.gz
    ├── 08ebbf2a4ddfe7b409d3455ab5e14d3eef3a96ad.nq.gz
    ├── 0907c83f782a7a1cd6b01a681b0d7371412a87d7.nq.gz
    ├── 09294263297b6124bd13b50db17dd82437f9e743.nq.gz
    ├── 094781ab3e7ab799a2ee3b697fdac9e38c032191.nq.gz
    ├── 09535eb1583c1ad2fc03d0b8f515d5df4cf90ec8.nq.gz
    ├── 095981c5a6af8c68af1c472fec9f6636586d2072.nq.gz
    ├── 09865fe93d7e0c33a68bffe22d850900cc107f19.nq.gz
    ├── 0995343c9af856538b7c5663f4d9805bb0295abb.nq.gz
    ├── 09b3e045c87fbfc3eb780c85413e0415cdec259e.nq.gz
    ├── 09c0556fd5829b0ac1dbb69b24d4e25d081efaf0.nq.gz
    ├── 09e3952082a6e02cf25fd76abb2d171ac41a6075.nq.gz
    ├── 0a011898549cb520922c508ced22dbb6cc93f9f1.nq.gz
    ├── 0a05f0e6d34cc0c9807cc2bc65a408ba60d5726e.nq.gz
    ├── 0a23fec692a8b075394a8c99e03699fb10c85070.nq.gz
    ├── 0a31cf1feb201bdbd5d6a6aa01d5ab6e86333439.nq.gz
    ├── 0a5553bd700defd95cbbc6f9935278e16556607b.nq.gz
    ├── 0a7a43abdcc7543dc6c1ce03b63988e85b3a37c8.nq.gz
    ├── 0a860e23d5098d9e39232f7ef1c424c9487679c7.nq.gz
    ├── 0a8c069b9d914445625e06ac98a1454bf2dcb49d.nq.gz
    ├── 0add8f0781516a2c7d13891a9ead0ff4d123f908.nq.gz
    ├── 0aed7a8ada90bb348ddabebe590eac8dc715fce9.nq.gz
    ├── 0af7f84a1d1151144128d35b9721ef73da29d3c1.nq.gz
    ├── 0af84b834cc925d9afc87eb44c987f748ecb4f99.nq.gz
    ├── 0afb40535aaa23ae229bd123c0cb33f579512410.nq.gz
    ├── 0b2021ab79ca493a356df407849da6f8bdb9a3d3.nq.gz
    ├── 0b2c9da6b3719ba890cbeb76e477623c51d7c583.nq.gz
    ├── 0b32a567ecc27b52d90c2b2958cafac879c90eee.nq.gz
    ├── 0b886411d467222582289e9b0ec89fda50f89316.nq.gz
    ├── 0b8871776f19838ccdfeac10bf11a81fe69e4b19.nq.gz
    ├── 0bcafb0d22c4ae4cf596308d31caf095964f2c41.nq.gz
    ├── 0c5e194d39c3df25dcbc04a1b970f4a6baaad6b3.nq.gz
    ├── 0c8b64a081ae9e0c90173fd8be9f4cb300f2bc43.nq.gz
    ├── 0ca31c59df9185ba79e3853ee0742f541a83628c.nq.gz
    ├── 0ccb4e27f7f11e166ed498e98992cbc67486edb9.nq.gz
    ├── 0d01012327bc5cbfa6028c4efd1d21f0882263b0.nq.gz
    ├── 0d44fb839f466c46b03d6de06ee281fb548be457.nq.gz
    ├── 0d4c8c0721f13fad5cd98f85b71d1587845c1bf3.nq.gz
    ├── 0d6e7c6d0b7d1de2e0b0b572a0c9b7ad10e93f2e.nq.gz
    ├── 0e568f980a8b9244faf6e35ff84e2a4808cfc310.nq.gz
    ├── 0e58560ee87626c29d221075bcfa6be39edc2892.nq.gz
    ├── 0e687deaa1262df335dd25a8180fb2f9ba8ea0ba.nq.gz
    ├── 0e71c84eb15b4665e14515a7e69e60486f4c2f1a.nq.gz
    ├── 0e7740039b382f5b3d9c1659c8dd7bd8b5e67a4e.nq.gz
    ├── 0e87abd97cabd8da95275bd37bd45c8a4482d64a.nq.gz
    ├── 0e8a470ce963a5f5feeca19a14f64211afb3a801.nq.gz
    ├── 0eb2da0b7b20bc3b66eb1708f06e69fac82aa2f9.nq.gz
    ├── 0ee68bd9e36369520063cdca36014f1058ec6c90.nq.gz
    ├── 0eedf4a957b506dca982b2d254e3777c6ae6bc3e.nq.gz
    ├── 0ef0c9950a725da4ceffdb8b09bb0954e1224896.nq.gz
    ├── 0f687996ca7e3b0da3dc60aeef8a832e7671735c.nq.gz
    ├── 0f7028a18327cd126d25e65f64d16fca6ca140d4.nq.gz
    ├── 0f7c44e98c5357b0c1cf6e9177c28d08e8418092.nq.gz
    ├── 0fbe3bee59be5085274b853bc279ffacc5829f2c.nq.gz
    ├── 103c7ab589e32f836dab5832b7a02287eee8a48e.nq.gz
    ├── 107d675ad6659ba95b89da72a07696e3ecb4e8c5.nq.gz
    ├── 1080e3409f6c5cb89c6b4e77b5a6f4fd4b38f594.nq.gz
    ├── 108eeaaf7f09bec444e9376e7d2c4bc7096baacd.nq.gz
    ├── 10e68417f97b8300f1d546d1392668d6898d0dc8.nq.gz
    ├── 10f643965dbd5649f58079726e3698fa64f47abc.nq.gz
    ├── 115783714a56806491f80693aaffe3c08eff90bd.nq.gz
    ├── 11bfd53b8101cc4019cc5d0c14586d87de0cb9e9.nq.gz
    ├── 11c70c5691a4ee9463a433291d3a0d0040e134b6.nq.gz
    ├── 11ce7f753725591406026006f58e46e845d7f539.nq.gz
    ├── 11ff2b2bef5d13ef820ab344b885cc43190ef07a.nq.gz
    ├── 126abb328f631456b73f52364a8a86ddffbb2c7d.nq.gz
    ├── 12981c17b267c772ca4a809eb90dd8d90e4f7c75.nq.gz
    ├── 12acd1f35677cdbb8f307536dcd0f42734f70db4.nq.gz
    ├── 12c41048cb50ce6f14a8f0783756833deab37770.nq.gz
    ├── 13132f343aaea6adef97a5fea045ecea915adcec.nq.gz
    ├── 133d88e93ad5cb48f770d7c0c5ddc7f723a489e0.nq.gz
    ├── 135069686b2ecc36fdb70f7915e9a9348dc36b4a.nq.gz
    ├── 13532f4806c5b7933980f21415870f4e9a38111c.nq.gz
    ├── 137e4a904fdefde0604e9f37aa2d1a81808aff0e.nq.gz
    ├── 137f6e37629f8108b1265752c935bd33f2da8f13.nq.gz
    ├── 138af2003c519ee21df9f666aca93f2b3cf800f3.nq.gz
    ├── 13c518fd7b9df962304e04a1ab03ca76dbdded08.nq.gz
    ├── 14308e09df5df41bd48cf9e79b96ac834dc36f5b.nq.gz
    ├── 143afd2bde103dbd1bd03b4a6c168aded4f98067.nq.gz
    ├── 1446f27f900371ef3553799c7ade56b7c5d082b2.nq.gz
    ├── 1447ff564e08fa06f847a9ef092f207beccd23a9.nq.gz
    ├── 147c08d4ac812186ddf925d9fc403a6b45b51f72.nq.gz
    ├── 14988d5acea87c5b4c235992a29a6d74f9e7c878.nq.gz
    ├── 14b697b7bbb0d85e8d8ee19141a2a92d9ce211be.nq.gz
    ├── 14f51d525df90b7dc0bee62576ac33cca8eeb5c8.nq.gz
    ├── 1504de65eeef162cce25a3af92a2aaedac230698.nq.gz
    ├── 150519f1521a2509f7e39eb7691cd9b3b3e6623a.nq.gz
    ├── 15714858e646d563bffcf3718ff675f2c6a5ecac.nq.gz
    ├── 15a1a203bae84c9bd90d2b9e56784548137027f4.nq.gz
    ├── 15c4c5f79184de3e0673cebb33e63b7a3778428e.nq.gz
    ├── 16055f2d80e43fc4764d9bb4dbd53fde2ad0b3c2.nq.gz
    ├── 161687b8786403f446a4130dede57c50277bc6c8.nq.gz
    ├── 163499efca87b600f56fcbe8b73a0bdcda1487df.nq.gz
    ├── 16486a918c25a14e66cb5b1586580869b509e983.nq.gz
    ├── 168d7779f3840b6784aec8b8eb151dd34ea7c1ba.nq.gz
    ├── 16935625991038210bced04fbbabb3cc034ca24b.nq.gz
    ├── 16c89cc13733da44a37aa705233e6704c91106ef.nq.gz
    ├── 16dad16cb8a3bb56df42bc2732d14b9094bc0e4b.nq.gz
    ├── 1710b1d96b8e6688419edb211b5fe0fbe246548f.nq.gz
    ├── 178cddcbb9b81fbd4d3bcdf6596138f378c6f565.nq.gz
    ├── 178e21ca3cb91b9a90759ec2e36f253d5602b5a9.nq.gz
    ├── 17926aed3c9f26d1b72fd174165edab2892f2ff9.nq.gz
    ├── 17b0cc01456dce801c8fbcd31b4ca14feb9cb1fb.nq.gz
    ├── 17e04ce55b5eb5af7ef290ec5c7f54dec77b380a.nq.gz
    ├── 17e6e1f330b8e5ed9e3a35bf8db5edc313a38382.nq.gz
    ├── 17ecbdace189f8d19bffbc3d5ffe7121c8588803.nq.gz
    └── 17ff836a2eb55b9f65106e86e389357083690ff4.nq.gz

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
