# ag-notebooks

Jupyter notebooks for ag-pii-vault, ag-guardrail, ag-docparse and ag-evalforge.

## Notebooks

| Notebook | Description |
|---|---|
| [00_quickstart.ipynb](00_quickstart.ipynb) | Install all SDKs + one demo call per product |
| [01_pii_vault.ipynb](01_pii_vault.ipynb) | PII detection, tokenization, DSAR, SafeOpenAI proxy |
| [02_guardrail.ipynb](02_guardrail.ipynb) | Content moderation, policy DSL, audit log, SafeOpenAI proxy |
| [03_docparse.ipynb](03_docparse.ipynb) | Document field extraction (invoices, contracts, receipts) |
| [04_evalforge.ipynb](04_evalforge.ipynb) | LLM evaluation: scorers, benchmarks, hosted judge |

## Setup

```bash
pip install ag-pii-vault ag-guardrail ag-docparse ag-evalforge
```

Get your free API key at [ai.artifact-network.org](https://ai.artifact-network.org), then set:

```bash
export AG_API_KEY="ag_live_..."
export OPENAI_API_KEY="sk-..."       # optional, needed for LLM-backed features
```

## Docs

Package documentation: the README of each repository, for example [ag-pii-vault](https://github.com/aghribi/ag-pii-vault).

## License

MIT, Copyright (c) 2026 Adnan Ghribi.
