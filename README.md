# Aliaksei Krachkouski — Python automation & AI integration

I build the unglamorous, reliable half of data work: getting data out of places it does not want to leave, putting it through a language model when that genuinely helps, and then checking whether the numbers at the end can be trusted.

San Diego, California · available for project work
**[alexdevcore.com](https://alexdevcore.com/en)** · [hello@alexdevcore.com](mailto:hello@alexdevcore.com) · [LinkedIn](https://www.linkedin.com/in/alexdevcore/)

---

## What I do

**Web scraping & data extraction** — paginated catalogs, listings, price monitoring, lead research. Delivered as clean CSV/Excel, or written straight into your database.

**Data pipelines & reporting** — normalizing sources that disagree on format, then making the whole thing scheduled and Dockerized so it keeps running without anyone watching it.

**AI / LLM integration** — pulling structure out of unstructured text, document understanding, categorization, translation. Including vision, when the input is a photograph rather than a file.

**Backtest & data validation** — leakage-safe methodology, confidence intervals that account for correlated observations, and execution simulated against a real order book instead of assuming a midpoint fill.

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| **[CopyTradeAudit](https://github.com/AlexDevCore/CopyTradeAudit)** | A leakage-safe backtesting engine, used to audit the "copy successful traders" hypothesis across 370 markets and 134,000 trades — and to publish the negative result | Python · FastAPI · pytest · SQLite |
| **[DocumentExplainer](https://github.com/AlexDevCore/DocumentExplainer)** | Live web app that reads official US letters — DMV, IRS, bank, landlord — and explains them in plain language, including photographs of documents | Python · Flask · Claude API |
| **[CatalogScraper](https://github.com/AlexDevCore/CatalogScraper)** | Turns any paginated catalog site into a clean, ready-to-open spreadsheet — pagination, extraction and export handled | Python · BeautifulSoup · openpyxl |
| **[InvestmentsScraper](https://github.com/AlexDevCore/InvestmentsScraper)** | Consolidates brokerage exports from six platforms that share no common format into one normalized table | Python · pandas |

---

## If you only read one

**[CopyTradeAudit](https://github.com/AlexDevCore/CopyTradeAudit)** — because the useful part is not that it works, but that it says so when it doesn't.

The measured verdict was *no edge*: copying tracked traders returned +0.0200 per share above the 0.95 price band, while buying that same band blindly, with no traders involved at all, returned +0.0211. Along the way I found four bugs in my own methodology, each of which had produced a confident false positive — including a strategy with a 100% win rate over 36 trades whose real edge over blind entry was 0.8%.

A confident wrong answer is more expensive than no answer. That is the standard I hold my own work to before I hand it to anyone else.

---

## Stack

Python · FastAPI · Flask · pandas · BeautifulSoup / Scrapy / Selenium · Claude API · Docker · pytest · PostgreSQL · SQLite · Railway

---

## Background

I came to the United States, founded and ran a moving company from nothing — hiring, dispatch, sales, ~200 jobs with 60% of them arriving by referral — before moving into automation full time. That is why I scope work around what a business actually needs rather than what is technically interesting: I have been the person on the other side of the invoice.

Registered vendor on SAM.gov, Cal eProcure, PlanetBids and San Diego County BuyNet.
