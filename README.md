# Repolex Knowledge Graph of rust-openssl/rust-openssl

RDF knowledge graph data for [rust-openssl/rust-openssl](https://github.com/rust-openssl/rust-openssl), parsed by [repolex](https://repolex.ai).

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
rlex download rust-openssl/rust-openssl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 48db60aca0159198b801c53dc4746bdd7808fe3c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 48db60aca0159198b801c53dc4746bdd7808fe3c.nq.gz
│   └── repolex
│       └── 48db60aca0159198b801c53dc4746bdd7808fe3c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d6359325a1c47a2da55f07b3ed6076a92af9ff.nq.gz
│   ├── 032fe60e90b90e1ee741f7d50322f50dfdd2a02d.nq.gz
│   ├── 067a538d8b28f7bdbc0c3e1f2e960229f53a9d9e.nq.gz
│   ├── 07f03bc733a7f67959206231d203cb29aae5d035.nq.gz
│   ├── 093f2ba12a50ef91b9770d7524b48e6e6d195b14.nq.gz
│   ├── 160d2daf355279080e0b861bae01af7af7fa8417.nq.gz
│   ├── 198679b53972e5f7967b2be8d70837ed26678d6c.nq.gz
│   ├── 1cc36c7fe88fa62d3c4526592793de41366acc7b.nq.gz
│   ├── 25ffe501bfb7870eb5bcffd18698ed4df6497ef1.nq.gz
│   ├── 2a82256967ac3a5174e1befe24bfcceeb709562f.nq.gz
│   ├── 2af8f50e1ffb28c64bdcbbf5bf33535a827f4d5f.nq.gz
│   ├── 2ef99c175a46d2d4159d5a15394042b6fbe55ad1.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 36d5ed49530a2f8d16d5e4fb229488412d4c7515.nq.gz
│   ├── 395b04a94b539dfeaac6cd567da787043027f616.nq.gz
│   ├── 3997bf35eba254989c64e01e1dd9e70dc0424c10.nq.gz
│   ├── 39d31b2fc3520a69ae44d2c703a12923c1b25cfa.nq.gz
│   ├── 39e0ed6602151f235148e6c08413aa7eda5b9038.nq.gz
│   ├── 3b831e6f2aba3a72dd52f555bbccb21f8c9587af.nq.gz
│   ├── 450dd113fb84e2d67c29a505994ed1ec90b2e6b9.nq.gz
│   ├── 47a2db8ad99c55424b3eba09cf195d9a826d9f17.nq.gz
│   ├── 48f499798443fc52c00dc7f63e9f03b8bc614f5d.nq.gz
│   ├── 4b792a7502817ef28414de82bbd70f1672fa69b5.nq.gz
│   ├── 4ec2f5388494b39112571639160b8fb801a8a954.nq.gz
│   ├── 50d9da7b2fca3af71e26e551f681e736e13d4a8d.nq.gz
│   ├── 519135cc211b4336b605ce462ce337a9888f0aaa.nq.gz
│   ├── 53bda543b69da29b57d8d18ccfbb019126c332c9.nq.gz
│   ├── 56ba1f3d095c76ebc55f82ea3f1a5f690d067582.nq.gz
│   ├── 5be99430a8694782bdcc38ac553a6d563169e01d.nq.gz
│   ├── 5c3e7cc884e7b22939bd1f3abde23391dcdfb3df.nq.gz
│   ├── 5f3e21709c521b512fc83057d396ed6b044ddae3.nq.gz
│   ├── 65315e473ae76c601d452b041e053f1e8161ba31.nq.gz
│   ├── 65436a4c4081a98c96cd255625a9fb12eb43d396.nq.gz
│   ├── 6b6209fd1fbe809a335cf29b263d9ffd5d1b9da0.nq.gz
│   ├── 6e4d4c68cb283d2a851be0a2cd117f2002e316f9.nq.gz
│   ├── 6ef399642c36a70b117271cfee1ffdf90d01c680.nq.gz
│   ├── 6f17e734cde30b7d5e869cd91f17e13033340202.nq.gz
│   ├── 70532436a25394d4793c0d99e9d9a73894c713e1.nq.gz
│   ├── 721f4b0c44f51624ce2426e98d4a12f1c22836bb.nq.gz
│   ├── 7254d7ba8537ae12805af4e9aa86b7aadce024e8.nq.gz
│   ├── 746ae2a68c5107a858b105d247914afafc2059bf.nq.gz
│   ├── 76eeba3fe0db47d0e69d7e44dc36e337fbe250da.nq.gz
│   ├── 7e7023ec590f7399e8cf571b19b8b26840abb025.nq.gz
│   ├── 7eb119c23dd3edf247199348646b53067bfc6919.nq.gz
│   ├── 82ec38b64717028df393530e3bbfddbfd125ce37.nq.gz
│   ├── 83a8266030a25cfb5631923cab1f900aed615488.nq.gz
│   ├── 86111280c6180066d459b3462e4609eeab9a6f44.nq.gz
│   ├── 97b095d093bb645fd6700e7b4991795830709507.nq.gz
│   ├── 9b1984eb721f24985b4152eb6bd10567f285a482.nq.gz
│   ├── 9b55018486fba03e7cf22022d0df72074e824917.nq.gz
│   ├── 9d3516620da5d83a5dabb3b5962651aa15f8bc32.nq.gz
│   ├── 9ef7e8854a35077e8c08c009f35b011029ef3e9a.nq.gz
│   ├── 9f75f125983075ecb5c280d3e50d15feeadb5f62.nq.gz
│   ├── a0db182ec632049d34e893fda7ab8232aee4e4f0.nq.gz
│   ├── a6249997268d606672670ec007d38b4d1cc9a9f5.nq.gz
│   ├── a730cc49f88fb72d3e6ef88d13e2cdeb650e057f.nq.gz
│   ├── a819ed566e396add6cbce5259aca7ac26ed13ef0.nq.gz
│   ├── a90d1570a4b569b2346f3cbab6cb7bbde817295e.nq.gz
│   ├── aa6920c49aec0eee0494daab9d994835892d6f9e.nq.gz
│   ├── ae298d093d0fda94cad283baa101eb9a79796724.nq.gz
│   ├── af58130e048038cb02b9543ee54948f856b8f200.nq.gz
│   ├── af8ebbc145bef813b818f3eb4d90bb426a492c32.nq.gz
│   ├── b02b92168cc4ab2c9338e4c522871fa3b0cc6bff.nq.gz
│   ├── b37e4770e91052928d2fffc018b3dd375bef3eb3.nq.gz
│   ├── b5adb828206b90b06a69ddfd665f3b6b0ca7a195.nq.gz
│   ├── bae5d621e35178897704911c5aaa5e31e2fcb1f1.nq.gz
│   ├── bb60ed35e4b07d9e3affaefb280539e5b090a6dc.nq.gz
│   ├── c062125fd97d7bd2ae8dc11208a4222cdf946791.nq.gz
│   ├── c39930a5cb4f003f48ab94cc87f9435730540f24.nq.gz
│   ├── c64dc007ff9348a07c1371d538fae241edd420d4.nq.gz
│   ├── c687531e9309003d2744433aea8fe0f041510871.nq.gz
│   ├── d129235ae633dad11fe990b6359de76ead0b6fc9.nq.gz
│   ├── d1648b37c7a1cc97ba5f2cb67e8851b4d1a20e2f.nq.gz
│   ├── d16abb8c70627bd959667495e578fb6f010a7f1d.nq.gz
│   ├── d381795d3ba3c09578cf3edaae34ae9b1805e77a.nq.gz
│   ├── d7c4805098115519069f7c5c6dfd595e251000b0.nq.gz
│   ├── d8185fed6691aed6f339267a38dd87eac791cd46.nq.gz
│   ├── d8589352d523432eab35685da75b6081e0fac841.nq.gz
│   ├── da52ef5fe0a35e0f1f1a63db2942690da42c6007.nq.gz
│   ├── de6722abe0485ea3d678b498b5c8bcaf03d77780.nq.gz
│   ├── df1090c15019c923811195fd9fbbe5543730e905.nq.gz
│   ├── dff652223a5888bfa152578ea2e6ea5770733ecb.nq.gz
│   ├── e109b2a7d527d81d8a8ac84662b2eb5ec1151e36.nq.gz
│   ├── e2f7c83033491194a540905385d856a2bd01febb.nq.gz
│   ├── e40105872495a936e46c35e19fb873a7a40f2770.nq.gz
│   ├── e844ffed7109ce4e6b9e2eccef57f27fc2bb4d77.nq.gz
│   ├── eb8894fd3f6d4fdeaeb46f7153e35d551ef86eeb.nq.gz
│   ├── f259067e9a54ac652802c9eb80788ddfe5bf7335.nq.gz
│   ├── f983aaf75d89ae114264ab9229d41b5c1a8a8d78.nq.gz
│   ├── fabfb2b669a43873eae503f05a487d22d78308d5.nq.gz
│   ├── fb5d4f3c0570306598ec549b16a8ed545cad609a.nq.gz
│   └── ff875be5468c4ba91bedd75e3169f4e46cf65a83.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 48db60aca0159198b801c53dc4746bdd7808fe3c.nq.gz
├── filetree
│   └── 48db60aca0159198b801c53dc4746bdd7808fe3c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 102 files
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

[rust-openssl/rust-openssl](https://github.com/rust-openssl/rust-openssl)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
