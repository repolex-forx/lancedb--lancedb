# Repolex Knowledge Graph of lancedb/lancedb

RDF knowledge graph data for [lancedb/lancedb](https://github.com/lancedb/lancedb), parsed by [repolex](https://repolex.ai).

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
lexq download lancedb/lancedb
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 93aa0df9729840c6f059976b41e193b5e8922fa7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 93aa0df9729840c6f059976b41e193b5e8922fa7.nq.gz
│   └── repolex
│       └── 93aa0df9729840c6f059976b41e193b5e8922fa7
│           └── chunk-001.nq.gz
└── blob
    ├── 0093169156808aa6a7818eb14f3aa980f503c008.nq.gz
    ├── 009b7d78584859361163b91eccc42f596c9d9914.nq.gz
    ├── 015c4127ea7ca782b9b1c7c10278b211f4b49c12.nq.gz
    ├── 0185f20c7d34d9c6a3d4951b5768df02fbcd56bd.nq.gz
    ├── 01cc4a9de52900925a38ddd42b4349c0ba0b4bc6.nq.gz
    ├── 0223b829c4c32e90cf9f4c2e76d6f7d33fa592dc.nq.gz
    ├── 022b845e103af7d114eddbdbd56efb9317f2d4b4.nq.gz
    ├── 02d298c7b20c287d5ab8316a1cc7b7867017736c.nq.gz
    ├── 031f28cfa296ca11c38079dd69c559658eb89d55.nq.gz
    ├── 03725d03fefabd2185dbf2925558f07539313970.nq.gz
    ├── 03bc434e6ffd8da8c6bb60d6ecf3d41219da9a0a.nq.gz
    ├── 03c87db59ef732e5e9db7f38b7b99e37540e128b.nq.gz
    ├── 041e55247d67249366c6d427708b15f7541ce0f8.nq.gz
    ├── 04602c49f7af14b99d5d47adefbcba95e5b61d1a.nq.gz
    ├── 052d10703ec6365ec7dff030f2eb24f15d8a7c8b.nq.gz
    ├── 05803f2390ca25ebc2956306f700a5101f6640f0.nq.gz
    ├── 062a1dc960547e0e9d3e133e3a30240b66aa840c.nq.gz
    ├── 06e3599f5bd8485de7d99cc2f6c358277df6dbca.nq.gz
    ├── 07888c548aa854882c36e98caad5df4ef8c3df63.nq.gz
    ├── 08596469056b23d77e2c9b7f733d0937eeb0279f.nq.gz
    ├── 09b902f4d21f822ad5ea19c3d0831934a2f8f913.nq.gz
    ├── 0a3c9834c7133eb245391cfc8e06b4b0ed96b237.nq.gz
    ├── 0a4e3990e8040b92d75e29a95820ca5335aacc4c.nq.gz
    ├── 0aa94827bd915c10a4d84bc477c7b8f0d196d8ef.nq.gz
    ├── 0ac0971e3eb336d7ff8f1ea9a10da5efeaecc709.nq.gz
    ├── 0af8623b4c2b11939a918eac610331760da0ea3c.nq.gz
    ├── 0b2f5616a007d8ceb2e43c27645551ceb93b61c4.nq.gz
    ├── 0b44569e38978dd3af5d9c6d57f0ee65fe256b92.nq.gz
    ├── 0bd5abf97c22679a99d177b87b4b5494058716e8.nq.gz
    ├── 0ca796b6be304e3808c6f7002b9a83c68df97736.nq.gz
    ├── 0dd880cc0c3110d127a7411900581b6c0d8fb747.nq.gz
    ├── 0ddacfb3b1e117f1f12c97f3547cf23226fefdfa.nq.gz
    ├── 0e420c894b1d95dca80d661bb688b8f6e8de3604.nq.gz
    ├── 0e7383316f5ec4cd7b31a72cdea0ca8ef9f47873.nq.gz
    ├── 0e98221631a0274b8048be2b6e6c3408d0c5900b.nq.gz
    ├── 0f0cd6911c86769cf5c464d92377143a10c624ab.nq.gz
    ├── 0f41ba9277d6b70e1baed35ed43ca87efdd334b1.nq.gz
    ├── 0f4a9cdc18957e67a71fb8a2c0c7692cf3d497be.nq.gz
    ├── 0fccf430ac81895f77dbcef70b3d989097efeebf.nq.gz
    ├── 11f0cc61b7950433402b6349002aa2f5af449b2b.nq.gz
    ├── 1226773640bef55c626d4748b8a37c7717bf65ee.nq.gz
    ├── 1329b99dc90c1b49444a4bb853eda301e0625f37.nq.gz
    ├── 13338f4ec53933c30c4ad000f7489803107e3be9.nq.gz
    ├── 1365fa58443fc96b6e9ea714a5e709ffd590d657.nq.gz
    ├── 136b7f83310fe0b54ab40ded798ebb06e6a336d3.nq.gz
    ├── 138cfb230d5487414c6c6efda3ef8413346b59b9.nq.gz
    ├── 13b39348f1a8c6faff32a0ee914ae7a8f3170035.nq.gz
    ├── 14141a8a7787838a5388c4719cf52753ba92e87d.nq.gz
    ├── 14846e037fe88303faf6fce6f95dd7791b2cff09.nq.gz
    ├── 14d3595bc7260c30d8dcd777b1d7d5c2b9dfa241.nq.gz
    ├── 151388bbd170f660c8d89d56147968e91f34b135.nq.gz
    ├── 157018e16e424597f7b50e0dbb1d39414ff051e1.nq.gz
    ├── 161575285cd4c05dd54626ff552c1a4201a5363f.nq.gz
    ├── 16840038f5e8b9f3c055ec218125ed34acbfbe67.nq.gz
    ├── 187721c00928452a935f4056010e06b344d0a6b4.nq.gz
    ├── 189bbe53c734b69764305a13162d806019bcac48.nq.gz
    ├── 18daaaae81b852a8d91d294a37a51b91421e7843.nq.gz
    ├── 19529ddf8c6eaa08c5c75ff80652d21ce4b72f8c.nq.gz
    ├── 19b2a544088a9b0514cbf906036cbc0f061e19d9.nq.gz
    ├── 1a354eebb376a9625c8df3f477d7f428390d9f24.nq.gz
    ├── 1ab5a8effc5edd9014aaf1468b93f5f2a79ddc0b.nq.gz
    ├── 1ae7c48e2160d43ff0040f0899b989e3d2a4faf1.nq.gz
    ├── 1b3311c88639d281c34d63be8cdaeb9769d1b2d0.nq.gz
    ├── 1b33dab6aedcaa34f76624577959f000431a9908.nq.gz
    ├── 1c31d37dafb384597252bf361908efbb56697a4b.nq.gz
    ├── 1c35d5120b5111734bcea85e8f2bcdba80492c71.nq.gz
    ├── 1c368e2f53aca8facc9053152133b9f18c2fc2db.nq.gz
    ├── 1c4b4bdf3ed52cb09a7502ed12bb5772bfc0a01e.nq.gz
    ├── 1d0566730a6c72ee7b28bd333964ecfc93975014.nq.gz
    ├── 1db4e734482a845471076ddcad4718a13ae7f259.nq.gz
    ├── 1dd81ff984198edeb9893123a609623e7b628601.nq.gz
    ├── 1e16946771209ad817a62471946b061bf4b22afc.nq.gz
    ├── 1f326e29a721dc6b8caca32c4bb1b9a0cdf4b6e8.nq.gz
    ├── 1f50bcfe979863028b87d9c0fc0e2882c50cd009.nq.gz
    ├── 2089838bb47119c2bca1c756724a9716a1a9a6b1.nq.gz
    ├── 20f0a020ab0f11648a9adb345cc401ecf4e5cf68.nq.gz
    ├── 2186d69631a51989cd9f13e746feb08c1005f065.nq.gz
    ├── 21b8c9c47fc659f942e0e7da3188165ee14cc0dc.nq.gz
    ├── 21c081ada5d763315cafc5f920eee7400c6f2679.nq.gz
    ├── 228faa31beca94ac99863e265a9ee46047f39b46.nq.gz
    ├── 2290b77fd276599be0a086b33fb6d34a22c9a668.nq.gz
    ├── 22c430cf2284ae7910083e07a355be67162237bd.nq.gz
    ├── 23a30f8b74ad4a54f2477250eaa7430af506d862.nq.gz
    ├── 2433114b6330e102a970c49cb572ed3b1ac7f72b.nq.gz
    ├── 264880beda852db349297384ae015691b72b904a.nq.gz
    ├── 26f2ca4c8e25868363e5879d4d19a1bc96a66dca.nq.gz
    ├── 276ca263dddd4a530061d04792f9a1d58a7937e8.nq.gz
    ├── 29d7d64a71a2863925272ca9f49c9089d0da9fec.nq.gz
    ├── 2a7d4e9cc9a1740b6ba1fbfd3162ec3dc9880a63.nq.gz
    ├── 2a824371f824a82741aacad423e6552986f65af6.nq.gz
    ├── 2a87281a33b232cee54a8247600623ddf15870a7.nq.gz
    ├── 2b065c82a9f9d5269656ac3aedcff6159ccb8dac.nq.gz
    ├── 2cc76a94f35dfd87f51b041b9147edbc22883988.nq.gz
    ├── 2d1f33e239c9542376e69b5fa012633b8218417e.nq.gz
    ├── 2d7d48bb70824db4eb6ffb8219cd8e875aa5dc3c.nq.gz
    ├── 2eae90ed3742a2a29b1770b142ad6c04ee40b32c.nq.gz
    ├── 30113d3a6cd2cfd80d1d00474ddcd7757f7ee966.nq.gz
    ├── 30ad9d3829424ee1cf84772fbbb6c2dbece3b70f.nq.gz
    ├── 30d283cf75600e9222ef9e7b4ac680a158dde5af.nq.gz
    ├── 311f56a4dd343689b8368eb136032b0fe31ede43.nq.gz
    ├── 31a1b1711513c1c4f9d2ab125f19913847448c6a.nq.gz
    ├── 31b3d16ac661c8efaac1a06ec160b8f0f906f4c8.nq.gz
    ├── 31f5a3d0c6b600721639c5cb913cfc118efdcd25.nq.gz
    ├── 3210d05685a30565c7fe26ae8f91ab078429209c.nq.gz
    ├── 32165ea009326470f25238466045de6ae61728bc.nq.gz
    ├── 324b6fda55bbf51d657c85d2453ab0ebb8fb50c2.nq.gz
    ├── 327e630ca66a3b13e2f2be76175de5a9f36565cf.nq.gz
    ├── 331dbd60b9dfe7027c51f1ad4526a194cceca70e.nq.gz
    ├── 336ba961bde43cc1ed4d4cea05008d890bfe46e8.nq.gz
    ├── 339aca323c8e62e6aa826076d9c436d67cd0ff9f.nq.gz
    ├── 341673b3772557801ff12d27c7fc312f9075f505.nq.gz
    ├── 349a8eca594965c23739fd077239e66a90202f31.nq.gz
    ├── 34bb9bc5e19e28f2efca6c1deaf10bef09215f3c.nq.gz
    ├── 35af9e590cb9de603402d728e1b2bfebe72d3b1c.nq.gz
    ├── 35c10be5942cc7469f7e2297f771dc1de6d101de.nq.gz
    ├── 35c64d4a931c30a3e93145c92bd056fde1b772b1.nq.gz
    ├── 36d46b6bfcbca823023591b487c81fbf98a4a5c0.nq.gz
    ├── 36da98907e60e95664ad8ecf75ab744d6475db9a.nq.gz
    ├── 372a1ac428ee77ce183ced90f1af0db04d03ecad.nq.gz
    ├── 377712e987a25d5b179023cc48fe9264242fec3a.nq.gz
    ├── 37f12bc16c83294c54352938bee26b16d30cd581.nq.gz
    ├── 3812b00324fe3c47e4b99e7d970a4b4631445cf9.nq.gz
    ├── 383998bb53080c57dfe2b0f556aa04eb9d87aa61.nq.gz
    ├── 3914caa748cfd7d6851b7414b674546c3f4259c7.nq.gz
    ├── 3953b79028588555807e437877edd435b6d2e450.nq.gz
    ├── 39a7bf6ecb4eb2a2924d307edbd64f9ee5ee3ac9.nq.gz
    ├── 3a345761fbc0c8e85f9a3f781173cb09a8042f20.nq.gz
    ├── 3b01438d56748c86b1ca9fa6a1a133810c813ef6.nq.gz
    ├── 3b62e1160a510af81f9fda7a53461e83f5d6cb89.nq.gz
    ├── 3c751e26b21e014669961ba93f74a9a03794c42b.nq.gz
    ├── 3cebe6931c6984d56153f9eb99679600456ff3d6.nq.gz
    ├── 3cf70d332a2426ed7e4607a3031c4588cb3af5d6.nq.gz
    ├── 3d469393cda93c425d04c24f8e08e7e56992e107.nq.gz
    ├── 3dd8d8125702a0dc086b065b4baafbae81851fb4.nq.gz
    ├── 3ede0d6869b03dcda2402965b2e347bd74b71eb1.nq.gz
    ├── 404abedf7053a6342d75be415dc54e360c873c88.nq.gz
    ├── 404efafea58f2f753364d3b829bbedaf702e6188.nq.gz
    ├── 40a750f0bc9a8c7ee39d9de65b60f2a8710712d2.nq.gz
    ├── 417c51c30a23f0cea489d0a158fb7b196922959f.nq.gz
    ├── 41f6643a61d9b55f1a2a7231fedbb6e44510b58d.nq.gz
    ├── 42b06d84d644230e32ad704d9ef6c002c8f295a6.nq.gz
    ├── 43c229a0a582019552bbea1384086ca931419538.nq.gz
    ├── 43e2e1e8a5929b4f876f9ab75f53756df8a05b17.nq.gz
    ├── 43f7b44ac519310e5d13e8b2a72a4848db0695af.nq.gz
    ├── 444c4c3f0c590954bd624a890d743bf357250952.nq.gz
    ├── 4516385d57a5dd4a4faef8ddc5fd7b884db87d3f.nq.gz
    ├── 45aa83f5a942a969595c5306def1e3f8cabc1c46.nq.gz
    ├── 45fa3d1b06a151553cb8a5500df34805fc55da72.nq.gz
    ├── 46b06ce7e5ba6ab3b51ce509e32f7fa75352a67e.nq.gz
    ├── 471e174df44a74c7203f7135abf5ec535886f776.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 48214a5d9ff253cc2498527cca8624974fc34c66.nq.gz
    ├── 488f8c03816dc8f31fc864abdce1c87862ae1443.nq.gz
    ├── 48fd66183b908018cd15184c26465b92976d72a0.nq.gz
    ├── 491f7704a2d67b6a328c9146718810419cd5da18.nq.gz
    ├── 49a04ac109596c03e29c60ef82e1654bbd0325d1.nq.gz
    ├── 4a1075a0ecd5400136907f20cd2977377dc34a92.nq.gz
    ├── 4ac524cc694751057150af1ce487a427bbf227aa.nq.gz
    ├── 4b650d253c327195d63833f8df4be2117314e971.nq.gz
    ├── 4c128f4694f235d98d0ab13e0b84f3a6d63849b6.nq.gz
    ├── 4c91445a5cb6290fc3c3630f4f9bd9a0fbce3348.nq.gz
    ├── 4cbbb0822e3b554c5a025f0c65eef77f7af8961b.nq.gz
    ├── 4d700497fa0948e9d8ded8ad3a5fa2d2431ee594.nq.gz
    ├── 4da1927bea452b3f72aa3daf1882d4b08a57c04f.nq.gz
    ├── 4dd9eda4f4911868a01932f16c8bd03bb752c714.nq.gz
    ├── 4e28855cd588d431fa82f99b99298aba5f439ce6.nq.gz
    ├── 4e801b76764a32546566f21dfed9aab2b65a8d90.nq.gz
    ├── 4edd4c522242ace25f5867f4aa400b1cfee127ba.nq.gz
    ├── 4f547a30b4cea642709a1b06202c82b0c78f501c.nq.gz
    ├── 4f5f4d9e28fc6a2f83d19259107f5dda9cc049ce.nq.gz
    ├── 4f9540ba358a64607438da92eebe85889fdad50a.nq.gz
    ├── 506727a19f65eedb367ebfed7392482c64cf12e1.nq.gz
    ├── 5132d648e2a61bc875fcae62c987f23d7f489e07.nq.gz
    ├── 51be4abb854954160927ccc8bb17efdd08e279ad.nq.gz
    ├── 52bb5b87631f2d6beea28b5ad9b1e21146352167.nq.gz
    ├── 53ac89da5c1b0cef327680cf2e64e396a8cb404c.nq.gz
    ├── 541a85598043b9fcf65da00530dfbd237965961d.nq.gz
    ├── 54c4ba691fa0cf8dd70e6503001fbaf67c90b4ef.nq.gz
    ├── 54d4a38f5a3ba99d0b25783c786943d8ac3215a7.nq.gz
    ├── 55858fa9a9022652a1210483f605fbb6eb3b70a8.nq.gz
    ├── 55df0c82b1f6d4009b93322e69f257c69b86488d.nq.gz
    ├── 5691bbf62c43ec6e8c60e6d058b60d70e75361df.nq.gz
    ├── 574a0d71f33d270c892820de33b4667481569861.nq.gz
    ├── 57704d104c8b56b90459a7d0697feb5e70f07b04.nq.gz
    ├── 5771cfeb55ae989dd2609ce1951b3e41b61e8677.nq.gz
    ├── 57e337d324a378563949bfe4427c11aaf2640a6c.nq.gz
    ├── 585737a5a7af048670f005e95dac29800d29b9fe.nq.gz
    ├── 585c25a9499ed2e8faf8b4f81ced09ccc20e080b.nq.gz
    ├── 5880537226e4018af35a0b40b3f41605d6ca38a9.nq.gz
    ├── 58df345a912f27a929fbac758a35b35c0030d24a.nq.gz
    ├── 5a568d66a5f91bab0588961199609d2d54e28951.nq.gz
    ├── 5aafcf4a8c61f3f0ca8e2659c9a122901f82916c.nq.gz
    ├── 5b29753da12e37d3b206d67f2ec908b91a7ac03d.nq.gz
    ├── 5b50ddfa3183d02cffed9085806007d917684a68.nq.gz
    ├── 5c087f8084e49c86e34ce5f6de4fa7c548d73e18.nq.gz
    ├── 5d02ca02450ab796315dab410c640df1aed2315b.nq.gz
    └── 5d133c3095beabf97a2451ed18459da0efe999b6.nq.gz

8 directories, 200 files
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

[lancedb/lancedb](https://github.com/lancedb/lancedb)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
