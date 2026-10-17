# Repolex Knowledge Graph of huggingface/accelerate

RDF knowledge graph data for [huggingface/accelerate](https://github.com/huggingface/accelerate), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/accelerate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2cc46162882e3e59bb1ea5d5d113191f6c1d5b73
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2cc46162882e3e59bb1ea5d5d113191f6c1d5b73
│           └── chunk-001.nq.gz
└── blob
    ├── 00d06aab98f2a5489d7a1505dc8e1107fcc20762.nq.gz
    ├── 00fb0dbfb85d38c0db05bba2196a9f9447dc77d6.nq.gz
    ├── 0128fddc5f4eb7642d70e18617d7dffe8d0bf37c.nq.gz
    ├── 02edee66e8a0added1f96a91254ed15669d85311.nq.gz
    ├── 0313418667a8b522e194f3416f6ac835e9391b91.nq.gz
    ├── 036fec94fd3cb1c8eefbff107fec439b292d6e2f.nq.gz
    ├── 0384963a9504fdddeedf8f7d00c0203bbdf11176.nq.gz
    ├── 048471154da0b1b8feeb39a6e93be7609e4754ad.nq.gz
    ├── 05a7cfd87122b3b2ce362a3ad31d1f248f43aae0.nq.gz
    ├── 07a7df28c39d0ff148c448cd2564031a16e07689.nq.gz
    ├── 07b6f588b8ab93744ebfe1a3549f5d4da46f0cc7.nq.gz
    ├── 07c2986dd2ae3bb3d782ecd00530f135eb7eb32a.nq.gz
    ├── 08f6eb9d3226a8641b246b2e75c9120391c32139.nq.gz
    ├── 0a2381ac4182437151c1840847970bb6ade6bcbe.nq.gz
    ├── 0ac665104ae9ae5a4feb63af5d60ad636f1d54a2.nq.gz
    ├── 0c6fdde5530e57f7af04361d1022badb2979f370.nq.gz
    ├── 0d923898e9de66dc37ccd778eb29a50a9ac18e21.nq.gz
    ├── 0d9892b691ea822b77e6a2e03ad545dcdff6465f.nq.gz
    ├── 0db5844e026d1c035670e518a8f81d33136ea665.nq.gz
    ├── 0db61ad13c930cb9eb32bb5c53048033777d0389.nq.gz
    ├── 0dcf67b5631f1234db6d8aa34f6a0e67ed72252d.nq.gz
    ├── 0dd23c8e39a0a499a85e83f8994199aba66beb75.nq.gz
    ├── 0eba7bc3d61cb012366f43a31873871f6d29a83d.nq.gz
    ├── 0ebac2b2c0b89a781c35fc8d9bc3971ed58d50fd.nq.gz
    ├── 0ed184b4ce00a975a0cf06db333a329eb26d2313.nq.gz
    ├── 10044293ee0801e8b5201eb6e86a8efbb3a3f77e.nq.gz
    ├── 11f7115acbd41fc3126da55a1a1914c34c1abbad.nq.gz
    ├── 140133926c2f88d39c70f5a9f46a08f88bed36da.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 16111314f4f733d0551f3ce917a58e4ff74bda0e.nq.gz
    ├── 1708fe20958ef8b3346069f811d0627dbe962b15.nq.gz
    ├── 17954bf851a1a4320b8f0fe9eddeee242062da9f.nq.gz
    ├── 18549cdb31492650e707b6008e25eeac8e33b04e.nq.gz
    ├── 18e21c8086b51b0df8d213a3afa4878dcc503a5b.nq.gz
    ├── 18fd8b58da39d3b522daa69cc51293ad74138a0c.nq.gz
    ├── 1a24abbde0f0e1861a8909a0d68f508b71fd92fd.nq.gz
    ├── 1a685315827f15caedb832a76ea66d2639f1e85b.nq.gz
    ├── 1aea2085be30eeb6f7921bb3039babf73bc7e3d3.nq.gz
    ├── 1b6dfc7bd359c13081d50b117eab0d672f2b9b12.nq.gz
    ├── 1c8dffa81a05d107dbe0b53d6623cb1c6b9c5913.nq.gz
    ├── 1dbd86c46b4a0c12df8ea4d736c7cd1e03f81813.nq.gz
    ├── 1e9107f4c9a0635b1a931ed169eb435dc08a3145.nq.gz
    ├── 1fa8a13f238afd7b908ee8e8cb8e0620f48d4ff8.nq.gz
    ├── 1fae42170cbb336e79c433bcf02bce70b9c94d5e.nq.gz
    ├── 209b035f5e375ec5f09a1e99895587fc5c8cba1d.nq.gz
    ├── 2140f8a69ee8719db95f4f8c6a5588bdf045bb46.nq.gz
    ├── 221b887084af9a3468f793001dfd9a2759a20cec.nq.gz
    ├── 22db891c63d9bd48691acd87a15a206c270017a9.nq.gz
    ├── 242542100ecb2f8f4e79ac237aa922895a1ab8b8.nq.gz
    ├── 24333fed4c76b34cf895f30a253a9a7042f9d324.nq.gz
    ├── 244654aa03189ea329ec6fb3fe91e56b6ec4766b.nq.gz
    ├── 24decd17fc27f4bcac7332058105368c37eccf71.nq.gz
    ├── 252b618be464d591c19fa4205c68c534eb38bd4e.nq.gz
    ├── 2604b3d23c5bfde4ced21f51c2b3a043372b8191.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26aca70ac6cd2af49570cef55977e3694202d446.nq.gz
    ├── 26b09a081d76480b00f7e72bb184af1afa65d742.nq.gz
    ├── 27cb0430772257aab7404a8a8f43c2772859ad21.nq.gz
    ├── 27f8bc7c2ff7ffe2731d971025d8b2f8296eb622.nq.gz
    ├── 28963c1956787b9f5331b7c2330fbd3b34abf2ca.nq.gz
    ├── 28a1c7f22cd33104e40eac98df78b130ee7c61d2.nq.gz
    ├── 28db7a0801cbff4fddb3c667f4174ca6f816d613.nq.gz
    ├── 2ac5d3904ffaf9e1b6e2ffb12d6254727aca422e.nq.gz
    ├── 2b3420f5d708920d1bc5a6dba37fd45b1633c15b.nq.gz
    ├── 2b559222c42a279376eda83d1664494e8f46aebc.nq.gz
    ├── 2b5a6c0530c632952529b0012ae31b1881e320ae.nq.gz
    ├── 2c3f8e5940f80a6dfbb59d3718e23bbc724ced6e.nq.gz
    ├── 2cab285e1f842b9cc374e6d3ed5b1310acb6da30.nq.gz
    ├── 2cdd94b82e0ee68a0895d66bc81809e3144c8b8d.nq.gz
    ├── 2d48661b7fcef92ef1168b74cc275c6d3ccc67a1.nq.gz
    ├── 2d4873c1573eb2ee7392162f440a76d4f07cd8ce.nq.gz
    ├── 2e19e6caa4ae26b61dec7602f02199d3a4daf036.nq.gz
    ├── 2e1ff0f1b3a2256169a66e7cdafe354fe8bd5d83.nq.gz
    ├── 2e2499aa6f60f1ab57d3ea930dddb077b785553a.nq.gz
    ├── 2ec6fff41a79b4f1ad0d1849cbba640de67b113d.nq.gz
    ├── 2ec96b4347ca909d4e45d19b42d26592f60d27f9.nq.gz
    ├── 31b61364fe2630f2b03a0ac64749333b14f6eada.nq.gz
    ├── 326f37d7f93de2417e4171e5ffe91193fb97225c.nq.gz
    ├── 32932c2a1c1099684d53a3aa10d842a6f7f5266c.nq.gz
    ├── 354e72279027326f127077430a0b24ff5dfca157.nq.gz
    ├── 35c99399baba62f77bbaac8adf4e2eacdbabf779.nq.gz
    ├── 369bb638e60516cb1ef46dbe53497c915834cbe4.nq.gz
    ├── 36b7829c1547f4399b94fab51ca091fff20aa40f.nq.gz
    ├── 36bcafcf070cdb41aadc3d2bda2bfee7bdd0dcb4.nq.gz
    ├── 389584a4cb417f0e493f2bcb1b5e45980babeb98.nq.gz
    ├── 3928477299c5de958beaed171895d0f691954562.nq.gz
    ├── 3a79ad97cb1fa6cc029d25f88581bf3525baeefb.nq.gz
    ├── 3b7373c296f84ec3abe304ba7dc2b7c3620664d3.nq.gz
    ├── 3b73c0d76770e581bb978303abe4e6cbd7468206.nq.gz
    ├── 3c09884600ca7a4fe32eeff9754d180d566809d1.nq.gz
    ├── 3c1c497e66f9a916b98b25f66ab57a8f33e3e8b4.nq.gz
    ├── 3c5ccd6330687e26bda8e4ad473393dae030ab03.nq.gz
    ├── 3e58ce77be655709f12a95c4935c391e1cc077c2.nq.gz
    ├── 3f17ce6bcc140f1accc2777f19d990b554eb5f26.nq.gz
    ├── 3f8b0103f8c1f3afd63b9eab7e4da63b11e6cc90.nq.gz
    ├── 3ff80c972f2f5871911e185ed78f6baeb0e85fba.nq.gz
    ├── 409f3302c36191d5f0a594ac9bd6f3253a96342b.nq.gz
    ├── 42857199f4f1b3832218e234bc70f535a22208d6.nq.gz
    ├── 42f4337fe608594b6b4b52ad3f0c436d109672ef.nq.gz
    ├── 43ccf311acfc9487bf6e13f8daa5be9fb0ce8390.nq.gz
    ├── 44a46e28f798cf7feec260670b58ae67d8b0c7e8.nq.gz
    ├── 456348ef9e6d01326d727b71c1dddd4177f89861.nq.gz
    ├── 45773d164c4c009d4c0d9a0c37cb93613b1a9160.nq.gz
    ├── 470206954505e52df0e78dc902502a843ab1ec58.nq.gz
    ├── 475b53b5bbb71b959057126f8667d7f61eb9d0e1.nq.gz
    ├── 480d93088247ccf128bed6f6f65fda40902f21ba.nq.gz
    ├── 4874f4439938ef18997f2cfb78f55c83fae70965.nq.gz
    ├── 48b5bec1d688717750faa5b77704f7029d945d7c.nq.gz
    ├── 49639b417dfa41259223c468d6f56b5f7926502c.nq.gz
    ├── 4ba20c4b523ab773949030aafb1c9fd0e0822a7f.nq.gz
    ├── 4c089297dfc6f0ae4cf6022d17b4694b81db288a.nq.gz
    ├── 4c414b004789d347f2a59e2d5e7f0bc0a0b4b514.nq.gz
    ├── 4c78286c5dbfb44721b0d3ea9a25c911fe7a19b6.nq.gz
    ├── 4cfd56f2ac5e2b6bc3579acfe29ef332d3d59e7e.nq.gz
    ├── 4d7778200a52b9a5bbf33979bbb3cd34090854dd.nq.gz
    ├── 4dbb9d5d38bd753be1c1d2e79298a13dffa9e8c9.nq.gz
    ├── 4e0ae3d27a465681f88a3c7c8355d82b2af48423.nq.gz
    ├── 4e638f0dd5317be1f1b9218e8115a7b45752646a.nq.gz
    ├── 5092ef31fc4715f901be6c1e7bfe80c0b140d767.nq.gz
    ├── 5166c0237eef6ad924fd401ca4974dafac224cfe.nq.gz
    ├── 523f6a916acba36c1e91c14fa4446ea1799ccfd2.nq.gz
    ├── 52a7aa4dca23f395f2842a1afe716d200baec0c6.nq.gz
    ├── 56c0d921a1c76619a93e921031b8a43ebc3c13f4.nq.gz
    ├── 57e49dcd9a275ff7130c62aba4191512d3ead67d.nq.gz
    ├── 57e69cdc6cf6afd6fe0bdb64bb39c50448d5013c.nq.gz
    ├── 592a7d5324e281f0bfc5490e4ae303cae1fe7df1.nq.gz
    ├── 59e813ad2d25c0911ddda3058a9bba01bec1dc2b.nq.gz
    ├── 5ada8cd4762fab13e5f8b46548c85489e296889f.nq.gz
    ├── 5c15924277fe067fdf7c4a251732aa562378079a.nq.gz
    ├── 5e2ee2e3f9fd0647a62ee310d1ca9a89afed9bd0.nq.gz
    ├── 5e2f88e7d5bf23e8575fdf6e7f441f0c4a64978e.nq.gz
    ├── 5e41646b94d46a8009f41980a1b55b5dff3c9845.nq.gz
    ├── 5f1669db322daf97b93c0c200502331961a8dfae.nq.gz
    ├── 5f41c02bce5025943d3ae06128f79b31e6323600.nq.gz
    ├── 60255de75f6e3c97b2ff6504eae5a4de7662baa9.nq.gz
    ├── 608b1a334523b24d2a78407f75a5cbffc07d548d.nq.gz
    ├── 609912bf542aa4d7eccf475689db066a5a8897c4.nq.gz
    ├── 60ee5a673fad86bacc83cc39260b1e648f64b692.nq.gz
    ├── 6263ffa68babf0a04d974102b838b0482964a471.nq.gz
    ├── 62f7f724636651f91dc9d8a08ab7e10261308a3b.nq.gz
    ├── 631da07bfcf90ec0ad324428b14e8924a94b8431.nq.gz
    ├── 649a15888cccd070b3d4ca9a600457c6ad59d4d3.nq.gz
    ├── 64fb6d6aa10121e90c1a4d61eb08d768799ba23a.nq.gz
    ├── 653d372d3f74ab5c55deffc9800bb80d77fb7ff5.nq.gz
    ├── 6619cbc6d0ae4e14e764edc2a8f54b94c81a050f.nq.gz
    ├── 67031886219f56344b1173c792ac4d8d421746d3.nq.gz
    ├── 674420e57fc21329cd466dc2a2e68f981c621bce.nq.gz
    ├── 6775cb76e1738c48f9e03ef03bec1d5fc5970659.nq.gz
    ├── 685863a4e330febae5a66132d6b116c453937cf2.nq.gz
    ├── 68997e9e11ffa70ecd63379c19f622c2f4fc85a1.nq.gz
    ├── 69283ab40a8f5229abf4bfbe4f7291e2fbb7bc61.nq.gz
    ├── 695462656d867dd2e865ad9d2517c473879da5b6.nq.gz
    ├── 6b1b8c959ef2ebf44d8f236176973785eebb707d.nq.gz
    ├── 6d64bf4f29a4f28a9f69bc0b4b01467dd1775dee.nq.gz
    ├── 6dc6eedc03f4a0aa5dd37c802a6e91ccdce5bc27.nq.gz
    ├── 6e444fa17c47cf7192386c57b6f7ae89b0967c60.nq.gz
    ├── 6f1425a2cde7dc9ca3b0c8e4209d10be43ffd24e.nq.gz
    ├── 6f183e3f8d3129e3384e0cf670810a7b129684e2.nq.gz
    ├── 71391014df3bb73ccb49c103dd25db65aea3c364.nq.gz
    ├── 71fb42dbdc192d4493d92c265fdaa62ec4eb5b34.nq.gz
    ├── 72414f2abe62d76bd5133f4b0ed99bf34133f6f6.nq.gz
    ├── 742b2af78adc976bc36da15e67b2890c3a862f7d.nq.gz
    ├── 7492857c18bc4cd989eb64e9f2e159ee43c0e753.nq.gz
    ├── 7522badb65bf846716c2a98c185792c133a4b945.nq.gz
    ├── 787db12860fe21c6786dda69c34fcccab114f2f8.nq.gz
    ├── 7a0da2404899e9335e4ccd7559d7af36f825be37.nq.gz
    ├── 7a524222e10aacb849bdb3e4bbbce1da45874459.nq.gz
    ├── 7a561c03dc49ee4b694114dad9deff790b8c0f26.nq.gz
    ├── 7a766dfcf60da6323ccd252bbb17ee6d0c0c2cbb.nq.gz
    ├── 7b825dd18b3594be13e818c7b895637c3e76b6d2.nq.gz
    ├── 7bce41003394bafc96ac0cd8f129be1a7f749cf3.nq.gz
    ├── 7be56d264ac08f17977f74ee040ca425584182d1.nq.gz
    ├── 7d543c7c3a9417d78668041c255387605142c7a3.nq.gz
    ├── 7d915a4ee60e5518f1f652f549476ed286e98e10.nq.gz
    ├── 7da4087c853396e081c289ea261175c170159ce4.nq.gz
    ├── 7e73eea88bc112a9cd32a4bab3e81535250186fd.nq.gz
    ├── 7f7877120fd240f0b7d0d7c152aaa4479d648bbf.nq.gz
    ├── 8081a27ee486e7f7000f269581bf6a9bf8837f06.nq.gz
    ├── 80eb70ea8d5a3b45e4a1e2fb81057a1024f2902f.nq.gz
    ├── 81ec0c965f6dae924f607f713ba6559457456fc1.nq.gz
    ├── 828e41e74978838389c274090025192b7d5bb55c.nq.gz
    ├── 82a0cc7ea2eb38d576cf809952ba9edd959e90a5.nq.gz
    ├── 83f31b24960299e311579a923e6cddeb4de96575.nq.gz
    ├── 846cd73614802f6e6f51bce59bae93f771b3b8cd.nq.gz
    ├── 84c88bca7e4c2d8755439cf8005dd29f0dbfa026.nq.gz
    ├── 8568c82be1c638c0ccd34d460fd8b0f73dcbec4e.nq.gz
    ├── 8736bec246721a73e5089cd0a3492e1ff687db8d.nq.gz
    ├── 8879933e6cda150267451c9e7d07dd22b7b0d3f1.nq.gz
    ├── 88c21934d4eb435565916376997fe16811057fb6.nq.gz
    ├── 8a18d7dc8e6d5646b77479dea010526b3addc90c.nq.gz
    ├── 8b2ff33577ead0d32f54818998427c845d3cfb63.nq.gz
    ├── 8bb324f0ec5b73bbef66a4742a44b1c60ec13615.nq.gz
    ├── 8d647bfd1f990ef9ff3a400cd668ef3209a53f3d.nq.gz
    ├── 8d9cc7a292d0b3cb2f1d071df44123ab849277b2.nq.gz
    ├── 8db6802b065f06b188bc441accb40de997743b7f.nq.gz
    ├── 8e70193f341dddd940d05dab613fb6f987d5338d.nq.gz
    ├── 8f01f9faba0dd62020914ed8ff62a7c8c8f99820.nq.gz
    └── 8f4a21504097ef327f4e4db5618f71171b42520e.nq.gz

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

[huggingface/accelerate](https://github.com/huggingface/accelerate)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
