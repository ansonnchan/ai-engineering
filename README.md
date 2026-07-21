# AI Engineering Roadmap (LLMs, Agents & AI Applications)

## Goal

Learn how modern LLMs work, how to prompt them effectively, and how to build production-ready AI applications using tools like OpenAI, Claude, Gemini, Cursor, Codex, MCP, and other AI engineering workflows.

---

## Legend

| Tier | Meaning |
|--------|----------|
| Tier 1 | Core concepts every AI engineer should understand. |
| Tier 2 | Essential techniques for building AI applications. |
| Tier 3 | Advanced concepts commonly used in production AI systems. |
| Tier 4 | Specialized topics worth learning after the fundamentals. |

---

# Tier 1 — LLM Foundations

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | What is an LLM? | Next-token prediction |
| [ ] | Transformers | High-level architecture |
| [ ] | Self-Attention | How models process context |
| [ ] | Tokens | Tokenization, BPE, SentencePiece |
| [ ] | Context Windows | Limits and tradeoffs |
| [ ] | Prompt Tokens vs Completion Tokens | Token accounting |
| [ ] | Reasoning Tokens | Thinking models |
| [ ] | Embeddings | Vector representations |
| [ ] | Positional Encoding | Understanding sequence order |
| [ ] | Temperature | Creativity vs determinism |
| [ ] | Top-p Sampling | Output diversity |
| [ ] | Hallucinations | Why they occur |
| [ ] | Determinism & Seeds | Reproducible outputs |
| [ ] | Fine-tuning vs Prompting | Choosing the right approach |
| [ ] | Inference | Model execution basics |
| [ ] | Quantization | Faster, smaller models |
| [ ] | KV Cache | Efficient long conversations |

---

# Tier 2 — Prompt Engineering

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | System Prompts | Controlling model behavior |
| [ ] | User Prompts | Clear instructions |
| [ ] | Prompt Structure | Role, task, constraints |
| [ ] | Delimiters | XML, Markdown, JSON |
| [ ] | Zero-shot Prompting | No examples |
| [ ] | Few-shot Prompting | Learning from examples |
| [ ] | Chain-of-Thought | Reasoning prompts |
| [ ] | Self-Consistency | Multiple reasoning paths |
| [ ] | Prompt Chaining | Multi-step workflows |
| [ ] | Structured Outputs | JSON mode |
| [ ] | Function / Tool Calling | Connecting external tools |
| [ ] | Prompt Evaluation | Measuring prompt quality |
| [ ] | Prompt Versioning | Managing prompt evolution |
| [ ] | Guardrails | Safe and reliable outputs |
| [ ] | Prompt Injection | Security risks |

---

# Tier 3 — Models & AI APIs

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | GPT Models | OpenAI |
| [ ] | Claude Models | Anthropic |
| [ ] | Gemini Models | Google |
| [ ] | Llama | Meta |
| [ ] | Qwen | Alibaba |
| [ ] | DeepSeek | Open-source reasoning |
| [ ] | Model Selection | Choosing the right model |
| [ ] | Streaming Responses | Token streaming |
| [ ] | Server-Sent Events (SSE) | Streaming transport |
| [ ] | API Rate Limits | Managing quotas |
| [ ] | Cost Optimization | Token budgeting |
| [ ] | Latency Optimization | Faster responses |
| [ ] | Request Batching | Higher throughput |
| [ ] | Retries & Backoff | Reliable APIs |

---

# Tier 4 — Context, Memory & Retrieval

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | Conversation Memory | Maintaining chat history |
| [ ] | Context Engineering | Optimizing context quality |
| [ ] | Context Compression | Summarization techniques |
| [ ] | Context Compaction | Long conversation management |
| [ ] | Chunking | Splitting documents |
| [ ] | Sliding Windows | Long-context handling |
| [ ] | RAG | Retrieval-Augmented Generation |
| [ ] | Semantic Search | Meaning-based retrieval |
| [ ] | Vector Databases | Pinecone, pgvector, Weaviate |
| [ ] | Similarity Search | Cosine similarity |
| [ ] | Hybrid Search | Keyword + embeddings |
| [ ] | Re-ranking | Improving retrieval quality |
| [ ] | Knowledge Bases | External context |

---

# Tier 5 — Agents

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | What is an AI Agent? | Beyond chatbots |
| [ ] | Agent Loops | Think → Act → Observe |
| [ ] | Planning | Task decomposition |
| [ ] | Reflection | Self-correction |
| [ ] | Tool Calling | External capabilities |
| [ ] | Multi-Agent Systems | Coordinating agents |
| [ ] | Agent Memory | Long-term state |
| [ ] | Agent Frameworks | LangGraph, CrewAI, etc. |
| [ ] | Model Context Protocol (MCP) | Standardized tool access |
| [ ] | MCP Clients | Using MCP servers |
| [ ] | MCP Servers | Building tools |
| [ ] | Resources | Shared context in MCP |
| [ ] | Prompts | MCP prompt resources |
| [ ] | Tools | Exposed functionality |
| [ ] | Sampling | Model requests within MCP |

---

# Tier 6 — AI Application Engineering

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | AI Chat Applications | Overall architecture |
| [ ] | Streaming UI | Realtime user experience |
| [ ] | Conversation State | Managing sessions |
| [ ] | Async Workers | Background inference |
| [ ] | Queues | Redis Streams, SQS |
| [ ] | Caching | Prompt/result caching |
| [ ] | Observability | Logs, metrics, traces |
| [ ] | Evaluation Pipelines | Testing AI systems |
| [ ] | AI Safety | Content moderation |
| [ ] | Cost Monitoring | Production budgeting |
| [ ] | Rate Limiting | Preventing abuse |
| [ ] | Human-in-the-loop | Manual review workflows |

---

# Tier 7 — GitHub AI Engineering

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | `AGENTS.md` | Project-wide AI instructions |
| [ ] | `CLAUDE.md` | Anthropic project memory |
| [ ] | `GEMINI.md` | Gemini project instructions |
| [ ] | Cursor Rules | Cursor IDE customization |
| [ ] | Codex Instructions | Codex project guidance |
| [ ] | GitHub Copilot Instructions | Repository-specific guidance |
| [ ] | Skills | Reusable AI capabilities |
| [ ] | Superpowers | Reusable AI workflows |
| [ ] | Prompt Libraries | Shared prompt collections |
| [ ] | Slash Commands | Custom AI commands |
| [ ] | Tool Orchestration | Coordinating multiple tools |
| [ ] | Context Engineering | Organizing project context |
| [ ] | Prompt Compression | Reducing token usage |
| [ ] | Conversation Compaction | Long-session optimization |
| [ ] | AI Coding Workflows | Human + AI development practices |

---

# Tier 8 — Advanced Topics

| Done | Concept | Notes |
|------|---------|-------|
| [ ] | Fine-tuning | Custom model training |
| [ ] | LoRA | Efficient fine-tuning |
| [ ] | Distillation | Smaller models |
| [ ] | Speculative Decoding | Faster inference |
| [ ] | Mixture of Experts (MoE) | Sparse architectures |
| [ ] | Multimodal Models | Text, image, audio, video |
| [ ] | Vision Language Models | Image understanding |
| [ ] | Open-weight Models | Self-hosting |
| [ ] | Local Inference | Ollama, vLLM |
| [ ] | AI Evaluation Benchmarks | MMLU, SWE-bench |
| [ ] | AI Security | Jailbreaks & defenses |
| [ ] | AI Alignment | High-level concepts |
