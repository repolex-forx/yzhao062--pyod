# Repolex Knowledge Graph of yzhao062/pyod

RDF knowledge graph data for [yzhao062/pyod](https://github.com/yzhao062/pyod), parsed by [repolex](https://repolex.ai).

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
rlex download yzhao062/pyod
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0d0967d162ed46150cfa39ca61ffd1e7f78404b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0d0967d162ed46150cfa39ca61ffd1e7f78404b
│           └── chunk-001.nq.gz
└── blob
    ├── 0110df067e09c31e2274c6228ea6418a35613f6b.nq.gz
    ├── 013e6810995ddc2938328854fd55bb3b0c72f225.nq.gz
    ├── 01b803234751f2f240fdf2f4ee4999e4965dfad0.nq.gz
    ├── 0251509c05096a44a04b864de38978222aa1a72e.nq.gz
    ├── 0267d4e0b30bd1a8d69b8c0962b732df8021b01f.nq.gz
    ├── 0292656b234ad0d37863a99e9ac9a201391479c5.nq.gz
    ├── 02974787f04c6861049a9e4d52b9a665411547dd.nq.gz
    ├── 02b550a6c89e9ec32d48af0c52aeb298723b8e93.nq.gz
    ├── 034e7c133879237a7c8e16b57783e6e7e792542e.nq.gz
    ├── 0373ffb29d51cb76a8cf6467a3ca2860728f12c3.nq.gz
    ├── 03b32237e2debcc86f03e9fc5a72accdcbffa9cd.nq.gz
    ├── 042835a1954b9ed6b8468cd9ab4237cfb299d6e9.nq.gz
    ├── 0527d388c12ca8d93642dedc441fd4d12004e615.nq.gz
    ├── 054ab34976de5df63a1282c693733413a27ce885.nq.gz
    ├── 05da3fedfa87c4c4af0dd152d3e6b3f75d825777.nq.gz
    ├── 05eefb19b91ff8015cbb8ead844d2550b923f79a.nq.gz
    ├── 05fde6b07ee1378f778e41b5ed27f02995ea759b.nq.gz
    ├── 0612fafc6eae0c3184e0acfa90234154ef4efe74.nq.gz
    ├── 066ba097166152d96350d109c65bd910cdd275d0.nq.gz
    ├── 06a614ada1fcd025fe4aed0a7a7e29afc8138e4a.nq.gz
    ├── 07f62e6e9c925a7311b4683a40ee6fe01f9e3c9a.nq.gz
    ├── 08b41266487cac12a3237388b0ffbac2fc36ce7d.nq.gz
    ├── 0ae8641101c334a30bb378294dc939f4b6794f56.nq.gz
    ├── 0ba1b308c4e2bcbcb5113238913a12697ae20b86.nq.gz
    ├── 0ce6a86daefb40a414d88b74c7c4f0e96d99cb85.nq.gz
    ├── 0cfb2b845b0dd9733222b464bb9e674556098a89.nq.gz
    ├── 0cfc2a52930f4c6e6b66900126f52f4729e3c5dc.nq.gz
    ├── 0ecb32b8460bf69f8dd5218fc496f80cf157b998.nq.gz
    ├── 0f56dc41f2d146e7de143d26f41aa02c8b275e19.nq.gz
    ├── 114b2cba9237ac7752e5cf973ad6e5dcbcad30a9.nq.gz
    ├── 11c018a8b7778c7f7da97c884d25d3162aae2673.nq.gz
    ├── 11c111138f13064e3fdf225424c33a7c056850b7.nq.gz
    ├── 1331e41201a6db7417595fa0124487fe8ab10b12.nq.gz
    ├── 13ee112e42449429d9ebe3309932b758f15a3a58.nq.gz
    ├── 14be9f8660a8f9a2ac0f6d1ebcb9825e555642f1.nq.gz
    ├── 159288d977adc0ad8f56429c3dfdbd31e019fc62.nq.gz
    ├── 15e626e9228f82a7965f0677f4bff5e2cf4421dc.nq.gz
    ├── 162db952972dbdafa3229facc43b8f6bbfcbf6e6.nq.gz
    ├── 16b803b7a6ff9dba16e796c1276e8577152b8391.nq.gz
    ├── 184a8ba3fde6a0c0fe02162fd552b31025793a48.nq.gz
    ├── 1901427929abe6b45c006a394009b04f234483d8.nq.gz
    ├── 19e4eac355b61745f5d4ff90bdd2082eaaa1da88.nq.gz
    ├── 1a0933e7a799ed18eb2462268980cd8f2e02d6df.nq.gz
    ├── 1a73c250ceb2991f423de9445ae9ea50634f7013.nq.gz
    ├── 1b497aed260f7e26cc3f15a5ee45dda87503193e.nq.gz
    ├── 1b859aa103b7ad35595b7b078909519b76cdfb25.nq.gz
    ├── 1b971fdaf59250f075a30954f06523cc89b8705b.nq.gz
    ├── 1bc3a8000ecf89b3c83702a4a8dda34a249609b7.nq.gz
    ├── 1c8c7715a5d0563d1857b6157a65f330009e5dc0.nq.gz
    ├── 1d4a4ef9d0158cb402e6f541e31fbcf30012bff8.nq.gz
    ├── 1d96f814f1745a123691c6266f08fd04380a3b53.nq.gz
    ├── 1db744770efcaa5f575c8787bc50467f0d9fd8d7.nq.gz
    ├── 1dc3e0651bcbae0ebb3bf1c2a546e48c74524e97.nq.gz
    ├── 1f939129dec746ab847d68139ca7717fc28b9c4f.nq.gz
    ├── 1fa71bb7dca45ea9e937a7a436546a25123de3c7.nq.gz
    ├── 2047f7cfad9332dc31a5d25fe5b2caf6cb19a0be.nq.gz
    ├── 206e2b5403ed5f38de950d3cdbaf6f486473a300.nq.gz
    ├── 2229e90fb64929fd6ff18e772fe0876847f72248.nq.gz
    ├── 22548fdfa408c08ab5f6480ca53a1b4d48d3d6de.nq.gz
    ├── 22d548b0e84df99d1ceb1a79b8b23b7380e43315.nq.gz
    ├── 22f4b094f91604a9da5b3a566ee6b2a0f2f76108.nq.gz
    ├── 2394dd79e23bc11cec463b21eca0aa31cda5771c.nq.gz
    ├── 241736b185861105831521dc8bca24b548d0b801.nq.gz
    ├── 24a7c6aa730c5b1cb029000cae59844e2d692e59.nq.gz
    ├── 25509662d0a868c88e5cc2dcb19e5b2c3751e96d.nq.gz
    ├── 25f909b0fdaed2e378663e4dd7bae0918e12233e.nq.gz
    ├── 2616482831b9f8df6ccb1a360bb3932b407f4c25.nq.gz
    ├── 267a25697a843c536f7285789e438fe6bbfa06a4.nq.gz
    ├── 2690c4c54b6395ffaef0de6bdfc02a2d76ceac5c.nq.gz
    ├── 26cf262e63edff18d750b4b183ff06a390600264.nq.gz
    ├── 27ac22c0d33b56151c6eed475475f4bfb3e12091.nq.gz
    ├── 27e4bb221baad5d3771ddb9bbd1bbc20d698c4d6.nq.gz
    ├── 283546e1be77474d2de1aa6b459f2f4b561cba37.nq.gz
    ├── 28f7a4b159a310f9b6c2f2985d785610723784be.nq.gz
    ├── 2976e2e2e3d7da45baad5b09d8bf194b86879171.nq.gz
    ├── 297c0674edac157fa310cff071c67061505b62a4.nq.gz
    ├── 29801bbdcd5ca6f6b5754fd81a210a7c3b3ac9b6.nq.gz
    ├── 2ac242ba41884474f1c4711e20af208885e4b437.nq.gz
    ├── 2af62ba9637d1e809dc918dc81e2cb1fc503bee2.nq.gz
    ├── 2b7f22f88c348d5d566308eff89af912806cb264.nq.gz
    ├── 2c0a0deeda177b3aeca5d660d8bb901b4bc43b90.nq.gz
    ├── 2c8f67c729e49e0592e2410a4bf30c4014dd3347.nq.gz
    ├── 2c9bc9770e43abf4d0bb00c452697e1d969db892.nq.gz
    ├── 2d412c8c6c9df1fa8de0fb9986314d01d90e6e3a.nq.gz
    ├── 2e91d4b38d6ae8128f058e1211e5c316433cf2b2.nq.gz
    ├── 2eee6a41a8734082bc8e5c74c17c3ae71103b942.nq.gz
    ├── 2f4db47e2d9d05ca58913e3c4c4a835be865a8ec.nq.gz
    ├── 2f96f85f95e9195dbc1e090ad6c3aa84b12e8ecf.nq.gz
    ├── 2ff3c3357fba1b60e790604ac64c257f0eeb10f1.nq.gz
    ├── 308a5eaa6e8e38f0a76712a6fcc8d40ad42eb58f.nq.gz
    ├── 309cce23baa4507b685a7e6d484400e41af97592.nq.gz
    ├── 3150b95e71d8177300aabbd8655205647ce562e8.nq.gz
    ├── 32a93b1d84d098f395224b53faae01f04f414d53.nq.gz
    ├── 3330611a61900795a3181e4f1d11d0bf5799c9c6.nq.gz
    ├── 344e27043a1bb6401654d74dec92cc2cf10f6605.nq.gz
    ├── 346022b4835fe41926a697c03cf3693a03f716b1.nq.gz
    ├── 36f64356520fecaa913fde5596955d78890c8a07.nq.gz
    ├── 38d74f809127b59870bbc9d82044cc44c7ac3b38.nq.gz
    ├── 395263da2354565d57ea4a4185060969f63bb415.nq.gz
    ├── 3a135a98e69ee9a2fdcce17abe34ab4abf427a6b.nq.gz
    ├── 3bf6501f28a4a0487b484f1b17da10b46312f7eb.nq.gz
    ├── 3d97480e8ce5a973a8eb5818612a1fb34494506f.nq.gz
    ├── 3da7ff1adf76d8a78255391d9e406015cdf87051.nq.gz
    ├── 3e24d6b80428e62f1158bf068294669db39e8dd6.nq.gz
    ├── 3e7fcbe25e3d16cb6d8648578b7bd757a20f1738.nq.gz
    ├── 3f5b0d66d340daf337cc96f9c577f40436cd22cb.nq.gz
    ├── 3fb5d01b2675eac20131fcd9bc3720eb4801c632.nq.gz
    ├── 3ffeabaebf7b8687fa850fcd84e35546c2e69a4e.nq.gz
    ├── 4007795d93da97f614323d203053588b7d921e61.nq.gz
    ├── 402d5b736add48dbfbf62f5c33810f8cf0ba5aca.nq.gz
    ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
    ├── 418540baa4d315504258c0b8de6933c357684089.nq.gz
    ├── 427085dd8320d07bbc30cf3b5dfbaa13739db12f.nq.gz
    ├── 432ed6533b74ec223d1a79115d82b836801e5141.nq.gz
    ├── 43dbd82ce97bb09b3318e5394ffb0c899200414b.nq.gz
    ├── 4507742c08054c2fae98bf2c1104733acfb79459.nq.gz
    ├── 451ebe733e6ff916ee7bad4408886a4b9f64cd39.nq.gz
    ├── 45f32d60f0fdb10570e19dfbffc32186878ddbc6.nq.gz
    ├── 45f63b4d338c8b262d92eb545e1dae82e8cc8916.nq.gz
    ├── 46161ce05c75e74742082d3189cf4c41035cd888.nq.gz
    ├── 462da94c5fd0a097e8a7983dda6afd09bfc4e291.nq.gz
    ├── 48b04a039a558b0420ef2e3c775249bb468c6e40.nq.gz
    ├── 4af9049d23fcbd264f39edb5ecab646805163b5b.nq.gz
    ├── 4b5059b5cdb23576444a2c5348fa072f1604228b.nq.gz
    ├── 4bb2e2af3a659e5ad9e7d043c391bad517f8c4bc.nq.gz
    ├── 4bd04d06c82316bd23951280db23e64178478b6e.nq.gz
    ├── 4c4d7b8d6fc186d3417e66cc4f3ef6df3a94db5e.nq.gz
    ├── 4d7be4966b916370069b0b9d4263aa7977f31dca.nq.gz
    ├── 4d9016e98ca0a36e366125102a0102718cc772cf.nq.gz
    ├── 4dbc3bdcfe6dee3cca1f5e7cc5ee7479034c28e9.nq.gz
    ├── 4e333af25bae2cd0892a6e33aa158ae790d61866.nq.gz
    ├── 51a4b164074ba3d8955d815cfeb38183a27bad3b.nq.gz
    ├── 51ff68a0098caf61fcc29498f1925208f3d0827f.nq.gz
    ├── 52948fff31132ed34c447f9e1a0758bd12a5fb7a.nq.gz
    ├── 52bdaa30e3215bd52fb3fc48744418a89f2ae99d.nq.gz
    ├── 530c011f65c741bca79f6f9d1d39cf93ffa38539.nq.gz
    ├── 535aca188d37e928a6e7a73323aaa88593ac68b2.nq.gz
    ├── 53cd8ae9722afb673c9169bc6146429a55fe2ce2.nq.gz
    ├── 5490deb939f8ec00f515daad5bb8caa802315476.nq.gz
    ├── 54d2213bde357c24b3a38f19f17bcea84f9ce8ae.nq.gz
    ├── 55183a25a2aa1f5693d6e6570c9e93dbf7a2f27a.nq.gz
    ├── 55fffa9cefff196c14c0b2ea82ac2a01117af08e.nq.gz
    ├── 56239fa1017fcca129a10e0f4e1d5fca27228673.nq.gz
    ├── 5749c4d757100c0e1f5cfe054847f483aa9a60f7.nq.gz
    ├── 5791a528442a66f4bc490447a948e138063cb9b3.nq.gz
    ├── 57b8927754de6008bcbb79d2559dd3a6a62a621f.nq.gz
    ├── 5805881799170a76e327cc13074c432a5d1e5ad1.nq.gz
    ├── 582a51ec8396a9df43c16af198565e10cb945d31.nq.gz
    ├── 583574137ba773fabc2dfe888b38fb927a7ec37d.nq.gz
    ├── 5a97e3ef4ce39b837db4d4db5129d41255afe60f.nq.gz
    ├── 5ae35b084493b151143c4710d0d038b73b009c3c.nq.gz
    ├── 5ae79576309c33f971f1562e67eea2542bdd0a7c.nq.gz
    ├── 5b1cc4d5a66a1567e31fede587492b13d2abf9cd.nq.gz
    ├── 5b1ce22f334dcf5e205e819402d0b7a37b72edd3.nq.gz
    ├── 5b215e193bb3cc4a6ab1b266060e61cd89b68f35.nq.gz
    ├── 5bfc9c02bf63cf2bae2f2c39df1974dbbe3bb47b.nq.gz
    ├── 5c01aec96cb6375783724bf64f9d2cabd4673c27.nq.gz
    ├── 5c4c8d19d62cf455b9a081fc25413ffff5c6127e.nq.gz
    ├── 5e02f55a4a8f442bbb54af024f3e83ef2042093b.nq.gz
    ├── 5e037e96a846b40ee11394d633f232272dfe1cd2.nq.gz
    ├── 5e96516b3532a76a6a895c5f81f22dd19a5eb303.nq.gz
    ├── 5eae23dee1b9f01ecb194dabb2934da894358349.nq.gz
    ├── 5ee1a87de28d65f88ba1c47dabf8893034db8fcc.nq.gz
    ├── 5fc1ee4b74e8121bf76ddf6aa8e79e980ab5bbc7.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 60752bd642a30177e27a6bbc5e1710b5d9e55379.nq.gz
    ├── 6090e3374e35e8c0fdd980fe81f98903a734791e.nq.gz
    ├── 609825e8eb0f53e154338b4396197283ac6ee953.nq.gz
    ├── 60d9b6d68a2acb7dc8248c3ecf6a4521353e5820.nq.gz
    ├── 60e2b3d80583072f30dc699de412f331c327ac1e.nq.gz
    ├── 61739ffea60e87e138669185c48412012e434256.nq.gz
    ├── 64fc5b760a93bb6780802ec769786346259a97ef.nq.gz
    ├── 66610456553df76d33008a3b67ae9592ba88a743.nq.gz
    ├── 666c3ec9a2ac78be480596be5f6dd417087bfc7e.nq.gz
    ├── 672a8444799f745b04f394a9754505467f04eb09.nq.gz
    ├── 68380df43643e313b36f944084ac5e4456c98938.nq.gz
    ├── 68bc7ce2257996957a46e5cb79958fdb13b32d32.nq.gz
    ├── 692134180df54ce0a1b625b491852b5b93c536ce.nq.gz
    ├── 69a5709af8373055b2cf139b5b3d748d020e59fd.nq.gz
    ├── 6a9713a6a50772c9823b7639d872fb3ef7c66fe8.nq.gz
    ├── 6aabd1410426176e3a33fccca129081bd51006ac.nq.gz
    ├── 6b780f5d6011e69d57054825804ebfe7a4880456.nq.gz
    ├── 6c11007e999f660a3447976ea0a6f802cc1c4408.nq.gz
    ├── 6c50c68c2c2ee88c477e7ed1e6f8b43f5dea251f.nq.gz
    ├── 6cb1558c6ee17dde29148be24380be651f559da6.nq.gz
    ├── 6ce66048d4c1139ba487822cb1acde69e9a4a5bb.nq.gz
    ├── 6d00e0606e913c0a086828d14c0e4d76f9e89922.nq.gz
    ├── 709ca56ec3b622c3905882608ab2f1902e142e2d.nq.gz
    ├── 70b65ea76bef40e74f5b24de4779f58784516f9a.nq.gz
    ├── 7163056cd2039f9b7da49510efc3d0955935df79.nq.gz
    ├── 716fbb7846033764ef83fe6f618e9f051e928775.nq.gz
    ├── 719f005e044dcfe5b8d577e2c12dcf9ab7dbc418.nq.gz
    ├── 735964cd4442c79bb4413f8f13da8cdd56b6029d.nq.gz
    ├── 73e4331e156a442e8419a4afc247a85285c60239.nq.gz
    ├── 74e4fd734858d0cea538836f9c8bc200ec3eb0b1.nq.gz
    ├── 75409fe3ffb030964bf7734d2b79da5953482cef.nq.gz
    ├── 7574d096e3a4a0bb7c07d97fd0e4ea15c4f068ee.nq.gz
    └── 768db7918ce5805f31a28a79b41181543d0fd480.nq.gz

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

[yzhao062/pyod](https://github.com/yzhao062/pyod)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
