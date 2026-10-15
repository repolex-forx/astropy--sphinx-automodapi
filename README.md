# Repolex Knowledge Graph of astropy/sphinx-automodapi

RDF knowledge graph data for [astropy/sphinx-automodapi](https://github.com/astropy/sphinx-automodapi), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/sphinx-automodapi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 330ef7db93f45c03ebb346be8d6984527379412b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 330ef7db93f45c03ebb346be8d6984527379412b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f2bbcdc46903c407d49b1a5167fa047c05404e.nq.gz
│   ├── 035a9b2d14fa526cab571f3143b685b2fd0b7211.nq.gz
│   ├── 0381ea232df35dbdb48162fdd1d2f3fe940baeed.nq.gz
│   ├── 03e5701a3fe23ca40b5d2ced3c3e60b8c89c02d7.nq.gz
│   ├── 06c5c782778488fb23490d9ca08576438e7628c0.nq.gz
│   ├── 07638af9bc667ce8b62df852be7160b568c88ac6.nq.gz
│   ├── 0abbdf1c9832d8690750935235d5a86f813c6bb3.nq.gz
│   ├── 0c0c57fa604f64828979f1959fa1865f78f97b02.nq.gz
│   ├── 0c7850fa68c22b0cef8a96cffadf283c7cd8ffaa.nq.gz
│   ├── 0fbc725e52f4a7651237758165022c1881e621aa.nq.gz
│   ├── 11208a25c6b1c0ea2902dbe733baf4eb84572dc9.nq.gz
│   ├── 117167dd9a32d1373170db018905042dfb032f29.nq.gz
│   ├── 11fa36627457d04875aaabd77d5561fc7e18d14c.nq.gz
│   ├── 123413a0aab88f43807d0c12982fdbbc932d188d.nq.gz
│   ├── 15c97921187ae11a5f59af11acb915b7c7f5f0e0.nq.gz
│   ├── 1710307238dc2a36c0b716fabf48e13c6c245858.nq.gz
│   ├── 175a33a1e69d685143ef4e36b6106868fcda4e06.nq.gz
│   ├── 1b95d3102b78239900f4e84483a0fb61428fd79b.nq.gz
│   ├── 1c57a6afaff7c369ffff5d82b57536aa30b94224.nq.gz
│   ├── 1d99fcaeaac85c939ed104987e75332503119b4f.nq.gz
│   ├── 1eb1ec4fd16dd7e1a37954b9afe0bb3805c25c95.nq.gz
│   ├── 1ee57e4e84f221433b3904f96cb09f8ae96bac7c.nq.gz
│   ├── 22da8408c2da62616bd30e4ce42c0356f3955054.nq.gz
│   ├── 246a87f590a71e379e448a7d27ae21bdda668dfc.nq.gz
│   ├── 2821ea110a6d69167f3de569a272da1ff556139f.nq.gz
│   ├── 2c0e67cdbe62f479d6a8664f48830fc3b1b56d11.nq.gz
│   ├── 341be9d74ab83103f86f2187462e48d917ddf47a.nq.gz
│   ├── 341d67b485fb3567d1bcaf48f2eda01afc3ff5ce.nq.gz
│   ├── 346cf8d5377ed8cc5f7c6cf126783ac6293132ee.nq.gz
│   ├── 36c45c67e6c096fca810b59b90abedfba28011a5.nq.gz
│   ├── 37d01faacec21a5fce60b2e316a8fe4320e9cb27.nq.gz
│   ├── 38089973af06acfb89bb581e71b97ff2f0513ca6.nq.gz
│   ├── 3a2438ccba347f2c95de0430fe41009a230f4b8e.nq.gz
│   ├── 3a418d422ed2ec05b9b6cddea9952a7c9f2e6fbb.nq.gz
│   ├── 3fe2bd2725b328543b9dd8f7449e7143ac05c168.nq.gz
│   ├── 3fe6e7c24cf8332a98b34f5ffe64754825375390.nq.gz
│   ├── 402562c8755f1d88f98974f5b58dd15976afbcee.nq.gz
│   ├── 41d86536694cee15cf461f86dd9aa91c9c783c34.nq.gz
│   ├── 41e5e0065eb10f084f38d887df168a509926d10a.nq.gz
│   ├── 43848da9d07eb246cac866f679199f20cca2ee12.nq.gz
│   ├── 45b17da642fb474a2990b8e01335a0457e17bbbb.nq.gz
│   ├── 45e84a5a80ea6370aed25879b5cdcd9cb0139ad7.nq.gz
│   ├── 467c878cc707c7e1df30487c25af5ec91c52df57.nq.gz
│   ├── 487ab9f164327458844076821b8558ae74b2af15.nq.gz
│   ├── 4bdc13bb2fcb18b45454090354cf7272af8188ef.nq.gz
│   ├── 4c42b9093ad2b85477d6224860cbf788197ab9cd.nq.gz
│   ├── 4e2793e984d5794b5b8517c2796140a8affa5fda.nq.gz
│   ├── 506979d38b54e7c626126e4d7e633bfc0d884093.nq.gz
│   ├── 5109e332463503ade15d835c3fe2e3b896ee4ff8.nq.gz
│   ├── 51a0974b6d22c544ab967bd94090f35cfe1870e0.nq.gz
│   ├── 52a1c9488f2bbd396b7ad57b908a56f76cda155f.nq.gz
│   ├── 55140c91d42bbfe8336df233299c9131a5f10ec9.nq.gz
│   ├── 55c72017d9bf7412f5e92f1ce876cdbd850626a9.nq.gz
│   ├── 57d5169d818d4be06e618648a03e61e3d51ebdb1.nq.gz
│   ├── 58937b189cc649434ee94ec9227df5fc80937434.nq.gz
│   ├── 5a04d61a51e4446942393bf7b5fee63703168d45.nq.gz
│   ├── 5e292a2c05e8f184efa861d892ffc1318eb19660.nq.gz
│   ├── 5f409b22ece77f52d5362ea0ee02f669eac93f36.nq.gz
│   ├── 60842bf82c71dcc071542240c0e2021eea1f61cd.nq.gz
│   ├── 6183891e6369ddce331366ec1258b86051fe6031.nq.gz
│   ├── 62613a0b1ae92b23608912d0e2104b2e15fb3fae.nq.gz
│   ├── 626dc69cc78ee10701230d07b9b628dd8e7bfc1b.nq.gz
│   ├── 63824088bf02c9f86e5bdba1b98f05c1a4763b31.nq.gz
│   ├── 65b497c5a4042e66f0d3aa64ed5756e885af3b05.nq.gz
│   ├── 6606195748eb35ce4d159017cf720b128eb5e376.nq.gz
│   ├── 677c5d33c5749b47a9943498169a7fc1c9f8a4be.nq.gz
│   ├── 6c697c7a45a3a6a4d75ea880dc1df13055627a32.nq.gz
│   ├── 6d2b2af24c8a98397874bc1a9b4ff62557587536.nq.gz
│   ├── 6d769e7ca66ff56e7eadf390c774454a368e90df.nq.gz
│   ├── 712364854b15130b678a8f4f857aa70fc39f100a.nq.gz
│   ├── 76ea9e4fb9916ba4aa77115cbe62038f60d1f063.nq.gz
│   ├── 783668229a767fa528962b2393cc758016e46302.nq.gz
│   ├── 78e0494dd035313b3b812111f3ffc44f34fa58d3.nq.gz
│   ├── 78e41219ad9cab2d35128d59f59b0a1e373b7a73.nq.gz
│   ├── 79a26217062a65e0560b809dd18a8bb0f329b5de.nq.gz
│   ├── 7b2b01a4f1cd2a6a3db007328a87536601727504.nq.gz
│   ├── 7e143cb90d4094a7375712fdfbee5c1fa082070f.nq.gz
│   ├── 7eade32e3e45700e0d7ebee727462aec79e8b5b3.nq.gz
│   ├── 806728b40263a40a10a33de8226d02d051e9e35c.nq.gz
│   ├── 80e83303592f6b3264019dc31fa4ccb94de981cc.nq.gz
│   ├── 83b7aa7f40216e588b51d134ddff810a65eacaa5.nq.gz
│   ├── 84671ebe25277bf92b4fc78feb35670d41827d33.nq.gz
│   ├── 84fc1a4df0912bf4c22abb0e3134260341bc61ab.nq.gz
│   ├── 86235afd529ae3b6ad8ad5fcbb3015f5df7e8a2d.nq.gz
│   ├── 89cd6e5a9ef3a40c86a7a02e29206f48b1978bee.nq.gz
│   ├── 8aa64a3e759753ae4f9aafcdf6d67d8d2e549031.nq.gz
│   ├── 8b185299b1c3a2c18daa37a996ca0439025234c7.nq.gz
│   ├── 8c516b6d9a451a7cb5e508f69156d45c3c908874.nq.gz
│   ├── 901ad52eb8d5b2d7add2640663b5aa35bc43cf1b.nq.gz
│   ├── 9371398ed1f97c13be547e8e8cf7821f5f74523a.nq.gz
│   ├── 941833e539eb428d21597dfc5734047f2c072450.nq.gz
│   ├── 941dcacba80a5701cbd7f08cdc2fb277fc89e327.nq.gz
│   ├── 966572fa899f2e8f20dee25ed830b141129d4cc8.nq.gz
│   ├── 9a2a48769a331fbe5f3340feb32d18d730f05a5d.nq.gz
│   ├── 9aafd6b2f5a5e6b4b6f00a1c5fd9d8a4d297037a.nq.gz
│   ├── 9cb859e11f05c6daffa59983a31cd9a2c14f10f2.nq.gz
│   ├── 9ea19469b40b620636429097cde6ed46f0da12b2.nq.gz
│   ├── a0f5ea7d38f47fcf884fb8fb146d43673f6ed4cd.nq.gz
│   ├── a15a7ef6c7acac3b1a6f2a7a1fa2faf97787c069.nq.gz
│   ├── a356bee5d370fc57339512da9579f9d29ac554c0.nq.gz
│   ├── a58aa35ff9c132ca3da845587dd0dd730962b5ae.nq.gz
│   ├── a74e487f3cf3e9bb8064645768e7df02b915b70b.nq.gz
│   ├── aaea6f95e3bdfea661ae0f8ba4041bbfd8ff006e.nq.gz
│   ├── aed35233e4d7ccb2809f082409222c350cc6d5a2.nq.gz
│   ├── af1102df789fa2619cfde19dce0c0ecec5d7308b.nq.gz
│   ├── afc0f69552e52f5ef067cd54b8116dc1f5e1f41c.nq.gz
│   ├── b11c8ff04fdc1ccad2332d2f8ffdb08cf0426788.nq.gz
│   ├── b280f1de1026e65ca909d5c3c8f6d178f62d4fb2.nq.gz
│   ├── b3a40efde1f35ac46e6b0d316f3477042193137c.nq.gz
│   ├── b45453f7e67b98cc879f926dbd7e30dced00ea71.nq.gz
│   ├── b62463c5749962c9ac05116b1afa93f9fcffb4b7.nq.gz
│   ├── b635876d8e7c83d21bc43a25b1b4c8adb65fcca5.nq.gz
│   ├── bd1fc3630532122c2196572885df45faff744fd2.nq.gz
│   ├── bdd48f34b4c517dd442ce3b5e556e37afefef39c.nq.gz
│   ├── becaa5a3931030fdde7f761ff544c64c8149c9f7.nq.gz
│   ├── bf19304cc865d72e42a8d1185198d4e3891d5f63.nq.gz
│   ├── bf65bf47e6fbc2a7a7eb4009dbfeedde89018cad.nq.gz
│   ├── bf88a3ba87fe80742eb794c2e426490aef6ad07d.nq.gz
│   ├── c45165e4b63cb65f34a0651b53355d9f7d3dee5e.nq.gz
│   ├── c578c63858aadfbab56d46c5dfd8cd410414499c.nq.gz
│   ├── c706ea36c369d9c820683b5bf5cf11d80b136ec9.nq.gz
│   ├── c8479d96349d5d09893eba0d57fa1951b7566055.nq.gz
│   ├── c84b9e6aa24674f10a1b4b5c3a09f863fc68f3e1.nq.gz
│   ├── c88af2d2f8af65248da958e157fc7960e9ddc6e3.nq.gz
│   ├── c8e65ebf7934528a5ff652b2e1ca38eb0e8c3df7.nq.gz
│   ├── c924cc63a54c812183fac5854cbb7d526f83819e.nq.gz
│   ├── ca645fd9fff416ca4b11a757129a8a8228293b53.nq.gz
│   ├── caab61b870e56e93ad247455269f37bfef456e88.nq.gz
│   ├── cc706fed3107d4978b470376791081259c0320e2.nq.gz
│   ├── ccdf348710e43eee74a006b0876f85354bb80aff.nq.gz
│   ├── ce9b980da9340773ced671d1a70735db52d152f2.nq.gz
│   ├── cee0a7a15b89ab704a8f2847f04168fb875e0b51.nq.gz
│   ├── d0082bc2470f0705261e1996a76c48a7ac16a620.nq.gz
│   ├── d10c9db95bf68f31aaedddcdd4d07fb0d306d7eb.nq.gz
│   ├── d1451c8300be1e042ba94e265db813d25ffd1c7a.nq.gz
│   ├── d285595b0805ad68644d51e0d4131cfcef3d9154.nq.gz
│   ├── d2b83d4ad57df0e0d0b4bfa4e09d3b33c815e39d.nq.gz
│   ├── d56131407564795322afa03453d4dd9400e4afc6.nq.gz
│   ├── d8285b9d2597bd89c474930c78162757bf647456.nq.gz
│   ├── d9ec7cf16b7cd9ae26971454ade0cc0e7426745c.nq.gz
│   ├── da625e516e94b9fa852cd4df1bd3dc2d4250e687.nq.gz
│   ├── dc0e6ff8224b331879c30283d5916fe08b8b2611.nq.gz
│   ├── dc7cf3b1c01b4d4c88ed6759a90d025dbba2a2ad.nq.gz
│   ├── dd3478f934dab8812af0597d6732fe01c45b7b04.nq.gz
│   ├── e0fcb479401e800bf5c0ec7055920c14e3df3cc9.nq.gz
│   ├── e37d6b29887564fcc36cd2987626e63fc1918c0e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecbe4fc6cdd5bfffef57691bfa6029fd6d323b40.nq.gz
│   ├── f0d0e22887796557ee7d09103b0f7114c1e8085c.nq.gz
│   ├── f550686294a5a7ffc958cfedab3c868531ec45cc.nq.gz
│   ├── f55e3aa0c1ece4e26e15b5a9291202e0f916b567.nq.gz
│   ├── f602813f696b582936270bdb8cd69d3872f2f4ef.nq.gz
│   ├── f677b538353fb631a2eaed2a9206566d0f3d0360.nq.gz
│   ├── f720dbdb628413d3ec51027a8b40487eb2ff0dce.nq.gz
│   ├── f7e71cd1ccefd4907fb48b50372038bb92ca3364.nq.gz
│   ├── f8d762a22375ba85ef0aff20d15068de9bb4fb18.nq.gz
│   ├── f9fafe3650f9d3fbfcd9a17f62f67591e6dfa2fd.nq.gz
│   └── fdf9586ce78d09ab49305ec41dd7dd2113db1226.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 330ef7db93f45c03ebb346be8d6984527379412b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 166 files
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

[astropy/sphinx-automodapi](https://github.com/astropy/sphinx-automodapi)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
