# Repolex Knowledge Graph of django-hijack/django-hijack

RDF knowledge graph data for [django-hijack/django-hijack](https://github.com/django-hijack/django-hijack), parsed by [repolex](https://repolex.ai).

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
rlex download django-hijack/django-hijack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c0bfe94e9fa9944195e8995e1c0fe9e642f81cac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c0bfe94e9fa9944195e8995e1c0fe9e642f81cac
│           └── chunk-001.nq.gz
├── blob
│   ├── 0077963fc2cf2bb4bc28587b8ce8c3ca92e478f2.nq.gz
│   ├── 012b4a11acdaa3354916595b46e305d5e47a3399.nq.gz
│   ├── 0651705fe2fb60c96f31d069dcd88ae7fc73e55e.nq.gz
│   ├── 08bc65668007eb593c5042da749866cf294b8d8f.nq.gz
│   ├── 0a8ba36801ca8946cae15b9f98b95526daafeb95.nq.gz
│   ├── 0ae78cc17b588c28ccbd027e991f0ffc788ec695.nq.gz
│   ├── 0cd92dab3e74614076da6482a09d6a78b1f5a54b.nq.gz
│   ├── 0f6451dcec2daa4a6651556dd412ccc1943bd088.nq.gz
│   ├── 14b350b878e21d424d566259a42a3fb5f00ebeb5.nq.gz
│   ├── 175520c47b43443e9bf1e39af9f92dd59ee5d9ca.nq.gz
│   ├── 1a6bd458748bdf50ff241ec18cc99027030fe02c.nq.gz
│   ├── 2d4725170850ab1580272a0c791679ec2fd0f46b.nq.gz
│   ├── 324347be8ed22fad962f2a6329643514bf5c27ab.nq.gz
│   ├── 3995942a9d4ff3d31644cbe15a06666216901543.nq.gz
│   ├── 40d6718febffadd78c9e6318c59e58f4abb3a302.nq.gz
│   ├── 42516630101eec0c943b5c7f13dd09360659ca7c.nq.gz
│   ├── 43605cb94f260a0532a017415e46ab40e2793aa5.nq.gz
│   ├── 43ea383002387feff445ee19821967ca885ec637.nq.gz
│   ├── 49eb060ac05cba717de07a9edc543bf2e92b9ce8.nq.gz
│   ├── 4ef6628c0521cad2a233290d434a8eb99c21ebe2.nq.gz
│   ├── 543b18c3264242dd4f9d93a36cdae2d22ee18688.nq.gz
│   ├── 55e0ab2560209a13089d1772859776e0786823e3.nq.gz
│   ├── 592658a5a0f8ff5ab0374f09cace588e22f87a23.nq.gz
│   ├── 5aab635167953401184e4f310e11264caff9c107.nq.gz
│   ├── 5d7a1ab09a6076787cbf1b9b56f990c7a0be0e25.nq.gz
│   ├── 5da8ac00eb5155434c1ce86f6ae011f96e061ee8.nq.gz
│   ├── 60059548de46e08a6f619d08c5615b371ea727ec.nq.gz
│   ├── 682f679d3e9647dd01a0ec50eda76de1853b4168.nq.gz
│   ├── 695d5de20bf4f61597ff57eab9f706365edb4e61.nq.gz
│   ├── 6a2abd6e36a725b88703b6af831e5c6f7b43e6f8.nq.gz
│   ├── 6ac9ff1abd474e976c429f54b1bde530690dc550.nq.gz
│   ├── 6c83a1ec60f7b483074a6f71ba8ab79cf50db70a.nq.gz
│   ├── 6d42967563d05073263e95237dd785e448a8006b.nq.gz
│   ├── 6feca566fffbad127cb52d98788eb6f6fd2663cc.nq.gz
│   ├── 7193dc2e36772b1367c5b1643817f0421ea1630b.nq.gz
│   ├── 78eb772ede270473f85322d1d75c30d1a3943ae6.nq.gz
│   ├── 793592893dc2a6c20f558a93808b6a106f99b77b.nq.gz
│   ├── 7957cdbcc43d66d9f12d19bf431888ae6385c52b.nq.gz
│   ├── 7a993b3683ca33c0474ef54077ea193e5930ea6c.nq.gz
│   ├── 7aac0486f65dfac68429b0a6393c5c165331310d.nq.gz
│   ├── 8581e932192bd1da9b27fda3d7a81cac79f14f75.nq.gz
│   ├── 890b97158d1a53ff27d3712cc266e88319e66974.nq.gz
│   ├── 89a0ed074563c5d26a61b1a8302f5bfea0b68cd9.nq.gz
│   ├── 89accbe4f3308915fe60cb0a8577de4c0c4811c8.nq.gz
│   ├── 8bcf8c8998e144c800cbc040baa4165e41ceedc6.nq.gz
│   ├── 8e5479961435707eec229be34d7a35cce1fa2360.nq.gz
│   ├── 8f5ec94d0b8b7aab1e0bbb61edd60cd1bebbb13d.nq.gz
│   ├── 9105aab110788aa6f10b81fe7e70bc67914fa721.nq.gz
│   ├── 97ef9b3d1ae0324732a7962d67ca56c0ca0d1c22.nq.gz
│   ├── a01c15ee116552560d0742697c30ea715f0a1c55.nq.gz
│   ├── af2ad0a51ed534e811804a8de3efce156ad19b57.nq.gz
│   ├── af886fbb51c57548b96b9254fda675b08e6e6892.nq.gz
│   ├── b009dfb9d9f98f39d71d2a4ecc3110332b969fd3.nq.gz
│   ├── b86a174ee9fd77d4a820cb76809dbf27b26fa164.nq.gz
│   ├── bae044153cfc95b0bbe91b02e1ead405985dfacd.nq.gz
│   ├── bb67c6d066dde9788f236dd339ba41ae00191d79.nq.gz
│   ├── bc83c754e4447c14356624536d0a731221939a9c.nq.gz
│   ├── cef38faa327b942891567426eafe32546caa2d68.nq.gz
│   ├── d19979717b4e1e6d4ca8e06232b8cd0f25c72176.nq.gz
│   ├── d2c9fd192e803e136bcfc4261ae87ce10c2db496.nq.gz
│   ├── d501df5f6ab78105c57daacd98440552a500e624.nq.gz
│   ├── d7abf0f669dfae9fa82d5493533c40fe05a8fade.nq.gz
│   ├── dbea1a5de7531fe7d0e25872272f805036dc5c2b.nq.gz
│   ├── e20ec8a8061284018d7f4b0bc1631a6d33ae50ad.nq.gz
│   ├── e4b9eb9d6e2e223cc5e59250e70fc36bbacc7c3a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b7751c3ab817125e50ee31175e3d12bd179a5e.nq.gz
│   ├── fdfcea7e556a3642eaf54532c2fa8ed019813eca.nq.gz
│   ├── fe1c84a64f5e6f45fda6421e2ac57baab0237406.nq.gz
│   └── fedee5562fb57a5773a08cf123ed93b241ad6f4e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c0bfe94e9fa9944195e8995e1c0fe9e642f81cac.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[django-hijack/django-hijack](https://github.com/django-hijack/django-hijack)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
