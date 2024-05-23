# legitimoose-world-data
Automatically updating world data snapshots from the `legitimoose.com` server's worlds.

## About
- Contains `.csv` and `.json` files containing world data
- Includes:
  - UUID
  - World Name as a string JSON and as a string without formatting
  - Description as a string JSON and as a string without formatting
  - Item used for the icon
  - Owner as a string JSON and a string without formatting
  - Visits
  - Votes
  - Date created in Unix time
  - Resource pack enabled?
  - Player count (-1 if offline)
- Uses [legitimoose-world-scraper](https://github.com/unin-able/legitimoose-world-scraper) to scrape and upload the data
