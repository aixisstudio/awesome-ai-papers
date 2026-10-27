# Awesome Ai Papers

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Les papiers IA incontournables, expliqués simplement

_Le contenu détaillé (listes, liens, descriptions) est en anglais pour rester maintenable — les sections ci-dessous te guident._

## 📜 Must-reads, explained simply

### Transformers era
- **Attention Is All You Need** (2017) — the paper that started it all: self-attention replaces recurrence
- **BERT** (2018) — bidirectional pretraining; encoder models for understanding
- **GPT-2 / GPT-3** (2019/2020) — scaling laws: bigger → emergent abilities, few-shot learning

### Modern LLMs
- **InstructGPT** (2022) — RLHF: teach the model to follow instructions, not just autocomplete
- **Chain-of-Thought** (2022) — "think step by step" actually works
- **ReAct** (2022) — reasoning + acting interleaved — the agent pattern
- **Constitutional AI** (2022) — Claude's alignment method
- **RLAIF / DPO** (2023) — simpler preference training without RL instability

### Retrieval & agents
- **RAG** (2020) — retrieval-augmented generation, original
- **Lost in the Middle** (2023) — long-context models ignore the middle → how to arrange context
- **Toolformer** (2023) — models teaching themselves to call APIs
- **GraphRAG** (2024, Microsoft) — entity graphs beat naive chunk search for multi-hop

### Efficiency
- **LoRA** (2021) — fine-tune tiny adapters, not the whole net
- **FlashAttention** (2022) — exact attention, way faster
- **Speculative decoding** (2023) — small model drafts, big model verifies → speedup

## 🎓 How to read a paper (fast)
Abstract → figures → conclusion → method skim. Most value in 20% of pages.

## 📜 Additional canonical papers

| Paper | Why |
|---|---|
| LoRA (2021) | Cheap fine-tuning |
| DPO (2023) | RLHF without RL |
| FlashAttention (2022) | Why long context got cheap |
| Scaling Laws (Kaplan 2020) | Predictable improvement |
| In-Context Learning surveys | Why prompts work |
| ReAct (2022) | Agents' reasoning loop |
| RAG (Lewis 2020) | Retrieval-grounded generation |

## 🗂️ Where to follow

- **arxiv cs.CL / cs.LG** daily
- **Papers with Code** — paper → implementation
- **HuggingFace Papers** — community-voted daily
- **The Batch** (Andrew Ng) — weekly digest
- **alphaxiv** — discuss papers layer

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
