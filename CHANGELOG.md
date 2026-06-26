# Changelog

## [0.0.1](https://github.com/alpha819beta/private-gpt/compare/v0.0.1...v0.0.1) (2026-06-26)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/alpha819beta/private-gpt/issues/1426)) ([468b925](https://github.com/alpha819beta/private-gpt/commit/468b925dab3befda1e7a0c7d9cca02b84e3b77ae))
* add retry connection to ollama ([#2084](https://github.com/alpha819beta/private-gpt/issues/2084)) ([1d4431a](https://github.com/alpha819beta/private-gpt/commit/1d4431a9e48cd2cac553e94aab7c386356269c68))
* Add stream information to generate SDKs ([#1569](https://github.com/alpha819beta/private-gpt/issues/1569)) ([6f4faa8](https://github.com/alpha819beta/private-gpt/commit/6f4faa8ec6dde0f3f5ee3113797350501a4337b7))
* Adding MistralAI mode ([#2065](https://github.com/alpha819beta/private-gpt/issues/2065)) ([99f61b8](https://github.com/alpha819beta/private-gpt/commit/99f61b84d865de2118b270441a4ec4d2fb05d4e8))
* **API:** Ingest plain text ([#1417](https://github.com/alpha819beta/private-gpt/issues/1417)) ([9f9a898](https://github.com/alpha819beta/private-gpt/commit/9f9a898dde65b516f4ba36d0c70fd5de1476fbea))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/alpha819beta/private-gpt/issues/1432)) ([152350a](https://github.com/alpha819beta/private-gpt/commit/152350a41e28e37c0d3a4b0f9a6f9d530ec7b811))
* bump dependencies ([#1987](https://github.com/alpha819beta/private-gpt/issues/1987)) ([6872de4](https://github.com/alpha819beta/private-gpt/commit/6872de40152933d8ef28ec172ee7e744fac36037))
* **code:** improve concat of strings in ui ([#1785](https://github.com/alpha819beta/private-gpt/issues/1785)) ([d661543](https://github.com/alpha819beta/private-gpt/commit/d6615434990fa10a8667d9d60a8e1dfffc5f53d3))
* Disable Gradio Analytics ([#1165](https://github.com/alpha819beta/private-gpt/issues/1165)) ([28ea56d](https://github.com/alpha819beta/private-gpt/commit/28ea56d5ab48faa4d36e6ad624d45a694050c39b))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/alpha819beta/private-gpt/issues/1812)) ([1cb5270](https://github.com/alpha819beta/private-gpt/commit/1cb5270fdad7e920dc1ca3bf4979eaeb8a7e098d))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/alpha819beta/private-gpt/issues/1782)) ([357f3d7](https://github.com/alpha819beta/private-gpt/commit/357f3d704af6275ff8669566ecb659c6a3b8d8ac))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/alpha819beta/private-gpt/issues/1924)) ([121d0ac](https://github.com/alpha819beta/private-gpt/commit/121d0ac29a2b8a616d6900fee9f9d16389aef243))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/alpha819beta/private-gpt/issues/1741)) ([3d83421](https://github.com/alpha819beta/private-gpt/commit/3d83421201e1580da7b401e0c7e9a2629a5b925a))
* **docs:** Fix setup docu ([#1926](https://github.com/alpha819beta/private-gpt/issues/1926)) ([1af96eb](https://github.com/alpha819beta/private-gpt/commit/1af96eb46bd958501c5781d560e49bdc0a32c7a4))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/alpha819beta/private-gpt/issues/1968)) ([5955bc7](https://github.com/alpha819beta/private-gpt/commit/5955bc7a556887214e29f5fc39db181883dcbed3))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/alpha819beta/private-gpt/issues/2000)) ([71db9be](https://github.com/alpha819beta/private-gpt/commit/71db9be1ef7e02902c7d9514d77643d2fe174ccd))
* **docs:** upgrade fern ([#1596](https://github.com/alpha819beta/private-gpt/issues/1596)) ([e78a294](https://github.com/alpha819beta/private-gpt/commit/e78a294626bc1467353014a1990376e2e31b8514))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/alpha819beta/private-gpt/issues/1133)) ([f9876c4](https://github.com/alpha819beta/private-gpt/commit/f9876c471be4a9dcd09f396859aaa8f4a8d48882))
* enable resume download for hf_hub_download ([#1249](https://github.com/alpha819beta/private-gpt/issues/1249)) ([f68e2ba](https://github.com/alpha819beta/private-gpt/commit/f68e2baf0b0326d8e9ede1d8d1946e8fb7eb6372))
* Get answers using preferred number of chunks ([06064ff](https://github.com/alpha819beta/private-gpt/commit/06064ff0d35222b3df9dc7aa237ced4c8c5c0603))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/alpha819beta/private-gpt/issues/1750)) ([2e5cf42](https://github.com/alpha819beta/private-gpt/commit/2e5cf425ab27b508ab34ad9250ef133613ce3307))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/alpha819beta/private-gpt/issues/1698)) ([8a262de](https://github.com/alpha819beta/private-gpt/commit/8a262deccf9c2bd39752bb9e123649445e69bdf5))
* **llm:** Add openailike llm mode ([#1447](https://github.com/alpha819beta/private-gpt/issues/1447)) ([f930aa0](https://github.com/alpha819beta/private-gpt/commit/f930aa02a2fdd2cf86715f0b153640a1edb2af25)), closes [#1424](https://github.com/alpha819beta/private-gpt/issues/1424)
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/alpha819beta/private-gpt/issues/2031)) ([6d4aa08](https://github.com/alpha819beta/private-gpt/commit/6d4aa08ece4f1d95a94e521e0ec94fd6fcfbac06))
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/alpha819beta/private-gpt/issues/1526)) ([83e6006](https://github.com/alpha819beta/private-gpt/commit/83e6006e9aa33aefb7a09c43c1dde0cbd248fc2c))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/alpha819beta/private-gpt/issues/1703)) ([a5881d2](https://github.com/alpha819beta/private-gpt/commit/a5881d2b411638aee398b2a4ce1d0e44d10c9264))
* **llm:** autopull ollama models ([#2019](https://github.com/alpha819beta/private-gpt/issues/2019)) ([6967f06](https://github.com/alpha819beta/private-gpt/commit/6967f06bc76b2384c417ac5a95396ddbfdfcab6f))
* **llm:** drop default_system_prompt ([#1385](https://github.com/alpha819beta/private-gpt/issues/1385)) ([3679639](https://github.com/alpha819beta/private-gpt/commit/3679639130c39f7477ea41371ceccfcff5872681))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/alpha819beta/private-gpt/issues/1800)) ([dbbc2df](https://github.com/alpha819beta/private-gpt/commit/dbbc2dfe62ec449451459a069db2d874fb60b19e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/alpha819beta/private-gpt/issues/1773)) ([b55f096](https://github.com/alpha819beta/private-gpt/commit/b55f0962b6ab584b8c6c3f69b743d6d5e014bd01))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/alpha819beta/private-gpt/issues/1965)) ([f999e5a](https://github.com/alpha819beta/private-gpt/commit/f999e5af504ec84c3c20b78eee7a6856045d720e))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/alpha819beta/private-gpt/issues/1467)) ([f0412a7](https://github.com/alpha819beta/private-gpt/commit/f0412a78a9979cbf66704417f41393384e733d64))
* make llama3.1 as default ([#2022](https://github.com/alpha819beta/private-gpt/issues/2022)) ([e072d2c](https://github.com/alpha819beta/private-gpt/commit/e072d2c4447dfcceadaf4236496711d789794010))
* move torch and transformers to local group ([#1172](https://github.com/alpha819beta/private-gpt/issues/1172)) ([c17b58b](https://github.com/alpha819beta/private-gpt/commit/c17b58bb4edf0e7c77736bdf887fecdb9b9c7ca2))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/alpha819beta/private-gpt/issues/1706)) ([30ddcbd](https://github.com/alpha819beta/private-gpt/commit/30ddcbd3fe98e33aa69a9d14476b539127930f50))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/alpha819beta/private-gpt/issues/1835)) ([1f84b18](https://github.com/alpha819beta/private-gpt/commit/1f84b18bde25d3fa41bcc91dea501536a50712bd))
* Qdrant support ([#1228](https://github.com/alpha819beta/private-gpt/issues/1228)) ([48f91b0](https://github.com/alpha819beta/private-gpt/commit/48f91b0558a57725232647f692b645c746e7d6d9))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/alpha819beta/private-gpt/issues/1771)) ([6ffe724](https://github.com/alpha819beta/private-gpt/commit/6ffe724c31e59f68393a69270ae6cee0856e1970))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/alpha819beta/private-gpt/issues/1810)) ([3180508](https://github.com/alpha819beta/private-gpt/commit/3180508fac562c4e2f28b2754f620e7c91efc70a))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/alpha819beta/private-gpt/issues/2028)) ([71a5795](https://github.com/alpha819beta/private-gpt/commit/71a5795ac03ac08e1691c7f69e8b5c8bf2596e13))
* Release GitHub action ([#1078](https://github.com/alpha819beta/private-gpt/issues/1078)) ([56dd6b6](https://github.com/alpha819beta/private-gpt/commit/56dd6b6416b75488eb1a35bfe64ec9ea8e582147))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/alpha819beta/private-gpt/issues/1783)) ([fb81000](https://github.com/alpha819beta/private-gpt/commit/fb81000c96ff2413f96fdef2c71571e985d2a1f4))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/alpha819beta/private-gpt/issues/1437)) ([5e375f1](https://github.com/alpha819beta/private-gpt/commit/5e375f1b8eb8d323e286e9ad8eb500d7dfd9fbf3))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/alpha819beta/private-gpt/issues/1415)) ([66eccf5](https://github.com/alpha819beta/private-gpt/commit/66eccf5334f6c101c524c8206555739837e1b605))
* **ui:** add LLM mode to UI ([#1080](https://github.com/alpha819beta/private-gpt/issues/1080)) ([4ad03f6](https://github.com/alpha819beta/private-gpt/commit/4ad03f6c269219026984e26a852f020f8a156d74))
* **ui:** Add Model Information to ChatInterface label ([5782031](https://github.com/alpha819beta/private-gpt/commit/57820315577e50f40be07288803e27fcb23f51b0))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/alpha819beta/private-gpt/issues/1705)) ([1962d48](https://github.com/alpha819beta/private-gpt/commit/1962d48393a728867abbde751b30aed428869410))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/alpha819beta/private-gpt/issues/1353)) ([b782f20](https://github.com/alpha819beta/private-gpt/commit/b782f202c60b9b1bc656ee68512219396ce45a25))
* **UI:** Faster startup and document listing ([#1763](https://github.com/alpha819beta/private-gpt/issues/1763)) ([22a57e1](https://github.com/alpha819beta/private-gpt/commit/22a57e15f966c589ffc43203a290239c8278dbac))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/alpha819beta/private-gpt/issues/1643)) ([d8bc0ec](https://github.com/alpha819beta/private-gpt/commit/d8bc0ec925dc8281be8c98ff34644656e0a9be0a))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/alpha819beta/private-gpt/issues/1397)) ([d101e43](https://github.com/alpha819beta/private-gpt/commit/d101e43cee597b37948a4445da96aa5f60c2ab25))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/alpha819beta/private-gpt/issues/1612)) ([4e65c5f](https://github.com/alpha819beta/private-gpt/commit/4e65c5f3d8d32296d4bf602a7eace3295ad04729))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/alpha819beta/private-gpt/issues/1730)) ([cdf12de](https://github.com/alpha819beta/private-gpt/commit/cdf12de98146ee8e817c191d95c282b75361e423))
* update llama-index + dependencies ([#2092](https://github.com/alpha819beta/private-gpt/issues/2092)) ([93ce903](https://github.com/alpha819beta/private-gpt/commit/93ce903b3e3ec4b121d834698ac686e2295f75eb))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/alpha819beta/private-gpt/issues/1663)) ([0e5176e](https://github.com/alpha819beta/private-gpt/commit/0e5176e1f995be1ecc29237ba4da635c40985aa9))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/alpha819beta/private-gpt/issues/1996)) ([d58cee5](https://github.com/alpha819beta/private-gpt/commit/d58cee5981baa84684e8a9018a63d4a404f1ebfb))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/alpha819beta/private-gpt/issues/1883)) ([a22a548](https://github.com/alpha819beta/private-gpt/commit/a22a548e979cd6c20025ca66c3e5dd7252b32de4))
* **Vector:** support pgvector ([#1624](https://github.com/alpha819beta/private-gpt/issues/1624)) ([dc2cdad](https://github.com/alpha819beta/private-gpt/commit/dc2cdad3b0b22ff8529ec03b352cea278146a792))
* wipe per storage type ([#1772](https://github.com/alpha819beta/private-gpt/issues/1772)) ([59a85b4](https://github.com/alpha819beta/private-gpt/commit/59a85b42ac4b5b7746c3c6d53f7cf963d9733bca))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/alpha819beta/private-gpt/issues/1841)) ([cee95ce](https://github.com/alpha819beta/private-gpt/commit/cee95ce22df24713e9d0ecedb520ebbbbaceebc0))
* 294 (tested) ([fa06742](https://github.com/alpha819beta/private-gpt/commit/fa06742362fae04eec059a5c8f50ef7f84137275))
* 503 when private gpt gets ollama service ([#2104](https://github.com/alpha819beta/private-gpt/issues/2104)) ([baa783a](https://github.com/alpha819beta/private-gpt/commit/baa783a727ea07e0143a544f33dbc5c231298fba))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([d7abd6e](https://github.com/alpha819beta/private-gpt/commit/d7abd6e6df5561027bb686a8697b328083ced54c))
* add built image from DockerHub ([#2042](https://github.com/alpha819beta/private-gpt/issues/2042)) ([7eb0800](https://github.com/alpha819beta/private-gpt/commit/7eb08008fe8283c1e436d44ad1aaeae6735d088f))
* Add default mode option to settings ([#2078](https://github.com/alpha819beta/private-gpt/issues/2078)) ([ecef64b](https://github.com/alpha819beta/private-gpt/commit/ecef64b3275d048c5ecddb05742548ffa15d2566))
* add numpy issue to troubleshooting ([#2048](https://github.com/alpha819beta/private-gpt/issues/2048)) ([58df4da](https://github.com/alpha819beta/private-gpt/commit/58df4dae8abc6365f7394cae9d78d028ea22246f))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/alpha819beta/private-gpt/issues/1519)) ([c43d76c](https://github.com/alpha819beta/private-gpt/commit/c43d76caacf8e4afcadeb0194c5fa9ebd5e44aa4))
* Adding azopenai to model list ([#2035](https://github.com/alpha819beta/private-gpt/issues/2035)) ([98c864d](https://github.com/alpha819beta/private-gpt/commit/98c864dc41a12c794dd5e9136d54abd8b8b3d6aa))
* auto-update version ([#2052](https://github.com/alpha819beta/private-gpt/issues/2052)) ([bcff823](https://github.com/alpha819beta/private-gpt/commit/bcff823f686d06504bfb3256e0beb34e59ead65b))
* chromadb max batch size ([#1087](https://github.com/alpha819beta/private-gpt/issues/1087)) ([fbb1f03](https://github.com/alpha819beta/private-gpt/commit/fbb1f03965aee471a665d76b5eab2df203554ed2))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/alpha819beta/private-gpt/issues/1998)) ([1ffb584](https://github.com/alpha819beta/private-gpt/commit/1ffb5848940741656ba83f4369aecbdb10157cf8))
* **deploy:** fix local and external dockerfiles ([194599d](https://github.com/alpha819beta/private-gpt/commit/194599d6543f20c9fd9edb47f90937ea88c1b0cc))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/alpha819beta/private-gpt/issues/2038)) ([9d73049](https://github.com/alpha819beta/private-gpt/commit/9d73049bb1cbec0a405cb83136a9556b1e98a7cb))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/alpha819beta/private-gpt/issues/2037)) ([c174627](https://github.com/alpha819beta/private-gpt/commit/c17462701f00af97f3d9cdee00fccc5d6c2fb486))
* Disable Chroma Telemetry ([44b4704](https://github.com/alpha819beta/private-gpt/commit/44b4704979de9241d747c15c69402199fb96e526))
* Docker and sagemaker setup ([#1118](https://github.com/alpha819beta/private-gpt/issues/1118)) ([53a2f45](https://github.com/alpha819beta/private-gpt/commit/53a2f455d063d46819dce1ff3bc8ea4cf000e016))
* docker permissions ([#2059](https://github.com/alpha819beta/private-gpt/issues/2059)) ([1390fdd](https://github.com/alpha819beta/private-gpt/commit/1390fdd45050a4c459793d7c2edad6f56d983ca7))
* **docker:** docker broken copy ([#1419](https://github.com/alpha819beta/private-gpt/issues/1419)) ([7841f6c](https://github.com/alpha819beta/private-gpt/commit/7841f6c3c56412552c296d286343b1db16af958d))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/alpha819beta/private-gpt/issues/1779)) ([5e75a88](https://github.com/alpha819beta/private-gpt/commit/5e75a88962a1867af2b38737d689fc0bac1163e3))
* **docs:** Minor documentation amendment ([#1739](https://github.com/alpha819beta/private-gpt/issues/1739)) ([1d8fc07](https://github.com/alpha819beta/private-gpt/commit/1d8fc078d72766811d9ae39e42bacd40a06cbeba))
* **docs:** Update installation.mdx ([#1866](https://github.com/alpha819beta/private-gpt/issues/1866)) ([d033b9a](https://github.com/alpha819beta/private-gpt/commit/d033b9af26556f2dc2ba1a9b1459bb04b099caa4))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([4e62902](https://github.com/alpha819beta/private-gpt/commit/4e629025990431581115fb1fcfecce70cdb5c8b6))
* ffmpy dependency ([#2020](https://github.com/alpha819beta/private-gpt/issues/2020)) ([bee3207](https://github.com/alpha819beta/private-gpt/commit/bee320710bd10b83ab81633f731a1400821dac27))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/alpha819beta/private-gpt/issues/1123)) ([4dd5bce](https://github.com/alpha819beta/private-gpt/commit/4dd5bce63a4a758b0776a653e81f497d10806815))
* Fixed docker-compose ([#1758](https://github.com/alpha819beta/private-gpt/issues/1758)) ([50b647a](https://github.com/alpha819beta/private-gpt/commit/50b647a37a8879667ee92fa988b5478a16afd614))
* **ingest:** update script label ([#1770](https://github.com/alpha819beta/private-gpt/issues/1770)) ([82fef1d](https://github.com/alpha819beta/private-gpt/commit/82fef1d67432694faece327864528a1663b0089e))
* light mode ([#2025](https://github.com/alpha819beta/private-gpt/issues/2025)) ([1f60573](https://github.com/alpha819beta/private-gpt/commit/1f60573a14a2ebb6e417109aa8c2e072dbd5e567))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/alpha819beta/private-gpt/issues/1954)) ([4715803](https://github.com/alpha819beta/private-gpt/commit/47158032d67fb4b9fc37f57206f0ef08036e7822))
* **llm:** special tokens and leading space ([#1831](https://github.com/alpha819beta/private-gpt/issues/1831)) ([c9c822a](https://github.com/alpha819beta/private-gpt/commit/c9c822a7c071270b806433299a69dfb364372f10))
* make docs more visible ([#1081](https://github.com/alpha819beta/private-gpt/issues/1081)) ([59652ae](https://github.com/alpha819beta/private-gpt/commit/59652ae0e3d6cb6664bd008b4a94f8c6e1db61b6))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/alpha819beta/private-gpt/issues/1859)) ([e77372a](https://github.com/alpha819beta/private-gpt/commit/e77372a9094fd9fcd50cbb8322f95107af0725e5))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/alpha819beta/private-gpt/issues/1449)) ([8a5d9ed](https://github.com/alpha819beta/private-gpt/commit/8a5d9ed2a28fe378a3ec7ede811503c9da1dc118))
* naming image and ollama-cpu ([#2056](https://github.com/alpha819beta/private-gpt/issues/2056)) ([2eeaf09](https://github.com/alpha819beta/private-gpt/commit/2eeaf094c978d273ad38394602196d1f52aff311))
* nomic embeddings ([#2030](https://github.com/alpha819beta/private-gpt/issues/2030)) ([e47225b](https://github.com/alpha819beta/private-gpt/commit/e47225be57a4e0ec556b662919cc46aea5e760b5))
* prevent to ingest local files (by default) ([#2010](https://github.com/alpha819beta/private-gpt/issues/2010)) ([ea1d16d](https://github.com/alpha819beta/private-gpt/commit/ea1d16db277b114ee6b64dfcc6a55d724e169f46))
* publish image name ([#2043](https://github.com/alpha819beta/private-gpt/issues/2043)) ([c6301d2](https://github.com/alpha819beta/private-gpt/commit/c6301d2b58476b8f00f574f51a75315df262664f))
* Rectify ffmpy poetry config; update version from 0.3.2 to 0.4.0 ([#2062](https://github.com/alpha819beta/private-gpt/issues/2062)) ([521d7fd](https://github.com/alpha819beta/private-gpt/commit/521d7fd5760edf2c976710afb639e05beb63b358))
* Remove global state ([#1216](https://github.com/alpha819beta/private-gpt/issues/1216)) ([cee3c07](https://github.com/alpha819beta/private-gpt/commit/cee3c07a38978acf7341a9520a057aafd16968b4))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/alpha819beta/private-gpt/issues/1890)) ([1ff8e35](https://github.com/alpha819beta/private-gpt/commit/1ff8e35b94d2d3239d4e2969909cf44303131b59))
* sagemaker config and chat methods ([#1142](https://github.com/alpha819beta/private-gpt/issues/1142)) ([20ec0a1](https://github.com/alpha819beta/private-gpt/commit/20ec0a1fc98e5ba5e11a37d362f4bed08e0ea955))
* Sanitize null bytes before ingestion ([#2090](https://github.com/alpha819beta/private-gpt/issues/2090)) ([a0f80bb](https://github.com/alpha819beta/private-gpt/commit/a0f80bb573932d91bf14353a1350132e51a7f7b8))
* **settings:** correct yaml multiline string ([#1403](https://github.com/alpha819beta/private-gpt/issues/1403)) ([89a149f](https://github.com/alpha819beta/private-gpt/commit/89a149f2e00f23aede8fdf99e8d1755a3ec61175))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/alpha819beta/private-gpt/issues/1925)) ([0c9f9ae](https://github.com/alpha819beta/private-gpt/commit/0c9f9ae968f2bfc1f5ddd4c3c97b9eaf31740d6a))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/alpha819beta/private-gpt/issues/1709)) ([0746180](https://github.com/alpha819beta/private-gpt/commit/0746180358f051e22ecd496d049e4abadfd53f18))
* **tests:** load the test settings only when running tests ([65c4d75](https://github.com/alpha819beta/private-gpt/commit/65c4d7529a315c0b4e07cd19a28abdc4d1bc83d6))
* typo in README.md ([#1091](https://github.com/alpha819beta/private-gpt/issues/1091)) ([9ec96b3](https://github.com/alpha819beta/private-gpt/commit/9ec96b3a13fa403366eb03f2a338fea01734cfb1))
* **ui:** gradio bug fixes ([#2021](https://github.com/alpha819beta/private-gpt/issues/2021)) ([5504936](https://github.com/alpha819beta/private-gpt/commit/5504936696ca0305133be489e97d2b131f6e461d))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([d00de30](https://github.com/alpha819beta/private-gpt/commit/d00de30d4c67e216066c36d0f155514a12f86a74))
* unify embedding models ([#2027](https://github.com/alpha819beta/private-gpt/issues/2027)) ([552f1ad](https://github.com/alpha819beta/private-gpt/commit/552f1ad5646899368314b49da7768fd0d33bbd19))
* update matplotlib to 3.9.1-post1 to fix win install ([7820517](https://github.com/alpha819beta/private-gpt/commit/78205170bcbab49813b37a0606c83efce4030016))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/alpha819beta/private-gpt/issues/1260)) ([11e4878](https://github.com/alpha819beta/private-gpt/commit/11e4878d9e441a0b175a7781d8ed8eea7392f9e3))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/alpha819beta/private-gpt/issues/1280)) ([4226183](https://github.com/alpha819beta/private-gpt/commit/4226183ec4e912a0db27fe4f399d6c026c8457e8))


### Miscellaneous Chores

* Initial version ([7d4b6a7](https://github.com/alpha819beta/private-gpt/commit/7d4b6a70bf481b634aa2b5a5d5914af87c243af8))

## [0.0.1](https://github.com/alpha819beta/private-gpt/compare/v0.6.2...v0.0.1) (2026-05-13)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/alpha819beta/private-gpt/issues/1426)) ([468b925](https://github.com/alpha819beta/private-gpt/commit/468b925dab3befda1e7a0c7d9cca02b84e3b77ae))
* add retry connection to ollama ([#2084](https://github.com/alpha819beta/private-gpt/issues/2084)) ([1d4431a](https://github.com/alpha819beta/private-gpt/commit/1d4431a9e48cd2cac553e94aab7c386356269c68))
* Add stream information to generate SDKs ([#1569](https://github.com/alpha819beta/private-gpt/issues/1569)) ([6f4faa8](https://github.com/alpha819beta/private-gpt/commit/6f4faa8ec6dde0f3f5ee3113797350501a4337b7))
* Adding MistralAI mode ([#2065](https://github.com/alpha819beta/private-gpt/issues/2065)) ([99f61b8](https://github.com/alpha819beta/private-gpt/commit/99f61b84d865de2118b270441a4ec4d2fb05d4e8))
* **API:** Ingest plain text ([#1417](https://github.com/alpha819beta/private-gpt/issues/1417)) ([9f9a898](https://github.com/alpha819beta/private-gpt/commit/9f9a898dde65b516f4ba36d0c70fd5de1476fbea))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/alpha819beta/private-gpt/issues/1432)) ([152350a](https://github.com/alpha819beta/private-gpt/commit/152350a41e28e37c0d3a4b0f9a6f9d530ec7b811))
* bump dependencies ([#1987](https://github.com/alpha819beta/private-gpt/issues/1987)) ([6872de4](https://github.com/alpha819beta/private-gpt/commit/6872de40152933d8ef28ec172ee7e744fac36037))
* **code:** improve concat of strings in ui ([#1785](https://github.com/alpha819beta/private-gpt/issues/1785)) ([d661543](https://github.com/alpha819beta/private-gpt/commit/d6615434990fa10a8667d9d60a8e1dfffc5f53d3))
* Disable Gradio Analytics ([#1165](https://github.com/alpha819beta/private-gpt/issues/1165)) ([28ea56d](https://github.com/alpha819beta/private-gpt/commit/28ea56d5ab48faa4d36e6ad624d45a694050c39b))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/alpha819beta/private-gpt/issues/1812)) ([1cb5270](https://github.com/alpha819beta/private-gpt/commit/1cb5270fdad7e920dc1ca3bf4979eaeb8a7e098d))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/alpha819beta/private-gpt/issues/1782)) ([357f3d7](https://github.com/alpha819beta/private-gpt/commit/357f3d704af6275ff8669566ecb659c6a3b8d8ac))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/alpha819beta/private-gpt/issues/1924)) ([121d0ac](https://github.com/alpha819beta/private-gpt/commit/121d0ac29a2b8a616d6900fee9f9d16389aef243))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/alpha819beta/private-gpt/issues/1741)) ([3d83421](https://github.com/alpha819beta/private-gpt/commit/3d83421201e1580da7b401e0c7e9a2629a5b925a))
* **docs:** Fix setup docu ([#1926](https://github.com/alpha819beta/private-gpt/issues/1926)) ([1af96eb](https://github.com/alpha819beta/private-gpt/commit/1af96eb46bd958501c5781d560e49bdc0a32c7a4))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/alpha819beta/private-gpt/issues/1968)) ([5955bc7](https://github.com/alpha819beta/private-gpt/commit/5955bc7a556887214e29f5fc39db181883dcbed3))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/alpha819beta/private-gpt/issues/2000)) ([71db9be](https://github.com/alpha819beta/private-gpt/commit/71db9be1ef7e02902c7d9514d77643d2fe174ccd))
* **docs:** upgrade fern ([#1596](https://github.com/alpha819beta/private-gpt/issues/1596)) ([e78a294](https://github.com/alpha819beta/private-gpt/commit/e78a294626bc1467353014a1990376e2e31b8514))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/alpha819beta/private-gpt/issues/1133)) ([f9876c4](https://github.com/alpha819beta/private-gpt/commit/f9876c471be4a9dcd09f396859aaa8f4a8d48882))
* enable resume download for hf_hub_download ([#1249](https://github.com/alpha819beta/private-gpt/issues/1249)) ([f68e2ba](https://github.com/alpha819beta/private-gpt/commit/f68e2baf0b0326d8e9ede1d8d1946e8fb7eb6372))
* Get answers using preferred number of chunks ([06064ff](https://github.com/alpha819beta/private-gpt/commit/06064ff0d35222b3df9dc7aa237ced4c8c5c0603))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/alpha819beta/private-gpt/issues/1750)) ([2e5cf42](https://github.com/alpha819beta/private-gpt/commit/2e5cf425ab27b508ab34ad9250ef133613ce3307))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/alpha819beta/private-gpt/issues/1698)) ([8a262de](https://github.com/alpha819beta/private-gpt/commit/8a262deccf9c2bd39752bb9e123649445e69bdf5))
* **llm:** Add openailike llm mode ([#1447](https://github.com/alpha819beta/private-gpt/issues/1447)) ([f930aa0](https://github.com/alpha819beta/private-gpt/commit/f930aa02a2fdd2cf86715f0b153640a1edb2af25)), closes [#1424](https://github.com/alpha819beta/private-gpt/issues/1424)
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/alpha819beta/private-gpt/issues/2031)) ([6d4aa08](https://github.com/alpha819beta/private-gpt/commit/6d4aa08ece4f1d95a94e521e0ec94fd6fcfbac06))
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/alpha819beta/private-gpt/issues/1526)) ([83e6006](https://github.com/alpha819beta/private-gpt/commit/83e6006e9aa33aefb7a09c43c1dde0cbd248fc2c))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/alpha819beta/private-gpt/issues/1703)) ([a5881d2](https://github.com/alpha819beta/private-gpt/commit/a5881d2b411638aee398b2a4ce1d0e44d10c9264))
* **llm:** autopull ollama models ([#2019](https://github.com/alpha819beta/private-gpt/issues/2019)) ([6967f06](https://github.com/alpha819beta/private-gpt/commit/6967f06bc76b2384c417ac5a95396ddbfdfcab6f))
* **llm:** drop default_system_prompt ([#1385](https://github.com/alpha819beta/private-gpt/issues/1385)) ([3679639](https://github.com/alpha819beta/private-gpt/commit/3679639130c39f7477ea41371ceccfcff5872681))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/alpha819beta/private-gpt/issues/1800)) ([dbbc2df](https://github.com/alpha819beta/private-gpt/commit/dbbc2dfe62ec449451459a069db2d874fb60b19e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/alpha819beta/private-gpt/issues/1773)) ([b55f096](https://github.com/alpha819beta/private-gpt/commit/b55f0962b6ab584b8c6c3f69b743d6d5e014bd01))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/alpha819beta/private-gpt/issues/1965)) ([f999e5a](https://github.com/alpha819beta/private-gpt/commit/f999e5af504ec84c3c20b78eee7a6856045d720e))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/alpha819beta/private-gpt/issues/1467)) ([f0412a7](https://github.com/alpha819beta/private-gpt/commit/f0412a78a9979cbf66704417f41393384e733d64))
* make llama3.1 as default ([#2022](https://github.com/alpha819beta/private-gpt/issues/2022)) ([e072d2c](https://github.com/alpha819beta/private-gpt/commit/e072d2c4447dfcceadaf4236496711d789794010))
* move torch and transformers to local group ([#1172](https://github.com/alpha819beta/private-gpt/issues/1172)) ([c17b58b](https://github.com/alpha819beta/private-gpt/commit/c17b58bb4edf0e7c77736bdf887fecdb9b9c7ca2))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/alpha819beta/private-gpt/issues/1706)) ([30ddcbd](https://github.com/alpha819beta/private-gpt/commit/30ddcbd3fe98e33aa69a9d14476b539127930f50))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/alpha819beta/private-gpt/issues/1835)) ([1f84b18](https://github.com/alpha819beta/private-gpt/commit/1f84b18bde25d3fa41bcc91dea501536a50712bd))
* Qdrant support ([#1228](https://github.com/alpha819beta/private-gpt/issues/1228)) ([48f91b0](https://github.com/alpha819beta/private-gpt/commit/48f91b0558a57725232647f692b645c746e7d6d9))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/alpha819beta/private-gpt/issues/1771)) ([6ffe724](https://github.com/alpha819beta/private-gpt/commit/6ffe724c31e59f68393a69270ae6cee0856e1970))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/alpha819beta/private-gpt/issues/1810)) ([3180508](https://github.com/alpha819beta/private-gpt/commit/3180508fac562c4e2f28b2754f620e7c91efc70a))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/alpha819beta/private-gpt/issues/2028)) ([71a5795](https://github.com/alpha819beta/private-gpt/commit/71a5795ac03ac08e1691c7f69e8b5c8bf2596e13))
* Release GitHub action ([#1078](https://github.com/alpha819beta/private-gpt/issues/1078)) ([56dd6b6](https://github.com/alpha819beta/private-gpt/commit/56dd6b6416b75488eb1a35bfe64ec9ea8e582147))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/alpha819beta/private-gpt/issues/1783)) ([fb81000](https://github.com/alpha819beta/private-gpt/commit/fb81000c96ff2413f96fdef2c71571e985d2a1f4))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/alpha819beta/private-gpt/issues/1437)) ([5e375f1](https://github.com/alpha819beta/private-gpt/commit/5e375f1b8eb8d323e286e9ad8eb500d7dfd9fbf3))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/alpha819beta/private-gpt/issues/1415)) ([66eccf5](https://github.com/alpha819beta/private-gpt/commit/66eccf5334f6c101c524c8206555739837e1b605))
* **ui:** add LLM mode to UI ([#1080](https://github.com/alpha819beta/private-gpt/issues/1080)) ([4ad03f6](https://github.com/alpha819beta/private-gpt/commit/4ad03f6c269219026984e26a852f020f8a156d74))
* **ui:** Add Model Information to ChatInterface label ([5782031](https://github.com/alpha819beta/private-gpt/commit/57820315577e50f40be07288803e27fcb23f51b0))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/alpha819beta/private-gpt/issues/1705)) ([1962d48](https://github.com/alpha819beta/private-gpt/commit/1962d48393a728867abbde751b30aed428869410))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/alpha819beta/private-gpt/issues/1353)) ([b782f20](https://github.com/alpha819beta/private-gpt/commit/b782f202c60b9b1bc656ee68512219396ce45a25))
* **UI:** Faster startup and document listing ([#1763](https://github.com/alpha819beta/private-gpt/issues/1763)) ([22a57e1](https://github.com/alpha819beta/private-gpt/commit/22a57e15f966c589ffc43203a290239c8278dbac))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/alpha819beta/private-gpt/issues/1643)) ([d8bc0ec](https://github.com/alpha819beta/private-gpt/commit/d8bc0ec925dc8281be8c98ff34644656e0a9be0a))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/alpha819beta/private-gpt/issues/1397)) ([d101e43](https://github.com/alpha819beta/private-gpt/commit/d101e43cee597b37948a4445da96aa5f60c2ab25))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/alpha819beta/private-gpt/issues/1612)) ([4e65c5f](https://github.com/alpha819beta/private-gpt/commit/4e65c5f3d8d32296d4bf602a7eace3295ad04729))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/alpha819beta/private-gpt/issues/1730)) ([cdf12de](https://github.com/alpha819beta/private-gpt/commit/cdf12de98146ee8e817c191d95c282b75361e423))
* update llama-index + dependencies ([#2092](https://github.com/alpha819beta/private-gpt/issues/2092)) ([93ce903](https://github.com/alpha819beta/private-gpt/commit/93ce903b3e3ec4b121d834698ac686e2295f75eb))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/alpha819beta/private-gpt/issues/1663)) ([0e5176e](https://github.com/alpha819beta/private-gpt/commit/0e5176e1f995be1ecc29237ba4da635c40985aa9))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/alpha819beta/private-gpt/issues/1996)) ([d58cee5](https://github.com/alpha819beta/private-gpt/commit/d58cee5981baa84684e8a9018a63d4a404f1ebfb))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/alpha819beta/private-gpt/issues/1883)) ([a22a548](https://github.com/alpha819beta/private-gpt/commit/a22a548e979cd6c20025ca66c3e5dd7252b32de4))
* **Vector:** support pgvector ([#1624](https://github.com/alpha819beta/private-gpt/issues/1624)) ([dc2cdad](https://github.com/alpha819beta/private-gpt/commit/dc2cdad3b0b22ff8529ec03b352cea278146a792))
* wipe per storage type ([#1772](https://github.com/alpha819beta/private-gpt/issues/1772)) ([59a85b4](https://github.com/alpha819beta/private-gpt/commit/59a85b42ac4b5b7746c3c6d53f7cf963d9733bca))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/alpha819beta/private-gpt/issues/1841)) ([cee95ce](https://github.com/alpha819beta/private-gpt/commit/cee95ce22df24713e9d0ecedb520ebbbbaceebc0))
* 294 (tested) ([fa06742](https://github.com/alpha819beta/private-gpt/commit/fa06742362fae04eec059a5c8f50ef7f84137275))
* 503 when private gpt gets ollama service ([#2104](https://github.com/alpha819beta/private-gpt/issues/2104)) ([baa783a](https://github.com/alpha819beta/private-gpt/commit/baa783a727ea07e0143a544f33dbc5c231298fba))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([d7abd6e](https://github.com/alpha819beta/private-gpt/commit/d7abd6e6df5561027bb686a8697b328083ced54c))
* add built image from DockerHub ([#2042](https://github.com/alpha819beta/private-gpt/issues/2042)) ([7eb0800](https://github.com/alpha819beta/private-gpt/commit/7eb08008fe8283c1e436d44ad1aaeae6735d088f))
* Add default mode option to settings ([#2078](https://github.com/alpha819beta/private-gpt/issues/2078)) ([ecef64b](https://github.com/alpha819beta/private-gpt/commit/ecef64b3275d048c5ecddb05742548ffa15d2566))
* add numpy issue to troubleshooting ([#2048](https://github.com/alpha819beta/private-gpt/issues/2048)) ([58df4da](https://github.com/alpha819beta/private-gpt/commit/58df4dae8abc6365f7394cae9d78d028ea22246f))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/alpha819beta/private-gpt/issues/1519)) ([c43d76c](https://github.com/alpha819beta/private-gpt/commit/c43d76caacf8e4afcadeb0194c5fa9ebd5e44aa4))
* Adding azopenai to model list ([#2035](https://github.com/alpha819beta/private-gpt/issues/2035)) ([98c864d](https://github.com/alpha819beta/private-gpt/commit/98c864dc41a12c794dd5e9136d54abd8b8b3d6aa))
* auto-update version ([#2052](https://github.com/alpha819beta/private-gpt/issues/2052)) ([bcff823](https://github.com/alpha819beta/private-gpt/commit/bcff823f686d06504bfb3256e0beb34e59ead65b))
* chromadb max batch size ([#1087](https://github.com/alpha819beta/private-gpt/issues/1087)) ([fbb1f03](https://github.com/alpha819beta/private-gpt/commit/fbb1f03965aee471a665d76b5eab2df203554ed2))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/alpha819beta/private-gpt/issues/1998)) ([1ffb584](https://github.com/alpha819beta/private-gpt/commit/1ffb5848940741656ba83f4369aecbdb10157cf8))
* **deploy:** fix local and external dockerfiles ([194599d](https://github.com/alpha819beta/private-gpt/commit/194599d6543f20c9fd9edb47f90937ea88c1b0cc))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/alpha819beta/private-gpt/issues/2038)) ([9d73049](https://github.com/alpha819beta/private-gpt/commit/9d73049bb1cbec0a405cb83136a9556b1e98a7cb))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/alpha819beta/private-gpt/issues/2037)) ([c174627](https://github.com/alpha819beta/private-gpt/commit/c17462701f00af97f3d9cdee00fccc5d6c2fb486))
* Disable Chroma Telemetry ([44b4704](https://github.com/alpha819beta/private-gpt/commit/44b4704979de9241d747c15c69402199fb96e526))
* Docker and sagemaker setup ([#1118](https://github.com/alpha819beta/private-gpt/issues/1118)) ([53a2f45](https://github.com/alpha819beta/private-gpt/commit/53a2f455d063d46819dce1ff3bc8ea4cf000e016))
* docker permissions ([#2059](https://github.com/alpha819beta/private-gpt/issues/2059)) ([1390fdd](https://github.com/alpha819beta/private-gpt/commit/1390fdd45050a4c459793d7c2edad6f56d983ca7))
* **docker:** docker broken copy ([#1419](https://github.com/alpha819beta/private-gpt/issues/1419)) ([7841f6c](https://github.com/alpha819beta/private-gpt/commit/7841f6c3c56412552c296d286343b1db16af958d))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/alpha819beta/private-gpt/issues/1779)) ([5e75a88](https://github.com/alpha819beta/private-gpt/commit/5e75a88962a1867af2b38737d689fc0bac1163e3))
* **docs:** Minor documentation amendment ([#1739](https://github.com/alpha819beta/private-gpt/issues/1739)) ([1d8fc07](https://github.com/alpha819beta/private-gpt/commit/1d8fc078d72766811d9ae39e42bacd40a06cbeba))
* **docs:** Update installation.mdx ([#1866](https://github.com/alpha819beta/private-gpt/issues/1866)) ([d033b9a](https://github.com/alpha819beta/private-gpt/commit/d033b9af26556f2dc2ba1a9b1459bb04b099caa4))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([4e62902](https://github.com/alpha819beta/private-gpt/commit/4e629025990431581115fb1fcfecce70cdb5c8b6))
* ffmpy dependency ([#2020](https://github.com/alpha819beta/private-gpt/issues/2020)) ([bee3207](https://github.com/alpha819beta/private-gpt/commit/bee320710bd10b83ab81633f731a1400821dac27))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/alpha819beta/private-gpt/issues/1123)) ([4dd5bce](https://github.com/alpha819beta/private-gpt/commit/4dd5bce63a4a758b0776a653e81f497d10806815))
* Fixed docker-compose ([#1758](https://github.com/alpha819beta/private-gpt/issues/1758)) ([50b647a](https://github.com/alpha819beta/private-gpt/commit/50b647a37a8879667ee92fa988b5478a16afd614))
* **ingest:** update script label ([#1770](https://github.com/alpha819beta/private-gpt/issues/1770)) ([82fef1d](https://github.com/alpha819beta/private-gpt/commit/82fef1d67432694faece327864528a1663b0089e))
* light mode ([#2025](https://github.com/alpha819beta/private-gpt/issues/2025)) ([1f60573](https://github.com/alpha819beta/private-gpt/commit/1f60573a14a2ebb6e417109aa8c2e072dbd5e567))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/alpha819beta/private-gpt/issues/1954)) ([4715803](https://github.com/alpha819beta/private-gpt/commit/47158032d67fb4b9fc37f57206f0ef08036e7822))
* **llm:** special tokens and leading space ([#1831](https://github.com/alpha819beta/private-gpt/issues/1831)) ([c9c822a](https://github.com/alpha819beta/private-gpt/commit/c9c822a7c071270b806433299a69dfb364372f10))
* make docs more visible ([#1081](https://github.com/alpha819beta/private-gpt/issues/1081)) ([59652ae](https://github.com/alpha819beta/private-gpt/commit/59652ae0e3d6cb6664bd008b4a94f8c6e1db61b6))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/alpha819beta/private-gpt/issues/1859)) ([e77372a](https://github.com/alpha819beta/private-gpt/commit/e77372a9094fd9fcd50cbb8322f95107af0725e5))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/alpha819beta/private-gpt/issues/1449)) ([8a5d9ed](https://github.com/alpha819beta/private-gpt/commit/8a5d9ed2a28fe378a3ec7ede811503c9da1dc118))
* naming image and ollama-cpu ([#2056](https://github.com/alpha819beta/private-gpt/issues/2056)) ([2eeaf09](https://github.com/alpha819beta/private-gpt/commit/2eeaf094c978d273ad38394602196d1f52aff311))
* nomic embeddings ([#2030](https://github.com/alpha819beta/private-gpt/issues/2030)) ([e47225b](https://github.com/alpha819beta/private-gpt/commit/e47225be57a4e0ec556b662919cc46aea5e760b5))
* prevent to ingest local files (by default) ([#2010](https://github.com/alpha819beta/private-gpt/issues/2010)) ([ea1d16d](https://github.com/alpha819beta/private-gpt/commit/ea1d16db277b114ee6b64dfcc6a55d724e169f46))
* publish image name ([#2043](https://github.com/alpha819beta/private-gpt/issues/2043)) ([c6301d2](https://github.com/alpha819beta/private-gpt/commit/c6301d2b58476b8f00f574f51a75315df262664f))
* Rectify ffmpy poetry config; update version from 0.3.2 to 0.4.0 ([#2062](https://github.com/alpha819beta/private-gpt/issues/2062)) ([521d7fd](https://github.com/alpha819beta/private-gpt/commit/521d7fd5760edf2c976710afb639e05beb63b358))
* Remove global state ([#1216](https://github.com/alpha819beta/private-gpt/issues/1216)) ([cee3c07](https://github.com/alpha819beta/private-gpt/commit/cee3c07a38978acf7341a9520a057aafd16968b4))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/alpha819beta/private-gpt/issues/1890)) ([1ff8e35](https://github.com/alpha819beta/private-gpt/commit/1ff8e35b94d2d3239d4e2969909cf44303131b59))
* sagemaker config and chat methods ([#1142](https://github.com/alpha819beta/private-gpt/issues/1142)) ([20ec0a1](https://github.com/alpha819beta/private-gpt/commit/20ec0a1fc98e5ba5e11a37d362f4bed08e0ea955))
* Sanitize null bytes before ingestion ([#2090](https://github.com/alpha819beta/private-gpt/issues/2090)) ([a0f80bb](https://github.com/alpha819beta/private-gpt/commit/a0f80bb573932d91bf14353a1350132e51a7f7b8))
* **settings:** correct yaml multiline string ([#1403](https://github.com/alpha819beta/private-gpt/issues/1403)) ([89a149f](https://github.com/alpha819beta/private-gpt/commit/89a149f2e00f23aede8fdf99e8d1755a3ec61175))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/alpha819beta/private-gpt/issues/1925)) ([0c9f9ae](https://github.com/alpha819beta/private-gpt/commit/0c9f9ae968f2bfc1f5ddd4c3c97b9eaf31740d6a))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/alpha819beta/private-gpt/issues/1709)) ([0746180](https://github.com/alpha819beta/private-gpt/commit/0746180358f051e22ecd496d049e4abadfd53f18))
* **tests:** load the test settings only when running tests ([65c4d75](https://github.com/alpha819beta/private-gpt/commit/65c4d7529a315c0b4e07cd19a28abdc4d1bc83d6))
* typo in README.md ([#1091](https://github.com/alpha819beta/private-gpt/issues/1091)) ([9ec96b3](https://github.com/alpha819beta/private-gpt/commit/9ec96b3a13fa403366eb03f2a338fea01734cfb1))
* **ui:** gradio bug fixes ([#2021](https://github.com/alpha819beta/private-gpt/issues/2021)) ([5504936](https://github.com/alpha819beta/private-gpt/commit/5504936696ca0305133be489e97d2b131f6e461d))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([d00de30](https://github.com/alpha819beta/private-gpt/commit/d00de30d4c67e216066c36d0f155514a12f86a74))
* unify embedding models ([#2027](https://github.com/alpha819beta/private-gpt/issues/2027)) ([552f1ad](https://github.com/alpha819beta/private-gpt/commit/552f1ad5646899368314b49da7768fd0d33bbd19))
* update matplotlib to 3.9.1-post1 to fix win install ([7820517](https://github.com/alpha819beta/private-gpt/commit/78205170bcbab49813b37a0606c83efce4030016))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/alpha819beta/private-gpt/issues/1260)) ([11e4878](https://github.com/alpha819beta/private-gpt/commit/11e4878d9e441a0b175a7781d8ed8eea7392f9e3))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/alpha819beta/private-gpt/issues/1280)) ([4226183](https://github.com/alpha819beta/private-gpt/commit/4226183ec4e912a0db27fe4f399d6c026c8457e8))


### Miscellaneous Chores

* Initial version ([7d4b6a7](https://github.com/alpha819beta/private-gpt/commit/7d4b6a70bf481b634aa2b5a5d5914af87c243af8))

## [0.6.2](https://github.com/zylon-ai/private-gpt/compare/v0.6.1...v0.6.2) (2024-08-08)


### Bug Fixes

* add numpy issue to troubleshooting ([#2048](https://github.com/zylon-ai/private-gpt/issues/2048)) ([4ca6d0c](https://github.com/zylon-ai/private-gpt/commit/4ca6d0cb556be7a598f7d3e3b00d2a29214ee1e8))
* auto-update version ([#2052](https://github.com/zylon-ai/private-gpt/issues/2052)) ([7fefe40](https://github.com/zylon-ai/private-gpt/commit/7fefe408b4267684c6e3c1a43c5dc2b73ec61fe4))
* publish image name ([#2043](https://github.com/zylon-ai/private-gpt/issues/2043)) ([b1acf9d](https://github.com/zylon-ai/private-gpt/commit/b1acf9dc2cbca2047cd0087f13254ff5cda6e570))
* update matplotlib to 3.9.1-post1 to fix win install ([b16abbe](https://github.com/zylon-ai/private-gpt/commit/b16abbefe49527ac038d235659854b98345d5387))

## [0.6.1](https://github.com/zylon-ai/private-gpt/compare/v0.6.0...v0.6.1) (2024-08-05)


### Bug Fixes

* add built image from DockerHub ([#2042](https://github.com/zylon-ai/private-gpt/issues/2042)) ([f09f6dd](https://github.com/zylon-ai/private-gpt/commit/f09f6dd2553077d4566dbe6b48a450e05c2f049e))
* Adding azopenai to model list ([#2035](https://github.com/zylon-ai/private-gpt/issues/2035)) ([1c665f7](https://github.com/zylon-ai/private-gpt/commit/1c665f7900658144f62814b51f6e3434a6d7377f))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/zylon-ai/private-gpt/issues/2038)) ([1d4c14d](https://github.com/zylon-ai/private-gpt/commit/1d4c14d7a3c383c874b323d934be01afbaca899e))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/zylon-ai/private-gpt/issues/2037)) ([dae0727](https://github.com/zylon-ai/private-gpt/commit/dae0727a1b4abd35d2b0851fe30e0a4ed67e0fbb))

## [0.6.0](https://github.com/zylon-ai/private-gpt/compare/v0.5.0...v0.6.0) (2024-08-02)


### Features

* bump dependencies ([#1987](https://github.com/zylon-ai/private-gpt/issues/1987)) ([b687dc8](https://github.com/zylon-ai/private-gpt/commit/b687dc852413404c52d26dcb94536351a63b169d))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/zylon-ai/private-gpt/issues/1924)) ([d13029a](https://github.com/zylon-ai/private-gpt/commit/d13029a046f6e19e8ee65bef3acd96365c738df2))
* **docs:** Fix setup docu ([#1926](https://github.com/zylon-ai/private-gpt/issues/1926)) ([067a5f1](https://github.com/zylon-ai/private-gpt/commit/067a5f144ca6e605c99d7dbe9ca7d8207ac8808d))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/zylon-ai/private-gpt/issues/1968)) ([19a7c06](https://github.com/zylon-ai/private-gpt/commit/19a7c065ef7f42b37f289dd28ac945f7afc0e73a))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/zylon-ai/private-gpt/issues/2000)) ([4523a30](https://github.com/zylon-ai/private-gpt/commit/4523a30c8f004aac7a7ae224671e2c45ec0cb973))
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/zylon-ai/private-gpt/issues/2031)) ([cf61bf7](https://github.com/zylon-ai/private-gpt/commit/cf61bf780f8d122e4057d002abf03563bb45614a))
* **llm:** autopull ollama models ([#2019](https://github.com/zylon-ai/private-gpt/issues/2019)) ([20bad17](https://github.com/zylon-ai/private-gpt/commit/20bad17c9857809158e689e9671402136c1e3d84))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/zylon-ai/private-gpt/issues/1965)) ([fc13368](https://github.com/zylon-ai/private-gpt/commit/fc13368bc72d1f4c27644677431420ed77731c03))
* make llama3.1 as default ([#2022](https://github.com/zylon-ai/private-gpt/issues/2022)) ([9027d69](https://github.com/zylon-ai/private-gpt/commit/9027d695c11fbb01e62424b855665de71d513417))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/zylon-ai/private-gpt/issues/1835)) ([e21bf20](https://github.com/zylon-ai/private-gpt/commit/e21bf20c10938b24711d9f2c765997f44d7e02a9))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/zylon-ai/private-gpt/issues/2028)) ([8119842](https://github.com/zylon-ai/private-gpt/commit/8119842ae6f1f5ecfaf42b06fa0d1ffec675def4))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/zylon-ai/private-gpt/issues/1996)) ([43cc31f](https://github.com/zylon-ai/private-gpt/commit/43cc31f74015f8d8fcbf7a8ea7d7d9ecc66cf8c9))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/zylon-ai/private-gpt/issues/1883)) ([2612928](https://github.com/zylon-ai/private-gpt/commit/26129288394c7483e6fc0496a11dc35679528cc1))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/zylon-ai/private-gpt/issues/1841)) ([947e737](https://github.com/zylon-ai/private-gpt/commit/947e737f300adf621d2261d527192f36f3387f8e))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/zylon-ai/private-gpt/issues/1998)) ([01b7ccd](https://github.com/zylon-ai/private-gpt/commit/01b7ccd0648be032846647c9a184925d3682f612))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/zylon-ai/private-gpt/issues/1779)) ([dde0224](https://github.com/zylon-ai/private-gpt/commit/dde02245bcd51a7ede7b6789c82ae217cac53d92))
* **docs:** Update installation.mdx ([#1866](https://github.com/zylon-ai/private-gpt/issues/1866)) ([c1802e7](https://github.com/zylon-ai/private-gpt/commit/c1802e7cf0e56a2603213ec3b6a4af8fadb8a17a))
* ffmpy dependency ([#2020](https://github.com/zylon-ai/private-gpt/issues/2020)) ([dabf556](https://github.com/zylon-ai/private-gpt/commit/dabf556dae9cb00fe0262270e5138d982585682e))
* light mode ([#2025](https://github.com/zylon-ai/private-gpt/issues/2025)) ([1020cd5](https://github.com/zylon-ai/private-gpt/commit/1020cd53288af71a17882781f392512568f1b846))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/zylon-ai/private-gpt/issues/1954)) ([c7212ac](https://github.com/zylon-ai/private-gpt/commit/c7212ac7cc891f9e3c713cc206ae9807c5dfdeb6))
* **llm:** special tokens and leading space ([#1831](https://github.com/zylon-ai/private-gpt/issues/1831)) ([347be64](https://github.com/zylon-ai/private-gpt/commit/347be643f7929c56382a77c3f45f0867605e0e0a))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/zylon-ai/private-gpt/issues/1859)) ([2a432bf](https://github.com/zylon-ai/private-gpt/commit/2a432bf9c5582a94eb4052b1e80cabdb118d298e))
* nomic embeddings ([#2030](https://github.com/zylon-ai/private-gpt/issues/2030)) ([5465958](https://github.com/zylon-ai/private-gpt/commit/54659588b5b109a3dd17cca835e275240464d275))
* prevent to ingest local files (by default) ([#2010](https://github.com/zylon-ai/private-gpt/issues/2010)) ([e54a8fe](https://github.com/zylon-ai/private-gpt/commit/e54a8fe0433252808d0a60f6a08a43c9f5a42f3b))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/zylon-ai/private-gpt/issues/1890)) ([9d0d614](https://github.com/zylon-ai/private-gpt/commit/9d0d614706581a8bfa57db45f62f84ab23d26f15))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/zylon-ai/private-gpt/issues/1925)) ([966af47](https://github.com/zylon-ai/private-gpt/commit/966af4771dbe5cf3fdf554b5fdf8f732407859c4))
* **ui:** gradio bug fixes ([#2021](https://github.com/zylon-ai/private-gpt/issues/2021)) ([d4375d0](https://github.com/zylon-ai/private-gpt/commit/d4375d078f18ba53562fd71651159f997fff865f))
* unify embedding models ([#2027](https://github.com/zylon-ai/private-gpt/issues/2027)) ([40638a1](https://github.com/zylon-ai/private-gpt/commit/40638a18a5713d60fec8fe52796dcce66d88258c))

## [0.5.0](https://github.com/zylon-ai/private-gpt/compare/v0.4.0...v0.5.0) (2024-04-02)


### Features

* **code:** improve concat of strings in ui ([#1785](https://github.com/zylon-ai/private-gpt/issues/1785)) ([bac818a](https://github.com/zylon-ai/private-gpt/commit/bac818add51b104cda925b8f1f7b51448e935ca1))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/zylon-ai/private-gpt/issues/1812)) ([f83abff](https://github.com/zylon-ai/private-gpt/commit/f83abff8bc955a6952c92cc7bcb8985fcec93afa))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/zylon-ai/private-gpt/issues/1782)) ([8a836e4](https://github.com/zylon-ai/private-gpt/commit/8a836e4651543f099c59e2bf497ab8c55a7cd2e5))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/zylon-ai/private-gpt/issues/1741)) ([5725181](https://github.com/zylon-ai/private-gpt/commit/572518143ac46532382db70bed6f73b5082302c1))
* **docs:** upgrade fern ([#1596](https://github.com/zylon-ai/private-gpt/issues/1596)) ([84ad16a](https://github.com/zylon-ai/private-gpt/commit/84ad16af80191597a953248ce66e963180e8ddec))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/zylon-ai/private-gpt/issues/1750)) ([134fc54](https://github.com/zylon-ai/private-gpt/commit/134fc54d7d636be91680dc531f5cbe2c5892ac56))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/zylon-ai/private-gpt/issues/1698)) ([1efac6a](https://github.com/zylon-ai/private-gpt/commit/1efac6a3fe19e4d62325e2c2915cd84ea277f04f))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/zylon-ai/private-gpt/issues/1703)) ([02dc83e](https://github.com/zylon-ai/private-gpt/commit/02dc83e8e9f7ada181ff813f25051bbdff7b7c6b))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/zylon-ai/private-gpt/issues/1800)) ([b3b0140](https://github.com/zylon-ai/private-gpt/commit/b3b0140e244e7a313bfaf4ef10eb0f7e4192710e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/zylon-ai/private-gpt/issues/1773)) ([6f6c785](https://github.com/zylon-ai/private-gpt/commit/6f6c785dac2bbad37d0b67fda215784298514d39))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/zylon-ai/private-gpt/issues/1467)) ([821bca3](https://github.com/zylon-ai/private-gpt/commit/821bca32e9ee7c909fd6488445ff6a04463bf91b))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/zylon-ai/private-gpt/issues/1706)) ([68b3a34](https://github.com/zylon-ai/private-gpt/commit/68b3a34b032a08ca073a687d2058f926032495b3))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/zylon-ai/private-gpt/issues/1771)) ([087cb0b](https://github.com/zylon-ai/private-gpt/commit/087cb0b7b74c3eb80f4f60b47b3a021c81272ae1))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/zylon-ai/private-gpt/issues/1810)) ([83adc12](https://github.com/zylon-ai/private-gpt/commit/83adc12a8ef0fa0c13a0dec084fa596445fc9075))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/zylon-ai/private-gpt/issues/1783)) ([ea153fb](https://github.com/zylon-ai/private-gpt/commit/ea153fb92f1f61f64c0d04fff0048d4d00b6f8d0))
* **ui:** Add Model Information to ChatInterface label ([f0b174c](https://github.com/zylon-ai/private-gpt/commit/f0b174c097c2d5e52deae8ef88de30a0d9013a38))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/zylon-ai/private-gpt/issues/1705)) ([290b9fb](https://github.com/zylon-ai/private-gpt/commit/290b9fb084632216300e89bdadbfeb0380724b12))
* **UI:** Faster startup and document listing ([#1763](https://github.com/zylon-ai/private-gpt/issues/1763)) ([348df78](https://github.com/zylon-ai/private-gpt/commit/348df781b51606b2f9810bcd46f850e54192fd16))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/zylon-ai/private-gpt/issues/1643)) ([410bf7a](https://github.com/zylon-ai/private-gpt/commit/410bf7a71f17e77c4aec723ab80c233b53765964))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/zylon-ai/private-gpt/issues/1730)) ([63de7e4](https://github.com/zylon-ai/private-gpt/commit/63de7e4930ac90dd87620225112a22ffcbbb31ee))
* wipe per storage type ([#1772](https://github.com/zylon-ai/private-gpt/issues/1772)) ([c2d6948](https://github.com/zylon-ai/private-gpt/commit/c2d694852b4696834962a42fde047b728722ad74))


### Bug Fixes

* **docs:** Minor documentation amendment ([#1739](https://github.com/zylon-ai/private-gpt/issues/1739)) ([258d02d](https://github.com/zylon-ai/private-gpt/commit/258d02d87c5cb81d6c3a6f06aa69339b670dffa9))
* Fixed docker-compose ([#1758](https://github.com/zylon-ai/private-gpt/issues/1758)) ([774e256](https://github.com/zylon-ai/private-gpt/commit/774e2560520dc31146561d09a2eb464c68593871))
* **ingest:** update script label ([#1770](https://github.com/zylon-ai/private-gpt/issues/1770)) ([7d2de5c](https://github.com/zylon-ai/private-gpt/commit/7d2de5c96fd42e339b26269b3155791311ef1d08))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/zylon-ai/private-gpt/issues/1709)) ([d17c34e](https://github.com/zylon-ai/private-gpt/commit/d17c34e81a84518086b93605b15032e2482377f7))

## [0.4.0](https://github.com/imartinez/privateGPT/compare/v0.3.0...v0.4.0) (2024-03-06)


### Features

* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/imartinez/privateGPT/issues/1663)) ([45f0571](https://github.com/imartinez/privateGPT/commit/45f05711eb71ffccdedb26f37e680ced55795d44))
* **Vector:** support pgvector ([#1624](https://github.com/imartinez/privateGPT/issues/1624)) ([cd40e39](https://github.com/imartinez/privateGPT/commit/cd40e3982b780b548b9eea6438c759f1c22743a8))

## [0.3.0](https://github.com/imartinez/privateGPT/compare/v0.2.0...v0.3.0) (2024-02-16)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/imartinez/privateGPT/issues/1426)) ([e326126](https://github.com/imartinez/privateGPT/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* Add stream information to generate SDKs ([#1569](https://github.com/imartinez/privateGPT/issues/1569)) ([24fae66](https://github.com/imartinez/privateGPT/commit/24fae660e6913aac6b52745fb2c2fe128ba2eb79))
* **API:** Ingest plain text ([#1417](https://github.com/imartinez/privateGPT/issues/1417)) ([6eeb95e](https://github.com/imartinez/privateGPT/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/imartinez/privateGPT/issues/1432)) ([b178b51](https://github.com/imartinez/privateGPT/commit/b178b514519550e355baf0f4f3f6beb73dca7df2))
* **llm:** Add openailike llm mode ([#1447](https://github.com/imartinez/privateGPT/issues/1447)) ([2d27a9f](https://github.com/imartinez/privateGPT/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/imartinez/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/imartinez/privateGPT/issues/1526)) ([6bbec79](https://github.com/imartinez/privateGPT/commit/6bbec79583b7f28d9bea4b39c099ebef149db843))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/imartinez/privateGPT/issues/1437)) ([4780540](https://github.com/imartinez/privateGPT/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/imartinez/privateGPT/issues/1415)) ([8ec7cf4](https://github.com/imartinez/privateGPT/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/imartinez/privateGPT/issues/1397)) ([c71ae7c](https://github.com/imartinez/privateGPT/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/imartinez/privateGPT/issues/1612)) ([aa13afd](https://github.com/imartinez/privateGPT/commit/aa13afde07122f2ddda3942f630e5cadc7e4e1ee))


### Bug Fixes

* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/imartinez/privateGPT/issues/1519)) ([869233f](https://github.com/imartinez/privateGPT/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/imartinez/privateGPT/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* **docker:** docker broken copy ([#1419](https://github.com/imartinez/privateGPT/issues/1419)) ([059f358](https://github.com/imartinez/privateGPT/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/imartinez/privateGPT/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/imartinez/privateGPT/issues/1449)) ([6191bcd](https://github.com/imartinez/privateGPT/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* **settings:** correct yaml multiline string ([#1403](https://github.com/imartinez/privateGPT/issues/1403)) ([2564f8d](https://github.com/imartinez/privateGPT/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/imartinez/privateGPT/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([24fb80c](https://github.com/imartinez/privateGPT/commit/24fb80ca38f21910fe4fd81505d14960e9ed4faa))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
