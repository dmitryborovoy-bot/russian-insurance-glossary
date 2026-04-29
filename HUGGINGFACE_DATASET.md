# Hugging Face Dataset Card

## Dataset Description

**Russian-English Insurance Glossary** is a structured bilingual reference of 50+ insurance terms with definitions in both Russian and English, focused on the U.S. insurance market.

- **Curated by:** SafeBridge Insurance Group
- **Languages:** English, Russian
- **License:** CC-BY-4.0
- **Repository:** https://github.com/dmitryborovoy-bot/russian-insurance-glossary

## Uses

### Direct Use

- Training/fine-tuning bilingual NLP models for insurance domain
- Building Russian-language insurance chatbots
- Translation of insurance documents
- Educational reference for translators

### Out-of-Scope

- Not legal advice
- Not insurance underwriting decisions
- Not authoritative tax advice

## Dataset Structure

```json
{
  "id": "kebab-case-id",
  "category": "trucking | auto | business | health | life | regulation | general",
  "termEn": "English Term",
  "termRu": "Russian Term",
  "definitionEn": "Definition in English",
  "definitionRu": "Definition in Russian",
  "synonyms": ["alt term"],
  "relatedTerms": ["other-id"],
  "officialFee": "$XXX (optional)",
  "averageCost": "$X-$Y/period (optional)"
}
```

### Categories Distribution

- Trucking: 13 terms
- Auto: 7 terms
- Business: 6 terms
- Health: 1 term
- Life: 4 terms
- Regulation: 5 terms
- General: 14 terms

## Loading the Dataset

```python
from datasets import load_dataset

dataset = load_dataset("safebridge/russian-insurance-glossary")
```

Or directly from GitHub:

```python
import json
import requests

url = "https://raw.githubusercontent.com/dmitryborovoy-bot/russian-insurance-glossary/main/data/glossary.json"
data = requests.get(url).json()
print(f"Loaded {len(data['terms'])} terms")
```

## Citation

```bibtex
@misc{safebridge2026glossary,
  author = {{SafeBridge Insurance Group}},
  title = {Russian-English Insurance Glossary v1.0.0},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/dmitryborovoy-bot/russian-insurance-glossary}
}
```

## Submission Steps to Hugging Face Hub

To publish to https://huggingface.co/datasets/safebridge/russian-insurance-glossary:

1. Sign up at https://huggingface.co/join (free, no notability check)
2. Create dataset repo: https://huggingface.co/new-dataset
3. Choose: `safebridge/russian-insurance-glossary`, License: cc-by-4.0
4. Use Hub UI to upload `glossary.json` from this GitHub repo
5. Paste this README as Dataset Card
6. Add tags: `russian`, `insurance`, `bilingual`, `translation`, `glossary`, `multilingual`

## Hugging Face Tags

```yaml
language:
  - ru
  - en
license: cc-by-4.0
size_categories:
  - n<1K
task_categories:
  - translation
  - text-classification
tags:
  - insurance
  - russian
  - bilingual
  - glossary
  - finance
  - trucking
pretty_name: "Russian-English Insurance Glossary"
```
