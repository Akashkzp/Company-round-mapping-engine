# Company Intel + Round Mapping Engine

This is a single-file demo that implements the assignment shown in the screenshots:

- Company Intel block (heuristic)
- Round Mapping Engine (dynamic mapping based on company size + skills)
- "Why this round matters" under every round
- Persisted history (stored in `localStorage`)
- Note: "Demo Mode: Company intel generated heuristically."

## Run

- Open `index.html` in your browser (double‑click it).

## Test scenarios

- **Enterprise + DSA/Core CS**
  - Company: `Amazon`
  - Skills: `DSA`, `Core CS`
  - Expected: 4 rounds (Online Test → Technical → Tech+Projects → HR)

- **Startup + React/Node**
  - Company: `SomeNewStartup`
  - Skills: `React`, `Node`
  - Expected: 3 rounds (Practical coding → System discussion → Culture fit)

## Notes

- No external scraping is used.
- History persists inside the browser (per-device).

