# UltraTech Cement – Financial Model & Acquisition Analysis

**Question:** Did UltraTech overpay for its South India expansion (India Cements, Kesoram), and what is the stock worth today?

**Status:** Three-statement model ✅ · Acquisition analysis ✅ · WACC & DCF valuation 🔄 in progress · Scenarios 🔄 in progress

![Cover](images/cover.png)

## Key findings so far

**Acquisition test**
- India Cements cost **₹928 Cr per mtpa**, **55% above** UltraTech's own ~₹600 Cr/mtpa build cost (a ₹4,739 Cr premium), and above build cost under every assumption tested.
- Kesoram (₹707 Cr/mtpa) was fairly priced: 18% above UltraTech's build cost, 13% below the industry estimate.
- India Cements needs **₹1,978/t EBITDA** to earn its cost of capital, 1.8× UltraTech's own ₹1,104/t. Bear/base/bull turnaround scenarios give **2–6% ROIC** vs an 11.5% hurdle.
- Closing the gap through South pricing would need an **8–10% permanent price rise** on UltraTech's other South plants.
- **Verdict:** UltraTech paid for speed and South market share, and overpaid in financial terms.

**Forecast (FY26A → FY31E)**

| Metric | FY26A | FY31E |
|---|---|---|
| Capacity (mtpa) | 191.4 | 261.1 |
| Revenue (₹ Cr) | 88,512 | 1,43,672 |
| Operating EBITDA margin | 19.2% | 16.9% |
| EBITDA per tonne (₹/t) | 1,104 | 1,068 |
| Cash from operations (₹ Cr) | 15,316 | 19,725 |
| Net debt / EBITDA | 1.04x | 0.06x |

- ₹47,400 Cr of capex for ~70 mtpa of new capacity, funded ~1.9× by operating cash flow.
- Margin pressure of ~240 bps as raw-material inflation (+5% p.a.) outpaces pricing (+2% p.a.).

## Model structure

| Sheet | What it does |
|---|---|
| Cover | Summary, key outputs, model status |
| IS / BS / CF | Integrated three statements, FY22A–FY31E |
| Ops_Data | Historical operating data from investor presentations |
| Ops_Forecast | Driver-based engine: capacity → utilisation → volume → ₹/t |
| Capex_DA | Growth + maintenance capex, depreciation, PPE roll-forward |
| WC | Receivable, inventory and payable days |
| Debt | Borrowings, repayments, interest on average debt |
| Fin_Inputs | Tax, other income, NCI, dividend assumptions |
| Acquisition | EV per tonne, buy vs build, ROIC, breakeven and scenario tests |
| Check | 13 integrity checks rolled into one MODEL OK flag |

## Modelling standards
- Colour code: **blue** = input, **black** = formula, **green** = link from another sheet
- One formula per row across all years; no hardcoded numbers inside formulas
- Balance sheet balances in every year; cash flow closing cash ties to the balance sheet
- Every input has a source in the model's source column

![Acquisition analysis](images/acquisition.png)

## Sources
- UltraTech Cement annual reports FY22–FY26 and Q4 investor presentations FY23–FY26
- India Cements annual reports FY24–FY26
- Damodaran country risk premiums; CRISIL and ICRA industry reports

## Author
**Ankit Jandial** – B.Tech, Punjab Engineering College · [LinkedIn](https://linkedin.com/in/ankit-jandial)

*For educational purposes only; not investment advice.*
