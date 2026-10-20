# Repolex Knowledge Graph of graphql-python/graphql-core-legacy

RDF knowledge graph data for [graphql-python/graphql-core-legacy](https://github.com/graphql-python/graphql-core-legacy), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphql-core-legacy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6e2fbccdec655ce9122b84d3808c14242c4e6b96
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6e2fbccdec655ce9122b84d3808c14242c4e6b96
│           └── chunk-001.nq.gz
└── blob
    ├── 00a7f9375fb6668c3facca16e7c1fa7e1585e6c6.nq.gz
    ├── 03026dc12ba7ce2de3fc3640328689daf8161d0a.nq.gz
    ├── 04b5108993507dff11979062f873a71444efa783.nq.gz
    ├── 04cfdbbd1c471f7503393146eec1c83fd1ff48c9.nq.gz
    ├── 056a530de90b0f265b8512ca66debc4458dbc8f6.nq.gz
    ├── 07b8068bbd312912536feafccc617534a0d0c911.nq.gz
    ├── 07bb4d0020b1f51f917b8274c66f19a81acd984d.nq.gz
    ├── 089309c46f0ce48b60ffee55228618e8c8a4524a.nq.gz
    ├── 093b3f6daed77d1542fb2419143ae0ffd41d0374.nq.gz
    ├── 0a87a8dd829944f2b7dcf51b341ab99f7db4c8bd.nq.gz
    ├── 0c06bbe903ff1ad560689d1815f87002ec328b43.nq.gz
    ├── 0c40d440da50c47f44a919c64f480884756294b0.nq.gz
    ├── 0c4c4358acbbe71bfd04713a3960248a8c7f5902.nq.gz
    ├── 0c7e103303990efc748b16f2e76cb8626e75076c.nq.gz
    ├── 0cc088444d01552a266db604c14e61b25dc5f88d.nq.gz
    ├── 0d1e493d47c6c8ae8b9f27e146a4a85bcf4cbcdd.nq.gz
    ├── 0e81bd9e394067ae3a534d7d5750f237070ea70b.nq.gz
    ├── 0f737774b8d0e617deaec16ac50dd9e3e46cbd0a.nq.gz
    ├── 12116a36fcc40e3ff0b833bae4c323cde00720e5.nq.gz
    ├── 137cf27998f756ef8c9a55bc8261c7d2cfe121a9.nq.gz
    ├── 1392fe3e1be64eaca6abf26910b770843a5e6c74.nq.gz
    ├── 141776c3546b0a7ed487f1cdedffc5a14c14a34d.nq.gz
    ├── 152abaaf22a53f310d29627cc56b84e494c01b01.nq.gz
    ├── 179c45dbfdfad4a369aba64f152337a55dc557c0.nq.gz
    ├── 1839483eefa83e9bebc43905df096ba9f4019e2a.nq.gz
    ├── 1a2dd8e4adc5eb11caf525777cb94e4ba9853599.nq.gz
    ├── 1a3b48b56a999a91974a7f02ea77eb3baeb8365b.nq.gz
    ├── 1b65d871dee24bc6cc7e5c744a637fe248e59a73.nq.gz
    ├── 1c3948fdeaf5c6d61eddbba04d30e311127ec3f6.nq.gz
    ├── 1d14dddb106d7d687f8d2b0cd522c81fc5e9ad70.nq.gz
    ├── 1f5cfdc0edbe7efa7468e6cec763ec31f573dfd5.nq.gz
    ├── 20c1bcb57c7b1e3127c876405220a609e5b6ab26.nq.gz
    ├── 22f9607cc09eeb8c9dd00a72c9d55876444c2cbd.nq.gz
    ├── 240b95c16874b9ff6a8aa6ec1608fbab27d6e7a9.nq.gz
    ├── 257eb64b640438054e438e45f7543c0be6b31487.nq.gz
    ├── 2727207d34543607a49ee009c294cbf72deb6284.nq.gz
    ├── 2775b9ede41a68e26a81b41d6c6d900cfe565c5a.nq.gz
    ├── 29d62d46b9cce20f175d7b19b4277082e6987fe4.nq.gz
    ├── 2bac5b1d926dbea94e7b7989c0bb2694758177bd.nq.gz
    ├── 2bfff7c5dd3036bc7b7633c9a0194dac39646b87.nq.gz
    ├── 2e07ef29ef14eb511cddcc548bff4a259b26ebb9.nq.gz
    ├── 2e08bdced7d9fed869c1631f89553866e41159d7.nq.gz
    ├── 2e62a2868701f3aa6c09092ee17eab79bd5a5b03.nq.gz
    ├── 2eb2a15a9a5f380c17dce4eea1fd8978174b7c54.nq.gz
    ├── 2ed1803fab6b6f6a827bbd22832dcf37cb1417f4.nq.gz
    ├── 2ff530d25bbe9fd35df39bfc581eecc542f88983.nq.gz
    ├── 320a0c4ae48c416c73b5faf4070d36c0da799edc.nq.gz
    ├── 33324b40cd9fc6268ffc6bd47a2d2f132d531ecd.nq.gz
    ├── 3534a137c4afe835c42e6360abd1ac5b009c86a3.nq.gz
    ├── 3562d53aabcaadecdf60d125f0df4a15c454cbb7.nq.gz
    ├── 361e1525197d82d4eab224eaec9c54120a0a3123.nq.gz
    ├── 37372c48dbe5434067fce421fe670a9f9b9a4a85.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bc05c16950c968da4d139cf1a56601dc31431fc.nq.gz
    ├── 3bf82177de68eb15975963012af1e4f5e9e8eee7.nq.gz
    ├── 3e389d53de7c35af92a9eb9840683b823b93448d.nq.gz
    ├── 3fe55a4651802281e658af450f18331e4705e4a1.nq.gz
    ├── 41a11115c7f191c30859196df766155fae87ac30.nq.gz
    ├── 45cd6683b1db337dd7766e6ba0ef0a87d4ac8250.nq.gz
    ├── 460d9191344529f35b47d3db9bb774376ce4eb84.nq.gz
    ├── 470991df504b1a83b1ee7f64159598bf09a5a2ce.nq.gz
    ├── 472f95b960d818e0c85a25990826acd3f9c0ecfd.nq.gz
    ├── 474bad9e8ce4320fcf34c0e23632b52162277e6c.nq.gz
    ├── 49397ad9bcb15faf093776f1334b66d1e64158e3.nq.gz
    ├── 49b81faf082adc40769adb68902e80cbcbfeeace.nq.gz
    ├── 4bc5ac4e9c6abcf8e643f5432cffa55add80cc11.nq.gz
    ├── 4c68c27b510082546c5c46ba2fd3a9cee68200cc.nq.gz
    ├── 4e3b4d947d9fc957a761cbf9f97f940977de4c85.nq.gz
    ├── 4f7cefc13f3a546826236bfb426e15207c7b9d5f.nq.gz
    ├── 51b1ae23ffcd5ac8d50d9cd2d45353350f63ac6d.nq.gz
    ├── 52e59e2a5b0de08c33d53b273c9765436bc8af54.nq.gz
    ├── 53541c9c0e2ae2d4ee6e2809eddb83f974e8c365.nq.gz
    ├── 53c6040fe23ee08e604b90bdbdac303a0fe455d8.nq.gz
    ├── 55a2b8c28631ad36b292622e8b15fa9f64b17183.nq.gz
    ├── 578eddee58f663c0446a19e1dac0e58dbdeff46a.nq.gz
    ├── 57b181539c8d6f41c43a79d69cbefc4582da1edd.nq.gz
    ├── 57e6e92bebb3a66fae44c407d916dc05755be33d.nq.gz
    ├── 59df5bb0a0c6633a7dc7354974688c88ecdac1cf.nq.gz
    ├── 5e3c2cd055b8405bf64eef82414cfaf0ce58692d.nq.gz
    ├── 5f373e065685458a37431c47a18944c604c90f52.nq.gz
    ├── 64b849a01c5bd7bc67f554f190393eef143b2839.nq.gz
    ├── 6587ed0946dbb9d95119e4c3ca3f0700b4f36627.nq.gz
    ├── 6743ff38c1a98af6ae8e010c4d66ebe30afb6053.nq.gz
    ├── 6793cf0ebfea6784a26d7ef0abf6988885f731f2.nq.gz
    ├── 67a75f402e38a53c0c680e550eeefed6f2a04c87.nq.gz
    ├── 6868c138915971e258e045893e0b67421b95c623.nq.gz
    ├── 69b64e453263fe8db6b5311cb20b94f2848cb78b.nq.gz
    ├── 6c4eac1307d05915ad7089db428f7ecaaf5b667f.nq.gz
    ├── 6c9d5f477e60ec89e7ff9fb1e07fd1ff3c0069e8.nq.gz
    ├── 6d7bfcbfddb86e329bb15363a3ff646e0dc2e84d.nq.gz
    ├── 6e71ea6b802ff6ebd602d871b962ae06432cefb7.nq.gz
    ├── 6ec58d4def3f93f89c2592fc20a7c761777de0e6.nq.gz
    ├── 6f84aa640a932459bba3054963dc5004f30fd263.nq.gz
    ├── 6f8a3725c9f6060c77643a1f5733703b81164e90.nq.gz
    ├── 714f59ee153d7d55f83f6ee5cc81773e09defa2a.nq.gz
    ├── 718b324b4b82020fdf96cabd8fec72a4cc19ff1a.nq.gz
    ├── 71c19bd936a2b466f0b7bb1555908c177e8905ee.nq.gz
    ├── 787089ab58a2c573c193c13a1c54f7ae8051fe13.nq.gz
    ├── 7a62771129838edb539b69677375bbc8e9102f6e.nq.gz
    ├── 7b9aa677e6dc598c6560093e723a077fdab7ea6a.nq.gz
    ├── 7b9f87d3a1e33df93faeebe395c3320aa9ba639c.nq.gz
    ├── 7bec2763832cbb01a3eb2b383e05ab3e05bfe2c3.nq.gz
    ├── 7d7538203b9059a39937fffc1d9455e86657c327.nq.gz
    ├── 7f29b8dde44c2574e2b1c0d97eee0e32b65e693a.nq.gz
    ├── 7f4868db119729ba75c64c53e25bc8bd8d9eef02.nq.gz
    ├── 8085189bc0c13b310035fc619aa61e5460493890.nq.gz
    ├── 82174da1a5d0c2b944d3a4c1e4e6476c111e6730.nq.gz
    ├── 8501558ee5f757e9ba60d46708aa459129be028e.nq.gz
    ├── 8517c50b861cdd9811ae8b85ff22cb456aff8be9.nq.gz
    ├── 85492b26244257da4e05fb126a75323e8f577757.nq.gz
    ├── 860a209e88a855aa7c9f4457529521f75d9be34f.nq.gz
    ├── 86728355ae1cc2f95752691ef12f41e4b2026db6.nq.gz
    ├── 869a81cc379703f1a13447a9c3503f8069727beb.nq.gz
    ├── 874d1fb90fd0a9e50a53c7d9dfa481a184ecb5f3.nq.gz
    ├── 88f292d105e489a6d6a36276c15ea3190fb5bd75.nq.gz
    ├── 8931cec18c7452c99fec1d4321ae63eba36b64c6.nq.gz
    ├── 89cdb4c768ce8b6d758eb9b589faf293df041545.nq.gz
    ├── 8a0209d16a5750d08a18db49fdc55677be1d3c0b.nq.gz
    ├── 8c2e7a93a8fcb978af8aa8abf9edbf7238b54ea1.nq.gz
    ├── 8d60ccb13e750bf617eeb343fd5b36654b665cc7.nq.gz
    ├── 8e2755f224501c71f9db8a9d5158469b07bd46c3.nq.gz
    ├── 8e5d12f4ca3fed60ffb07d1cd1f724953053801f.nq.gz
    ├── 90043da63ec04e80db5e799dd1528b7d9df4d05d.nq.gz
    ├── 9007b1a56412cf69f5ff416e9000e5aaa218393b.nq.gz
    ├── 90769cbecd437bc71ef557eb9828ea2988c8354d.nq.gz
    ├── 9256a018cb6b413a5175b94d713c47634226d32f.nq.gz
    ├── 93c3331c6f8b766e7ca46c6bc43ed3bba38583da.nq.gz
    ├── 948279aee4fe44c1733f3053c329ebb2a1fbf59e.nq.gz
    ├── 951d00c4da3f8e25e6d6281f3a98676a4c6f889b.nq.gz
    ├── 96966a8cd65ee4ca56fb80a5682ea7334bbe7ff0.nq.gz
    ├── 9715288dbb76e3d55a6991157b7dc45ef7305aa6.nq.gz
    ├── 977a2b3ce9fae8fa5f2d774a32b6344110ace632.nq.gz
    ├── 9a73b3757533c8017985f5e5df7561417f7efde3.nq.gz
    ├── 9c8f88dad1f4cc10dbb1104bdace90c344f2563b.nq.gz
    ├── 9cbb05810cd53eadfbcb643ba8577b26f5cb83dd.nq.gz
    ├── 9ea0b439f003ea6b229afdcb246fd26cb1d8f630.nq.gz
    ├── 9eac02b3fa2a1b3cf2c3a44f717014d5663a0fc0.nq.gz
    ├── a03538615850fd2e23b9b7f8abf8f4a85d2b34c2.nq.gz
    ├── a20a18c1eadc1275799c902b294ee3acdcf6f10e.nq.gz
    ├── a36c4e8d0708774194c8d77068e70ec18129057a.nq.gz
    ├── a3c3ff93f52ebd3e2fff3ca77d3a999eecf1ee87.nq.gz
    ├── a4a1a8fe854bbe50ef3b43a93c615632251d99fe.nq.gz
    ├── a6f730780466ab4bcdb4075835b7fd313d1861a5.nq.gz
    ├── a9daea355d5ff0b9de803160ddca1202c64e4ec5.nq.gz
    ├── aa7fa5ba1eacc1f4f855d9e0f648427438274a88.nq.gz
    ├── ac1c882dc38bc6d1d88c0a38ea6320c199c9f780.nq.gz
    ├── acc1ac141b3194d423f83a355fd23931fed84b0c.nq.gz
    ├── adafd859f29d1ed462a0d53d9ee9bc463829b30c.nq.gz
    ├── aecd71f8025309d89311e1cb638439c1c2658755.nq.gz
    ├── afa979cb4b5e482dde81324a873902dda0aef113.nq.gz
    ├── afb44fa5fdd937fd1eb334b19a9c14e761558b6f.nq.gz
    ├── b0e6407750aef60d49f79823fb669d2aaa186f34.nq.gz
    ├── b16653c49cf9b283ab26e45a68b63de6424f6acb.nq.gz
    ├── b1db4820f2a84e217a58e89bfa6d546b263931dc.nq.gz
    ├── b25f1ed1468a6cfa1644e0696f152ae9b77b439d.nq.gz
    ├── b4304cb404b91c83a3d4ddbff2efcf625605979c.nq.gz
    ├── b5bec97f139ba448451fd7482bdc129652fadf9c.nq.gz
    ├── b8467bcf885d8723f805fd4665665b2eb68a6437.nq.gz
    ├── b877c3daae9095fadd5cadf181e9c45205047a8c.nq.gz
    ├── b912b3de80b6d1244ed0f8f930caae7d833fe0f0.nq.gz
    ├── bd61ba30ef2010e5f03cd511f2d462ca01359223.nq.gz
    ├── bfdbabe8f27541fbd93365ba79c8d6917e4f2746.nq.gz
    ├── c17a4dbe53398badc3f5c79a989b7b3b12d2c920.nq.gz
    ├── c45d8a8f474996982eb0f6be6339a6a633a4ce4c.nq.gz
    ├── c8e14afe4955ce65efda4adc06ff21d9f6dd085e.nq.gz
    ├── c9a8dfda1bf9ed5029d4239c81465499c1e3b6a7.nq.gz
    ├── ca6f69d002a5ca69999fb73a7da4a274a031da23.nq.gz
    ├── cbe6c05313e44742120e0bcad9e111eaba40463a.nq.gz
    ├── cc48096423d2f7499a7a5f3ad7c63f8b2ac749c1.nq.gz
    ├── cd4ef3797728486d76b916fff4603e29b32a60b8.nq.gz
    ├── cd5ba26d74535f6631aee9112fbd080d0a490545.nq.gz
    ├── ce474e11c02bccb8343d46575c86a19fe3900db8.nq.gz
    ├── d27b50cb332e5dcfcbf241e32825a17ea1e64317.nq.gz
    ├── d35c0872725225bab314f1e089045d9e5af40026.nq.gz
    ├── d38adc1fe8742d70679387592ddedc7abbbdc250.nq.gz
    ├── d40bb47ab608a4bf6851006a4f08bbd78e8a14c8.nq.gz
    ├── d58e4e24da2d8a458b40e27339e44f8c71f1eea8.nq.gz
    ├── d6c2a7f7cb1375ff0082b3c980a45beea65a6192.nq.gz
    ├── d76dfc52af2db75934c20919d819f62baf6650c0.nq.gz
    ├── d7ec17bc08f373c1f3ee7a94c057e88ad427d5d5.nq.gz
    ├── da4588328d9216e47ebe1bacb424819b878696a9.nq.gz
    ├── db1656691685ee6a0e417a4632e0bb4ebd04a1b3.nq.gz
    ├── db8f80a9a37086cf5439ce509114302fd5d5daaf.nq.gz
    ├── dc971265bc48650e423e91afc37af885e7c1d6f0.nq.gz
    ├── dceb4aaa586cf2f871fe19afc276b0cdf28a95aa.nq.gz
    ├── dd00fd4434fd06e8dd59df62230bf41dfd5ffd1e.nq.gz
    ├── dda777d9a9b4bd27ff652c085ff16baaad77e46f.nq.gz
    ├── dec4d8469345b208db140f5a05cd566bca1a8c22.nq.gz
    ├── e224ff37a47f21269610f7b3a3e2a8ec87eb722b.nq.gz
    ├── e282a875b5a2f84368370586a4de84dee3c64e5c.nq.gz
    ├── e392b82d3d43fc403295f2f4289f36768590332b.nq.gz
    ├── e3f3e6299df747804c2d4e9fa9e1897f0b8a047d.nq.gz
    ├── e540bce51c0034f5a05f2e52d18de0af85bcaacb.nq.gz
    ├── e572ce8ef499ec506dc9380926297f4d6ff63873.nq.gz
    ├── e6940fbfb607ced96e86eeb0301f393786affe2b.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7b18ebb80318bed1105b8453928f7400494424a.nq.gz
    └── e8fc309947b8c90aaebe237ad1b67bb80411fb8d.nq.gz

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

[graphql-python/graphql-core-legacy](https://github.com/graphql-python/graphql-core-legacy)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
