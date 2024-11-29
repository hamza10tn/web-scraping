# Google Maps Scraper

This is simple scraper that uses Playwright to extract data from Google Maps. 

This scrapit is easy to customize.

check both Excel & CSV files (google_maps_data) to see how final data will look like. 

## To Install:
- (Optional: create & activate a virtual environment) `virtualenv venv`, then `source venv/bin/activate`

- `pip install -r requirements.txt`
- `playwright install chromium`

## to Run:
### A single search:
- `python3 main.py -s=<what & where to search for> -t=<how many>`
- exemple: `python main.py -s "photographer in London" -t 50`
