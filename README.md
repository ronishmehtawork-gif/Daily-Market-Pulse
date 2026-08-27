# Daily Market Pulse

Standing task setup for Artha Equities' daily market report, run unattended via Cowork's Scheduled Task feature.

See [`standing-task-prompt.md`](./standing-task-prompt.md) for the full task prompt. Before scheduling, fill in the two bracketed Google Sheet links (watchlist and holdings) in that file, then paste it into **Cowork → Scheduled → New Task → Set up manually**.

Each run produces `Market_Pulse_{YYYY-MM-DD}.docx` in a **Market Pulse** folder on Ronish's Drive.
