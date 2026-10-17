# Repolex Knowledge Graph of mahmoud/boltons

RDF knowledge graph data for [mahmoud/boltons](https://github.com/mahmoud/boltons), parsed by [repolex](https://repolex.ai).

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
rlex download mahmoud/boltons
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4e5faa3d7e4008d89e0d8bf1ea87b6d9a061a16d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4e5faa3d7e4008d89e0d8bf1ea87b6d9a061a16d
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a930a6b26d714b1037fff3059293a6a23ac0e6.nq.gz
│   ├── 0310f86855d10320903cc4a14b1049e55ce3c635.nq.gz
│   ├── 0a86f57e42650fdd2a8fb3413b682a3e51cfda95.nq.gz
│   ├── 0e383e5c7de1935ed6d0da07735276b472773888.nq.gz
│   ├── 10cfbe9801fbf532d17be44c0ed1deec8f9a07fd.nq.gz
│   ├── 144c265eff5437e7c755723c10df9c6695b93bbd.nq.gz
│   ├── 156a698bf282ad03b9e074a65402e9a7a4db3670.nq.gz
│   ├── 16d18d4b9078d8864477cbe445d142addfae7134.nq.gz
│   ├── 17c515540610465bd0935c5f06e5ba21ff258fa9.nq.gz
│   ├── 19b678a9dd04bcee6abfab8785619f7477c3a84f.nq.gz
│   ├── 1a8c5f434b513d1ca29b0bf3a49b087cc3e29b47.nq.gz
│   ├── 1d6a16637d5d1ddacf0481cd01380b80f2686d8d.nq.gz
│   ├── 1db18b462ae47ec4a53ba990634d539b1cfe1c8e.nq.gz
│   ├── 1eb285e3b98cb7e5d4cb9c6b78b33a58b1365a4c.nq.gz
│   ├── 1eb8e419c0fcfe0bc3fe33642a9366817df27e53.nq.gz
│   ├── 1f767d03f15f6ade5af53bebb5ba8a7e127a1484.nq.gz
│   ├── 1f8b44e36506de5f82edd33e8d6db98899cbf3b5.nq.gz
│   ├── 203e8ac277d91441b2036c706ee80ac20acaadb8.nq.gz
│   ├── 228500080be5d9a7cdcc117bbdeb990273702621.nq.gz
│   ├── 25b486e3a4a59a46e7c616faa22c523630ece4cc.nq.gz
│   ├── 2623ea35935cd027951a36a9b2c3c690b872cfb9.nq.gz
│   ├── 299d105955a2f303190f2e52b75d8e81b590852c.nq.gz
│   ├── 2b1d9711b2cf161906df9cd3585291f87ea69385.nq.gz
│   ├── 2e0b80f09c732715895987ceeb2f825ea76debd2.nq.gz
│   ├── 303403493c2421f5950285b012f777e3742ec463.nq.gz
│   ├── 3151464bf966c954d9a0de94c89c27a349663fb7.nq.gz
│   ├── 346d125e1ec20fabe94b7f53a1cfe4fcf4acbd1b.nq.gz
│   ├── 3659d088f16825d651788a32281ec9994e1457ae.nq.gz
│   ├── 37ce8a6e978c33af998869caa4f4fd1c8c288c27.nq.gz
│   ├── 387f84f0dde1e0d6a80a7c0518e39be4c6949855.nq.gz
│   ├── 3948aab6d488ae3356b202d652bfe9cadfd97dd1.nq.gz
│   ├── 3e37afd9ca4fbc5828700edfd1c2e75badf8bd4d.nq.gz
│   ├── 412061832f27a51abadb65b376c4b078e69078ad.nq.gz
│   ├── 41cbff6d3b93ced42ba7512fd7ae3b810b77cef4.nq.gz
│   ├── 4c81fb975063160dba6a16fc2021b903976789ad.nq.gz
│   ├── 4fbc9a7679e0910db4196b97d1a26311ca3af0d4.nq.gz
│   ├── 53f2e2f12009197333bf1490cafd40ed80032a14.nq.gz
│   ├── 540a15bbae18562d429569a508db81fa226be48d.nq.gz
│   ├── 5b8fd12a37ab7f0f13db6fd53a68d4a5cd68ef16.nq.gz
│   ├── 5c0e871b45ad07a2be50712786c2408276ce19ff.nq.gz
│   ├── 5dacc4e8311c575cc0f34ca2dcebc73c57d31868.nq.gz
│   ├── 5df4aa21c2e13053b86877b627da23739df2b86f.nq.gz
│   ├── 5e5feac131f443c19088625c8a132b8b8031f423.nq.gz
│   ├── 625943631406a9058bb10762f4588e25a49cd2c8.nq.gz
│   ├── 628d9ed768baac40572ac6b5a1f6abd2215fef3e.nq.gz
│   ├── 68c5fe98ea6c80be2549b14a08e254f069e43484.nq.gz
│   ├── 6a4c9d2496f53c61c99ae7c113e6ed94b15b038c.nq.gz
│   ├── 6c56736f98156e3b1aa63d867f23f400601bab8a.nq.gz
│   ├── 73c1b54d69241f0c6519f85c59c5be3e245326eb.nq.gz
│   ├── 74441c7e39dc5a666d76ca559f2ea6b80b3372c6.nq.gz
│   ├── 746b2fa34663835ee34c92dbe6e35981124ff7b7.nq.gz
│   ├── 76afdec094440c01613160217fa6ec1503835ea9.nq.gz
│   ├── 785791224afc93709e012bef26c46f4dc0296353.nq.gz
│   ├── 7bfcb7e7d2dd9d4db8d5188bdf6cbaa4eb9d1f8f.nq.gz
│   ├── 7cb2ec449199954fbe130ca1a885c7dde7a5546f.nq.gz
│   ├── 8183238ab1c7f1b7f360cd8536d5f4f75e3fe170.nq.gz
│   ├── 82f08ced13392c5bed123e98970d7b2065fe611b.nq.gz
│   ├── 875e2e2b0412bc7fee0a11726371bac402566ee5.nq.gz
│   ├── 87826a215314b93f332a47a60083683143224f0b.nq.gz
│   ├── 8eba3c1f43f66bb2190a4d3bf3e9359641d6e71e.nq.gz
│   ├── 901f657854bc7895c07fba406b8b6b6d40633908.nq.gz
│   ├── 99408803542d943fcaf2753732cfdac04fa6bd76.nq.gz
│   ├── 9b175210c98a376079bc77de4374c0d4d1e8444e.nq.gz
│   ├── 9cc530cc5359e63db2c5e6380ea0e694267a2b00.nq.gz
│   ├── 9ccbe4715c2ef611801003a381db095883a830c2.nq.gz
│   ├── 9d5f80fe1bc4cb5c884309a4f0d6974c5b42095c.nq.gz
│   ├── 9eb162a524a03cb4055fd81cdf92708e160d1480.nq.gz
│   ├── a1861ff38ce043ebe2beeaff3b99428c5c97ea00.nq.gz
│   ├── a1f9dc01649ab42e1f32d70af4ff3677f212cba1.nq.gz
│   ├── a2f9f97d51ecdba688385fe0bfa8a18df0f3d7de.nq.gz
│   ├── a54a71e4d5f5a0dfc5196ffff9f35a797a39fead.nq.gz
│   ├── a8cb2602f31b5920c67c03027684b01c22bf371c.nq.gz
│   ├── aa653f22ff67e4d05f3331f5c6f2d1d779b63a6d.nq.gz
│   ├── abf5e09a5ccc68e53b1bdd78b153a7d7c4e64f1f.nq.gz
│   ├── ac9317b2b52b37cb878c1fb185243022cb6bf84a.nq.gz
│   ├── adefc31a36c6740f087c3eac8df358dac3e3d2ce.nq.gz
│   ├── aebf4c405d0e6a04b67a1dc76cebf4fe4fa78cc4.nq.gz
│   ├── b0b310f172ec46e1f52347d270b18b61ad7551ab.nq.gz
│   ├── b3732b25871b405cfe3c3df944571b7ca63d2e54.nq.gz
│   ├── b5bc6e1218a1a792c2b80a3fab4cefbac69b9f43.nq.gz
│   ├── b66fe29708504e31aaab4f16285aba8e56d8e1ca.nq.gz
│   ├── b7cbbdc45f5f7ab199c9dc74542ffd1fe869a9a6.nq.gz
│   ├── ba5d0789d8bc2865f34786bda3a3f3c7ebcd7299.nq.gz
│   ├── bd2dcc7f6c4696bd352048921ad1bc82f5635c91.nq.gz
│   ├── c3cb987d46616dbc984fa765b678632c49d1afc5.nq.gz
│   ├── c4b39ec4929a1064c6dd7e3248671e7777432d1e.nq.gz
│   ├── c9a028150f9eeaa1e4b83614e9e6f2e5f2e7b22f.nq.gz
│   ├── cacdb8aa07458c319e4cc2dcc1288177ebe02e19.nq.gz
│   ├── cfed65ff3140f65529c9a9767cabd1c9b46c8f85.nq.gz
│   ├── d85cc83b80d63b1b47c95e4885b53c9f0760a03d.nq.gz
│   ├── e0c73bc92b98645c5e749f405ebf8a3c8407aea9.nq.gz
│   ├── e134b1b5b88767df7911566a079d19b508164cf6.nq.gz
│   ├── e2c9a0cfb653756cb81f79695b6c833bc23f1af7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e85443851a3db93f84d3b0203abb365c50111792.nq.gz
│   ├── eac8abf9edf2aa793c96f5c48ddf98f92d2ad208.nq.gz
│   ├── eb590483b5f9bb1ad3ff67c4b0379c1f0f87cac1.nq.gz
│   ├── ec46164749d0ecb1f598cc89fdd82a027b267a30.nq.gz
│   ├── ec6a3a685c5b351cbf06a5f81e66e6037aaf2741.nq.gz
│   ├── edf30c69b9e8e83cc74bdd2f55d607dd47aaa5ea.nq.gz
│   ├── ee13a176e0a827835765276bd8b69db0e8cfd12f.nq.gz
│   ├── ee37f38e1fc2d300acd97b13b13da1de8caa5659.nq.gz
│   ├── ee51360c8604c2c8e7d78e2af9e501743855ab33.nq.gz
│   ├── ee8edd5eab7095492339a6346a08350f94340b84.nq.gz
│   ├── efab638a06e9f7145da00c389967cb284238dc9f.nq.gz
│   ├── f0c71ef28a1a49577ec84ba1ccad834a6c01302b.nq.gz
│   ├── f6e4e4c28d0f0a394eb6deba7fec1f92b1344059.nq.gz
│   ├── f75fe46a49e1bc46c744ff41aa4eed70380a34a8.nq.gz
│   ├── f81fdd387a68e4372be4e48dd864c5607c76c0e7.nq.gz
│   ├── fa3262d4d8d21207341f3f1ae4ec9b26eb866fea.nq.gz
│   ├── fa731179904c74e9693a7ab19df5a00d1bb6ea06.nq.gz
│   └── fab2e0679b576c6e457066f37e2c97137c83cd78.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4e5faa3d7e4008d89e0d8bf1ea87b6d9a061a16d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 120 files
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

[mahmoud/boltons](https://github.com/mahmoud/boltons)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
