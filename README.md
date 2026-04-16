# Repolex Knowledge Graph of anthropics/claude-code-action

RDF knowledge graph data for [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/claude-code-action
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ff1acb3ee319fa302837dad6e17c2f36c0d98ea
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2ff1acb3ee319fa302837dad6e17c2f36c0d98ea.nq.gz
│   └── repolex
│       └── 2ff1acb3ee319fa302837dad6e17c2f36c0d98ea
│           └── chunk-001.nq.gz
├── blob
│   ├── 0056dd66b3b8b282d911443daacc754274f01ce6.nq.gz
│   ├── 00b4bae03cdf4804e0920ac0211ba7c61a3ba5fc.nq.gz
│   ├── 03b5d86ce2c52f5dec97f816784a814a3a349314.nq.gz
│   ├── 06c15c847b2795e7a05fde75b7b1b846f026a39e.nq.gz
│   ├── 079565c7b84e52ed9a428ec07d6be1d9351e8109.nq.gz
│   ├── 088d6cf160d2a6cd37dd300963348c41b466cbd0.nq.gz
│   ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
│   ├── 0d1232fe585c9d9b00e39016bd000dc0e772c1f1.nq.gz
│   ├── 0d57a9c16e9db66613ee5bec2f1df6dad56aa7df.nq.gz
│   ├── 0d5c0bbe26692840098d1e8bb5cfe61b331fea06.nq.gz
│   ├── 0d69cf4566e6849dfc2841aa8684e1524cdc8808.nq.gz
│   ├── 0eb12e74472801d2c4685457f66bb2e28123b4f8.nq.gz
│   ├── 0fe68414fb483e439c824dc032c06405871f8b7c.nq.gz
│   ├── 1243035b759cffdab97e609f7fa934955277afe2.nq.gz
│   ├── 13acd792a210137c740e5c1613f8da9955bbd51e.nq.gz
│   ├── 13ba45a03a0764220d67014c4d320886e9a6ce7b.nq.gz
│   ├── 13e5f5b83126b32b7893e36d76d3dd4f38923467.nq.gz
│   ├── 1404b0d64409c7bc2beabf9474d88b3743e8293a.nq.gz
│   ├── 15821596f963d970653553101f75c8da3d7db1b5.nq.gz
│   ├── 15a5324335c859f4b4d68cc248ba9f6142267f40.nq.gz
│   ├── 187232f0985c3449098d244b8d699de4cdbbc05f.nq.gz
│   ├── 1b21ab2fb7bcff9d167eb6e2602da8032c0c9f07.nq.gz
│   ├── 1bd07290f50186ab6d5cf27c402a3e00e8349b6b.nq.gz
│   ├── 1d456dd7848e41dc2db5b1f46b62a6996717a89c.nq.gz
│   ├── 1d6545755258e734eb0f843c911393698667121f.nq.gz
│   ├── 1e819fff769090232d42f7106bdca942dc5edb00.nq.gz
│   ├── 1f28da37e0427870d5f3b607f129b704674eabf1.nq.gz
│   ├── 219f1cbc338c9e361030170a189678f21411c793.nq.gz
│   ├── 21fb13f8ab05da02d1f2ae40a522b0f0aa053f3a.nq.gz
│   ├── 22758e9e93f89384311c9eb770fa8e09eebeeb35.nq.gz
│   ├── 236ac7fd55f648503e636925547c549c162fcbf2.nq.gz
│   ├── 27a15df0b4c3393d74039f48c9fda3b338ae38f2.nq.gz
│   ├── 283743274265d9ccb4cb42af64ef66963bacc457.nq.gz
│   ├── 2aebae705d12e3d4940d57b90996922ee6621cfb.nq.gz
│   ├── 2c29d9ff6becdb3a57d7c56ed0ed508ee7030dca.nq.gz
│   ├── 2c628674727eb1f203f122ad0f52ed16e76bd8a2.nq.gz
│   ├── 2e3388c256eb2ea8d82d669105f9b97c01c1d982.nq.gz
│   ├── 30c5f50fbf4a2ddd8dcdce0cfe2042eba4721a4e.nq.gz
│   ├── 324104e68dbc9d4bb030f0f252d5a0cbca265da3.nq.gz
│   ├── 32417459426424aec55d8fcc3941242b3986c7d6.nq.gz
│   ├── 326197b6aed2daf3477a3ea1e06937660adb3d6b.nq.gz
│   ├── 32818ff5147a6c5fb56bc25ae0ada98cfbeb2546.nq.gz
│   ├── 34246a6bfb2387430f1fe1ed2d413999fe03b05f.nq.gz
│   ├── 36be2ff61d9398e9c5e81f7b9bce769d32c91328.nq.gz
│   ├── 37b4f45abcbf73101e21a1382261311df8801e45.nq.gz
│   ├── 37d5a72eb08a045cd24e76db27a8a794f2b16422.nq.gz
│   ├── 38144ce3954563e838d940a40796f132cf26a9c2.nq.gz
│   ├── 38d1395e06a621e1cad140143bf380ffaaa688f6.nq.gz
│   ├── 3b58f9e9cdaa696ae167fa45f616bcc4cc5d83c3.nq.gz
│   ├── 3df584ba7d23a0a3bc645507782eab39f7dc8449.nq.gz
│   ├── 3fa6a64e52f30d3ad836f98b3f0da6f4b6263bb8.nq.gz
│   ├── 3fb81c7271fd838222e27d13059578d79d8b51e7.nq.gz
│   ├── 42474fbbb058b86c1c74b153b60447d9d9bdec2b.nq.gz
│   ├── 495ebf6fb0299dc74d685516f6fe8b4571245bf3.nq.gz
│   ├── 4a4b09334dca084a13e12c9518cbf479df734299.nq.gz
│   ├── 4c6b150dd69e6bc3dfce7306ad63946f03dfa2c9.nq.gz
│   ├── 4c9d206da342d29c8e90a4df594723d838e07ca4.nq.gz
│   ├── 4d61621b62e0b8f657a88ab86582952a2b2b4539.nq.gz
│   ├── 4dc2592635379332d233abccb0c8a51d9e470ed7.nq.gz
│   ├── 52796b59b6fdd1b7519303cf65eafced0724f129.nq.gz
│   ├── 535124f3250a739708d2614b1ef8ed88fb913896.nq.gz
│   ├── 543705891ad37759939eba67aabff3619d78198f.nq.gz
│   ├── 584bc7ddb3a39e0cb1a83714caa91de1436c7d5f.nq.gz
│   ├── 59c591bf26f6e9133f3e690fa7b65527b0fdc910.nq.gz
│   ├── 6035a946cc6a9b2f2b8e94479fa4f4f0a31e4cd5.nq.gz
│   ├── 62ab6c1caa2b8797c5a2e79de11c8a8f529fd8c7.nq.gz
│   ├── 639c9131a0edc6abc68ab2e41cb3a0ad1719e592.nq.gz
│   ├── 6662476ac3678c510e6de4169c9bcdec5dc1ff63.nq.gz
│   ├── 66ec3acdb2a27a31d4d5faeecdd8f5ade7576839.nq.gz
│   ├── 6a8e9a7382d09ef2fb39819ccce16d5098f81578.nq.gz
│   ├── 6c636bdde05235da1a0ef14640d68f22f04aadb8.nq.gz
│   ├── 6d9cac01e9e671102c35e3d8dfec2c86f86f7006.nq.gz
│   ├── 72bf8c0fcf9dac482402f812d56ed9961c0ce6e2.nq.gz
│   ├── 731fcd41cd18d6b73e80101da428e136ff48f07a.nq.gz
│   ├── 742f13852ff4adddf16116e00aab4a5b1006a649.nq.gz
│   ├── 74573995f9e5f620935ae61cb0716cce9b6c2238.nq.gz
│   ├── 74b385d8d148602a2370c77011d35c427a0e06f3.nq.gz
│   ├── 74e61409f9d2031b2447ef31b129f9b5953df885.nq.gz
│   ├── 75ba8803a25d1cde71bc843e12ac09e0a9fb6f38.nq.gz
│   ├── 763dae7fdd817db45b0b87def9dd210abce372fd.nq.gz
│   ├── 7b0ab28ba6bdfc1991ce67b190b3bad60a9ad505.nq.gz
│   ├── 7b1963ae39846500133baffd172d24402a1680d3.nq.gz
│   ├── 7bceb8f9d2e04edca9f867c20adfa1c900ce7ee5.nq.gz
│   ├── 7e68c424a505d9409354270ff063ff6c18cee880.nq.gz
│   ├── 7eabe21c5bf008eb9a25199cb430bed521b5e55e.nq.gz
│   ├── 7f1be0fec1fd2a10d6660ab8911b83b5a69893a5.nq.gz
│   ├── 7fed15e55e8f38cd2328b5288613d07281fb1a96.nq.gz
│   ├── 838b154454eb5f50c585eb3f16bc80316b31eec4.nq.gz
│   ├── 83ee096bae8f92c035a93c6c7c30308977fc6b75.nq.gz
│   ├── 84916fb13ad3ebea5a75151a101daabb30c86766.nq.gz
│   ├── 863bf611721db3b90ef7fe06b223c319737f4f17.nq.gz
│   ├── 86be57f496ab5d76198988adbd6bf035e82d897e.nq.gz
│   ├── 87c751365d08c01b73cdf3c82674edcf13552b02.nq.gz
│   ├── 88de6de7ebd19ebd721dba057a3c087055268b15.nq.gz
│   ├── 8b23bf230daf218437cb870bd6f018738ba95f7b.nq.gz
│   ├── 8eb1d6d496ee3561b3594c305d2b3d316891ea0b.nq.gz
│   ├── 8f27e512f723f7de9bb148aa88e83c9805f1bef8.nq.gz
│   ├── 970e79d1c90bd75f1c51e94140aed77b86d05b01.nq.gz
│   ├── 97f1b60ef2a9883b22e4825f4c612359e1a8b37d.nq.gz
│   ├── 98f52e57254f3054cd30858613297cac28e269aa.nq.gz
│   ├── 9a1d6d73ee5c49cf1050af4b832e335ef1f6865d.nq.gz
│   ├── 9e533e58dd9fd9540a841545f51cdba1de7f4219.nq.gz
│   ├── a02846df043c9b2f051c886975302082acbe81be.nq.gz
│   ├── a0b0aad6b4749e8a699544edc9d13834886f52cd.nq.gz
│   ├── a13f92343f579dcdd90bee573feec6b4dd2d1683.nq.gz
│   ├── a151b03ef469182249bdd057bb8b5d8640c94475.nq.gz
│   ├── a3182b41d7fd825bd38abc0fe1d65c33e4a2bac8.nq.gz
│   ├── a3639c72d5d0d81d874422c1481b51b3c4495f12.nq.gz
│   ├── a550ae4de655fb6c5346d59f3eab0866ffa09062.nq.gz
│   ├── a5f3924d4ec22752f312c6e5d61742ae96fd7e94.nq.gz
│   ├── a670c4b2b8256f07312692167ccc97153da451f6.nq.gz
│   ├── a83d8e35c29e90d3390eeceabf62fc69fb24608f.nq.gz
│   ├── a89353b7877785f9505bbee12905f6ef4b7e1730.nq.gz
│   ├── a8afcb140c76320d8157918a55792c3b4edb5a2e.nq.gz
│   ├── a93a3f9f87dd65c71c3de83d1d70f06a5a4d5a68.nq.gz
│   ├── abef64363112e03e0879b1c0d3bed2a20502ffd7.nq.gz
│   ├── ad75c9e774b8073e78474d009a7da582410a7d03.nq.gz
│   ├── adc9213ec0da845a40e284987df88dca1ca3e2cc.nq.gz
│   ├── af15bf5e4721e04c457986a3bb95447b26d9ef27.nq.gz
│   ├── b043680396e3f7adf17a135d9d103289eb540a6b.nq.gz
│   ├── b18b3f938cc72bdd3e7d205edc8afd969ed11979.nq.gz
│   ├── b2c145b7ab9dd1dfc1cc7e755aaeccbfcc4e7b3e.nq.gz
│   ├── b491343fe1df3c584659cf7cfddf894a6aa37b86.nq.gz
│   ├── b648716cf46e4344abe0cb23052e4321917067cd.nq.gz
│   ├── b713a39fe897639927455cef75e80653e3bb66b2.nq.gz
│   ├── b8301f71a0aa300d09559fb9bd51349adfc03afd.nq.gz
│   ├── bb26f2e577c07bd505da35b6bf7db6a792464b9f.nq.gz
│   ├── bfbeaea54096dd20c82bb60dd73af4ce6745c24f.nq.gz
│   ├── c0963e864a9f8e09f39a7eff6381753c479cc828.nq.gz
│   ├── c15ce88a1058bae975cd9bfa6735258a1c8cee83.nq.gz
│   ├── c694d718be141baafe614ef0c0729d381b2a61a3.nq.gz
│   ├── c74d98e9c76b351b057b993fd1d1b18596d7f3c1.nq.gz
│   ├── c8526950896345a04ec8e0b59ccca88dad75abf2.nq.gz
│   ├── c9e64e7014d2b0444cabd2a0952399c3495ebeab.nq.gz
│   ├── cc3f3063756047cc2ed138a033c139640ea833a4.nq.gz
│   ├── cd0e5c3a0d3ae851a9067dec21f16df1fdae7497.nq.gz
│   ├── d38865be6d39deae94b07efd8c6bf3a6da5e8b3b.nq.gz
│   ├── d4d0b6fb3bd8a4811787679546a10418a0f3af24.nq.gz
│   ├── d55c82d7b985645458463894b8bd9b8a358639bf.nq.gz
│   ├── d62057c25f597209cbf4fb615887e1e2e3445d05.nq.gz
│   ├── d65b437fd38ddc8e2128287d21aff2bb77020e3f.nq.gz
│   ├── d68d7fc2001bfbc47f787352b1bf5e90a365f349.nq.gz
│   ├── d6f4bd11bb2aa3cc88c3bfbb032b79a163f4411c.nq.gz
│   ├── d792193b867d80b341a2c50d4c7523ff3b6fb73f.nq.gz
│   ├── d7e4e78c0fd0d024c06ce11021218e89e8ecec74.nq.gz
│   ├── d982620da644d7b885b995f19183b96e3d169fa4.nq.gz
│   ├── ddf8eee68c830f9005c2c7cd36da4e03c7ed7661.nq.gz
│   ├── defe251495a9ad3d70dc9f43614fd52ff3b9f6ac.nq.gz
│   ├── df24c03290cfac81085aa7bdf45d6c977520f663.nq.gz
│   ├── e00b6d05faf4b360e550ee891f40937ce89d4926.nq.gz
│   ├── e0c7f56c8d50c65ced19d947b1a0d636792f75cd.nq.gz
│   ├── e15cb04c3f4d7da6e482836a594b488a5ccdaa8d.nq.gz
│   ├── e25c95238cb94a7c435db48c4a377fa2b7fef607.nq.gz
│   ├── e37184a7fe2250b145a65ccbe82ed29c0aaa4c04.nq.gz
│   ├── e40b53f3a4ada21fd34707d3bd2625747e2e1097.nq.gz
│   ├── e56c039413df9079a53191ad48ebcc160b0ea30e.nq.gz
│   ├── e59ed46f640483404ad32aa1d84bd231ae5d255e.nq.gz
│   ├── e600624812079cbf647c7e209bdbdea79f0939b6.nq.gz
│   ├── e8e2eb4f5eea46227b0bcb768f29ea3576b38a0f.nq.gz
│   ├── eac47d784f051f9d9e36edf6d12d19d1b09d1797.nq.gz
│   ├── eb352b3493a5b4828daa9732f47e8f2e96b406d7.nq.gz
│   ├── eb4b24c735563d3736bc829bce41fb8db7dc68c4.nq.gz
│   ├── ec65b8fbb39a829338e21db4eb8ac969e245738d.nq.gz
│   ├── ec72b1c2facd18d2c4cc05cb795bfa8b1e01adcd.nq.gz
│   ├── edb7fd2cff027cb853da6d07c43f5a9ce0163c80.nq.gz
│   ├── eeefb998c282c4724ebe630a24ac4419ee78702c.nq.gz
│   ├── ef6728c94072e7503b1aa2fbf1574f437a43ffc2.nq.gz
│   ├── f235928b87b89373851a115be1691695ea761ee9.nq.gz
│   ├── f2e991b68d06927034b2061d1ea1b01099af8b60.nq.gz
│   ├── f4fffe671d2d13524c86ecd7ee51d8d8bb759190.nq.gz
│   ├── f7f2a17296cd48fdace7ee3a123b8524c9be18bc.nq.gz
│   ├── fabb52ff0d4571bfe2f9f65790bc78db73f9355d.nq.gz
│   ├── fb44af35df709e88cddc05108467b613e9d59325.nq.gz
│   ├── fee95857695214bf1e602d317bcce95ad2ae8d51.nq.gz
│   └── ff2577a6f06790e29ec1c9bb9169e56963933bcb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2ff1acb3ee319fa302837dad6e17c2f36c0d98ea.nq.gz
├── filetree
│   └── 2ff1acb3ee319fa302837dad6e17c2f36c0d98ea.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 185 files
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

[anthropics/claude-code-action](https://github.com/anthropics/claude-code-action)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*
