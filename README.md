# Repolex Knowledge Graph of remy/nodemon

RDF knowledge graph data for [remy/nodemon](https://github.com/remy/nodemon), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download remy/nodemon
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cfebe2feb2054a13fa6b9c493c1cd826ffccf167
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── cfebe2feb2054a13fa6b9c493c1cd826ffccf167.nq.gz
│   └── repolex
│       └── cfebe2feb2054a13fa6b9c493c1cd826ffccf167
│           └── chunk-001.nq.gz
├── blob
│   ├── 0001598cfcb029d7fda65ab13c5577d2c44e11ce.nq.gz
│   ├── 04aa92f87ef0e915a4e7640ab418cb79a29df8d2.nq.gz
│   ├── 0701bc79b2f78fa7acf0e48ecaf80e6a03ce0eaf.nq.gz
│   ├── 07c7cc27575ac273023d724eeb2f98ffcfca7063.nq.gz
│   ├── 0823e23b48ba7e96b36c698cd0b1cbd13308b972.nq.gz
│   ├── 0a563eee173fed8d9fef0a2fc14f567ec2a0a2da.nq.gz
│   ├── 0def979941ad3fe67064cdd24cfad9af6de32b5a.nq.gz
│   ├── 0eca5c457d357f6528e263deba131848e4380154.nq.gz
│   ├── 1054b60253704f876ad69c746fae40e81e2bcff9.nq.gz
│   ├── 11f1fd714a2c866e863d47794802cd7b1a8a6837.nq.gz
│   ├── 150f97f591cc291a3bf128d4ab25db9679ab0e4e.nq.gz
│   ├── 15309ce5492dad4a934610481f624d3da1f431f9.nq.gz
│   ├── 19c91a2f3ba9a1b12b0b232adcabbf9cf2a131c3.nq.gz
│   ├── 1df2333152f716930530587cbb485dab8e6c03e1.nq.gz
│   ├── 1f3440bd6aa2b3815ae547818a41bfd8e86b3d75.nq.gz
│   ├── 249742a210fd2dcf25a09c4902c6f40bf29c9a11.nq.gz
│   ├── 256734a01f90029f50ffad8bfbb9a721ec68ac62.nq.gz
│   ├── 285e9237938d3c018221d4080f146ff3d8ba7993.nq.gz
│   ├── 2b79971f55122ac7994075eb78124e3bc50074bc.nq.gz
│   ├── 2c754c51a3b134164d3357f6bff088d817b73018.nq.gz
│   ├── 2d3a9903dc780acc3e0303bfad01bfe2ab3ff636.nq.gz
│   ├── 2ecb156ec8fe6b4bab6a595fb5f11187001c56a4.nq.gz
│   ├── 308b0d790cf4b3992aef68e8b203d865b2a504d4.nq.gz
│   ├── 308d19f0d3e78ccd78baedbcf175bf72b08c2468.nq.gz
│   ├── 3128bc6131fa72aee94fb953b8d239e90db689c7.nq.gz
│   ├── 34872c111de5d949034416b272f3eb1d64aa1d8f.nq.gz
│   ├── 380dde3acf0dd32aaf832f8e4651f4a2f0747471.nq.gz
│   ├── 395d65aa6192c6d0200f9173338de6916b896807.nq.gz
│   ├── 3c55bb559f128aa3d643e7cd36d82cb6ed7fa40a.nq.gz
│   ├── 3ce94eba701b15d00a251f02e942418eadea33ff.nq.gz
│   ├── 3d490f140dd264f98dfb50ab820456c88fe92a64.nq.gz
│   ├── 3f86459c5d1f37a0429341f69abb62a11ac9c6b2.nq.gz
│   ├── 3fbc2697d69de18e6ee558ea0e8ced688d60e47d.nq.gz
│   ├── 413fe3e8dc5345fed05074e6b73f097bb3dc85ba.nq.gz
│   ├── 415cf20f162bae5cdb8443a56d4b9013bf68289f.nq.gz
│   ├── 42be595dd8cb30388518d304966831ab7451afdc.nq.gz
│   ├── 42ce1d567c30a613750e4c0c7c746010e8300c05.nq.gz
│   ├── 4648e701849ee7d52fb685111a7f0e4323505a35.nq.gz
│   ├── 48c0b5991728fd127c3d62c961c02b4bc06c2f44.nq.gz
│   ├── 4a37389dcd77440401ef464c578875b82417ce99.nq.gz
│   ├── 4bcc8e26d978564dbbeb64de6d632c9b45179e01.nq.gz
│   ├── 4d6327eed7b4dd35d22104777496226f5229389d.nq.gz
│   ├── 4e120c58d6d4f3a1f35156b48b06eef92e233a73.nq.gz
│   ├── 4e7a18020a2440c3b68a0d8834cf7065737c7e24.nq.gz
│   ├── 51a2d8dbca15c2e45958904ee247516d96d557ae.nq.gz
│   ├── 529600c7604b62fba8ab04d6965f1e747fdf5673.nq.gz
│   ├── 544138be45652abc7bc3873341deacd3f4f90c61.nq.gz
│   ├── 55e82dabb7a27593b5f72d0b90d2d34fcf83568c.nq.gz
│   ├── 560cc71534e0439ae591ea994ab0338796565fb2.nq.gz
│   ├── 598ae63ba310e212a9cac7b2f5449cbd91e9a34f.nq.gz
│   ├── 59a34e2e9f62c32b8a93e75d5dc671cf610beee9.nq.gz
│   ├── 5af7f9e1b850e2136a33595667b43dc1a07d224c.nq.gz
│   ├── 5de9bba5745c38ec8b756a934ada8bce90ef6b27.nq.gz
│   ├── 5f043a9c31d4a7cdc0a50eb258428ab97ab7c405.nq.gz
│   ├── 5fa7f45ad215c29c9591ac5b0b7a7fc094f7dec9.nq.gz
│   ├── 6047a020c72fb55de6753b253876a7c937890f34.nq.gz
│   ├── 6337f5b5c16036559d2018960332058dc7f1c32a.nq.gz
│   ├── 64192f1474eb8f859d8d7c42d715d9554224d56a.nq.gz
│   ├── 65800872d11b5fe861add16be08cf024fcbddc2d.nq.gz
│   ├── 65c05c57488c53e41682a8765f32629ff3e5e6d1.nq.gz
│   ├── 675185e2bef6c76a3fe2507eac0ba4c8b1f1678f.nq.gz
│   ├── 6ba6330f33551e3378bd53ab17d8a2c3a3e56b65.nq.gz
│   ├── 6c65e50c3819eb70941b2679a9230291d118cde6.nq.gz
│   ├── 6c77a12aeee2f68df8895db02c3d4b24eb489396.nq.gz
│   ├── 6e1caceaa1e574fac2323d5e78ccf1f226bd832e.nq.gz
│   ├── 6eaba7e12945a931458fe2d875fc39f7d3bbe0bd.nq.gz
│   ├── 6fa8ca74ab4b09e47de98f91d95a66beeb1d4cc6.nq.gz
│   ├── 6fc4f5ff30555433e61040f1201d7cf423e987c1.nq.gz
│   ├── 71369bffb6b04679c3585aec7c764a0c8276302f.nq.gz
│   ├── 72a71e920edcea714d09812649e2e1ac158668cd.nq.gz
│   ├── 75619ba40184df7761f8a2677633d9669d990a3c.nq.gz
│   ├── 76818d03d3c08cb324c70ce89758ec1d95e85b8a.nq.gz
│   ├── 7933ad429fbe635f74cd3e4070239faf9daa3258.nq.gz
│   ├── 7ba4ff2a393f67640413a75cc7ff066922b1b956.nq.gz
│   ├── 7c57d32306f04986477f4777431b7200d938c81b.nq.gz
│   ├── 7c775d6df2fe91d648ca2623da468baf7002c77d.nq.gz
│   ├── 8057e91c4945e17e58e844b38d5edfea4b3a7032.nq.gz
│   ├── 840a8a9238d4e0b464cdfaaf009c9d5c03a7a221.nq.gz
│   ├── 84dcb122af08159d4135ebbf530f11b3129b988b.nq.gz
│   ├── 858db5cf626ec1077adbb637816c8b562089a516.nq.gz
│   ├── 89db029b09e005e9e102a085c93f2b261eeb88b7.nq.gz
│   ├── 89df9d062bac0c3dbaf51a83ac9aba99d6b7dccf.nq.gz
│   ├── 8c1b59054413d7c17868e8935a186878ed6e2238.nq.gz
│   ├── 8d2943f43c1afc38c46f96c2125eff2c721babd8.nq.gz
│   ├── 8fc07caddd72eedc4570adb2c7c4ac775e96f1d8.nq.gz
│   ├── 8ff8e15c9d956d23919d612e778ee23521ae6ccc.nq.gz
│   ├── 92651216d2f127321b2b1cf5a08a46a92325cc73.nq.gz
│   ├── 937189a89ec8ab3da03f0d2f2ff6a79019608777.nq.gz
│   ├── 938964a28547b5ed1c75fc289134e8a3091b9b66.nq.gz
│   ├── 95927cf480ea30db913945fe85fb3b97579f8ba3.nq.gz
│   ├── 96f318ec34cfbd04291aae667eb7b51df8d89c5e.nq.gz
│   ├── 970528b37be898cd7cd35a29d282d3daaa4faaed.nq.gz
│   ├── 9839b5c7cba45e7df6217b23fe82bcb5cefc7dcd.nq.gz
│   ├── 98d7d7f7ed95fd8662f82dda3d16203f0d76e580.nq.gz
│   ├── 9af56fe3437237b08b69c4ac9878565b893dd09c.nq.gz
│   ├── 9b153f3c00753366eb9b6e066f96bf3832e93c36.nq.gz
│   ├── 9fe3e2b5996cbd408c82d28c3788de95aac0e530.nq.gz
│   ├── a0b6a1137b97e488848c37c41f3ab690a08234f5.nq.gz
│   ├── a0f0343fe1a7783780ca3be8d05327dca9387753.nq.gz
│   ├── a20c47838a7ac9152ca40472a83d93027fb4cfc3.nq.gz
│   ├── a6ac854008f2b3caa79e3453e4b3ccfc9cf4d923.nq.gz
│   ├── aa07556f68482b16b2baac273cd3a26df0bce522.nq.gz
│   ├── ab2ad6c0f2176e76a7fa4ba2bf731e3634254e32.nq.gz
│   ├── ab5fc28e72f5b1b0a70af20d269a2efb79a39e45.nq.gz
│   ├── ac5e5be70534e7e3b5cd3278b558e429fcceaf02.nq.gz
│   ├── b2d317dc8dc8e3d7628bff4359beef057f7dfb53.nq.gz
│   ├── b7514ed1e000516fe97262f100f899f13082d1d7.nq.gz
│   ├── b88a0cfb51bd5003e7b9fc37e353448a6194bf6f.nq.gz
│   ├── b9bbe32d3858103687966cd54c3fd100856df530.nq.gz
│   ├── b9c3dd19b8e58714e539c45b1d12d8d8e82704a0.nq.gz
│   ├── bca98b5e614e6f74f98e19b39384a8f694ae7370.nq.gz
│   ├── bf9e80991e4e0a553866499b96877328a2b96042.nq.gz
│   ├── bfa4f0b425db55f53c2e0557c144932968a11c8d.nq.gz
│   ├── bff03f470700365f15249417fe291e941b413513.nq.gz
│   ├── c508e4554cd6807e589ee0b264a0c172881fc944.nq.gz
│   ├── c5564b65a4ab65e025d7cb1287d84d6d6406ef95.nq.gz
│   ├── c78c435cdda56d7f231dbaea7ca13b32459f58d0.nq.gz
│   ├── cafe685a112d33947d986be8cc156e0cab38068d.nq.gz
│   ├── cd9b301dff396010b31f3e62e2c3cd580d886591.nq.gz
│   ├── ce94710b9cbf58bbd3c8febfcc12ce4b643d598a.nq.gz
│   ├── cf8df0d5105aadc8a409cc4a6c2cfee6b1eb5d3a.nq.gz
│   ├── d0ac7fe14f65bcafebe0ae971834fa4d6beb28e4.nq.gz
│   ├── d0d45508f28856c3ae66cec764b2817f906c22bd.nq.gz
│   ├── d0f510447f57b96aad5bf60c59f6cd3d741bfb8d.nq.gz
│   ├── d2d53825c8d5f742f87e029d0a88d4c2eee5c8fc.nq.gz
│   ├── d466447a9c70737c916c714ee2c3e6cd4445ea02.nq.gz
│   ├── d77141cb5f4b08384f3a69650fd702e6d8f094a7.nq.gz
│   ├── da9e42ec46694bb6080e28653b3aa091aaa0ac7b.nq.gz
│   ├── daff6e05389aedf0b669bbcb32554599692cb121.nq.gz
│   ├── dbb953f3f08cfae5ac41f96a746291cab4acbb73.nq.gz
│   ├── dc95d346bf505e6edbf54a839e45ef76ad934dd4.nq.gz
│   ├── dc9cf4e0f9970696a049d246eb44af2e0a46b898.nq.gz
│   ├── df14235a3dfcd4af4eec53271a56b1a223aee2ec.nq.gz
│   ├── df56eef2637e0247c92c19feb949de4fbccf4e03.nq.gz
│   ├── e10345f78937f7ab1742cc16168cafcf7cd6be87.nq.gz
│   ├── e18a6264148cd23d279eb3270774fca274c2151e.nq.gz
│   ├── e2ff9e3821e9e960d5ecd5fc745829930f4de79b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e81bdb30faf9212cde5450fbafd4eeb5755d8060.nq.gz
│   ├── eceb49005dffd1888c8838fefaedd9b3050e758e.nq.gz
│   ├── ef97139ccebefcef6b8e938e86f184980e8dce1a.nq.gz
│   ├── efc3382ef38e269516d61e813c49a8d4539688c9.nq.gz
│   ├── f0425825db6bd5888539b62faae6d0563519e06e.nq.gz
│   ├── f249d171d583c3990e037e21133fbac8d1e36b7f.nq.gz
│   ├── f2c7de3df39d1fc6fcde147d1d873ac669959253.nq.gz
│   ├── f4d5a7bf1140d7131d2bf518ef16edff01e6d9eb.nq.gz
│   ├── f579a202498c46a4fea362b481d0ab4abe1f65db.nq.gz
│   ├── f62587368730a0d7288d7afb80497154b228290d.nq.gz
│   ├── f72b25ad351ce258816e7233bf3093ddce75e1cb.nq.gz
│   ├── f7ca20a864cc7fe0570c93708478202d8f052404.nq.gz
│   ├── f92d0cdb7fe4d3796d8a3995db3d1246190b08ce.nq.gz
│   ├── f9962a61b42032b849e33c7409aef6b89ae42a1d.nq.gz
│   ├── fb991ae890932a81bcc47dec61f6f6b525b14deb.nq.gz
│   ├── fefd305de8669d0aec8783cbbb64ea4f38da1fcf.nq.gz
│   └── ff37cae2b7b4f24df2f7db5a32085efcb59d5171.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── cfebe2feb2054a13fa6b9c493c1cd826ffccf167.nq.gz
├── filetree
│   └── cfebe2feb2054a13fa6b9c493c1cd826ffccf167.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 165 files
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

## Source repository

[remy/nodemon](https://github.com/remy/nodemon)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
