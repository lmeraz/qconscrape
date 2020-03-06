# QCON Scrape project
Qcon uses the following url pattern `https://www.infoq.com/conferences/qconsf{yr}` where year is in YYYY format. For example: `https://www.infoq.com/conferences/qconsf2019/`

## Requirement
Scrape the 5 past years of QCON talks and ouput to CSV format. with following columns
1. Name of talk
2. Speaker Name
3. Track
4. URL link to talk (if talk is published)

### Bonus
If you follow the link to the published talk you can gather additional details like
1. Summary
2. Bio
3. Transcript (some years)

## Getting started
1. Have virtualvenv installed
2. clone repo
3. in repo directory `virtualvenv .venv`
4. in repo directory `source .venv/bin/activate` and any time you work on the project
5. in repo directory `pip install -r requirements.txt`

