# Repolex Knowledge Graph of jupyterhub/oauthenticator

RDF knowledge graph data for [jupyterhub/oauthenticator](https://github.com/jupyterhub/oauthenticator), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/oauthenticator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02344def2a5e57b9fb25424dd806bcaff8de800d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 02344def2a5e57b9fb25424dd806bcaff8de800d
│           └── chunk-001.nq.gz
├── blob
│   ├── 017af1aa63420c778d6ac3f4f47027a92efff506.nq.gz
│   ├── 04677f838a1270733382949592160301b4dc16ac.nq.gz
│   ├── 0477f16d21f6846aca4d4a140adaa09200f2faf6.nq.gz
│   ├── 0d88b7ce12c2fd0134f19e094bb04971826d8cf9.nq.gz
│   ├── 0dc89813dc10ed07777226c26d348a19ce3afb93.nq.gz
│   ├── 173fc0034b6bf1eb599fce485d8fea7e6bd3855a.nq.gz
│   ├── 1b1bf0be2669bb08c542121d603134e7ccd03e7f.nq.gz
│   ├── 1bbcd8539e9bfc2d88d0ea56b0e220cc596f115c.nq.gz
│   ├── 1cfaa161097531aa5e3ceec4cc9d04285cbccb7c.nq.gz
│   ├── 207e7cbd4ce9a2b48329731521f40b44d9f90133.nq.gz
│   ├── 20f57a2b7889a5091bd2a31168987b9df84cbbd4.nq.gz
│   ├── 25e9e0bc8813a22c0dd8a30068cb8f14358cd628.nq.gz
│   ├── 2852361fe99105f4d6d7217f24f49ed7e4991bd5.nq.gz
│   ├── 30a494848993df85b9e52c2c0a84889e79bfc0ae.nq.gz
│   ├── 342fbfea0cca17995fe472fe69b876fa53d42dcd.nq.gz
│   ├── 3801f8678d3e808b8bbf7d5611a6885b2801bd52.nq.gz
│   ├── 3d5d14b39d7c067e440582112dcd650b7e3c3566.nq.gz
│   ├── 3e1d8f1ded5b67a0e73fbb6f1534658bfcd1d8b2.nq.gz
│   ├── 3f0c46466e71a04f104e920d97d52275307f524f.nq.gz
│   ├── 466ad6d8f5fdd3eb3d2bd1800444e5895a2f54f2.nq.gz
│   ├── 46deb6f3de38f9c26653178cc1aa1a575665a959.nq.gz
│   ├── 4a80a2f43416239fc84864116ebe89ee082df9a1.nq.gz
│   ├── 4ac37b4e2a201bb6196fb3a306243c94fc476a3f.nq.gz
│   ├── 55c10d0892140becbffd8777d6ef40e6aaa501ca.nq.gz
│   ├── 563db34f7f9238f3e43b6adfb385af911605dc4a.nq.gz
│   ├── 5718cb952647ef958988c7acfe53644ef6352568.nq.gz
│   ├── 585cabacba632d544b2fb12a9fbcfe017d62a300.nq.gz
│   ├── 5a72351a5a2e55d20b501507693abb95f519993d.nq.gz
│   ├── 5bfaabe9ecaae67414d89a9cf853d22f00246455.nq.gz
│   ├── 5e90b9bbe32cf4158ae90f452340f86a943766d7.nq.gz
│   ├── 60c9f09a55322dcfd4e5434fd572d32592eac85b.nq.gz
│   ├── 62531f76aeaa3a24e11fd0ea0b725e43fb49d899.nq.gz
│   ├── 66ace99c84e3e99bc2eb2b2ca41ee3d63779b2f7.nq.gz
│   ├── 685ff9fa89fd16347a8c91287c78022ab4e47ec1.nq.gz
│   ├── 6a5c9edb5249cc7d476401914252f241b94911b2.nq.gz
│   ├── 6a836f2e0e2349e3c042a5f0f8d9b5fa5786de59.nq.gz
│   ├── 6b650b86a12ed9e386ddee032de134aeb239f0e1.nq.gz
│   ├── 6c6663df0daaf5ec102d26275770c32610619509.nq.gz
│   ├── 7314b90b0aabc94e0da9cdf92f4a9a802bd28b9f.nq.gz
│   ├── 7360aa53e5493e798ace326e93122d403a17c743.nq.gz
│   ├── 7450dcdcfdd475a488465a51fa91f7c158de842a.nq.gz
│   ├── 7aa7b6083429c1e47090fe1ac18779d923b67e52.nq.gz
│   ├── 7f4c431d9039fcef6ffb2a4f44c98467c693b914.nq.gz
│   ├── 7fb7d89c87429bb512f6e4836b7a8047d9aeffdd.nq.gz
│   ├── 80373bc73a69141a4e5fa6d328938d090cd9b409.nq.gz
│   ├── 80b26e6a890ffc13bdf3b34e386c223647daeb36.nq.gz
│   ├── 85f1346c062e4834ccb1caa60a8fb2644e97d03b.nq.gz
│   ├── 8735f126e73dc28a3185bb89bd2ab5980506b341.nq.gz
│   ├── 88f71a0403f3a1d9fb9571c16098ef97c4780b1b.nq.gz
│   ├── 8bfa17996c6c06dd862404d3b920f919aebf3373.nq.gz
│   ├── 8c7cb1772648d2b4edc6bf9f58a58a2a84e75b30.nq.gz
│   ├── 8e022e194e3d48f704fbbdd9c45a104f313391cd.nq.gz
│   ├── 92ac5b3b19d8f4b361346d1f0337333853813561.nq.gz
│   ├── 957e2a722400c76a9035f83d5aae1770ac8af724.nq.gz
│   ├── 9f1d8af52405bcfcb4de50a5ee9f724cbf37a979.nq.gz
│   ├── a7a4e61b76ef38ddfc30a3e157aaae6674120bdf.nq.gz
│   ├── a7aff073b6cfdd69d007ca73a3f1967d7a8d5db0.nq.gz
│   ├── a86e3bebc0e5a9171164d4ebce9c2da21bc5bd2b.nq.gz
│   ├── acd1dbbbc11efc4b604b4448a74e63c00b6c00e1.nq.gz
│   ├── af2565200fe7fd310f34092bde748b2365ccd9c6.nq.gz
│   ├── b085c7e1655d9fa561334d32708b588a363b39af.nq.gz
│   ├── b1e65fc7ccfc79f1b6bf24c33809a412a8f8daf6.nq.gz
│   ├── b3a15b3d0f2162c74c9cd40cc7e1f0e247e4425a.nq.gz
│   ├── b5e5fa4649dd04b3a27dc2895a92af85f7c15334.nq.gz
│   ├── b63183477b01f9f472c289444751d7cf5a8aaed4.nq.gz
│   ├── b79a1400b07524cdb31e0abae9b06f26e5df4e5d.nq.gz
│   ├── b89e6ec37379c8005de0a0fd798d9330d9ddbde8.nq.gz
│   ├── bbe94147267e3eee1c23296e641316493faf59e8.nq.gz
│   ├── bee0b797f6830a6c0c58b34521de7f8240c63efe.nq.gz
│   ├── c139ee143176baf5b6a26c014ff798b7c8d91662.nq.gz
│   ├── c16a6399b20c8f0af13e9939c7af9b4389794b0b.nq.gz
│   ├── c28c8468fedcf30ccfd909a34d7c1c3ee66228b3.nq.gz
│   ├── c3288d5f263b71243590a1bab4c99dc13b6fa5e1.nq.gz
│   ├── c645067c8b28e0b4b3e1a25eff1033f68561e004.nq.gz
│   ├── c831de53edc1b650fcfe00200c0281b0ed2d3a4e.nq.gz
│   ├── d954ebacaa480d595589ac613e27c3b17fe1e678.nq.gz
│   ├── dbb3c5917f22fc47982a4b3e9c08a5ce68e7d7de.nq.gz
│   ├── dbf0d3c06eba6c2bb6c547f88484d6dd2847454b.nq.gz
│   ├── dcc0567911fecbeb1ed5da442b2fdc0111f14252.nq.gz
│   ├── dd74ec8655aab6c60fd26912d16d7f10e7188bf3.nq.gz
│   ├── de9cf842278cf78dd8d061143ada4c3e90ca536a.nq.gz
│   ├── e0c2fde823bc8ade8fcc8a37b9f8a9d43e76ec8e.nq.gz
│   ├── e4d527877f382c67f15d7e7b5716b2d589ce240e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7168f4e1bc9625690dc5d325e21a0cd5813f28d.nq.gz
│   ├── eb2d86b64d89fac598119b355518e1a4b129a6fc.nq.gz
│   ├── ec2907a406e3a40730e4fd1ae13e1c9210786114.nq.gz
│   ├── f0d70a7b8e4642f0850f9936c3c2ce9683d2053f.nq.gz
│   ├── f51193eb7c2b2d2837f0dea79d686c5960c28f37.nq.gz
│   ├── f699c16b02c7e666338bc6a0cd6a3343836e6496.nq.gz
│   ├── f6fcb84ef624b4dce5eedb1d8f019640b1563ae4.nq.gz
│   ├── f8ea050ea7734656a29fc6c7c5c676908096622c.nq.gz
│   ├── f96fcc88719cb88d54a4c1203d8d1eadb1719f2c.nq.gz
│   ├── fa9c7b0a7911217992e934752c5661e60b588ba8.nq.gz
│   └── ffdf84e2314ca24a8b508642368dbba3bc61c7cc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 02344def2a5e57b9fb25424dd806bcaff8de800d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[jupyterhub/oauthenticator](https://github.com/jupyterhub/oauthenticator)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
