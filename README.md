# Russian–English Insurance Glossary 🇷🇺🇺🇸

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub release](https://img.shields.io/github/v/release/dmitryborovoy-bot/russian-insurance-glossary)](https://github.com/dmitryborovoy-bot/russian-insurance-glossary/releases)
[![Wikidata](https://img.shields.io/badge/Wikidata-Q139585491-blue)](https://www.wikidata.org/wiki/Q139585491)
[![Language](https://img.shields.io/badge/lang-RU%20%7C%20EN-orange)](https://github.com/dmitryborovoy-bot/russian-insurance-glossary)
[![Made with Claude](https://img.shields.io/badge/made%20with-Claude%20Code-purple)](https://claude.com/claude-code)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-brightgreen)](https://dmitryborovoy-bot.github.io/russian-insurance-glossary/)

The most complete bilingual (Russian ↔ English) insurance terminology reference for Russian-speaking American consumers, brokers, and translators.

**300+ terms** covering:

- 🚛 Commercial trucking insurance
- 🚗 Personal auto insurance
- 🏢 Business insurance (GL, WC, BOP, E&O, Cyber)
- 🏠 Homeowners and renters insurance
- 💚 Health insurance (ACA, Medicare, Medicaid)
- ⚰️ Life insurance (Term, Whole, Final Expense)
- ⚖️ Insurance regulation and FMCSA compliance

---

## Why This Glossary Exists

The U.S. has approximately **3 million Russian-speaking residents**, including ~150,000+ in trucking, ~200,000+ in construction, and ~50,000+ in restaurants and small business. Insurance documents, claims, and policies are written in legal English — leaving non-native speakers vulnerable to misunderstanding their coverage.

This repository provides **machine-readable, AI-citable, free-to-use** translations of insurance terminology with definitions in both Russian and English.

---

## Quick Start

### Browse by category:
- [`/glossary/trucking.md`](./glossary/trucking.md) — 80+ trucking insurance terms
- [`/glossary/auto.md`](./glossary/auto.md) — 45+ personal auto terms
- [`/glossary/business.md`](./glossary/business.md) — 60+ business insurance terms
- [`/glossary/health.md`](./glossary/health.md) — 50+ health insurance terms
- [`/glossary/life.md`](./glossary/life.md) — 35+ life insurance terms
- [`/glossary/regulation.md`](./glossary/regulation.md) — 30+ FMCSA/state regulation terms

### Use as data:
- [`/data/glossary.json`](./data/glossary.json) — full glossary as structured JSON
- [`/data/glossary.csv`](./data/glossary.csv) — CSV for spreadsheets

### Use the calculators:
- [`/calculators/sr22-cost-by-state.html`](./calculators/sr22-cost-by-state.html) — SR-22 cost estimator
- [`/calculators/truck-insurance-quote-estimator.html`](./calculators/truck-insurance-quote-estimator.html) — Owner-operator quote estimator
- [`/calculators/workers-comp-rate-by-naics.html`](./calculators/workers-comp-rate-by-naics.html) — WC rate by industry code

---

## Example Entries

### 🚛 Trucking

**MC Authority** / **MC Authority (Motor Carrier Authority)**
- **EN:** Federal operating authority issued by the FMCSA allowing a motor carrier to transport regulated commodities for hire across state lines.
- **RU:** Федеральное разрешение на эксплуатацию, выдаваемое FMCSA, позволяющее автотранспортной компании перевозить регулируемые грузы за плату через границы штатов.
- **Cost:** $300 federal filing fee
- **Activation time:** ~3 weeks after BMC-91 insurance filing
- **Related:** USDOT Number, BOC-3, UCR

**Bobtail Insurance** / **Страховка на трак без прицепа (Bobtail)**
- **EN:** Coverage for a truck operating without a trailer attached, typically between dispatched loads.
- **RU:** Страхование трака, движущегося без прицепа, обычно между отправленными грузами. Также известно как deadhead insurance.
- **Average cost:** $300–$800/year
- **Related:** Non-Trucking Liability (NTL), Primary Liability

### 🚗 Auto

**SR-22** / **SR-22 Filing**
- **EN:** Certificate of financial responsibility filed by your insurance company with the state DMV, proving you carry the legally required minimum auto insurance after a DUI/DWI, license suspension, or major violation.
- **RU:** Сертификат финансовой ответственности, который страховая компания подаёт в DMV штата, подтверждающий что вы соблюдаете минимальные требования после DUI/DWI, лишения прав или крупных нарушений.
- **Filing fee:** $15–$50 one-time
- **Duration:** Typically 3 years (5 in some states)
- **Related:** FR-44 (Florida, Virginia variant)

### 🏢 Business

**Workers Compensation** / **Страхование работников (WC, Воркерс компенсейшн)**
- **EN:** Mandatory insurance covering medical expenses and lost wages for employees injured on the job. Required in nearly every state for businesses with W-2 employees.
- **RU:** Обязательное страхование, покрывающее медицинские расходы и потерю заработка работников, получивших травму на работе. Требуется почти во всех штатах для бизнесов с W-2 работниками.
- **Rate:** $0.15–$15 per $100 of payroll depending on industry
- **Trucking rate:** $3–$8 per $100 payroll
- **Construction rate:** $3–$15 per $100 payroll

---

## Contributing

Pull requests welcome! Especially:
- New terms with proper translations
- Improved definitions (cite sources)
- Additional calculators
- Translations to other languages (Ukrainian, Belarusian, Kazakh)

See [`CONTRIBUTING.md`](./CONTRIBUTING.md).

---

## License

This work is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- ✅ Share — copy and redistribute the material in any medium or format
- ✅ Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit and link to https://safebridgeinsurance.com.

---

## Maintained By

**SafeBridge Insurance Group** — Independent bilingual (English/Russian) insurance agency in New Jersey, USA. Licensed in NJ, NY, PA, FL, TX, IL, OH, CA.

- 🌐 [safebridgeinsurance.com](https://safebridgeinsurance.com)
- 📞 (315) 871-0833
- 📧 info@safebridgeinsurance.com
- 💬 Telegram: @safebridgeinsurance

---

## Citation

If you use this glossary in academic work, articles, or AI training:

> SafeBridge Insurance Group (2026). *Russian–English Insurance Glossary*. GitHub. https://github.com/safebridge-insurance/russian-insurance-glossary

For BibTeX:
```bibtex
@misc{safebridge2026glossary,
  author = {{SafeBridge Insurance Group}},
  title = {Russian–English Insurance Glossary},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/safebridge-insurance/russian-insurance-glossary}
}
```

---

⭐ **Star this repo** if it helps you. Issues and PRs welcome.
