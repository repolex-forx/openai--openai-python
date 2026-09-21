# Repolex Knowledge Graph of openai/openai-python

RDF knowledge graph data for [openai/openai-python](https://github.com/openai/openai-python), parsed by [repolex](https://repolex.ai).

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
lexq download openai/openai-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0a4ca536f356aa23a021962b442d0c187559326d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 15afa21e54952c06e2ac4d3e3a82f144c2cf9ed9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3e0c05b84a2056870abf3bd6a5e7849020209cc3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 481ff6ef4c050469fa971746fb14b675d90a2e56
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5ae2cc10e4140d36aa236fa7c0bc5ce5ff190a01
│   │   │   └── chunk-001.nq.gz
│   │   ├── 656e3cab4a18262a49b961d41293367e45ee71b9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 750354ed65565b31d0547bf00f4f3180ac1bfeef
│   │   │   └── chunk-001.nq.gz
│   │   ├── 921c330d4baebb04bbdb8070e9ced539cf49d97a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9b1bb6ee10d4a0a04d04b1f67907f3747c57f5a2
│   │   │   └── chunk-001.nq.gz
│   │   ├── acd0c54d8a68efeedde0e5b4e6c310eef1ce7867
│   │   │   └── chunk-001.nq.gz
│   │   └── fc7f598efa70c6bef5ad15d1a8c9dfcd0fbd33fa
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0a4ca536f356aa23a021962b442d0c187559326d.nq.gz
│   │   ├── 15afa21e54952c06e2ac4d3e3a82f144c2cf9ed9.nq.gz
│   │   ├── 3e0c05b84a2056870abf3bd6a5e7849020209cc3.nq.gz
│   │   ├── 481ff6ef4c050469fa971746fb14b675d90a2e56.nq.gz
│   │   ├── 5ae2cc10e4140d36aa236fa7c0bc5ce5ff190a01.nq.gz
│   │   ├── 656e3cab4a18262a49b961d41293367e45ee71b9.nq.gz
│   │   ├── 750354ed65565b31d0547bf00f4f3180ac1bfeef.nq.gz
│   │   ├── 921c330d4baebb04bbdb8070e9ced539cf49d97a.nq.gz
│   │   ├── 9b1bb6ee10d4a0a04d04b1f67907f3747c57f5a2.nq.gz
│   │   ├── acd0c54d8a68efeedde0e5b4e6c310eef1ce7867.nq.gz
│   │   └── fc7f598efa70c6bef5ad15d1a8c9dfcd0fbd33fa.nq.gz
│   └── repolex
│       ├── 0a4ca536f356aa23a021962b442d0c187559326d
│       │   └── chunk-001.nq.gz
│       ├── 15afa21e54952c06e2ac4d3e3a82f144c2cf9ed9
│       │   └── chunk-001.nq.gz
│       ├── 3e0c05b84a2056870abf3bd6a5e7849020209cc3
│       │   └── chunk-001.nq.gz
│       ├── 481ff6ef4c050469fa971746fb14b675d90a2e56
│       │   └── chunk-001.nq.gz
│       ├── 5ae2cc10e4140d36aa236fa7c0bc5ce5ff190a01
│       │   └── chunk-001.nq.gz
│       ├── 656e3cab4a18262a49b961d41293367e45ee71b9
│       │   └── chunk-001.nq.gz
│       ├── 750354ed65565b31d0547bf00f4f3180ac1bfeef
│       │   └── chunk-001.nq.gz
│       ├── 921c330d4baebb04bbdb8070e9ced539cf49d97a
│       │   └── chunk-001.nq.gz
│       ├── 9b1bb6ee10d4a0a04d04b1f67907f3747c57f5a2
│       │   └── chunk-001.nq.gz
│       ├── acd0c54d8a68efeedde0e5b4e6c310eef1ce7867
│       │   └── chunk-001.nq.gz
│       └── fc7f598efa70c6bef5ad15d1a8c9dfcd0fbd33fa
│           └── chunk-001.nq.gz
└── blob
    ├── 0056727fa04c92cb19edcc80929c3311e3e27627.nq.gz
    ├── 005a32870e04e10d904ce3316491eb60e8720790.nq.gz
    ├── 005f4d1f0d9207351f228b46b9bb927ca3efeff3.nq.gz
    ├── 013f22d0df081e44a697541c216e42485cb6949d.nq.gz
    ├── 017218fa6e3ace8d42ad745d4649bfd341535460.nq.gz
    ├── 017c6d699bf8b1c8e69357a0eca1679705c1226e.nq.gz
    ├── 0198c6e866ea3b86df84708ea2a4035bf5860ff5.nq.gz
    ├── 01a08ab5a93de69d97a4639113dfa0bede48ddba.nq.gz
    ├── 01bae80562b6a9feef68b83b1a27deecca0617ee.nq.gz
    ├── 01ec43af325ecddf66ecec01580cacfb79b43f5f.nq.gz
    ├── 020ff41d583f9d57ac0f32aa490e2fba34560ffa.nq.gz
    ├── 020ffeb2ca2061c9f3a606b154672ed55b7cd7c7.nq.gz
    ├── 022ddb406a695f20eb41668e40733efe1daeef6a.nq.gz
    ├── 0275859d274c6863b712fc86a1d59e059b44d6a4.nq.gz
    ├── 02804c30dafe23126effd67be4c8aa527cbc0017.nq.gz
    ├── 02bdfdcf4f487c4c2764049ef0e45ef6b516fe63.nq.gz
    ├── 02ca8250ce4083a67a793588d6235915df52c661.nq.gz
    ├── 03439fb17fab4fba2166cb43d04ca0bfd0508c11.nq.gz
    ├── 034547f3083e2201536c5210826a3a9c8057e84c.nq.gz
    ├── 0374b9b457206db07cb9f0d0228d0dd1c2a265a8.nq.gz
    ├── 0399bbf7427a4942c38a63cbbbaca1cbe91ccad5.nq.gz
    ├── 03be59a29f6b2828e87800ec4220a73834ca6925.nq.gz
    ├── 040a058df6a2d8b6c17ba8fbf143b2c8b8729d33.nq.gz
    ├── 042db29af5210fa0d26d6dfcdef2ffdba470f1e0.nq.gz
    ├── 043b43a030eb0079e138de73c280b1834e397a7d.nq.gz
    ├── 044c014b19b1ed49e2ccb64f64da843a59f53de5.nq.gz
    ├── 044ed525d181506e7bbe2572a9179fad8e20dfa8.nq.gz
    ├── 046e5202221867895a8680277cd28b0e4cb5a298.nq.gz
    ├── 0498cf7f6f76af40107553ee8cb5ea419f3cc304.nq.gz
    ├── 049ca54429600683f29cec65f075b7d2a62cadb8.nq.gz
    ├── 04f8e51abdb6e79310377639c18499e16e9f5564.nq.gz
    ├── 0503301f16324ac7e8563bac03e7896f4210dd19.nq.gz
    ├── 051b951edeeb27fa34546dbc958883f94e14fdec.nq.gz
    ├── 058d874c2967a24783bcc01c45e51c5c0a5b638c.nq.gz
    ├── 05916bb6689b2441417d371d759bcece14896d98.nq.gz
    ├── 05cc2c2f6780bc41230cddf78664ae447fb9796d.nq.gz
    ├── 05f24d62380b713b8f26c3c773f7606732e797e7.nq.gz
    ├── 05f3401d2d1015a72442dd278e08a8db77354091.nq.gz
    ├── 0638f40086c56e9fa4e02222f5b4c0427b829654.nq.gz
    ├── 064267a5aa5a15d585809fe1e4b4c62e663ae2c9.nq.gz
    ├── 06b8a285bfda322ec1d8f16b7748ea68ab1004be.nq.gz
    ├── 073bfc69a7ae83145b0807448bc2d031541015e3.nq.gz
    ├── 0751a655866484b526c0ab4220fe8f591e583548.nq.gz
    ├── 07585fe2390395716b162a6f45c181b33f5ea851.nq.gz
    ├── 075f5bd290755b3874bcbecbc55b4c922a82bd2c.nq.gz
    ├── 075ff9764412316c537626ff2c24651793dc7fa2.nq.gz
    ├── 0798c2e12378ffba43e2184455d30a2725961d70.nq.gz
    ├── 07f4d6729dc6789876fdaa5876e654fd62d5718d.nq.gz
    ├── 0803c313d114a11f500d0508999cca7fa8d1f052.nq.gz
    ├── 080613df0d6020e933f892f35d8dc44b6bcadc09.nq.gz
    ├── 08591f43f41a5245e1177ab5d584942175cecec1.nq.gz
    ├── 08596ef9ea298c540b7a46ce0112419653936d6d.nq.gz
    ├── 08cf29390a724d10f6464b63084dbcae85e258da.nq.gz
    ├── 08e1b146014c7d074af2dce096d1fae8751886bd.nq.gz
    ├── 08ea9300c36b09cad2d9d7593ae940748bd36cf6.nq.gz
    ├── 09016dfedb2d29233e9c431abaf12f97fa9868a1.nq.gz
    ├── 0907c3c2a74fc93abdea0f3c26229fb97dbf58d0.nq.gz
    ├── 09619a33940fa80e077837a280afbb76e1986db2.nq.gz
    ├── 09c12876ca66fdf6677fadbddbe62298559b22e6.nq.gz
    ├── 09cd357027867f15c24bff1ec59e0b059e6341c8.nq.gz
    ├── 09fdd9507e14a6fb197a2df4147ec2960e2bfa6d.nq.gz
    ├── 09fec5bd5897bd380ae16d19a5e3168a0693e734.nq.gz
    ├── 0a0e846873fea87c21fd63bdc9959a07f07b0879.nq.gz
    ├── 0a382bddee74abb5095e9f16b344e091d384d928.nq.gz
    ├── 0a541cb23d7d1aaba30f4070f934848b8cdcf92c.nq.gz
    ├── 0a5db533231a1be3939b8ba126449a8c4103c126.nq.gz
    ├── 0a8c1371e0155ec810df5b99fed8e79e195df653.nq.gz
    ├── 0a93baf45264d2a8acea2d419cb2310aa578dee3.nq.gz
    ├── 0aca59ce11701dac55186c206745f84fb2748450.nq.gz
    ├── 0b146bc0bce82eb9e7eed13a1d28055a329298d7.nq.gz
    ├── 0b163a9e78488483d72ede5a4d5df911ecb59f93.nq.gz
    ├── 0b28f6ea23d4fe145da316641ec85506233c03d4.nq.gz
    ├── 0b9a2d23c7247b05262174a0f2a61f3934648db1.nq.gz
    ├── 0be935c54d00b810ae00f3c99745be3bf54126db.nq.gz
    ├── 0cf2bd2fd9d04040ba557f3f6658e6c4134d26d4.nq.gz
    ├── 0cfff85dad92f7ec8f7c698ac7ea435a143ab6cc.nq.gz
    ├── 0d4ef7b71c403f5d8d580e5f4bdc73519d962956.nq.gz
    ├── 0da88c679c27f27642b9162a17780c8930cc3bdc.nq.gz
    ├── 0db7d8ff79c60cf2503785d0cd6c7bf4193e55df.nq.gz
    ├── 0dbcc90f3999d7537fa8c0674de0efa0280b145c.nq.gz
    ├── 0e05226c9415054bea9e5130de9950428941c733.nq.gz
    ├── 0e336a9261b62cdecfc4697c959af159b44fa6b2.nq.gz
    ├── 0e33aa84c8e27e263e0fdca40e0bdd5dd97e5a4b.nq.gz
    ├── 0e438a3c61dfa89fd9c589e283f32812f6191fbc.nq.gz
    ├── 0e464ac93422febca5c4a84bfd96f693ea02b59b.nq.gz
    ├── 0eb6bf954f865a23fdbf15d4a8e902e8725f40f8.nq.gz
    ├── 0ed1e81ffc97ea8fd0b14a8586522fa165ee0d74.nq.gz
    ├── 0ed5fbaa802f5fd84c75cf4bd73b2ecb69bd30f5.nq.gz
    ├── 0edcfc76b61a2c582d2213675c0bcb5157bf0edb.nq.gz
    ├── 0efdfca968c8c781874b41dd95c7b829215b29e1.nq.gz
    ├── 0f239a33c6df82d00988a48777a64ab13449b72f.nq.gz
    ├── 0f6fb04d7d309d33b46b13d3e3fbe02a0c08b42b.nq.gz
    ├── 0f8bf7b0e76f84fd42a704a5097fb56817654aea.nq.gz
    ├── 0f91a6218a635d64f7e081dca562bb83206f09bb.nq.gz
    ├── 0fc71749e90e9eb20067f0bc671cc76d71915906.nq.gz
    ├── 1033c319d4a963fc84c98fa81c765f8d5c48d751.nq.gz
    ├── 1065632910696eaa89305338920fd9adc7861793.nq.gz
    ├── 118f0b5f720784e6f2be2ad5c22ae4535963dd7b.nq.gz
    ├── 11a2dfccbd6be1fb477576ab88a6a43379d12704.nq.gz
    ├── 122ee10078a57dfa8bcad62357af217c9e2dd290.nq.gz
    ├── 1231bbdd80739b4507457af378aefa6b62c03da7.nq.gz
    ├── 12478e896dd4f9c1f80d3bb59e69f16db519e736.nq.gz
    ├── 12b2c41ca860673b159d714eda412de6a622f6b4.nq.gz
    ├── 12d1056f9ec2ae80dfa5862832d6446def23bf93.nq.gz
    ├── 12d3b3aa2887d27c5babd492bfe1eb04a07d2379.nq.gz
    ├── 12f1e1aea1ef5c5a84b5de73bcfdcf2e227f229d.nq.gz
    ├── 130260539a04eb004925df1df7094220358afdb4.nq.gz
    ├── 1348fed2b2de2ee4c48a059c7a195f0e09034377.nq.gz
    ├── 1367cb4bab9ddbcb6cf8663c93c34e5b482781f1.nq.gz
    ├── 13a12f55027c0f84beb48e74ee38fb9aa1e107fe.nq.gz
    ├── 13c10abf4d840c51453a26ce7b2d0e38476f4f20.nq.gz
    ├── 13db577160b100688488bf0703ceed84b0ddde50.nq.gz
    ├── 13ffa66d1ab706c1f74d87caec0bf43bd5f3fcd9.nq.gz
    ├── 140cd520c78479db0be071bae0fedcac6f7727a3.nq.gz
    ├── 14198251933f378bb602ba3b5b35173a9838b004.nq.gz
    ├── 143cef67a5c79f90a99292d5a18a898e795fe283.nq.gz
    ├── 1441304df6dbd2235a0f3bbeff1a96ab91d49d65.nq.gz
    ├── 147728603a2dec6b9f341f358beeecc05d6ee69b.nq.gz
    ├── 147fb879658c8980f46f1870b143dc33433c019d.nq.gz
    ├── 14f56a04cd7f6b2063c3c7a11ea0e0e70e4bc90c.nq.gz
    ├── 14f9224b416002d1de21fff09a1a5aab36143935.nq.gz
    ├── 15118f3388217aa6e415869b7fae9199e312d8ec.nq.gz
    ├── 15184e130bda7ed9b2c1c1818f564241064ae94a.nq.gz
    ├── 1520a97b0aae0e25fd64e543398def9b0ce15217.nq.gz
    ├── 152ce9cb77b36fa819a74da8d440dd355626d412.nq.gz
    ├── 15388d6172516fcdbfeff7620b78eb9db7c2d874.nq.gz
    ├── 15540fc73f16fa26917bee0c80e854cc77a788ab.nq.gz
    ├── 15a200ca173370ea86dfb6a07ffa258ad0589e5a.nq.gz
    ├── 15d5c6a8110580337891c90f335b0f053546db97.nq.gz
    ├── 15dc8254f3d41554b626549f11fd24b2c33ea8fb.nq.gz
    ├── 15e313b0d32172ec83a3c74c6618c2478df4d28b.nq.gz
    ├── 163a0d16d800ff0855eae4b379f193122b7c8d7c.nq.gz
    ├── 16a218438a3f00014a773275ba98bef52c52e91a.nq.gz
    ├── 16c82183c4215ef8792caea874107b5e114cbb5e.nq.gz
    ├── 16e0e11a0a3c00e86108a8c86754806089b98059.nq.gz
    ├── 1704b254241aa1e6e0bd2a2a1a349b90bdb24964.nq.gz
    ├── 17065bf30a5db30d3e6240f56d9f5713ce0e7767.nq.gz
    ├── 1726909a176a05395553a2e11fa5f5e19fc78507.nq.gz
    ├── 1744c90070fd3e6778a644b1899ba7ca4e4466d4.nq.gz
    ├── 17762771acd8c5c14aeeae1a2f55b379521b8357.nq.gz
    ├── 178150dc1587e7a82b88d594910b258d821d35fd.nq.gz
    ├── 17863bc067102ae62d604c9ecf730ee659660183.nq.gz
    ├── 1789f731b4fe325937b1cf57764bcc5eef48e41a.nq.gz
    ├── 17ab3de629fd2ffe2f638338a0d8a5bc66a8b561.nq.gz
    ├── 17d6bb36c9745e4910cb0692682ce23cac79dbbe.nq.gz
    ├── 17eaacd905de700c9d703254310ba361e2b61500.nq.gz
    ├── 1803d18cf64bdb71a73339b14e40afa95092e7fb.nq.gz
    ├── 181bede2d972c72da8f14f6d427eea2ba96d1867.nq.gz
    ├── 182a563dde10ec864a2235b561e66c03a2a4aa45.nq.gz
    ├── 183208d0ab219895dd51e99b4773a3f4018a403b.nq.gz
    ├── 186c03711a1f4d5fb765f7e85702296bd4fa328d.nq.gz
    ├── 1897aaf6ed420177af3876e80dfedf4b69f1da24.nq.gz
    ├── 191d3a1b04d79d3e25140071b4808ae5e69253cf.nq.gz
    ├── 193109f3ad2b3c00e59ad3f41ad32d9f704f5f23.nq.gz
    ├── 193c99328a7281698cb7a57ff8058d56716d9e66.nq.gz
    ├── 1948f8933b064d1f245ab4f81bdefd1fa5e2741a.nq.gz
    ├── 194e3f7d6a795b04ae65e2ecff955cef3d76748f.nq.gz
    ├── 197e39e7e96ea65c53264d24750144ad48fa6c16.nq.gz
    ├── 19c73b909bc114789925c17fca14b11f22a3cf80.nq.gz
    ├── 1a178384db9b3139cd468c25060ab9751bd19947.nq.gz
    ├── 1a22eb60cc2e3293a8aa7df03156afb231784f6c.nq.gz
    ├── 1a2c848cb3314c4ba29ee755d47f464c047e0c33.nq.gz
    ├── 1a58c2dfc32d173a85e3743621b53f1282cf6e42.nq.gz
    ├── 1a73bb0c7ec3aa731965b64ffd3f6c9c557d331c.nq.gz
    ├── 1a92d912facbc602d271b8e346e52b595d7df1a1.nq.gz
    ├── 1b04cb62ba08595293e32466561cfbf888457774.nq.gz
    └── 1b8d4a4d812de13335d41a097fa19b6f6d5e562a.nq.gz

28 directories, 200 files
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

[openai/openai-python](https://github.com/openai/openai-python)

---
*Parsed on 2026-09-21 by [repolex](https://repolex.ai)*
