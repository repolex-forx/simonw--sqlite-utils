# Repolex Knowledge Graph of simonw/sqlite-utils

RDF knowledge graph data for [simonw/sqlite-utils](https://github.com/simonw/sqlite-utils), parsed by [repolex](https://repolex.ai).

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
rlex download simonw/sqlite-utils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9c66bafa52ae23d40499c74b0db3b635bcddb876
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9c66bafa52ae23d40499c74b0db3b635bcddb876
│           └── chunk-001.nq.gz
├── blob
│   ├── 0117862596326d7a5e72f5342e2c4d2ef77048fe.nq.gz
│   ├── 029a7fc495bbcf4dc93503039a0d47b063bde2e0.nq.gz
│   ├── 02b28c3da186862da52c34220272e55835e8347d.nq.gz
│   ├── 04b5bc31f53c86bfd6483b2d81ba9bc3a074626e.nq.gz
│   ├── 064026a0b082e6fd5a4a9db708960d8f6ceb6792.nq.gz
│   ├── 08c2f81a1b0f37ba6fbdef850610c9976febc589.nq.gz
│   ├── 0df72907ce741617b035e1770a239ab201a100c9.nq.gz
│   ├── 0e8f332bcefc2bba48385feee030b502c07db625.nq.gz
│   ├── 10815b4048693314f88a95b33204de0d3826dcb3.nq.gz
│   ├── 1230b6c8fd6f8c537a81f39f33637a91da0f7393.nq.gz
│   ├── 1333f5d9f89ee7f2a222da28b1127d6515e351b2.nq.gz
│   ├── 1aab04e34e5d89abaedbd980604ee39a6d91e44e.nq.gz
│   ├── 1f9e9ed15d7125c8731461863d387790a452c9f9.nq.gz
│   ├── 23aa9d853b4823667ddca40498ff7fdf85b4a804.nq.gz
│   ├── 23b23bdc968623c396d282e628b5bca6fbe5052b.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2afa7b730b4a7b3356b365f3eac4608e084e55a8.nq.gz
│   ├── 2b11e365931add69c89ef67589c55d330d195fe6.nq.gz
│   ├── 2b700990a105d2c74e83651602a8215d54141768.nq.gz
│   ├── 2d7846e5afbe897956164a3e75c82553da1f9943.nq.gz
│   ├── 2f6a8757066456d124cf525aee81eb1df84c4434.nq.gz
│   ├── 343424d0d783cca04f39a20533cc0c449e49c5be.nq.gz
│   ├── 360a4436a99fbaf93f5beb10144ce07cf4ab9cb8.nq.gz
│   ├── 3f13c6bcc2981ce7d974f124a5f983ab57fcb9c0.nq.gz
│   ├── 3f350e15be1394c04f5f50a85c001330d7ecaf3f.nq.gz
│   ├── 412b66c2c5f1bdda58c0278cde559ba136d73a78.nq.gz
│   ├── 445f50b0f197c4862847f469127c14b835d8274b.nq.gz
│   ├── 44cc098af5e34c283f43fa8fdb19f579ae3ac078.nq.gz
│   ├── 476569ed5882deefae5ed9b21848306d9d737f8c.nq.gz
│   ├── 4dde7e4c56ff26d6cc787c0ebc9344051dc5ae6c.nq.gz
│   ├── 4e7cf39b36c639b224669a80620ae01abbc98fe4.nq.gz
│   ├── 5578ae3abb410e7f83a5a22b32c17cdc457dd82e.nq.gz
│   ├── 592af4c3db0039dfc8697f7bb1a12b7500093b54.nq.gz
│   ├── 5b5d2c65954d89bb38c30a402ddc12b5d463be38.nq.gz
│   ├── 5d024e1a249c861bde0b7543093c202afcf2ec4c.nq.gz
│   ├── 5e29506b90faacce09c58d320cd14a27efd1fefb.nq.gz
│   ├── 62d46421baf0bda54bd45f814bcd3ee776b2f223.nq.gz
│   ├── 63f0570b775adcb74f8d65538fc1f01fe8a71e0d.nq.gz
│   ├── 69397baa23265251bf06bf9547b17cbe4eefa0c6.nq.gz
│   ├── 6bc06c8ff2471e8e2b0a5c9ec838827ffe0579e1.nq.gz
│   ├── 713f81e70ff558ccbff498d71dfe9a5780027a03.nq.gz
│   ├── 7347534356fac4c66356b0ba757ad2f7f1114c32.nq.gz
│   ├── 7377f4fd6c5c8dc8020e93af55ed6fe4c249e698.nq.gz
│   ├── 73d1acc6662463171592f7143e8856d48a300c29.nq.gz
│   ├── 743988736426b45c8b6ef93f3fc9eb703b43c197.nq.gz
│   ├── 74a089cc0fd7f715e7356df74286ab11dad15746.nq.gz
│   ├── 75f5a7613a4f8a5b67b4a45346d7a18251743066.nq.gz
│   ├── 78c33b8aee09c916308dd514fbe4df0348da4810.nq.gz
│   ├── 8274557faf0584075ed3666c291589ca459632f7.nq.gz
│   ├── 873871308cfba8dee7170f88a54e377b2a6ad81a.nq.gz
│   ├── 87868650dd7d421a99d93936fb3e84ed309cb13a.nq.gz
│   ├── 89a318adf9206e9ee3823e46859bc47c4bb4a24b.nq.gz
│   ├── 91fd24ddd215cfcf600c9aabda3e73c041823fa8.nq.gz
│   ├── 92650e23b6b8013ec72beea6539b0d16c19f3cf1.nq.gz
│   ├── 92b582a4596fff16fe37860280e3088b6c1261ee.nq.gz
│   ├── 93c4daf1b64aac6e0850202cff7d2e9efdb6fc53.nq.gz
│   ├── 98dcca0c2836ae53d67260be8a5431b855e461bb.nq.gz
│   ├── 99588eec244c552323e5551e536fcdc91e266c71.nq.gz
│   ├── 9e4799cd9e5b8baf05ca253d9cff973259d08124.nq.gz
│   ├── 9f59d59e11f8b761556f880b564e26ca43ca9d10.nq.gz
│   ├── a1cb09b53e194aaba092865f7d3c75c532c1fd77.nq.gz
│   ├── a4eb8600ed1af5fbb24c81cdb4307d289097dc81.nq.gz
│   ├── a8e7f9d76b74c1eba1af76021150169f74ff78cd.nq.gz
│   ├── a9341b8754ba2e7d69140524c7a4c04e6748f57c.nq.gz
│   ├── a9fdf29d3c10cca3a2faa1a720e6aa03cd609bbd.nq.gz
│   ├── ac0d9249b6fee273d3f014bfac77ba525e618eb8.nq.gz
│   ├── b3f03c9a5806273258b595087fab69ce8de05567.nq.gz
│   ├── b738df952dfea9337dc0eee90377fc8b45a8b087.nq.gz
│   ├── bade68681891c754a0fcf61562efda6761714e16.nq.gz
│   ├── bb58df42074f5f40a63e0151547b959452144838.nq.gz
│   ├── bfdc9877d9acc165c0342befa33f2e8f769538cf.nq.gz
│   ├── c011d9bb0cb61883808f37d74c317a20644fc22b.nq.gz
│   ├── c23090283b17569e5c81cbecff7fa2c082c3a323.nq.gz
│   ├── c444c641a5122f5e3ee1ed2d32b956f013770541.nq.gz
│   ├── c53d642223aa265d9dcac4032d91817177f2a681.nq.gz
│   ├── c5c9dcdb86562d51973dc1164ff179072a44e336.nq.gz
│   ├── c6a548c53143262ea7671ce86c655e5f8a528042.nq.gz
│   ├── c7a5612a2ef57567bba245f632b2e6179642345c.nq.gz
│   ├── c7b05c480cae625ebc3d62e554fb6b9e5ac6628b.nq.gz
│   ├── d017f1fc2d963fd83b8c4165dd7cd97580a31bb4.nq.gz
│   ├── d28a099b5b7160fbf5f8ab5aec68211e7cfb7ed8.nq.gz
│   ├── d4f28d37e95c4b5ae57cc8ee4eb29d7b864de6d3.nq.gz
│   ├── d515642a59bd6fd58dca25fc62ae57aa24f7895f.nq.gz
│   ├── d8b846e7110778a6e892e58604ba8810045e2975.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e3c921266e4bf9da62b42c235c1f00c317ca1283.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec81f2f05817ed9ef89378a8fd1343d832797176.nq.gz
│   ├── edd51745f42cc63f1371b51b2c0043ec90c86a3a.nq.gz
│   ├── ef202bee360fc1289216e57419e21bd4498d13d8.nq.gz
│   ├── f0bcdbe0c4a4ed2f260953e75d3daa6778b2d269.nq.gz
│   ├── f10b02a9f73e5286146f5a22c8b51d0da709658b.nq.gz
│   ├── f190d4745cd4409e529015a3bd7a1e6247441a0a.nq.gz
│   ├── f195cba578509745af484f94e664dd7b996b13fa.nq.gz
│   ├── f5b3276e94467a05b10522e9ba9f9bf3be1030af.nq.gz
│   ├── f8418c47f50c2ccee6ea86a7294e1dc29e6a0f20.nq.gz
│   ├── f8550411a6ccbdfdb57e1dc1e13a2afeba946d08.nq.gz
│   ├── f916c658d1e83c7b883d7d3a49c90ed5bced462d.nq.gz
│   ├── f96cfefafba80c83a1310abe39fe50fe26a43222.nq.gz
│   ├── fa419ecf7dbdeb552b3f994516b4bb5d0475d498.nq.gz
│   └── fdbc71c9a9864c94a8a010d17fe5204e49ad2d37.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9c66bafa52ae23d40499c74b0db3b635bcddb876.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[simonw/sqlite-utils](https://github.com/simonw/sqlite-utils)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
