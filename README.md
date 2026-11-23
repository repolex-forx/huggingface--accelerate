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
│   │   ├── 2cc46162882e3e59bb1ea5d5d113191f6c1d5b73
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5dcd16e78969a79c65f34b4abbaad7bb0bdc53b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 61ff83394592db1052be9e64ab46beb21d794d69
│   │   │   └── chunk-001.nq.gz
│   │   ├── 623cc0ba588d192c77758939a6e340adf07edd4f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9a81156b4b46943fa64d098701c48c98c5f20243
│   │   │   └── chunk-001.nq.gz
│   │   └── e6ee1337014f6f97c3cf58f806aa28a0109f09a5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 5dcd16e78969a79c65f34b4abbaad7bb0bdc53b4.nq.gz
│   │   ├── 61ff83394592db1052be9e64ab46beb21d794d69.nq.gz
│   │   ├── 623cc0ba588d192c77758939a6e340adf07edd4f.nq.gz
│   │   ├── 9a81156b4b46943fa64d098701c48c98c5f20243.nq.gz
│   │   └── e6ee1337014f6f97c3cf58f806aa28a0109f09a5.nq.gz
│   └── repolex
│       ├── 2cc46162882e3e59bb1ea5d5d113191f6c1d5b73
│       │   └── chunk-001.nq.gz
│       └── 5dcd16e78969a79c65f34b4abbaad7bb0bdc53b4
│           └── chunk-001.nq.gz
└── blob
    ├── 00d06aab98f2a5489d7a1505dc8e1107fcc20762.nq.gz
    ├── 00db75fc22be46b34558fea2e4c125b115b8f53f.nq.gz
    ├── 00fb0dbfb85d38c0db05bba2196a9f9447dc77d6.nq.gz
    ├── 0128fddc5f4eb7642d70e18617d7dffe8d0bf37c.nq.gz
    ├── 020c0e820e5554d4a5f80f2a86b7e5315bc8d06a.nq.gz
    ├── 02edee66e8a0added1f96a91254ed15669d85311.nq.gz
    ├── 0301a188d52456321ec457448ce1502a735fa2b2.nq.gz
    ├── 0313418667a8b522e194f3416f6ac835e9391b91.nq.gz
    ├── 036fec94fd3cb1c8eefbff107fec439b292d6e2f.nq.gz
    ├── 0384963a9504fdddeedf8f7d00c0203bbdf11176.nq.gz
    ├── 048471154da0b1b8feeb39a6e93be7609e4754ad.nq.gz
    ├── 05a7cfd87122b3b2ce362a3ad31d1f248f43aae0.nq.gz
    ├── 060e87188dba13e641d179eacb858e631f23ccd3.nq.gz
    ├── 0704088d2096902c952867add39892c32b1f661e.nq.gz
    ├── 072473a952a8747c7d325008ba65179ad80659c7.nq.gz
    ├── 07a7df28c39d0ff148c448cd2564031a16e07689.nq.gz
    ├── 07b6f588b8ab93744ebfe1a3549f5d4da46f0cc7.nq.gz
    ├── 07c2986dd2ae3bb3d782ecd00530f135eb7eb32a.nq.gz
    ├── 07c3e1b83e085011f4ccdd6811ebd91938aa7d41.nq.gz
    ├── 0869d0aca232407f1891e2d8109eb33026c9c9d2.nq.gz
    ├── 088c0f6efd2a8d7e64a778d70450dd0966984446.nq.gz
    ├── 08cbbeb844bcc3189c99d328580c251aeafc2052.nq.gz
    ├── 08f6eb9d3226a8641b246b2e75c9120391c32139.nq.gz
    ├── 0a2381ac4182437151c1840847970bb6ade6bcbe.nq.gz
    ├── 0ac665104ae9ae5a4feb63af5d60ad636f1d54a2.nq.gz
    ├── 0bac1079c3bd4936be553c3ad8a8bbd67b4d9815.nq.gz
    ├── 0c6fdde5530e57f7af04361d1022badb2979f370.nq.gz
    ├── 0c8b965135072b708679480a496c342f2bcdea6d.nq.gz
    ├── 0cd3fec55d5a4ea77c16168329a3d29f769fe1ed.nq.gz
    ├── 0d297144db391ee9e75618f076dbe1c938cec1ad.nq.gz
    ├── 0d923898e9de66dc37ccd778eb29a50a9ac18e21.nq.gz
    ├── 0d9892b691ea822b77e6a2e03ad545dcdff6465f.nq.gz
    ├── 0db5844e026d1c035670e518a8f81d33136ea665.nq.gz
    ├── 0db61ad13c930cb9eb32bb5c53048033777d0389.nq.gz
    ├── 0dcf67b5631f1234db6d8aa34f6a0e67ed72252d.nq.gz
    ├── 0dd23c8e39a0a499a85e83f8994199aba66beb75.nq.gz
    ├── 0e86e870205263883752c32f2ef290612d1b6f78.nq.gz
    ├── 0eba7bc3d61cb012366f43a31873871f6d29a83d.nq.gz
    ├── 0ebac2b2c0b89a781c35fc8d9bc3971ed58d50fd.nq.gz
    ├── 0ed184b4ce00a975a0cf06db333a329eb26d2313.nq.gz
    ├── 10044293ee0801e8b5201eb6e86a8efbb3a3f77e.nq.gz
    ├── 10a381309f9aed121f8e17e1a7464aa58657a785.nq.gz
    ├── 10ae5ad2c2a724dc2e9a2f21264f2495632f475d.nq.gz
    ├── 11e9432ac218e6944c6d006f3dd1a5256f1dd0cb.nq.gz
    ├── 11f7115acbd41fc3126da55a1a1914c34c1abbad.nq.gz
    ├── 11fa84e191aac0a45acb776b17333560b570a04e.nq.gz
    ├── 12e087d891fad40d3ce0515e226c39e561d19f55.nq.gz
    ├── 13b551abd05a8e600d34a3e5699a45373fb4a731.nq.gz
    ├── 140133926c2f88d39c70f5a9f46a08f88bed36da.nq.gz
    ├── 14e0a66ccab18a6bb9fa678c4a2aa37d4c6ad907.nq.gz
    ├── 14f2f4f5a459fef9e9862ab32ce42c36e2ed573e.nq.gz
    ├── 1563cffda8f500200924130ddf1e57497f6f2750.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 16111314f4f733d0551f3ce917a58e4ff74bda0e.nq.gz
    ├── 1615bc313b74d4f01166384435b6c499ff616f49.nq.gz
    ├── 162034287c751291fdf6aa7b6e79b0a918ddcbd0.nq.gz
    ├── 16d2d82ddd89b4a0fb5d11246e4fb3aaef42e436.nq.gz
    ├── 1708fe20958ef8b3346069f811d0627dbe962b15.nq.gz
    ├── 172445c305b2d469c26997df35a97c1c22fe25ed.nq.gz
    ├── 17954bf851a1a4320b8f0fe9eddeee242062da9f.nq.gz
    ├── 17ae88a93316e9832af8dd57374e35a3c0400a7c.nq.gz
    ├── 18549cdb31492650e707b6008e25eeac8e33b04e.nq.gz
    ├── 1892f195d7e619244ea1a9b6602f31d686e1af25.nq.gz
    ├── 18e21c8086b51b0df8d213a3afa4878dcc503a5b.nq.gz
    ├── 18fd8b58da39d3b522daa69cc51293ad74138a0c.nq.gz
    ├── 197055fe6da5af66c365b01d5db0b50593a94db8.nq.gz
    ├── 1a24abbde0f0e1861a8909a0d68f508b71fd92fd.nq.gz
    ├── 1a685315827f15caedb832a76ea66d2639f1e85b.nq.gz
    ├── 1aa9b095e257bf63623b5127624b54c4a376c5ff.nq.gz
    ├── 1aaa7db5df999b89b503094a09c3ad60d6b03998.nq.gz
    ├── 1aea2085be30eeb6f7921bb3039babf73bc7e3d3.nq.gz
    ├── 1b6dfc7bd359c13081d50b117eab0d672f2b9b12.nq.gz
    ├── 1c8dffa81a05d107dbe0b53d6623cb1c6b9c5913.nq.gz
    ├── 1dbd86c46b4a0c12df8ea4d736c7cd1e03f81813.nq.gz
    ├── 1e9107f4c9a0635b1a931ed169eb435dc08a3145.nq.gz
    ├── 1fa8a13f238afd7b908ee8e8cb8e0620f48d4ff8.nq.gz
    ├── 1fae42170cbb336e79c433bcf02bce70b9c94d5e.nq.gz
    ├── 209169a7c1e2106256c5574f6b9b9d4c909f6e40.nq.gz
    ├── 209b035f5e375ec5f09a1e99895587fc5c8cba1d.nq.gz
    ├── 2140f8a69ee8719db95f4f8c6a5588bdf045bb46.nq.gz
    ├── 218f4a50914b85d1d29ddfb6e1f0e33246b90be5.nq.gz
    ├── 221b887084af9a3468f793001dfd9a2759a20cec.nq.gz
    ├── 227121bf611d21433b8c91c0a2440821dca8ae31.nq.gz
    ├── 22790c40bfb7c489dda7e5e5aa172998f80fd45b.nq.gz
    ├── 22db891c63d9bd48691acd87a15a206c270017a9.nq.gz
    ├── 2357fdf03ba533714bf517e67269b3be36a78e39.nq.gz
    ├── 23ccd264b936503c7d48be0f15e6a8ba06221bea.nq.gz
    ├── 242542100ecb2f8f4e79ac237aa922895a1ab8b8.nq.gz
    ├── 24333fed4c76b34cf895f30a253a9a7042f9d324.nq.gz
    ├── 244654aa03189ea329ec6fb3fe91e56b6ec4766b.nq.gz
    ├── 24decd17fc27f4bcac7332058105368c37eccf71.nq.gz
    ├── 24ee971383c8fdda1491e2b5795446790755ac70.nq.gz
    ├── 252b618be464d591c19fa4205c68c534eb38bd4e.nq.gz
    ├── 25992affd2e97058883efb2a9897cedc84dcff92.nq.gz
    ├── 2604b3d23c5bfde4ced21f51c2b3a043372b8191.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 267c11b50b22250e781f94e3643b8895cc6aeb02.nq.gz
    ├── 26aca70ac6cd2af49570cef55977e3694202d446.nq.gz
    ├── 26b09a081d76480b00f7e72bb184af1afa65d742.nq.gz
    ├── 27cb0430772257aab7404a8a8f43c2772859ad21.nq.gz
    ├── 27f8bc7c2ff7ffe2731d971025d8b2f8296eb622.nq.gz
    ├── 28963c1956787b9f5331b7c2330fbd3b34abf2ca.nq.gz
    ├── 28a1c7f22cd33104e40eac98df78b130ee7c61d2.nq.gz
    ├── 28db7a0801cbff4fddb3c667f4174ca6f816d613.nq.gz
    ├── 29e0aece74eedabd6c7417c11609eb24aad8df50.nq.gz
    ├── 29f1e7964951725eab86d0ad3a6fc06e46b4511a.nq.gz
    ├── 2ac5d3904ffaf9e1b6e2ffb12d6254727aca422e.nq.gz
    ├── 2b3420f5d708920d1bc5a6dba37fd45b1633c15b.nq.gz
    ├── 2b559222c42a279376eda83d1664494e8f46aebc.nq.gz
    ├── 2b5a6c0530c632952529b0012ae31b1881e320ae.nq.gz
    ├── 2b753e6e206b3d1fbca55adb0cd68fc1e526c6ab.nq.gz
    ├── 2bace0f5615f37c84c1c3e77fe116081ed691bac.nq.gz
    ├── 2c3f8e5940f80a6dfbb59d3718e23bbc724ced6e.nq.gz
    ├── 2cab285e1f842b9cc374e6d3ed5b1310acb6da30.nq.gz
    ├── 2cdd94b82e0ee68a0895d66bc81809e3144c8b8d.nq.gz
    ├── 2d48661b7fcef92ef1168b74cc275c6d3ccc67a1.nq.gz
    ├── 2d4873c1573eb2ee7392162f440a76d4f07cd8ce.nq.gz
    ├── 2d6d9639a1bbf9fa4b1187c29794e9ef7b8c4526.nq.gz
    ├── 2d81dcb88850f7e2a6130f1360a2fb28ee0f48ae.nq.gz
    ├── 2e19e6caa4ae26b61dec7602f02199d3a4daf036.nq.gz
    ├── 2e1df35b611a9ddea66e35be5dd2bd2309ec5609.nq.gz
    ├── 2e1ff0f1b3a2256169a66e7cdafe354fe8bd5d83.nq.gz
    ├── 2e2499aa6f60f1ab57d3ea930dddb077b785553a.nq.gz
    ├── 2e2be5434b240105b523044d53988ee498bf8605.nq.gz
    ├── 2ec6fff41a79b4f1ad0d1849cbba640de67b113d.nq.gz
    ├── 2ec96b4347ca909d4e45d19b42d26592f60d27f9.nq.gz
    ├── 309fa8b5c5c7bdf6ceb740731c3fdfc075166c49.nq.gz
    ├── 310e46e1920466fdf57866919472f619a41f5b33.nq.gz
    ├── 3110af5786f81844d0c33dd7c3277e7377d15a26.nq.gz
    ├── 31b61364fe2630f2b03a0ac64749333b14f6eada.nq.gz
    ├── 326f37d7f93de2417e4171e5ffe91193fb97225c.nq.gz
    ├── 32932c2a1c1099684d53a3aa10d842a6f7f5266c.nq.gz
    ├── 337213453b3d15f610f41ac71c5afe15e034b38c.nq.gz
    ├── 354e72279027326f127077430a0b24ff5dfca157.nq.gz
    ├── 35c99399baba62f77bbaac8adf4e2eacdbabf779.nq.gz
    ├── 369bb638e60516cb1ef46dbe53497c915834cbe4.nq.gz
    ├── 36b7829c1547f4399b94fab51ca091fff20aa40f.nq.gz
    ├── 36bcafcf070cdb41aadc3d2bda2bfee7bdd0dcb4.nq.gz
    ├── 3729ecf4c72190bf865d620b6941206ab904818c.nq.gz
    ├── 3803048c7b48db53f1168d02400e53b3c6d5fdc6.nq.gz
    ├── 389584a4cb417f0e493f2bcb1b5e45980babeb98.nq.gz
    ├── 3928477299c5de958beaed171895d0f691954562.nq.gz
    ├── 398639a164320b9f9f6a14ab82166ddaf8d75f4f.nq.gz
    ├── 3a79ad97cb1fa6cc029d25f88581bf3525baeefb.nq.gz
    ├── 3adfbbfaa63c9ee3d517a67285fc6c9e31d7187f.nq.gz
    ├── 3b7373c296f84ec3abe304ba7dc2b7c3620664d3.nq.gz
    ├── 3b73c0d76770e581bb978303abe4e6cbd7468206.nq.gz
    ├── 3b7becf1b0c7f864b04e626b5313bae7647774cf.nq.gz
    ├── 3bb538908ddd10406396c8352dfffb051bca81ac.nq.gz
    ├── 3c09884600ca7a4fe32eeff9754d180d566809d1.nq.gz
    ├── 3c1c497e66f9a916b98b25f66ab57a8f33e3e8b4.nq.gz
    ├── 3c57e2bb28de3023a7a65df1385b3f92f455e00c.nq.gz
    ├── 3c5ccd6330687e26bda8e4ad473393dae030ab03.nq.gz
    ├── 3d1a81cedaf0b057f91401b7532874bcab75779c.nq.gz
    ├── 3d2012f097d402b754b4e943e30bab2ce54e73c9.nq.gz
    ├── 3dd2170aea8ba48a08e31c8031c0447825ec4797.nq.gz
    ├── 3e4174a9a6e7d12dd73ea7d972144759af55a7c1.nq.gz
    ├── 3e58ce77be655709f12a95c4935c391e1cc077c2.nq.gz
    ├── 3f17ce6bcc140f1accc2777f19d990b554eb5f26.nq.gz
    ├── 3f8b0103f8c1f3afd63b9eab7e4da63b11e6cc90.nq.gz
    ├── 3fc782e8cb456ead66be3c469b2037ca8bdaf99d.nq.gz
    ├── 3ff80c972f2f5871911e185ed78f6baeb0e85fba.nq.gz
    ├── 409f3302c36191d5f0a594ac9bd6f3253a96342b.nq.gz
    ├── 40b198d46aa24610d8eaf46424474d7c1c9881a1.nq.gz
    ├── 425dd3fecd323dc2cf161ff5b427662b82ee823b.nq.gz
    ├── 42857199f4f1b3832218e234bc70f535a22208d6.nq.gz
    ├── 42f4337fe608594b6b4b52ad3f0c436d109672ef.nq.gz
    ├── 43ccf311acfc9487bf6e13f8daa5be9fb0ce8390.nq.gz
    ├── 43e1d904886523744c75245d539fe3a74c73b3f9.nq.gz
    ├── 443407cd983dcb31711b75c2a6337f9a7af24584.nq.gz
    ├── 449d72d668541b8f4678076c5015d3d66a7a4899.nq.gz
    ├── 44a46e28f798cf7feec260670b58ae67d8b0c7e8.nq.gz
    ├── 44a6a4b7b7b509f8254341552fd1c31c81e77afa.nq.gz
    ├── 44e1ecc1d59c5691f284282fb8cd2259c8a70658.nq.gz
    ├── 454b6a6bd9b80229a25b8bb9dadb35103a2e8688.nq.gz
    ├── 456348ef9e6d01326d727b71c1dddd4177f89861.nq.gz
    ├── 45773d164c4c009d4c0d9a0c37cb93613b1a9160.nq.gz
    ├── 470206954505e52df0e78dc902502a843ab1ec58.nq.gz
    ├── 472080f9aeeb6cc1d724a0c94ae722384c521892.nq.gz
    ├── 475b53b5bbb71b959057126f8667d7f61eb9d0e1.nq.gz
    ├── 480d93088247ccf128bed6f6f65fda40902f21ba.nq.gz
    ├── 4857b3b5df22a3762280340a8b1902b249cd0c1c.nq.gz
    ├── 486f1d662673cfaaa62469be586d0b86d76e6306.nq.gz
    ├── 4874f4439938ef18997f2cfb78f55c83fae70965.nq.gz
    ├── 48b5bec1d688717750faa5b77704f7029d945d7c.nq.gz
    ├── 48fe0beb50a02f8f74c56da121d6fcca1a041a43.nq.gz
    └── 491bca260d6a5425e9c6e52beefffebc03c0e17f.nq.gz

14 directories, 200 files
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
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
