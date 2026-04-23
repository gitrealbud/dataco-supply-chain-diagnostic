# DataCo Supply Chain Optimization Diagnostic

### Data Source
This analysis was performed on the **DataCo Smart Supply Chain** dataset:

→ [Kaggle: DataCo Smart Supply Chain for Big Data Analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

**Exposing $2.05M in hidden leakage — Late Deliveries, Status Chaos & Profit Signal Contamination**

Deep diagnostic analysis of 180,519 orders from DataCo Global's logistics operation. Identified systemic failures in order status management, delivery execution, and contaminated profit signals.

### Key Findings
- Reconstructed true profit signal: **$3.88M phantom loss → $905 real loss**
- **95,000 orders** (52.41%) stuck >90 days → **$2.05M** locked in blind capital
- Late delivery rate: **54.83%** overall | **95%+** on First Class
- 23.68% of orders require 2–4 day escalation

The system was blind. We made it see.

---

### Repository Contents

| File / Folder                          | Description |
|----------------------------------------|-----------|
| `DataCo_Global_Supply_Chain_Diagnostic.pptx` | Final stakeholder presentation deck (12 slides) with speaker notes |
| `LICENSE`                              | Free use with explicit permission for commercial/public use |
| `README.md`                            | This file |
| `/powerbi/`                            | Power BI dashboard file + DAX measures |
| `/scripts/`                            | Python/Pandas cleaning scripts used in initial analysis |
| `/images/`                             | Original dashboard screenshots and chart exports |
| `Full Report.txt`                      | Detailed written stakeholder report |
| `DataCo Video Presentation.docx`       | Full video script used for narration |

### Project Overview

This diagnostic was performed to surface immediately actionable control gaps for the Head of Site Operations at DataCo Global.

**Core Issues Exposed:**
- **Status Chaos**: 95K shipped orders stuck in non-final statuses for years
- **Delivery Failure**: Systemic late shipments, especially catastrophic First Class performance
- **Profit Signal Contamination**: Extreme discount-driven volatility made the original "Benefit per order" field unreliable

**Recommendations Implemented in Deck:**
- Mandatory real-time status updates (Priority 1)
- Tiered escalation framework (Glentel model)
- Auto-cancellation triggers for aged orders
- Minimum margin guardrails on discounts

### How to Use

1. Open `DataCo_Global_Supply_Chain_Diagnostic.pptx` for the stakeholder-ready deck
2. Review `Full Report.txt` for deeper methodology and numbers
3. Use the presentation + speaker notes when presenting to leadership

### License

Free for personal and educational use.  
**Commercial use, public presentations, or derivative works require explicit written permission** from FolkForgeHQ.

See [LICENSE](LICENSE) for full details.

---

**Built with density.**  
Questions or collaboration? Reach out on X: [@FolkForgeHQ](https://x.com/FolkForgeHQ)
