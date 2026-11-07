# Repolex Knowledge Graph of allenai/atlantes

RDF knowledge graph data for [allenai/atlantes](https://github.com/allenai/atlantes), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/atlantes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7258902ee64123439cfa1db59aa1cf520fdf761a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7258902ee64123439cfa1db59aa1cf520fdf761a
│           └── chunk-001.nq.gz
└── blob
    ├── 00ca6919b94efc39106dc5f463443ddc17482cf6.nq.gz
    ├── 028cd1a08ef89a0ef6fb50f38a41566797a9c1b0.nq.gz
    ├── 02958ea1a22215e68e5c13c7f58d27a19fb4ef57.nq.gz
    ├── 02af32661515e15097f8ad548e67e4d953e039be.nq.gz
    ├── 033a5a3b03286b111c7dc410adce3a017401437e.nq.gz
    ├── 0492e45d86a4b635ae6152fa7fdbb5516652e352.nq.gz
    ├── 064836b86ed29f2e27cdfa6c8ef69ca81ba9bb76.nq.gz
    ├── 06951a3c63b213f4c0c042a225cd1ac892ba0aba.nq.gz
    ├── 081d64db29516cc9214d7760e2546c3caf48f99e.nq.gz
    ├── 096affcbc86fee6187a04d4f532daf0b7d1a0aef.nq.gz
    ├── 0adb1baefc908ed19fba9dac2de467d75d7f286d.nq.gz
    ├── 0b4e984b9ffd5efe258366bf00ee56e606c57405.nq.gz
    ├── 0bd05ca0d1db562d97fcf636cd73f344b610aca0.nq.gz
    ├── 0d130fbc6cf9870ca0648654ccfce549aac2ac96.nq.gz
    ├── 0deac1eb7edda249545e16b41af45b2a9f290f38.nq.gz
    ├── 0e610faba2e25df4067dc57e9d88d1dcc05224d1.nq.gz
    ├── 0f2146c891635add96c53c096a5c922aa1a37041.nq.gz
    ├── 0f96f8de946146b18ec11f20472d7bf02400416f.nq.gz
    ├── 1238431eaceae12b5506769787414e882633aaf1.nq.gz
    ├── 13c526d57042a088fea37b82f1245ce6bd628c6b.nq.gz
    ├── 147f5ace0bcbd3891916e2b805b2073d934facc7.nq.gz
    ├── 17e705596efdcaaf4eab20189323b4fb2325eaae.nq.gz
    ├── 182319e5f336bda0170a0fd99ef4ecc2d45de0bb.nq.gz
    ├── 1a4098ad753e839356c3b2aa43ba5874d45c32d8.nq.gz
    ├── 1a7ed54d2a2731b04ca3f704c4be98c117bf9af8.nq.gz
    ├── 1b89f19175e581023eab2eb04f3564d65a59e288.nq.gz
    ├── 1c489ea91e63970b4cd3106537ecff9677a91558.nq.gz
    ├── 1db2c1c23432e78e5cff73ea1c25ed9477e55a6e.nq.gz
    ├── 1ede6bad7f851a79ba03152d73228e02d3f189f5.nq.gz
    ├── 1f7f0fa20ed12a51918ed62a5beee47b9d737fc8.nq.gz
    ├── 207ef28e04fb9a1f252339d600e4360b182da427.nq.gz
    ├── 213b3d8b6fd678f888eafece43430d6442775e10.nq.gz
    ├── 214713fbafb0e0e46d04ff9a735fde462b06e5a3.nq.gz
    ├── 216e41e48723a85990f88937e197241f0bb83a51.nq.gz
    ├── 21e0387b1092bf83bb5714e01512ea58d9282b31.nq.gz
    ├── 223efb4d0037a83b6f752aa027a9ebc1e39bcbf6.nq.gz
    ├── 22d5e066b304f1735338fa64d4481b582d221202.nq.gz
    ├── 231b3d2ed1f0ba22eb0d4fee25d9dfebdf1e594c.nq.gz
    ├── 2547d6035f60d2bc1165e3e8cc0285bfe901925f.nq.gz
    ├── 266c119a5d9dc50210b1e083d6fa2adc8ad6b86c.nq.gz
    ├── 26aaba0e86632e4d537006e45b0ec918d780b3b4.nq.gz
    ├── 272292fbc1aa5e7c32129c6c140031debd4339f8.nq.gz
    ├── 27dfa3ef2f82390ca1f1fb7af17e6a17ab7ef141.nq.gz
    ├── 29c820545398dd876a6a6fbbdb40f30304bea8cc.nq.gz
    ├── 2b8779076d46982163e4a9deab4564a68a5c0557.nq.gz
    ├── 2d0f3fe0c72766617660ecf65ecb16278c2eca2d.nq.gz
    ├── 2d10dc909bf5d84ba80eba2046c9d2adbb0809b8.nq.gz
    ├── 2d686b31615f7770fdcd995cdaf45a3590934045.nq.gz
    ├── 2ec928af45439205db404b9f46877796780223b8.nq.gz
    ├── 2fe9b4861dad818f7c22c6b00533fc78162aa03f.nq.gz
    ├── 30270786f8d3db01c1ff88caf13dfbf1e09b5e48.nq.gz
    ├── 309a8fa12af91a415b3348bc590e73d5f10db87f.nq.gz
    ├── 3197e78f5da496cadf02906ad39c3855be5aa267.nq.gz
    ├── 329d1f8334fa1c1ccc2639304b78a7bfee311c9f.nq.gz
    ├── 32dcb246024d6d691c7a1eb273bb45d88c24d246.nq.gz
    ├── 33b4d2517efe11bd9145a1e4f7e3eae40a3820f0.nq.gz
    ├── 348e72880eb19a37d192ae7d5ae7d6f2f0cc1499.nq.gz
    ├── 370491c07118ae3b85fe2d459688f27a7928df8a.nq.gz
    ├── 375464e609f43e307068c43a4a04e6032f05dc0d.nq.gz
    ├── 37671712443ebed8bfac936d82a0205c0718cb09.nq.gz
    ├── 3874089f2bcb2b791e5a000c6ab6bf688c7d84f9.nq.gz
    ├── 395f503b973799cd66906a1c25dd595e40d134ac.nq.gz
    ├── 39eaa6063c16e75d3b00ef39c701e8d0a850bb4e.nq.gz
    ├── 3a1adfd3972cd7abd7500b87dde8eb3c9b40e825.nq.gz
    ├── 3ac9ec9eb3801d725e7adaa2e41c5af520db16d7.nq.gz
    ├── 3c337b2263994fa82b79e43813ea72b4007ab6f2.nq.gz
    ├── 3d1b455239d16eac8c45c249172e41d84a239ef7.nq.gz
    ├── 3d8c5f7539ed2cc255c83a5946fb8f3a4408225e.nq.gz
    ├── 3edbebb2fa47b7c01d0ed48b05af44518da8180c.nq.gz
    ├── 4048bc647e831b27e7ba487e7a41b1bb0c657d16.nq.gz
    ├── 41bba9bda22c31cbe5c39a5cc180a4f6f6f2bc7b.nq.gz
    ├── 4365b0579f6553aa3eb7a803eeba9fc89ba6949a.nq.gz
    ├── 44f71e97899d7f498fe9c110f3e4778270f4afc3.nq.gz
    ├── 4504a0319bfb763771c893116cb7b6ac8896d4b3.nq.gz
    ├── 458c448cee35d460529717315d690d8f77009ed5.nq.gz
    ├── 4602575791981e7c8989407757f8aaeaabd99d2a.nq.gz
    ├── 463d0b678ae23e727ca0bacb808eed5e2413bea7.nq.gz
    ├── 46d43e87637d10714da7f4c4183af151f7fa551a.nq.gz
    ├── 4835a4781c8906c023af914f963180b148e40c90.nq.gz
    ├── 4a5c08f478aef3cc918c6b32e2e040fa4e716e8c.nq.gz
    ├── 4ad3c2c1a087024d8aed7b3da00be0424a92f7ab.nq.gz
    ├── 52f6b6f1e9d8820f29917ed42dd9de3171df958b.nq.gz
    ├── 543e4424983413b55cfbc8b7fde1d234abf25edb.nq.gz
    ├── 54e3ee8a6ed2784837e9f6dccef03251084a5ea2.nq.gz
    ├── 560241b471716507b0f9da1ce52e8add237cce0f.nq.gz
    ├── 560d4cc61cad9eafc293c16ef3435f4863c9883f.nq.gz
    ├── 561fe579563dc37984289983d1513ffa6e54f318.nq.gz
    ├── 57f367944dc9b5a43e158c93d333dd59b602cc39.nq.gz
    ├── 58e533f83825c4e3e78f43348e564e28bead0220.nq.gz
    ├── 590b04be143460d825d6b2f2e34d5c0199542d29.nq.gz
    ├── 592e2bf67959ea38f7d07d303e0ba092c9dfbc65.nq.gz
    ├── 5968000c59749d957a27f0fe65cbac62fabda26a.nq.gz
    ├── 5a9a8a82cbdde30834fb729631e9741abd26e420.nq.gz
    ├── 5b4a62911558c924040e54e8826e14d3ceb6ed2a.nq.gz
    ├── 5bfc4a981ce34019100c5fc3d90c93b3c8f27ccd.nq.gz
    ├── 5c5644e2dea108dad5fb35da8fd8e8efeaebb0e3.nq.gz
    ├── 5e8eba5a363ea48066f80c3a9824ec8badb7ce06.nq.gz
    ├── 5f33ddd4ca16f2100e9d4702cd450fc9da3f57cc.nq.gz
    ├── 60f68fe0fec37ac18e6f7ff23e1de68d89cb816a.nq.gz
    ├── 685918c7ce3bafc4c4724517009a2397ff98e3db.nq.gz
    ├── 68e19fc666533aae7547b8fb7f5bc825aa7211d1.nq.gz
    ├── 6a337921c38ec8dbaeb2ab243a8acc2943e83307.nq.gz
    ├── 6ab3390e0d36df0c6bfaaf494e187c38feb2e0ba.nq.gz
    ├── 6b371bffe54472e00cfbea3b1096370d8c1def07.nq.gz
    ├── 6be3e38b26906c8cb3e0121121acef556a1fbca9.nq.gz
    ├── 6ee94877211844b08ab583e3086e4572dea5d3be.nq.gz
    ├── 6f359d5b4109bbd718e2715b1b618feb6a121be2.nq.gz
    ├── 6ff19de4b804f2eca2b2d72657dd908c216b6537.nq.gz
    ├── 70ae924317c040aae892da6fb3b94911c8571824.nq.gz
    ├── 715644b910e815484d78c6d061583081f0016c89.nq.gz
    ├── 716da075661ef66958282d3705168854a4b4bc1a.nq.gz
    ├── 72e3555d67fb97f102bd63fe6dfc2a5960c9b256.nq.gz
    ├── 741582af9c7fe85834797fc9f85c4b2de41d9ad1.nq.gz
    ├── 74b2dde3d8a8b2d2a11d615857955889e9e28128.nq.gz
    ├── 7576a975b15f91bd6d7aa5e176bcad0292b49c86.nq.gz
    ├── 77662d0c71a93ad523ffd86c81c10a7cb282e7fd.nq.gz
    ├── 78f6592ff93af9cc50f5e015a6fd41e413f243d1.nq.gz
    ├── 7af4ff73337c527690df67a83c757d3c437b375f.nq.gz
    ├── 7b631209feb530918eb04a2885d8fb96e10f13ee.nq.gz
    ├── 7cafc94f8aae565f30e6178d219eea4d7b68eae5.nq.gz
    ├── 7db2536bd166c713e45bb1094fbf59d70ea63543.nq.gz
    ├── 7de5d4201b81229501358c5a30f928cbc2ffddd7.nq.gz
    ├── 8052328e1457b92d8336f4b7a610ba700e9ed8c2.nq.gz
    ├── 81359c3855324d0f3373c8f79ac6b5aa1cdc5dc2.nq.gz
    ├── 82a66db64cf0348a156bc4b5b596ffe4fd5f360d.nq.gz
    ├── 835bcc8bcdcc07d5c5a70cc437b98ac4b6f7f784.nq.gz
    ├── 8686be910f2796d7a1dadd1c94ad473b316234b5.nq.gz
    ├── 87a183dd57676fb7549736c35f45bb432604a271.nq.gz
    ├── 8976ac0ddc6ca55fb7093368f3cdad5f8779e9e4.nq.gz
    ├── 8ae1774d1683968714b77a13003a293fda9f13e2.nq.gz
    ├── 8be18e4d45d27c874e126bcd08f4d346a48d421f.nq.gz
    ├── 8c99c7aa7c0a3dfcd5d6a2cfbefa4ac99f0cf349.nq.gz
    ├── 8cb3a9e96f5fab4cf3fc77e54714efcec4b47fcf.nq.gz
    ├── 8d080e88eb8c72ae4bf40d101125ae053b50b338.nq.gz
    ├── 8e8ceab71dfc7cd96a4f5458df53ca984edaf6a0.nq.gz
    ├── 8ea35be485b3a4eaa3c1710c498f085249102ba8.nq.gz
    ├── 8f0d07d4f5980771b7719e17cde22eab42787abb.nq.gz
    ├── 902e51418cf425525f7fc460af19fbd3a5a33a1e.nq.gz
    ├── 94522409a9a1104517670300139527f4722f85c0.nq.gz
    ├── 97c04ececd1b4f51e473840ac66682bc0f7861d3.nq.gz
    ├── 97c88c332e70c30fa4098c47dce9c478bdf81870.nq.gz
    ├── 98313e65da8fc01a21a5c2e8bfc66677875ad1f5.nq.gz
    ├── 9b5768ada01a463d011f6756d37c3684fe19da87.nq.gz
    ├── 9c943e4e177479aed00119922f17e53523945061.nq.gz
    ├── a0432550b3ccdf15b7111f214ab18b1782c5476d.nq.gz
    ├── a512d9c80c265706fa14c7aa07a4b6b3f9f68c61.nq.gz
    ├── a73a97782096e06bb091ba245913dc9f124b20a8.nq.gz
    ├── a81987ff5f94038771c47fe940cd6d3673220f7c.nq.gz
    ├── a992a904fcee0238b8464a4523488f2da5d8f91d.nq.gz
    ├── ab46a97f1d66bd5bb927f55b4fdc3ad06d6719f5.nq.gz
    ├── acc85cefc1a94c8b0c63f605d6681a6d2339fecf.nq.gz
    ├── af67303ee6a49d00738168fbd49c784a3e939205.nq.gz
    ├── afa7c7f5285a7efd8a3871f17a12d16aa282fa6a.nq.gz
    ├── b0510c39558f00fb4b336d258af8e188da6b97ef.nq.gz
    ├── b169471bd478118f39bc91856f54f32cf579c837.nq.gz
    ├── b24746a77e40a7a54028c7795a4b97c74b96a6e6.nq.gz
    ├── b50a016d299c53be08f590d013793395d3aa1278.nq.gz
    ├── b623f1ac0cfd2386765fb1ae6402ae191983ff5b.nq.gz
    ├── b6a928d9d583b1fa9f429883d3f0861c144988bf.nq.gz
    ├── b7bb76e8d028a8edff1ffcb1eeac85acc9fbf1f8.nq.gz
    ├── b844faec27da75afd1ab37cfc6d38e5ca021eff8.nq.gz
    ├── b96819218020a5d8ec2bd9e4121d89976f623046.nq.gz
    ├── baa551582fdbcee6ad6ac4ce56577596241e4a44.nq.gz
    ├── bac379ecba733e409377766f4d6eba34cec8c189.nq.gz
    ├── bb1a38be3287491aefd250ac94af4dcc5b5e65e7.nq.gz
    ├── bca41235bca33e6081dc51bd37076c5120bd25b6.nq.gz
    ├── bdc413d7731165a67e54c2377aa545db593b6842.nq.gz
    ├── bdf50a1e702a83cb057af1dd1392c261dd53a26e.nq.gz
    ├── c09b1ff4022dee999a400bee1fc232bd65a38790.nq.gz
    ├── c125f8d53c4885b406edc0c5ea455b0dfabb12a4.nq.gz
    ├── c18e431abe873a7ceacda01a04c6821587618232.nq.gz
    ├── c27bbb05bbbd046d24a3887927d0bdf2bebf9080.nq.gz
    ├── c2b2a427198831cf2012722daa0ae4bc862e22df.nq.gz
    ├── c320124a5f78d7a6a9a66b052ed403295546ca59.nq.gz
    ├── c420c70e4655b9c1a679dd10aaf48e93d7ad35bd.nq.gz
    ├── c577d3ea14ed55fc5c493799d25362f77702dac7.nq.gz
    ├── c6ae3fb6b341f45b976c3784a3832e93c4e200b3.nq.gz
    ├── c8325e177ba19e8e9da085c0c20874be418e3749.nq.gz
    ├── c8ea8fbfef28eb92491b8d934418f53fcb63e261.nq.gz
    ├── c93c9815b39132a63b13cb310c0961498457bd74.nq.gz
    ├── ca190a19429fc2d007c146e2a402a5e3c604ee6b.nq.gz
    ├── cc3d339bb4d39f998828148a21c911d35ac7070e.nq.gz
    ├── ccf2031da5f93dd042caec2520863e23f550892b.nq.gz
    ├── cf4810e13f5c3653946a92fc83032147a1750d4b.nq.gz
    ├── d210c8fd47e509c7024887f373d567fa4882b969.nq.gz
    ├── d260ef7a1a2e55cc4e189d1be4486d7d29b193b5.nq.gz
    ├── d4aea14ad8de083766ba95a54b05cc5200e03229.nq.gz
    ├── d5e0ffe13a18a37f49965b729dbbbd795a1c9a25.nq.gz
    ├── d5ed41173381207d95102cd53ea6ffe8cd7c1f78.nq.gz
    ├── d5f50534d70b875000bdb9a27ebb525ed5173886.nq.gz
    ├── d642c4cd6b42176036285c84ada8ad9cc4d8fc87.nq.gz
    ├── d7a7caaf4976bbb92b78472b4fc9136afdd11629.nq.gz
    ├── d88406543fbf8b16b00d1b1b97b702083b38ee0d.nq.gz
    ├── d9518347a050de91026ead98c14dff1b3316a03b.nq.gz
    ├── db1d0e1be6405b3d8150ed2bfad15048229e2b65.nq.gz
    ├── dbecc2f5d4df280cc6fa103dde0469ce8494be39.nq.gz
    ├── dc00b0f30d808a599e17955b6f2bdd1069e7406f.nq.gz
    └── dd1fc015fa8658e47662b3312d771e00625f6757.nq.gz

7 directories, 200 files
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

[allenai/atlantes](https://github.com/allenai/atlantes)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
