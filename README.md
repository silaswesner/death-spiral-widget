[README.md](https://github.com/user-attachments/files/28022576/README.md)
# 🌀 Peloton Death Spiral — Interactive Widget

> An interactive cost accounting case study built for **UNC Kenan-Flagler Business School**  
> Demonstrates the **demand-driven death spiral** using real data from Peloton's FY2025 10-K

**[▶ View Live Widget](https://silaswesner.github.io/peloton-death-spiral/)**

---

## What Is the Death Spiral?

The **cost allocation death spiral** occurs when declining volume forces fixed costs to be spread over fewer units, raising the per-unit cost. Higher costs reduce competitiveness, driving further volume declines — and so on, in a self-reinforcing loop.

> *"As output volume decreases, fixed capacity costs must be spread over a smaller number of units, increasing the amount allocated to each unit. Increase in unit costs can lead to further reductions in volume and on and on into a death spiral."*  
> — UNC Kenan-Flagler, Introduction to the Death Spiral

Peloton is a textbook **demand-driven** case: post-pandemic subscriber losses forced fixed platform costs onto a shrinking base, causing per-subscriber costs to spike even as total spending was cut.

---

## Widget Features

| Section | Description |
|---|---|
| **KPI Cards** | Snapshot of FY2025 key metrics: revenue, subscribers, net loss, churn, gross margins |
| **Revenue Trend Chart** | FY2020–FY2025 total revenue with hardware vs. subscription breakdown |
| **Subscriber Trend Chart** | Paid connected fitness subscriber count across all fiscal years |
| **Net Income Chart** | Annual profit/loss showing the depth of the spiral and partial recovery |
| **Fixed Cost Per Subscriber** | The core death spiral metric — fixed overhead ÷ paid subscribers by year |
| **Spiral Flow Diagram** | Step-by-step visual of how Peloton's demand-driven spiral unfolded |
| **Historical Data Table** | Full FY2020–FY2025 financials with color-coded cells |
| **Interactive Calculator** | Adjust fixed costs, subscribers, price, and variable costs via sliders to model spiral conditions in real time |

---

## Data Sources

All financial data is sourced directly from **Peloton Interactive, Inc. — Annual Report on Form 10-K, Fiscal Year Ended June 30, 2025** (filed August 7, 2025).

| Metric | 10-K Location |
|---|---|
| Revenue (FY2020–FY2025) | Consolidated Statements of Operations |
| Paid Connected Fitness Subscriptions | Key Operational & Financial Metrics table |
| Avg. Monthly Connected Fitness Churn | Key Operational & Financial Metrics table |
| Subscription Gross Margin (69.1%) | Segment Information, Note 17 |
| CF Products Gross Margin (13.6%) | MD&A — Cost of Revenue |
| Operating Expenses (S&M, G&A, R&D) | Consolidated Statements of Operations |
| Net Loss / Net Income | Consolidated Statements of Operations |
| Adjusted EBITDA ($403.6M) | Non-GAAP Reconciliation Table |
| Free Cash Flow ($323.7M) | Non-GAAP FCF Reconciliation |
| Subscription Cost of Revenue | Consolidated Statements of Operations |

> **Note:** The "Fixed Cost Per Subscriber" metric is a derived calculation:  
> `(Subscription CoR + S&M + G&A + R&D) ÷ Ending Paid CF Subscribers`  
> This is not a figure reported directly in the 10-K but is computed from reported line items to illustrate the death spiral mechanic.

---

## Key Numbers (FY2025)

| Metric | Value |
|---|---|
| Total Revenue | $2,490.8M |
| Paid CF Subscriptions (end of year) | 2,799,943 |
| Avg. Monthly CF Churn | 1.6% |
| Subscription Gross Margin | 69.1% |
| CF Products Gross Margin | 13.6% |
| Net Loss | $(118.9)M |
| Adjusted EBITDA | $403.6M |
| Free Cash Flow | $323.7M |

---

## The Spiral in Numbers

| Fiscal Year | Paid Subscribers | Est. Fixed Cost / Sub | Net Income |
|---|---|---|---|
| FY2021 (Peak) | 2,330,000 | ~$412 | $(189.0)M |
| FY2022 | 2,968,000 | ~$598 | $(2,827.7)M |
| FY2023 | 3,082,000 | ~$771 | $(1,261.6)M |
| FY2024 | 2,981,000 | ~$727 | $(289.7)M |
| **FY2025** | **2,799,943** | **~$607** | **$(118.9)M** |

The declining subscriber count combined with a large fixed cost base is the textbook death spiral mechanism. The improvement in FY2024–FY2025 reflects aggressive restructuring (layoffs, facility closures, hardware outsourcing) rather than subscriber recovery.

---

## Course Context

This widget was created as a teaching aid for the **Death Spiral** module in cost accounting at UNC Kenan-Flagler Business School. It illustrates concepts including:

- Demand-driven vs. supply-driven death spirals
- Fixed cost allocation economics
- Practical vs. actual overhead rates
- The relationship between volume, unit cost, and competitive pricing

Related course cases covered in the same module:
- **Internal Telecom Example** — demand-driven spiral from user defection
- **Manic Broadcasting** — supply-driven spiral from cost allocation gaming
- **Clay Sprays / Coronas** — acquisition to absorb fixed overhead

---

## Tech Stack

- **Pure HTML/CSS/JavaScript** — no build tools, no dependencies to install
- **[Chart.js 4.4](https://www.chartjs.org/)** — loaded via CDN for all charts
- **GitHub Pages** — static hosting, zero cost

---

## Running Locally

No server required. Just open the file in any browser:

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/peloton-death-spiral.git

# Open in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## License

For educational use. Financial data is sourced from Peloton's publicly filed 10-K and is used solely for academic illustration purposes.

---

*Built with ❤️ for UNC Kenan-Flagler Business School · Cost Accounting · May 2026*
