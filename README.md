# Repolex Knowledge Graph of pydata/pandas-datareader

RDF knowledge graph data for [pydata/pandas-datareader](https://github.com/pydata/pandas-datareader), parsed by [repolex](https://repolex.ai).

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
rlex download pydata/pandas-datareader
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a3e2fe8c4e202bf9be6b4543fd1a06c3cdce7de
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9a3e2fe8c4e202bf9be6b4543fd1a06c3cdce7de
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b6347798e6ca18b6636c004623c138f2020604.nq.gz
│   ├── 03165cabe67cd005c4fa305234f674b58f2c8a0c.nq.gz
│   ├── 0349bd5b896e28c8dac4d8e9dc4bee27776a3cd4.nq.gz
│   ├── 0b7bf10a9e0aa6ed625828bd78f666ecf227c77c.nq.gz
│   ├── 0d9a00d716d480cd45f077e916b0fdae4293c99e.nq.gz
│   ├── 0ff21d66795901a6cebbaa4df63b011f851e0264.nq.gz
│   ├── 103a03a1ae67d5d114cfcc687c806bbd091034cb.nq.gz
│   ├── 1179e1b9c1219ad877e34a9490fd9f4e72ba7736.nq.gz
│   ├── 11b9458bdd3f8467117250247ec1862b99a60ca9.nq.gz
│   ├── 11dbc27b6b6fb07347b0b6762f771321091cd962.nq.gz
│   ├── 132fa9267719ee015d8f23724831c45a2029097a.nq.gz
│   ├── 1b1e7b1030a3a18f77d7a31a76dfd887466027ec.nq.gz
│   ├── 1b5195673bb0e8db8f13524f421b58859d010f21.nq.gz
│   ├── 1bb147481a1f6d61d4cdde02cd33b8b117ba6bb7.nq.gz
│   ├── 1ee6ed8a0d2a2537adca6133b22d482b75e3a4f4.nq.gz
│   ├── 214262f47ed8889eca86700751ef8ebba03d7844.nq.gz
│   ├── 2608191e9e10b5040f6c9d0476ed62131a024335.nq.gz
│   ├── 265d27be5882de8f4813cf3c256486cd1c5b1bf6.nq.gz
│   ├── 28da65099105ace2d3fd972b7cadeb4284fdda3e.nq.gz
│   ├── 293d7af07fd25c353c872f3f391022545ee3d2e2.nq.gz
│   ├── 31a252acf48aad871b897bdb14d593b45ee3b70e.nq.gz
│   ├── 3482af1997a0293671a07b30846ef7c4c4b3ba24.nq.gz
│   ├── 3c1493bb21002ffeee63ebb715c6c11ca5e3ec81.nq.gz
│   ├── 413bf52e83206282a860bd163c0145f344df9ecb.nq.gz
│   ├── 415426bca13ecd1bd829d3a3cda0c1e7dd4acbdd.nq.gz
│   ├── 42c0c07fc679ef35a404038f6e2a7dc0d5d61421.nq.gz
│   ├── 474cd65bfb481befa8c69fbde22d01c0b29e40b4.nq.gz
│   ├── 4a506739af35d31dd8d79dd50547f3f28c866e46.nq.gz
│   ├── 4b0c0e26be235c158960caf7a8158de974429ca9.nq.gz
│   ├── 4b27e120d99067bc0ccc5d99559531f0365f86e2.nq.gz
│   ├── 4cad06f6162fdf4a8f5ab6348a123b8920320915.nq.gz
│   ├── 4e90462ff9b612a689752e456163f21ead397a15.nq.gz
│   ├── 539639d2f51b9ce5b3cb1ee6a4df2b931d270520.nq.gz
│   ├── 56cd91ff3a68090f7e279082ebc0af0fe080d574.nq.gz
│   ├── 59fcf1bc82aba0c59af09a7812e4624249f64024.nq.gz
│   ├── 5b4c028b897222c9889eb27879b1b41b39d68c44.nq.gz
│   ├── 5b64d9f8f7757ca550098a881b627136fc969939.nq.gz
│   ├── 5ba91c0123c9192d7538f2ab7d060a1e975bc12e.nq.gz
│   ├── 5f3e3024aac67f977fd02aa0be331147f2f12148.nq.gz
│   ├── 628ed151f308d104cfa3c5d611219f968cf441bb.nq.gz
│   ├── 683305f1a75c8ad3432c2a7652cfb06e0ea79cfa.nq.gz
│   ├── 6908afcc316d201ccd9c5c0b62e1e16c9abd21b4.nq.gz
│   ├── 6d8382bad7e1c6022f112123cafe4584255de0fd.nq.gz
│   ├── 6f3e278842d499490e54b4d88384f1737f117d1d.nq.gz
│   ├── 7359a44944a392425628ba7fab48eb938ba854e6.nq.gz
│   ├── 73c115b1bc26e542055dfaeb2620ab730deb55ca.nq.gz
│   ├── 746040a56f16fcf11e989eb5a9d65e52a8f59a19.nq.gz
│   ├── 7559cb9d0d913764a628e18811960b666453b0d2.nq.gz
│   ├── 7a51984e9dbfaa1a7f43c4b6fddcb67a83ef2521.nq.gz
│   ├── 7dca13e17fd055bcf534d13c6dc33b99da456821.nq.gz
│   ├── 7e58da90e9e8f0d6cf4d361b73ae872eeefc31ce.nq.gz
│   ├── 87f2a3053bcf2c65cf776bf341df8783808ba32e.nq.gz
│   ├── 8a2480b454a0df74319eb5ccab7dc0c3024e23d1.nq.gz
│   ├── 8cd3e8c486165c82398d00b086456ae9a2862a84.nq.gz
│   ├── 8d06908d1acf9ee3bedb9fd8453dc5ac645b759d.nq.gz
│   ├── 8d20a0299d81c4df4fd3570b1b38c7d570c8a0cf.nq.gz
│   ├── 92f208d33f2e5a784702634d47e1e257b272663f.nq.gz
│   ├── 9338dbb2252f66add188fe10625a5c2d1472477e.nq.gz
│   ├── 93decc6809bfd2a125b7f34ccc1d68d8686bf42c.nq.gz
│   ├── 974212937f2f8afc2147fd26ef7e35f99d6c6122.nq.gz
│   ├── 9869b72f82f8a7713ffb2f85ae0b384dd888750e.nq.gz
│   ├── a139adc9b3ec5a5f76a7d24159a3cdcea8240ddc.nq.gz
│   ├── a186d4006fa03a8bf9a4dd2ab6f02c7456627849.nq.gz
│   ├── a44176debf422ab2993a0803c284616283deb38e.nq.gz
│   ├── a532457bf698829c6881094b9de23615f1aea058.nq.gz
│   ├── a54d9bb122f6fdd943ec26e597ab84b7b62c35fb.nq.gz
│   ├── a5efb5a9d4a84d5801c8f0a9346edbd963adfddb.nq.gz
│   ├── a685ae1100452b31766e8e24b3f74e11c7f6e3ab.nq.gz
│   ├── a7f53b0aae5033600479068c31da86d1a254bdfb.nq.gz
│   ├── a806d4452bcdd09d083381ae054577e5945f8e0d.nq.gz
│   ├── a90a7acf1d8c2c88ea08d658e645909a1ac33d83.nq.gz
│   ├── ac17d5c6bc805c951b634f29decc1b9bb73a5bce.nq.gz
│   ├── ac27a84869a2cb5b416c12fc1fcf57aa6f626958.nq.gz
│   ├── ae7cbdf9fa5b10f6fe5a7dead0a2ba69c36da339.nq.gz
│   ├── b05a0de8c4a94490ff34ba71a6b0f7986dee0cab.nq.gz
│   ├── b16719f92583b3e4f6ecc76e7f0db6333e401092.nq.gz
│   ├── b621e510fbe15da93f9a9b1c7a3e99d1d19d35fb.nq.gz
│   ├── b710ad2165712ed7666180fae3d77b5a0eb0ec5a.nq.gz
│   ├── ba270394375566824e4bba625fbdbf96488b8dc3.nq.gz
│   ├── bff2c317f20273f73b9d0a346729a1e30553793b.nq.gz
│   ├── c05937d4124f365093f245ed988e6e4db4d96151.nq.gz
│   ├── c14bea77e435b7b0e34f335d500eacdfa8f33539.nq.gz
│   ├── c44519168d158bb087facf5157182db5503d53ca.nq.gz
│   ├── c44b0674074391c1c9bd938f7a51fbb1b8c232c1.nq.gz
│   ├── c4bc347a71b8ceb8735b52ddfd3a6d5092b633df.nq.gz
│   ├── c6efb9c9a8162d70cede30179cc614f173ac0ca3.nq.gz
│   ├── cf34afa191c5b8068de9ca81d6a212649ff0737a.nq.gz
│   ├── d02cd49f9ad058cc32109da9c569ef5a9a4abe14.nq.gz
│   ├── d72999dbdf3b6325eb8614357476c4f594d3ddf7.nq.gz
│   ├── d8eb333e2087789af53af95596c4734cf1ab727b.nq.gz
│   ├── dc06429a99089414744100d7f59198c15c7caaff.nq.gz
│   ├── deaa8b8f75d12a801374a7651a8fa8045c5ea040.nq.gz
│   ├── dff62eee916812c91bfcae645832fbe187c676e8.nq.gz
│   ├── e0d024512321699c05aec89accb1e58b445b1e2b.nq.gz
│   ├── e21c7b19c169ef3f1290e1708db0fd05c3448fcc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaa72d8ececc4c133234305459db2bce78bf3849.nq.gz
│   ├── eabb19dab67b2cacb374b38541e78ac1665f3ff7.nq.gz
│   ├── f3058ae0fc73646e28ef6911f86b435861a998e1.nq.gz
│   ├── f7e1a36de164a8450e9e8852b7c5c7cd5505b965.nq.gz
│   ├── f8418e42e5ab312596498618d60b320cab43ed74.nq.gz
│   ├── f94bd2bb3ad591c4af601073e1c81655190bdb9e.nq.gz
│   ├── fb464ceba9a12f0101ac0b6ad80cda5b2d5123ce.nq.gz
│   ├── fc12be4d1cc1e88f7250d55084806386bc746beb.nq.gz
│   └── ffee45128f1b7257abedb2cabaac2734796bc23f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9a3e2fe8c4e202bf9be6b4543fd1a06c3cdce7de.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 113 files
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

[pydata/pandas-datareader](https://github.com/pydata/pandas-datareader)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
