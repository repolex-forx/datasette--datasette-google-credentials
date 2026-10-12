# Repolex Knowledge Graph of datasette/datasette-google-credentials

RDF knowledge graph data for [datasette/datasette-google-credentials](https://github.com/datasette/datasette-google-credentials), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-google-credentials
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c2813790682282c732a26bffbfd298aac302ea74
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c2813790682282c732a26bffbfd298aac302ea74
│           └── chunk-001.nq.gz
├── blob
│   ├── 01685fd5893cebc25261c6075779fdb058a23404.nq.gz
│   ├── 041a9256df4f3ed84960c2f22122fed7db564135.nq.gz
│   ├── 04d11ca8f91835b006218de1e9ee117418c5cdc1.nq.gz
│   ├── 059070a553f64b2ffadafedf01f79d2ce5410140.nq.gz
│   ├── 09cc08cc9caebbef9cedcdce156211d81394d18c.nq.gz
│   ├── 0aab4b1ec67f0fc07271908ea2658ea5c6fe3af3.nq.gz
│   ├── 0c8f844d8132f7498c8d9806b2be641314a41c84.nq.gz
│   ├── 0d1381455c529387064b9c9f2a02afd2c1ffda6b.nq.gz
│   ├── 0ee728b1d7aa2b647b22001decb0ee336d0d79c3.nq.gz
│   ├── 1064b29ed7736b2a88e90ee98be478e546326607.nq.gz
│   ├── 138a26f89e3e2c16c0bc890f236a604d866209f9.nq.gz
│   ├── 144e21b2534b633bf77f3262b37357fd85ff4947.nq.gz
│   ├── 15bc15cffecc0df545f287587e412a8d2cf928db.nq.gz
│   ├── 1716a7d04fa08b4e504368bfacb45be55858db83.nq.gz
│   ├── 1726bfa4d20d4a05a85aa6349f94a9570df8fe4f.nq.gz
│   ├── 18dbbe05bcdb299383c9b0470feb476b587adebe.nq.gz
│   ├── 19c32dc7549433efa22556d0dfb90cca8396d7ba.nq.gz
│   ├── 1e4b0165a3275056baa8fa67a58aff0d971c2291.nq.gz
│   ├── 1fe6a8d3cf36d30a0f8162b904386c94563b30bc.nq.gz
│   ├── 211dc57ede7c955215a35f4c0ebceba121560d0c.nq.gz
│   ├── 2271144a138c48ae96a099a9d27f4f266e3ad19d.nq.gz
│   ├── 23f26f2629b28d66e70594c7c687396d4e1e7d82.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2d44b689836cfa9b1e3095374cd3c38d8aff3a42.nq.gz
│   ├── 2eaa64193cbde917ad69bd6130e87d5dd183f1d9.nq.gz
│   ├── 34ca5ca87b2e13fbf7425e0d1c08643688599ccc.nq.gz
│   ├── 34de2f304d3c89d0e2e443785cff4a453e02ae8f.nq.gz
│   ├── 364b3f4c31f483a0d404816cf31ce00b9378b200.nq.gz
│   ├── 3711458e5b54a61a73e588eb5e79679652e40281.nq.gz
│   ├── 38296f5fb6cf7165e1c08b851774eb74e756deb1.nq.gz
│   ├── 4076ecbddd1a940ef120cfed1d8ae38ef8609296.nq.gz
│   ├── 44342715d7905f7fbbdd8348f352728904db12db.nq.gz
│   ├── 470751e86fa02f3a21b2ce44862919658111a0b9.nq.gz
│   ├── 47cd416113697d08f938d49595efd5dab307cc72.nq.gz
│   ├── 48ff553c69b2f48c74793407bc0153dba051c9e2.nq.gz
│   ├── 49af5f2f83d16f013b4267b220284104689d60e4.nq.gz
│   ├── 4d7290f26c3517d13e325fd4c32ffe034cebafc9.nq.gz
│   ├── 5219b314c60042e38d5ac75526e038725fabedcd.nq.gz
│   ├── 5546a924a04bea5f94d1277123f14f5600b8024c.nq.gz
│   ├── 55d2143cb39362edc67db61212f10ddf57f00cbb.nq.gz
│   ├── 57b7a09a21400dc7be3716dc1bb9f36550615e8c.nq.gz
│   ├── 58a10329f54545e25b8b32352399c4d7957cdab5.nq.gz
│   ├── 58fd0e75c177fd44227c2026d9ee5b21de383034.nq.gz
│   ├── 5927f8b1c31bd567a39373dc5c47ed3ecb8b906d.nq.gz
│   ├── 59f0ef0be4fd2984acce8aa4b2cd018bdbd16c64.nq.gz
│   ├── 5bf2e998f3400c8036bbb7b5036a2c5a089264e0.nq.gz
│   ├── 5c222ce12f4510c58d356a924853b14b7292fe44.nq.gz
│   ├── 5e8059e70b4a9eb12eaf99c486a8fddd52c99e08.nq.gz
│   ├── 5f97d57583111a70bce462a3d34d5ce9de81d19e.nq.gz
│   ├── 6221e5cbd78a0a3b9d90990ef9c65856d340bd48.nq.gz
│   ├── 63625cfe0f96b94650ce0fde152224781f7c81c6.nq.gz
│   ├── 63be98e6d574a517cb7c28b1a2971a9bf36e072c.nq.gz
│   ├── 64d9c333ea50d94e9ca7c0fa15cac681f9b5af51.nq.gz
│   ├── 64dce45dc25eeeac235dfcb28ff8fe8465e588be.nq.gz
│   ├── 65108cd5376d491ad475a5b59c3c84b5e2110b27.nq.gz
│   ├── 681311eb9cf453d0faddf3aacaec7357e97ba8e9.nq.gz
│   ├── 6aac7c786eef6a1cb6e3724489f622258b8a7fb8.nq.gz
│   ├── 6fc6c7963aa47ad49493c340180d0734768f9681.nq.gz
│   ├── 726fd0c5629953decedf517384fcbc2f33fa8d17.nq.gz
│   ├── 74b1ba458f7d28d80cf0e66078562b8d6a46a39e.nq.gz
│   ├── 7a30f9fb718551c31de5c68a7a6380c9ab6625a8.nq.gz
│   ├── 7c5c9b28729726c49112a7c3ce96e2c338e7e84d.nq.gz
│   ├── 8a47239953fcf5ea4f168c8ae0f8bb49f3b67b9e.nq.gz
│   ├── 8b58651e62516abd1321fa372ebbd867269f104e.nq.gz
│   ├── 8c1e1bee059d7c4b3aca8286451efb3646e9b139.nq.gz
│   ├── 91ef6d332cdb2582408577f891fd5c5ae97e782d.nq.gz
│   ├── 95515948a3d5859dfcf09ee7adbc549952e5aacc.nq.gz
│   ├── 99489bfd6978547ab7597938e92f5a7b294fc6de.nq.gz
│   ├── 9c1f408bb4e30b1b75867ea57caa095e218c3582.nq.gz
│   ├── 9d187d68b6b9bc677f18bcd8264ee12f9df00bed.nq.gz
│   ├── 9ddbe1b32f929b9c9f5797a0f6b1ab4c5191a30a.nq.gz
│   ├── 9e73914f0487f24a9b7d3325dfedc4ea722c9fc1.nq.gz
│   ├── 9fb2e99f29cd35ee98622814865f5da0f2b10a25.nq.gz
│   ├── a05eb6cf88209ad988476d9e78461b6d507431be.nq.gz
│   ├── a094c558a2e532da100eeec4b6b45b3012e82fb4.nq.gz
│   ├── a226ed6e69128db72c0fa0a14e823ce3bdf55081.nq.gz
│   ├── a31a93790a04880da18659382d3578f382289213.nq.gz
│   ├── a6c8ce30d76d24f959491fd62972127357f37e51.nq.gz
│   ├── a90467361071704f7f78fea722251e8a5e20e4bc.nq.gz
│   ├── aa3dadadf8135cab667b27e3eb4435ab5574a27b.nq.gz
│   ├── ab1c548206f3c3243c1b8deaa6796fbb0faa23ff.nq.gz
│   ├── abf3cfd42840b4986330dc4e838ca585ffbe7044.nq.gz
│   ├── ac4a5472aceda89d689ae78f495ab50a49de35d4.nq.gz
│   ├── ae0e53e38ad29c33921ed63818ad7e10540eaf28.nq.gz
│   ├── b0f628db356830590e20a8cc898d48acee668529.nq.gz
│   ├── b2d21711fb0bac5123da7f3e2a4e6c4d3badcbeb.nq.gz
│   ├── b5b01ca1fb406b5bc16df333d146bb2ae7adddde.nq.gz
│   ├── b66a3e1f4fadc8a893d76572ebcc7844119f6d00.nq.gz
│   ├── b68ae0ea79dc4fe715831e5c6f21e3a7df30f0fc.nq.gz
│   ├── b70ecab446f59cc8fc44563eb7d195ecef48498d.nq.gz
│   ├── b7e801bcc40761cde36c6d1c36319755df4491b9.nq.gz
│   ├── bc329224e253799ce0e5e8cf58891190c068e497.nq.gz
│   ├── be6f1f5c3e99a43b02d84391223e45cdacb89c05.nq.gz
│   ├── beaef1b2102067f3b38fdcb5be272a093a4e5fbd.nq.gz
│   ├── c067f7319a9ec9eec408cda16515496fff27627f.nq.gz
│   ├── c3be3d001175d78250615df1fe6cd15ba937c28e.nq.gz
│   ├── c4d93c28b7e2daaeaab14b0ec7dcefaf70cc974e.nq.gz
│   ├── c6ae1e5240ccfcff10a26b5f8770cd2ffdd000b0.nq.gz
│   ├── cabd6453c9d7831962232836b792bfdfed541e67.nq.gz
│   ├── cbf0f24e4c35545e16de1150410d580145151e9e.nq.gz
│   ├── cd79e5b7de0e1a9d1d58212264bbcdcaed48f164.nq.gz
│   ├── d0e64483be5144a42bdbfdc2dd86fcbff6cb10dd.nq.gz
│   ├── d17fbbd78439c6c0a08c74f5f698be564f3a6812.nq.gz
│   ├── d548aaf6f16e2a5044e8466c46ad89718b7bd515.nq.gz
│   ├── d7382d5ee5d689852e0448c995cae481c4625804.nq.gz
│   ├── d996d052550c82fc90e0da364f5743d4c8b4aa84.nq.gz
│   ├── e16903dd1bf6cc860c68d6fc0021a4977a74900a.nq.gz
│   ├── e3c8b3fc385f1e0b7c1140f473a2f5f7d6de2c6c.nq.gz
│   ├── e505f6ab1ecb7ca436ebb72d06d7ec34f676fadb.nq.gz
│   ├── e637381f5bc561a31b42df6a95ea07f2142fd55c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb5d0ea6e363535381f4a865c3eeb7ac99185f76.nq.gz
│   ├── edf54a8850c6ee983a1df9260f470f88a05f04e9.nq.gz
│   ├── f1ef8132bc7437615eb4a079d580858c1f081c00.nq.gz
│   ├── f403326da5d37526819eb1a7c9874a4d8bac9492.nq.gz
│   ├── f555eb84487bb3722ea70eb1558a22715c4bccac.nq.gz
│   ├── f630fffe44d1ba9a64d9cad7600146ed1d397b5a.nq.gz
│   ├── f65f2defb2eb26f4d9fe9a621624c4bc27d5397c.nq.gz
│   ├── f6f21271a09235ae1f5b3f7694c4cf3b61d9bd67.nq.gz
│   ├── f8d9140bf344091fd9a6c8d4445069e75490b3bc.nq.gz
│   ├── fb70c3e21aa7f888642ea5bd560eaced069a8aa1.nq.gz
│   └── fdeaf94b58803c28d57fecd7d5109433cf3e1b7a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c2813790682282c732a26bffbfd298aac302ea74.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 128 files
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

[datasette/datasette-google-credentials](https://github.com/datasette/datasette-google-credentials)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
