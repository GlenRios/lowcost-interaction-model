# lowcost-interaction-model

A general, domain-specific, low-cost interaction model that runs effectively on CPU with limited computing resources.

## Idea

Interaction methods based on AI models (LLMs, embeddings, rerankers) usually need costly infrastructure or are too slow on CPU. This thesis explores combining lightweight models that run decently on CPU (such as deciders and extractors), other non-LLM components, and LoRA fine-tuning of small models, to build an interaction model that works with few computing resources.

## Status

Early stage: state-of-the-art review.

## Repository layout

| Path | Contents |
|---|---|
| `docs/state-of-the-art/` | Synthesis matrix and search protocol |
| `docs/state-of-the-art/papers/` | One summary per paper |
| `docs/decisions/` | Design decisions and their rationale |
| `references/` | Bibliography |
| `src/` | Source code of the system |
| `experiments/` | Configs, scripts and results |
| `notebooks/` | Exploratory notebooks |
| `thesis/` | Thesis text |
