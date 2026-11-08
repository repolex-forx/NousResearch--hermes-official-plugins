# Repolex Knowledge Graph of NousResearch/hermes-official-plugins

RDF knowledge graph data for [NousResearch/hermes-official-plugins](https://github.com/NousResearch/hermes-official-plugins), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/hermes-official-plugins
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13b2c1c9c8204bf333df240b2aacf98c3e6250b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 13b2c1c9c8204bf333df240b2aacf98c3e6250b7
│           └── chunk-001.nq.gz
└── blob
    ├── 0205ce141c7d0ed68a54c1e38eb624993d8da9d6.nq.gz
    ├── 0206aecc115bcc861f4d191c03c514d850ab55d4.nq.gz
    ├── 0300befbc74e9125858789417e27159ec150d50a.nq.gz
    ├── 0358bef6c02c0f82927c8d1438d966418c88057f.nq.gz
    ├── 048e49554552ee7a531ac4e95a253622b9ced1bf.nq.gz
    ├── 05012e2dc63311c30e7268dde042c4965e5018dd.nq.gz
    ├── 053bbec575d87f08d46b2080229ef2351296e0e1.nq.gz
    ├── 058e826009d03ea23f3815de975e8ac1ba145b2a.nq.gz
    ├── 06099eeba8010c201c37208de04b1b9f560a1850.nq.gz
    ├── 06141311801f56eeb18b561100df7b38b402ed5d.nq.gz
    ├── 06a141bae0a90dc0b0bb3f5218be6b30e62f59ef.nq.gz
    ├── 074a83488993c1a288e8f22639f3055fa8e5bcd2.nq.gz
    ├── 081f0fd7db6ea558abf5974bab544d8cb40aa62c.nq.gz
    ├── 0888996658da3f8a728dfb2e6d6b2fdd61d54b7b.nq.gz
    ├── 0891ea9ff7d0d7bb547f34a48a65e10173c37c65.nq.gz
    ├── 08cfa42af129382656f038126003e0ba50a88142.nq.gz
    ├── 09238776f53e6eda60f8473e7d8877b24a07370d.nq.gz
    ├── 098703d8205a6b02222a8f07c0226b49b143d428.nq.gz
    ├── 0a9dab8d2647ab7e945d6f30aadef68040204f84.nq.gz
    ├── 0af140497ea4ce9f3739ccc979237ad12860d88d.nq.gz
    ├── 0b7ce728371996dd0f904df522dc0b9d52fc4718.nq.gz
    ├── 0bfd45b199859a62643870711d4197b0e5401893.nq.gz
    ├── 0c0ce211f7904ba55354aceb34a55202695a1082.nq.gz
    ├── 0d12c58bc0eeff8d3e4f4eecafe1eb8692c268d8.nq.gz
    ├── 0d6fd71c61e50fb30336b075f0667e50743df8fe.nq.gz
    ├── 0d75f0e98032b2128f7397b1b94253f4542ff0c2.nq.gz
    ├── 0e030204d55f8b2b23fe6f2023cb869a4d0641bb.nq.gz
    ├── 0e0f077cf86df663a1edc86e8e6d7144d8b7e4b4.nq.gz
    ├── 0e3998cfb58df40ba538b7370e58fc84c2a05e37.nq.gz
    ├── 0e7bf57fcd2161b74a82107951f5f9874de90fc3.nq.gz
    ├── 10095871c0bb5cafded7ccce1735fe69bd01dbc8.nq.gz
    ├── 100ed5c16ed215025112c2970724cd5e61da4cd3.nq.gz
    ├── 110119543fcbb6e49ea93cf87593fd43683113d0.nq.gz
    ├── 11b556b753d7381c8cd3bda340e5ecd15d17c4e1.nq.gz
    ├── 12e084d9e0fc30e98322cd4eb467c1fc659d26a2.nq.gz
    ├── 13de3473561c01d5d3eefeef40887c73cccd85a2.nq.gz
    ├── 1475b06d2d85d7ef9e248bcb8f4f6aeb0f323af9.nq.gz
    ├── 149d3389a91b63e914ab5e3fb5d68f3d128624bf.nq.gz
    ├── 14da2ea847d22eb307715415e1601b600b54a88f.nq.gz
    ├── 15f4fd7675b925a2997157ee2c9fff7916d37d27.nq.gz
    ├── 17149a0403a8fa92dbca3712f90a65827dacf515.nq.gz
    ├── 1798d40742aac0b1f1abf410dff539ef8b8b8180.nq.gz
    ├── 184a4b7fdbbdf5243b91affb827bf1929e0a3a0f.nq.gz
    ├── 185446a5f508379f7541b651c17f0d983a7465d7.nq.gz
    ├── 1865661b9c4f2c90bfe2aa3fe031d87bfb5ac6b3.nq.gz
    ├── 18c478b45aebc687590dfd772758e64940bb485a.nq.gz
    ├── 190c195563d2a7cbcbcb5337b7f8104b4d64e496.nq.gz
    ├── 195d0ceca1cdebc79343dcf0f0163bb83f417716.nq.gz
    ├── 19637375e52c5a7a27546d8ab8b25a769ee8b19b.nq.gz
    ├── 1a6787102a33fad3084ba43a3e40264ad043e9d7.nq.gz
    ├── 1ab993fe3613c61cd863959096b3f4dfe2d62bee.nq.gz
    ├── 1b917f98ddc33abbe85cd4a2756f22cb4dfe63a8.nq.gz
    ├── 1c363741d7514f811375f676cdeb6df03a400d8f.nq.gz
    ├── 1d12eeaeb37d0d897e4f27785284addfbfea6473.nq.gz
    ├── 1d6aef2ca9cf74d8303ef6577461af65699e8c92.nq.gz
    ├── 1e0657e2254a10373352eb49b8b12541dca49f63.nq.gz
    ├── 1e99289a3196457f1687e8f1d8fb05681ba2d906.nq.gz
    ├── 1fae625427c42f6edcf56031b32cc9a8706e3b5e.nq.gz
    ├── 2014bdcb64ea347da249146c831157a004550eba.nq.gz
    ├── 2122052bfb12035398966722962119cd518cd764.nq.gz
    ├── 214cebb150f29ce791cce8e96861d1f13d4bdec6.nq.gz
    ├── 21a5cd444a81dfd581dd288476db65727764c325.nq.gz
    ├── 21e1c8dcbeecc0f0e98671b485c7d1ec60835d29.nq.gz
    ├── 23cbbd850a349fe87f12a07c26ff6b227b81cddc.nq.gz
    ├── 249ddf04a7c70dff99ab81222012ae0e6bdd25b2.nq.gz
    ├── 251617acad9061badc49b07a797b63820b3fa95a.nq.gz
    ├── 2561b3eb7cba9ac478586d492f737e9f15977c34.nq.gz
    ├── 2563001936bf9f8a6018cd679f98ec397b1f6935.nq.gz
    ├── 257e95a4e55ac40889581c75d871519009fb08f2.nq.gz
    ├── 25f726b8f04b459a5b418d282ce48ecbe30eb468.nq.gz
    ├── 26373c54d27841d4adc8df3bfef90cb81aa6bec6.nq.gz
    ├── 26d8d85d7c94e8f63848d9bb6b8dfa572f897e12.nq.gz
    ├── 26fea197d7b43b84cb1003d111b95454aff20395.nq.gz
    ├── 2738fc1e81c5623f13416da9a84be500c2d9ff08.nq.gz
    ├── 277e2e96bc12434ac2ad93beba6dae6a40712da1.nq.gz
    ├── 286e9914f018ec6612426ddf0cb0c6a7f11257f2.nq.gz
    ├── 2878297edb5538f280b6262938377e17aa7aa67b.nq.gz
    ├── 28b534c5748c10fcecb6bc876a565fbf3f15069e.nq.gz
    ├── 28cd5c0a10e9e4d9e0e50f332c82cd2e96bb88e8.nq.gz
    ├── 2903eab9ba4da0a248203a16e532c3a0caf2056a.nq.gz
    ├── 298178cfdaf629a02c387903635d8f48c55a73b6.nq.gz
    ├── 29ba1303f59430579c8738941d797628b888c152.nq.gz
    ├── 29bff3ab39a98f5b9eeca71c108d27503199e09e.nq.gz
    ├── 2a7111b1032dbed42ebf064450526a3b2a51a45b.nq.gz
    ├── 2b4c7c42f94abaf658a0bf0336842660f84068ce.nq.gz
    ├── 2bd870dd0822c7f15d7c8eaab7063eb26422263c.nq.gz
    ├── 2c1d01b8a5d6321e3c2a7eb27eb1fc0255e79855.nq.gz
    ├── 2c42acf7a9359b5144b8695df188fd680c139d58.nq.gz
    ├── 2ce55dd5e8658df5991156f1eb13c4ba6fabc7ad.nq.gz
    ├── 2d032ed5b8378858ea763a3b79702c0ae16e5d3d.nq.gz
    ├── 2d4c48cccb65927c757a5f09d4f5fe9f97ac85bf.nq.gz
    ├── 2da1c79ec47c32c18d4057c5168b0b2ef01bed44.nq.gz
    ├── 2ea74cfbf2401863636a0df32070d7f47c5dc40f.nq.gz
    ├── 2ed8f947855c3fcff0a807fae6a274b4235d4279.nq.gz
    ├── 307b7d8948ce6361f1604c811524738b12919bc3.nq.gz
    ├── 318ca509b90415b37a4761a935e551c865503f68.nq.gz
    ├── 3205d1a4aff5a0d7959254d8d9ab008c101be70c.nq.gz
    ├── 32416eaad741d3a57ecb173754d2281eccba5793.nq.gz
    ├── 32431f916d80f6fb37465d7c2547c971cd043e9f.nq.gz
    ├── 3277b0cb9f617904801c2855a4d463a188e76484.nq.gz
    ├── 32c4cac773b15c342308995f31d2d40f00a76e11.nq.gz
    ├── 32f113ebb064c38e83ecd24ceb7e46ed47b833f7.nq.gz
    ├── 340a9abc1da572cdf175f01ee28f983f6076e1ae.nq.gz
    ├── 34558fed8988512cf4731e5ef0afc657d454d3e5.nq.gz
    ├── 34b91fbfdce454d50950ca166a467e4987ef765b.nq.gz
    ├── 34ca50f9499fdf70244f25f0bd7ae7e5f6304262.nq.gz
    ├── 353f56fcfbc439d419a7fe4c89486697a4a0df01.nq.gz
    ├── 355fd61b517447af8fa594de60c624fafc29a819.nq.gz
    ├── 3695abf9a256dbf48b562754a399c3afaec67939.nq.gz
    ├── 37893bd9d7cb533c12bb42712063bca6641897c7.nq.gz
    ├── 38836a815a935fb4ccfc2e06a37f0f45a040e27e.nq.gz
    ├── 38b0d0872ac12cdba9c94e85e11d13a3226039f8.nq.gz
    ├── 394bb43c1a57a868584169f39fc706da50465624.nq.gz
    ├── 3996014ba0d000d8912d13632c33b53c889ce902.nq.gz
    ├── 3ae1baeb783545d24dc2833008e62593835e268c.nq.gz
    ├── 3b4eda7eeefd07ae9d47e0db3897110fb3c1d8c6.nq.gz
    ├── 3b5d7f0cc498e34d7285bb5fe564ce71cf44ed13.nq.gz
    ├── 3bb6fc7cc99c6ed740d1c08dca006dbba59209c6.nq.gz
    ├── 3e1db2d51ebabce2b0469926428f1dc4a174be25.nq.gz
    ├── 402f944f96df7b6745503a38f20f68d903199402.nq.gz
    ├── 41437ac1c2b051593314e1b881969ed20e1eff22.nq.gz
    ├── 4166c610efc27ea5e185ef97d414b7c3a11e737f.nq.gz
    ├── 41e5cd2e6c7cade59673381e3d63518799b3984a.nq.gz
    ├── 41f8f2295b7da18d255ea75e2cbb3894c257c9c0.nq.gz
    ├── 4253702abcf5eb62d3d14d0b67d50aa3b3203bab.nq.gz
    ├── 42b2b18af58f6229a7c54f04f23333cfa373633b.nq.gz
    ├── 42b553d968e0b76e0c154f30d813bc0c1e894df8.nq.gz
    ├── 4350bce29a9fc5f452b2d463f055013fe250e1ce.nq.gz
    ├── 43d5e09694459fa77cdc32820174e9008ffa59fe.nq.gz
    ├── 44aa94d68d02043407e44d967923fe2e336261b5.nq.gz
    ├── 455a7abf92c6f561ea69006b9ea9f9d886467569.nq.gz
    ├── 45adf6a78de4c7c17e40758c7c5dab09aa4a1fed.nq.gz
    ├── 4606e72e042564097e8780d66c1d4dcb611869bd.nq.gz
    ├── 4624bb65bcdebb77cae44f47d168abfaa856e484.nq.gz
    ├── 4697a24252d55a30e0096d9ba1362f2eec3a6c06.nq.gz
    ├── 475ed44b1d61cd12bdc200c8c558723cc4f00f77.nq.gz
    ├── 478ecf6b821a8a89a3c41d162f8b428bab9bd57b.nq.gz
    ├── 48180a90232c1664282a4a04e32b72fd3ba3f390.nq.gz
    ├── 48327f58d4212468ec260f57a4da23e01b780be7.nq.gz
    ├── 4834927d67ae9cfda0d3b6a83b8dba7d8743c732.nq.gz
    ├── 485d0274cf5ea974b19549d53ef8602ec5306717.nq.gz
    ├── 488c0048acdce0b5cd9565ade4bc239a66fbec99.nq.gz
    ├── 48f7e497952b06497dba2c855510cf1b2b315fd2.nq.gz
    ├── 4978d30a37d6e1299d04dc6be710ac346417ed5c.nq.gz
    ├── 497b652edb3455314a156fe0f857669b7f5d0823.nq.gz
    ├── 49b073c13cbed3509b854e0935dfe4f7c2bdb553.nq.gz
    ├── 4b721acc3fa06ed0c452b445f366f115fcd5f602.nq.gz
    ├── 4bddb0af9ac79a5aafa11d20ac69c6d85ac64a54.nq.gz
    ├── 4be83e75e29a7bd07cf950b9da57f3018d73056a.nq.gz
    ├── 4bf1953fd35f3ae792a8740566e028c95253ab0f.nq.gz
    ├── 4c8ae40aed7582505628949a1beabd861f9acc9c.nq.gz
    ├── 4ce10920652d90e6696705afd8ba09e812444a1f.nq.gz
    ├── 4da92c3675d6bdc5b1e01fa844d2870975c60b36.nq.gz
    ├── 4e21b478510f37fc42b0e40457f9086c475a24a9.nq.gz
    ├── 4f10139518cd926fd04f8bfee3f29ce775cfba8d.nq.gz
    ├── 5027b1a2823d0e75edf262e8644d188fd9a08bec.nq.gz
    ├── 506b50f6ec00bdeecd90ec43092e9b5df2a52d62.nq.gz
    ├── 5094867786a202de79ca34e96e21ffdc00846708.nq.gz
    ├── 5120c06a56ba728caef9e1e39a501507ce86b14c.nq.gz
    ├── 52aab5c5658319eea86163be436795ab7a4e8190.nq.gz
    ├── 52cea74f60591b06d00ddfab6fe0ab9a86de14eb.nq.gz
    ├── 535a7033e91d9ae43f8017d16bc971ac214b8b6f.nq.gz
    ├── 539bfb6b2fb07c91ff89d27c5582c4637def420b.nq.gz
    ├── 551cba665d3757e0afda89cda413ba7b9e9031f6.nq.gz
    ├── 551da33feac4fd550e4923247de80901a2957ac7.nq.gz
    ├── 5535febb9a39a1e11e23d53fe94efc0450485e56.nq.gz
    ├── 5598708e7f5079c602cce88d4cad5f70e3d582dd.nq.gz
    ├── 55cdbceef4145bab4776c16a03f711c1990b8118.nq.gz
    ├── 560820b1d2dc519f0c5220bb75b2c6a090a82c76.nq.gz
    ├── 56287c8b01f9224e1916602c2b97baeacbce5bb5.nq.gz
    ├── 567bfba1c256321dd0b3992648032a60c777ee78.nq.gz
    ├── 56c48442f8a9607b557385510658809be4aa1ade.nq.gz
    ├── 5700b997827973cb0eb6d84a2782bb08a5872434.nq.gz
    ├── 58bc63753aba0e29dcd1835371a0bcbf9fc6f75f.nq.gz
    ├── 58c512d21de6d38759e9ba9cbb34bdd6d0e4048f.nq.gz
    ├── 5a2666daef4fc1ea6ffa9eed7cc231ac91c60c29.nq.gz
    ├── 5a9dd7791dbf1ba61e757a6aab814ab5e1e33bba.nq.gz
    ├── 5ab2908b167628f2f435f412d2f39a767fffb132.nq.gz
    ├── 5b0e1653c2694e3f0124c3279cd237a1d3ee0413.nq.gz
    ├── 5b82e28cadd5625dc007437e9f76ed46ca54a206.nq.gz
    ├── 5b9cd3da3d97559e4de5d8ceeb3dcada3d5d77d4.nq.gz
    ├── 5c669a9e18241c57ea2d3b763712923a3c3de096.nq.gz
    ├── 5c7a0135666744fe530d7cadd2ba65838001548a.nq.gz
    ├── 5d1e7c46d44eb2b2e0b57b7e2b3ae50d844c179d.nq.gz
    ├── 5d80a79e592441da26e004055ab8c319d24e1c9b.nq.gz
    ├── 5dc28d8d66d24c1a1cad042eae6b3561a1f75370.nq.gz
    ├── 5f52e30a1975de73cee266d288a44baa024b2c84.nq.gz
    ├── 5fd853026c63d09d6da0f878623a2f3b77e3d341.nq.gz
    ├── 603519fd43130b0120672e0ba24e8bd6bff924de.nq.gz
    ├── 61de576504258088cfd9fde770f8a7205def5bb9.nq.gz
    ├── 61f5d9d724fa63d8be976f799d8d849156d8e6a7.nq.gz
    ├── 630de50533f9e0bf34f35d75a4507226f932c114.nq.gz
    ├── 634e16ac5fbac89dcd42832f18c204ab153c7941.nq.gz
    ├── 6474f5492fb6e52d0b7815e507728ef79ec4b6f7.nq.gz
    ├── 64777da0fbb4b64e1c9bd2c05af650b9d8497a17.nq.gz
    ├── 64b52205341f515e0175ebbd1381922119fcc1de.nq.gz
    ├── 64ba754dbd06cb8e0e39af41027eba4e12b8c821.nq.gz
    └── 64fd2a817d62b4959a7ed9ef539c016a77eb93e0.nq.gz

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

[NousResearch/hermes-official-plugins](https://github.com/NousResearch/hermes-official-plugins)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
