# Coronawhy Spanish Flu Scraper
This repo contains two "scrapers" of news articles news articles in PDF format issued between 1918 and 1920 in the United States.  The queries in these notebooks are currently written to search for articles on "spanish influenza" (and associated keywords), though they can easily be repurposed for other search terms.

Databases scraped include:
* [Library of Congress - Chronicling America](https://chroniclingamerica.loc.gov/) - complete
* [HRVH database](https://news.hrvh.org/veridian/?a=q&e=-------en-20--1--txt-txIN-------) - currently incomplete

As the textual data from these sources isn't as good as I wanted it to be, a notebook converting PDFs to image files (so they can be fed into an OCR) is also included.

Further work will include:
- Inclusion of the OCR in the repo
- Completion of the HRVH scraper 
- Deduplication of HRVH v. Library of Congress data
