# Ahmed Semih Özmekik

Software engineer working on backend systems, LLM infrastructure and developer tooling.
I run [Fergani](https://fergani.tr), where I build NextLangua, a language-learning app on the
App Store, and the open-source libraries below.

**Go · TypeScript · Python · Rust · C++ · Swift.** Mostly interested in LLM serving and
evaluation, real-time audio, distributed systems and tools other developers use.

[![Stack](https://skillicons.dev/icons?i=go,ts,py,rust,cpp,swift,react,nodejs,postgres,redis,docker,kubernetes,gcp,linux&theme=light)](https://skillicons.dev)

## Open source

**Backend and infrastructure**

| Project | |
| --- | --- |
| [go-idempotency](https://github.com/aozmekik/go-idempotency) | `net/http` middleware for the IETF Idempotency-Key draft, with memory, Redis and PostgreSQL stores. The handler runs once per key, however often a client retries. |
| [go-adaptive-limiter](https://github.com/aozmekik/go-adaptive-limiter) | Adaptive concurrency limiting and load shedding (Gradient2, Vegas, AIMD, priority partitions) for HTTP and gRPC, with a discrete-event simulator. |
| [webhook-signatures](https://github.com/aozmekik/webhook-signatures) | Zero-dependency webhook verification on Web Crypto for Stripe, GitHub, Slack, Shopify, Svix, Twilio and more, cross-validated against the official SDKs. |
| [orderbook-cpp](https://github.com/aozmekik/orderbook-cpp) | C++20 limit order book and matching engine with no allocation on the hot path, tested against a deliberately simple reference engine. |

**LLM and AI infrastructure**

| Project | |
| --- | --- |
| [radix-kv](https://github.com/aozmekik/radix-kv) | C++20 KV-cache block manager: PagedAttention-style copy-on-write paging, hash and radix-tree prefix caches, a trace-driven simulator and Python bindings. |
| [llm-loadtest](https://github.com/aozmekik/llm-loadtest) | Load tester for OpenAI-compatible streaming endpoints: time to first token, inter-token latency, throughput, open-loop arrivals. |
| [hnsw-index](https://github.com/aozmekik/hnsw-index) | HNSW vector index in Rust, written from the paper, with SIMD distance kernels, filtered search and deletion. |
| [gguf-inspect](https://github.com/aozmekik/gguf-inspect) | Inspects GGUF (llama.cpp) models without loading tensors: metadata, quantization breakdown, KV-cache sizing, diffs. |
| [mcp-contract](https://github.com/aozmekik/mcp-contract) | Contract testing for MCP servers: snapshots tools, resources and prompts and flags breaking schema changes in CI. |
| [llm-cassette](https://github.com/aozmekik/llm-cassette) | Record and replay for OpenAI and Anthropic SDK calls at the httpx layer, with a pytest plugin. |

**Clients and local-first**

| Project | |
| --- | --- |
| [swift-sse](https://github.com/aozmekik/swift-sse) | Server-Sent Events client for Swift Concurrency that follows the WHATWG spec, with OpenAI and Anthropic stream decoders. |
| [fugue-text](https://github.com/aozmekik/fugue-text) | Fugue text CRDT for collaborative editing, with randomized convergence tests across replicas. |
| [turkish-inflect](https://github.com/aozmekik/turkish-inflect) | Correct Turkish suffixes for dynamic values in UI strings (`Ayşe'ye`, `2026'da`, `TBMM'ye`), following the TDK spelling guide. |

## Recent pull requests and reviews

- [livekit/node-sdks#745](https://github.com/livekit/node-sdks/pull/745): audio and video frames built from `subarray()` handed native code the wrong bytes
- [resend/resend-go#174](https://github.com/resend/resend-go/pull/174): `preview_text` and `topic_id` for broadcasts
- [charmbracelet/crush#4090](https://github.com/charmbracelet/crush/pull/4090): accept `--yolo` on `crush run`
- [apache/superset#45428](https://github.com/apache/superset/pull/45428): reviewed and fixed 208 Turkish UI strings
- [mui/mui-x#23912](https://github.com/mui/mui-x/pull/23912): completed the Turkish locale for Data Grid, Date Pickers and Scheduler
- Root-cause analyses for [modelcontextprotocol/typescript-sdk#2408](https://github.com/modelcontextprotocol/typescript-sdk/issues/2408) and [sharkdp/bat#4080](https://github.com/sharkdp/bat/issues/4080), and a Turkish docs review for [huggingface_hub#4655](https://github.com/huggingface/huggingface_hub/pull/4655)

## Contact

[fergani.tr](https://fergani.tr) · [LinkedIn](https://www.linkedin.com/in/aozmekik) · ahmed-semih@outlook.com
