# Contributing to Russian-English Insurance Glossary

Thanks for helping make insurance more accessible to Russian-speaking Americans!

## How to Contribute

### Adding a New Term

1. Fork this repository
2. Edit `data/glossary.json` to add your term following this structure:

```json
{
  "id": "kebab-case-id",
  "category": "trucking | auto | business | health | life | regulation | general",
  "termEn": "English Term",
  "termRu": "Русский термин",
  "definitionEn": "Clear, factual definition in English. Cite sources where possible.",
  "definitionRu": "Чёткое, фактическое определение на русском. Укажите источники где возможно.",
  "synonyms": ["Alternative term"],
  "relatedTerms": ["other-id"]
}
```

3. Submit a pull request with title format: `[ADD] Term: <term name>`

### Improving an Existing Term

1. Fork and edit
2. PR title: `[FIX] Term: <term name>`
3. Explain what was wrong and what you changed in the PR description

### Standards

- **Definitions must be factual.** No marketing language.
- **Cite sources** when possible (FMCSA, NAIC, IRS, state DOI).
- **Consistent capitalization** — use Title Case for English terms.
- **Russian translations** must be reviewed by a native speaker.
- **Avoid jargon** in definitions — explain like to a smart 12-year-old.

### What We Don't Accept

- Promotional content for specific insurance companies (other than factual market share data).
- Politically charged definitions.
- Translations from machine translation alone (must be human-reviewed).

## Maintainers

- SafeBridge Insurance Group team
- Open to community co-maintainers after 5+ accepted PRs

## Questions?

Open an issue or email info@safebridgeinsurance.com.
