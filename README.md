# Repolex Knowledge Graph of BerriAI/ai-gateway-bench

RDF knowledge graph data for [BerriAI/ai-gateway-bench](https://github.com/BerriAI/ai-gateway-bench), parsed by [repolex](https://repolex.ai).

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
rlex download BerriAI/ai-gateway-bench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 35ba690a53e9c7bea86d13dc077921b0faf02d97
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 35ba690a53e9c7bea86d13dc077921b0faf02d97
│           └── chunk-001.nq.gz
├── blob
│   ├── 006348194499b0ef17f7589f17d36cb3e465708e.nq.gz
│   ├── 01d81d2a1bd2162cd59b0bdf5e4eb00a761cdca6.nq.gz
│   ├── 05608ea3dffb8655df6382193dfc91626785d400.nq.gz
│   ├── 062a0a6dab32626e3a172c9499cb47eb6b06d314.nq.gz
│   ├── 064088131c8eb6c531060eda1ac79f5295d07b2f.nq.gz
│   ├── 07310bf1795f3f71314269311a6aca7e874f3a4a.nq.gz
│   ├── 078cc15b1e6763ef22ad99b01b924aeca6ae8d99.nq.gz
│   ├── 08195cda0a3e22c4e5dee26d9d662769bc676a08.nq.gz
│   ├── 0a120a89e2bbac1e231513ae31585404a3d1015f.nq.gz
│   ├── 0b23fe1ac5cba417b8ca7f7589e9928b880a079d.nq.gz
│   ├── 0b9da0d445db0fa3fb536571b45941e69b0d278d.nq.gz
│   ├── 0ce36a34b1b777f0bebb4f8d8cb239b5ffd1f3a2.nq.gz
│   ├── 0ec0427ef2029d83355c5eaa582a5913e595ad06.nq.gz
│   ├── 0f2d6a5db115e9bcc2de71ca1cb93a3be3a5dcc5.nq.gz
│   ├── 0f53ae44c51881a26262d440533d98b48483786c.nq.gz
│   ├── 0fcc075ce58dec34197fead15eb6459867025bf7.nq.gz
│   ├── 11bfb18d88d1dadc2196dc69080fa790f77dd342.nq.gz
│   ├── 15d00f38a6ec450c0873fd43024d8824a4093f5a.nq.gz
│   ├── 16217d1f9e5394ed6832a56f0826c0383e896eb0.nq.gz
│   ├── 17d492a5f7f8335a80dd5e01a5e5cacfab908fb0.nq.gz
│   ├── 18929ff90e0f0887c96637aa6ecaa47e9aa382b4.nq.gz
│   ├── 19a639536cf879477126dbc9fe7c9fc834960014.nq.gz
│   ├── 1c66e6bb2178600cdfe9fd51b9b86492164d0a5b.nq.gz
│   ├── 1ca2a53ce8d840472778cb592bb3245592a209e3.nq.gz
│   ├── 1f8805657224fc7acf2a358c32bce281137373ba.nq.gz
│   ├── 1fb74cd4a2a35740bb481491974aca407bb455d8.nq.gz
│   ├── 204fe47140fab07581931b14aa7a407949340ad7.nq.gz
│   ├── 20e3e48b1c868b61e6efb3db9a0239df30c6cd62.nq.gz
│   ├── 264c225df554433ba4fb3b88082b5e63de3ff61f.nq.gz
│   ├── 29b2fb9ff78d5b00be3880a7b1a7ef6057648b65.nq.gz
│   ├── 2ae6defbbdcdd63b0760e5d87e9132b67f02f662.nq.gz
│   ├── 2bc473cf7c7d37b5d1b14489edc836023dd9a676.nq.gz
│   ├── 2be23906282c76a4c9ef131492169f13861e198f.nq.gz
│   ├── 2be4b9699c05d5abb6e6dffa0ba8a8fc4df3f9ae.nq.gz
│   ├── 2ede169dd530b4b6fc7de2a08e425f472d0337f8.nq.gz
│   ├── 2fb2ae3f0900e0448b0b76ed5d4b551c4050a8b7.nq.gz
│   ├── 30b447e3bf91c3374cc22ad09fe267ea5890276a.nq.gz
│   ├── 33f79c0b1235f475e56aab5a90ba442ae7519f6c.nq.gz
│   ├── 3597907a9d07c76d8fa33625f00da67a4e8fe561.nq.gz
│   ├── 38ce4f7a74f596dad28e9f7f92946fd84b0ba767.nq.gz
│   ├── 391d2360e92e416f9f5327ae9926db8ae6ee76a2.nq.gz
│   ├── 3a0ccbc2d0ec715dd8e5a934007e9bb70bf3c4ad.nq.gz
│   ├── 3b5920fb7c54de93e855df859d0e140cfa8ffab4.nq.gz
│   ├── 3bbd3f07b9ded59f586bef9904874959cadaf27c.nq.gz
│   ├── 3db959735f869b8b6ba2274b089075fdac1da204.nq.gz
│   ├── 3ee4e69f9744784e326070c7e351275269e21ed2.nq.gz
│   ├── 3ef2b53637b5393c0927d53d106f702bbe442dd5.nq.gz
│   ├── 3fa95ad61ae7afbfd0e19a67ae8d770557a9c0da.nq.gz
│   ├── 41eaccedb384eeff4eab954087844456d07c359a.nq.gz
│   ├── 42a73caa80b716e275a57f6d62d5ce8a9bb9380a.nq.gz
│   ├── 45cd538c0eba1563d4e6224a62efa3cfff1aa3a8.nq.gz
│   ├── 45f2f96076cc9412a5d204d0a867d29f048c19ed.nq.gz
│   ├── 4686bc97d87d89367a4124d77a7faaeee2d04df3.nq.gz
│   ├── 469f871598783e2f4984573022dc1a26b3922641.nq.gz
│   ├── 470ccbea0e0522a0df6b2947f4d3682c0245f03e.nq.gz
│   ├── 48c1ada9c0081c4b599af39683b344fb2fa3b6d3.nq.gz
│   ├── 48ea035b1cc516331ef9d8308321989d70ab73cb.nq.gz
│   ├── 4c4cc668229085af011a2e4e82b9e370c7d3678d.nq.gz
│   ├── 4cbdf546ed29422efee4f66a571bf4c455c7f928.nq.gz
│   ├── 529ac1f84ebe7c2ddfe420dd25649f7ada3e86cb.nq.gz
│   ├── 538c28e3364e98b23f045a07415cede32a0a3bf5.nq.gz
│   ├── 53fab790eff565e466e5e0da0e5b661b607cd078.nq.gz
│   ├── 5428950ecd80e6bae20f6fa325b16349902c6e56.nq.gz
│   ├── 54cf22570e7fc7047207216cbc6cfe2feea39388.nq.gz
│   ├── 55a6cc9663a298c44dfe09ec6139f29fd2eff47b.nq.gz
│   ├── 56c6ae9e2c0e4637dc5814289a494e0188dfdb25.nq.gz
│   ├── 57bd3f5ee822122b68143648cd151d6cd88708c7.nq.gz
│   ├── 584a06383d72481cda77bbe9719286eb1e40ff38.nq.gz
│   ├── 5baf5060d834f24f1ca3ccf4e4e1aaa3053e8b6c.nq.gz
│   ├── 5bc4c3b12de51f1e480fdd8dd4f19d23a8427999.nq.gz
│   ├── 5c00734f9183ce67450847f307d76baa03e8587c.nq.gz
│   ├── 61dd4051f56539f385441135bafe4dff284f1980.nq.gz
│   ├── 6286bf1be47b03f5c031a5c7c4eb145ea0f6685e.nq.gz
│   ├── 62fd571e5b7c061bc57061d0d965b5fbc4dbae46.nq.gz
│   ├── 637ba072682bf8802656b4b057574f86c75d4e8e.nq.gz
│   ├── 63c2fcc2a34414a69c5ececf6266c57def9f6efd.nq.gz
│   ├── 64690f023f16e684b671420b15ff7b03e1670a6f.nq.gz
│   ├── 679f6babfb19b2bf54ea370d10a60a72c20432bb.nq.gz
│   ├── 68270d6f54984556a0e6f778cee7d434761f324d.nq.gz
│   ├── 68aac11deed420ca5708f1c138a9e06c28e89e9a.nq.gz
│   ├── 6b1fe71669e44b5c2a4fb136be42745c53eb087b.nq.gz
│   ├── 6b4065fc8f646321b1eaea6afd2037f2f2481ab0.nq.gz
│   ├── 6d511c1a850dbdf543093c8fac2b6c82ed041168.nq.gz
│   ├── 6f60558e2215b972c9a96e8c57b6a6e9c421f79e.nq.gz
│   ├── 72a002a4df5592cc163acf491c1efc2fe080634a.nq.gz
│   ├── 734961d10e10629d1923eb6801fd4659523f6530.nq.gz
│   ├── 7435db45c5f6eb901191622cedf7033a996ce5b1.nq.gz
│   ├── 75c243d46d398dfd7e7ba8719011dc1aa656caa6.nq.gz
│   ├── 76b28b561a7be14a0141ad38f61c35a6812aad0c.nq.gz
│   ├── 77675318e8a3d41f7dc42b67009c683d7f730b74.nq.gz
│   ├── 78534c10fea6fc34c991de412aa272266ed527ef.nq.gz
│   ├── 78f1139d483a32d5198de45e4f8f4888ca2a0f83.nq.gz
│   ├── 7911014dfa98ea21aff33879e4522a5b10dc033b.nq.gz
│   ├── 7b051b07116628950b15e37e65e24f7c3c3017d4.nq.gz
│   ├── 7e1dabae160f637db1d7ea42555f2a6c2c8969f3.nq.gz
│   ├── 7fef87b6c64115eb2d8677864d1c3c2ce800c198.nq.gz
│   ├── 804c6a38e1d208f24a7882856cc3a4975473440f.nq.gz
│   ├── 8193780f5d4befd42f45743fd5f617ea2adacc7b.nq.gz
│   ├── 8348da2944fc82b441c7fc3495a2dbca7a55be42.nq.gz
│   ├── 866e4710432cd3004f3993f5be553fbd8b05c2f4.nq.gz
│   ├── 867cdcef1582db02fd397041aff40b6d4ebd699c.nq.gz
│   ├── 881340d754c43f8e73c06bd4fd344ed998e47723.nq.gz
│   ├── 8a76c609493377ee0dc4e8aca185c22e96602fd1.nq.gz
│   ├── 8b275a130b94736617a5ccdbefc9e9eb18f0acba.nq.gz
│   ├── 8b4f53141d812b89abbc8517c85c392cf0a55606.nq.gz
│   ├── 8bb553e5c97c2811534992155675c3d60dc69f1c.nq.gz
│   ├── 8cca75fd901ed8a73846c30e9ff4f16b32004345.nq.gz
│   ├── 8deadb6fbfd2cafdd8fa29cfbaf4472ba6f628b6.nq.gz
│   ├── 8e4eae1864d9632bac416dc0b045552b0987f91c.nq.gz
│   ├── 924b310c1d1dd41c377182c98b99209dbee4d450.nq.gz
│   ├── 925b449ba46c225a4b4566748a27d39102ec63d5.nq.gz
│   ├── 93185daa61ae6f14ab3354c56e437c86e609d6e2.nq.gz
│   ├── 997b7c1ffe2f57525a169b6fced229e3797858a4.nq.gz
│   ├── 99b0159debf6337bcee5a78b0379110095a426a3.nq.gz
│   ├── 9a3f1c95eca0cf9c60295d24d615245f7e5a8f20.nq.gz
│   ├── 9dc1dfa36c9748d5d98409d8d498d0b3ce711982.nq.gz
│   ├── 9dea073d67de48327e041b79337c7d9de9acf23d.nq.gz
│   ├── 9f538fe46e05924ac3cc8f8b7daef128124037bb.nq.gz
│   ├── a5168f30678380d639dd83bfbdaa39b541d2d593.nq.gz
│   ├── a6aee15bea3c6931949532d6647d3f7eecedf961.nq.gz
│   ├── a74a7436b7003c45c92138923bc0aa8fc0c8ad1c.nq.gz
│   ├── a7e9d2669ffe76d6b45ac5697693d81c7643f3f0.nq.gz
│   ├── a87b2705b409a4b07857f74efb30c7ae38011805.nq.gz
│   ├── aa3543e1d6412b4a1b6a376602001a059ad00125.nq.gz
│   ├── b0aac4872fe25bd4df6bd3309d1714765e063ad4.nq.gz
│   ├── b0d6e5ba570b91d7d476d21ddc5d3ae9539088e6.nq.gz
│   ├── b4315d7770557748c7d581fe4ac870a42840a2cb.nq.gz
│   ├── b69e6e4bb94f5dab3111a5fde8ed70ee8ea75f8f.nq.gz
│   ├── b6cc05c661b63e4e7ca093974c56d3bccc4cb793.nq.gz
│   ├── bb8c31301b29cae3a546626919e1424ba218fdf0.nq.gz
│   ├── bb94f3e1aa07e89f791a01a12d510ab7181ade80.nq.gz
│   ├── bcb86ef8e49f4ff089b7e9f4b95496c9ce1e1ad9.nq.gz
│   ├── bd6d384c7b7624f39357237c3a53e7dc20b8da38.nq.gz
│   ├── bd9c76fc7d9c493af9090dbd67d9c1f46c1763de.nq.gz
│   ├── bdd3dc028f2c12812377bef8397ea5e3bc79b0dc.nq.gz
│   ├── bde67daccba453cea3b4e53c545638411d83af19.nq.gz
│   ├── c0087ae8543b844292615a67464f76a1d55c5ddd.nq.gz
│   ├── c164013058c0a7de2669c7b55e572d371a9d236a.nq.gz
│   ├── c2d7d9e4f69cd72d34e47da9e65b3441a809279d.nq.gz
│   ├── c343d3c3c9e697d44b1d065734cf3f7787c2a2e9.nq.gz
│   ├── c5d64d07f3ccfd15805e6146056339600539c2c3.nq.gz
│   ├── c6b64f360797f6ab0f56d25dc6bcd09192a9b65d.nq.gz
│   ├── c7d36ff0a0eb9ab87647bbb9e862eaf3b9b4c336.nq.gz
│   ├── cc43aad7436b8423219e53fead4b426c675c88a0.nq.gz
│   ├── cccbc8c6b065bc846c4b1393b50316520d103fc1.nq.gz
│   ├── cd9833b13ceec0e9290f977539b0b29b5c7d1672.nq.gz
│   ├── cf378e5ccd348d9e745a8960de97f4e915c77c84.nq.gz
│   ├── cfdcdd7e4772ae30c92850f6ff0668ee0bc8e795.nq.gz
│   ├── d1061b0309c70faea77ec9bd98ad54db393418c7.nq.gz
│   ├── d20c6ed0fc99341053fdf56af426e345569cd5da.nq.gz
│   ├── d2ebe64addb78ac51887aee73d88a06ab18738fe.nq.gz
│   ├── d5725ddbe00e5a58bba9a7359e8a532997c7d44c.nq.gz
│   ├── d5e45982de99c00e7750fbe779704fc0311788aa.nq.gz
│   ├── d633ccc6a76476692febffed0f81af4f0ffbd9f4.nq.gz
│   ├── d826ac8a8f8ce8f3abb091b6f88e3710839bbc8a.nq.gz
│   ├── d8bb18ebda67a20a2f1ed144747f453cab1bf29c.nq.gz
│   ├── d9482711b49f9d1d2009cca5caf34740e9fc3e66.nq.gz
│   ├── da5f6f3424c610cae73ea34de6c87636ef0c4364.nq.gz
│   ├── dbf48d0e905e613703aa362f202b13e28ff434bd.nq.gz
│   ├── dd58f810af5915dfb2949fd51bc4f3aefb124e32.nq.gz
│   ├── de18ab11b0247a660941406790d4543308d751da.nq.gz
│   ├── df89621d6ab21c62a93a729c5f6383d59ee8c39d.nq.gz
│   ├── e0c609de61b1649d6683b9febe15d57857989902.nq.gz
│   ├── e1ceb03036fe9effc38deede57dfb63723ae840f.nq.gz
│   ├── e3d425c8c0ff4e9d51e7fe6b3f2f80b9741ec879.nq.gz
│   ├── e43b4376fe47a1d6360a3a56e7a0b56ba87593e3.nq.gz
│   ├── e5b8de3036756f8209148968cf9f5a213ba47bac.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7133da37246bcdc8cd382182a60390999120384.nq.gz
│   ├── e955cc57036d8a19957c5059c326db649fe3081b.nq.gz
│   ├── eb413a747703f8bb2d3a2d249a96d3c4993c4f16.nq.gz
│   ├── eb5a5e445ba4fc5f15bf9495effef66eaa7fc3cc.nq.gz
│   ├── ec8f80e150e51d323d9fdac7f5418a71f9ada418.nq.gz
│   ├── ed319c638fcc830b2249dbe5b9c2c7e6a13fcaed.nq.gz
│   ├── eda368bc2eba199527a9037d03b8006d64af760d.nq.gz
│   ├── ee0dec19d4b381f68a8ce40a9cdb3961cc2d9520.nq.gz
│   ├── ee32b1b611c1ba096cb5046b32acdcfc3148011b.nq.gz
│   ├── ee3f4fd52b2a8ed1a59feeb35c0c5035e77bcb1d.nq.gz
│   ├── f0e1d860839015429237b05138f31c609e1a89b1.nq.gz
│   ├── f1d23bc1faf4b6fe6dd803a9b7e7018a2fbfb189.nq.gz
│   ├── f2ec3141899bc5daa3a84d6d4aec266dedec6bad.nq.gz
│   ├── f39f2a87724b00ad7011cfa2c0eb1bfa41750379.nq.gz
│   ├── f3ea933bb8e2aad95a7acb741acc27a8fe762943.nq.gz
│   ├── f65a1464e30c990612e266eae96a869ad5f8d439.nq.gz
│   ├── f66a3e5ec79e1956db021ec158b350b365ff349c.nq.gz
│   ├── f84a81b464c6bfc7254bf911b8f56693d37c679a.nq.gz
│   ├── f9234b6d5120e64f60071e167ab1888a3df242af.nq.gz
│   ├── f925cc403c419bb74bfed5849e419ce0e1e1f61d.nq.gz
│   ├── f9ad96ed67b6a1c1b8a39c45855ff68b2f866fc9.nq.gz
│   ├── fa9c161ccf44ec6e9efab7223757ffa8bbc91832.nq.gz
│   ├── fa9c9751799e695579a1a3f5b55435889a0f538c.nq.gz
│   ├── ff2b7096d7b6b85a51084079363c6e5c0d6dc6d6.nq.gz
│   └── ff94a57ca8537851dc2fe609aac4a0b075134c82.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 35ba690a53e9c7bea86d13dc077921b0faf02d97.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 200 files
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

[BerriAI/ai-gateway-bench](https://github.com/BerriAI/ai-gateway-bench)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
