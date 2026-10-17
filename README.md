# Repolex Knowledge Graph of espressif/esptool

RDF knowledge graph data for [espressif/esptool](https://github.com/espressif/esptool), parsed by [repolex](https://repolex.ai).

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
rlex download espressif/esptool
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── af1ed10290e6328416cf8c73076bba15b459cbb2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── af1ed10290e6328416cf8c73076bba15b459cbb2
│           └── chunk-001.nq.gz
└── blob
    ├── 00919ec55a55513ac115ef955c94189374359ad3.nq.gz
    ├── 00f62cab9e99c150dbd7badd952815dcf7dc2c2d.nq.gz
    ├── 01a98e3743baf5aa5508b7338da90a60547273c8.nq.gz
    ├── 035f30c5b5b6ba1f6a3d7892a7d5b350e279c2af.nq.gz
    ├── 03959b299ebfca222f768de2a1560dc9f7f6bc31.nq.gz
    ├── 05d0b5066dc07853cd50e59c160c91e03650c5a7.nq.gz
    ├── 063f790a95bf73e30b575ea0d228e39ecf68be6b.nq.gz
    ├── 068858e4d45527d4b09069214b56b632790ca865.nq.gz
    ├── 06d145580c1359c876e846bc9232b9dc4780dc0c.nq.gz
    ├── 07a71fb1dd1edbb1271d66f290278ead2f436ed7.nq.gz
    ├── 08a903daa8ea9b74c90dc91dcb880189766ca689.nq.gz
    ├── 09a50d0d8beaef011d4a64f00261706144600866.nq.gz
    ├── 0b6acb8a9f95e8f1a8b7ad47531f4815907447c8.nq.gz
    ├── 0bbfae881908abad82a122e8a55826447f3afef0.nq.gz
    ├── 0c4252dedaa345c89061cca429bb24e138190f93.nq.gz
    ├── 0d1db19dbaace2b255418489a1f10b24ade5da9d.nq.gz
    ├── 0d9df748aed98c3f050d847b4a2b6eadcd7934f1.nq.gz
    ├── 0dbfe4d8f9f8d084d4bd9ee01133f6b0ce875eb9.nq.gz
    ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
    ├── 0e8f5b9e71392ea839b9966699e78ee5814c19a6.nq.gz
    ├── 0f30051b51d7b2441ad25d7eb5d95644629164cd.nq.gz
    ├── 10090054868ab747d00d8c594ffe44c746c541a9.nq.gz
    ├── 10143c20ed4df96487f31685f0ac8ab1a3b9640f.nq.gz
    ├── 102da679448ceb72a49079d8ab1cbf92e64b6431.nq.gz
    ├── 105228f5772450674dafeff2dcf5fab11e5b5b95.nq.gz
    ├── 11e3bce1bfec8317ec20a4dcc6805ba344e57cc8.nq.gz
    ├── 134f2d41a7ce9ed3e2d6491518ad85b170e31489.nq.gz
    ├── 1422b596fee093b4a950508acb12dec08b927bd1.nq.gz
    ├── 1432b07e078c47b804341b618cd0cc89a36288f0.nq.gz
    ├── 144c201071935a4d24c11f419043b1bdc2081768.nq.gz
    ├── 15abeeb964662f6b84566efb844ba3de99f437e0.nq.gz
    ├── 167574c94bba26d5fe9501188a81c7cd6d99382b.nq.gz
    ├── 16fd312667a9d66905fd8c7f258fda958a9ef198.nq.gz
    ├── 17be52caa2aa67291c0555e02263510f1faba00f.nq.gz
    ├── 183b65089a9f567479f9a7c8771040e996701c46.nq.gz
    ├── 19227d8fae0e89e3124525fbd1e55a67df3d83ce.nq.gz
    ├── 1a5a92c57ed83f4160fbb276d16a8496ec550a94.nq.gz
    ├── 1a6b7e7997c114f45f5f17e92124918d8226425e.nq.gz
    ├── 1a74e68b176147c8a9f064264865a21bff680f5f.nq.gz
    ├── 1c3d8c95b47e31e680e96213e58e436e4ff74fa6.nq.gz
    ├── 1d3569671cce74f52e04ab9330ec301665ac26c9.nq.gz
    ├── 1da3d01c4987a1be907d80a55685d14a43b9445e.nq.gz
    ├── 1f8fda37580865309583a3b06628f943a27404c8.nq.gz
    ├── 1fd53d8a6b84dc1838dae7fdad18fb954b47c549.nq.gz
    ├── 204ce85e9f3c7cebcfbbbfc27fb0379ada60fc98.nq.gz
    ├── 204e07ffa38be1850bca8f57d785bbc9299f3ba0.nq.gz
    ├── 208e35edfd39bcc15674b88d309f29fb89f217a3.nq.gz
    ├── 221dc450263b9a1bb8eb3d4c7639f0fb987a91a1.nq.gz
    ├── 2222d4e55c754227055660ebbb3de2abbea36137.nq.gz
    ├── 228df47fb5ba017c47df81ddb7d335d40b7efbe8.nq.gz
    ├── 22cbe20fc29547c72903fbf66046de1257db7744.nq.gz
    ├── 2318517102ebf9de409907cc6fcc4dcca075712f.nq.gz
    ├── 240b05442dd11a631bb901c1f7508d111ce1399f.nq.gz
    ├── 244ccca12a3f99f808360a2e7563df41c18d92ae.nq.gz
    ├── 2533a3af010304e0ce3473831f257cbc667f5053.nq.gz
    ├── 259f61552155bfc24dc18f1b22bea7d29caa1968.nq.gz
    ├── 25e83c7f2a8ee23bd4c4a497e1c44b2f2dcc76e7.nq.gz
    ├── 261ebf8061711c3e2b942afbcc1f86cf518f69f9.nq.gz
    ├── 268666c87017be45b65d15da03f85b7455b59f3c.nq.gz
    ├── 29b8e48e83b7f4b5c3ddf61c75f8e6b5cbe8abbc.nq.gz
    ├── 29c855fe76a802ae3ed4f06d43747ea767ca746d.nq.gz
    ├── 2abb2cb2e3d6a35110f0ef1ba44942fd771becef.nq.gz
    ├── 2afea25f35dc605267eccaf2d0a3f4d889ff4452.nq.gz
    ├── 2b6e32e3b06563595fb94f3ce31ddb5bc2def576.nq.gz
    ├── 2c517e97ca41c41a82180acdd490f040eddc220a.nq.gz
    ├── 2cb3a2809a7ea55907ae042a178b08e54d7e0b3c.nq.gz
    ├── 2e0fdaa03dbd898cf99124ae9c22bcab170e9824.nq.gz
    ├── 2e81d0c1297790de88c17e1c9c00d5dfcd1ba2e7.nq.gz
    ├── 2ed193cc8b570b619bfd8d742de98c5bf31851e2.nq.gz
    ├── 2f2f647099e708485f4c5bf6c0043a62c36d113b.nq.gz
    ├── 2fea0bf07b32b4639657262bab4a7d284028748a.nq.gz
    ├── 3039091b5be063a8e43e69782d5d5a4903e84e87.nq.gz
    ├── 30befeebf172cab6d6741cc95091fce268f85fc6.nq.gz
    ├── 30f765b4b103d9dd4c65c5393a2f56642ebccef0.nq.gz
    ├── 314a061e8d7b78222c9b90401d4d6fe2e0ecd0d2.nq.gz
    ├── 31a2fb1854d2ba6ea838595e79e6746e042f3aa4.nq.gz
    ├── 31c40cca699a790e4211b0134137a038bd0a18cf.nq.gz
    ├── 31dfdc2d03f355a267fb7951d92c1760bf226194.nq.gz
    ├── 32717c7930d31efc661e7a9418aab8a2901ee2c5.nq.gz
    ├── 327a1a205011d8c4ae6d9882a3d30b80120fa1ee.nq.gz
    ├── 32e4361cf7c26b11e84e047f06a6980d5f3bab57.nq.gz
    ├── 32eca6bc3d6b2aa25693a557b18d1aa66c82c4b3.nq.gz
    ├── 32eed2754b0fcdf52394ba32faa0b72cb633324b.nq.gz
    ├── 32f3e3633717d0870c25c8fc16c56a5713eb883b.nq.gz
    ├── 333fa24d4c4f410534c8f2c8ea607f216d524f69.nq.gz
    ├── 33b1616adae83cb7122ae6b55efda39435ebf86c.nq.gz
    ├── 3439c21505f60aa59905b20decd612a6af53490d.nq.gz
    ├── 357f733a48134cfcce5b8f1618cc0d3dcfead54d.nq.gz
    ├── 363f3c8d180fd1a701861406f9701c7d5b945756.nq.gz
    ├── 3674ec0ffc819a2d0a708af64b5fe83ca1cc2fe1.nq.gz
    ├── 36b5a913743fbc851276390c5217dbd0e6258e7b.nq.gz
    ├── 36d41abb8802213a28a41b61478bafeed711a4e0.nq.gz
    ├── 3709b039939c7398b6651cc769fb7f6b21efcce0.nq.gz
    ├── 38de7b16ca87425c5adbf38c82e158f3d5bb3a82.nq.gz
    ├── 38e3e2d2dffced130c280d815f2626f80fb8df63.nq.gz
    ├── 39cc98c3aeefcfe20e14aeabe6ab8a47851b406b.nq.gz
    ├── 3a38450d3a01b6bec6675fd46ae6a6bce67776df.nq.gz
    ├── 3ade74c82a49ab6adc6763a55fa39a7e9b72382d.nq.gz
    ├── 3b178b9ea416909e30691ce46010d5d5f7002bab.nq.gz
    ├── 3c19eec517b1b89f7e667089267cd97c81d9f6d5.nq.gz
    ├── 3cd59ac5229b784201ef3d574e76987e831ba063.nq.gz
    ├── 3cefce1c93d30944501f0957ad3ac0c722d66d23.nq.gz
    ├── 3dddb106cc7be35423576a18fdc6fc1535f4295a.nq.gz
    ├── 3e3ed0c044a166e78bace314c8f6184996392415.nq.gz
    ├── 3e5863266351d4548beadf911ba5c2678cf59d54.nq.gz
    ├── 3eb32eac951f6181e8eec568eaaea19fd27f5e6c.nq.gz
    ├── 3f3d435552ecace08403ec228baa7c9d84321e7f.nq.gz
    ├── 40fb1ae98e471183db5c67882664c96be3d5b96a.nq.gz
    ├── 41325c4994156dbafa3bc8875916393463c12f2a.nq.gz
    ├── 421331a4bb6445d07aedd19c92dd074f61471f7b.nq.gz
    ├── 421e5dc7089245b4e20de45f2a8ad70fc45dbf15.nq.gz
    ├── 426e77fa84ca35cabb36b99b1f1ec427bc992227.nq.gz
    ├── 42ebc116812d8430c88c4caaaf4adcf66cb71c51.nq.gz
    ├── 437e0ced73dcbe53334914145d9067ca85d810ea.nq.gz
    ├── 439d8272215cbfb1f35ec2444f34451d256e3abe.nq.gz
    ├── 442ab8bc2eaf11885d5dd3ac6c04359fd35dea34.nq.gz
    ├── 442ecf77f9d4f98fd9c1fa6f6e602533c852a64f.nq.gz
    ├── 450051a1bd9c06b91768dab81e87a13e78d90d56.nq.gz
    ├── 45a3b5309e61ca5da4fa29a6a0a4b08038800d39.nq.gz
    ├── 45a4eaa084c84d1c9980976e0dd9779210f1a678.nq.gz
    ├── 45b5900e488dfde40d236192e64ab7004aead27b.nq.gz
    ├── 46e660e5bd48ba1f8979a900b9b9d822b8bbe968.nq.gz
    ├── 48ec542deae6181c180bd8fd42fc315cd0fa28ef.nq.gz
    ├── 48f5acdd8fb1f37788caaa657d9dd649e02bd34b.nq.gz
    ├── 4a7611e1be1e63f52e267018f99c520d7022273c.nq.gz
    ├── 4ad5d951a19e8f6d7967f1b23220983be67b5f15.nq.gz
    ├── 4af0288fcc66d3c307069f9b466641214a0d5802.nq.gz
    ├── 4b297a78fe5add51d2de8153f1e4be88a8e077d2.nq.gz
    ├── 4befdd4cecd41bcd2fbadc191f25204447bc447c.nq.gz
    ├── 4c8c9caee2cbdffa5f1b0a3cde607d25bfe66e38.nq.gz
    ├── 4e72191b14d51e5252ab81de7b1cad2ede550b09.nq.gz
    ├── 4ee0cd0fb632ea5e75952279fc55b79034806bb3.nq.gz
    ├── 4fa9eb3f7da4c99a9877071854097426818f89b5.nq.gz
    ├── 50d7e3e972cb60932089051cbac4cdee9192b30c.nq.gz
    ├── 51d73884cfaaf11332f770c47261b709c022dd4b.nq.gz
    ├── 536aade1684c37542aa6074ba561aacd05f82adb.nq.gz
    ├── 5425beaf692434bd72cecfb7b9772c6062da52d1.nq.gz
    ├── 568e22856986b095faa9ea29c0166fe118af2cdf.nq.gz
    ├── 571e6d9f9af91b9cb5fc97ba4479a3f11e0a2b5b.nq.gz
    ├── 579e5e93b11d4467b74431d207bb4f7fce7595bf.nq.gz
    ├── 5891afc1e8dad6940b59dc6e2204cd7f155e7040.nq.gz
    ├── 5912bc462efeb5f30924ca33590e267eb802e9db.nq.gz
    ├── 596cf6567e194eaba7025aaf054ddd59270b8170.nq.gz
    ├── 59a06af53cb78907e3a2b6e0f6904cb73e9f0392.nq.gz
    ├── 59e32bbfc0357700bde35e553e0db6e061b163eb.nq.gz
    ├── 5a6c1abbf1585a5e173bbb3ba4587cca5af2d057.nq.gz
    ├── 5a70629ed7d9cdc6634c9f1f8278d93c5ce2b562.nq.gz
    ├── 5a7998161b342a3c7a0765218c3affc9e785f93d.nq.gz
    ├── 5d1f86ed7a7475405613c3938fe5e99d80f77ed5.nq.gz
    ├── 5f510f4c1ae1760f82c1330f3721f30373782f5e.nq.gz
    ├── 5f9e03352abd2010ab8d5816efc6ffdfabeb3833.nq.gz
    ├── 619c94be115461d440894a99c917d1e6f5291f13.nq.gz
    ├── 622e1053fc5dea58a98ed9f58c55a501d6d5a649.nq.gz
    ├── 62593298a991c97eb8ec3ae9cfb99d95aeacbc64.nq.gz
    ├── 62723acefd062940e32b7a53c31de4cdfb5f6d87.nq.gz
    ├── 629b8902f176da67bf568a05baf21508332dee1b.nq.gz
    ├── 635662d9e3be4339d1f8c3d32c50ddfc0672b674.nq.gz
    ├── 641fadaea503f27dd76f3b348722aea282a45c1c.nq.gz
    ├── 652214e4706e9652971a78bb396879ad71d64a80.nq.gz
    ├── 65a0534508c1d77ad19435e484a4affcf5ee708f.nq.gz
    ├── 665679c10ba60caee4c5b851cd406a2946e20a06.nq.gz
    ├── 66af36e9bfa321493b9d8307c83edfccb51859b9.nq.gz
    ├── 66f0ed044ac82445b0ad73b7d0f5fb5d5d906c1b.nq.gz
    ├── 691ea08330d50e14f9f2de7d948ed22647180449.nq.gz
    ├── 69b59b9f01fdb44cee1e517a14322c392b351646.nq.gz
    ├── 6a6150b89b8fc626c6801310045083223ed6d898.nq.gz
    ├── 6aa54bb79d3d37ad573d20b0412c1c663324cbc1.nq.gz
    ├── 6b17a7a38ad130fdd10a90d7a0d4f2783c363788.nq.gz
    ├── 6b234435d2d1618efd6be31aa366236e5c89414d.nq.gz
    ├── 6bff0b6aafcf57bfa2f7fdc6e7196cb6a42e9c7d.nq.gz
    ├── 6c708d0c9268be11f49cab5a76ddbcd0518a6851.nq.gz
    ├── 6c90e1ee3b0e9e98191579ee926d2e6f0d9c9744.nq.gz
    ├── 6f0d61a2cfaf1b89fbded44fa3b9364e5d2c1db5.nq.gz
    ├── 6f4191a30a52ae6ece7e11b83e3fe8f5c7363a8a.nq.gz
    ├── 6fd5d7f986d82b138bc57e7779c6c9e53773eb1d.nq.gz
    ├── 700c67240e46d65498a68a592c5812acbb76fecb.nq.gz
    ├── 700ebed915eb4dd80a46b449a745597f78ba06fd.nq.gz
    ├── 7011b83078f689555e8bcc82de3b7ac448c5ea60.nq.gz
    ├── 71c01b5b204d63f190b7d86d85e294ad3df941e9.nq.gz
    ├── 71e178ad786e3deab99a1d7e95c66cd55d753e8b.nq.gz
    ├── 73068b768c59810784f26b00b6e1f5caed4aade8.nq.gz
    ├── 747c12a1da56ad90cd6d10e9faf534d574ab9ec7.nq.gz
    ├── 74a033bd35c862447d10f26fee27fb4597532c52.nq.gz
    ├── 752ddaef509067d84fa71cd591df34817788674a.nq.gz
    ├── 7566c37e5f26f143cb8af728689eb31c4fee8400.nq.gz
    ├── 75b33461b4dca4e9a15f5d0701dd0bdf833a20a5.nq.gz
    ├── 75d095fcc2e3b6ddf3d455bd6a2d0697ccb84478.nq.gz
    ├── 7614bf8aad05cbcd66a1f29b741e8f1ed315aa19.nq.gz
    ├── 7692abdfb7db52296fe6586dbe79f7afaad885f7.nq.gz
    ├── 76d968b74188d9c07fb4a046877266e594132b32.nq.gz
    ├── 77ba98ca7f2217031c944348a98dfa976b0c238f.nq.gz
    ├── 7865969f4922ab82135ba551a8f9ecd40c931af4.nq.gz
    ├── 78fd314df92eeedf8cf8225f8e30fdbb21c8c6f8.nq.gz
    ├── 797eaccfbd31ed38649f0715f52fda82b6976914.nq.gz
    ├── 7ae2520b3c3666d32a3386a732bf6659fa513da3.nq.gz
    ├── 7c3663663e59892bcc48359118a9dc1b9079aff2.nq.gz
    ├── 7cd5714ea1e5df7335b09759618c3b69ab843068.nq.gz
    └── 7dc73b4ca512363cfc5f0de7c778c937d7d783bc.nq.gz

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

[espressif/esptool](https://github.com/espressif/esptool)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
