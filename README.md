# Repolex Knowledge Graph of pysal/notebooks

RDF knowledge graph data for [pysal/notebooks](https://github.com/pysal/notebooks), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/notebooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 55a073041ad8542cdae18dda413c1a961481dc6c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 55a073041ad8542cdae18dda413c1a961481dc6c
│           └── chunk-001.nq.gz
└── blob
    ├── 0063dd3740c38cea160e0bd1687af0bc2e51fc63.nq.gz
    ├── 012be2f3afb491e220ba81b6873d15ac8bdd3d57.nq.gz
    ├── 0254b17671dcb15f5b3e13c0f9d39bd1fee8d6be.nq.gz
    ├── 02e1aa4f95aef65ccd5cf7923f1534e469b9063e.nq.gz
    ├── 03379846103699a0e43abee20a2672dd339153f6.nq.gz
    ├── 035723e856ca2f072b8672c78b82953d18bdf8fa.nq.gz
    ├── 03f99b9df356bcefc2697d1e5bf4c7c07a011eaa.nq.gz
    ├── 04d41572640eea2c832740ba21384035615ef82a.nq.gz
    ├── 05b620fb0519cb6b929c34b2954d5339fea7087a.nq.gz
    ├── 0607806511af38135a0f355e9318cd22d2514c83.nq.gz
    ├── 06864dd4c060ce6805cd5ff13ea8711e76d2bd1a.nq.gz
    ├── 06d49417fcd8babfb837820a704c6cdc3afa1566.nq.gz
    ├── 0949fd170a90f8c3b85077225965d4cd9f847116.nq.gz
    ├── 098549dbe1d9393f1cc3a5c2347ca25329a38182.nq.gz
    ├── 09b978648c69f7a76eff9f80168c61192dacb950.nq.gz
    ├── 0a02b063ac7d22a352d0303e13a55ae44d0c370f.nq.gz
    ├── 0bbf01a0346ff67bcbc77d632a36eee4048eac73.nq.gz
    ├── 0c349a5ac1cc0e12c7996ae375785eab2dc615b6.nq.gz
    ├── 0c897728b4c5fb79305f1b7b01ea16f01d4b936e.nq.gz
    ├── 0d36c21ec1d57c2c238544a26f050d6188ab695c.nq.gz
    ├── 0d74c7e353108a8bdd3b41ce47d23fbea0a36462.nq.gz
    ├── 0ddcf54a0b0c8ca174e6bd4fc11ca0b06c7f11f2.nq.gz
    ├── 0e7332f0fff04e66812e33beca6aa41cf5756e13.nq.gz
    ├── 0ed9d046449145ad99339d0a96fc0c27686e791d.nq.gz
    ├── 0f20eb340207c83b37108554f82b18697fd57cea.nq.gz
    ├── 0f3ae8979d5fd2d302b5e99413c247f19bbc5eb2.nq.gz
    ├── 1023b934e3b6e6d2e8c1b13ae47cc9be93863d67.nq.gz
    ├── 102823c5aa2ed45f399a39e405fa06a6f0731537.nq.gz
    ├── 1046573aacb932cbd50548361216429d3e74e870.nq.gz
    ├── 10c2d0935c8b35ee6ca07d147f4360d1928ad9cf.nq.gz
    ├── 11b46d59a2b58eaa8cb5233621b24af54e71bc89.nq.gz
    ├── 123ca8dd9393aa436915523d91ac1fefe2e6ecbd.nq.gz
    ├── 12682a978ddff91afb358dc856252a8219fa597d.nq.gz
    ├── 12bf2e606b64e859d4e6b3e734fa7c35a88f2b48.nq.gz
    ├── 1307e5d6177af61bbe75620502502a76844362ee.nq.gz
    ├── 130d8b234f50a476d8fe49d3ed72f4634e3ab926.nq.gz
    ├── 138edea8aac2431e86df4bfdc17123a2fb3943d1.nq.gz
    ├── 13abb08f6363ee0e9b0974ffe881e7fbac57c681.nq.gz
    ├── 13d8abad84943b671ac11bf8cd8ddf6131274b4e.nq.gz
    ├── 148f464cc1ce7644c9623684f80f90960a09eb0b.nq.gz
    ├── 15012aaf0e5146cec85e4af23d98acc479cb91bf.nq.gz
    ├── 15f4b2d168a83fdf68bcd8b2fa870c0ca1a26ce7.nq.gz
    ├── 162d86b65a59890d057b2ef4c9feb4c26ad80baf.nq.gz
    ├── 16390ee417be9ce290da0bf878b8becf9952bf76.nq.gz
    ├── 16cf91f1538f7834ddb641204950f47c323485c4.nq.gz
    ├── 191613527b4d6b3b0cb5bd102ab7bd92bbf9370c.nq.gz
    ├── 196e93cc8b63685fdf12b9c816c3ebee978538d6.nq.gz
    ├── 19cf365c31c05fab462cfbf021b9e810aa6df4bf.nq.gz
    ├── 1a0f682079041cd83fd3822d7ac8d38679723336.nq.gz
    ├── 1b45602e94152f781a739ba935c126ad29edb944.nq.gz
    ├── 1bac9b32c3ddefa551b4c5ec8ea253ded1eb78ad.nq.gz
    ├── 1bd0097040ea5baf5e5069cf17f15234cbb059ed.nq.gz
    ├── 1d9d248fc721b5f3b7e905dc0212de32824853ec.nq.gz
    ├── 1dc97334ca702d1bc477ab705398151e9fdd4266.nq.gz
    ├── 1e037008aa5fc0040ceafd582565b9ddff4bd853.nq.gz
    ├── 1f36d17f8722fbcefa7241abb5f6da3a01e77706.nq.gz
    ├── 202020448a8381bd786b87660cc34bd963489973.nq.gz
    ├── 216038b900c2d620bd515fbcf21873766bf98d5a.nq.gz
    ├── 21d8e75c5669ad166065f2248e8224bc3009b32a.nq.gz
    ├── 222c3b1b0bf4afa7a3fea05e1b850531d4b7e7d4.nq.gz
    ├── 229292aa0c28f87586cf3907fe273b9647eb14ab.nq.gz
    ├── 23191f5c889cb98f99c0899cf996960741f6ffa0.nq.gz
    ├── 2342378c8210d6bd1174fa1eedf0f6e0446f092c.nq.gz
    ├── 2366720fb056250b9f18f6607425ca9e024fcad4.nq.gz
    ├── 240963c7a3953ec64aacfe482509a2885a32e353.nq.gz
    ├── 2476cd01a36cf6ce54b89c20fd9ff51c1ebb7bce.nq.gz
    ├── 25237c57801439e3e0dfd1e9d10586a870f6838c.nq.gz
    ├── 25d23db0efabd7d444c6119de96af39343776ee1.nq.gz
    ├── 2601006bfa0079de98fe91f3843ee9e121eefb28.nq.gz
    ├── 2680ebc4f288018769120515f37cecd6d0d21853.nq.gz
    ├── 26941c2efdd6136a534541e1fa41c6dcbbb0fe73.nq.gz
    ├── 27276c168736f60abf143459793e4cc2e7f84ffb.nq.gz
    ├── 285cef66bfef04717366bb1d4289b31d8ce01441.nq.gz
    ├── 2890090abc0c1be868e9f79f440966ce9e840f50.nq.gz
    ├── 28f3168a2aa16031907fda72836bcfd18943eff4.nq.gz
    ├── 290731a77ff9048056d3098f387880149fe8abf8.nq.gz
    ├── 2953c27db6be89541205e043fd4c63d7f65cc4eb.nq.gz
    ├── 2966f06224bdc3a8d5387a01d5fbe837a94810b4.nq.gz
    ├── 2a47e3f1940febeb6d21117b206c6b27c752e6db.nq.gz
    ├── 2bc6859117827f540e4ac816c9e5831b6acef016.nq.gz
    ├── 2c08f2f00a40d16800e76a63261ea9e1ac3fc0e1.nq.gz
    ├── 2c58810e24cacd2b70bf88732dae3e229f769b87.nq.gz
    ├── 2c6adfb778008cde95bfe475dc7e4f743682b5bc.nq.gz
    ├── 2dc7d22560aa0c33f9e20bf6ca1b6246d90eb184.nq.gz
    ├── 2e620d5196da41e09383307bfd4a9ed693994881.nq.gz
    ├── 2e76ea8151b3059aeff1e2e46eb88b0707eee9a1.nq.gz
    ├── 2ef836ecefee9c70aa5faf7ee80bbf2576fe09d0.nq.gz
    ├── 2f05d87e2546fc29fe4bcde0616b05057bea699f.nq.gz
    ├── 2f58b7eea755ba9eb0051d5d73690a083fbfef68.nq.gz
    ├── 30b7bb73af9fb2ba050d3d17f6f27151329b0598.nq.gz
    ├── 31354ae09292e8faa5ded57f42f613449aef85fa.nq.gz
    ├── 31ee5c6045cb6699e190e9e3abcfe50d231d1165.nq.gz
    ├── 3381ede54b9cdbbc87f0bfbca12c4f92ccf9f5fb.nq.gz
    ├── 33fdeb7ab5aa92ba67a2319de7091ebed4b290d4.nq.gz
    ├── 35527ad769e862a4b9aa4f6f1dfbf4deca820fe3.nq.gz
    ├── 35dbb9e70e5c1d3c6cbbef69db64f8d9f1ea5e49.nq.gz
    ├── 3665e52621fe1afd1353ae3d47e347814b23aad1.nq.gz
    ├── 36a71bf76ad5cfe6d51069831830b60d4833c26b.nq.gz
    ├── 372e1d642a4714c7258c00393afd6ccee4568cd9.nq.gz
    ├── 38d594ce4af0f20927d187e1bd814f0a3a3f42f8.nq.gz
    ├── 38fc00ceeb8a18933c87be5e2b21002abce7a3cb.nq.gz
    ├── 3b4a74e980fd0426d96e4fa2ddd9c2b5a1830017.nq.gz
    ├── 3ca2b9bfd167f72273defbc61ae0bd6c7b0b6327.nq.gz
    ├── 3cdc7e3ed01475799f83be6a5e06301eaab70aff.nq.gz
    ├── 3d2f36c3cd558ecf918db62105cb1cd117862d01.nq.gz
    ├── 3d9097106de0713ee0d15decc3bf2c0209d28ee5.nq.gz
    ├── 3e59d7df699654076a9b7f1716761fbc381d2e81.nq.gz
    ├── 3f87ae1cbc98ac71d9d07b5669edc08ed1be76b5.nq.gz
    ├── 3f8fedb98bfc3aec26aaeabc6900d9db73ed5e87.nq.gz
    ├── 3fbc7f654509407c81835e1a6c8da72b0dbff0b1.nq.gz
    ├── 4038d9e69bba533dd04e8cc63e29e5550c50d6f2.nq.gz
    ├── 410a818974efa70a2a3353cdbc0e7848c105ea4a.nq.gz
    ├── 41ed876b701702d0db2876449f259be0d6f43865.nq.gz
    ├── 43116a9f731bf3e19b8fd420273e07ad2fa278d1.nq.gz
    ├── 43c7e5b79bcf3651c0184c0c4fbb3a3fca09123f.nq.gz
    ├── 444ff345578003b1ed714a66321c7211acae20ce.nq.gz
    ├── 44763286bc03a64dedd07d0c73910f10b2d13d45.nq.gz
    ├── 455c198cdc346b2605630befc38f7f10fe7c5387.nq.gz
    ├── 457c4d2ebc2c1ea3aad9872c01d2cafea962ed7f.nq.gz
    ├── 464b0ce13b987ddfff6bbda0b9baae2d42a4380a.nq.gz
    ├── 46abc7a1a1d197f763f7870dcbc523bbb7af0913.nq.gz
    ├── 46ed15481cf6310a518eaa017e4661e7fbefe00a.nq.gz
    ├── 473306c47a6849e2628d4c5946ccd5e2033f22f5.nq.gz
    ├── 477b307d2eee531b9a05df948d9aaa5c137e6f10.nq.gz
    ├── 47a49d482560fabe97596ff79f885b26050b8fc6.nq.gz
    ├── 484d4e34f0d1b9dbc4d399b3ec3e7a0a0a3f3d76.nq.gz
    ├── 48ca98719336ee42cc4543d26e9e60bf0cc458db.nq.gz
    ├── 491c3e170240d94390f035439e0dfe62bc334020.nq.gz
    ├── 49683b0de105afbe40e55225a4b3e262a956c52c.nq.gz
    ├── 498b053de3852794519130784fdb7794d051f37c.nq.gz
    ├── 4b501da0f043a0d68ff9a27be7e6aefbd0666a79.nq.gz
    ├── 4b58b6e938af4b31efed67ab3c2cdba98be60b23.nq.gz
    ├── 4b6b5cb2b0a71758a91ae8afd3e9b2828b39fcc7.nq.gz
    ├── 4bcf7892202ec5b34e080813f2fcab3e6eabe46e.nq.gz
    ├── 4c0dcc3c47d1e625d7b5daaf8fdc42b5426f1605.nq.gz
    ├── 4c20564cb6b69bf28af05b71fe67d1f363cc2b4c.nq.gz
    ├── 4c67019368098e2971327bfb92b069484cddd28e.nq.gz
    ├── 4cb5e7591732ae0905d5a2c23e4d7d1e5863a9a2.nq.gz
    ├── 4d80511d8a033864493c890882a56aad9df76684.nq.gz
    ├── 4daf54b071bcee10636ffb75150bef29ee85fd89.nq.gz
    ├── 4f9d68bae3d7f2681b8df546f4fb45da2339f6c6.nq.gz
    ├── 50192fb69134abccd4954ea484ee1a9a67058679.nq.gz
    ├── 50390adcb6d0e5c3c466c336f03997c6605d133b.nq.gz
    ├── 50c8cdb150060009ec2ef28f8f4dcabf4d39e591.nq.gz
    ├── 5153d1b1e2f3f1f6708f087fe49d979692ce0f08.nq.gz
    ├── 51904a4606c63d37ba99981511a4d4cfcaaa1438.nq.gz
    ├── 51d21771b74c99a396280292dec4abba85b7b529.nq.gz
    ├── 51e00ff5ec86adb91c7a5f478f734f09b06d5210.nq.gz
    ├── 5230ce56e222478aa197d7fd1f89422e628e957d.nq.gz
    ├── 5248f29fa2c2d68398d4153a43737719872e7f50.nq.gz
    ├── 524e1c9731a6b9d7e7832465f3c8a0ca5a5099c1.nq.gz
    ├── 5287b06430887dbfa16a01633d0103140685904c.nq.gz
    ├── 529a88fae74c743cd716ae2f518cc427a6c2a77b.nq.gz
    ├── 52d476db06bc293e43911423e8df33fa5ffdb088.nq.gz
    ├── 5367a2facea53b1763bd6cf007a72d447ad957f2.nq.gz
    ├── 53ea67f6a043c0632e1e9dc7e1fb4ac33f5d0534.nq.gz
    ├── 5408d3ed5e72d7e4a6e3211dda858e86b5b0f631.nq.gz
    ├── 541f86184e8b7c53a3b7fd1961834195ca0f7d70.nq.gz
    ├── 548d71365f0ec73769cdca035854598aa03d5485.nq.gz
    ├── 548ee2d228481cbf5904ff1f73acf99e2847f72d.nq.gz
    ├── 551576c8f834bc36ac8e7ad72c92196a61dc4c7f.nq.gz
    ├── 556be7d793bc8bfaea0d0724e9afc040887ec0e8.nq.gz
    ├── 55853167952caf7de1b1eed5543222d1c4d747a2.nq.gz
    ├── 558b47832d3531107127912febe8f79d2e6c5d86.nq.gz
    ├── 5607ea842d2ea76c8281854e8de371f46ba94094.nq.gz
    ├── 5779ff16a7cb133bb810c3473c0a83bd61ba83bc.nq.gz
    ├── 58606a7184ee52480eb984700239553bdefa8974.nq.gz
    ├── 5869e7e170a7a9f3e92e79ebc271b505dda29e6b.nq.gz
    ├── 595e6603b0c4e2c1ec01943ed324b570f3b7b34c.nq.gz
    ├── 5a20b27b4581f1e9b6a21994f0ba71f6bd544c93.nq.gz
    ├── 5a22dd66a74b1faf4f17a2d85ecc56f2b5dae473.nq.gz
    ├── 5a28a01573da8c523e5d0a19a4c542e7b2d99651.nq.gz
    ├── 5a6d0c38cc825b327eee03d12b453c5a158b46e0.nq.gz
    ├── 5a7d1cd404ece8d218984fef7c9c1021a56c7f02.nq.gz
    ├── 5a7db04e3f821ff8526b1b43329bfacfd1629117.nq.gz
    ├── 5a7db4e52f35d2c1c79dff2aa317677bdc6319e7.nq.gz
    ├── 5e3784bdb0c502af58f23e7559dc7b9be6754881.nq.gz
    ├── 5ed1160193c7d8dd2487718165ffa004a0f62449.nq.gz
    ├── 5f2d32bb61091412e6e4f77a72d5dc3a25a837bc.nq.gz
    ├── 608ea8287b63a38d779932cb44610b2b1650cbc4.nq.gz
    ├── 60d90ba2784707365b56571001b5ff8de0bdc1ba.nq.gz
    ├── 60e6419e5127d8c3a8a3a48d03479c8ee9b17f74.nq.gz
    ├── 616888bada5af5645547c65b1d4df494609ec288.nq.gz
    ├── 61a02d13d9b35f307fc9426c4109596304227035.nq.gz
    ├── 61c220616e2e4288a1813b95ccdb0bb20df105f8.nq.gz
    ├── 6236026fa104ddf1752b3cbe5db281a338c33365.nq.gz
    ├── 625442a45eaf8dc67a48d04828ff703b431c1c01.nq.gz
    ├── 625661654454fbb43dd1fcb223d8203431cc985b.nq.gz
    ├── 629e184b982519b95c71a291e76629fd9b36269e.nq.gz
    ├── 6351e20e1f964b7ab2206f5d989d2b42437d091f.nq.gz
    ├── 63ad6519f2d28727b53aaba79ca19a78dbd1c724.nq.gz
    ├── 65b4b71b35226bb58a3ee5664a406758f057a8f7.nq.gz
    ├── 66ea047b77faefe26c355d5222637856efa38722.nq.gz
    ├── 6758e34866b6eafcb6888dc25294d865077d60f5.nq.gz
    ├── 6818de9811f8006da1cb5a61586e771752984609.nq.gz
    ├── 6868209f495db38af224c7352c68f9ec26a13634.nq.gz
    ├── 68874f403a7bd5da7d6a9871fcc664d44e151f86.nq.gz
    └── 697647e5b0b6b9b286d862210ba0d8aafafb6db5.nq.gz

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

[pysal/notebooks](https://github.com/pysal/notebooks)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
