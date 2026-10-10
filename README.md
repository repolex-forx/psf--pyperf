# Repolex Knowledge Graph of psf/pyperf

RDF knowledge graph data for [psf/pyperf](https://github.com/psf/pyperf), parsed by [repolex](https://repolex.ai).

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
rlex download psf/pyperf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 00556e18777c36cfd96c91fdf1cd6bf70dd8c276
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 00556e18777c36cfd96c91fdf1cd6bf70dd8c276
│           └── chunk-001.nq.gz
├── blob
│   ├── 066beb8feb2f217ac9ad3adea37f01f1da11c0a2.nq.gz
│   ├── 077c77a15a7b8ecd8310d5098079176f4e7cbbcf.nq.gz
│   ├── 131721d7a9e8f98cf6d9aeef350e75f4803a5c39.nq.gz
│   ├── 1c8c22a44ccb5bf41e296de6b181b78b6eac28db.nq.gz
│   ├── 20e9034905758efc5697b75966ca36de4f3d8443.nq.gz
│   ├── 24b4ec782ae69bc445182b18c4e47e7a0cfe48b5.nq.gz
│   ├── 29ecbecbef67acae8806986b731ed639f4fec9af.nq.gz
│   ├── 2d1446c7115da46fd49eda502c15d64671919bc0.nq.gz
│   ├── 2fecd9732f99d4d3985258b5466b054dbe340b2e.nq.gz
│   ├── 3199e8450731f232dbbf9bdef48ca6733efff0ff.nq.gz
│   ├── 3547faeb4f060d31bef8c455ae4601e9bf9b8b42.nq.gz
│   ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
│   ├── 37cc4290f3dd814e24697f1e9eaf3334299bb340.nq.gz
│   ├── 38298953bc30cdc3456d2c0feaf09d9f76f35534.nq.gz
│   ├── 3a7ab11d7f96d5173bb27444d6801e3c6d57615b.nq.gz
│   ├── 3b163edbbdda8e10cfcb2a84463b8d7ebafdd00d.nq.gz
│   ├── 40f27dd7307fc3ee3254700c6374dc8a943186f8.nq.gz
│   ├── 4452bca1aa1c84afe92ab463786b1ea9f3172f3e.nq.gz
│   ├── 483b89aaba28d69e366fda0aee4f43c42594e890.nq.gz
│   ├── 48bfe74337c8d0402b7891c107f06c3913da10b3.nq.gz
│   ├── 4acd6cb783bed6ea076674da061ddc5f7232fe8f.nq.gz
│   ├── 4b2b9b17ebed33a07a6efb47787e74269999ceed.nq.gz
│   ├── 4d199c87d1ed94d4c8e836e7baf85c3eccd3e066.nq.gz
│   ├── 4d8cb43df43be9aa7cf3e271d9736e99d8c5d82d.nq.gz
│   ├── 572253aec07e212e19389560a4526dc231dfa4a8.nq.gz
│   ├── 64da6a510151706f70f933f66a8a2a74ad8aa94f.nq.gz
│   ├── 6a9cccbb6d95f235403240efc31b4fda5836e08d.nq.gz
│   ├── 6b021f5355e6e7f5aa920c7b86c44f11e5b8f73d.nq.gz
│   ├── 6d4519ecfd3a4f7eab6c27772932f45049822649.nq.gz
│   ├── 6e6aa2393c46dafdc6402d30a3d5cc6e70e6d105.nq.gz
│   ├── 6e9dbf4c64547a44300e2655ea58d159c56a22bd.nq.gz
│   ├── 6fbb4e7236f76be568c76377aba3427442f97671.nq.gz
│   ├── 773d40476470c3d568e3a59be3045116ebb36209.nq.gz
│   ├── 7a755703f91187c67a471bfd1a148584757cdce7.nq.gz
│   ├── 7bb5c28077625f9b7cc6a664d0a73f2a1a4ac6c3.nq.gz
│   ├── 7cea4414952017cc77b8741a9950fb5cb5412184.nq.gz
│   ├── 7eca372de6b28711691c6e8d40694bc86aa7e598.nq.gz
│   ├── 8138983e413a95dd3a4c2717fb496db3ac77917e.nq.gz
│   ├── 81f644e0eaa3aa92ff92d28433c50d7d3082e095.nq.gz
│   ├── 840837127865bd46fcb8fcc5e8821e6b9b8a8b55.nq.gz
│   ├── 8551dead494f3e16dd4b0f28ff383dc23e8c1372.nq.gz
│   ├── 8ce1bdbe8075610e6431dca691cb826de2d093dd.nq.gz
│   ├── 8fd4e2a1e8d04a39be2719c34ea42ded08327878.nq.gz
│   ├── 911206e8503c42c803febcd1dbae1c27dc088fbe.nq.gz
│   ├── 94981b38701f48b0d665c2fa15afb4d6d348effb.nq.gz
│   ├── 962bebe5d6cda07f17fbbea06513621a1727e36e.nq.gz
│   ├── 98b86b0aa915095b32e14b405f0cafb99c10cf1b.nq.gz
│   ├── 9a3a0d6286c063c0f4ca3e38e28fc9d8d1d27e1e.nq.gz
│   ├── 9b5669aa1f8ca3d5c68dc00d595b338d2972d795.nq.gz
│   ├── 9d3d03b55b08599deece7034711f364f7613c680.nq.gz
│   ├── a393754fd3a9e0eaf48fdff4dcea757b8f1685b3.nq.gz
│   ├── a4c36913fb2176c7406628509eb4a42f944596d1.nq.gz
│   ├── a55f7a5a28e62af660c0f147beb0def30d997a12.nq.gz
│   ├── a5fa856079f122473481733e7c40e7b71eb8a3cc.nq.gz
│   ├── a8ef6f5d9e503253bb3c86a90152837bdafa9769.nq.gz
│   ├── a9058e36bd8cbe656c693129316399bf5920d1cf.nq.gz
│   ├── ab211d47a47b8504004c2b2406575ed5bb0fba19.nq.gz
│   ├── b143f2601264ca9a1c189cb0f2575f7fb994aed1.nq.gz
│   ├── b56429708970d929823609805f639749ad09f65c.nq.gz
│   ├── b8293071b622e0f16444a6b56443b3c2bcb4291a.nq.gz
│   ├── b9ccaa9100d72feede4ca0974b96308983945b4f.nq.gz
│   ├── bfb59e4c6aeb624ab779cbf4590853999ef5ecba.nq.gz
│   ├── c0834ffc4c10671236c583c7adf840db879607b9.nq.gz
│   ├── c09e6fe44dbc5dd5c5a10a7515a45e608712f53e.nq.gz
│   ├── c77e02516c59e56a5ba41d1594636f6e7ad25aa2.nq.gz
│   ├── cb08ebed018333916b6adaa8af646bd0ebc19e4a.nq.gz
│   ├── cbc75d61447c83113e2f0d88c08395187a058259.nq.gz
│   ├── cd09f3fa2f7ac6f16cb20ed7d5ec689cba418768.nq.gz
│   ├── ce6ed079794532f683e8ed1da4b79b2ffcb79db2.nq.gz
│   ├── cf9d349cad0ead3dea434e0efee0f63bc4d9eee0.nq.gz
│   ├── cfef2e233fb4af9f8a8af63fd3ff7e0ba3168d6c.nq.gz
│   ├── d007be21f77fcc82d08ab2082c9aa192d46645d4.nq.gz
│   ├── d0f8e52685caddd27038e8daa2702024ca000599.nq.gz
│   ├── d7d9fcfcbbf0ea9323e29a704d1ba51c2d80b1b2.nq.gz
│   ├── d7ebd0328520aba8744214ebdf621d9d3ecae834.nq.gz
│   ├── d842a2d3c243b208d3d135ba9c444176ae3fb7fd.nq.gz
│   ├── e1378f2dd3246c4f34408fae4b96a2ab85452901.nq.gz
│   ├── e727a09163920e417d02be19b3194a916d52cd49.nq.gz
│   ├── e8d519a30b27418c012dfdf8039354d3863f0e92.nq.gz
│   ├── ead1a7c389469d8f6297509952f4603a3979477e.nq.gz
│   ├── f18dee203d1a351759c6b88c6e136a2875ed975b.nq.gz
│   ├── f5ddbad3a748970854f23483da5584c53c95cefe.nq.gz
│   ├── fb9aea8f0a25bf89dbe1672a13a3a8ed98405580.nq.gz
│   ├── fbb9403735b6546e8b151a85f31dc7f358fd93de.nq.gz
│   ├── fc908ac47c8da71792c803ff6cb867a8488c8d94.nq.gz
│   └── fd58a175d094560922b79ae525a3061b0d238083.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 00556e18777c36cfd96c91fdf1cd6bf70dd8c276.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[psf/pyperf](https://github.com/psf/pyperf)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
