Business Overview — Excel-Backed 5-Year Trend Dashboard

What’s inside
- index.html  (interactive dashboard)
- data/       (4 sample Excel files the dashboard reads)
    - population.xlsx
    - avg_years_service.xlsx
    - avg_time_in_grade.xlsx
    - likely_to_retire.xlsx

How to run (recommended)
Browsers often block reading local files via fetch() when opened directly (file://).
Use a tiny local server from this folder:

Option A (Python):
  1) Open a terminal in this folder
  2) Run:  python -m http.server 8000
  3) Visit: http://localhost:8000

Option B (VS Code):
  Use the “Live Server” extension and open index.html.

No server? Still works:
- Open index.html directly and use the “Upload Excel Files” button.
- Keep the filenames the same so it auto-maps them.


Update:
- The included Excel files now contain MONTHLY points (last 60 months). The slider still controls a 3–5 YEAR window (36–60 months).
