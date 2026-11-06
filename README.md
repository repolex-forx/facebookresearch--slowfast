# Repolex Knowledge Graph of facebookresearch/slowfast

RDF knowledge graph data for [facebookresearch/slowfast](https://github.com/facebookresearch/slowfast), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/slowfast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 287ec0076846560f44a9327e931a5a2360240533
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 287ec0076846560f44a9327e931a5a2360240533
│           └── chunk-001.nq.gz
└── blob
    ├── 0013a1d5ea8ff7c224f2eddedbbd444235684ee3.nq.gz
    ├── 024c0ff05c49dee7fdd0ed1cd818e53fe118e031.nq.gz
    ├── 044b66c69bdf73dd5d33ab5b684c12f3e46b91a3.nq.gz
    ├── 05257f025ffdde70783d1c43f23ad1f93247d6a6.nq.gz
    ├── 0572d92af379ae9903b1cbca7559418321fc3a53.nq.gz
    ├── 05e40f9d447cffde9ba7eb1869b3030878ec8d77.nq.gz
    ├── 06a9b0bfa263d1ae0ec9035d9afb2f0af650f922.nq.gz
    ├── 07814e9d69bb3231f9e099f1f0b322ed9ca60319.nq.gz
    ├── 08ac70c0d6f2f3d23a4b9aaf930eb18f22601d5b.nq.gz
    ├── 09879627dbbb25b986127de58ca386000fa02bc1.nq.gz
    ├── 09938f39f110a312de7305e8a53e2b34fb77f583.nq.gz
    ├── 0ba7144d2ba27a84d6540107a9ec365ea1eac35e.nq.gz
    ├── 0ce804617bee0f21580f4a842c8c9afbeee84b9a.nq.gz
    ├── 0d542cdf858f7611aa4dacc8d711a9ed0256cec3.nq.gz
    ├── 0f7ad8bfc173eac554f0b6ef7c684861e8014bbe.nq.gz
    ├── 10393fcade84da398003c551941973ce4a774e45.nq.gz
    ├── 120aab3c9179a02a2ba9e268420eba4b974d45a4.nq.gz
    ├── 127c8aa4f522cf121b459910b14b3db737e99dc7.nq.gz
    ├── 12f6eaed485b4c77fa947e76cb10e9c1b581d3ba.nq.gz
    ├── 13437b2c35afe6aa6ff2769efef8e830d0621649.nq.gz
    ├── 135c7768e66de42aebdf6c415a2339489e9ca09f.nq.gz
    ├── 1387c48f9c3a3b92a8661d18d5381c6e046fbb9c.nq.gz
    ├── 176283263ec11487013535922a172fd28f911dc4.nq.gz
    ├── 185c7d64f5ec5db00c4d100a6f86c02813bd13ca.nq.gz
    ├── 191ed594efe3cfc299d824bef38ffcd32e60cd2e.nq.gz
    ├── 19e4b8d16e0441e258c03c6c020e97b21fe45087.nq.gz
    ├── 1a70c6c9c123f3b08318d93cc0c1a6d714663cb8.nq.gz
    ├── 1a77ca2dfb105ea9556f8421cf272f1882d7576b.nq.gz
    ├── 1af2c7b1a9056e399eb009d9a54a885f73967d31.nq.gz
    ├── 1bf0531bf88897d4065bbe4538778763c90f4a56.nq.gz
    ├── 1d0d2fcbd6ec6117ebe8921bac8e0a05e9056bf2.nq.gz
    ├── 1faf5f985a8dec97fcb71557949b5afbd4d18e94.nq.gz
    ├── 231b44cab0bb277e4b6c4ea142be1a2cf81184c3.nq.gz
    ├── 23bffcfed15326f1d233e0c220844dd987419547.nq.gz
    ├── 25093efad47033f78eac01156e838f578ecc4ddc.nq.gz
    ├── 25705f40637f96e668a0de207c96f70feba10327.nq.gz
    ├── 280381d27bec6ffe70b0a4c9e27db7a850dc4ef8.nq.gz
    ├── 288ee8c532f8c60fcbf51c1c09d5c7a9a2bedaec.nq.gz
    ├── 28b5b7b4b2c25fbb966be71755f87b2172049369.nq.gz
    ├── 2947d821c19265659fccc3b3c28421feffadf9bf.nq.gz
    ├── 29c80f046c40aa5b86cc5dede9159029d173f66e.nq.gz
    ├── 2abaf256fcd60983be9c63ce723a2a3bc3070eac.nq.gz
    ├── 2b5c4113679468b0d36bf71ca3bd0ef64e1a6cee.nq.gz
    ├── 2d4bb975de8f3b0e68a46bf2ab1413df7166a6b6.nq.gz
    ├── 2dba5752cee908108a8ba4aa6afbca73020d5e6e.nq.gz
    ├── 2f850019749b36b0f8a816eec9306454819aac3e.nq.gz
    ├── 2ffa39348c7b2179b3fddee21a797dd811da325f.nq.gz
    ├── 31c306cadc25e06cb8fe11d0a2c1b6d72d1bff73.nq.gz
    ├── 323f4e8e69fd23e13744f7be7a1a936137ba2595.nq.gz
    ├── 33dd5f7c5c364c3cfcc8c16bd94037679c8ff1c5.nq.gz
    ├── 34dabc4b5ab7c34572b0f7ea9ad0be0ac87947bb.nq.gz
    ├── 35b37340708a7e086ea81f43cff8e8a20f4f16c9.nq.gz
    ├── 35ecf398dba309ee46ef63990548ca7aa87bb015.nq.gz
    ├── 374b7c592e902e3dcc72c79f3d8eb1053c6d5233.nq.gz
    ├── 38f9118f26e94f866a76b852fa753de37670492e.nq.gz
    ├── 396f533c0eac624b00b6eeef2755ae20408f8621.nq.gz
    ├── 39abdfd83eb2b6c649be0004f9ea6d4c1835c7fc.nq.gz
    ├── 39dd8640bb18db822e497aac1ba35a217d39910d.nq.gz
    ├── 3f8c7eb76d008d71863b9fb23a49342bbe40ee8d.nq.gz
    ├── 3fe4626c550747a442768784e55516f23aab0354.nq.gz
    ├── 4032cf06ba9b559fb04f674046a7edc635e244ea.nq.gz
    ├── 4190400bb8d583e1307154b175439b892642cc00.nq.gz
    ├── 4333f26f13934becd07f8a36797e93d5dcfa8388.nq.gz
    ├── 449b114ecbdec6c7d023a60496265742d139bc9a.nq.gz
    ├── 44cc47ec18af66c8a5945292fc6f603b2d17a5f6.nq.gz
    ├── 45375d6eaaba3e6bb056506befe5fc94b71a038d.nq.gz
    ├── 45460b9c74dd8b082709c54b4d5d26c1ab721b62.nq.gz
    ├── 46ef50debec24d5988b4864661eb740777d24a23.nq.gz
    ├── 481e059a46b7fd8f47b75dc38efbed6dc3646932.nq.gz
    ├── 4916f45873a9bb8b783b71204e0c1b75ed26eee8.nq.gz
    ├── 49ec7c3d305a853ba1bcb6986f42a775db495888.nq.gz
    ├── 4ac8a01bd3af7d06e543272380ca91d099acf8e3.nq.gz
    ├── 4ca42b81cd9342d970fd3482af5c8a27ceb083ad.nq.gz
    ├── 4da44f7cc08e0748393f87c4485dd3f187110655.nq.gz
    ├── 4ea9341df0df0056f54b1a8074552254aff4f8ec.nq.gz
    ├── 4f74227df4e8958f85fb6bcb069e1b8b8ff37165.nq.gz
    ├── 4fffec0788c58e660c955edd000cf25fedd64475.nq.gz
    ├── 50161095aa7b980bbafa23526cd8072be9b086fa.nq.gz
    ├── 5046fc34e50c2c2893a554792c63026c42c22b22.nq.gz
    ├── 5114d754d6a003851f6f4485fc9b97add948bf84.nq.gz
    ├── 51bf33f07516c1fe9350c97bbf7fda4581db975a.nq.gz
    ├── 53418160b0dbd2c1993ee4cd6d5a34f3c0975d0a.nq.gz
    ├── 5411597d68ec975569f1088677be964791475ff3.nq.gz
    ├── 5589ed4f6a201f8601b140d3b82561b3224b70cb.nq.gz
    ├── 5a6472d09db9f31be6cfe508ba2495a43bf99c3d.nq.gz
    ├── 5a90478a33957a01c8b1c16fb4d9bf8d0687affd.nq.gz
    ├── 5ac31a3832d8e43d61e6a8658dd9833609bacfb8.nq.gz
    ├── 5c6e3a29acd7ea975d6e279a6fd08d0053659b9e.nq.gz
    ├── 5d0a330e7cfce20434d0d637858f2567924e6d11.nq.gz
    ├── 5e2c485682830919a09300ac851e6b0e4bdf3efb.nq.gz
    ├── 5e4504612758c90f7313dc619d8ae0ffc46d5c59.nq.gz
    ├── 5fd28fe41fc23b6d3e0d7ef39a67753676296281.nq.gz
    ├── 6077899d713159c05f8fad2079d82d5f8e2806ad.nq.gz
    ├── 621026dd044e12f043a83bf91243e982c175eac7.nq.gz
    ├── 63a3c681c0a152c475c73a3025f0fb3a7d4bedec.nq.gz
    ├── 64efa45df49d7a7feabb4041c25adaeeac181d42.nq.gz
    ├── 6844df3ca46a5d8717cd6d09e5b2197a11a82afa.nq.gz
    ├── 68fa2d0eda1a33217fa98c455cb797bb453a2a6a.nq.gz
    ├── 6c667860632496f102fd01c2e87622b3d9b888f6.nq.gz
    ├── 6c956886857ddda067349f14f0fc1de7c7b57a12.nq.gz
    ├── 6cb7989fe6b6d80fd8eb24c58c5b66c8480a1ae0.nq.gz
    ├── 6d35ba29f7d06f86d13b0f80cec76d99e3640392.nq.gz
    ├── 6d64185fb12f2b7cb3d8b16103e0953a7b0f2da0.nq.gz
    ├── 6dd7ac57e838408116a8b942bb5ab6355f8ed033.nq.gz
    ├── 6f0e4de458ba337de29a96f8671b7243e492efd4.nq.gz
    ├── 6f419180cec37c1e69b4e32cdbd15544e0e9a332.nq.gz
    ├── 6fb8b660bc92219853d73ed4d82e95c1cae76e86.nq.gz
    ├── 712913c8a1999f7ae333cc305f7b194fb7ee9e73.nq.gz
    ├── 713b88702a0640108472e6a71be2b6832683aa09.nq.gz
    ├── 71f37da719a7244a42a10b1a84b7406c16802f1b.nq.gz
    ├── 755790b757c6810629133ac4e05acba228ffe546.nq.gz
    ├── 76451f2ece1699622d0422e7aa78e2f83799501a.nq.gz
    ├── 77e37d7e41803b7663f36471143dd45437dded80.nq.gz
    ├── 78532e5ccc432db9d7be020dcf943de46b803884.nq.gz
    ├── 79f4f3d68354ae4124e7f22f8a31ced65ed0d3c3.nq.gz
    ├── 7cfe32c9272c4c2bc72a4d930bb18d2992cc4cb4.nq.gz
    ├── 7e8b11f0660b38b9d272e1ad1d3d609634318c62.nq.gz
    ├── 7fdfc4b936eb41e3d7cd86c42193432e194de8d8.nq.gz
    ├── 8131da2951d8cb629f664b39da4675d0ae5adee5.nq.gz
    ├── 81360fd542b4dc98ea5ba64aa911e6c3dd8e6129.nq.gz
    ├── 81b851820620beec021375d09e74dc1f34efcfab.nq.gz
    ├── 82eabf371c9076d4907bcd876885814e95f39d23.nq.gz
    ├── 8309e5dbf04de7d91bf957f47697f45ba595c3de.nq.gz
    ├── 8398e2bc8b4efd98dd087b6466f309c8d620888b.nq.gz
    ├── 839f1ff30682e7624045d0db88a7a0846b23cef3.nq.gz
    ├── 841a177edce3bfb6dc42aabcf4198c9a3c446f1a.nq.gz
    ├── 85b7006562eda489f4dccd9fc7e13a4d4f001c4d.nq.gz
    ├── 85ce8c5ad71c33da55d4b754b1415a9caf57f280.nq.gz
    ├── 85f4050e11188ac1a91635592240496fd29a0c70.nq.gz
    ├── 86d60a1234dcb51f50ab954a7bb3e12f53dd6a83.nq.gz
    ├── 86d867369e5f261ab892cb4ba619a13b36db44fa.nq.gz
    ├── 87cb1bed77fa5a3f4e1dae1ad7b301e0f177e9fd.nq.gz
    ├── 88de25564cfc2a674f06191e056dd42bb5d74be8.nq.gz
    ├── 88e0e89979044e5b91bd6334e428b78eda7ebd2e.nq.gz
    ├── 8a5da028459219c302c07dd4ea8f72ebca96d217.nq.gz
    ├── 8c5d476301a1849dca743d4fc18c2877cf56a8a1.nq.gz
    ├── 8cae0a58ef9b666c41ee6347d47ec69c9f5aaade.nq.gz
    ├── 8dbe96a785072a24a9bcc4841a1934024f2b06a1.nq.gz
    ├── 8ec682a88c8f2945c944d8b59d9b75e3ad332f1d.nq.gz
    ├── 9004adb3d99aa82068ee27ec26707a0c046d0de3.nq.gz
    ├── 924ebe86e22fb3ec0c316d06f14a713efd8986f6.nq.gz
    ├── 93939e3d00bb8ab8650130d013b317e3d827b108.nq.gz
    ├── 953dff57375f04ad5d1c2fe9de6f7a1397ce8729.nq.gz
    ├── 98faf82e75415fdef1024e9877384cf79ec65f4c.nq.gz
    ├── 99388faf848b50f1605e4aaa5eadb043386c0a7c.nq.gz
    ├── 9ac25de9b3b353e0f3e493ab75bd04a3c03cd8a5.nq.gz
    ├── 9b624926ac895255aa8d26d7c991af6fa6ebf251.nq.gz
    ├── 9e14e0a511a3df4e5dbe62709fe39fd4260225a5.nq.gz
    ├── 9efa213065a8cefdbcefd50404864355165a180c.nq.gz
    ├── a2963370756e9c3216ecf1791a0b1415b321d6c8.nq.gz
    ├── a3014a5b864e60069ffa47b616713ed4306574b2.nq.gz
    ├── a34607779906bd32c98466e1b02eef5343f98185.nq.gz
    ├── a3b5fd710a8ca29c1ee090331285629d796acb5d.nq.gz
    ├── a3e918d19214c283295c3ea921c0b4c48b9beec4.nq.gz
    ├── a49b54059bf9d1ed39bef075f091596bf2ae4fc2.nq.gz
    ├── aa356727f9d5e2ab1c53a11858adf9297aed49d8.nq.gz
    ├── af2c72805bfd4f9c5dfffb61f4b4701f9f1a7c93.nq.gz
    ├── afce4ecbfb686269eea9244b0f2f33c73edf7d82.nq.gz
    ├── b020eccd898accc5c0b37da73cd5b61a16e29f40.nq.gz
    ├── b0363d4216e1e33efd030cc680f5509800a381ae.nq.gz
    ├── b11b14a9e4372b63952af1763269b51a7bb18ea2.nq.gz
    ├── b1334cbf26dea11070429adb3ddfafbf00e233ec.nq.gz
    ├── b38f665d2c97cbb73761ceb8b55a2a51321d184e.nq.gz
    ├── b4e84189b20228f11158e72364b7f0cae07d68ec.nq.gz
    ├── b6382368cb1afc7de5bb894163e280c66110fb7f.nq.gz
    ├── b65a8f9dc0cd5092e2dc879f6bb4aba8fafbb092.nq.gz
    ├── b735fcc7444dec47c362aeb50618b3999bdd089a.nq.gz
    ├── b847651402a88f524e9b95398034b605197dd622.nq.gz
    ├── b97e5b1f8a02a5c98bccbabc62c24bbd0f0560e9.nq.gz
    ├── b99f7cb8033aaffeef45fd27d83c2fbfabc8d7e4.nq.gz
    ├── bacda1650649f2d5a0a15d626382591562d905b7.nq.gz
    ├── baead7b1f510c2434df0149b257de6959eaec83d.nq.gz
    ├── bd5229a8a3b056e1b36d8bc405bacd87ab9bb8dc.nq.gz
    ├── bdc8f08482c1915bb85c6c8831200f96ac86a9c7.nq.gz
    ├── bde7f4dc71208e591f8a6b2ce497ac7f61c34aa2.nq.gz
    ├── be906023fd1357b757483cccd484c53c0e7d03e8.nq.gz
    ├── c2a3d639ebfc38b99bc35bb9384ae228471cd4c6.nq.gz
    ├── c2b415358bba34cf78e40253b00490d9d432e4fa.nq.gz
    ├── c2fb7ed78d63662b3e593421a8eaedc1f2d0c920.nq.gz
    ├── c37125d4dc0897aaf8ec2075020a5c7d9137bc9e.nq.gz
    ├── c3df8a86a25ec00bfb1469c19e11b7971bdf962c.nq.gz
    ├── c3f741a9b64a876d278fe1d685586f3db5c0bd7a.nq.gz
    ├── c4ef12e2bd6cb6b2347210dd5dbb52b2e6dbd10d.nq.gz
    ├── c4f4f1cda794eebfbe7e1ea7e298697a7fc41bd6.nq.gz
    ├── c5726b8da1622ba632aeda20078bf7e74c173098.nq.gz
    ├── c7ec58cd8f67e73915529d37dbdaa1d3edac1d8f.nq.gz
    ├── c8f014f757d72f247e3f3f20667a3455101ece4f.nq.gz
    ├── c9a462b843cf0246c48690964624b211e403dca8.nq.gz
    ├── cb1b9e53bed5f457f659fce8528618182da6fb6f.nq.gz
    ├── cbb1585bc2cc2bff1aaae179555b5ba00f1570bd.nq.gz
    ├── ccce0f7e7a855e8e86576f4d33e304a0bd925a6c.nq.gz
    ├── cccf06d8c93b4fe4ad4fb55ef09cb34c707a9f71.nq.gz
    ├── cff417e17fd75c8b403ab427d22f1daa55d13386.nq.gz
    ├── d03b20bc5bfd71ea2c5ff73c970e444347fbc826.nq.gz
    ├── d080f457065f0a59e7c6b2ea7710e5eff3726860.nq.gz
    ├── d1045e5167e78ee14fa9647d27d7e7cbbc48393b.nq.gz
    ├── d1d1dd460827915822849a90e433ee9fcfb5406e.nq.gz
    └── d290ff1ab5b94193d17a6154e1ce9ced30277e5a.nq.gz

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

[facebookresearch/slowfast](https://github.com/facebookresearch/slowfast)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
