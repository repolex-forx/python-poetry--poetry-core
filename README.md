# Repolex Knowledge Graph of python-poetry/poetry-core

RDF knowledge graph data for [python-poetry/poetry-core](https://github.com/python-poetry/poetry-core), parsed by [repolex](https://repolex.ai).

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
rlex download python-poetry/poetry-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b52c25c451bbaed9f309d45fc6e6e35c704e55bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b52c25c451bbaed9f309d45fc6e6e35c704e55bf
│           └── chunk-001.nq.gz
└── blob
    ├── 01cf728d8934a057b42f28ceb798cfbc63852482.nq.gz
    ├── 02114a532f002b205b8774fe4c9d414d0f074a9f.nq.gz
    ├── 03ec729d602c2c0d6305b5f22079b6aeb0560e04.nq.gz
    ├── 055b95a323835d2da85d50553718e62d9f2e01b6.nq.gz
    ├── 06da5a04845b804acc9ac91d82a2516829483bde.nq.gz
    ├── 077cc3f9074c01c0796051eb23fa4031f0ebc099.nq.gz
    ├── 07e9283fa0103758d3fcfb0c07a745d75d326a00.nq.gz
    ├── 085cfa38407ef8d6f3f7539beac4cead585b7c0f.nq.gz
    ├── 0906d396806014855aa73fe4840097f6b5825b67.nq.gz
    ├── 092cc215ebc7e89f2a58566fa65f9c50f9530921.nq.gz
    ├── 093312b57100a210cc4bec536e7da791144493e8.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 0a2ffa274d7896e46b58305748f740734cb75361.nq.gz
    ├── 0ab849e3fd86310e83671e866e31f2afbf5e471f.nq.gz
    ├── 0ad2d013cc25245c7e8f24f537112bc0332e41b5.nq.gz
    ├── 0b49f7ed80848739321b2674d473ddeddd0a26de.nq.gz
    ├── 0b6bf8e8fc92b2ecae6e9fa570fddf8cd8987758.nq.gz
    ├── 0c6018291a572e36dc359c2af985cfe329aacf95.nq.gz
    ├── 0c66c72d213a5ef8db46b1b14726d3251fdb5d35.nq.gz
    ├── 0c72a6f520920a9ed1c4a1db3e559a067a68f061.nq.gz
    ├── 0dd504d554407aed33b278f2f3b46dcd21c36cbb.nq.gz
    ├── 0deae926002c105c8ee1b0d23689a4d89fa990c2.nq.gz
    ├── 0ea2d4fa9e0058bf19776d009f4a983baf849ad9.nq.gz
    ├── 0f1e025e0586505a3ec5563a9a102daa86487801.nq.gz
    ├── 0f503ecd7c08cb12e509eda8bceb77618fb6e007.nq.gz
    ├── 106110500510483721d3eb92760ddfc6f3e869a0.nq.gz
    ├── 10aa336ce071b5ebf71e8545a55b72f3c5b661a3.nq.gz
    ├── 1264acb19b3501c437049664c6bfeb95e520ae70.nq.gz
    ├── 12b34a38933b4c1aeedb4d943745fb1f035c8523.nq.gz
    ├── 1318d50b2657ef3e376091b3e1b30e5b1d83959e.nq.gz
    ├── 133b64421f86ad26448e0b0f27be33df6808c14c.nq.gz
    ├── 13d592ddfff0c8122a91c5d6c9000843d2a50af8.nq.gz
    ├── 149aa9527c577a1828a5a3114377960fd1e41a88.nq.gz
    ├── 151b83a32aae47bd319e7dc23a2e99c124159b6b.nq.gz
    ├── 164c005f1d32827d359a8a9dcf6a931cb9413bc1.nq.gz
    ├── 189b4ac62357a016e6c7a4002d66ad1392b3b346.nq.gz
    ├── 18c6a59515ed52295e05cfa28a26e510325a6fcb.nq.gz
    ├── 1acad4d3de426316ae44f1af9afacb4725753192.nq.gz
    ├── 1b10d6ce068317f81e8b80748306577b582ee9ec.nq.gz
    ├── 1b462f018c5c0c56eec4ebb7cd62102908a59b37.nq.gz
    ├── 1b86deab7b1275ee2415c8959a90438a12c16026.nq.gz
    ├── 1bacf06f6b07e3c8ed4679a07146489eedd28ed3.nq.gz
    ├── 1c07efe3187b18e629e2852776ac107bcb521a16.nq.gz
    ├── 1ce081d0d2b3f8ff75e5b7f3406b7341bfbc489c.nq.gz
    ├── 1d77bbf99f3a4b9e4b38e7a75c368c84514fcce1.nq.gz
    ├── 1eced65d47bd2238febb9c2966f53d44e2aa402b.nq.gz
    ├── 1f24c5954b2b490f1f1826b6478d7dc88a65ef82.nq.gz
    ├── 1fc27d565b4ba98192a5037c791c3819fe534586.nq.gz
    ├── 210413ed02e19021ef464e33819b32124f715051.nq.gz
    ├── 2215fd54777aa0cf4287c76855a0199d7237058d.nq.gz
    ├── 222558f3a182936bc253349e0c624ad57b618b15.nq.gz
    ├── 230c44fe87c263f0c0838e57e91ede91f75fff95.nq.gz
    ├── 2532ed282b654566997db6ec338feb51fdcd98b3.nq.gz
    ├── 263073d5e8d45bfc6e6ff52a17fe4e18a496264f.nq.gz
    ├── 265d70d6a73471326a6d73571fbc6f1c4ac2771b.nq.gz
    ├── 265effd0f120fe5059f1e6158be6f8bd1523fff9.nq.gz
    ├── 273b5df6ba6a754a1e1acaa0a39ab0568a5119c2.nq.gz
    ├── 273bc002e555abe0bc27cc8f89a34eb109ad58c7.nq.gz
    ├── 282cabf874a5297555faf36aaa8d488735d50933.nq.gz
    ├── 2853ff3a8487f47b0f2cb8ad1d08489c51cdbde1.nq.gz
    ├── 2887b8c8497e1c6fe89694e94ad76554d6cdf5ce.nq.gz
    ├── 28d3cb637fa5cfe2a2be3c4fc1191ee635a199b9.nq.gz
    ├── 296828c759d2c2e61018c50b099e718d5250324c.nq.gz
    ├── 2a9686ac65d66cad38f728c754b6446a265ed459.nq.gz
    ├── 2ac1083e121285d97ee7f3c9570bc82af149ce21.nq.gz
    ├── 2ae9072ffa686a2b8ee8f50eb5a0ca3dd8b03adf.nq.gz
    ├── 2aeed237af0b5f66a07862c5a005db0d0c686c7e.nq.gz
    ├── 2c2b495292e1eea24fe6c9a4f65566d15f65de10.nq.gz
    ├── 2d1c25a1945080811bf5ba30541b88825207eaf5.nq.gz
    ├── 2d33a8d19fee7c136a67649567d9da08e86e1251.nq.gz
    ├── 2d41a885ba2afb4a913c5f03994ae0f30ff98867.nq.gz
    ├── 2d66d5ef04c94b3a03c3ff610a727de8fe16a06a.nq.gz
    ├── 2d8423aec03f69d3d768f3c4a6d30bfe31db22a1.nq.gz
    ├── 2dc2df0d552b7e7a81baada89e3ddd3eec0508d5.nq.gz
    ├── 2df691a13a6ac17d8481f53859fd83fe5f175b2d.nq.gz
    ├── 2e706b5c497aaa0812be2946fccffe5ea81ea4f8.nq.gz
    ├── 2eece88768a066ea5cc9875a2a76db42db64ad73.nq.gz
    ├── 2f0ce20744749bcf3aea28177eb764ed2afa7c85.nq.gz
    ├── 2f8d8a21a4a283e6e96989a4e14dfc8503b5a7f4.nq.gz
    ├── 31b594839909df0d9713696fc9b5e3c93a44a21a.nq.gz
    ├── 324a152ae67f3ca0515abd3dd6137e84dd113258.nq.gz
    ├── 32a36e3e7165de891c2c444527082b4f5a266afd.nq.gz
    ├── 32a92735db299f7d4084d2969d9f5fa3a1871f4c.nq.gz
    ├── 33d01e0c1620834f012649a7180c42a4322ffa76.nq.gz
    ├── 33e2ab81d564461ddb728dc0ae4e35b219797723.nq.gz
    ├── 345f0c25b1ff9afc1ae24b317d20de1e14c474ef.nq.gz
    ├── 347257889d0e9c31dcd49963083737e93b70d50d.nq.gz
    ├── 34b77e4ddaf0bfb3d8a212cd4f6fbd33354db48f.nq.gz
    ├── 36a077afd9523e22fc250307c5d41135261f9ba9.nq.gz
    ├── 39ec567807db884f1b20e7f906e845b8121c997d.nq.gz
    ├── 3b12ebc940d9470904c18c83916af7952280870b.nq.gz
    ├── 3b97a3d94489ba159319d85dee4054ccd48f0c0a.nq.gz
    ├── 3c7edf13a1fb372c7c27435d8adce6a929cd8501.nq.gz
    ├── 3cce862ca6c3fae494ac225fcbd2321a3b141ae7.nq.gz
    ├── 3ce109da3fc713b3b064dd03e2c420d092794b68.nq.gz
    ├── 3d706f61c2f25153181d27d2238a35b2bb127201.nq.gz
    ├── 3dc1f76bc69e3f559bee6253b24fc93acee9e1f9.nq.gz
    ├── 3eddee0a981b7f0ec5136b1da4fccc40ac51aca2.nq.gz
    ├── 3f0df9023f90ca00be6f017b31fa94e7fd812713.nq.gz
    ├── 3f613eb215f8db54d76231ad403983ac7659d0c6.nq.gz
    ├── 3fc8d4fbb251d7cf6da9c536cda474fbeaeda4dd.nq.gz
    ├── 41b06418805bdfe2b5fba390566aaa4d274f829e.nq.gz
    ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
    ├── 4306784d9a26466aa0a210cb2f262903c67d46ca.nq.gz
    ├── 4340a907ee5dd1da92ebcea992c4a6b00eee0433.nq.gz
    ├── 4456fdb6c6960931d27409032a7f37c6b18b736a.nq.gz
    ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
    ├── 44f728ea7b6156a5b5f72a3c90ca40b1b3794529.nq.gz
    ├── 44fce7aed095d81977013593950976f77fcb6a4e.nq.gz
    ├── 47f014647e4100de8c51cfd13e77958a406327b0.nq.gz
    ├── 4a8767b9009b7ebeaca29ce9125e2610297522dc.nq.gz
    ├── 4ac99e645bb5faefb8e653a6f2a5c719017ea917.nq.gz
    ├── 4b5f4dddb18e68719aef38591997cade57946867.nq.gz
    ├── 4bcfd9320e8fe523f6d3ff954ecd7cbe2b48333d.nq.gz
    ├── 4c6f3033d6e309efccbf251b7a3f7d1917b84b19.nq.gz
    ├── 4c83ec4f603c660fd5b64d82d8c30166ddfb6d56.nq.gz
    ├── 4d609342caf5d93b68f2195606bc09c60c6bc541.nq.gz
    ├── 4d6eca6cd6f50fc4c92810201f16fcf5ec5eebbf.nq.gz
    ├── 4de7acc0a9e5c22301623438f6290fd03f8040b4.nq.gz
    ├── 4ea8077d1faa07759ef876b07eeac1e68ad40119.nq.gz
    ├── 4ea8f643a9f59b4d28b820149873f3cd0e262c52.nq.gz
    ├── 51b60364603fe03e80e61c03cda07964fa474e76.nq.gz
    ├── 527cc7c115ce1ebdb4b0ca32766856cfb75a6536.nq.gz
    ├── 5370ec87e61881a9f290d5764411328366b46dbf.nq.gz
    ├── 55624407ca759edbd8911c03392b2ee95bbfe3a4.nq.gz
    ├── 56b8ba5bf9f4c870cdfc2e1ae516e35bae38c373.nq.gz
    ├── 57b6cc255505eefece1beef59deb57b653406ca8.nq.gz
    ├── 57ba2213b55b052123b52a9bed8691695f8fdaf9.nq.gz
    ├── 5845305caff3aa299d4b35f1eafc4d6c12cec702.nq.gz
    ├── 58bb26cca166505f56d950e10ba907c0ff0e4205.nq.gz
    ├── 5a964bd22fd540dcb5e5f1ef13510346c28800b3.nq.gz
    ├── 5a969154fefef91c98d6c42a5a709745ced5d0f8.nq.gz
    ├── 5aca79eb23e7f086516f044e1ad87ac386970a2d.nq.gz
    ├── 5b29ffccef86b5755db8a2cab6f6f4491573eb36.nq.gz
    ├── 5bb485d142ce5b2e934aebb3f5052688c438632b.nq.gz
    ├── 5bf778601f04bac9920517da23d18406fe2298de.nq.gz
    ├── 5e22e1fa1c7959f775f194e5bff14643ff7fd606.nq.gz
    ├── 6232baad2286319311fbf482f0d4f4c6fa5bd147.nq.gz
    ├── 63302b7ef3b7ead9c11dae0afe1dabfe3b620a49.nq.gz
    ├── 63d29a4b65e83c8924d0f3bf102bfbdbb914d939.nq.gz
    ├── 63df92de050af93b28e8efd3e5b5d6fa834c92ae.nq.gz
    ├── 6626840762aeb152878aed7034bc0023e2da8348.nq.gz
    ├── 666b2b24f6def85dfd2eaeb042cd911936121793.nq.gz
    ├── 68fe5fd482707a1ff77d9c469a1162a83298070b.nq.gz
    ├── 6a110a1f73a98532b9c05bb8ed42ee4aa5987d22.nq.gz
    ├── 6a991f05af1b8754884cc742ec725b5465b00023.nq.gz
    ├── 6ce15cd1f477922abbef77f2528aff8431608c5f.nq.gz
    ├── 6e239c72e9d1464f442c276a2bcee3bd7357056d.nq.gz
    ├── 6ec7323f449ce3b4e70c6f7efbae4fd7153495f7.nq.gz
    ├── 6f62d44e4ef733c0e713afcd2371fed7f2b3de67.nq.gz
    ├── 6fb808ffaad86ee33b9f146126962e536d175ec5.nq.gz
    ├── 713e46e0901dec993d7e986bf809249158bc72ca.nq.gz
    ├── 71b6a4c1e17cfd38f4ec9c96888b825455d07a62.nq.gz
    ├── 728753c44db4176cfb544194b6b20f93cef7d707.nq.gz
    ├── 72d0c0beeda49b341bb036b5340faf15cfb32ec2.nq.gz
    ├── 7335117c21b8617ace85a2db01e8e1b2063bf6b6.nq.gz
    ├── 74b7c269dfabf6237c16454a25ce672ad6ef326c.nq.gz
    ├── 74c4136f535085c88902c00f506f0c4ccad67188.nq.gz
    ├── 74f373694181abd20ea5dde421d1c2abb0052e72.nq.gz
    ├── 75a5db8002b0bdd78c8e127fa3deb030a70bc6eb.nq.gz
    ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
    ├── 77d54395b7d5d149a8d6eb56e874451d45172521.nq.gz
    ├── 77dfdec14febf5213a31b3abddb2c285e76cb586.nq.gz
    ├── 7812ac06323ab35396d4910d40da73d7cfa86491.nq.gz
    ├── 78eca4ff91c70564126d0695e40310d9707ed2e2.nq.gz
    ├── 79786fe9fac0ec9bdeb40922a8ee1569c650a522.nq.gz
    ├── 7bedf82ebf951b8e598194258cc7c9f135569446.nq.gz
    ├── 7d4cd45a65975a40634060ea81d26441ac1facde.nq.gz
    ├── 7d5b48d52d4198c9260eee5cea9d146b8dbbf4a7.nq.gz
    ├── 7e38e8abf63bc795ce8fe02e4dd24257b7119c99.nq.gz
    ├── 7e9aaa7c50dcf7b46771f55d31373fe5e6eb0208.nq.gz
    ├── 7ef41c5d4eaf3eac556c8fef40de53403c5d3fd7.nq.gz
    ├── 7f1a0119d2125b8167feb869571ae89cd1cc9ceb.nq.gz
    ├── 80ee5d35fa905f85b22e53a860f22168dfb511cb.nq.gz
    ├── 8144a65c4d2ea0b9f9946d795e556221ca9b9438.nq.gz
    ├── 838119a8e659ec0ec77612923cd509d5cb99da1d.nq.gz
    ├── 8392a4539dc81933ddf7a02919394b914a0f6024.nq.gz
    ├── 840533168afb0951cdc9b79749d7cbbe6fc4a180.nq.gz
    ├── 848cf2019afbb29c4f8cb60d9238725c688e2478.nq.gz
    ├── 85c9c128dc2e9cc1551dcc2143c7c2eea2afc776.nq.gz
    ├── 86dcc30cc6137e291c0afa8436dc0011c0e17481.nq.gz
    ├── 86de1e6d599dbe5e8426eb130db5e8558cb47d58.nq.gz
    ├── 87195ed238da37b4e960a35b55cdae3605cbaf05.nq.gz
    ├── 87c34f31def33d2a35bf1c96258742528bcd0dcb.nq.gz
    ├── 8980ea3c0d5274403c52e1140abc9c981969e124.nq.gz
    ├── 8a75966b29642baec43d1a89343da873b1574d26.nq.gz
    ├── 8a8e8a8fb257e453536bf85fdf46d7f6b58b4a5e.nq.gz
    ├── 8ac7ecbec6ab6204b5002d4d2c0e492c1957e4f0.nq.gz
    ├── 8af2072beeb5b3af2fced47305379a387b6e707e.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b36a60d6e56617f19cfa4763690214a62185b64.nq.gz
    ├── 8d1b44cbaa341e60ca6346c7b9206a9190a53ccf.nq.gz
    ├── 8de3a59b0b6e78207ed79384bddd03ea2a3d7d7b.nq.gz
    ├── 8e0a3756cd4189e4ebcd13626e035f3882712ae5.nq.gz
    ├── 8e612d497159e181ebef79e2c59380f08a03891a.nq.gz
    ├── 909a09b002cb519bd99a8d270b0af666ca6d96ee.nq.gz
    ├── 910186f6b433fa7b2197a81bdea4c1d8782e1f2b.nq.gz
    └── 924a2b664869200621f5a04b99870b0d8d4bd707.nq.gz

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

[python-poetry/poetry-core](https://github.com/python-poetry/poetry-core)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
