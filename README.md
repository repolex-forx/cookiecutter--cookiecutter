# Repolex Knowledge Graph of cookiecutter/cookiecutter

RDF knowledge graph data for [cookiecutter/cookiecutter](https://github.com/cookiecutter/cookiecutter), parsed by [repolex](https://repolex.ai).

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
rlex download cookiecutter/cookiecutter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c88fbe921c97c58b65f1883ba90a0ab53cc91b34
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c88fbe921c97c58b65f1883ba90a0ab53cc91b34
│           └── chunk-001.nq.gz
└── blob
    ├── 026cb1bb16fb01960f29fe6fe009c2bf597a0e11.nq.gz
    ├── 03148f70161185231bb83cc41fc137f37cce31b0.nq.gz
    ├── 03609179fe63efd7eda3d119b261760b76aaa9a3.nq.gz
    ├── 0400d574603b68b016931720c37336bf3d0521f7.nq.gz
    ├── 0402dbb33fa00ff0e3f8195d576f8225fef6267d.nq.gz
    ├── 05a34755cf90e193f1c92b9b52f6028698e49725.nq.gz
    ├── 05d1d33079662ee7377bb966312ad759d3bfcf97.nq.gz
    ├── 072cc299d517b4f21f48a781a80dc8d902edbe1d.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 09ded13862f84e0858984d9326ac68c5b3283cb9.nq.gz
    ├── 0abd26eb203269ac766f8f9c6cfc598c2d6d2ae3.nq.gz
    ├── 0b832ece269db09d8a359d2ab19feb7f834ab4f2.nq.gz
    ├── 0da68ba49a0d7217442a7f3bb37618704e233c06.nq.gz
    ├── 0e159067954bff2f3714723fbd5f301ff97a2056.nq.gz
    ├── 0e74081d85755b7ee21fed0d04c2fe43756cc9fd.nq.gz
    ├── 0f2f2487db0478033735effc58eff8515cde766d.nq.gz
    ├── 0fa1c98b05f8a996454f5b04e7db39b79589bd2d.nq.gz
    ├── 0fba83a3b5f3fd9ca3d9e7b779afa109acff9efa.nq.gz
    ├── 115da3236524d559fb4f21e7fc72c210305b23ad.nq.gz
    ├── 1260a8c32ff13a4e7f7afd324d309fa1de1b394f.nq.gz
    ├── 1325a70d0228d354860138d5121fa2e9b2124880.nq.gz
    ├── 1376ea2ec86206b99846d691e82ef9c94cd91a46.nq.gz
    ├── 158f434f98ddd018ef7b4328e1893b03b8ba359d.nq.gz
    ├── 15cb0ecb3e219d1701294bfdf0fe3f5cb5d208e7.nq.gz
    ├── 16e565c68848b4279b2a752c18e09edb1784df22.nq.gz
    ├── 1bfbba02cdb1a565d655cb5209b36ae49e6a4337.nq.gz
    ├── 1d1b4bb313b422ba98904cc48041171db36f1ee8.nq.gz
    ├── 1d3c95473ec5d430baecca24e776ebbfb7194e64.nq.gz
    ├── 1d3dce939d2881c9189613025a7892f5fe32b2a0.nq.gz
    ├── 1d6905dc24068ef7fb0f5087bc2ca2b7a0bde89b.nq.gz
    ├── 224d5c1fa642fdd2d9372904148ae93da22840ca.nq.gz
    ├── 2271e0789491c64baf045cf5f28979f57d971c6b.nq.gz
    ├── 23f2c8c430452dd21c4511fd971d5c6ac0daf155.nq.gz
    ├── 2413548bf709475547fe31607fb2d60c101671a9.nq.gz
    ├── 24ddd9e11fe7ae195b860e07de8f983e7c770689.nq.gz
    ├── 2535ae386aa72f9e9d24ed55875ecccda7b3741c.nq.gz
    ├── 25930f81474c329dc72f4d8a7b65cd1a48ada471.nq.gz
    ├── 27520eb6dbbc855969c4a1ba7af41997b7d3d412.nq.gz
    ├── 27b4ac2c916c94a3f520de6331d8fa11c2e5d8cc.nq.gz
    ├── 291e7b9a569f90a96c9bc6e52941b01943c9c48b.nq.gz
    ├── 299a720aa04105a25fb5bf936c7d65572041e903.nq.gz
    ├── 2b44dbf9de06cc78fd6f3b3b66fc142b25c0a724.nq.gz
    ├── 2b5fb3a27d41ce426a2868dd4fe2ff952afc9389.nq.gz
    ├── 2b6b14e9f9d60e15f28c1f3045b023ac374d0290.nq.gz
    ├── 2c022884c1016152647adabc52c0ecff8ce6464d.nq.gz
    ├── 2c757996549ac009f88e951bfac234f944187bae.nq.gz
    ├── 2cb77b2c0a08c69f13d1645b4233935f2f40684d.nq.gz
    ├── 2cdf1d2725f3b395fc9f145d9da05b3cde292fff.nq.gz
    ├── 2d662bdd94b4e61b4cd49497e559155574811544.nq.gz
    ├── 2f35817958cac36b237066cadee7d38c33c8edce.nq.gz
    ├── 2fc3522ab49d635888970f5994cb0fd2ac81ffd9.nq.gz
    ├── 3034a3a0b80707262b513e55b843101b79b15503.nq.gz
    ├── 3043a6babd5573e6ec961dd79f992ba520b72c9e.nq.gz
    ├── 30849f09c4a3b5290fc6b77b935bc2e2a11c5038.nq.gz
    ├── 30ec3132717382dc2fe402370e3b525e2ba08957.nq.gz
    ├── 3234d6e079296960c9478d789bc66fb5b81af819.nq.gz
    ├── 32837083cd9ea72299df30e0ce15db19cc7e9c56.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 330986e8c893637aa3133b67ff9f9b26bde9b207.nq.gz
    ├── 347e5d6a863418b3b081fa3bedf936234b573ee6.nq.gz
    ├── 351b6afc85ee488a788856384ba3e9922d07f88d.nq.gz
    ├── 357c9544ab99f923229b96222e3f2628599f938e.nq.gz
    ├── 35e6f25c9cc1bd9202df7d16cd102205e0fece56.nq.gz
    ├── 3a6e177a85cc118e1f9820ca8fb732a4cf671028.nq.gz
    ├── 3a9f764ba8fe97cc10cf92f72a1884d247f5df03.nq.gz
    ├── 3b8263b1a7ce0ae751269f50846ad8a0874ac050.nq.gz
    ├── 3bd59868c6bbbf5d893b52c3746ae5ebd3ad2a07.nq.gz
    ├── 3bec060474b23ab589cbaae6c4878c394214787d.nq.gz
    ├── 3c50be9406083de6528dd804ae5d1755893a84dd.nq.gz
    ├── 3c5b47601e280faca7847e775e267a25bc634cb1.nq.gz
    ├── 3d0ba31ebc7f3ce31924b6461f9bc8e3c5d75761.nq.gz
    ├── 3de2463ee7f11deea2fbfc4dcee06728664ffa44.nq.gz
    ├── 3ea8291ef2f9841d25bf8d5c6297cf6a80f91c4a.nq.gz
    ├── 401f6afcc01633acaba55a5a7faeefa049680d42.nq.gz
    ├── 40633f5453ce664c8b3c6d253115ef9808634e2b.nq.gz
    ├── 4159dc8e584a075832ca1d2b6f80248856efa472.nq.gz
    ├── 417df750ad445e58d6ee2eede519a71bfcfee993.nq.gz
    ├── 41f9fa3f5c6efa1b47cfbc1dc4335dfc1c27a358.nq.gz
    ├── 4242773d820c990bc63e83f1c51a8b8d8e099004.nq.gz
    ├── 434bf3fd9d22e611788dd4b19254b2ae88c05416.nq.gz
    ├── 43d66aab07d52e87879bcb81b9c32d419ef8ecc0.nq.gz
    ├── 43edc6dd07db4edae83ec0b2fbb995e6aa556d70.nq.gz
    ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
    ├── 4761595c06571184d9cad6dd7e921f08195169c5.nq.gz
    ├── 47c3d51967bcc9d5b4c6bc7cc01cccfa89109397.nq.gz
    ├── 4817865045e440bf8393e4ea734ee0ded4140acd.nq.gz
    ├── 488837e09a3018fb94d03065efebd7c918bf8c42.nq.gz
    ├── 49d4ea4941a85370a6a3dcfde87e7c7a57ed06bc.nq.gz
    ├── 49e34d3e5b46fe4e2889a71d5881398cea1651cb.nq.gz
    ├── 4a307dfe243542bd48b0bc3482cc51febcfa4077.nq.gz
    ├── 4bed24619c4391d7f57ec3811d5fc07319f08a17.nq.gz
    ├── 4e5b82449109ffb074c15a11e846ec05a8080b21.nq.gz
    ├── 50e10e485ffff8866e3be0c474ea34bf644eecf8.nq.gz
    ├── 510b34bcd6d8ab13776903c91ee0b4a117667902.nq.gz
    ├── 5113bf9407e995c444493e6e5c0d01113cbd4ba9.nq.gz
    ├── 51ebc92d015433c2b87fa4a66eb65c9ca8cf93a3.nq.gz
    ├── 52118af71091b613717b80c45f2d5411edb4c22e.nq.gz
    ├── 52b880eb756533df8d59e886c1b6ebc474160f15.nq.gz
    ├── 52c8e11a09cce1cece07ef762ad7f3b85db117ab.nq.gz
    ├── 539d01a2fd99f8c49d96eb0d1712eed9793e69a2.nq.gz
    ├── 53b49029b4e1bb67491731f5007df096b9a873d8.nq.gz
    ├── 5561b3d83a8c56ffe91345038ff66cc2826587e9.nq.gz
    ├── 557a2726715ce3f26a8ccbc9809bda09aa791b13.nq.gz
    ├── 55d97bab3e651657b66195f02935e8535d6cbba7.nq.gz
    ├── 5872d5084e8a918d7a2573a1468d2f2955cbb297.nq.gz
    ├── 5cca6ccb23094fcdf83ebac114574a556ccd85ff.nq.gz
    ├── 5d2e6bafa5e229023b0675ef3f497786c8b52765.nq.gz
    ├── 5ddc8a6492ca39738ef4d65266c3431f965d0f32.nq.gz
    ├── 5e4bc008dcf8fbccc1cd59266572e6139c909069.nq.gz
    ├── 600faeeb7b558a43189629ee0f160652a510ca01.nq.gz
    ├── 60e99613a80f03f8ffb9fa210aa22d41fa552184.nq.gz
    ├── 63241c0a02c3be46cb46d1b59fdb396b6e55de74.nq.gz
    ├── 638b654d411f67d01cef6184c094ea2eaee0c89d.nq.gz
    ├── 63e48ded7ed8719046c8bb0a854c2693992b4caa.nq.gz
    ├── 652f78acbcaed0d7c7bbec3abe9d75343299043a.nq.gz
    ├── 655209c3975cb3173b5a41f19779a840d61a0842.nq.gz
    ├── 67e4e213bbe74f0cd9212ed69bde39b4aed6a9b8.nq.gz
    ├── 685a977ba5749f00921c3189d9682a65b32eda6f.nq.gz
    ├── 68f4a292e971c356c3bf1ac442a4827920bd9b3f.nq.gz
    ├── 6976489d69a4ac1c23624bdc59255837aa6d34e9.nq.gz
    ├── 6a4dae36f702962ffbc6bd45c1430bca4d337666.nq.gz
    ├── 6aff887ad24b6d0e53d50ca528361e181a3a7a66.nq.gz
    ├── 6d17268b30c8b829c693ef809f53788889718fe9.nq.gz
    ├── 6e43d772b2549f0607f893a328f64affe5639a27.nq.gz
    ├── 6ed26a4e6009e7e534b29dbc23125a6c3ea80f1a.nq.gz
    ├── 6f1887bd4d5a041934528137bed9d9fa9012c75b.nq.gz
    ├── 706d53947e8c0f13e71b3495d74f121e91645e97.nq.gz
    ├── 71edf41008deaf1257cb2e3f9602ead287986174.nq.gz
    ├── 7240eb02aebf98e25db1e50362f84a115fb404d1.nq.gz
    ├── 724c9414f9bc051819973a674407c665d2db6fd1.nq.gz
    ├── 7546a233d19f3b7a32e682202375751a21c6074b.nq.gz
    ├── 75d08c9845ed320dfe8c751205ffa3cdd857f34a.nq.gz
    ├── 77b4104b3aef18a0a7f2d806dd03e5123d11f3a0.nq.gz
    ├── 7873e1f4faf6ddd7a84adf557c26ab4b96bcf6ee.nq.gz
    ├── 79232a2a9bbb09f173a946e5478696b5bb86ec6c.nq.gz
    ├── 793746729da8f76051da7c39f4f3c432ab693632.nq.gz
    ├── 79672e2844706e72fa8aa46a3a0d0aab009b803c.nq.gz
    ├── 7984235d5cd6efd9fdb6d6511a96124125327358.nq.gz
    ├── 7ab2fb3f18f5f5365305a9914c66886d73c62d46.nq.gz
    ├── 7b4eeb179fd7606bae5aeb74f5bafb2197130d11.nq.gz
    ├── 7b7883c9d8e743c7d775ebb269bb4742c58c1362.nq.gz
    ├── 7beeef50e2c16018bcad7d88e01ce8e2dc2263e3.nq.gz
    ├── 7c00e9957aac21c2120649730213548b5034da80.nq.gz
    ├── 7c75a09d61caeaabe658c41734bc1a8a3a307a34.nq.gz
    ├── 7d2cc7d88d9651bb3115da75f0999f993f650a66.nq.gz
    ├── 7e6d65b0f39cd178572331f201b184253142d708.nq.gz
    ├── 7ed9d531509edcbc79f7d5145c8b87854c8c59e1.nq.gz
    ├── 80ebe2f815d2f217067e3c7dc5088c41904901a2.nq.gz
    ├── 825aee84d866ea335035710bd5db987479e5dfbd.nq.gz
    ├── 82c172e1e0b195e3aa237df6e0bc29b951a09abc.nq.gz
    ├── 8499b993189ea58e5f1a25600d165d1f8b77cb25.nq.gz
    ├── 84a4d5aad1cd627a0ce031ef67fd168b6b3cead5.nq.gz
    ├── 854f3b3bbad53082a036a838c0cd36724fc8c7da.nq.gz
    ├── 85a88998fc3b430c406920b240c3c59807e52769.nq.gz
    ├── 85ff6610e8ce84a18f08f2884025e981e07afb9e.nq.gz
    ├── 865888417fe37d61b4faa3a2cea0da4fd3abd724.nq.gz
    ├── 87479a88da24f64affc5d30b0ff2b5adea0bd587.nq.gz
    ├── 8a763f67cdfe580065dd26976d3b16f4ae710ad3.nq.gz
    ├── 8ac6b8c4984dcd382e54c7923325af6d226ca3df.nq.gz
    ├── 8badfc492375840c111b32340761def4790eeefa.nq.gz
    ├── 8bb7c61369c79eb52677c4fe5631ee06155705cd.nq.gz
    ├── 8c02abbd05ff454387cf098db4cca29e4e2f5b84.nq.gz
    ├── 8eae15f74f8f1ed7c1e0f41ca409c3cea22c483a.nq.gz
    ├── 8efa6b1966e9f9f15016e59051fabe170548a7f8.nq.gz
    ├── 9286841c37cd064a966309cff5799fcd529cc068.nq.gz
    ├── 970ec6779458ff77c718163cb7bdf09b04166554.nq.gz
    ├── 985f20bb0faa66568a5ce8e9521e7f67fcf1914c.nq.gz
    ├── 988f6ffbf73ac2c3b025509a2f744144ab6de067.nq.gz
    ├── 989dd08e2eda9a9b504b6c40e34bfe01c80824f3.nq.gz
    ├── 98a5a353b34f94fe755934630da859cdf0a3307f.nq.gz
    ├── 98be230205f8e3c5a975ee4918cc1824d8b62a16.nq.gz
    ├── 98e60585d2e11212eee62f51ced7e79cc6447201.nq.gz
    ├── 9958cb92e37eaf3e5b098374e30b192b562e44b1.nq.gz
    ├── 9d86b3ea984fc5c43f9d76b873866be3efd1cab4.nq.gz
    ├── 9df30dc30d973197c16e27b6105e7913eb84662a.nq.gz
    ├── 9e91aedfa99a1f7d8e2c3c40be7dde844601b552.nq.gz
    ├── 9e986c732a7a14ccb474e7e9d5c33c02414c48fd.nq.gz
    ├── a0cd6f382730449e3995d23e1a892c67e97abebc.nq.gz
    ├── a175465d9ac788cb628cc3c5eed494e377ff45f2.nq.gz
    ├── a1dde3573c13319680beaad20d9d855eac710ea1.nq.gz
    ├── a31cf752c12d6c915bbab4d32354c769cc7206ac.nq.gz
    ├── a360b14d7c1e1ed1c704002d00b2613805f89a2f.nq.gz
    ├── a44961c7e65ca967b6e4fa2a947d8093887b630f.nq.gz
    ├── a4cbc91e1bca52bb4b9ef9e80ff4b95f566cf878.nq.gz
    ├── a68ddbe9ea8954caa6e070013b0be93d575c017f.nq.gz
    ├── a71dc4116ab617559c1889343f0a3df305b5c888.nq.gz
    ├── a926067e8b90f4b644320f17132bece34db17c5f.nq.gz
    ├── a9d3e723feb5214126de539b9cfeba59cab4ce85.nq.gz
    ├── aacf7cc1adab849c429742dc3a2e1414c8b4ea9c.nq.gz
    ├── ad2b49088afaf4a805d1c757a9070f416671ad73.nq.gz
    ├── aeaa16683112e15fb5a67eb42c4f8487b2e65c88.nq.gz
    ├── b058f1cd1b998892d9d6e69c2a3bfcd4b04b42ca.nq.gz
    ├── b0f40e80c6b52a768760de513b567116a5162823.nq.gz
    ├── b18365dec1b189566acf15fabd393f61920df5c6.nq.gz
    ├── b22029da111371c502c4d18509f16057e2521c55.nq.gz
    ├── b23f0357fed832311d9cf1cff8b3ac6e13fa55f1.nq.gz
    ├── b271175cc8e83407a46ba3b8ee4ca30aff4b2cd1.nq.gz
    └── b27fc8edb450d3c7e3f1859c5de2a0b665ce3df7.nq.gz

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

[cookiecutter/cookiecutter](https://github.com/cookiecutter/cookiecutter)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
