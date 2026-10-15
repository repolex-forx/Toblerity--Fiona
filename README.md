# Repolex Knowledge Graph of Toblerity/Fiona

RDF knowledge graph data for [Toblerity/Fiona](https://github.com/Toblerity/Fiona), parsed by [repolex](https://repolex.ai).

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
rlex download Toblerity/Fiona
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 51cc8e3aad5e3415fac5ed00c988ca5d6aa0277c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 51cc8e3aad5e3415fac5ed00c988ca5d6aa0277c
│           └── chunk-001.nq.gz
└── blob
    ├── 019258d5a059adbb70f598f1e2d3a13427b0d650.nq.gz
    ├── 03338174a1a990ee3939d06a2f44377218c4bdeb.nq.gz
    ├── 04399dae5b4ccdd77e1635f3091c77e06b1b318b.nq.gz
    ├── 047146033a55ffc740f9b62e3a387d5e59ac197c.nq.gz
    ├── 04d5ec48804246c75abc9b9dcbd5338204b42f38.nq.gz
    ├── 05529cbd644c0a8f99185df36f3f2201a9d09809.nq.gz
    ├── 064d3ff58b0941174fef76e4280c45ab462108e7.nq.gz
    ├── 072bc56ae74694a69a6be005b0cf537f7a0d5651.nq.gz
    ├── 081e1c142708398ac0f598dae0d3a5cb3a9fb5b1.nq.gz
    ├── 082b7e7654c549bd3481e2a5bfae7e95be6f4929.nq.gz
    ├── 085dd1f3bfc84c15d643962ea2071f2a2eeffe5e.nq.gz
    ├── 0a87a637b44ccdd639d028b32aec47c916091f86.nq.gz
    ├── 0bcca78f20842153d79f2e1d1f2c6cbb0ed42b96.nq.gz
    ├── 0e5b54d8f71f0aab13b00637b5446024c0611428.nq.gz
    ├── 105ab92d15573a26ed70285dc66f292bd8ffac59.nq.gz
    ├── 10fa979669c245b3f9e12148aa3ec15f4051c943.nq.gz
    ├── 122124b03a10fb738bd52565d0da9789e55415d2.nq.gz
    ├── 12e0e9ffbde31c453cfc52728a06df63378a2a92.nq.gz
    ├── 149d270469d71a564f931b614550033db33a2425.nq.gz
    ├── 14af7b756e87deb2252096f4ccc99810176a3ba4.nq.gz
    ├── 160ba55c07370f97fe3cf7d40da5b96434891bb3.nq.gz
    ├── 16521cc15b8de5650bd041b3696e2adcbcce1372.nq.gz
    ├── 1a6e09f3db6f5ea8b26590856e5be524cd813fd2.nq.gz
    ├── 1acd7d84226cfe021c0d50a203e5d732762ef27b.nq.gz
    ├── 1c5dfa8f02712bc8bf9281a95e8513c0bb54d9dd.nq.gz
    ├── 2008815e854528c8b49b70af8bba71edb2bacccd.nq.gz
    ├── 2157515dadbba3c18958477e533598fee5f68934.nq.gz
    ├── 21a142759151a94c6b3543d541adeb7d31518a90.nq.gz
    ├── 21fc6ba79228bd14a6c0c20af2865f3c5dad7e8d.nq.gz
    ├── 24384138cd760f2bd1b2eb91ee0224e925ab9fc2.nq.gz
    ├── 24d9ef0a70e3dce6813cff36be70ac498e4591b2.nq.gz
    ├── 24dbf860ff9e38cbd3b14e810e1cfec5c2a4543c.nq.gz
    ├── 2601f8c103cb26c9cb0e7d2616562a6c204cddc5.nq.gz
    ├── 26c1253d901d780e067122375aa0ba42d6676d43.nq.gz
    ├── 26c9c7bb88870427750bdb5128b96fe4f0090a03.nq.gz
    ├── 282297518fc88b49b20cf93f661acd31ddf0e1d8.nq.gz
    ├── 2899c9f205eb03e4f9fa7acfd1adbf6fd42e3917.nq.gz
    ├── 2a18aaf542f670764f8d55a7d9234ccb6d4bb671.nq.gz
    ├── 2a445eb6951b66235159da2ce4513a79a097ede3.nq.gz
    ├── 2a60ae6c92280a3e7bc6ce2771f570e8cef19b08.nq.gz
    ├── 2ad82e77fd17f9c85eda8cc14eb4cdb923be7e1a.nq.gz
    ├── 2e7422a320e6cf66b3776140e83706925c9b4cad.nq.gz
    ├── 2ed578d012f29424cef6adf3a1f526830402465b.nq.gz
    ├── 355139bc5108df784e15e68bcf0dabd770232325.nq.gz
    ├── 3614050a3a6852801e260793cb468bae3e092dbb.nq.gz
    ├── 372d732acf82af85162611e1a9781ca1c1506000.nq.gz
    ├── 373fc095634c28dc0805ca8c2e692371685e24ee.nq.gz
    ├── 3abf4e1bd0bc7934ca034e3e20c8fed4ee7eb3d3.nq.gz
    ├── 3b42b85f3cfa1b645df3859edc91a7945d7c4e86.nq.gz
    ├── 3bdbbf9b679637983dd127b0722d47937b0eb4f2.nq.gz
    ├── 3d44efde9fde3f074a6ed971976ec3a9e144efc5.nq.gz
    ├── 3e78a085eb23abf3d50b7304e6f1ee0c73793670.nq.gz
    ├── 401420bcd0e19c7528ba2629db30fa917c8de0e5.nq.gz
    ├── 41a701670aeb439c2bd6bfbf4307d8ed3db4cce4.nq.gz
    ├── 41b61611ce4a15b1641cea231f6ced0a0ac209f9.nq.gz
    ├── 4274e7dc23842ea6565abea00e8bda61c626ea00.nq.gz
    ├── 42dea4b01904f254673de1688ad96571ac7fb485.nq.gz
    ├── 4418961444ccbab9dde0e0feaa7839a27e494ff3.nq.gz
    ├── 441c14e37c6f500257dc4f30c01b7850c198215a.nq.gz
    ├── 47255e9ac130493715892be093508e6fd6df4588.nq.gz
    ├── 4729cdfa7c6332f8a13143313b97c9eea9a87138.nq.gz
    ├── 4732a63d50cbcd1a89b10aa9d01633ca5e1fc17e.nq.gz
    ├── 476ac00a078a131ef94887faeada8a6ec2ba9416.nq.gz
    ├── 4992f9c1016af57ccaf3947c1532211c51536032.nq.gz
    ├── 4afd1f3b73a5e57ca21e6ed698f2ec44f47d867e.nq.gz
    ├── 4b6c0daf7a062ff66985e369b94a17214d162dad.nq.gz
    ├── 4bfd03e4467856f34fec5783e8fcd787d9981bac.nq.gz
    ├── 4d2b49078d1bbb1474c8957cd90c229dd95e74ad.nq.gz
    ├── 4f98773129006aea6a3a3b231dc7478fa7dfdc3b.nq.gz
    ├── 5024f87072fe3567181565f4f53b273bceb26858.nq.gz
    ├── 5287702b1a7550e172938fb639538267b2532d1f.nq.gz
    ├── 547012bf3bd0ff95ec93203a334b113c9e864121.nq.gz
    ├── 54cc455dc823960b1fa532a532c0a25d2797411d.nq.gz
    ├── 552b104ebc934eaa716207782626806afa3148b8.nq.gz
    ├── 5549bd7ce752484427d112f9c6898a4ae4c76c8f.nq.gz
    ├── 5685324803b7f586f4dd2e532d11d9d330b8feb6.nq.gz
    ├── 5714ec5e5f377945efc3b74ceab6ce692dba6632.nq.gz
    ├── 573e910dafb4fe203ed572853e51a3cd8ed33389.nq.gz
    ├── 57decb48120254539eaaff5f98ccf50f7ab9b516.nq.gz
    ├── 5b268068a3d113e911800b066196e5ebb4e6ca82.nq.gz
    ├── 5c315943613fd48b876b733595a987f7f602e84e.nq.gz
    ├── 5c90406ec76c8492808d476e8cf2e6a11d7c2961.nq.gz
    ├── 5da547c499eea5b8b91ab7f29d6752a376148a8a.nq.gz
    ├── 5dbc366745eaf77751b329580b39d46f5207ebae.nq.gz
    ├── 5e169976add95551103723e0176be9942f62fee0.nq.gz
    ├── 609ee410a85e01a5e2ed7af1c177c9e1c3cc4f4c.nq.gz
    ├── 617f4104aed677d6326b354cb5a8d6a8a0ff6054.nq.gz
    ├── 6474c5352cfc942d0ca7afdf813d3e095bd9c894.nq.gz
    ├── 67c1bd9258843a3a75955985045bf7fa451f74af.nq.gz
    ├── 6adbde1008066dcbee34116ff7c7f208db086988.nq.gz
    ├── 6b7911c31aa88dd0fb63501251888956160e5cba.nq.gz
    ├── 6cdba7492ea2141fbf2ca08802b679346c8cfd36.nq.gz
    ├── 6e6a2a820469c18ac654916bebcba77b78094528.nq.gz
    ├── 71094bbe5984b89d70229583693fc66b8bae7bfe.nq.gz
    ├── 71578b255aa476a70f69955a0e732427136739d0.nq.gz
    ├── 72123de477b9334c94dc218f18554ef6c1004362.nq.gz
    ├── 72f25ac8b16a049a8fb743c447a7c58c3d04bbfc.nq.gz
    ├── 730a6270802fdd3db366d32e7e8b846d7869f0dc.nq.gz
    ├── 75091686edf545c00634c02899c2d4eb9b68d5c7.nq.gz
    ├── 767e02804d0c2991cc392e48c6b9f3195505e29d.nq.gz
    ├── 768b198a91cdfc951a49ed23c3b98554805064ce.nq.gz
    ├── 76daecf8702e618a92e7fe30642a1b02234dc367.nq.gz
    ├── 781b63a9311e99ea0544f55fd539ed09582ac060.nq.gz
    ├── 79f67cef244f218f7a0b0b7c5ccd4ebc46023983.nq.gz
    ├── 7a6a9fb71ed73dce06f1ce83fbf052b5c7841621.nq.gz
    ├── 7ae766c1d6189bda16ff596b17917f2334b8ce76.nq.gz
    ├── 7c0e2a561c7708f451c27bd053cf427f891354f3.nq.gz
    ├── 7eae7002fa8fbb935b0f012c4aec5b9a918ce079.nq.gz
    ├── 7edc66b06a9d03549d75d2c9cbb89f83c611ddd3.nq.gz
    ├── 8003f8e45a210a995aaf8c44f9dd430cb24a1e81.nq.gz
    ├── 8035c18983692b4ab8f4a2477660364496394228.nq.gz
    ├── 8250ab14171c5f1a93cc1cef9e9d1b194cdd01fb.nq.gz
    ├── 82ba5e9c98ba262d3f8bb52831ab16dfced6daf2.nq.gz
    ├── 86e767fb0444f1927e9d6cba70278fc8add1ea45.nq.gz
    ├── 87a87a575c3b3e943892b5ecdae0ca44e939f471.nq.gz
    ├── 88cd68a8b3c710a52170e4d12ff68affeb73f5ef.nq.gz
    ├── 8ae7f799ee30add3861794f15b7b1f55af4d06c0.nq.gz
    ├── 8bd654707f7b81c917c0d65a81c21302545361f6.nq.gz
    ├── 8c61a23ac2f56e79bb0a543c52a7580119f9e1b3.nq.gz
    ├── 8e485d7069685d36614fe3826d085fcc91c5c71a.nq.gz
    ├── 8ee3b6b440ba71794a560f796c472d63fae28206.nq.gz
    ├── 8f857d0e1ae2fc907163aa11e99a2feae38c27e0.nq.gz
    ├── 907dbcace220e2d2e6c8ee2e47bfbc20c14b176e.nq.gz
    ├── 9174fa1853981d6ae51cabb3221b84a94ee12efd.nq.gz
    ├── 9403bb2b6d4c9166db1720128dd9d9f9c525f967.nq.gz
    ├── 95d9264720cda0f7e45457f1a40f35985621ca2d.nq.gz
    ├── 96c07421cd786cd08145469851bc23cf18030539.nq.gz
    ├── 97bb625f69ba541128efdd341d2cace2952c9e19.nq.gz
    ├── 980f51ef5497538f2dc198f6f4efe4e629529154.nq.gz
    ├── 98e781cb64c74265081944b5992a9472a559f2f3.nq.gz
    ├── 9baa6d0b5ef582991bfcd07dc8cafd4879eac674.nq.gz
    ├── 9e7b71b280d490ce0fb0534fed97655b7049f450.nq.gz
    ├── a056c2aa63943ec8f5d666c098bbca937ce0b673.nq.gz
    ├── a0696e156fe85e625c64dcc2ae82e8d1a7c48593.nq.gz
    ├── a24422b1bd86e4a35d1676d8d0e5390165472ef9.nq.gz
    ├── a30c00a55de19be195abf9e942f6cff93bf0a825.nq.gz
    ├── a4ba4eff0c1375ef856cf500db3ec44cf5a3f882.nq.gz
    ├── a67640d4d234a78ac75db0e9d0a53706be80b4f9.nq.gz
    ├── a91d7931ce6649fdda33adbf169f40240002709e.nq.gz
    ├── aa6965f39078954dd4906dbe5c09637078a3212a.nq.gz
    ├── aa9787f30fe6d818da22f4896bb296858128a5cc.nq.gz
    ├── b1e7497c08ef4be89d55e1bcb802e597d3bcbfd0.nq.gz
    ├── b299799b634ece8ecc7423e62d35ef159b786fa1.nq.gz
    ├── b358c9a568f4b312c65c26e0c5af26ef26dcbf5c.nq.gz
    ├── b4722f123dd82a1fbff7b5728dd2b3d52302e458.nq.gz
    ├── b55493b076112a46b63dda350ac12af91167a93a.nq.gz
    ├── b9d0f15e7a4c705a83c4aeca44480efae8ee6e52.nq.gz
    ├── b9f7902ad7ef785da2b386138390de03e3909748.nq.gz
    ├── ba6558d62a5f0ff1b8b1695e4385a2eb2f8f9630.nq.gz
    ├── ba6e61723771cdc7ede4f22e83e1670270587fef.nq.gz
    ├── baa9bcf18b1a3f750f23c3062772e01c017f2b91.nq.gz
    ├── bafe859fb5c56cfc1b12c794181a7a894cf7d7a6.nq.gz
    ├── bc7fe77122d2f5bc3434ec40d5508db55f414156.nq.gz
    ├── bccfb5344587e0e8e3692434546db627e80e94a9.nq.gz
    ├── bf02a6f35cd617281db33383d109a6000798d4cd.nq.gz
    ├── c1de77c1e089fac517fbf5b7c5ea7028ffa59137.nq.gz
    ├── c20f525dba86ddba186e78c498b558abdfc5ca78.nq.gz
    ├── c23008d7a0be74cb632ccc9dfd500d09c31c5872.nq.gz
    ├── c2703a2da5b2f59074639003bf589d55d0958432.nq.gz
    ├── c28878ced012b4b2f4e2fafeb82c832b5c13b55b.nq.gz
    ├── c3d3513bf24ebfea3038bac87c5dc6aa30f9f606.nq.gz
    ├── c4750bf5ec6a942d5962a2cd74fda3f134e9d994.nq.gz
    ├── c49f94f665a5ca148f202e9f796ca467151012ec.nq.gz
    ├── c57531fb7831e341ff9c4b11d68f2d1a7b68fcc1.nq.gz
    ├── c793b1a9fc3db56d93aabd342d4855b1d7dc2d21.nq.gz
    ├── c8f3567cbcc024b53102c51c23ffd3ba5727814f.nq.gz
    ├── c947bf1debbf939da67bda00354878672aa55f31.nq.gz
    ├── c9f7753c7206dfa15fc651c3b962b50af15bd4c0.nq.gz
    ├── ca23b7dff110cf45c44c70efb74fc98ce7259100.nq.gz
    ├── ca441b941d75dedc6b6d26b5970999a33650026e.nq.gz
    ├── cb433769251fb9a135e41a1352ed19ef04537aa1.nq.gz
    ├── ce2750de2d4b9fc859bee0641901f3284f74afbc.nq.gz
    ├── cef9664e4f652ca9f581cd4cfb6a2350ecc71ccc.nq.gz
    ├── cf50ced6a2e78ee78092ed1ee96a856a3c7c875e.nq.gz
    ├── d0b9e6d5c83d34ff346a843d86e3372a60b2285e.nq.gz
    ├── d11e3a7ff9f3cb747d4556bbd29e28e34d8827a8.nq.gz
    ├── d1a68fa48539d3da8c190dbc07f397fef6cb950e.nq.gz
    ├── d3d4882edc3732c7fc9e3db8681ad519f1db67bc.nq.gz
    ├── d45ac59fd03847b4e77e4b0c375e2d0cd5e52a29.nq.gz
    ├── d66318cc6db812c73ef96f628869b8b3f32e021a.nq.gz
    ├── d736745d462c02bd0d21890097c2d005f5f76213.nq.gz
    ├── d7b24ec4a87d182c9595eef9c571309ee775539a.nq.gz
    ├── d80aa01d90c5490a07b0e99e7fd23c90e5a812da.nq.gz
    ├── d8f5cdd7d69639a87d0f014b7dbe938a6676a4d5.nq.gz
    ├── dd290d4d41f8e5252d3c7e9b8c9d56f0c451c471.nq.gz
    ├── df1b815e26a54a72c41102766bb3787dee4f92c4.nq.gz
    ├── e0c8d354a71a102e093eaaa46616d7dd2297ac88.nq.gz
    ├── e12dd5c478717111199e31abdecde0bb2e3e0e4f.nq.gz
    ├── e2e4542ee4e2cfae36e73ee9fc981b0b4916504a.nq.gz
    ├── e32cf55b833d9d0fc64664c050e212cf031e5186.nq.gz
    ├── e35ee2bf28357e3d23569111651b471cfedf997f.nq.gz
    ├── e4790558a63bc200fc8d183bafedbf050a836fdc.nq.gz
    ├── e4f3561e0ad0edc8b9800a22382a18566e67bb4e.nq.gz
    ├── e5cf837186be5564ee59f88771323a11d8c04549.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e70222c99172696df1de830127176a72bfcccf15.nq.gz
    ├── e7349607fe8f4220ddd2c20b45c8a73246176e71.nq.gz
    └── e764668437eaf2a8ccbb645f4572ca5c15e32101.nq.gz

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

[Toblerity/Fiona](https://github.com/Toblerity/Fiona)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
