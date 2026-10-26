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
pip install "ag-pii-vault>=0.6" "ag-guardrail>=0.6" "ag-docparse>=0.6" "ag-evalforge>=0.6"
```

The local examples need no key. The hosted examples call a running [ag-platform](https://github.com/aghribi/ag-platform) deployment:

```bash
export AG_API_URL="https://your-ag-platform"
export AG_API_KEY="ag_live_..."      # issued by that deployment
export OPENAI_API_KEY="sk-..."       # optional, needed for LLM-backed features
```

## Docs

Package documentation: the README of each repository, for example [ag-pii-vault](https://github.com/aghribi/ag-pii-vault).

## License

MIT, Copyright (c) 2026 Adnan Ghribi.
