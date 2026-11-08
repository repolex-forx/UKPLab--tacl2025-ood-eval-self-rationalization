# Repolex Knowledge Graph of UKPLab/tacl2025-ood-eval-self-rationalization

RDF knowledge graph data for [UKPLab/tacl2025-ood-eval-self-rationalization](https://github.com/UKPLab/tacl2025-ood-eval-self-rationalization), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/tacl2025-ood-eval-self-rationalization
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ff791547441cf1f2326580253c3c771707ebed83
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ff791547441cf1f2326580253c3c771707ebed83
│           └── chunk-001.nq.gz
└── blob
    ├── 0107ffc426ef25252d7f5656789525d38bef44a8.nq.gz
    ├── 0138caf323bc12cf83f29af39dd8d43ff2d79896.nq.gz
    ├── 017a8f0936f43eb56293ba085e1f606f66572e6d.nq.gz
    ├── 0275198197ac2c2dba68f6ca3df0a1001f10a709.nq.gz
    ├── 031f9c9d13f3dab19e15c270bf70060b31d97c8c.nq.gz
    ├── 039496b0082040b12e12437d943f43733e46ba7c.nq.gz
    ├── 03c56534c73cdf95158bf24f4f39e23229c278cd.nq.gz
    ├── 03daf897c689b4ac2a330ff15946a5f9194b77a4.nq.gz
    ├── 04a2eb2e670b12bd37323b0a4e1868ef09effb07.nq.gz
    ├── 05d7bd809d71c976b0559cbc602e7d8e7f918a65.nq.gz
    ├── 07e5a1f6f02973b8ef96f21581924b91a4c36b41.nq.gz
    ├── 08962fff28e14650203a39fad87c9dcc28021334.nq.gz
    ├── 0924e85e88530fb29d4ffdd6d60b04aa748a1601.nq.gz
    ├── 09be4565e4154ba37f208ec7911a7e7f713f405e.nq.gz
    ├── 09c0b95d85cd34bed8d07ee235d9328a047e1ad5.nq.gz
    ├── 09e10f5d670093a2c5052c3393305c6722dc7102.nq.gz
    ├── 0a0653dda8b8fd5a73b824d4e6c32471966d4dad.nq.gz
    ├── 0aeb1e23998d79236cd25d326ae7d1319809eccd.nq.gz
    ├── 0ba13348d5ab31bda359979bfff0359068f749d9.nq.gz
    ├── 0c319ba1bbf6f5d6df89c00515bda1b2f21fee2d.nq.gz
    ├── 0c9f72f688beb48a6a875cee5327e3a156fc6f97.nq.gz
    ├── 0cb1cef37e83e2c1270aa5af4c176ae53a3626c9.nq.gz
    ├── 0cc49ed66f999bceac04323aafbde6842f6c15a1.nq.gz
    ├── 0d5191df51d9ee1db33aab3a1f901699c52d96cb.nq.gz
    ├── 0e2dd5a88ed4144d56e3cfe5ba4ea0ff9750f3e2.nq.gz
    ├── 0ea98be9e4711e8baf6d2c26a32bb91ae88ba513.nq.gz
    ├── 0f05213e9f03aa05deb707970ccaaaff20c795de.nq.gz
    ├── 0faa0ab2362a8bb1cc43fd9017b2b23552a9d4b4.nq.gz
    ├── 12024cdb086f1079afa72a760851946df9e2c938.nq.gz
    ├── 123ab003b2352d63b5d5ea4166dd027b3499a508.nq.gz
    ├── 126b5081e12f80113460fc7fe45c2d15e1518261.nq.gz
    ├── 13465fe46713d02851da27d6787153c2b79c5092.nq.gz
    ├── 1398ce16a1743aec1628a8ef374844725fa24683.nq.gz
    ├── 139e892e49290a178091aefd9202450df20625bc.nq.gz
    ├── 1411ab9e4f0f2a7022ad7953033d081a2fd37aee.nq.gz
    ├── 1467394867270b792a3aa7d22ea8500abb3a71a0.nq.gz
    ├── 1533da7c7172fe5f60c2c41b03fa5cb2cac7561a.nq.gz
    ├── 1660e85956d12524a1c6a9add81b8e3052fb3113.nq.gz
    ├── 16a477facb520fdb01234649d48584d5cacc2dde.nq.gz
    ├── 16dca060912c34d2c8b3de5d168a29b86ee121a3.nq.gz
    ├── 16dfbcf4eb00f6805e3ce8c657a62b8acf79d0d5.nq.gz
    ├── 17d7e5bdea62f5fa2d485a216bca7226ee82a20a.nq.gz
    ├── 194e976504da9e7027be74216f984f647099ef70.nq.gz
    ├── 1a496b26aeaafda4ca8686a84d244119f2fd4b57.nq.gz
    ├── 1afe5ff5cb28524e3db96b26892c2131cbd52d1a.nq.gz
    ├── 1b09689e4ada65fa0a5ba8209ca2226adfb092c4.nq.gz
    ├── 1b714755c52af4da7fea142107ac3af500db8f2b.nq.gz
    ├── 1ba7e07e3c2e2bfc65da281f6440dd7cce052bd9.nq.gz
    ├── 1bbbe18e6a184a60351da718be9c201362bd5f16.nq.gz
    ├── 1cbcf437c3d51e4dc155e2b4e36820a5460ee435.nq.gz
    ├── 1cc71bf44789fe88300acff29a8e62bd07b4d7e0.nq.gz
    ├── 1ce26baf7997cf3233c7dfe6492ae6f7c0ce5d58.nq.gz
    ├── 1e7311f8968d4c2b1dc85589363114bf00255c12.nq.gz
    ├── 1ef4072fa1346df15845c54e66d5348abd735db6.nq.gz
    ├── 21410b6fc2f5db7164db5bae91a381766374c443.nq.gz
    ├── 224acd34b01e7960301836cd4d1abbb27076a4bc.nq.gz
    ├── 247cccfd6ad7ad5603a9e51e3502c31531e61d93.nq.gz
    ├── 249e96a0f90125e40e7fd1540ecc17513e40cd07.nq.gz
    ├── 24e68ec9c17fd5772b25bc2d59fdde60aa2fcb27.nq.gz
    ├── 25cab302e9ce973d10dc42a4f9d46ced877b4b8e.nq.gz
    ├── 261a13876a55327aad10e2aefe355ce2c37dc7cb.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 262e4ea15968f5dbf895c117e1292d29d75ad6a8.nq.gz
    ├── 27579c73a16d96de1cec9d7ed68dca5016c970b0.nq.gz
    ├── 2782a8ae67c2d018fb8ef0553c540301177b7f9a.nq.gz
    ├── 27958bb1d4f5f0bc49f4d266ffae1d8db01be3f3.nq.gz
    ├── 2802cb54fe5953863e4c62682efacf237757ab96.nq.gz
    ├── 28245b0831de5f54c88cfe357f03f0a1d9ae6a4d.nq.gz
    ├── 294fe40e8fecb38b5b039d9472b74e42d5b97c51.nq.gz
    ├── 29d49489d252709ca23cdb0678e2c4226191d795.nq.gz
    ├── 2a5d099d0e147b77071a35c1f9a1fd87cef679ab.nq.gz
    ├── 2ac301bb332821c33e33657a2a5ec3abf1333d52.nq.gz
    ├── 2ad4f333b1ed0d0de4af62b40d1eb47a799e2d8f.nq.gz
    ├── 2b0817a9125d8a2c94aca808e6d1320209700fbc.nq.gz
    ├── 2ce4a8f2e4ca1a556618be122d4ceb9ebef4eea3.nq.gz
    ├── 2d3728f64840623cc49f66feadaf71ffcc929db1.nq.gz
    ├── 2d8c59fb1c043b9cc840dad72105da5949f3d7c1.nq.gz
    ├── 2e027e63aa5f0ea672ad8224da97f346c714f1c5.nq.gz
    ├── 2eb3ea2f90e383b5c9668f9115e62535b105a0e6.nq.gz
    ├── 2f671e447fdce958012089ec7d151c88b873a70c.nq.gz
    ├── 2f964af9499e76c337874e5afe504938de35aa9b.nq.gz
    ├── 3015bf53bc37285cf20accaf4833c1bb50c130e8.nq.gz
    ├── 302dc76e3b57997dfc68d40ea8191ea523e9519e.nq.gz
    ├── 3035e6a392f51ec5c92dee1fb974bcb8e8e10886.nq.gz
    ├── 311ec11379d012be7055fb5c857d7d0ed9bb5165.nq.gz
    ├── 325d0fe99c31f318d9b9a5b1c00b7c1c7a01d6c7.nq.gz
    ├── 3303879874d8ec195d2594ebed1595fae1c8c951.nq.gz
    ├── 3371fd1754959ddf4ce0b422b491934b4b615ac7.nq.gz
    ├── 3390ccd5cfa13eef4493c17bee2638e301cc4519.nq.gz
    ├── 340c125a858933ab39f3beb223b78afc4b4cc460.nq.gz
    ├── 3430f1f8e7cf3a624fbada7c40ba5295e0bd09f5.nq.gz
    ├── 3467b742c64ba6de0473d91e325ef98d801d07dd.nq.gz
    ├── 349fac90e4d719d11d82a50889265de172ff02d5.nq.gz
    ├── 35283d7de55634cb73fed16d7b4f3acd879f4eea.nq.gz
    ├── 35977e843fd49f7114e9b506ac527a844c0cb8bf.nq.gz
    ├── 35e1c728137997202252c40b58ab8aac7323404f.nq.gz
    ├── 36cda687877ca369219969f8f105a0b3abb1cc18.nq.gz
    ├── 3744cfb449452b78f3b2886bd2e07b0f30cffaaa.nq.gz
    ├── 37df2b3859c069ccbe3eafe1c98b26b8ca6b65c0.nq.gz
    ├── 37e0898ea2203c7eb47d51527fc93f4858c47a43.nq.gz
    ├── 38180203be8783e48776ae1b37b7ae4ff602e058.nq.gz
    ├── 3aafea4ad931d2fd27e603b2520d166228a207ed.nq.gz
    ├── 3adda747e78f81944c6a1a6b1c02ca0828a34fcd.nq.gz
    ├── 3bc9deabb42ffbbb2005849f543eb3cb5d094a16.nq.gz
    ├── 3c59cdd5ab14be0f5d2fcbd32de9af593dc12266.nq.gz
    ├── 3ce206cde84a1ebc38bca42b6edb801a4d1c2dc1.nq.gz
    ├── 3d49a5dae1e43ecef3f426230d1e13b4843eb42a.nq.gz
    ├── 3da229648fcea5b174108ec57b6c2da16d9dfc83.nq.gz
    ├── 3db50c42bd8e3528502a0cfcf00695aaf5bd644d.nq.gz
    ├── 3e05a7e758cdeae83169912c51c421075e5cc0e4.nq.gz
    ├── 3e40a45c4b921a7f26e6f3f28a9f3a72e69fe045.nq.gz
    ├── 3e98f78a46cb59b0c0cf9cf2e289ca1d6f54d120.nq.gz
    ├── 3ea06aa7c2a88bcfb1afb6f7d2bedea67032fac9.nq.gz
    ├── 3f2f9b8ee7bfa37cba579103fe3d14a8ffa297f3.nq.gz
    ├── 3f5932fd2aa4673314751d98bfccd84c4c619841.nq.gz
    ├── 3f627967ff1af2abf69dc1add890546ed8e0d7d2.nq.gz
    ├── 3facac104a95a03f7a07b400c356cc2067d08e72.nq.gz
    ├── 3fccb7ed5284c40a963a79ec72335db0a9201daf.nq.gz
    ├── 407e2dfa0e1d2d1d775a156d6e4c0ab07532c9a3.nq.gz
    ├── 40e5f7717b9a649610bc0d6cc16efe650531981b.nq.gz
    ├── 4176bd26699e85900b9153a689215b50a5acdd6a.nq.gz
    ├── 41ba1389db931b2c50fe09954a427edf60b95cd5.nq.gz
    ├── 426653f0c75b5674b20f253b17391b7575e211bb.nq.gz
    ├── 42b3b884ef2242f2f3f1cf15bd6d2f47dbcddaf3.nq.gz
    ├── 42c692471136e6872ffef9dd3a637368c03d7fcc.nq.gz
    ├── 42e53b5051749d861600d7fb30a4fa069e4e701f.nq.gz
    ├── 43171edb6f5f5606011a90b6f8b36cde9b8775bb.nq.gz
    ├── 43bce4466ff8a58bb6ce857569bad0e2897d3851.nq.gz
    ├── 43c8e47d7b5b96176282f5aeb808f42081c43c90.nq.gz
    ├── 4624f077adb3385d88df9c7e551b6e93c0591964.nq.gz
    ├── 4736fdac97a95caf83c68298f694c359aac20b91.nq.gz
    ├── 481f8bbf11d71e0fc8814251c8ac2993cb221677.nq.gz
    ├── 48a044ca24e0b3e15b16c9b0de27062d744978ef.nq.gz
    ├── 49b35efd60f716969b058344137f2b9ad0182af3.nq.gz
    ├── 4a19abf62b28a1a7c1427043ea8122a0b5a78743.nq.gz
    ├── 4a40b837a463467b4504949329b36b38904a84fa.nq.gz
    ├── 4ae0379dc7d4e7825d2f30c5a479800505ec2431.nq.gz
    ├── 4bd19cd5c6f24147610fb7c11eab34d7d35d3689.nq.gz
    ├── 4be5f7f7f8fbcb42c1a294e1c72ea35a712d17cf.nq.gz
    ├── 4c7e6c834b6e5862c06a4ff41f54506072cd8e27.nq.gz
    ├── 4c8046746b97044971d45d8625c9b5b6872fdd5e.nq.gz
    ├── 4cc68cf14e72d99edfbe934f0b20b736a2ec4739.nq.gz
    ├── 4ce2fbe5ca3ee23aece8eaf00b4b201ae9882c17.nq.gz
    ├── 4daf822f5876f10679b35cea4f4380f69519a004.nq.gz
    ├── 4de2ab6411da151b2ed6e3006707be482c68ab73.nq.gz
    ├── 4e1cedb3e09ad736dcde3e52e2f1c03eb757caf8.nq.gz
    ├── 4ea10d5f4f3bda274eab618f0b73eb012f28cefc.nq.gz
    ├── 4f52ec0f3380d0696e7b8dd67e4a712730b51809.nq.gz
    ├── 4fc184765d22178451a9e9f8f496263e18529f19.nq.gz
    ├── 4fdd055affa7cef88fe11e394634082ef4464d0c.nq.gz
    ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
    ├── 506ca783c425941020e52d2059333688f76815b8.nq.gz
    ├── 51fb1ffc829cdfa74b995fbebe619cfcc1697d3b.nq.gz
    ├── 52c385e02ebaf5ad881f517c51842a70f764abe7.nq.gz
    ├── 52c7d76239c2c8ef8f3996ef8722fe164dd608b0.nq.gz
    ├── 52ce8c446adbc8b48550d9a2e771215b14da637c.nq.gz
    ├── 54b27f77bd9f394dfde44df801f740e5e07ec6a4.nq.gz
    ├── 54bd6cc9b2f068a1e6748f7d3f51439bdab1b316.nq.gz
    ├── 5596ae9d97d1b37426c2f023e84a7ef90e184590.nq.gz
    ├── 55b2c3c829fb38928e9db9658685d9d15a96c431.nq.gz
    ├── 563ef8a24d0b6f93abdc8a101655ad142baacf1d.nq.gz
    ├── 5666885bab924b9e77807c94a9e99d3153db1567.nq.gz
    ├── 56dc89c94df2171dea9af506c2303926514ddfb0.nq.gz
    ├── 5749d312ea59b6fe5b1b549d3fd58d04d8fcc1b9.nq.gz
    ├── 5867b3cd68f9eca40f607530dd77e329e94b01a3.nq.gz
    ├── 593413bca998d42fb3da7f7d4f3221e2c1987457.nq.gz
    ├── 59eacdd6d7ea0df2e6b81424b71c17b11926a8c7.nq.gz
    ├── 5a1658715b83b53a7643690fe5e166247afe84a7.nq.gz
    ├── 5a1868336ef99d04c7ced1e340363e2035cbc4d3.nq.gz
    ├── 5b365b3944da977b6d7c2b0f90e61e51d190c1c9.nq.gz
    ├── 5b4b21cc207b35cb03d90fcad78024df06c49ddf.nq.gz
    ├── 5c45cff4f9eb269b729adc0212d9ba76ccdc0634.nq.gz
    ├── 5c494e9f105d89aa82041c8e5925943dbbb59667.nq.gz
    ├── 5cf54dc21a4eef759ace847655b2e39f6bdabc2d.nq.gz
    ├── 5d7b3b30dd86fac019e0d367ccf300d47e31d65b.nq.gz
    ├── 5e4db7cc4a3040dd3b726e02ce14ab04f543fb8f.nq.gz
    ├── 5e716ad4457519adaf966ca75ed6576c369207fb.nq.gz
    ├── 5f048f7cf9ad12b4c9c2a48ed9ab40b23983ce75.nq.gz
    ├── 5f2baeea89dfe2ff905efb8e757ba86bcc7fc71d.nq.gz
    ├── 5f6fa4159b9171f9328db667656ffde9f23362e1.nq.gz
    ├── 5fda71d93c7f0f44014a14b5c1c0c50de0c1a2de.nq.gz
    ├── 60614225fa76711f8fb0c29348c8eada48d7526c.nq.gz
    ├── 607704ddb8f241c0d4a69237d3f253de3aa493da.nq.gz
    ├── 60e98e8ee68a9a1c51c22636bc5fc09094fb4437.nq.gz
    ├── 62b689f60def31f301c98f1655094f3ae92d2dfc.nq.gz
    ├── 62ec8489dd753b68567fe4ebf042bcc87fa30559.nq.gz
    ├── 631af3d94490964a2aab739612f8144fdf83e2f5.nq.gz
    ├── 6338bfb53da2e73b3139cc1c0f2d55f9a60935d8.nq.gz
    ├── 633f2ed16a597bb4f6e7eb4afe15b1eea082b8f6.nq.gz
    ├── 63a09c1c8f29167a2bfbd9a5e641cec1003be5a9.nq.gz
    ├── 6402603ed166d41be1f71f6d31b8cdffc4772a76.nq.gz
    ├── 640cab69a6fc60f9eca4039e7b53feda36849cb6.nq.gz
    ├── 642c8d5f37aa6efbac3c13caa200db29461fbb55.nq.gz
    ├── 64bc2af50ce594b52e4b38f0a78b0e21db80c101.nq.gz
    ├── 64c5924738f310c8fd3ab9d01ec79adfc9015a88.nq.gz
    ├── 6517afaa9d8c8050e03c6e61a77950b0f5ef52ff.nq.gz
    ├── 6585d36353cccba5133ceec1e3eb9f23b1674350.nq.gz
    └── 6652e868fadf3c4cc1056011b8bb656baf382527.nq.gz

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

[UKPLab/tacl2025-ood-eval-self-rationalization](https://github.com/UKPLab/tacl2025-ood-eval-self-rationalization)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
