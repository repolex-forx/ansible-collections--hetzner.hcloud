# Repolex Knowledge Graph of ansible-collections/hetzner.hcloud

RDF knowledge graph data for [ansible-collections/hetzner.hcloud](https://github.com/ansible-collections/hetzner.hcloud), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/hetzner.hcloud
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c4375bb34a4c4125c262e2f4814c4b7aad268971
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c4375bb34a4c4125c262e2f4814c4b7aad268971
│           └── chunk-001.nq.gz
└── blob
    ├── 0178009f113c3d5592010d965aa2e1125f697517.nq.gz
    ├── 01c8076de2a51ec5e3fdac64d9702fc6ad02b655.nq.gz
    ├── 041118d8f8c0bd2056eb37830d0d08d2c9354ec4.nq.gz
    ├── 041fcc9654235f784412fa1f666b4336fb8980b0.nq.gz
    ├── 04f3d67bb0d1699db1f0533f9381cb24931b5bc7.nq.gz
    ├── 052ce3cd40a1aea690ea46ab9a757c52e71ffde4.nq.gz
    ├── 0580e1218b5f68b436f6709f289ef50a006d4585.nq.gz
    ├── 06cd2c4b8ecba91641160d33583c9014a5242021.nq.gz
    ├── 08efdf348967f0bb3e421795d78be6a695147673.nq.gz
    ├── 0c0363cbcdbed3cda8beaa0028406cd653a5b4cc.nq.gz
    ├── 0c95d2c65611b8423310ce0c7b9533d4c503da3a.nq.gz
    ├── 0d85fbb21295a43f78181b1f03680acf1e6519cf.nq.gz
    ├── 0df360a33e61ba6b6ed9656e6153507d160ff667.nq.gz
    ├── 0f8686a5176a373cd96fb5e48a76fdcd74d4180f.nq.gz
    ├── 1041959e0def3eac0fee309e43e718bd1eff025f.nq.gz
    ├── 106d299ee4b016265cd6c996896eaa5a324cc81a.nq.gz
    ├── 116a632ba4d1895c940cd8062cf3bbbd26bdcdfc.nq.gz
    ├── 1242d43277017748bbbf3d0a104ec4cf78245822.nq.gz
    ├── 12ad679b8b969fe1bad0af56ceeeeb43e2cfd5a4.nq.gz
    ├── 13cb64ae084dbd54b851b0430f868f75bb5971b5.nq.gz
    ├── 1422f583607371985c0e88d5d9a45fb88628cdfe.nq.gz
    ├── 1551ef3e86ee93884e8eb886494d58e5c5a8e414.nq.gz
    ├── 163f4db09ec470b8b64200402ab7f0b860bb0125.nq.gz
    ├── 16affbfe627043aac3216b09d832bd8486a5f9bd.nq.gz
    ├── 17226236bc48bdd7d1cc915c0c3ade597b751ff7.nq.gz
    ├── 176a6b1804b4836374d75c14b794660c67eb363a.nq.gz
    ├── 1864e4441056fcc37fd4024ff19c946244d82a60.nq.gz
    ├── 18a884dc934ef18913bdf30cda8bcfbde67f4394.nq.gz
    ├── 18b11115ee77c020af2118548a59bf9a9fe6838c.nq.gz
    ├── 194dddc62d6a574893848adc10f6cfa9e315d105.nq.gz
    ├── 1b147bf7226ac6e3e5bdb0c3443117a40a9ee5d4.nq.gz
    ├── 1bc74fbfd902eb07a9d7d9e38ddadfb706ea05fa.nq.gz
    ├── 1bdac38592714fa48f1e9a366649e091ab3b0e78.nq.gz
    ├── 1c3398ea3051e2e7ec5e06ccd7e831d29d7fa905.nq.gz
    ├── 1d40e0588cdcc8911fba52527e14c0727ce25f94.nq.gz
    ├── 1d49f1eeeee35898ec1dcffc4bed31589f4f3889.nq.gz
    ├── 1dc9b9ddde6f2420d0a17f3a0ae18ae5304d0b01.nq.gz
    ├── 1e991caa356891df32470bada3260847699a05ab.nq.gz
    ├── 1f3926cc1c9c269b21cfc5d2769eafc879787575.nq.gz
    ├── 1f470551dbace0aa2a5a4e6d905de2905122ad6c.nq.gz
    ├── 20e8208606ae6895537ac93cd0bf74559e0075f5.nq.gz
    ├── 210a1eb369dc43eaf753d99e587ec17db19889ab.nq.gz
    ├── 225404b68c62ffebbe601c2c10d66aec17f380ea.nq.gz
    ├── 22bc9a39e086b123cf9ae60beb0690149b3d8612.nq.gz
    ├── 23d0ac87310b90ad87f811334208bf5caa67bc2b.nq.gz
    ├── 241c0cbc47336f64b0c65341bd7e6bb3e8ae1757.nq.gz
    ├── 24d580d21da91258d9e63c144cf91c052b091c1c.nq.gz
    ├── 2513909aa09b86c6f29a2227f1940550cc3995c3.nq.gz
    ├── 2566a96f44af595a40661ae53a4da981714774e2.nq.gz
    ├── 25a576cbac880cd4d8a6f3d7bc34ea58678a6573.nq.gz
    ├── 25a6eb787671ed60e386d9786bda52a8fc55b011.nq.gz
    ├── 25e7bb724c494af42b04502ceb32cbf683bfd371.nq.gz
    ├── 270285e9cd00bcf858b74728be44a3629173b19c.nq.gz
    ├── 28d832b0056c26f677cae2cfe3b7f46fea7f9eb1.nq.gz
    ├── 29702af85c990dc62cd737d81336aaabba41a11e.nq.gz
    ├── 2c14a3248ee341d618f5d31a30f2fbe4d6b55550.nq.gz
    ├── 2df913fd4397a1f5449a5b9d0a4366dcbe554f86.nq.gz
    ├── 2e96449866aef342252e9fa4c82e929b9dac7f7c.nq.gz
    ├── 2ec97686fb73768fc46492645245201cb3206c93.nq.gz
    ├── 2ed33338a244f71858da36c38fbfc356e91ea44a.nq.gz
    ├── 2f68028687073d829d6ca2a504b5149388ef7eaf.nq.gz
    ├── 3213e279f8fe387565cf31472073c72d4514d128.nq.gz
    ├── 32ea45060700a368b9e1f53dd60a8d676d16f266.nq.gz
    ├── 36ad43b40e639dc77a8bdd47495ad7455d8a3b89.nq.gz
    ├── 3713bd3358877bfb1a6273f8256572ae73770fe2.nq.gz
    ├── 375bfbda466fa2f45f44e693227c50ea2eab76b7.nq.gz
    ├── 379a372d62072f0fd4b28c0f3ca18fdb1fe95aeb.nq.gz
    ├── 385e70bac59c4b7ed66ff71fb59cdbdf466efafe.nq.gz
    ├── 386644a0459a5e8492aef39440687f6af44c75b3.nq.gz
    ├── 3946da7b83ac3105597107c3143bba08fac9f6b5.nq.gz
    ├── 39497f9da5c16659018c4571015387c074484df9.nq.gz
    ├── 3a2cb4fcbead941d98ada8aeff988edfad52646c.nq.gz
    ├── 3a96ecb2d5433c513b045c439fe582dc018c9639.nq.gz
    ├── 3d740447b5996b6b0ff4813fe43a46498cc46cfe.nq.gz
    ├── 3ed8e44edac435b01130e661327d1b4264e50122.nq.gz
    ├── 3fd9a8f5e21b62a22a7a993beb6e74675a4c82f4.nq.gz
    ├── 3fea3f39256a94ce3c03a32a75d408d77ebbc77c.nq.gz
    ├── 40db1f87d4c4d3e490fcab0dd2d0eba1b09885c0.nq.gz
    ├── 40e7daa8c58e3dcb599642c00b18dc08dd19b5b0.nq.gz
    ├── 41530b3709a82ad5b42cf5e8459fc4015aaa90e7.nq.gz
    ├── 41b2cea81ccef0a089e298526b628d37b96bc1d9.nq.gz
    ├── 441e948edb011828ef9fcca10435ef2fad20c498.nq.gz
    ├── 45f5039c6797bbf655fa20f6cc40ba30669f3aa9.nq.gz
    ├── 463cb0656ca98405e234c3671d9c9f5a4d66b408.nq.gz
    ├── 46a6a538ff89c53f0c66bb099e4bd131cc123a36.nq.gz
    ├── 47303597497760ea7fe967ef405ead4455195e82.nq.gz
    ├── 473bc56a5ee48d39ce4ddb41ce004e3b9c77e6bf.nq.gz
    ├── 47ff0beaffa3620356a22a7c5d9b7685455b0049.nq.gz
    ├── 49555d105c90eab8c59d57c20eabd023130f64c3.nq.gz
    ├── 49751f91266043deaeea820e4878a862b7727df1.nq.gz
    ├── 49f5c0c4bb663b0f50afa10e455ff6fd817be00c.nq.gz
    ├── 4b93511e216647d4ccfd70189f4d72bf1d1a9499.nq.gz
    ├── 4bdb959962e17682718edb605dac8a0a52e7ed8e.nq.gz
    ├── 4cbee7fb74d6d7015cfc7fb6fcb1dcab3507392b.nq.gz
    ├── 4dd0e91f53b28e25d3db2db1ee8d410b574c81b4.nq.gz
    ├── 4e0151a4b06914909ea7a49923933742eb641ec4.nq.gz
    ├── 4eb2272298fba51b51233108c23f164251caacd7.nq.gz
    ├── 4f660e96d75119d68cf713781525445bfa144955.nq.gz
    ├── 4fa4c0e1c1f7ceeb3a64f394e218e4a47ad2e8bd.nq.gz
    ├── 4fb66e8636c36b40098a42ecc23be640367bd5f8.nq.gz
    ├── 502f3a806ee752f419c476f2d9c5d7c1d1562cac.nq.gz
    ├── 504b1b5de65bad7ab52629da7e9a649ac0b0cda3.nq.gz
    ├── 5074e01dd4872d6609e5ec8d2b3a96fd1fc76a0d.nq.gz
    ├── 515fd48bd0bc2f44b827fe34e51201cc526a813b.nq.gz
    ├── 5175e62dcd13b908c92b9bd2f69004449817e033.nq.gz
    ├── 519bc852614c45cd9b59faa17d4514ceb1fdd26c.nq.gz
    ├── 51fb56eb3d24a3f3071f6a9c38b5594dc2e1327f.nq.gz
    ├── 5220424ed3dbb6c3e2c66eaa76d49f3fa579e7e3.nq.gz
    ├── 534c50a70c76f4007077aba0424347376622e6a4.nq.gz
    ├── 557219b0d1b1ec712d2a5a8d5b9adb03fb71a2a9.nq.gz
    ├── 5581fb2d9657cf02d30527c9bc65a25b477f2879.nq.gz
    ├── 56e2dae9c27897a998ebc321b59cdb7688d1670b.nq.gz
    ├── 571f29a8646e151065c524960953c15c8b4e9f80.nq.gz
    ├── 57c6929a4c52f44487c9dd475c314e6c39abdf25.nq.gz
    ├── 57f246a9d3a0ce41579d216127b2c5a80c62fc38.nq.gz
    ├── 590c0e87dcfd769872220b8bee8bb8179fd278d9.nq.gz
    ├── 5925f56929183933169c7431040adcabd77854fe.nq.gz
    ├── 59a50c8f7bcd0fa91bc118a257ea7b754c09beeb.nq.gz
    ├── 59b7f4428a6d95a09f36803b0e1715917880ed9c.nq.gz
    ├── 5a527ee0030069e830dcee2055930d4208e73fcd.nq.gz
    ├── 5a71c0f6d775f567fe139d6f27155973ff24ac6a.nq.gz
    ├── 5ae08fca038d2576a1bc4fd798c35ec5c75a5354.nq.gz
    ├── 5b567c396502487855980790b5a0fdc07470f908.nq.gz
    ├── 5b75c231a3270bde234fad5972042c99db597737.nq.gz
    ├── 5b85358e7831fa646178ff87e299d81edbec1380.nq.gz
    ├── 5c10843d552b903d50a2e41d4c7d7ee9bf4e579d.nq.gz
    ├── 5cace703a422c7936293f797a180b2610aa89748.nq.gz
    ├── 5dd7cfde7c6bc65d5be1736cce93a936ea077c1b.nq.gz
    ├── 5e009ace5478cf5bd64d4ebeeef63d3e19b1568c.nq.gz
    ├── 5ef9fb0c0ce4382169ecd477a3617806a07f0caa.nq.gz
    ├── 5fa63d71b6c721143ba738c21e8c5787b6c6c06c.nq.gz
    ├── 606f7789d80983b22589fdac5b72d985ec8f00d8.nq.gz
    ├── 611d8e00cefdda5d0b0c9c8508de32c9bb7053aa.nq.gz
    ├── 618eb88894b60fcdd59c5cf3ba92485ddc3067e3.nq.gz
    ├── 6249a9bd688205f9ec84e926409609b4bd039d81.nq.gz
    ├── 627897ecd58406127771fa0098642db7f038b66f.nq.gz
    ├── 62974078e67dd10a7c51bf08c5781b24d367e895.nq.gz
    ├── 63c342baff8e4903aa8b98c34b8088d16de3a628.nq.gz
    ├── 6443901bbf8cbf01351fbde25ef6224a9b5fbd38.nq.gz
    ├── 65949c814e5974d954f0ab986029da57c6c863bb.nq.gz
    ├── 677ab8f2db557ce29b01d87fe88696d5e91d3135.nq.gz
    ├── 6840e32733d6315b7c805e6932ffcb1ff8900dc6.nq.gz
    ├── 688ddbb0b51db89fd2d9699b3b2914f26582a711.nq.gz
    ├── 68a7f5a35ab904aef174d68fee65bace6ec41919.nq.gz
    ├── 693e086f1d433471d980f31e303597a664e4c7e7.nq.gz
    ├── 69717f4ece01a93cf1d48c888a1c060cf61c9f1d.nq.gz
    ├── 69a709ddfa2e96f919259dcd5abbd8e6f49c5c55.nq.gz
    ├── 69c5659be830db58308d2cd03c0bcbc80a7ce230.nq.gz
    ├── 69e82161c4dc24b5b011b1361305af634cbf7544.nq.gz
    ├── 6a67e283691b63a8096b3834634243ab6ea4c00d.nq.gz
    ├── 6abbe61f719030a4c49755ef8be448ad63e738c4.nq.gz
    ├── 6aefb42ea2f9f3794111f6fd7becba8a86f37912.nq.gz
    ├── 6be6b5331dbcb401b6864302379246cefa8db44f.nq.gz
    ├── 6c205e1dfc23a435a9c217971f4c4eb48d3aae49.nq.gz
    ├── 6d8d32b2c2b7bd46441772217003a75542f630f4.nq.gz
    ├── 6e245bdc5f83660911b1a0a10c28a0a22502a3ab.nq.gz
    ├── 6ec8537e27ef1e91f42b707fff8d003e0893c8b0.nq.gz
    ├── 6f005104729570ff5bf8a6b10aee5c45fccef47e.nq.gz
    ├── 70bbd3cca0b0d40b696e8a71831009f15fe513bd.nq.gz
    ├── 715204c6afd9c78b334be1dda5fe092ff4e6c2ba.nq.gz
    ├── 71e75ab02a770dca5e123ad26453eeff3ff8d7f9.nq.gz
    ├── 743982f099ebedc367243bf6ab96942d96254a2e.nq.gz
    ├── 752f79464d1d8168161345440126a4a113734e18.nq.gz
    ├── 7619fa5e12d04345cd957aa6d45cfb6b90376392.nq.gz
    ├── 76a9b596ef67f76dbc6397be0e6e30d1ca28ecec.nq.gz
    ├── 76c06b57bac57ae0d7eb51f4d4dae1bb2cc87662.nq.gz
    ├── 76d6e179180301d59f5a6c31555dc6a4447daa6f.nq.gz
    ├── 76f7479becb07d373a67fb4e74e7a7f0f18e9827.nq.gz
    ├── 77aee489d9a734f1a20ab136aa1722c55b82eacc.nq.gz
    ├── 7814a4f48f9940b15ef60e3ca8a55ac2cedc6892.nq.gz
    ├── 783e745d87877c5098c3c8e244bc6b2637e2eae0.nq.gz
    ├── 78f4314242388ac58403b5e9e806928c45301f76.nq.gz
    ├── 7944d5b2521bbffe956005c6e32230b9c5b4dc6f.nq.gz
    ├── 7b5356b415988924573d107a003e3cf725793b39.nq.gz
    ├── 7b587b23c1e2cc84e50a938e426318981e6f414a.nq.gz
    ├── 7e72ee47860c06ebc18a3b00dd0e8119906c0dc5.nq.gz
    ├── 7ef54cf09c6592795fc805c61b66823a5d74d4c6.nq.gz
    ├── 7fd8a28d7287a028bf063e6d46fb782133eea036.nq.gz
    ├── 8066c4115b859ae0c638bffd5c494944a3c9aa06.nq.gz
    ├── 814b56ff384e7ef0ad4fd2b851aa34de77ad20af.nq.gz
    ├── 81deee5ff2d4c784e439da434996226ee0fc82d8.nq.gz
    ├── 824c33b9788909a0a8d6239985f5def823bb3ac4.nq.gz
    ├── 82c14648d2fd3fab08d52c1a45277d5b61e7f227.nq.gz
    ├── 82d722dcc0bc1e9a28de2945c3e868d9c26c90cc.nq.gz
    ├── 846a2e1a088fba9b80280fa8ad29615af6249ffe.nq.gz
    ├── 848dbdd5fbc4ba4759d31acb2e720453fe3918ed.nq.gz
    ├── 8551f85697ec15fbcaf4cdd63b9b9df71d2c16e2.nq.gz
    ├── 85a6b809858481126f5d0f7dd990b0a856a5de6a.nq.gz
    ├── 87c4d8e316bf0f5d647ee413b5d95652e416e7cf.nq.gz
    ├── 87d44e2f8ce12ea5bbc578a1f956e4fd4e163ff4.nq.gz
    ├── 88e7ea42e24dbf954c45bc49b4938c44c267f1aa.nq.gz
    ├── 8a9fa1485b5dfba5c1320cf1291b05076aeba39d.nq.gz
    ├── 8b3801627efb98016822a8b6d1447ec1d3825336.nq.gz
    ├── 8d2237a2a24ebb21c4399e258e5a3ef5c96e28fd.nq.gz
    ├── 8d80ca31794dd2833d2c31b5f418f0ac4a10595e.nq.gz
    ├── 8fa589a43a1f5e32c375c4511ee937460b47b035.nq.gz
    ├── 8fc48059ec0ed5c02c0e9720d3478bacafe257bc.nq.gz
    └── 902e3415313252dee3b1f904286eeb3478318f0e.nq.gz

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

[ansible-collections/hetzner.hcloud](https://github.com/ansible-collections/hetzner.hcloud)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
