# Repolex Knowledge Graph of JamesNK/Newtonsoft.Json

RDF knowledge graph data for [JamesNK/Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json), parsed by [repolex](https://repolex.ai).

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
lexq download JamesNK/Newtonsoft.Json
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5f19fd9a7add1d149056fae2b6fcffa2f4b7e6ad.nq.gz
│   ├── lsp
│   │   └── 5f19fd9a7add1d149056fae2b6fcffa2f4b7e6ad.nq.gz
│   └── repolex
│       └── 5f19fd9a7add1d149056fae2b6fcffa2f4b7e6ad.nq.gz
└── blob
    ├── 0017997aff8d259c520de852ccb10880a5f59d94.nq.gz
    ├── 002606fa895a025d6d4dae13f94c71f00b74ee49.nq.gz
    ├── 0033ca3471f2ced4f028b1e229767445a5c788fd.nq.gz
    ├── 004a9ec0bf278d520e9433b28687eb4005ff43f4.nq.gz
    ├── 00603deee77d60edb8f49f523ae9ff77f8e2106d.nq.gz
    ├── 00b00f8f00993cc6a189a1e6598be3c33397162b.nq.gz
    ├── 00c5466fb99345b88440f480db23a166e814b791.nq.gz
    ├── 00d81359302943e958cecf3f117b31c6f7b6610c.nq.gz
    ├── 0101e813e837da6c6eb3801758b37e4f1d344a11.nq.gz
    ├── 010bd3b7a4725e03a8a5ca0a709d68366253df4b.nq.gz
    ├── 0111607fe1626893203d3b4ecf07a0ab9d360219.nq.gz
    ├── 014081f989553f789262478d9a493e973b0c1efb.nq.gz
    ├── 014362fa2cab3f74c0a92eb5472a1adcb0449644.nq.gz
    ├── 01574aeb545c1b22ccd54eb79222329ada66d44a.nq.gz
    ├── 0198d6605a270911c5b92c1c43f53729870d50a0.nq.gz
    ├── 019fbc1e59e44b82f500a0418a791a2b57491299.nq.gz
    ├── 01b2c18d9be93bd6a0bc23f9c36ad90ff2f6c1a6.nq.gz
    ├── 01bda6e7590e5c19b20b930894d35fb4bf96681a.nq.gz
    ├── 01d03b18bf7f5f4d15ef9943d1ec2920cb6e2649.nq.gz
    ├── 0232d2abc4f2fc4a73f2265452ded72b2da9d3b0.nq.gz
    ├── 02330d6ac30f0b6c742f9f086c268a24a697b972.nq.gz
    ├── 0251d8e3ea32329b4335ef0175043af5bc5554d7.nq.gz
    ├── 02723cb509559736059b143a506fcd6ab673e9d9.nq.gz
    ├── 027c96b49cee320137f9fdb3b6290fe7131aa617.nq.gz
    ├── 027d0210190cda157b93b2cd30a10ef292ab95b7.nq.gz
    ├── 0280c833f0978fb4c1f09cfd6a04ddb97e521bd2.nq.gz
    ├── 028c58a34ccf1f57287d5ac64a32232d0a94d159.nq.gz
    ├── 0299dbc6448d290b0edcf79a42dc8ab875fd7d1c.nq.gz
    ├── 029f62c460b2de26dad6d09439ee7f5ae99b9857.nq.gz
    ├── 02bf9aee4cc58b081b4297c20ac2653d4cf0e2b0.nq.gz
    ├── 02e57a5a43c8cdadb8cb110155267af05810e805.nq.gz
    ├── 02ef524d4e28dc8c3de2ed3dc62fda8b994e9d35.nq.gz
    ├── 03281c8cbe8967d5af34c9932ebc460a3916ce21.nq.gz
    ├── 033692c496698f46dcfe3d24fc86c60355a4aad8.nq.gz
    ├── 0365799d7b4935d91c6300a0b7800803aabf422c.nq.gz
    ├── 039722bf031ffa95435196e158e6b5cdf45d12b2.nq.gz
    ├── 03a445df5458c2d315c10e47bfd0a3da6b8773d8.nq.gz
    ├── 03b3f5501d0d208a05af634a759bb5842b677d68.nq.gz
    ├── 03c3efec5d447935b476daed01c25d6f2e1adf17.nq.gz
    ├── 03d9e61e17ede5ebe07059757bdfec61f6ab6a8e.nq.gz
    ├── 03e3e6bcc59b906cfd9dbc6f04eae20529d20124.nq.gz
    ├── 03faa522b74f35a873b144eb64804bdf0bee7d51.nq.gz
    ├── 040613abe0963f52822b8859804ba1b47411adaa.nq.gz
    ├── 046899e0844fed087ac258086cb2ca6f620fd18d.nq.gz
    ├── 0478d2c33d6964e745575002d6e2212ec89cee80.nq.gz
    ├── 04880f4fcdfe71f7eb0a9b4ed34aa5528f31cea9.nq.gz
    ├── 0489ef1eea90cfc6e7c06d30f316d4ea069805c5.nq.gz
    ├── 049c70a745f95d6ddab692c1ae0b13bc41e5cd70.nq.gz
    ├── 04bac5a2f899bfedd2ea94ca6064f074c6dcfb14.nq.gz
    ├── 050223916bddf6b77af3425430c46c3dfb7f520a.nq.gz
    ├── 051f0e0e3e6cc3a601e15c662058b63a9ef72187.nq.gz
    ├── 05434c2b810546bbf138c6efd10ba51fac806bf6.nq.gz
    ├── 0549b70588bccd8adb8fc04a81ba8de6316c9ca4.nq.gz
    ├── 054d42d655e39715e579045b587d536045d17404.nq.gz
    ├── 05715cbbc2fd250366c4434707ba85f5d945824b.nq.gz
    ├── 0577ca3b4e7d7afc859148fbb642c3fa297675a9.nq.gz
    ├── 058072b7cadd77eea394239eff3394f07dc9a79c.nq.gz
    ├── 05873fafdc43116f4adaa7d034e7ba074e0939d0.nq.gz
    ├── 05a5aab37daafc00a44ef8c6d07d4ea44cd10b6a.nq.gz
    ├── 05b019913ff615f415fbd4162d5965d6578f02a8.nq.gz
    ├── 05ca2debc2af8b34c758772d82d75b6f60365aa8.nq.gz
    ├── 061587bdeced183e1eda206e616ec18763bfec1d.nq.gz
    ├── 06306b76c081ca49d24a0af7bcb017fb1058bbc5.nq.gz
    ├── 0645631d2283092e1df9eb8ee843298474d5d1c3.nq.gz
    ├── 065d678a1498f5c8b65267f91804548abf8824b6.nq.gz
    ├── 0660360697a02f6a5397401c6065a11f31b74556.nq.gz
    ├── 066adc98cc4ec084d948f301e8b89a7538932b26.nq.gz
    ├── 0670a4e980a97828b9b0bd2d2acfda34d0752b15.nq.gz
    ├── 0689c84105603e7b226d7a9da97f6e737e80b353.nq.gz
    ├── 06927a47b2bd3662d9aadd2de4f27527ecbf083a.nq.gz
    ├── 0719a778b7d5546b34bded7a43784ab7db812b27.nq.gz
    ├── 0723c679c5945972f8b4b0894fabc6c2473fb398.nq.gz
    ├── 073d2986a693d3f6002cb8d5a7ea9351353106e6.nq.gz
    ├── 073edd9d00de69e1d830aa39e792198da10aac9b.nq.gz
    ├── 0745995b060c1c94c2b2583aa05516f9c1d7cd3d.nq.gz
    ├── 076d639ba7c09e673ef441605b02748d14ea6831.nq.gz
    ├── 078619794bd168005c3caba01e3bf9f7729148cd.nq.gz
    ├── 07cb72f35a1251206625060d4e42be11de47528d.nq.gz
    ├── 07cd6700fd6dfaecbff6e13a59b6a50cbb465f23.nq.gz
    ├── 07dc43a5ffdc55c00bebccbf3e02336de03288da.nq.gz
    ├── 07e6a7fe48a8706b04ca869a993c41aa9402458a.nq.gz
    ├── 07f063c4f5a258a392ee7f8e1f3ba4c1123dfdc3.nq.gz
    ├── 0815fcaa459a40b3eb792a314c14775e4537781a.nq.gz
    ├── 082506ecbdf9093b35328e60d20d45bfca5fec26.nq.gz
    ├── 08264466dc701bcc4a64c5468d38fa12c4e7df24.nq.gz
    ├── 0834dba74ee9cb13331b4705706a1bee067e8dee.nq.gz
    ├── 083a5e9a8f34bd43044f8a0205374ed63ae82048.nq.gz
    ├── 083e228dc937fe60bbd7bd4ff62eec5e65e58e85.nq.gz
    ├── 0853b2e3ccd0a867acfba0b28946b83f72578c31.nq.gz
    ├── 08586544cfd2a41859d0f2a54363be40efcfdff0.nq.gz
    ├── 08858c0384907054b01e292d13db2c553e3ba945.nq.gz
    ├── 088c69ced59919a763135e4f7efbd0df47f0fe92.nq.gz
    ├── 089b89d9e2925727565dc6ebda0a4bdb295723b7.nq.gz
    ├── 08b4fd4e0472ec71ce66f9eb9d834906cc7e9785.nq.gz
    ├── 08c4f831dbb734c01b41183cc952ace53ee3b295.nq.gz
    ├── 08cc4ea582fa498f48c7e477b6028474b93ac0b5.nq.gz
    ├── 08d968a5c15e889d40e17c776fb98754fd34d97f.nq.gz
    ├── 08f80948ca6657bba98709bde5cba0d6a110577f.nq.gz
    ├── 092a14e7020c53f672d162543bf4777f8a9394b5.nq.gz
    ├── 093c34cb7f5226b650e219672a96768cbb25b241.nq.gz
    ├── 0941f3e4086c4f4e42454b2bc958e45aaa6a7920.nq.gz
    ├── 094356b0e1c53059dd3355c6a41b1cfc4626edbd.nq.gz
    ├── 095010fac0032764563b42dd28a938ed7907d451.nq.gz
    ├── 09568bfad08c7069dec0b0c84d29c458c86191f5.nq.gz
    ├── 096a57926a5eee06133c4d742492222b30180b0d.nq.gz
    ├── 097621ed42b652101aa4ec1b3cf77bd490b7d86b.nq.gz
    ├── 0987bba8878d47ae1621885efa8818e1c797a0e8.nq.gz
    ├── 09a3ffc2dafd862bcf72bbc74853cd97606c630f.nq.gz
    ├── 09b168e90d5d52871f38735993281cfed089c2c6.nq.gz
    ├── 09baeb2d72a2fd24b5f968364c5c02962f42136d.nq.gz
    ├── 09c5283ce43bf83ec4d064cbe7f9b1c997a96664.nq.gz
    ├── 0a0012dd26ce1cb35f038038992e736b09029673.nq.gz
    ├── 0a226fce0a8d03b9de61ab5a037feb9f363c24b1.nq.gz
    ├── 0a3ff215f915f680bb1885a08f744c5696e6930d.nq.gz
    ├── 0a4806d32437d77156de34e7b8c5846d195051a0.nq.gz
    ├── 0a4f3557b72e455bc74bc6a18dd88e5627228029.nq.gz
    ├── 0a514c5b21317c274b1f25862dee609941758e4f.nq.gz
    ├── 0a614e21371818e25c19c61d6f3770e41699fca5.nq.gz
    ├── 0a6b31f24789c9be1875d917a09281c5531c2ac4.nq.gz
    ├── 0a7acf63fd38b20c36d9856d44860f33c07dfd60.nq.gz
    ├── 0a8bad20aa3166786d3afb2a8c57f8049ef00447.nq.gz
    ├── 0aa9fce58fbb29fc13a2040c172b7714eb607246.nq.gz
    ├── 0ab4fe83e97feda3d85a2984c9eb3e9fa36a0e55.nq.gz
    ├── 0ac1470abdff4cf69b33cba629024009cad1da1f.nq.gz
    ├── 0ac87882059e3a76a63ae0bbdf03033cd65b7756.nq.gz
    ├── 0b1b3e37c59347b1a1d4755705f75b44e394be89.nq.gz
    ├── 0b28fc3cb08fbdb84cad1ab0fd8b9d3eb7a667ea.nq.gz
    ├── 0b315c2106daf056a34764827fa3ca8affd2959e.nq.gz
    ├── 0b47bceaed84d9cbe195c1408a5c128c3f4788b6.nq.gz
    ├── 0b4b571863e420a74e3883b2811619bcb88e3a6e.nq.gz
    ├── 0b722a560516552566b36fe3d6a35a274115f02a.nq.gz
    ├── 0b94146d2511fae8329ac75ebaf81949a33fb7db.nq.gz
    ├── 0b95394030677a0b4e60340476d55759f3e43cc5.nq.gz
    ├── 0ba60d6e972ff31cb325601969961521fd7f3379.nq.gz
    ├── 0ba9f05728108244905c18f5cd0f67629c552163.nq.gz
    ├── 0bb4285b36a5d95d11555430f811914c2e3be517.nq.gz
    ├── 0bbddf3f0c0c0803aef7cd440201ab984d726cc4.nq.gz
    ├── 0bc3efb491f3d3ac4c16505f551bcd7211950055.nq.gz
    ├── 0bdcc7a004e66cb56663b2b75121ae781e9f68c8.nq.gz
    ├── 0bfc623173f5142c0d7c9de653bf66eb1dcd3fd6.nq.gz
    ├── 0c20b34161428fe433205d215a11f919dad7f6bc.nq.gz
    ├── 0c29dbd2cfc43c837c431fc6fda7860dc0330ad9.nq.gz
    ├── 0c2edce8ba8272e4c8585466be8d49879f7849e8.nq.gz
    ├── 0c650c232e9cb10271992dbe12509b399b939f61.nq.gz
    ├── 0c905d2118dc935cc0a59a13743aa6ef7f8d8c9c.nq.gz
    ├── 0c9dc8694a0c89e55a8bc84c65d0bf18870fa096.nq.gz
    ├── 0cac1b93f6537972ac9252fe5099797999c9c0fd.nq.gz
    ├── 0cebb5e8e9f897170124f6ce8bd439e7f85eca97.nq.gz
    ├── 0cec51b0c99416ae05c2d6c9243a15daff33a0c7.nq.gz
    ├── 0cf8f056508ad83e5b3e27f60f91b59d8d4138a9.nq.gz
    ├── 0d2de30adc3940db2548ce80d45a82ad814414d1.nq.gz
    ├── 0d2f665a635279d811022bd3ac397c47ffa2a817.nq.gz
    ├── 0d40ea5a0d631518a42b257aba04495c61ac6f02.nq.gz
    ├── 0d438b4b74064755e74054dbde71f2ceff0d52f3.nq.gz
    ├── 0d47416ec28bf7ee76ebc59986d90fb4b253671c.nq.gz
    ├── 0d5fffa24377ec5c54d5aa5ecd77b6a55a871fd2.nq.gz
    ├── 0d77eabb5d6f81f7b805381183bc47fe6f1a46ee.nq.gz
    ├── 0d8ce1d6b56b66f56fa09b4ef34d957b7f58520b.nq.gz
    ├── 0d938b6cae54d66470ce5e27bc7ceb1b5c3660a1.nq.gz
    ├── 0d9837a2d89b993232f07e6cd51910db2ac2eaec.nq.gz
    ├── 0da426d4008048c766aeb823c9368c9723cd4a0a.nq.gz
    ├── 0da96411f11212d4fa29811378d4da5223c370ae.nq.gz
    ├── 0dbd63fff9c43236c9de990bab9baf6b1ad12780.nq.gz
    ├── 0ddf69c7e54dc909a43c034d1a6f4ec09649ca6d.nq.gz
    ├── 0e18ff9607d931afcedc43f66caa54e61a013eaa.nq.gz
    ├── 0e26ce0756664d5a57fca1c3a3a3d24416af086b.nq.gz
    ├── 0e27200eded39f1bd00316bcc1c9ba99e4f4a728.nq.gz
    ├── 0e31a1ebedee4acde03f7206fe53d383bff2e727.nq.gz
    ├── 0e438a03f3c592b56a721668e0373a4f2471dcbc.nq.gz
    ├── 0e506885c04bc5dc69aa7e47d795d7aaa16473ae.nq.gz
    ├── 0e9eda1e2d3af75ae3731c7b95fed394d7df92de.nq.gz
    ├── 0ea50f0a23bf4cf3143b902b72d8d6163886858c.nq.gz
    ├── 0ebdeb8a8f3f084a00cbc36a0580d722f694ba05.nq.gz
    ├── 0ec0aa407f9bacb1d96127c1e5d880c57909bea2.nq.gz
    ├── 0ecc15d8281574cc7de235fa2b9c0d84a98cf0d5.nq.gz
    ├── 0eeb6e360229b4b1bb966da72ae1230b74f1598d.nq.gz
    ├── 0eede8514696704ec0e15aeac8e6df2f15243b6b.nq.gz
    ├── 0ef4b0ea253bc5921ccf3afe1a262cd88a4b5bef.nq.gz
    ├── 0f199c344341921568cf1753e50789629eacdb1f.nq.gz
    ├── 0f2f2ca737f0ef62032c1526200db4ca67ca627d.nq.gz
    ├── 0f4d72424c0cd995e5463a85e828df780c447e87.nq.gz
    ├── 0f500687f8cd8586e84dc08d0c35058c8d0696b6.nq.gz
    ├── 0f589e43048863677a09c920d8cc4526ec9c12f1.nq.gz
    ├── 0f60780baa8edf0dce20b8dc301bc4b206482d68.nq.gz
    ├── 0f8b8fbf5fcc1d856aae3fa26cfc349b2a00987e.nq.gz
    ├── 0f9a2ec930b2f6f19b14b5f9349bb38d51c49266.nq.gz
    ├── 0fb2f67e517c2100ec99579882a8008802a8f6d3.nq.gz
    ├── 0fc1b845d0d79a4cf7bec9685dfc7e14631fb219.nq.gz
    ├── 0fcc11fff4411ec7177b0a24e968eefcdd2b0906.nq.gz
    ├── 0fd1c3e1c3b74806d0be290bcbebac5cbacc0772.nq.gz
    ├── 0feaa490fbf083e268cd94aa47379c4acc51086d.nq.gz
    ├── 0ff3fca103278b3476957b8cd04eea6061881370.nq.gz
    ├── 10081061cfd7e11ed98a2875642cff0ef40efa9a.nq.gz
    ├── 1010939ecd635e469f77a6b38bd5ebb00d14ae56.nq.gz
    ├── 10192bd72b561079b9e9c032512b45c850fc274d.nq.gz
    ├── 1041002c3c2dfe6086cb8d02e8dab4f7640c805c.nq.gz
    └── 10449d617231a74c90e5a481a617439bf8077ca6.nq.gz

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

[JamesNK/Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)

---
*Parsed on 2026-03-22 by [repolex](https://repolex.ai)*
