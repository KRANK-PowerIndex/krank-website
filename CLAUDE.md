# KRANK Weekly Update Instructions

## Google Sheet
The tracker sheet URL is stored in `krank.config`. Read the SHEET_URL from that file.

## Weekly Update Task
When asked to "update the site" or "weekly update":
1. Read the SHEET_URL from krank.config
2. Download the Google Sheet as CSV (replace /edit with /export?format=csv&gid=0)
3. Read Latest Followers from column AB, Latest Fan Score from column AD, celebrity name from column B
4. Match each celebrity to index.html by exact name
5. Update the followers and fanActivity fields for each match
6. Recalculate all KRANK scores
7. git add index.html
8. git commit -m "Weekly update – [today's date]"
9. git push

## Notes
- Followers are in millions (5.2 = 5,200,000)
- Fan Activity score is 0–100
- Only update celebrities that have data filled in
