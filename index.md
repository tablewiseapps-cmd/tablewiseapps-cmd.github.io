---
layout: page
title: Data tools on Apify
permalink: /
---

tablewise builds small, focused scrapers that run on [Apify](https://apify.com/tablewise).
You pay per result: only for the rows you get, plus $0.0005 per run, and
nothing for empty or failed results. Every tool runs from the Apify web
console, from code (Python or JavaScript), from n8n, Make or Zapier, or from
an AI agent through the [Apify MCP server](https://docs.apify.com/mcp).

## The tools

### Website Email & Contact Scraper

Give it a list of websites and get back, for each one, the emails, phone
numbers, social profiles and contact page it publishes.

- **Price:** $8 per 1,000 websites where it finds an email or a phone.
  Websites with nothing found are free.
- **Try a ready example:** [emails and phones from a list of websites](https://apify.com/tablewise/website-email-contact-scraper/examples/extract-emails-and-phones-from-websites) ·
  [company social profiles](https://apify.com/tablewise/website-email-contact-scraper/examples/company-social-profiles-from-websites)
- [Apify page](https://apify.com/tablewise/website-email-contact-scraper) ·
  [code examples](https://github.com/tablewiseapps-cmd/apify-scrapers-examples/tree/main/website-email-contact-scraper)

### YouTube Transcript & Subtitles Scraper

Transcripts and subtitles of YouTube videos as plain text, timed segments,
SRT or VTT, with the video details. Give it video links or IDs, or a
channel to take its newest videos.

- **Price:** $5 per 1,000 videos.
- **Try a ready example:** [transcripts as plain text](https://apify.com/tablewise/youtube-transcript-scraper/examples/youtube-video-transcripts-as-text) ·
  [subtitles as SRT and VTT](https://apify.com/tablewise/youtube-transcript-scraper/examples/download-youtube-subtitles-as-srt)
- [Apify page](https://apify.com/tablewise/youtube-transcript-scraper) ·
  [code examples](https://github.com/tablewiseapps-cmd/apify-scrapers-examples/tree/main/youtube-transcript-scraper)

### Google Hotels Scraper

Hotels and rentals from Google Hotels for a destination and dates: price per
night, total with taxes, rating and deals.

- **Price:** $4 per 1,000 properties.
- **Try a ready example:** [hotel prices in Lisbon](https://apify.com/tablewise/google-hotels-scraper/examples/compare-hotel-prices-in-lisbon) ·
  [New York prices by booking site](https://apify.com/tablewise/google-hotels-scraper/examples/new-york-hotel-prices-by-booking-site)
- [Apify page](https://apify.com/tablewise/google-hotels-scraper) ·
  [code examples](https://github.com/tablewiseapps-cmd/apify-scrapers-examples/tree/main/google-hotels-scraper)

### Tennis Results & Odds Scraper

ATP, WTA, Challenger and ITF results and fixtures, with scores by set and
pre-match odds.

- **Price:** $5 per 1,000 matches.
- **Try a ready example:** [latest ATP results](https://apify.com/tablewise/tennis-results-scraper/examples/latest-atp-tennis-results-with-odds) ·
  [latest WTA results](https://apify.com/tablewise/tennis-results-scraper/examples/latest-wta-tennis-results-with-odds)
- [Apify page](https://apify.com/tablewise/tennis-results-scraper) ·
  [code examples](https://github.com/tablewiseapps-cmd/apify-scrapers-examples/tree/main/tennis-results-scraper)

### Semrush Domain Metrics Scraper

Semrush Authority Score, backlinks, referring domains and monthly visits for
a list of domains, without a Semrush account.

- **Price:** $5 per 1,000 domains.
- **Try a ready example:** [Authority Score for a list of domains](https://apify.com/tablewise/semrush-domain-metrics-scraper/examples/bulk-semrush-authority-score-checker) ·
  [compare competitors' traffic](https://apify.com/tablewise/semrush-domain-metrics-scraper/examples/compare-competitor-website-traffic)
- [Apify page](https://apify.com/tablewise/semrush-domain-metrics-scraper) ·
  [code examples](https://github.com/tablewiseapps-cmd/apify-scrapers-examples/tree/main/semrush-domain-metrics-scraper)

More tools are on the [tablewise page on Apify](https://apify.com/tablewise).

## Code examples

The [apify-scrapers-examples](https://github.com/tablewiseapps-cmd/apify-scrapers-examples)
repository has a Python and a JavaScript example for each tool, tested
against the live Actors, with a sample of real output. MIT licensed.

## Contact

Questions, bugs or a site you need: open an issue in the
[examples repository](https://github.com/tablewiseapps-cmd/apify-scrapers-examples/issues)
or in the Issues tab of the tool's Apify page.
