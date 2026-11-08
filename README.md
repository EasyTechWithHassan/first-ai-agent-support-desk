# Build your first AI agent: support-desk exercise

The files from the Daily AI Minute video **"Build Your First AI Agent in 5 Minutes"**.

All data here is fictional demo data (22 made-up support tickets). No real customers, people or systems.

## Files

| File | What it is |
|---|---|
| `support-tickets-demo.csv` | The messy input file: 22 rows, 2 exact duplicates, one blank priority |
| `request.txt` | The full request (prompt) used in the video: give it to Claude with the CSV attached |
| `revision-request.txt` | The one focused follow-up request used to improve the dashboard |
| `support-tickets-cleaned.csv` | The cleaned file Claude produced (20 unique tickets, blank priority marked "Needs review") |
| `support-desk-dashboard.html` | The finished self-contained dashboard (open it in any browser, no internet needed) |

## Try it

1. Open Claude, attach `support-tickets-demo.csv`.
2. Paste the text of `request.txt` and send it.
3. Check the totals against the file: 22 rows, 2 exact duplicates removed, 20 unique tickets, 16 still open on the worklist.
4. Use `revision-request.txt` for one focused improvement, keeping the data and logic unchanged.

Compare your result with `support-tickets-cleaned.csv` and `support-desk-dashboard.html`.
