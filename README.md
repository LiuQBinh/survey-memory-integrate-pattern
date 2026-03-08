# Survey: Integrating Memory into LLM-Based Agents

Cloned source code of open-source memory frameworks for LLM-based agents. One folder per framework, numbered for reference.

## Objective

**Goal:** Survey and compare **how memory is integrated into memory agents** — integration patterns, APIs, and how agents use memory in practice.

- **Integration patterns:** Where and how the agent reads/writes memory (SDK, tools, RAG, graph API, etc.).
- **Storage & retrieval:** Backends, indexing, and recall semantics (e.g. semantic search, temporal, hierarchical).
- **Agent loop:** How memory is injected into context, updated after turns, and exposed as tools or state.

This repo is the codebase for that survey; findings can be documented per framework or in a separate comparison doc.

## Reference

- **Tham khảo** — Survey paper: [arXiv:2512.13564](https://arxiv.org/pdf/2512.13564), **Table 9**: *Overview of Open-Source Memory Frameworks for LLM-Based Agents*
- **Tham khảo** — Paper list: [Shichun-Liu/Agent-Memory-Paper-List](https://github.com/Shichun-Liu/Agent-Memory-Paper-List)

Table columns: **Fac.** (Factual), **Exp.** (Experiential), **MM.** (Multimodal), **Structure**, **Evaluation**.

## Frameworks

| # | Folder | Framework | GitHub | Website / Docs |
|---|--------|-----------|--------|----------------|
| 1 | `1-a-mem` | A-MEM | [agiresearch/A-mem](https://github.com/agiresearch/A-mem) | — |
| 2 | `2-acontext` | Acontext | [memodb-io/Acontext](https://github.com/memodb-io/Acontext) | — |
| 3 | `3-agentmemory` | AgentMemory | [elizaOS/agentmemory](https://github.com/elizaOS/agentmemory) | [Website](https://www.getzep.com/product/agent-memory/) |
| 4 | `4-chroma` | Chroma | [chroma-core/chroma](https://github.com/chroma-core/chroma) | [trychroma.com](https://www.trychroma.com/) |
| 5 | `5-cognee` | Cognee | [topoteretes/cognee](https://github.com/topoteretes/cognee) | [cognee.ai](https://www.cognee.ai/) |
| 6 | `6-hindsight` | HindSight | [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | — |
| 7 | `7-langmem` | LangMem | [langchain-ai/langmem](https://github.com/langchain-ai/langmem) | [Docs](https://langchain-ai.github.io/langmem/) |
| 8 | `8-lightmem` | LightMem | [zjunlp/LightMem](https://github.com/zjunlp/LightMem) | — |
| 9 | `9-mem0` | Mem0 | [mem0ai/mem0](https://github.com/mem0ai/mem0) | [mem0.ai](https://mem0.ai/) |
| 10 | `10-memary` | Memary | [kingjulio8238/Memary](https://github.com/kingjulio8238/Memary) | [Docs](https://kingjulio8238.github.io/memarydocs/) |
| 11 | `11-memengine` | MemEngine | [nuster1128/MemEngine](https://github.com/nuster1128/MemEngine) | — |
| 12 | `12-memgpt` | MemGPT | [cpacker/MemGPT](https://github.com/cpacker/MemGPT) | [docs.letta.com](https://docs.letta.com/) |
| 13 | `13-memobase` | Memobase | [memodb-io/memobase](https://github.com/memodb-io/memobase) | [memobase.io](https://www.memobase.io/) |
| 14 | `14-memori` | Memori | [MemoriLabs/Memori](https://github.com/MemoriLabs/Memori) | [memori.ai](https://memori.ai/) |
| 15 | `15-memoryos` | MemoryOS | [BAI-LAB/MemoryOS](https://github.com/BAI-LAB/MemoryOS) | [baijia.online/memoryos](https://baijia.online/memoryos/) |
| 16 | `16-memos` | MemOS | [MemTensor/MemOS](https://github.com/MemTensor/MemOS) | [memos.openmem.net](https://memos.openmem.net/) |
| 17 | `17-memu` | MemU | [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) | [memu.pro](https://memu.pro/) |
| 18 | `18-minecontext` | MineContext | [volcengine/MineContext](https://github.com/volcengine/MineContext) | [Website](https://app.daily.dev/posts/minecontext-is-your-proactive-context-aware-ai-partner-b0fvvtds3) |
| 19 | `19-mirix` | MIRIX | [Mirix-AI/MIRIX](https://github.com/Mirix-AI/MIRIX) | [mirix.io](https://mirix.io/) |
| 20 | `20-pinecone-assistant-mcp` | Pinecone | [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) | [Docs](https://docs.pinecone.io/guides/assistant/overview) |
| 21 | `21-powermem` | PowerMem | [oceanbase/powermem](https://github.com/oceanbase/powermem) | — |
| 22 | `22-reme` | ReMe | [agentscope-ai/ReMe](https://github.com/agentscope-ai/ReMe) | [memoryscope.ai](https://www.memoryscope.ai/) |
| 23 | `23-second-me` | Second Me | [mindverse/Second-Me](https://github.com/mindverse/Second-Me) | [second.me](https://home.second.me/) |
| 24 | `24-simplemem` | SimpleMem | [aiming-lab/SimpleMem](https://github.com/aiming-lab/SimpleMem) | [SimpleMem Page](https://aiming-lab.github.io/SimpleMem-Page/) |
| 25 | `25-supermemory` | SuperMemory | [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) | [supermemory.ai](https://supermemory.ai/) |
| 26 | `26-weaviate` | Weaviate | [weaviate/weaviate](https://github.com/weaviate/weaviate) | [weaviate.io](https://weaviate.io/) |
| 27 | `27-zep` | Zep | [getzep/zep](https://github.com/getzep/zep) | [getzep.com](https://www.getzep.com/) |

## Clone

Repos were cloned with `git clone --depth 1`. To refresh a framework:

```bash
cd <folder>
git pull
```

## Push to your GitHub

1. Create a new repository on GitHub (e.g. `survey-memory-integrate-pattern`), do **not** init with README.
2. Add remote and push:

```bash
git remote add origin https://github.com/YOUR_USERNAME/survey-memory-integrate-pattern.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## License

Each subfolder is the upstream project; see its repository for license and terms.
