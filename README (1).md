# Fee Desk - AI Mutual Fund Expense Ratio Impact Calculator

CLA-2 Mini Project, MBA 605 AI in Business, Paari School of Business, SRM University-AP.
T. Keerthi (AP25322130052).

**All data is synthetic.** Schemes, AMCs and clients are invented; no real investor data.

`index.html` is the whole dashboard: one self-contained file, no dependencies, no network calls.
Open it by double-clicking, or use the GitHub Pages link. It answers:

- what client holdings cost in expense ratios, in rupees;
- which Regular-plan holdings to move to Direct, now or later, given the exit load (before tax);
- which active schemes beat their index fund after fees;
- which schemes changed their TER by 25 bps or more in a year;
- which SIPs have lapsed or gone dormant;
- the cost of a higher TER on any SIP or lump sum, at a return you assume.

Every figure comes from a rule engine written twice (Python and JavaScript) and reconciled field by field.
`sample_month_2026-11.csv` is a synthetic next month for demonstrating the Update Data tab.
No API key is used anywhere in this page.
