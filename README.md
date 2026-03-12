# TALO Log House — Catalog Request Data Analysis

Interactive HTML reports analyzing 5 years of catalog request data (2021–2025) for TALO Log House.

**Portal:** [https://adachitalo.github.io/loghouseData/](https://adachitalo.github.io/loghouseData/)

## Reports

### Overall Analysis (7 reports)

| File | Description |
|------|-------------|
| [catalog-analysis-report.html](./catalog-analysis-report.html) | Year-over-year catalog request trends, regional breakdown, and customer attributes |
| [hot-customer-analysis.html](./hot-customer-analysis.html) | Hot customer counts and order rates by agency and TALO staff (2021–2025) |
| [prefecture-trends-analysis.html](./prefecture-trends-analysis.html) | Prefectural trends for current address vs. planned construction site |
| [talo-hq-analysis.html](./talo-hq-analysis.html) | TALO HQ (direct) performance analysis |
| [gap-analysis.html](./gap-analysis.html) | Budget vs. actual construction cost gap analysis (outlier-corrected) |
| [scoring-analysis.html](./scoring-analysis.html) | Conversion prediction scoring model (D–S rank, 32x lift between D and A) |
| [price-barrier-analysis.html](./price-barrier-analysis.html) | Price barrier analysis: structural shift in buyer demographics due to 64% cost increase |

### Agency Reports (6 reports)

| File | Agency | Area |
|------|--------|------|
| [nh-agency-analysis.html](./nh-agency-analysis.html) | NH | Chiba |
| [k10-agency-analysis.html](./k10-agency-analysis.html) | K10 | Kinki |
| [hide-agency-analysis.html](./hide-agency-analysis.html) | HIDE | Shizuoka |
| [fuji-agency-analysis.html](./fuji-agency-analysis.html) | FUJI | Nagano |
| [cnd-agency-analysis.html](./cnd-agency-analysis.html) | CND | Kagoshima |
| [act-agency-analysis.html](./act-agency-analysis.html) | ACT | Yamanashi/Nagano |

## How to View

Open any `.html` file directly in a browser — no server required. Charts are rendered with Chart.js.

Or use the **[index.html](./index.html)** portal page for card-based navigation to all reports.

## Data

- Source: Catalog request records (14,714 entries, 2021–2025) + EUDS customer data (9,593 entries)
- **Note:** Raw data files are not included in this repository.

---
*Generated with Claude (Cowork)*
