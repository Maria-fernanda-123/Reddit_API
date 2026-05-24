# Reddit Brand Monitor

A Python script to collect and analyze public Reddit posts 
mentioning specific brands for market research purposes.

## Purpose

This read-only script searches public Reddit posts to analyze 
brand sentiment and reviews. Data is collected for visualization 
in Power BI dashboards.

## How it works

- Searches public posts by brand name
- Collects post titles, text, and scores
- Organizes data with Pandas
- Exports to Excel for Power BI analysis

## Usage

```python
python scraper.py
```

## Libraries used

- PRAW — Reddit API access
- Pandas — data organization
- OpenPyXL — Excel export

## Data collected

- Post title
- Post text
- Score
- Date

## Notes

- Read-only access — no posting or interaction
- Only public data is collected
- Data used for market research analysis only
