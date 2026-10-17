# Repolex Knowledge Graph of huggingface/evaluate

RDF knowledge graph data for [huggingface/evaluate](https://github.com/huggingface/evaluate), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/evaluate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a5db2ad54aaeadf15c7aa1f056bc6f7bbeeb7e5f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a5db2ad54aaeadf15c7aa1f056bc6f7bbeeb7e5f
│           └── chunk-001.nq.gz
└── blob
    ├── 004d9011ca533ce5e8ed79d4a607c9ed199ee62c.nq.gz
    ├── 00c97c6d6a8c1d63ced5ab59047577ab8174ec55.nq.gz
    ├── 01364644042a8df60a161f30e60fe4c12029e3cd.nq.gz
    ├── 014dc0b32b5eb21808862301613360902bcacae1.nq.gz
    ├── 036c7211c00774608a613a2354aaae763c03bbb5.nq.gz
    ├── 03afd1700180ad1d0eeb0d8e885c9ad4c67489e2.nq.gz
    ├── 055996b1092d1c7d064d448c8f1ebb84781928b9.nq.gz
    ├── 05b0baadc6f18fc1125a0efec95c258c5c43949a.nq.gz
    ├── 063222ebb9814a282c1b479b84e58adc8bd3bf0e.nq.gz
    ├── 0666a386de190bab2906c58fef504a081cf52727.nq.gz
    ├── 071e76ff3be0ad52302ab4d5fc99beb4ed125161.nq.gz
    ├── 07a164583beb6ea53ba9718048b9855727346932.nq.gz
    ├── 0885712e698a34067e8faabe6b029ea8d719e024.nq.gz
    ├── 08c300137c6cb6c4c27a86262f2ffd306e77db15.nq.gz
    ├── 08e030c599698bd0bdf7aa986f1bc0c14bb792cf.nq.gz
    ├── 09903896d9408c5eba8fdecaf8c288e3fc17e72d.nq.gz
    ├── 09de31f19dedda5dbe38ce0295d8e5b0d962f389.nq.gz
    ├── 0a563648a5b9a8624ecd508248c9a15be8dbba97.nq.gz
    ├── 0b77fbc416b18f5668d2f466f2bb0f12957bdde9.nq.gz
    ├── 0c414a42fbffbec02bf8aa5862a0a6775bca2df6.nq.gz
    ├── 0cbc7ed2c0ffe712cde35cef4fe86b1f9e4939c8.nq.gz
    ├── 0d11b1f706b3d99f16537dcec21c0a46b85b5bf4.nq.gz
    ├── 0e2c025c639b785f60555c89d1f03b855e4a97f5.nq.gz
    ├── 0e4895cc156cd4758292c99d3275f1505b748182.nq.gz
    ├── 0fa25d16370b4cdf1cf46d5d314a1602e2e0cc9d.nq.gz
    ├── 1168061ad8adf4105e06a21741c615ec93acea99.nq.gz
    ├── 11ad20a70dbf789bdf89da74f44290277a06e41f.nq.gz
    ├── 124146cd024c05e01116403d6c4a164165288bd3.nq.gz
    ├── 15112ee4f090ba2a76e4b813f521a6448f55b405.nq.gz
    ├── 15522e860f7eb6fc693780f637337c0fdb22a21c.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 1602ebe7d71d14740c0ee7cd251ed9be8ee83e90.nq.gz
    ├── 170d0e5dda6f827b215d740f2294f8165a9b750f.nq.gz
    ├── 17e5248d4a4f49cecada5a8c6719f3bee85d995a.nq.gz
    ├── 1876358cb3d65e64fab0e3ef5c79531df3f285e6.nq.gz
    ├── 18a5ab4755a8af68bef1afcdee4f86ebabcf49b7.nq.gz
    ├── 1b1cdccd4d6498b9ea0db08177222def4f088abb.nq.gz
    ├── 1c12bf33be18033b4fc086c4db95a426266f595c.nq.gz
    ├── 1c20afc46154072824916a449ed908bf82fbbbec.nq.gz
    ├── 1c54425870ee74020ea4eadc825406dd62b09bb4.nq.gz
    ├── 1ceaaee211a3abb180cd0f4e3eb82459523c8a75.nq.gz
    ├── 1d5e74c372d6c5ab683a1058402856101f10710a.nq.gz
    ├── 1d8f9f406828016d38bbc88efd96848edd1b0013.nq.gz
    ├── 1de1656775bbebe6bf4353dabaf73a64a8d443eb.nq.gz
    ├── 1e2614e9aaa957acf7da9a3586cd7ac6920eae7b.nq.gz
    ├── 1e33db2f6a92b686f685e3ed80c9edc2d27d5b2a.nq.gz
    ├── 1e965003fc3dc2de64b71a48a2d97b846ab87b9e.nq.gz
    ├── 1ea4109cce00b058b84edd7867ed872d996417b5.nq.gz
    ├── 1edafea04b601ad33ecfae98fc01dac61fabc202.nq.gz
    ├── 200eb01d70336148db473edebebc96e3137c5799.nq.gz
    ├── 20d92316b60c4d98bdf02afe13630f3ec7f8760b.nq.gz
    ├── 20e2af28ed4df4e99c6d67cccdd24dda1c8cecf9.nq.gz
    ├── 2123f9f62a2ae6a5f2cb772b2c92e05f4bc03f90.nq.gz
    ├── 21aec5af413a5e8321704ca6ec172df48a900ab2.nq.gz
    ├── 21dc1b801a3c6691d3c234b57fb94b12b416ad0b.nq.gz
    ├── 21f83429fce2e58cf36c210d057de761640b2281.nq.gz
    ├── 24b82b06fcc7355f4387007992f8caa13df4b9ff.nq.gz
    ├── 252d16b6c6f4f45ae41bb982c00771ae3d707441.nq.gz
    ├── 259b5c7b9ddd9704b65d747bda9907df2479fa4c.nq.gz
    ├── 264dd46c41c956194d8faebc7f701ac62f9f9a63.nq.gz
    ├── 276a6c43a7e808d53be7cd9f57295a5d97d277f0.nq.gz
    ├── 280ab818d6e278cd26cfd2189b35fc7983ec0aeb.nq.gz
    ├── 28672438d8e576b2d0f323e2d737abb285be24de.nq.gz
    ├── 288e17e8104b7578b23cb20bc71ade3f07f53442.nq.gz
    ├── 3047caf48d013c0db28fe16ffb9a62424eec6f73.nq.gz
    ├── 30b8fe447f13fd199a4d6388fb689450975db7b7.nq.gz
    ├── 30bf8a0cec2251972e872fe09d15b6a7f2858f2f.nq.gz
    ├── 30f10b89aa93edb8f3fdb603f692081bd21dd5a7.nq.gz
    ├── 317078810c893387a5e0b6a697e96ac2d9483d33.nq.gz
    ├── 33953b07314852735bbe6c04760fe886fb3b6fae.nq.gz
    ├── 33b491b1e2e67ac99ad332d059c5224d899dca8b.nq.gz
    ├── 3426cc3a81288f41fde0d6cdf535f9220b73aadb.nq.gz
    ├── 35e72563906789ff02b983daa7febaf65fde63da.nq.gz
    ├── 36d2cda6bd6fa316879c2b26f3f97fc3f8f9503f.nq.gz
    ├── 372302c049278bc49ee848e45a61bc71e4ad17b6.nq.gz
    ├── 379a9f5e4bf84001e4f5a1ee642d20450135fc39.nq.gz
    ├── 38a10c3b34ee7dc24540fe8ece482e26f9cf3588.nq.gz
    ├── 38eb3fd38c21e1715cab970448654c9dc8a4f7bf.nq.gz
    ├── 391d65267014015c0f84ce91ab30a982e6bf6bac.nq.gz
    ├── 396d7ac8abc6d52180fb8d960eddad9b03919a21.nq.gz
    ├── 3a135afacbdd142a40cb9bcfe6073b76cc62d995.nq.gz
    ├── 3a887b6a21d4ac83b08ce90609d1d549dc6549be.nq.gz
    ├── 3b273568b99eb1c2ddfe2c685bb2ec85afbe1b56.nq.gz
    ├── 3b512ae92484772a8d10bdf43f4df68520cdf3ed.nq.gz
    ├── 3ba39d8fad7a96dc09227b1bae7ff849cd05f165.nq.gz
    ├── 3bcb6bf27d14ef87a84ffbdfda0721a13c811481.nq.gz
    ├── 40c830a4b596fd85b6493ee790152cd79b0e7552.nq.gz
    ├── 41b7d78d34856615fee2762cd51aacecc1cdc910.nq.gz
    ├── 42c6b9d0ebc561ea5edefbe01afc6f3c31a30007.nq.gz
    ├── 44a53000472750fbac5006656345038768a0db12.nq.gz
    ├── 44ad5052d08a72f946798ef6e572059541bb73ec.nq.gz
    ├── 44d372638f51aab0b358217cd059dd1353a7f494.nq.gz
    ├── 450a63cc303b2eceb983656a6201e7702b8a56d0.nq.gz
    ├── 45a1a1c3dbdcc4d4252933c4ef972f1bdb175a8f.nq.gz
    ├── 45a436f8c7c76daf6761b621e57b191120e72a8d.nq.gz
    ├── 462374e01a1972146dc87c0fa70864711046ee2e.nq.gz
    ├── 46a8408798a65bbb18157647da7fec8c91aef033.nq.gz
    ├── 470300f2e1f3c0fc9114d9c95c029ed0919e14ce.nq.gz
    ├── 4830128cf25675a2a6fe810c36f0469ff40f6c67.nq.gz
    ├── 4909fa251ff82893d7c3c536bb111ae947735a8a.nq.gz
    ├── 49d9259a54adadf3358b73e26c4e8fea083f59e9.nq.gz
    ├── 4adb9986cc4c5cd08fe03246d4dc8f54a31e0839.nq.gz
    ├── 4b245f1e27937ba85b4404dadb0f5cbf8d3f0884.nq.gz
    ├── 4c19864d34e346a25a646d19ca27aecefc260061.nq.gz
    ├── 4c278905f9bf9a61810b6ba256dae331ce6d8a8c.nq.gz
    ├── 4c6b193b97b8cdad0fafd75b7dcab2305510d807.nq.gz
    ├── 4d0530a826630b6a1dff034d5d739553845c64c9.nq.gz
    ├── 4d4814295cbcb796bc000d0db950ca9b35bc1d73.nq.gz
    ├── 4d4f21c74d1323e5c7c3e80b317f9c96e1081a28.nq.gz
    ├── 4e10e799a8075bc458ef18ba92e9653ef1b89a62.nq.gz
    ├── 4eea1a6a0c63551f0db9302130c7f5a7acced4fa.nq.gz
    ├── 4fe2c3b4c378a55d0cb869acb95dd6e35386de99.nq.gz
    ├── 505015b158eac54411ecdec3a28667e4cf3e1c94.nq.gz
    ├── 514080bf1a2b571122069de43e6faefc6a4d5d98.nq.gz
    ├── 5189f0b938e465e0b0554d0a14c5e96e8f1b4a66.nq.gz
    ├── 525287274f6137b655c504082debdd10eae5f982.nq.gz
    ├── 52b0e8aed7c551e2e5d173651d6f25565b6f0f0f.nq.gz
    ├── 53517a805cf84758b858612b62794b874590159b.nq.gz
    ├── 53b402e563499116a50c2f50222b666b76c3a943.nq.gz
    ├── 5423d3579f8135484afdf5e24279b2f93df0e8d0.nq.gz
    ├── 557172cdbf7680ce80ac60090e66ca50e8b0f4bc.nq.gz
    ├── 5583c25d2a780cf7a0f691f0afe0bac6569bab5e.nq.gz
    ├── 56baa5ec6c9867771ebbbf6821366b4ebdd31ef6.nq.gz
    ├── 56f7d3a98bb1bcfd747153724d77cff546124757.nq.gz
    ├── 578ebd2e846fb3519c8cd3efb284b4c373eaa4ce.nq.gz
    ├── 582df789b608693d0262b7c546e8aa94595b9b78.nq.gz
    ├── 58a477a928113558a68c019540daadd206d56458.nq.gz
    ├── 58b021c0709484732e0e0524735e7a6a51e44f3f.nq.gz
    ├── 58f118ded69c2b589eb1ab89e9c5fd93ab7eb41d.nq.gz
    ├── 598b0f9295a903002b367a629bb3cffbfd47402e.nq.gz
    ├── 5aeab0c08bd75f3039ab8b7452adf52d0979b808.nq.gz
    ├── 5c143c4978d02231681009e82f9b1154c0733414.nq.gz
    ├── 5c77b0098c7f80e74cd3b2197f12b6e087cab35e.nq.gz
    ├── 5dfcc1acdc65bbcd7a5016e7007807441c4f670f.nq.gz
    ├── 5ea3303869e05a5f6ec36cf3181cbdb833facbd1.nq.gz
    ├── 5ed0e76206f2876d52106eb9fd01185ab2bb41fd.nq.gz
    ├── 601ed757507caebec67493462d11eb4c8901c2a1.nq.gz
    ├── 604f93ab3d7b5c0cd6428df1d67a3a1791a954e3.nq.gz
    ├── 61be0a25f0b7c1182f1cbb30c4252362e326b967.nq.gz
    ├── 629cf5375bdff6520dcd7c86dbad8416ea1150b3.nq.gz
    ├── 62b07e07690f7c26bb1a9e3e0a8c621f665bc5c0.nq.gz
    ├── 62bc3fbe56cf92c6cb9ccf57796a53be5dff0522.nq.gz
    ├── 630637afffa554a9ac5588a774f4e0bf8b81a2fe.nq.gz
    ├── 6335cf1b0ff47f0f2a409d6641fd5c528a31e949.nq.gz
    ├── 633d2e0140474066e50609bae578387d4998369a.nq.gz
    ├── 6582ec47a21ff99a2b3e5696820f3b029b99a486.nq.gz
    ├── 6589f871a0b09e5ac45f71bdab13fcbb91410fcf.nq.gz
    ├── 6736bcc7d4b33c4772d4243a9fa05986598f4bb1.nq.gz
    ├── 6798775ab4cf401802e69b2be6d49af8b2b2fc2f.nq.gz
    ├── 6b80b769827cce0e5b4e689bf4477ec78765e7a8.nq.gz
    ├── 6c39a896a97f38056e34fd1536b9ed69c514f416.nq.gz
    ├── 6c4a7e2435106940f05565b5523f3dc53c98ed1d.nq.gz
    ├── 6cccd91ec9e4b6e27579abad648291d0d6b339ff.nq.gz
    ├── 6d01a084b99c92f920679b7261bb8d5cce66ae1f.nq.gz
    ├── 6d5b0970c9d00743c31656a2d5c993402d3e9263.nq.gz
    ├── 6dc6fe5b276009d16a04f0cbce4f9d42cf31207d.nq.gz
    ├── 6dfd2c035695b38c1e4f0d9d4929b12c6be30920.nq.gz
    ├── 6e077faacdec6e69fa5d9c696350847ccce311c4.nq.gz
    ├── 6e6ccafc20ab508661ed8a2964e51772e7012fc4.nq.gz
    ├── 6e756f4d4c9bc78390e3bb0d104f0f4515c2a0b7.nq.gz
    ├── 6f4144ec3fc649340ce77ecddc60a43328c907c6.nq.gz
    ├── 7092efd949bb407beb485f25d6c1847804a79170.nq.gz
    ├── 7370e289d29c603a33efddaf63ea4b140a1ae144.nq.gz
    ├── 7405f729dcab78fef1582199a2821cd367fe156b.nq.gz
    ├── 7512eb55ee41469e83db4a637bc9c61b6afe4e41.nq.gz
    ├── 75e0f7e00fca51bff42f924b4d98042d0848f864.nq.gz
    ├── 776da43b5ab8ae3dfd6871b6dfb793a2cc15f9fc.nq.gz
    ├── 7948097f8903b2e7f6fef3ae36f8b6153991cc1d.nq.gz
    ├── 7a85cf386b67ac245901a4fe6a22bf7edf6143b1.nq.gz
    ├── 7bd2cc9cb456af0160f1e1840728d3d85dcab1a7.nq.gz
    ├── 7c05d59ec96e2789c3850ce0d656b932564d34af.nq.gz
    ├── 7d021184d0f45ae1fb01d86f8c5320a4a62fdf89.nq.gz
    ├── 7df8b26f3b8f204880d345de2e27b1349483a06a.nq.gz
    ├── 7e22ac6a4baf025348645eb91d8f48fd206f715a.nq.gz
    ├── 80593c4dfa0f96c8d3ea5ff6131c13c0a94181eb.nq.gz
    ├── 81ea693fec8e2c4416bbdcf21df19c3eafcb3a34.nq.gz
    ├── 82831458bb8789ce9c9418d6c19d4af4ba5b35a2.nq.gz
    ├── 838242f4a9b6aca112847af598d3e039205fa5c8.nq.gz
    ├── 8437382790dfabf9aa62ade37b6f166dfb69e877.nq.gz
    ├── 84658b125f47aed592b6da4659ec60b22e02fe34.nq.gz
    ├── 84aa2f948a00c2613002720a04abb183e2892a07.nq.gz
    ├── 84eb91d19f4a5974796fd201cc805cbb22c907bb.nq.gz
    ├── 86118332c6d2293f475e84e80726364dcc63e292.nq.gz
    ├── 86536e8b85c78aa15a905e8cd8955176da56b231.nq.gz
    ├── 86b85b5e33d74260bb78d83a0225dc004729db5d.nq.gz
    ├── 88cef8b1fdb3e01c9916e3fde47a15e7881211c4.nq.gz
    ├── 8a8124560867182142d4cb3c0d94b0646105080c.nq.gz
    ├── 8c607bf1e2fef42fa3abcf1c672c90b576e6eef0.nq.gz
    ├── 8ca60ceff30c518e617602cbe050e70de50a7874.nq.gz
    ├── 8d6b262b7c04d29b6480d0183435c4b7599d97ba.nq.gz
    ├── 8d8d20d70e85b33e0aacdf90117dac45054f6550.nq.gz
    ├── 8f38be6e6533b94833ca11ce198095f064b5e79b.nq.gz
    ├── 904e17ff28b5c38a27953d130f359e2d37ede60c.nq.gz
    ├── 920b46cf82646adc77a312d9e90e5d10040b274b.nq.gz
    ├── 928da8437c330671424203a5de68732e7cd21a3b.nq.gz
    ├── 92e9ca311c8d45b2baa3024a6f3dad1175ff0e17.nq.gz
    ├── 958465145f45b0a1e5d3202d3f32fc350406d40e.nq.gz
    └── 96ddc17c415bf2e6c362fdbebbd7da7fe48ea69f.nq.gz

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

[huggingface/evaluate](https://github.com/huggingface/evaluate)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
