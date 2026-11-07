# Repolex Knowledge Graph of certbot/certbot

RDF knowledge graph data for [certbot/certbot](https://github.com/certbot/certbot), parsed by [repolex](https://repolex.ai).

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
rlex download certbot/certbot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 138defe9c7c68ceb29a66cbd5f3a346567139211
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 138defe9c7c68ceb29a66cbd5f3a346567139211
│           └── chunk-001.nq.gz
└── blob
    ├── 002b753600ab41eb5d361c7595f6b1db7db03a1d.nq.gz
    ├── 0087126c4008d3144ef9f5f24411607786e87284.nq.gz
    ├── 00d1d2b0bc66acafdf5942a83b12846cbc7d1a10.nq.gz
    ├── 018a7f7c09b8ae17ee55f7a12b16051a6495edc7.nq.gz
    ├── 0291a93415ee459231b96b650e28ca883db5725f.nq.gz
    ├── 02928d91cce099bdaf0e809bbeb2ae01d1b205e0.nq.gz
    ├── 02a1459be80ea378b9a85ba9ef7fec34cb7a30ba.nq.gz
    ├── 03226ae826f27b19bab645186939813ef7d1100e.nq.gz
    ├── 036c97fa7d3d2937e479087eda27a26630929e35.nq.gz
    ├── 0379003b79eeefaa951965ec108b7242036d285b.nq.gz
    ├── 0388abc2c8e7a216a26c01ad5ee56fbde43705e7.nq.gz
    ├── 03d53dd612a3e77f3634c432c4e89e6bad80a38d.nq.gz
    ├── 05698713697fb931422c6aa1d04dc09cec322b2e.nq.gz
    ├── 0575a68cd920a933143b5f2433e83289ccc0afd9.nq.gz
    ├── 05f80d917fb6622461cf6525546436d428c687c6.nq.gz
    ├── 0660d17178776c0afb9f6ba77072624b05e43dca.nq.gz
    ├── 06d4a72eb513938617b423c173a6105a2a3fb90c.nq.gz
    ├── 070927555a1996c4e4dee059b87219badc225aaa.nq.gz
    ├── 072961dde6d62e97b35ede6b3ad72ce383ddb362.nq.gz
    ├── 0857c5dfdead645b77f96b92bbed9c40ac95b19c.nq.gz
    ├── 089b292983237d98d337af579f912cbf9043ca88.nq.gz
    ├── 08e5305f8fa2690944f8879ae9f734cbc3ca3cb5.nq.gz
    ├── 09891f43433eff9d49f7e228ef1d06217779f2ad.nq.gz
    ├── 099d79989b08da2aa2813fc5b0f87544b3315ea1.nq.gz
    ├── 09cc5397d9f3e31fb7c05476b8ad16ddc2eddc1e.nq.gz
    ├── 0a1ccb0b5c551129ba5e4425c19f980270be3f9e.nq.gz
    ├── 0c56781b3ddbb4198e845840d9d2644b082fb3af.nq.gz
    ├── 0c65891e4612090457debb410442dad06b98c8d3.nq.gz
    ├── 0c8839024ee4ae774b5ecd4399d56c29f3dfe7e6.nq.gz
    ├── 0cbb1083da0fd99107d7d14dbb0f2107c75c2f62.nq.gz
    ├── 0d026242db86a338218bbd18e05eb8948ccdcd4b.nq.gz
    ├── 0d0d60590c164824f59a2a97d0b29521456ea0e9.nq.gz
    ├── 0dc1af725d3646f3341bb2a9ba803d0a160661ff.nq.gz
    ├── 0e9c09cfb23a5f52652fbdeefa1f5826b00a019d.nq.gz
    ├── 0f7c5576274f0dd2327bf2c4527768a0bb2adee0.nq.gz
    ├── 0f8bbbfb5d132e6cabec2b54d75714bcf709ac3d.nq.gz
    ├── 0fd7be0808879480e6a9180afe450b5b70d98b5b.nq.gz
    ├── 103b56009057a72b086c95f190f56f0c056927bd.nq.gz
    ├── 103c1b68d8f7b13d3610a3a6c11aebfb53d2ebef.nq.gz
    ├── 107b7f8cdfec8d27e18d2b7db1dae33b5e47e02e.nq.gz
    ├── 10bf483171893dc7f045aa1db1523feccb072c61.nq.gz
    ├── 10cf3fb54e31ef274bbc130b741efca927100d52.nq.gz
    ├── 1180f2eb1bd7b5b0b2f1267316b1cabb0d628311.nq.gz
    ├── 11cb33b092c986b7fdd71a63661fb25f654b7434.nq.gz
    ├── 1373ba8f389cf0df95feba9568f1ca135a1cb467.nq.gz
    ├── 13a07c00daa961c560ce0edcd06f771f45a56d2b.nq.gz
    ├── 142b31c933b9ae8c19911ec57e364f780085abbf.nq.gz
    ├── 1489a37be18c9ae51e3aac5ee0a7637f311c7ab7.nq.gz
    ├── 14cf95f9ec32f5110e3cc339de321c1b2b84c6ab.nq.gz
    ├── 1500400d7720e65bbcce8b13043eb49ff7d6c09e.nq.gz
    ├── 15194ae3a5d29273ce3a7d1765e987fe2c054b3f.nq.gz
    ├── 15bc5fb3c2de2e37a83111aeb8884f3646a6ebb9.nq.gz
    ├── 15ca8c81a9aa09a1f8756e705c8262dde64fd8ee.nq.gz
    ├── 1622a57df652b3e7e73bcde76261640f569de726.nq.gz
    ├── 162d2b08d794977a11178e716eee9595eec377e0.nq.gz
    ├── 16a57c16cb8bd33889e5057b644da0dfe6a4c102.nq.gz
    ├── 16db737c738736319af1d4e562b8762fb3b565be.nq.gz
    ├── 182aa6d78fffcd6505e8f83b34caaad57d6de95f.nq.gz
    ├── 199814126f86a07407caf974cb7f7853c924c52f.nq.gz
    ├── 19a846a46fb567dd46d2a6f63d113622f696c622.nq.gz
    ├── 19dc494442ebf3a55540a6abdeb6d6e52aee29ef.nq.gz
    ├── 1a1deb96b81e2e12e9c9b10789b748ae833b4b15.nq.gz
    ├── 1a961accd6b0bf728be59e3e7af6493eae12332f.nq.gz
    ├── 1b04b2998b36bba84983e18f2742f218cd9de9ab.nq.gz
    ├── 1b9c2b126b62b7aa68471bf01baa6a0f6a1ade6c.nq.gz
    ├── 1ba80ba4e9e298c3be68348dd1f640f141a19b60.nq.gz
    ├── 1c06d5497a68b892a6e7c6ebbd25710269c7b81e.nq.gz
    ├── 1c5a51cb4600bdc5af16412eab317ed1e231bff2.nq.gz
    ├── 1cddad6131643da5a5378f1882a31696219c609e.nq.gz
    ├── 1d56d3442e985a0ca54f62f86cbe4dc842f40f36.nq.gz
    ├── 1e1139514b286771e8eeaa8c55490c3da3dc23ce.nq.gz
    ├── 1e530778047ec5dc32a2bd64c6c92b72aa1b6972.nq.gz
    ├── 1ea53dfab405046dc8f02d37f5e8c0998c07de74.nq.gz
    ├── 1ef6163ef8b156930b2b1d05ab5dc9c2b8144665.nq.gz
    ├── 1f768f079fbec0a81b8d9693accaaaf0ffc17771.nq.gz
    ├── 20d718409eb9b141b0af51a209d2e11be7f9c103.nq.gz
    ├── 21408755087bafb175e7313a80ff8904941610b5.nq.gz
    ├── 2276a859833bacec131c6f8e0ab092d7241d1e2f.nq.gz
    ├── 22b59dc981263760b5b491647082ea5f6ea281e3.nq.gz
    ├── 23139f7ee09474f81c5972bc092b863ce955f0c1.nq.gz
    ├── 23d2fbbe980f7bf650f3ea6b8acf958f1e6ed14a.nq.gz
    ├── 23d7acd550e27b1eb4c9bf396a1df886517345f7.nq.gz
    ├── 23e9f36efbb6178224b5524b8e639c1b80b28723.nq.gz
    ├── 2405143acc32fc96da34263722c57db7fbf184c0.nq.gz
    ├── 245375f958c86402a053901c547f8f76c968dbf5.nq.gz
    ├── 2600295760496d2ba292ff674b4f7d4e034860fd.nq.gz
    ├── 2609e2080d2893c0b29161304afe9198c39efe5a.nq.gz
    ├── 273694b51c888545aafc1ea526c2fa7a55f26689.nq.gz
    ├── 277d4009f8e97cf2d33718da30467918ea08f266.nq.gz
    ├── 28181d739150931036d95662fe527b3fa9f9fb43.nq.gz
    ├── 29a54e2a1619be7c82411c60287054f8819491ff.nq.gz
    ├── 2a50dc33dccd9652d87d8322eadd22c87acd53d1.nq.gz
    ├── 2a5bb7be290cd9d76525e3ef48baa85e1b4eca5a.nq.gz
    ├── 2b2689f09e5d1d7980a3e6308a1780036e29e0a3.nq.gz
    ├── 2ce8a820983f1ea71d5a69a47e69d15051acfeb4.nq.gz
    ├── 2d1201ecf6f712b3bed81246b7c295276abd1e60.nq.gz
    ├── 2d6b30420f8b4c68f3b3448e2c9616595c9699e4.nq.gz
    ├── 2da2d6cd3639c406cbeadef571fe446895583087.nq.gz
    ├── 2e10e9b56f4a5b2b0dba7d6b3e514ddd4322c673.nq.gz
    ├── 2ee44b3fd5b4f90e61dc7a5fa272fb1c0dd0852b.nq.gz
    ├── 312ad687971c411a8fafc7f7f2dbf51943e821b9.nq.gz
    ├── 31cb6093c24a3261eae39d19cfa9764032ef8d4f.nq.gz
    ├── 331059a6098425a64b53d75cac533651f6daa761.nq.gz
    ├── 332b89fd5f401f39e758f9386a78716e2f448af8.nq.gz
    ├── 33a68c74d2c58e84aedc4eec21b6d16d25e4f470.nq.gz
    ├── 33b87d1a2cbc0c0c581c7e63fbac95c0d540b7ba.nq.gz
    ├── 33c598fffd905eba72f0dd57cea0a586a9b10a3a.nq.gz
    ├── 33e30a63bb6b2bf29c445515faafd3f8fac572ce.nq.gz
    ├── 357100558f0c32a4ca5a75c6c22943226e36237a.nq.gz
    ├── 35c2913e753c25db55a7feae009b461927a099fb.nq.gz
    ├── 35fe486490185bbb38875485dfbbb7b12ea36547.nq.gz
    ├── 37586abbf7f9de0a99b338f723a13cca75599d9a.nq.gz
    ├── 37fc215eddc09b88ebf5b6526d5c487830c1986a.nq.gz
    ├── 38635aa9de2a50a5244023a839fceee7efa60a71.nq.gz
    ├── 39e6d56f90f009d2feb71e32b7e571124d49fcb9.nq.gz
    ├── 3a08c14322d0951d67e81c82632be10e091b2644.nq.gz
    ├── 3a7e12926a28f5aa839640a9a23950e53146d6f6.nq.gz
    ├── 3c4632b73882eaa0687732a62611fe5f759041c3.nq.gz
    ├── 3c68dc087cba36ae8f0075931a3650ab309f968e.nq.gz
    ├── 3d022f346b1a948dfc733dd91bdb64808d2a0b7d.nq.gz
    ├── 3d0ac97ae612a7e958f27de1fe2845516e240517.nq.gz
    ├── 3d0b5d0cb683f4b4c55d870e05850a7478517d13.nq.gz
    ├── 3d2336ae0f42687a0612f58c7831017a184d6175.nq.gz
    ├── 3da1ece0ac27adc10a3f1b52826215e3f290fad3.nq.gz
    ├── 3f03358499dcab0eccda6a60a6e6f548d4a66b44.nq.gz
    ├── 3f0ba1600d56e5f233dd08fe9054d0c17438e014.nq.gz
    ├── 3f6e7e7c79d5e6814a6ab0844adf9e2f22576701.nq.gz
    ├── 3fccab043070aa35099304236e799a0010e4b73e.nq.gz
    ├── 4094e417323e2f965a655a1882115ea0916a894a.nq.gz
    ├── 40b628985a5bf2d7c7c47a0d28231a0805c994f4.nq.gz
    ├── 418f5f5bc0f5d4cfd16d3bf0bce5f13c49c7b278.nq.gz
    ├── 41b06370e96d85ac51157ed6ea92bb4a38e227bd.nq.gz
    ├── 41de4d236187e09bbe51b9ba41fdd0a90d59a048.nq.gz
    ├── 422d221fba162f6fb94d9b2e28226bf1a05b4705.nq.gz
    ├── 4314e4db8bd866441910691ee6b17f47df3f32aa.nq.gz
    ├── 43dd27746aeee7706f3626a206fbcf21e4ac3c7d.nq.gz
    ├── 444f0dade5c5035d187f96febe69fdc231eaec18.nq.gz
    ├── 4455137b419638f2b87924735b1c928873dc12aa.nq.gz
    ├── 4456914ce3a3bcd46f8774340cac6d58426d3239.nq.gz
    ├── 452bc45cdb6c7b700c774dcbe74f310502752149.nq.gz
    ├── 4547ac713f7dcfe11d345106e78b1c4e0930ed75.nq.gz
    ├── 459d8a829fa233bfac74e20cda040cd0e23cd25f.nq.gz
    ├── 4627c57d2d2a21cd965d4b11ea2d7d5519aedffe.nq.gz
    ├── 46a082b9c2b0d5ea1691e395a3c28e2eac40db6f.nq.gz
    ├── 471844859c6c16a35db8bf5e97406a761e559071.nq.gz
    ├── 4733013ff0d8da45dd182f98f89837c464567e5e.nq.gz
    ├── 477cb1c45c401ed7e08d5d56d0d39e9383fb9f03.nq.gz
    ├── 479edac5d5d0f9d05c99389c0f52aac324d7d576.nq.gz
    ├── 488c8ef6a6ed25af5b82f3722258316c598c825b.nq.gz
    ├── 48a3e8a173a3c8778296e61c62361f8767d0a8c8.nq.gz
    ├── 48c0f8aeb068acb594b003277a34f45ca0aeba66.nq.gz
    ├── 49d82725ca45a9cc26ed4f6172a25abc4824f3c0.nq.gz
    ├── 4a71ca8c3ce44696d8ebd504e3583017418b5882.nq.gz
    ├── 4a7f269209f1c402e56568e6915b6ea8c7e45dd7.nq.gz
    ├── 4bc4e68e52bc8bbcd4f87764743a78f35b04cbe3.nq.gz
    ├── 4c2b51156a3173dabda509d50ac462d0e54f148f.nq.gz
    ├── 4c3fa2af11248cf0d160eb64f4950bc4280e04ef.nq.gz
    ├── 4d4586b472a48c35ded9cab67a8c694a837bdef8.nq.gz
    ├── 4d63845355991fc439eb6003e634c6303abda5ed.nq.gz
    ├── 4e6b84edfb58b9776c029f46ae7a6cd7965bb9a7.nq.gz
    ├── 4ec3f24ce3d1c2d9f7da3273eb4b7b006dcd9b81.nq.gz
    ├── 50401671eb909bab1a35a3ee2aa6d341d790933d.nq.gz
    ├── 5050078ff851957acb30253390cf8f2d0fa5c2c3.nq.gz
    ├── 5081455bde9c4bf7f2b3acf2bd04a9289dc51f5f.nq.gz
    ├── 50cdd68c996347124a54bc4e0c6b149fa8c2c92c.nq.gz
    ├── 520d9fd82ca31c3c8d9002fbb2fbed978d6c7ad8.nq.gz
    ├── 52219b940e89891f62182a077f202d5e024f6695.nq.gz
    ├── 523b163001a6719187cf1f9edb6c0b0ba6a89145.nq.gz
    ├── 53187fd2f80ee576cdec5103fdb04b885b23199c.nq.gz
    ├── 531f16a2fa70f7c37aa7a22fb4b0008d88619c72.nq.gz
    ├── 5352aaecf3327a897c5183ab44fc116a399df5b9.nq.gz
    ├── 547b9d291645187cdf7d640cbb0145a2ccce6251.nq.gz
    ├── 54b299a6f8e4e4ed0641824b54161d2e367f63a5.nq.gz
    ├── 552b305fc0039a052f11c3d94d3881424c943ed6.nq.gz
    ├── 55e2107b0499544646ddc0caad0069100d2ba175.nq.gz
    ├── 55e2dab0d68e6d07c773325a6139fdf4de6ae70e.nq.gz
    ├── 55e84a2372458d86fb21b0e1ebaf65dc7c2951ac.nq.gz
    ├── 5684651fbb85639fb1a6f9e17172521434f4c7d4.nq.gz
    ├── 574955398a087cbb37bfa99b4dc7b000d742ffb4.nq.gz
    ├── 5765fdfb49a62a3ae5c79dcf6f84e2f919e0dacb.nq.gz
    ├── 58d8a13d91f7320db6a9e59595bd9597e7850682.nq.gz
    ├── 5a184a9daf70082c42570a8e73ea56c3b7287807.nq.gz
    ├── 5b3aa04ab2bcf5d9ff69db1a03d8ffcb0ddc29f2.nq.gz
    ├── 5baa13443fb61135025633b1cec295b2dea51369.nq.gz
    ├── 5c7fb7d6df1625ae390798af4d1e9291743306a7.nq.gz
    ├── 5c9e7e6ac84956bd7a4ea88720a9af8dcb024425.nq.gz
    ├── 5dab623a9a9cffefdfa70641dd706b139b8c956c.nq.gz
    ├── 5daec58c10e1ccab0a9fe56b5cff9504a0a38943.nq.gz
    ├── 5de7cc6cbff35e252962f0c8386ce246d253bad6.nq.gz
    ├── 5e0bb9f6bdf88ba47add81ba5f1a0f1c37417994.nq.gz
    ├── 5e30f2d2c0922e11bee424233d593525fb9f6d2b.nq.gz
    ├── 5e9f5e9e7ff6ac8f03ad1b4df70a1afd65f60353.nq.gz
    ├── 5eedeea7079f74b5abfcb43def1f9a2ea63b3c93.nq.gz
    ├── 5f02d7e9782563d4295d6448c5cec87f18b5805a.nq.gz
    ├── 5f2b727bf5a2f1485fecc7a2083058814bebde8f.nq.gz
    ├── 5f86022af9b631ee556e59a05d75ac9073ca36f3.nq.gz
    ├── 5fbc76676a57a59c6f48d55ceb8030c6bd0dccba.nq.gz
    └── 60bdeead6337af4c13d36621c00f1caa9a196945.nq.gz

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

[certbot/certbot](https://github.com/certbot/certbot)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
