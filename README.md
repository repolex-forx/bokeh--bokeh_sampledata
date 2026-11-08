# Repolex Knowledge Graph of bokeh/bokeh_sampledata

RDF knowledge graph data for [bokeh/bokeh_sampledata](https://github.com/bokeh/bokeh_sampledata), parsed by [repolex](https://repolex.ai).

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
rlex download bokeh/bokeh_sampledata
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c0ccb5facf6db1c2ee4dffdde80ad9c06bc9b587
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c0ccb5facf6db1c2ee4dffdde80ad9c06bc9b587
│           └── chunk-001.nq.gz
├── blob
│   ├── 0194ccb8ae10eae8bbe211e368545d83da247f59.nq.gz
│   ├── 08dcc2b7c437af262bc06321e764c3640078b457.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 0ec6b61783a87393b68cfbe9df6c313af3cdec77.nq.gz
│   ├── 10d7742092640e54475ad20ae6d4cad1ba615a2b.nq.gz
│   ├── 10e38d2f719430d7c56669fde5fda1d0568806eb.nq.gz
│   ├── 11d41ea611cf22e849b0f7222eae0c0fde6d0c59.nq.gz
│   ├── 13ab9536e1792bae3d45d518735fb9692a47db40.nq.gz
│   ├── 13ca539f377dc705af32b8d2ce89262298ea2f06.nq.gz
│   ├── 16ab3d3265b0efde8778458a7cd9beabce608060.nq.gz
│   ├── 16e7287d1c15f83e247e607af7a32892f4d409d4.nq.gz
│   ├── 1a16e05564d2aaa880bbe9e506a0a0226d8742cc.nq.gz
│   ├── 1d59e979ba507f2d4e2712ea9a0a28d64a9aecc6.nq.gz
│   ├── 1d83c8a3d0ff4cb028002366c19d5589a7d30b7d.nq.gz
│   ├── 25b2b16826195531c24493c78c848758019c26dd.nq.gz
│   ├── 28399740bf34015eefc04775b7cb06ab1804caff.nq.gz
│   ├── 2bd7ec946461b2a885eb2094ea4a0d3689260b4a.nq.gz
│   ├── 2bdef03a256a3caf520b3cb6b4d360bb185d4a56.nq.gz
│   ├── 2d216e7340954e2946840a499fdbd270e8aeec0b.nq.gz
│   ├── 2de536c2063485c737a672e820b710d1ff5441ad.nq.gz
│   ├── 2eb2bd5304ea06a97cde461358888115b5309076.nq.gz
│   ├── 2f42771ea8bce44e45f0a73a3829d13c4458f382.nq.gz
│   ├── 2f6ea1e485d8caf8ab0c99d306d607fa5c24a957.nq.gz
│   ├── 3013752e2cb0331f06c01ce6d68e922d2f16bdec.nq.gz
│   ├── 319c1b53a89085decd91a4de24b3e989d7459671.nq.gz
│   ├── 31d055050e4bf733690efe18c6ef34cd38898adf.nq.gz
│   ├── 321d9772da62f0a18acdd8eedafa925673aad579.nq.gz
│   ├── 336a35c7d2d37b061a5fac7c38456c2f0074923d.nq.gz
│   ├── 336c86d53bcf6df154e6debccb276385d9070026.nq.gz
│   ├── 35e3078d471591324f1e2b1c47e1319abf7aadeb.nq.gz
│   ├── 38391e9e6fca04d8cfce3d1de3148edff1487046.nq.gz
│   ├── 399419627853d6af89a8c66c29b168fc7c60df9f.nq.gz
│   ├── 41c2c1e9b5b1a9f2cc610070a6c79dda905ba346.nq.gz
│   ├── 43606ed976b0ca8a914557a192c0f0ebf8cc787a.nq.gz
│   ├── 438e02ef83e561f0a9cab14626575d49fdd66c15.nq.gz
│   ├── 46379f4da17dfb3adea8ef0d302f90877fa36429.nq.gz
│   ├── 46c5eee73bfd602eeeb61eec8432ca1f745f3693.nq.gz
│   ├── 47c3fefbd796a5343a319a8ce7d260994c92cd00.nq.gz
│   ├── 49b09075c51da01930d3b459096ba2e0229f5f88.nq.gz
│   ├── 4bb57e975bb0eca9bc985687728377578c768a18.nq.gz
│   ├── 4c1c85e8cdb8bc79c768491a710b087064f29962.nq.gz
│   ├── 4c52a72e68abd8057281b08e5fc5b8668b62b652.nq.gz
│   ├── 4db91adea5d3b47caa8cce5e19608dbdb032aee7.nq.gz
│   ├── 4e37f90c3c0915490c21b7ca8791edb8ad8ac976.nq.gz
│   ├── 501dffa83bd003bc74ae433ef08ac9e9663ecd1c.nq.gz
│   ├── 51796a1a726c7063b847cfc3d3b402b930df097e.nq.gz
│   ├── 55a4d1ce7be3331ff1d168cc306b4b334798ea2f.nq.gz
│   ├── 58cee587cb2abfc0ac4475f515ed33f9f3527958.nq.gz
│   ├── 5ac8250e5e7d1ba6bc127d3124c1842db88bde50.nq.gz
│   ├── 5b4e3f92735f8df7ba60c456eade3422fb4f8c71.nq.gz
│   ├── 5b5ae6fc4cade49af16c4a7d1864ec90f6202f6a.nq.gz
│   ├── 5c995dadf3558d759ef27a6101e1c2913f1f862e.nq.gz
│   ├── 5d2d792e05ef58ef75e72fbd513497468436c986.nq.gz
│   ├── 5db7046fee01c1865dcebaf40e62806811882219.nq.gz
│   ├── 604209a804632b6e5274005a22293976d07c3099.nq.gz
│   ├── 6290fdba8c5dd4ee3c0a6b1d2accc6790ab2427f.nq.gz
│   ├── 6330172b4272de09ebef6c6517035ef00bc7311c.nq.gz
│   ├── 65660bb865d2cccbdd9c7ad44a8c280fddbef55e.nq.gz
│   ├── 66b6a48fc4cd704ff465cfff67209c76e655d487.nq.gz
│   ├── 69d70753317aae4f94c2d187c009299971837c3e.nq.gz
│   ├── 7532cdacddc07063dfad611161a3ebfeb1d89503.nq.gz
│   ├── 75601fafec3bf5c77a359b09119f0445aa393162.nq.gz
│   ├── 764d8ebe153b45c06d99949990bc7cbb6f798b15.nq.gz
│   ├── 789b1bb33f2d27c41ab4db63338efe0ab6cc2b72.nq.gz
│   ├── 78c740f1015fdcdfddf6756b0f22bdef4836f6b4.nq.gz
│   ├── 7d11c63ddddd283a66a890f2b687164313b48004.nq.gz
│   ├── 813e3fc08f3ef778d2ff0cb7bde3b41401638971.nq.gz
│   ├── 817afee5fdaa36ce1ea4ebda3f50979c41a5564d.nq.gz
│   ├── 81c7db8c1784ad099b9450024d4aa8719d6cac77.nq.gz
│   ├── 835e7dabb0d87b3c876bb24b8378dbc224cb3483.nq.gz
│   ├── 867168194e7e7f3618a23752a0d5e4673468c8c6.nq.gz
│   ├── 868c153b93047cb8f90df4fbab3198b836aaee72.nq.gz
│   ├── 86f93505c549d0301dea54fec4902ac6e4a1e6f0.nq.gz
│   ├── 87ba4480cf9aa843a66798a22942f447a3b39fce.nq.gz
│   ├── 87bb3986e0f5b44f8e3477d8a3cf66904609b0da.nq.gz
│   ├── 88adb9ca8decb7866338f97e0e0b59ceac78c63b.nq.gz
│   ├── 8bb62da1a7f9e341c5bb5285299d566dfb994f38.nq.gz
│   ├── 8c595a8a0055c6ee995de7fc5a9ba90a1d8546a7.nq.gz
│   ├── 8ea29c9c9a6a3162fc88764a7c245c472b30cea8.nq.gz
│   ├── 92188254823ec9aceb2e5721672d7acfd428ff1c.nq.gz
│   ├── 92c8c8e5fba6b0f32f423cad0333633cb33e635d.nq.gz
│   ├── 932eea6069d20190ab8d863739394640043fe17f.nq.gz
│   ├── 94f18411a12963ffa4b5e08b4aa8817d9b2990bd.nq.gz
│   ├── 956a96ae23150f12ada7a531b1a76fc4eaacdbfc.nq.gz
│   ├── 967403cebf5370d69939d9633b28cd5a87672a63.nq.gz
│   ├── 9775e67633377ba595e691e7d7be9f2807799055.nq.gz
│   ├── 9839fddb1476356e37346478e2b11731a1f81e73.nq.gz
│   ├── 987b069a84f8cf3d312ea0b91b1715769d883837.nq.gz
│   ├── 9d6601561a10f278f3fbf99908239ce5f4afc8b0.nq.gz
│   ├── 9eb4041354f75e958d55ff20341aafca103d6330.nq.gz
│   ├── a27b13cd8e74ce99e5d665c11b7cd9da88ee51a1.nq.gz
│   ├── a34e9db44969281329bf1f694e87ff05241652fb.nq.gz
│   ├── a5e00d2a783369abaa6438d8a70cc6d9f267c791.nq.gz
│   ├── a8b310f426d8828164f21d529dbd4a3e313e594e.nq.gz
│   ├── abc939e97e4af5dde2e417505b0f6041ed9fefe9.nq.gz
│   ├── b1ba2d8ac1e94e53a227c89b8e5d86641ede60ab.nq.gz
│   ├── b3d066c7ffb3d171e1f7a257b15d0c5d2fa1c1ca.nq.gz
│   ├── b58c4f58e4187e9e65e0a5476099ac7012a1b791.nq.gz
│   ├── b9fe170038b3465f87e27bb5ba45217d1935e714.nq.gz
│   ├── be896c4c1c019fd5d1377e5431434ce3014c6937.nq.gz
│   ├── becff4aa449a408a86f8d9c513b85208224a9e1b.nq.gz
│   ├── bfc8bb913e56f88a9c9e9f5760121434f0268098.nq.gz
│   ├── bfd6038178fb1eccc502765706afa69e28d5726c.nq.gz
│   ├── c2a337e602d3a18c797941743e5c3367a525fe36.nq.gz
│   ├── c2cebb1a49e30c53bd0789854a80a6244a1e6dbf.nq.gz
│   ├── c428fb58b990cd6ca90aec09c968808789a2fc1d.nq.gz
│   ├── c57efacbab61863693bfe34cb3b6e5e56ae22f49.nq.gz
│   ├── c74e615a419f5516a0cf235abf473c87046f6241.nq.gz
│   ├── c7f20abc81d0e581e52fcd580d41ee264a2e6a9a.nq.gz
│   ├── cbcd7bca741c1246098371c77485e5e361b9fa2c.nq.gz
│   ├── cbd1aa89e927d8d54b49fe666bf17244c3c46a7b.nq.gz
│   ├── ccf0eeaba3f3ecde4d615885ae12c124298c79ff.nq.gz
│   ├── cfbe75466e133c05b8efcb1cc2b18614b17f42a2.nq.gz
│   ├── d31b4af2bea2d18c211ed8bb1de2aeb7f0a7ab58.nq.gz
│   ├── d34de0e0f613d797976249fe044ac8258edae3ae.nq.gz
│   ├── d63499a22735e4d0e1f65b6592b38d1d6fd2b079.nq.gz
│   ├── d7600d1924ffb44b27e8233203fc1a41649e2890.nq.gz
│   ├── d845a0e50a897444836a25a8ecf6b65990932111.nq.gz
│   ├── d9df1b35faf8a1b464b704d7d8acaf1bfa11743c.nq.gz
│   ├── da9435e6bd3842c99db78d22c32a9ee6c10c0ff8.nq.gz
│   ├── db2c9e653538d12f6204bcc50ec19e1d606abbae.nq.gz
│   ├── db5e1607fb899a2be70cfb474f6474617c9434c2.nq.gz
│   ├── df0eddc5e79ef4d95c2166325c5ba20912c431b3.nq.gz
│   ├── e69c5e39a30ce8d112e012cac36289e77691a9b7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebcc00b591219de779af94fea0b6c28e54c0eca0.nq.gz
│   ├── ecabe2ebf9680c6352cbb1cc6442a71fab7992ee.nq.gz
│   ├── ee6e20b841e1f02cebda4fa87d9c84fdd213dd74.nq.gz
│   ├── efb6865d32be987400ad6c386b481977e8eab096.nq.gz
│   ├── effd2479f47ade61a13ddafbe3b53ed84ab88e8b.nq.gz
│   ├── f08a95938a261bc24360a7fff3647aabadf5ca92.nq.gz
│   ├── f24af52a72d65ff56f13bb86c87b0b9edf8f140e.nq.gz
│   ├── f43afa722fc5e53f3b6b1260109d9e8e4bfaac5c.nq.gz
│   ├── f4abe6d8b58dc8f738ac5f41c655c99eaf16fb6e.nq.gz
│   ├── f5e61d0ccd92eae53e3435c657ddb57faa2fbf4c.nq.gz
│   ├── f6e1f307b98ba30bc267c6d886fb1ea87ba91f28.nq.gz
│   ├── f705532a85f1074bc5ba76c54451daa1e2bbebba.nq.gz
│   ├── f915f90acbda0afee58b36bcfc2f8b8a08863484.nq.gz
│   ├── f9dab6d00cce20575e4de8ea81f88e1ef61255a6.nq.gz
│   ├── fb9096789d4ea7b8d33a27229453aa24d9ce7bad.nq.gz
│   └── ff5fab3b8b0ccf00e1d67935346c661a1fe8b23f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c0ccb5facf6db1c2ee4dffdde80ad9c06bc9b587.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 149 files
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

[bokeh/bokeh_sampledata](https://github.com/bokeh/bokeh_sampledata)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
