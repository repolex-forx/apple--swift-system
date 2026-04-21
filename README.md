# Repolex Knowledge Graph of apple/swift-system

RDF knowledge graph data for [apple/swift-system](https://github.com/apple/swift-system), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-system
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2bc160bfe34d843ae5ff47168080add24dfd7eac
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2bc160bfe34d843ae5ff47168080add24dfd7eac.nq.gz
│   └── repolex
│       └── 2bc160bfe34d843ae5ff47168080add24dfd7eac
│           └── chunk-001.nq.gz
├── blob
│   ├── 004d67aff35d05d06650d50bf14a7ac789557e7c.nq.gz
│   ├── 03c3ff9e4e789d6a2af4c8c8da32649643f9fd33.nq.gz
│   ├── 0979f9525876cb996320b8f4b4535fcf9d207468.nq.gz
│   ├── 1636568a821bd0c7b678ed6c7aa92c5d91ce468a.nq.gz
│   ├── 183f5f7de89453fe9ea69e4d7fa546d506ab57f5.nq.gz
│   ├── 1ad9434abb8bf84d02747124811b8cd0a995d533.nq.gz
│   ├── 267539892ab9cfc7790e1bd3741887fa3a2a5e32.nq.gz
│   ├── 2b4ae3be0f625272ead791ff50cdf6e79efc8324.nq.gz
│   ├── 36acaceb78439d44ea96d4c965cc51208be8b505.nq.gz
│   ├── 36bbb6fbbca4beae000a6fdf37d90134113b7f26.nq.gz
│   ├── 36e90be00174f1878ec7a07116aebc42bd3d7992.nq.gz
│   ├── 38545988b17065b5cf49b6e0a1cda75caeb67af9.nq.gz
│   ├── 3c40a154e8db1ee5e9ee9ae68851d69986b0780a.nq.gz
│   ├── 442cda805cdfde10ea158ce908f0516498429213.nq.gz
│   ├── 4c6e4ab2c6bf169585cb75fd6849803bb89a43ff.nq.gz
│   ├── 4c74b6a483b5bdf363fec27ce3199a9c95311172.nq.gz
│   ├── 4ed4dbd196b9725b9e0275e03f1a4f00f00dfa04.nq.gz
│   ├── 507c89640ce28febdadab7d39be60324ed46af31.nq.gz
│   ├── 5a4a8dc6216bfe4e40175dccfa0e1d0131406173.nq.gz
│   ├── 5ab79b32ce4a76bb333ca3092945d981715bc8a9.nq.gz
│   ├── 6116cb6efa9555b2924fde3991b28c80543a6a96.nq.gz
│   ├── 6464869e69460a6422599c23ea816040b15b1c59.nq.gz
│   ├── 68eb9e82ebc09075ce28bb0386279936c5b6433d.nq.gz
│   ├── 695f4e5b50ded0a28c82ce08fd8f33402128a405.nq.gz
│   ├── 6dba7ff24dd8dbc40ad21828c25ad2652e266afe.nq.gz
│   ├── 7719be9e1ce697ac4c84c17d6654cb2f10c29870.nq.gz
│   ├── 776f7766b3281d8aa8ec308e1260894508907c23.nq.gz
│   ├── 7f3b96d76836b40678bc2321dbe239775927e71b.nq.gz
│   ├── 8659c3f8621a2d824456697d46d7a866b8d885d2.nq.gz
│   ├── 86a7664ea77a99b67de83bb7aac1012cb8f10d17.nq.gz
│   ├── 915993cb6d0eb5faf3327f3a13ca49e59c67938e.nq.gz
│   ├── 93bc3504456d9ba0ed6b38bc0a8dc778d9dbf900.nq.gz
│   ├── a47a05f3216f6d682f96ad716145d5bf6a116054.nq.gz
│   ├── a678ff590db99a2c94eaf64979d26c379e625625.nq.gz
│   ├── a9fa61ad08a7fda7068a3dd6c79d9d325b8f3d09.nq.gz
│   ├── aff3fe16887b67bc51606e337786da1ea9598a32.nq.gz
│   ├── b172d658c8dd9774c14a3962645de744ee029cfb.nq.gz
│   ├── bcfe632c23a2bc62a529b4670ef55df003bc1d69.nq.gz
│   ├── c038d461d275760bc1c86fdba6a07ed63f8e1699.nq.gz
│   ├── cc931d4d0cca7fdea384b6f197af47a6da2989ed.nq.gz
│   ├── d083c1018e28da3fdd9be6671bb639470d84504e.nq.gz
│   ├── d788b8c329aecf29f637a43d69c7b909853e2164.nq.gz
│   ├── db0651eb00e464e3b887649a229cf278277b2e17.nq.gz
│   ├── e2332eee9aaa589206ee27d44ab5972db0ca9b72.nq.gz
│   ├── ecfdc843954d2e079473615191035436fbd3186a.nq.gz
│   ├── f39a052ac9c3f165cb97e8b7999d56d2603cf822.nq.gz
│   ├── f492a2ae1dfa80d89f29c2123084b4d8c6bbd2f6.nq.gz
│   ├── f5a64b0ba3f9c1c8ade884b94e5d70ddfcbf3bea.nq.gz
│   └── f67a283ffd376ae07674d9059faed81c9621f986.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2bc160bfe34d843ae5ff47168080add24dfd7eac.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 58 files
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

[apple/swift-system](https://github.com/apple/swift-system)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
