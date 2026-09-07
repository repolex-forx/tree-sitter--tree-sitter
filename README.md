# Repolex Knowledge Graph of tree-sitter/tree-sitter

RDF knowledge graph data for [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter), parsed by [repolex](https://repolex.ai).

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
lexq download tree-sitter/tree-sitter
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cd5b087cd9f45ca6d93ab1954f6b7c8534f324d2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── cd5b087cd9f45ca6d93ab1954f6b7c8534f324d2.nq.gz
│   └── repolex
│       └── cd5b087cd9f45ca6d93ab1954f6b7c8534f324d2
│           └── chunk-001.nq.gz
└── blob
    ├── 000647afe02a8accb2d32e08185a2fcbe7a7ca91.nq.gz
    ├── 0038812250289cb1f455e689bcd206d051796b4e.nq.gz
    ├── 01e789ae962ca064238e4763486578488020cf64.nq.gz
    ├── 022542740864ee7e694b2ae659d213365f074b54.nq.gz
    ├── 026e9f16138e649c27dff82ff598f3e9c92a594d.nq.gz
    ├── 027ac7073eab70f985e5aa4f4bed58a18567397e.nq.gz
    ├── 0492f0aca9c6c16a8e0e5b1f88360e8103bc3948.nq.gz
    ├── 04a1890075eb7d6b5df461834756a0014b39286d.nq.gz
    ├── 05268df7a19fc5f6a4739ca30120d0067a075ed1.nq.gz
    ├── 0547df4c1eb86b3557be351ce41749a5c52d163c.nq.gz
    ├── 057426876da6c6debb7894397667e5f7bf01af75.nq.gz
    ├── 05a0c426c997983337072c48c0e8aa24d8b3d6ef.nq.gz
    ├── 05b37e6f0214157b5b8c6fefa55f30d5f165857f.nq.gz
    ├── 065fa88c68e816b1badf8416bb72a17d2b080083.nq.gz
    ├── 06acbc8fc3c35680df16b789395e537762a5185d.nq.gz
    ├── 08a939dc7febd40c45c4f91dc46c4d72eb56b071.nq.gz
    ├── 08ff2654cca7861672278ef2de189ed920042910.nq.gz
    ├── 09822ffce7b941de9017da0f295e32c1608492d5.nq.gz
    ├── 09fb459b92495e8a7aa8d619631f144a720283bd.nq.gz
    ├── 0b302a8279946f85e713aab3232003df0925fa0e.nq.gz
    ├── 0b70460a16c308e322f67d48aff003facaac813a.nq.gz
    ├── 0b9fa5acc4966eaa43d09a3604939af52a8a79cb.nq.gz
    ├── 0be5999d77b7ce2b4719f749fcb6a423155ab121.nq.gz
    ├── 0c9c1b45679dd087f8b60fdcab5265044f244454.nq.gz
    ├── 0c9f7111f4935bc90ee0dcc6934b36216bf41ce1.nq.gz
    ├── 0d0aeb60085ec1d8e51ff19c24fa9b212f7d6d9f.nq.gz
    ├── 0d542675e2bd86a70485f8f870865aa9688379a5.nq.gz
    ├── 0e0ff69d9c04cf95d09c052265693bf2ef25bd4c.nq.gz
    ├── 0e4baebf41650cdf1303a33944536e3001f2b45f.nq.gz
    ├── 0e8f24bd425a67dc6508531e8629dca926575f6a.nq.gz
    ├── 0f02be61f822ea09ceb166029f64ab956ad90484.nq.gz
    ├── 0f47e0f489d04a3da33ff654c18949ec0b3d2822.nq.gz
    ├── 0f57f24233efc2fb147d3f56d1b78123cb4b2447.nq.gz
    ├── 0fba3f29614d3688e553bcc9e896341d05e00d66.nq.gz
    ├── 0fd17e0d1736a0a69e428efcad494d74dee3d623.nq.gz
    ├── 1026d6803d7eded0e2ac45ea1fc3b95287964fef.nq.gz
    ├── 10cc35dc7fe4775133bab03cc45a9b7ec1928b36.nq.gz
    ├── 10d4a62b68e6885f72fa7f77268f726f35d68fa6.nq.gz
    ├── 10f119585a28f8920b2c46bb942d93052fe9b815.nq.gz
    ├── 116cb0a6dc2beeed9e3283daadb0fcd4425f5cd8.nq.gz
    ├── 118423b78cfa5f7e3fb22b50eb50a5b5fd33f1f9.nq.gz
    ├── 11fd569df55b35cd6b76ac6adb14d2452837cdb5.nq.gz
    ├── 120786287af983b0f797293382ac42c20c2e1ba8.nq.gz
    ├── 1276f1fa55c6c9c06cd16bc4045a93f03fd265c9.nq.gz
    ├── 1362b0c4f6fd3dd9a09aa89b3c326ed67555b035.nq.gz
    ├── 14163d80dc4abd3913971441ba47d75240f8ae68.nq.gz
    ├── 159ccd9fc346d84f542e333d009fd19f43de87c5.nq.gz
    ├── 15a4d02c3bdd6bb0ab0dc613805496eaad68116b.nq.gz
    ├── 15f15d9a9b3bdfb9b04b561a025d54895a3db946.nq.gz
    ├── 16270b0ac7a86e6b920a6cc6665f9dfa38b66025.nq.gz
    ├── 1709c418fde01e3876b0c575403fe08d3bf0fa74.nq.gz
    ├── 17972317ecc160cd4b107db9a747fb3d685812be.nq.gz
    ├── 17b1d384ac7fb5411ba606c18b964fa798ab285f.nq.gz
    ├── 185dfa2c8cecce593f1c0c6d299901423c4c1637.nq.gz
    ├── 193b09227db90022a74dfd9f0630a3ee03e8c06f.nq.gz
    ├── 1abdd1201578605b8d05a3001f01ebc0d58826d9.nq.gz
    ├── 1b0d20afa794d40e756bf5fe8a08fb97cf0fe0dc.nq.gz
    ├── 1b3666f6702aafe5831bf36175c8e9435bbcaf9b.nq.gz
    ├── 1b6d789ee583a7521c54ea4b17552b4e638e5d43.nq.gz
    ├── 1d07631f8a1f47dc30d7e92b67a5ef279901cdfb.nq.gz
    ├── 1d1a6aaa90c2c5aa1ac414e8b0ebfca327f5ccba.nq.gz
    ├── 1d262cf96eb043f194e7f0d1a615a5fd85d41e31.nq.gz
    ├── 1e1596df68a7930b0c1bdceed8dfe438e4807429.nq.gz
    ├── 1e8c9ca3c785245b16ba448a853f12bf4f7d27e2.nq.gz
    ├── 1e93f06b77b7da293ba0d0cc1001182967b5466f.nq.gz
    ├── 1e9f4949a5128b7cdd125bafc13d87addeadc6ff.nq.gz
    ├── 1f690ebd3a8d35c25e7087177aef0cb16f2d5dae.nq.gz
    ├── 223de3d3b53d46d83996ad5b5debf806359aff27.nq.gz
    ├── 231085ae3370dba61bb25bd11dbdb353de5bfa5b.nq.gz
    ├── 231f5c7799c639c9088ef10365cc94c76dcb1015.nq.gz
    ├── 231fe2abbb7137825e2677c6efd70dcc057b4661.nq.gz
    ├── 23b11167915d289e47340c5f3ac71e4f6df67567.nq.gz
    ├── 23ce2b246f6c1efa7e9d08ee0def8f500447a3a4.nq.gz
    ├── 2416dd9bdfb49c86b002a96fb6408641a7362e31.nq.gz
    ├── 2439be38608355068a6938935557878a3006bf1f.nq.gz
    ├── 24576d327c75d5e9895b11310f5cce8fe336f17c.nq.gz
    ├── 254ed931d8733b9badc4bc6da4fd0c3d068e32fb.nq.gz
    ├── 26020f2c19662e212a8ce62b548edd26b5ce249d.nq.gz
    ├── 2619f1e8a54dacfbffa84599a3f6b399e297be6d.nq.gz
    ├── 26e7804362b377f06527548ccdc6c28ab548715a.nq.gz
    ├── 27a2eea6de4ca90811561786c8b20d71303516bd.nq.gz
    ├── 280bbc3192baa887a1856bda0ca65057804d44ab.nq.gz
    ├── 281439ea48303bd7d96c9049fe5238b15dfa2dc8.nq.gz
    ├── 28ebd86a798f76074c71e824110bf079bd11345a.nq.gz
    ├── 29c2eb1b1989117bc9d30f163c7fac7ef8873bfa.nq.gz
    ├── 2a206db0bb826cc6c70c8c247d831afade5b30d8.nq.gz
    ├── 2a6f4be3b99b8890701898b5bda5fb9ae37c28ae.nq.gz
    ├── 2aafdea43dc6ebe9d62450e7ac0d45ce7413d136.nq.gz
    ├── 2b0285623a94fffc2a5a89c851bc3828d5175d24.nq.gz
    ├── 2b15db320d56b294c02ace9dd6414ea8b2e8eae4.nq.gz
    ├── 2b1bddae103f06b9be979a6ff6ca4e3b50031c9d.nq.gz
    ├── 2c20361f65ddefc09a9f086a8465d9cfc115f568.nq.gz
    ├── 2c4dbcf45a3b3c972fd14f18a9321b134c72b350.nq.gz
    ├── 2d0d9096e7908d7f09805820f8546f900cdf4700.nq.gz
    ├── 2d205c04938d61c554bc2fa9a1ab8de7796cd82d.nq.gz
    ├── 2da313abf6eed6425e1b416a043a6b8b6c2f0474.nq.gz
    ├── 2dc3639b045aa8e5cf9aee1b10baa8cce02f999c.nq.gz
    ├── 2e01e368768a4b992e22f98c05ead747134492a6.nq.gz
    ├── 2ec13846fe4093d34c5ff8d008d729fed78a24ae.nq.gz
    ├── 2f8851dc09d5d71801da69e0cd577a089c0a14eb.nq.gz
    ├── 2ffa6b1514ab00bee0a71b93f8f69fbf5156e0ce.nq.gz
    ├── 320937299572de5b23f4617a3bb85f1de0bdf71e.nq.gz
    ├── 32d3666a661c97da0a1e95e69f201d2caff5079d.nq.gz
    ├── 33606931146d4192cf5821041824fda468463ba8.nq.gz
    ├── 34347938edb304fe7c7889bc924be36d7c4c95a8.nq.gz
    ├── 345d8b9e3fefb361d3d49bf11629350a85755f5d.nq.gz
    ├── 35049cbcb13c204648d1f7897162492f05123199.nq.gz
    ├── 354d70e7d924d77020cff8ad93fdbd57590c80ff.nq.gz
    ├── 3550a30f2de389e537ee40ca5e64a77dc185c79b.nq.gz
    ├── 3622283ba3572c9d94c0482fd3dbc5084f2f7841.nq.gz
    ├── 36963d8ed87e3f42138950b3b79edd2c5d72e381.nq.gz
    ├── 370a572324de409d222e41f028835db1715ed417.nq.gz
    ├── 3843f184a8ef5347578a745c90dc0e1b442142b8.nq.gz
    ├── 38667efb96301d4a6658298eebbefd7fc9e25c23.nq.gz
    ├── 3960d961658da866af4f4279197a51ae7537ce84.nq.gz
    ├── 39c13b7ccc4353a68a49e61598012b55e88dd5ee.nq.gz
    ├── 3a389ed4b8a0148b3dbaee4991816cfc9fd285bb.nq.gz
    ├── 3b0b8e54be32fa9a01715da8dd6e62c0a432a3e5.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bb78e415650cd65a7d431175a1f6d37b51793f1.nq.gz
    ├── 3bec17bf6b076691e603c01addfcca318d7effae.nq.gz
    ├── 3ca4d264e2da719acc6c342a8c46807c7c0a9532.nq.gz
    ├── 3dbbfd100d8dccd935ca972abff5c5c64cd5ce50.nq.gz
    ├── 404739fa86a3ec8a107c68640c4ecda5b5352b3f.nq.gz
    ├── 4089cccc66605bc6523980e49625ae90af7bc6ab.nq.gz
    ├── 4104696419945371ad3bda38ab3d02190bee4969.nq.gz
    ├── 41b119067b4bf333f6759fa70e98349902c1a9f5.nq.gz
    ├── 4265a62066885605be5a5c0e234bc46a2d147682.nq.gz
    ├── 439d7fecc68f1c6dec4624609fd187e153619c6b.nq.gz
    ├── 44e05702911013ca8cded65ec3769366d825c855.nq.gz
    ├── 45aeff0511159ee68ee10950f4fe4b5c84207e41.nq.gz
    ├── 45f54634db4c1c936bf2833ec4e7c3163f780ed7.nq.gz
    ├── 460d2359219815a776c242c82d263c6a964db770.nq.gz
    ├── 463466991d0b2a8f16b50618dd7c7b05fc0c1f73.nq.gz
    ├── 464ddfb4e55864fb2ff526ad3a74a83527f8d95f.nq.gz
    ├── 46d603076235a40ba51d457e459e10cb0e21de22.nq.gz
    ├── 470c1ecc7429b14a39b49c78838dbe52d9af11b3.nq.gz
    ├── 4784abbb1599ce90eed9697018ff90664ac1ce6f.nq.gz
    ├── 478cbeeb570d5e395149e3729136ca52e706dcc1.nq.gz
    ├── 48c6cb3ca32fa1ecb6b2657942253a14adde12af.nq.gz
    ├── 48d6159989181075da91f85459c0cc0a9481c903.nq.gz
    ├── 4ab8e0db135db7fcffbfdc065f09cd16f230ddbc.nq.gz
    ├── 4b3bdb83b98f4aff3512b043f6294a949d032cbb.nq.gz
    ├── 4b5edfdf137d5edbfcce5362cd5240b4e1e79c8c.nq.gz
    ├── 4be1e1247e8126e12f59529ee5403ad07a8908dc.nq.gz
    ├── 4c68a633ca229c6d3ed902887a33f0c27482cf56.nq.gz
    ├── 4c9aabfc360693356e12cd15068be6da1a51d416.nq.gz
    ├── 4cb8f36a122522b73151dca8e3c6e41e940d6133.nq.gz
    ├── 4d2e6128a86b1efcd6d4d5ed0d40a7421d2b98c0.nq.gz
    ├── 4d691420c235a5159913245a9d2b6dd2a8136c59.nq.gz
    ├── 4d697a90cd7be24d790a0005c9a0db8377ff4fd8.nq.gz
    ├── 4f244a6c646597677905eff3446bfc2b1caeb3fd.nq.gz
    ├── 502bb31fe9dc567dabdf7e027f638b2a341a7c70.nq.gz
    ├── 503955b0201fb27293ab78b10ed46efe6ad4e70a.nq.gz
    ├── 509ea4f209b2bbcf5c6b640fcfbd1f23fe6c0c30.nq.gz
    ├── 509f38991f2afed9c357ca0cd912d39749bc9755.nq.gz
    ├── 518c06bfc55a635ba1adc3bf92a3b7548e12adc6.nq.gz
    ├── 52c5a6d6ba5f3aa8b2bc5300842a170ae9a2f924.nq.gz
    ├── 52c767c517852cfe820a6356155fe96e6367bce7.nq.gz
    ├── 536359d3a7ec4ef65cbffdf1ca4c2bca81f2a596.nq.gz
    ├── 54dd20216d896d74ff3344e1eb7197142560dd30.nq.gz
    ├── 56fc8cd470996ded64a5452be25e26dbd2aa682a.nq.gz
    ├── 57c5bc94c51fccc3b7184941d20e11f2c8d1207a.nq.gz
    ├── 5876db92447127e7a3681369cbcfd9703236d0ce.nq.gz
    ├── 58e0869cbee9eb14b731e81edab029b8ed8ba579.nq.gz
    ├── 5940bb87aeeccd07d9f41e5f33076f97627a2b59.nq.gz
    ├── 5976d0bc52c3ac8de4b9602ddaa2ceda6f3bcd62.nq.gz
    ├── 5a399f083e5d6e5bb55e35156795c910e22b2bf9.nq.gz
    ├── 5ab8208728ce4d7256894e9f3e031e0fa0d90b21.nq.gz
    ├── 5b2cd8045290db43f9bf5e5c45a651953563ae44.nq.gz
    ├── 5b46674393dd5d0acab68a5e4b4ddc2f9a989df7.nq.gz
    ├── 5c653bfc9553de23a7efc97e228b00105de7fb68.nq.gz
    ├── 5c88ff6c1a99b10dfb3fc3220d8b7126f15dba1c.nq.gz
    ├── 5c8dbbe67f5355b202f29ac55d3ea28783ca0109.nq.gz
    ├── 5e0bc8e2b05130ca7489c587bf82d00ebe3ef514.nq.gz
    ├── 5e93bf40ee526d4164790e0cf244653334114f5b.nq.gz
    ├── 5f0976d2fdd8adb696a4d897f0f6864bc4ea6f4b.nq.gz
    ├── 5f9140a7f5bb396d94dc79321d163354a59242a0.nq.gz
    ├── 5faedb0c086e6d39ea2f75343fd4a46ecad8e2a0.nq.gz
    ├── 5ffc889a0ab0d796c6043a4b2e0853f63ea71f90.nq.gz
    ├── 60559b10e60bb7323f2a1d57b040a1c8e41c920b.nq.gz
    ├── 607efe4020d47bc10ce67de9174fbabbb49be5ef.nq.gz
    ├── 60fe5c4a684be3ea827621cac06f7eb96f7918ea.nq.gz
    ├── 614bfdb993e1c1e76dcc0bf803f73c802f44c353.nq.gz
    ├── 61c6714078ad0f9e1ad71795c6350e433309419f.nq.gz
    ├── 6211d60c6e67d68bbb205f0905f5c6ec319226f8.nq.gz
    ├── 623b8e38430406db87ea955934b1e461af38a5ea.nq.gz
    ├── 6390bdeb2de91797348af739695c791e14858594.nq.gz
    ├── 63c47a01b4c2f399b9e049f8c3e2d0b8c562a671.nq.gz
    ├── 63fe3c1a36c7b3780f47c6c9fe951072f168b085.nq.gz
    ├── 641b434b33da81f5deaac766b503e99eea109f06.nq.gz
    ├── 64ed3bf27f18e0ff0ccb9bab6fa45350619d1a8a.nq.gz
    ├── 65e04cffcbf496606a55d4d12fedb113bb2d836d.nq.gz
    ├── 661fe42b224384058d04253adb25f4855a64ab91.nq.gz
    ├── 662fc3b14d578895a46036820197320fe84c0873.nq.gz
    ├── 664884f55d9e4cafd15ccf7254082c157b175c0e.nq.gz
    └── 664e355b25c9dadc9bf15db3072713337cb4dbce.nq.gz

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

[tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
