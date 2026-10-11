# Repolex Knowledge Graph of tiangolo/full-stack-flask-couchbase

RDF knowledge graph data for [tiangolo/full-stack-flask-couchbase](https://github.com/tiangolo/full-stack-flask-couchbase), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/full-stack-flask-couchbase
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4b74f124394cf658d4a51c277919e81dea7f999e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4b74f124394cf658d4a51c277919e81dea7f999e
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c2c2a9a1d5d0b960972324a6a3787634cfa9a9.nq.gz
│   ├── 022de0821523fd050654d2fe9126ef4b792c467e.nq.gz
│   ├── 02b5ca8dbb72214d56fe42d6d9cc540ba0a48cab.nq.gz
│   ├── 0334ba29177fec151b119ed0f574c1a3f355170b.nq.gz
│   ├── 038e8386737e16a2d3de02bd58fff0c36d368daa.nq.gz
│   ├── 03c0c5d5ec302ed7b0ee2c401df9427fb9d3c117.nq.gz
│   ├── 0477d145894dd87a24f343ca71bc4634147790f4.nq.gz
│   ├── 06088b011eccebb820b6e8de0cd244aa443208ba.nq.gz
│   ├── 0adfb9ab1bb0dc376c0774b8ed8834b061091ed8.nq.gz
│   ├── 0b3042d4de284934e364b5af44287dd87a047d06.nq.gz
│   ├── 0b8a935d15d83456ef771b1e6dbe53a65cf2cc4c.nq.gz
│   ├── 0e3c044bc95b47984c37db3f1fe911fb92c0ea47.nq.gz
│   ├── 1065fdc57acefef9239509ae930cc8f406038d37.nq.gz
│   ├── 10899715257a5be66255749341be437b9a8f2a56.nq.gz
│   ├── 122b5af43d9bf88d275938533027cfb3f648e896.nq.gz
│   ├── 12a9a6ed4e1b2dd5838edc31f8fa7b3010e5dd0b.nq.gz
│   ├── 12c6619ecc5761e3389d638b56d0d27b375087b6.nq.gz
│   ├── 1302ae2892eabeb59c7670f545a696983ae1d6e8.nq.gz
│   ├── 140713412fd78328d7049fbaf62a75e97909a73c.nq.gz
│   ├── 141ee407beffa6f984149e5e2810f92270b08ee9.nq.gz
│   ├── 1427cf62752646ad7217df0a61aa01fdef7475d1.nq.gz
│   ├── 16c033b07834d38d216bee271e47c1b8b57db9bf.nq.gz
│   ├── 16d3c4dbbfec555a7690fe6a0f9f812de215fab2.nq.gz
│   ├── 172f08e6f81eead5d52150d22d2796953ac592e8.nq.gz
│   ├── 185e6631928dca2f51224e61a3861cc88fa2b74e.nq.gz
│   ├── 1cf217443637341df5f328b4f7c88fbd38311d4a.nq.gz
│   ├── 20fba6421e8f6fc452a400139973f59b9dc6b653.nq.gz
│   ├── 27c0e1b98ee35308fae0c31217339a6c5cfb33e2.nq.gz
│   ├── 281076d5ba92d9f7426fda84b07be3742fdc26eb.nq.gz
│   ├── 2a0fec738b656a372e3261f06108c6a4e3c95f3a.nq.gz
│   ├── 2b37e401c3d6d00ca253ca75a0b602ebe886e6ea.nq.gz
│   ├── 2b6137cbb2188886801a98485e3ef1e5bf45aed7.nq.gz
│   ├── 2ea65d214bacf71e4954e8862cd7d0dc4f7cbbbb.nq.gz
│   ├── 31f2ebcf8b52c20972a40f3088c8fbb89f22cad3.nq.gz
│   ├── 3270e0879934a9738be22ffcfbec4c9a8990432e.nq.gz
│   ├── 34f0efd6d4e3e12f857ed940e793dbe614568253.nq.gz
│   ├── 3553c0526c6601ecefbd172f72f0eadfdc0c04b1.nq.gz
│   ├── 37afe3e286638480cb92562f62816c9eea8647df.nq.gz
│   ├── 3877ed83ce6d72f179cb58e359f77a7e97867719.nq.gz
│   ├── 3a3990f11c0e19346d47b820c42dda11d9ea376a.nq.gz
│   ├── 3a792b76cb8a0ce26419d898b2e62f669f4cb6ba.nq.gz
│   ├── 3aafe760fe0e449cd5d6376fce302bfca4015c21.nq.gz
│   ├── 3b37a43ae2fdef53050291d95da2e49f78cf398e.nq.gz
│   ├── 3b88b58292fa668f5f84089a7960dc9a826d96ff.nq.gz
│   ├── 3c3629e647f5ddf82548912e337bea9826b434af.nq.gz
│   ├── 3d7863466219ddd3ac9bffdec3df51d4558a65b9.nq.gz
│   ├── 3db8243bbe266249c358bb7776d6af2c86f8dc15.nq.gz
│   ├── 3e24f9e1f91ef0462ff1814ca53accfbbbc71b5b.nq.gz
│   ├── 3ef1a7f0cdcee342e9178267eb9c43a0d97782ff.nq.gz
│   ├── 404e192a95ccccbede087203c42b1f25f6bc6e67.nq.gz
│   ├── 4238c416e5eb4e965473984e435c6e81675ae8d9.nq.gz
│   ├── 42af00963d81b8e39a30435c60ac482d1f8756e0.nq.gz
│   ├── 43d6459d986c9afdb5b5e797d596b4862f48e856.nq.gz
│   ├── 46ca04dee251a4fa85a2891a145fbe20cc619d96.nq.gz
│   ├── 481b24fb32790ea8aa7e58781111e7062cd56738.nq.gz
│   ├── 4a77be863c842d5c5643172547131f494ab4f4b5.nq.gz
│   ├── 4aab557d58640533a0b04cd57d569f7c7ef9e0b4.nq.gz
│   ├── 4dab6554835996dcfb35973ee45f5a2552f573c3.nq.gz
│   ├── 4daeb365fc26a247f5153a6683af84207e06be39.nq.gz
│   ├── 4e1816f340101198174ee18ccf4040a6ac143c71.nq.gz
│   ├── 4f45ea285b7c5c7a29fcbaceb5e32328c8464043.nq.gz
│   ├── 5486b2ed0481ba311c8d353be621c37911c606de.nq.gz
│   ├── 55c9a402b3f2eefe75ad730f2759e53f43e0cbae.nq.gz
│   ├── 562d5e12efe771212a58647f899a7324ddd8904f.nq.gz
│   ├── 56ba1a0c2f5448026e5bb4089065dacf4cfdc8b9.nq.gz
│   ├── 5b9baa4594690423506f89cb35d9038045a57caa.nq.gz
│   ├── 5c4db163522b5e6477b31be682993a32f7ce88dc.nq.gz
│   ├── 5fdcdd2c7f7ac6876008490a411e5fe99eeed9e3.nq.gz
│   ├── 60e84fbb39f97a46e061ac32a84bdbb18e056563.nq.gz
│   ├── 67de6bdc10ecc52e1d931ebb7edf4ce36833c990.nq.gz
│   ├── 684ec55723738971eeb45fdfcc793a60d02c62a2.nq.gz
│   ├── 688e11a1f4bf9a1a392079713e48c711b3ea06cf.nq.gz
│   ├── 69f7c6c09a66f165a23f68efcd2e59add98155e7.nq.gz
│   ├── 6a5b0301c85ad5750e2dc45af5bb3f270f8d306c.nq.gz
│   ├── 6ff7fb18409c36c3e311091755dc697c38732967.nq.gz
│   ├── 70cde319d0268753d6e8742afd9d48103e3a75d4.nq.gz
│   ├── 7174066f44f7e608f5dfbad27c0eee5e4d7f3418.nq.gz
│   ├── 732afd8eb0aa8d33d077e92bb148901b454b40a1.nq.gz
│   ├── 75783cea94b2e71c80a1dbd06547464e057fd57f.nq.gz
│   ├── 7808237a18d4009501f950044f8388d13c5e1044.nq.gz
│   ├── 780ed884d3f0df8c5951068bdcae9f30293bb429.nq.gz
│   ├── 785b5cf95bf98bc8d0b24c1cbf983165b7f24e16.nq.gz
│   ├── 7ba2be42a98bf82aed00449a47f4c1fc2ff2d1a9.nq.gz
│   ├── 7c55d2cd3411467f2624c3805b83d73a07ca1340.nq.gz
│   ├── 7daba1e5d809c65f919d07dba20ac5effbbfe9c9.nq.gz
│   ├── 81308e2735a472496aea2452f87f9137a73d1623.nq.gz
│   ├── 841f895daf48026d6d6af39d6ac4890da4c5d102.nq.gz
│   ├── 84ea52b1d1df6a3e6b0ed464754d041bb3109ad4.nq.gz
│   ├── 84f9cce12e2766ab48c10f4c3cad6ba7dc9532a8.nq.gz
│   ├── 853036c78297da3a614b2cab2ad953e671a90f74.nq.gz
│   ├── 87db7a9f1dc7419272411555c38cfe6f9b833ca5.nq.gz
│   ├── 88cfbc31d8fed8b815abfd77513c52ecc302eaa0.nq.gz
│   ├── 8902e949e94f7c55337d895ec6e0f375a1d6b961.nq.gz
│   ├── 8ce10b9116018d65f1ea05624e9d58189a583130.nq.gz
│   ├── 8f6f4102637123d7e5696be9ff5776d810334a90.nq.gz
│   ├── 8fdfce3a4a1a5c35910bedf8df9d077c2e72aed7.nq.gz
│   ├── 904921f3e9e5f49deace01ed842ee4b6ec7b3c8a.nq.gz
│   ├── 932df2811f77340e8223335ec99b3f43cc9a4dbe.nq.gz
│   ├── 93b3ab9ed73311ef3b416e79fdafe7cf1e62344b.nq.gz
│   ├── 94ae472fb072143884650810eda6a5bf91d73cf3.nq.gz
│   ├── 95553769fc0e82f5c2021cdc5e873808eb2dc02d.nq.gz
│   ├── 9665c7f66e8123129f8bd474151e57b0d4a10d8a.nq.gz
│   ├── 97d395fc6510487d36a534f1aa0957843d558a77.nq.gz
│   ├── 98f27bf40515aba376958aca23358f1e5f997603.nq.gz
│   ├── 9c4238f2f7d53cc48ffa51dd40fb45c3ff2d23ca.nq.gz
│   ├── 9ef4cfebc68218ea03b3d4f703225ce83dac2c71.nq.gz
│   ├── 9f8009fc3aa1a66e83b00be65ccca86f84e9f965.nq.gz
│   ├── a1303d90c09fc201a5aae6bf58b0e9818293af4e.nq.gz
│   ├── a142a042a899f21dabdac2b3b00131f1a6014484.nq.gz
│   ├── a76f3c22078507872cc95d18266fe7e1409ffb54.nq.gz
│   ├── a844b1eab89110944469b21fe6aa64e4157f47a0.nq.gz
│   ├── aab7bc9443e4cf53799e9e77db6d85202811a42e.nq.gz
│   ├── ad7fa15631b854875b784a6615c4af2db2ef0ef4.nq.gz
│   ├── adaf3306e2c157885b00263fab6190414d22d881.nq.gz
│   ├── ade11b6a2e59c1d492a2dafb5c8f8017f88d0dde.nq.gz
│   ├── b02aa64d97167ad649e496908b35f14c603d9249.nq.gz
│   ├── b02f66ce1e0377b437c336be7e7da74f72886e99.nq.gz
│   ├── b3387e69bce35cde805e7b2bd2725632867aa7f0.nq.gz
│   ├── b40eed7bea09101fb8d27ca1d3d417aeeef34a0c.nq.gz
│   ├── b6748108251e916b262aa324734d9f4687e3b9e0.nq.gz
│   ├── b6fc7457814faf18853761d32bff892e2c8c7b77.nq.gz
│   ├── b9347cb9e57b24ab8b6504e5cc211c2f2a74cac4.nq.gz
│   ├── baccd71242544f17900c2a529607b79424bcdce8.nq.gz
│   ├── bc0ad3fe56a54b78e29b4213cd80f2684a3275cb.nq.gz
│   ├── bd28f40b9b3616b21552c251a68b4a1eeb588a1c.nq.gz
│   ├── bd677cdb111fcdeee7aa7ca7da3cec9ac5bc2be3.nq.gz
│   ├── be24b63ae9c24745bc2508b0b89c82184326af2a.nq.gz
│   ├── bf2a32ed22a20252e8c9a705cde2cf1e4d022730.nq.gz
│   ├── c2508ec512522752d221b1b5bd76b42976d7d5dd.nq.gz
│   ├── c2775d12badacc4a205dd86ded439cdb93b08540.nq.gz
│   ├── c500769e3df9d6a6f1977ace8be4e63a8095e36a.nq.gz
│   ├── c7b9a43c8cd16d0b434adaf513fcacb340809a11.nq.gz
│   ├── c7e170f85b4c057d9674d0571d226bbb5d1945f6.nq.gz
│   ├── c8c5e855137ae511c52870c7107b58709720a2d0.nq.gz
│   ├── c9b24a6333046d83f15762bd7d7ef5f2c1513f94.nq.gz
│   ├── cd730c1b80ed1a474f7b2e60937b7d35fe59c6e2.nq.gz
│   ├── cefdc537bb049e0608e4c31857d4086ea0ef4ed4.nq.gz
│   ├── cf10a5602e653bb126332934e2b7f34081c19a01.nq.gz
│   ├── cfb5d3cf3b1f3a3852f1d1ae5bf65579432488c5.nq.gz
│   ├── d117463ab91fe1962269872f093b7ecf851d5f82.nq.gz
│   ├── d2f872e7755c5e74ae0baa2b2f56bd556ac15f9a.nq.gz
│   ├── d3db583898e6fd7278d6d1d1156e3fa8fa249c38.nq.gz
│   ├── d41cbb815d425cdd0fdc8e81fc592be615fe1cd9.nq.gz
│   ├── d4d17f980e2f18c42612fc6e0107ac12c390794a.nq.gz
│   ├── d51f27d3c4829fa0b154d434cb4ed7b693cfd02d.nq.gz
│   ├── d932c62207af779953deb619503ad818ef16dcae.nq.gz
│   ├── d95d6bc90b049e843971a011d3fc7574483d5578.nq.gz
│   ├── da5f7528c73d3d2112f1917ca77d9e8f8d5c88a7.nq.gz
│   ├── dac6d0b13ab2c215dcd1d8e5ba006a2bae5aefd8.nq.gz
│   ├── dd29d439a07b107e5b8ec0340e1c1bc7a9fc926a.nq.gz
│   ├── df7b6566f4bbc9cf49f150f3c01d819e47210e12.nq.gz
│   ├── e121336c29f2c9aba9fe1b9861fdf6663dcd5685.nq.gz
│   ├── e297177b0daeb5a0e7a8e045b60674320b8d3906.nq.gz
│   ├── e2a866628689d7d806f6ca107fbc64f703a1287d.nq.gz
│   ├── e380ecc70f30a74161e9c93d112ccd75533dfe19.nq.gz
│   ├── e46b8435f484cddd19252b74bc60bfc1e88fca5f.nq.gz
│   ├── e57665f89fbdfb78c420b876650aa0463a5b2a73.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb0536286f3081c6c0646817037faf5446e3547d.nq.gz
│   ├── eb480309f772117df1638f466445e936a3cf2726.nq.gz
│   ├── eb541598d95e1ee578dd4699e9db13f9070413ac.nq.gz
│   ├── ec61494ffeb033fc8d238358666686bdc0ca43b6.nq.gz
│   ├── ecec111cd8dc4cb523efc833f0d2a19615b7a941.nq.gz
│   ├── ed8ebf583f771da9150c35db3955987b7d757904.nq.gz
│   ├── ed986a6fda9fd2849c6e52fa8ad804301e46921e.nq.gz
│   ├── ee245538391ed3faa506d56f2aaac5a81319cbd0.nq.gz
│   ├── f1bb0b8910f0e0202e424ac100cf88645c73c807.nq.gz
│   ├── f24d454a2ecb8851bb893192b64ee09386d30e24.nq.gz
│   ├── f36223312ca6e32c524f41e0e51f82fc330bf4e4.nq.gz
│   ├── f3d2503fc2a44b5053b0837ebea6e87a2d339a43.nq.gz
│   ├── f514897abfb8f6bcfd8a4dba939f455906c15762.nq.gz
│   ├── f661535f9d5e15744567adb97b97ebe36a1b5cb1.nq.gz
│   ├── f6ae21da8d471a536708773d4f06d44e785252cf.nq.gz
│   ├── f769d6dc37866ce5be96511dcd5069a78440b20c.nq.gz
│   ├── f8d45fa4a04e133b7e01d95761a34650f32012d9.nq.gz
│   ├── f959b902b9bd5d981a96968723cc6f834d6bca37.nq.gz
│   ├── f95ea915f65ff07156aadeb08cb62e2c7207a43b.nq.gz
│   ├── faccf6146e29bbca08b1a4c8e1e997bdc3e83afe.nq.gz
│   ├── fb25c36faf1e255bd61c812ec538267d0be32651.nq.gz
│   ├── fb29a1ca7755174fb41e267f857110700ac7c1e5.nq.gz
│   ├── fc4ac8fc5115194c9ccce8a81a4377802799b3f4.nq.gz
│   ├── fdb02ac41109ffa6d0fc6a4fe0bd69483aac6b60.nq.gz
│   └── ff5000eb30ee65060f662c56d515403c2b348eca.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4b74f124394cf658d4a51c277919e81dea7f999e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 191 files
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

[tiangolo/full-stack-flask-couchbase](https://github.com/tiangolo/full-stack-flask-couchbase)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
