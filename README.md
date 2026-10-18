# Repolex Knowledge Graph of google/flax

RDF knowledge graph data for [google/flax](https://github.com/google/flax), parsed by [repolex](https://repolex.ai).

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
rlex download google/flax
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41deea36bd06c735c65b6b480a111bc1a2174b5d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 41deea36bd06c735c65b6b480a111bc1a2174b5d
│           └── chunk-001.nq.gz
└── blob
    ├── 019511c324178fa489830e4441e080c3636a79e3.nq.gz
    ├── 01ca64dc2f063da063211dbfe1d9259f9c57a471.nq.gz
    ├── 021396f7bdb092a7c0f2e3b17525052c5d0e085d.nq.gz
    ├── 025ebdfdd7c105a4adf2d8c195b00c6a145593b4.nq.gz
    ├── 03087ceeb5c6d8098949cce8081f0398b6322bce.nq.gz
    ├── 0373150ec3d297081aab3ac9e4675a4b4bd94a10.nq.gz
    ├── 03aa18a6e14756d061e346edad9d1b9f6e3f7a76.nq.gz
    ├── 045553eeb681d20d3b402a8a030e8dfadfd228a6.nq.gz
    ├── 04d1da9c7c82f3b5404c851695e3ac95b96cf299.nq.gz
    ├── 04dc46a47af45bc0b1f4ae0d9b06fbbc6ba25c75.nq.gz
    ├── 058842e25dc2c71f3992296daba0209dd0284607.nq.gz
    ├── 05b4565e4562dd27a1151f39c7b2067924f8777f.nq.gz
    ├── 05d53788b55300defaa6c342595f71e2f9e12fa7.nq.gz
    ├── 06056d5d6ed8b471a2698bbff0e1a096d5598ae3.nq.gz
    ├── 064158703ba5fa260916c65db60ccd24263c2447.nq.gz
    ├── 06bf36f955e4c82bfdeb68c671cd3e6e4830fe11.nq.gz
    ├── 06fa5ab18ac0e3c2409f647f393995e073beb759.nq.gz
    ├── 079568c9a79af2cc1d750c22b4423c4343103365.nq.gz
    ├── 079dfea6c856ff6cadd2d236e35911eada9c3e6b.nq.gz
    ├── 091e3cd61f8a8e99574280340a5f26fdfccfdda6.nq.gz
    ├── 099ea90c92805ff35e203682e154197dec56b266.nq.gz
    ├── 09b0c18689bf0818ed9000df01be79e1512080ba.nq.gz
    ├── 09dffe48650636d3337676a0fb55cd09d01e8ebc.nq.gz
    ├── 0b916aa5d9be4b7ac79c43b948495fdd371dafab.nq.gz
    ├── 0c2a6bf4ac9c2284baf043cc7f921880c0fd0d10.nq.gz
    ├── 0cba373bfaf3e3267f95fc12191aa3cd0f2d0ba7.nq.gz
    ├── 0d3de3816dbf85194f9d1f756e53107249439063.nq.gz
    ├── 0d83c16715f215cfd063e6b3fbab4b3d4e1e23c6.nq.gz
    ├── 0d9e3a118c7e9134f3e1b8b683d404f8422402c4.nq.gz
    ├── 0dee79867e8cda9ca916f2d66f61559f2ed337a6.nq.gz
    ├── 0e6d5de2cbe42901f4d3cab51fef2337672f4b30.nq.gz
    ├── 0f4b9616af86fb8270d509a3fe37f4015c74cafe.nq.gz
    ├── 107a86d8a685dfcf57080884e30b6fbbc1818d97.nq.gz
    ├── 121789cc7be0f78a209095a4268d22044d80fc4c.nq.gz
    ├── 1337256a5074756ba7eb5e083f70bf2c1f1f0154.nq.gz
    ├── 13669136336c2f3a3e1220f1776aa4edec4c7164.nq.gz
    ├── 14cf759be1987332bf354427891be17a0db653bf.nq.gz
    ├── 1597e3ebfd8581c09e24b08d7d8efaa07155aaa0.nq.gz
    ├── 15f5c38a9aaad2f4051d309b45b80688e713d7f8.nq.gz
    ├── 16758e01cfb3fc9bfd7364a0a044654a36d202fd.nq.gz
    ├── 17666645465b84a339fca4b2e7d192bd4a3064cb.nq.gz
    ├── 17999b31ac0db33d430960cd51a5ee33f2617914.nq.gz
    ├── 17cb42594c5fd8cd79f14bd185ca4f93d282a48b.nq.gz
    ├── 17d630d1e46d97bb78c4e5173fde0a61168ee24a.nq.gz
    ├── 18b5c087a8ad9b9eece13b4da48e97cb8a42936b.nq.gz
    ├── 191ee3c80a6c3060c5e052a9056ef1739cb7e608.nq.gz
    ├── 19d03296316b98231232e0bb92cf5f60c9358491.nq.gz
    ├── 1a8b84a80a313decf77f9ca217a390790bc11c79.nq.gz
    ├── 1a929d24f91ae38ec6025f04164d528b7f368679.nq.gz
    ├── 1b55009a60dd60bb534e0bc9283e851383273c3b.nq.gz
    ├── 1b7fa2e2adac9fe60f4e0bef629b5d2890fbc10a.nq.gz
    ├── 1bd713d56d55cd9422fdceda0c639cf05d2e04b4.nq.gz
    ├── 1c3977d5c717acb03d9e286d6de73475232019e8.nq.gz
    ├── 1ca14ac1e27650b08f37ad457c36225d2d4b7e4b.nq.gz
    ├── 1e6e049ca2b0b6764bedba94ba040e06bcad3bfe.nq.gz
    ├── 1f54ed2ac73a1eeaae8114f2f077992ca11f9d0c.nq.gz
    ├── 1f59827b408ff64ad573d38ab4d868fed3d8cfed.nq.gz
    ├── 1f60d70ea3b08a0de34c2813dc9af41706612e7a.nq.gz
    ├── 1ffa87bd61356aedf0021c95df3d5d9f0bae2731.nq.gz
    ├── 2003cee643a5b460111eeb948e9dccf4c6271dbe.nq.gz
    ├── 200c3082bd904036d5a72dd6d125e2792d9ddc1e.nq.gz
    ├── 21458ef94552e012c5c11ce012ac0bc5d4d24488.nq.gz
    ├── 216f3cacc0c57b03c3959866032358703bae4558.nq.gz
    ├── 21b8d8c6cb1aa3ebd693b3dd39f130f414db4450.nq.gz
    ├── 21bf41e819db347baad91f8444528b5670963b3a.nq.gz
    ├── 222f9e439674e9eff6b81454cbaf065a427b470b.nq.gz
    ├── 23489e4076f45e654c37eaa3c667c151b97f99e9.nq.gz
    ├── 23a898534cfbaf6497d5dea227e615358af93678.nq.gz
    ├── 24b65b0c9f12c905b0d820fd6307e38b1c6831aa.nq.gz
    ├── 2516fbc7bf162d09e37d78fc4af50546868d6dce.nq.gz
    ├── 252c35d0a5d2ba28aa1b7ff53960ae14668aa773.nq.gz
    ├── 25f5e0ba44021daba0d1336f2a8cf37ef939e43f.nq.gz
    ├── 26c17dd1779c0725514897b0784a1dcdbfcf73b7.nq.gz
    ├── 27456fea610b48df3fca830932eccb0e6df21fec.nq.gz
    ├── 274fa6a2ffabf6ed0301a82fa43406c0dc02bf74.nq.gz
    ├── 2781ca25fda8c598a75b43d7017eb21133a24629.nq.gz
    ├── 27ace48695191898c78e3a6b173aca21f3dd45f8.nq.gz
    ├── 27f76b654935199df27652c591c69e810a37ca76.nq.gz
    ├── 2881141994d4cb38b9d251f18df28cd484c1bc6f.nq.gz
    ├── 28898736ba018c43c54387065983bdf77d2a1245.nq.gz
    ├── 28db6f9e1120e4afa4226aa3e89d8bb463db56fd.nq.gz
    ├── 29b4a837c8d3eea7b3431453c637dbedd398169a.nq.gz
    ├── 29f98fb8670b2411e050397c17e7c9ecf70e45d5.nq.gz
    ├── 2a44d7147a164914b50f3eef07d3f66c745bbffa.nq.gz
    ├── 2b0d0ed5c48e3ee3d34ef43b2bea8b68e6269937.nq.gz
    ├── 2b164e01e9e13589fc04bf1a885b96e7ab4c611e.nq.gz
    ├── 2b3059dba6c5358ebc6d4e369bf454a14954e539.nq.gz
    ├── 2c40c4627c69fa5405e21122f47669307937f704.nq.gz
    ├── 2cb4a137abc203ecdddb53c7372c168efe1eb026.nq.gz
    ├── 2d3df80877e3189bfe982f2605532cbade79e2f9.nq.gz
    ├── 2d7056bac6f17c7d637f451b9e80afc81db7f8e1.nq.gz
    ├── 2d8cd33bf2210ab11a18f776d16e6a8c1599d8cd.nq.gz
    ├── 2dbe5196ff18c2b32edc3b770f2b69f02c3c2a26.nq.gz
    ├── 2e9de338e1769233f91cb5bd32d66c9fd69de022.nq.gz
    ├── 2f543b1d8126899e6207c7fa3e0ef2ff77b1ff28.nq.gz
    ├── 2f934a9a9281dc7ae9e13d2fa65133dd565339df.nq.gz
    ├── 300d1e9325682dae5d5095368d75763a6ca19b35.nq.gz
    ├── 30472303916f63dacd1545128010a3ab673a84b8.nq.gz
    ├── 30bca1faf6e3a5f914ebcb88d4db49169dc67175.nq.gz
    ├── 3120ad84d055f2e4cc9064da59c0e40b43dfa72f.nq.gz
    ├── 317e01bb29de359d0fbf7a444d3acc667c692bc3.nq.gz
    ├── 322736f764a727196b129e7df3f9ea5e1405ec69.nq.gz
    ├── 323d7c6214c5d7cc929bcde4ca3431a4f7dd3e57.nq.gz
    ├── 327c92ad63f5fbf298d3b3ae8f413ed0d64328f5.nq.gz
    ├── 334bc8ced495c8a05f52f3a9d225aef89d25cbcd.nq.gz
    ├── 342ba861a4119b8200cc8630b8aa3370fffe4477.nq.gz
    ├── 34e3bacc11f010f7272495401f3d7f42e9185f57.nq.gz
    ├── 34fb134e22dfee296ceb0472e66068cd0dc10573.nq.gz
    ├── 35f77271ef93948cbd41fa0888a2ac69c9dc9215.nq.gz
    ├── 367f22373fdc4455a2a6325ed2f188f2db5d72bf.nq.gz
    ├── 36966f0552fb68948ec76c95c354882322dfc602.nq.gz
    ├── 36d95da4c272d040cef216c5bc4d95d1c1115e7e.nq.gz
    ├── 3734e21e99bae45026e14c8fc8397c44ee456e1b.nq.gz
    ├── 3740b53c809e4d74f5d9cb7974b061905bb8fecf.nq.gz
    ├── 380648528dc20f780f94d0e46097428a7a8cff7e.nq.gz
    ├── 386bc5feacb3238a1d2c6363e373bc41f55451ff.nq.gz
    ├── 387b95b8d1ed88b48cffdb73f1d6c061fc500f83.nq.gz
    ├── 39904815093965fd4d9b0f139986858e1cf81e6b.nq.gz
    ├── 39aef00050d1793f27431bfd1cc0ebb970efbd65.nq.gz
    ├── 3a4b6cd48a02b101d60a9aa81bc1b16e9da00031.nq.gz
    ├── 3ae5a607f4f46ae4e9420356ba5f1269b7dd4c2b.nq.gz
    ├── 3bc16317bac398ea3903c07bf5f92cf5d2f45618.nq.gz
    ├── 3c0a8c0248d665cbdbbff364bccb2d6199990ac9.nq.gz
    ├── 3c4589858e6043f460b650e6711610e7af00c7be.nq.gz
    ├── 3dad275f55bf05dad41d5f167285e7ccfc2aa43b.nq.gz
    ├── 3e062ff2f40f88767295d211af163370ee334da0.nq.gz
    ├── 3fb0401ccfe4894eaacf553d790a7392f9773ebc.nq.gz
    ├── 421a9f30b817dd6f2dc3461c1efb2d0db8ad3bcd.nq.gz
    ├── 427d59513297686a5883cde88a16c5a64b5baef3.nq.gz
    ├── 436f170a8faff619a2ed500e8c1a42ea59c30ded.nq.gz
    ├── 43e9477094d2ce7599844d98168cdeba0085e515.nq.gz
    ├── 4470301b75cf17e8dd7b9574f03d2b7f8ad61cdc.nq.gz
    ├── 44e92dd0a266f48045ffd651f1f93ee1ec2a001c.nq.gz
    ├── 4595a36b19520a95c5a7061d2ecc9318dabdb85c.nq.gz
    ├── 470164ac113e06001fd5c326ac57b562d38f71aa.nq.gz
    ├── 47779eee01650dfe21380d6fe3812574cb227b53.nq.gz
    ├── 482928353e7de3fa4ad32c0008b7ef727a52ec81.nq.gz
    ├── 489991429302feeca9b73ea4ad0f7c6cf5e14a2f.nq.gz
    ├── 48f93b6ed1fbf1fcf17336eeeee2f1b5a06f2ba1.nq.gz
    ├── 4a36d46fd89ff4cdb2ad99fb5900214f368bcc21.nq.gz
    ├── 4a671bd96438d1b1f6dd33fe0650e263d87216c7.nq.gz
    ├── 4aa82a883d41f15f8da8026c9c7b167d39948dfd.nq.gz
    ├── 4ad303c5f32f74b01b659b466b2f44783616f008.nq.gz
    ├── 4b6e5599f67c71f0a60a8f909b9db4ea20b20664.nq.gz
    ├── 4bd136db45027fc79026f91364903a7b8e8f6eb0.nq.gz
    ├── 4d7c207b9494a0f89899eeabe7f9ad95237fd4cf.nq.gz
    ├── 4e296d485b983474cf103feeeff7a837d9b4e30c.nq.gz
    ├── 4e603d57c325bad45e2ea0f1553016419ea971bc.nq.gz
    ├── 4ea8aef3046c3d728c7df1e66b3a91479d91c429.nq.gz
    ├── 4ee24e0745abef48dd4e6d5f1c94a2156b1cdcc9.nq.gz
    ├── 4f8e704f3e234908da2562d6b542565168e047ce.nq.gz
    ├── 4fe09f50aabde101b0bfa03a7df1336ab8d590c9.nq.gz
    ├── 50f28d1088e9a7ce40c08c57ca2b400f8b313ccc.nq.gz
    ├── 5282c8df45b41ef7e27cac5e9f19350610c4e296.nq.gz
    ├── 52ddc1a4a45f1aaf7955c1e51594d7e2cc7382f7.nq.gz
    ├── 53196cf8bd6981b78183118da5be618e38e37b5b.nq.gz
    ├── 538cddc700ac8b344fced1fab827ea1c3672f0d7.nq.gz
    ├── 53d35997aa0c50ca4c663913506e77338e67d3a4.nq.gz
    ├── 54085499f6d29e5d8f2d483d5c7098d96fe61dcd.nq.gz
    ├── 545baab4828226a2db62e0f747a04b241fb52547.nq.gz
    ├── 55613a957c15b01f6fe377ce0994b157ed212e7c.nq.gz
    ├── 557210ae3ceaae51ee06cb0de6302d6458f0d16c.nq.gz
    ├── 55eb343583de655ce77d8ae5f0f633547cb62b75.nq.gz
    ├── 57b8609c5bb4e1629b0699b79f49cf7f643d630f.nq.gz
    ├── 57bc73cf59dd1c334da9ec72feff8201078fec4f.nq.gz
    ├── 57eee7dd7d00b050cf786d252062e10208adf13a.nq.gz
    ├── 58506887496c2f53ae1fda8b3acede0e5b5a8ffc.nq.gz
    ├── 58a224844c2207883ca1a9db7908090b3f7e4316.nq.gz
    ├── 58cf3f32a79d93133c09a9997a4136c47517b5f1.nq.gz
    ├── 591810d9f42ec104b2f58f927b45354b58b0637a.nq.gz
    ├── 597fc6d05fe1379cc7c93561dfe25e544f8e1760.nq.gz
    ├── 59c70073bec68f4ce397ddadcfb7f29bff1ddd71.nq.gz
    ├── 5ac92defee603d0aaa0353fc2700603d559c84cf.nq.gz
    ├── 5b1433c3df9f80973415c8964dfb3f05e00e16cf.nq.gz
    ├── 5b233e6806278eef645e08bf4bba5c8d361310e0.nq.gz
    ├── 5b7e0657ff29a3266217ff1f0072b926836cc0b5.nq.gz
    ├── 5b7e1ca899eeba227b782da6676fd92e4d9666de.nq.gz
    ├── 5bb552c2aa13b57b91e82b5b06d815cd1305006d.nq.gz
    ├── 5be42b1498a0ea99ec9df2721f51bf955448db11.nq.gz
    ├── 5c3b2437e1c175554d03b9a031d335924f201e47.nq.gz
    ├── 5cc316870c1bb6a342d94a81a2a29361d8c517e8.nq.gz
    ├── 5cea631200696002136643ed0bc8cffd839d72db.nq.gz
    ├── 5e275eb8c0898d3ee690607e3692826d59b4a415.nq.gz
    ├── 5e652c4ab6fd99487d3983ee85b0335e0ecb15bb.nq.gz
    ├── 5f075ce77fa48e2a562a2f36939cacced0a4b5c8.nq.gz
    ├── 5fa9a098f8501c692d0a9606fbf38a33ec635957.nq.gz
    ├── 60012748bc9cf802e26e8d2a52bee6b4bc236ece.nq.gz
    ├── 6023d71e5b2e3e4f436c8c429e9eabbe0e092029.nq.gz
    ├── 6030c367d37bed3965f8f8edbfbcc98313b8561f.nq.gz
    ├── 60a98ddb49f211345a9f1ab4796e156491bd2d21.nq.gz
    ├── 616db2d1b9cc0b6f5d3872f712cc5d90067678f8.nq.gz
    ├── 61baa503c0d47b76105ef910b77c56decc9e98e1.nq.gz
    ├── 621c812021c23efbf8e604d2845b146e2f758498.nq.gz
    ├── 62216bc10b0756451d6f3dd9f3888b14fccc3ec0.nq.gz
    ├── 6259155c40ce3e5f01d8cc9456025a1f0747384a.nq.gz
    ├── 63680eca096e91b243eaaf66ce95e84491b2b258.nq.gz
    ├── 63a33e206e62030d88865b36ee5d2a45a16ae71d.nq.gz
    └── 64dd014d6c03afd6c821d26ad33ab9e1c71784f8.nq.gz

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

[google/flax](https://github.com/google/flax)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
