# Repolex Knowledge Graph of mosaicml/composer

RDF knowledge graph data for [mosaicml/composer](https://github.com/mosaicml/composer), parsed by [repolex](https://repolex.ai).

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
rlex download mosaicml/composer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6405188805a0054b4551ec49e4919c54c971d0e8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6405188805a0054b4551ec49e4919c54c971d0e8
│           └── chunk-001.nq.gz
└── blob
    ├── 00a6b5c25339ffc5720f6fd5431a7dde81a5bc50.nq.gz
    ├── 00bddd9b844a9296f45c4655d8a703ef4b143b04.nq.gz
    ├── 00d1cca9c521553a18fc3ac51ae5882e94c081cb.nq.gz
    ├── 016b9d7534b5a510d91f00bb5b6f32ba51422cc5.nq.gz
    ├── 0178fd1d08e004b62bc3c90d79440722ae5c4e33.nq.gz
    ├── 01cb3aaae042f08d4d25b73cdc710f3113cfc643.nq.gz
    ├── 01da4829db5a863f71e5dda78d566c974bde265e.nq.gz
    ├── 02ad3ccead4c36dcd5685efbbf83c0645b55eee2.nq.gz
    ├── 02fd3fcadff75dd22b2260a907ae3f8a3366672c.nq.gz
    ├── 03ca83b483d110f943baeff3023f7e2c675745a8.nq.gz
    ├── 03ee0c24ea28a339ed8f22cc273cdb54f62f06b2.nq.gz
    ├── 046bd785f2fb8e86232f0d674ebde32dff2b0597.nq.gz
    ├── 04807f845f4acd2ce4dc6539eb382e032f70f503.nq.gz
    ├── 048925d35d285187b728fe90a9e5389e0f51be1f.nq.gz
    ├── 04bae0336e89b53a3fcdf018127b6aed9f858906.nq.gz
    ├── 04dd501123dd43a65a50ec297328ec9205a8ace5.nq.gz
    ├── 055f280792766df19201888fbc0c58fb4912be5d.nq.gz
    ├── 05904234e6c5a732516a396d5e06487bf8695b76.nq.gz
    ├── 0599eeb81a32aeab4f93195c7b6258e1b0cae18b.nq.gz
    ├── 05d18b1c0aa25e464d741c9d104e020a507bf334.nq.gz
    ├── 06b733d619dbaf1169084c6196a06d37e924308d.nq.gz
    ├── 07440b83dd96724686958501c5e1365ca20ecaa9.nq.gz
    ├── 075bd2ca3312e7747dd5845fc09e535159f0bbdf.nq.gz
    ├── 086cba412d322b11ef3d5cb9d8545a99d34d8bd2.nq.gz
    ├── 0895a3def8a3b84f2ca0aa4d6ec14b14962be0bd.nq.gz
    ├── 08e18d0c8d6b6ad2acbd11a1fcd86c9b53085673.nq.gz
    ├── 09646aa25a58281ad591611ee5e7fe0765ba7be3.nq.gz
    ├── 0afab08f8aa5197d792efa8c891ba7e31f87f0e9.nq.gz
    ├── 0b635604bccee8470fbf0a8af79f95fe3da7d5d5.nq.gz
    ├── 0b6787058dc9bce6acbd1439106b15577f800078.nq.gz
    ├── 0c44a638203e63754d9c5233f470eb5b142b9c37.nq.gz
    ├── 0c5853033e6fb669e7935ac30ba2f0f07ede57c8.nq.gz
    ├── 0c926847ca1ca8e8d42ff4bbdfda7442dd31882a.nq.gz
    ├── 0d33774bc77bc78a228e88483256eb85db848bb7.nq.gz
    ├── 0d6115dc4d01dbf9e852f20c775f0566d3ba1977.nq.gz
    ├── 0e0421688f27e96f867b018430dfaf5be6064684.nq.gz
    ├── 0f9cb32de23d4b7f1d542aaeed39c55baa62d981.nq.gz
    ├── 0fa6a0547c1c815e4e3e8e391ce10c38a83f8426.nq.gz
    ├── 106a9639953eb08c78f4fd0dfd7e8e201a8d94dd.nq.gz
    ├── 107d45973ffb8aaee93fb343fdbbc57c82023fa8.nq.gz
    ├── 10a05b0e31ea25bd7e7ca00d64dbf7f56cb30cd4.nq.gz
    ├── 11340445215ff67adf7f86222e9be8d688fd4e1f.nq.gz
    ├── 114296afeff47020aad461d2b11faad3d627c626.nq.gz
    ├── 114bdc947bdc9ec0e91f2d0b8eaa6b612a9c553f.nq.gz
    ├── 11809daeeb66b1a39750003a82541b71a10ac8d9.nq.gz
    ├── 1198ffd32b8319f3dfebd4efbb35a3f7d689a302.nq.gz
    ├── 1207cb7618121f596d964b7b4a64a571b23304a5.nq.gz
    ├── 1237fc19abc9e2824c9ae587f6a8371a630e352f.nq.gz
    ├── 12416a95d36dd273870f0cddd67a3a9b3e5be4da.nq.gz
    ├── 124913222c3317926504330eca58f642ac4d3665.nq.gz
    ├── 144417ab724145006e41d530cdd85586b74c4a16.nq.gz
    ├── 146770f65c299a58756c76a720b9743041e36b11.nq.gz
    ├── 1472f2423294c14824ec17bf35a6aa3e65610162.nq.gz
    ├── 148746a19e9e44271f44154ce43025434b5e5363.nq.gz
    ├── 15f810683f273dc856a662643a6f6e8a80043d0a.nq.gz
    ├── 16317d1cc3875aff0c969d548d178e9619e53ac6.nq.gz
    ├── 16a46ef58c2c45131f99397b88763bd21b3320b3.nq.gz
    ├── 17196a23bc42a2f4a1d50800ee8014b3bf3cac9d.nq.gz
    ├── 17542c7ec4cc964f5fd9b1dc8e2f1569da173bce.nq.gz
    ├── 177ca9b6e642a45702d317636bb9ecf153c6c9b9.nq.gz
    ├── 17886874b126e459f0510ae43f6735706a2743d1.nq.gz
    ├── 17d448c9137a01ede3991612048344ae7c62eae6.nq.gz
    ├── 190f6b2b5475bd232a624d61459aa27deac1015e.nq.gz
    ├── 196a3b096ad8cd58a910877c06efff87786c7bf5.nq.gz
    ├── 196c9baa40b4c6c2cdac477719c41732f0e4f241.nq.gz
    ├── 19cb0a774a6fb57ca2fbc9fe8abf093b6761e28f.nq.gz
    ├── 19d337d4aac8301f9de74e236f5882d9ef5994d8.nq.gz
    ├── 1a4a6a427adcb23c5d40cde7c493b523187b1f75.nq.gz
    ├── 1ab905c5b0b0359ea7d6706491b722be754a663b.nq.gz
    ├── 1ad19f5d96f45fb5def5375bf4d716cce1dd6cc1.nq.gz
    ├── 1ae75b494e1daa99c04e4b89df0f4cd1de3e3d10.nq.gz
    ├── 1b649bd20a61eb4f70851f406adc8b1a8d5b1958.nq.gz
    ├── 1c4eb14902ebafca81652197013a6576f4259370.nq.gz
    ├── 1c86cacaa20177e9cc088d065a68ca92b7cecf64.nq.gz
    ├── 1d1bbc09efef04cef63e609dd778805d062ac5be.nq.gz
    ├── 1d33911743e094c1e1c12f3a5e3c71ce7b903b39.nq.gz
    ├── 1d4f2dade87e9486ef178df19fa33a5a61ba5260.nq.gz
    ├── 1d9f67d47bc90af5a22c0c3bd48e99750f762e2e.nq.gz
    ├── 1dd13efaa1bfd77ce469f5fea001b7a9715ab0d0.nq.gz
    ├── 1de99ff494b64c1915629d49d7782ffa3f2adcd3.nq.gz
    ├── 1e7652ab4f32caa8d600cbd876aab3cf0d5da4cf.nq.gz
    ├── 1ecefbee903dc58f449774bef9d47a3ff0de2b2e.nq.gz
    ├── 1f5c242c4b99937c7dfc20a693de240d275053fe.nq.gz
    ├── 2046b2f828cf5d650c01bf9b6ed5e26052677400.nq.gz
    ├── 204b90814c4110843b1198a65a7a99d906f7141e.nq.gz
    ├── 2094643fb1a52f298777c12f09ae3bded411e9ae.nq.gz
    ├── 20fb7973e8c0e6d7a2deafed6eb557172af0d80f.nq.gz
    ├── 20fd9f594a6007a40db669e763d778dc290f1d12.nq.gz
    ├── 21aa3042420f66310688842b693e8e23b66e4adc.nq.gz
    ├── 2211f10916ead21f2b90d57290ca66c7e03a32ab.nq.gz
    ├── 2238b8c0b6a9160587f91cf6359d0e4f65ed266d.nq.gz
    ├── 2247e609c845fc95edf8053d2f555a8890a5b977.nq.gz
    ├── 2254f507e94dc9650c8823c8bc58635a13fd802f.nq.gz
    ├── 22f126df31d940c86c4546a8a8913eebc3f3c2ca.nq.gz
    ├── 23aa71f00ce17f3cb61407d37e15e835bb11e1bc.nq.gz
    ├── 248c178f191fab6df4aa53adda3e710b06d51b88.nq.gz
    ├── 24ebcaf7e50b27715718b1607d38c02cae328524.nq.gz
    ├── 25801d5a03671f449de8c4fb0d5c7a5600fd93c0.nq.gz
    ├── 25d92b30ef08aff38268471cadd26f205eb1ca07.nq.gz
    ├── 27aa507a6862677f48590efd8d72baaa2281091f.nq.gz
    ├── 28830f90bf3f1ebc6b645290338fd6af488957a4.nq.gz
    ├── 28a782a58a1d5177764f0a078689b3eff1e7a609.nq.gz
    ├── 29d5ce683f80d0e02f84fba2f428c1e50aacbe0f.nq.gz
    ├── 2a6b14e341faa96a39cbee4931133367c1faee74.nq.gz
    ├── 2ab0eecee0b2e06fef6581ba9570554e5045f00b.nq.gz
    ├── 2b449da0f311e18499164c89bb3ae7cb87605ffb.nq.gz
    ├── 2be200583b76f953843ccc7dcfdf809aadbbc154.nq.gz
    ├── 2c029a4684c82f296797b90bc314f4e82d864171.nq.gz
    ├── 2c22a8cf6ce37a47f33307d65f825d2b91cfcb0e.nq.gz
    ├── 2cbdcff37cd0abef63054ebb5a7eda8106a1f4d2.nq.gz
    ├── 2d05bb0861763bf2c1905a455428e2d1489d28bf.nq.gz
    ├── 2d5d4fb364aedd2c30a021213f883b1ef0bf98c1.nq.gz
    ├── 2d6fc150f9fcdb23805e1e5602f22751d77cd873.nq.gz
    ├── 2e786939c38ad393d87c688fb4c1fe0a2d927531.nq.gz
    ├── 2f46a338dcaeec318c870ac4ed51b9ee4467aa1c.nq.gz
    ├── 30a733352598618b590e49e5e188507a275b20c4.nq.gz
    ├── 31b588da8f2ccbcfa58d0953918eb4dcd83f2d52.nq.gz
    ├── 32bf87c6dfc64e86afec712a3421ae821d99fe12.nq.gz
    ├── 32e7c2b81cec5288f09b1a585701827aa0cd4fa2.nq.gz
    ├── 32faf0448b54df6fe00cb0d4b381ff351ab9fe00.nq.gz
    ├── 33b0eb9db4a5434bc6ecdd85a27027dbea3410ed.nq.gz
    ├── 343a7f8523f7b4f83a31740f3fdb7b52fcb7a04c.nq.gz
    ├── 343c6f8974b264c6a2d52b02f0592cf959c02561.nq.gz
    ├── 36601189e8d10ffbc923d1c61c00f1aab5f07752.nq.gz
    ├── 3700a35ec5322a236f3d443071ffe498cc0c86b3.nq.gz
    ├── 371947c2fbb0ae77430950cf0e50c4ccd6daf4be.nq.gz
    ├── 3880bedf7e149b796d382244d02e3860e4304127.nq.gz
    ├── 389cc90888f3819d8ee418bea920901692c64c87.nq.gz
    ├── 393517c9161a8bf005cc7092da1473689dc395ac.nq.gz
    ├── 398d6b71c129e1abe154b30f8274d0285b16a931.nq.gz
    ├── 3b28475f9a105fe9ea8133ecab56baf703772723.nq.gz
    ├── 3b631d321d7828c94d04cbd14fab41a198a933a9.nq.gz
    ├── 3b7fd610753165d5f08bd125c6230b20c106223f.nq.gz
    ├── 3b9a43344ca5fe0b6a8bd089988b090e56e4107b.nq.gz
    ├── 3ba0f35e82273c3a6bc844cd6f749672c9e28a8c.nq.gz
    ├── 3de2c0ed9b6d1e17a6d47c0a6d360103c6974cbf.nq.gz
    ├── 3e4ccca4c16b278b9cd6b36e34af9f8200f0a8e8.nq.gz
    ├── 3f8ac951f9d98adb3b81a692db58a6dbb78c783b.nq.gz
    ├── 4060b656da1db0a356b02e4e4e124ccbd91e72cd.nq.gz
    ├── 40fc7095c658092e87994412a60c79c42130657d.nq.gz
    ├── 412fd737d8ab3f05515aee6364f7a9979d1a6b3b.nq.gz
    ├── 4158b2ceef2d24a2459c27fc4d8e6ea45da9b131.nq.gz
    ├── 4177cf06996fc953d2e3a08bfe7a916841752b43.nq.gz
    ├── 42b137a78fb1b06d217afc749a0b61b912fdcce4.nq.gz
    ├── 434a4ca906b3e7f623cffb96ba29e26de4dc8aba.nq.gz
    ├── 439e12fc7106bc887b487a1d62e65e750fa16aab.nq.gz
    ├── 43e2445b01c29825d1d86b5732f2b395d53d222a.nq.gz
    ├── 43e3b5af9e59d7ae4d87bccaea2edb6964a8ef6a.nq.gz
    ├── 4414de96e541c33cd6058e400bbb76a1cb10598b.nq.gz
    ├── 447b8bdbedead866c068b2e4a6c84e4f8c65d990.nq.gz
    ├── 460e63d32ab67af1db84ca874217b4f3aa232ab6.nq.gz
    ├── 4690cffdbb6ae8e0e00cd68c42068b0b686c705d.nq.gz
    ├── 46de659a912aca95fb4f8f96a470e3b95135901b.nq.gz
    ├── 48929bde6201bae9d0acafb9f2bead2770da4c89.nq.gz
    ├── 489c5342a8be2f674653565352cc150a2682b357.nq.gz
    ├── 49233abee12f294c858e751b07688a1408c765b2.nq.gz
    ├── 498be4379a60f6b16dcb8cf7a04aafb608b84144.nq.gz
    ├── 4aa24ab77ad254abd54a9354d615b7be2b8a39b8.nq.gz
    ├── 4d423b8aedd1527e7352b168aee8c37b73da71ff.nq.gz
    ├── 4debde1a7976367284881949efde336dcf4f3b13.nq.gz
    ├── 4ece87701704ca47750e17acd51764343f60f784.nq.gz
    ├── 5019bb03df45adf067c77cc8b12587da8c9dab26.nq.gz
    ├── 511635b06dd86b47701a788a3455b9eb8531325c.nq.gz
    ├── 514d47c574e2b0e71db8e163d6339b8390fcdd8b.nq.gz
    ├── 53311b3334848db8be28d0de255c18a5892041f8.nq.gz
    ├── 5387e71611d16d4e713ee22772003a62dd8e5964.nq.gz
    ├── 53a9d2e41aa1dee102bc00e7fc2ac0c142fb5836.nq.gz
    ├── 53f13389e8ad8e173f4fbe86f8e45b684268e9d9.nq.gz
    ├── 53f492f4f459baa1fc93af02653836757b7da13b.nq.gz
    ├── 55cedcd59a6bb25f3eb3a34f52e5f174d0026622.nq.gz
    ├── 565d7a6b06e7d7a15a7ce92639aed44e581a4eab.nq.gz
    ├── 566167df31b223575f8c2482ff6ddd117b1bd54b.nq.gz
    ├── 567b404a5a761c9b2884bf7c9938ed2402174431.nq.gz
    ├── 57125d28e56522bab29fafe23ac3ee3280dc2b7a.nq.gz
    ├── 57b3cb9130172bd3779cc9bbdde99e3d09ca525f.nq.gz
    ├── 58f750066a68ab3f61948220f0108723b0ebd949.nq.gz
    ├── 5991566b49a43558b0127bb7b0a3138f433bc9eb.nq.gz
    ├── 5a5f3120e9ea05832e74f3b5ea5edf5df9bfbc30.nq.gz
    ├── 5ad0ecc20572d0bf59dd8e0e430f1fdbd7a63329.nq.gz
    ├── 5b2f4eca2b5f6675b0cbcfd1ebfbaa5f33a02b59.nq.gz
    ├── 5b5583cc3906836ef4986e68d8b177b66635b173.nq.gz
    ├── 5bca397413748ba172ea178a4aec8fb3eb1d1bc2.nq.gz
    ├── 5be5a3cc57bd84c550b3973b1c0915ff236914e0.nq.gz
    ├── 5bfdc191e081a9a980fcd646b98ced20e5cd849b.nq.gz
    ├── 5d4ec29b1c55202ba4b13c9c40ddd733a004fc51.nq.gz
    ├── 5d70ffbe79830d85b58803a9dc78ebf9728c8d30.nq.gz
    ├── 5dbf251961fca1da0005361fdfbef52eafa1002d.nq.gz
    ├── 5ee339fb2616906215725569eed27296a739409b.nq.gz
    ├── 5f62aae1c89c78a4cf7b667fc10c183b236e7494.nq.gz
    ├── 5f9dc4a0164c24470da18ebdc9ebdbf29535759b.nq.gz
    ├── 5fcea9be4a627d857fa3d7f72a9302c48786f7d9.nq.gz
    ├── 6034b458773a740fb9a98fe4ee3facdde1715fa2.nq.gz
    ├── 6051d65ca70447b1ff1a5cfc8bae72aa4d039cce.nq.gz
    ├── 6100627df57d52dcd138462c0f9d933c29e9090c.nq.gz
    ├── 6291f11fd962bd1af76e8d03643071ed3bc4f471.nq.gz
    ├── 64277a653192b15d4baaa608c588fce27e594c0b.nq.gz
    ├── 646dbb3c4bb97fd9196e9dd7a364b30faec34127.nq.gz
    └── 649a91dcea307b038a6ff9d2f1724beea0884064.nq.gz

7 directories, 200 files
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

[mosaicml/composer](https://github.com/mosaicml/composer)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
