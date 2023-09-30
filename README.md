# LinkedIn-Scraper
Python Scrapy spiders that scrape job data & people and company profiles from [LinkedIn.com](https://www.linkedin.com/). 

This Scrapy project contains 3 seperate spiders:

| Spider  |      Description      |
|----------|-------------|
| `linkedin_people_profile` |  Scrapes people data from LinkedIn people profile pages. | 
| `linkedin_jobs` |  Scrapes job data from LinkedIn (https://www.linkedin.com/jobs/search) | 
| `linkedin_company_profile` |  Scrapes company data from LinkedIn company profile pages. | 

## ScrapeOps Proxy
This LinkedIn spider uses [ScrapeOps Proxy](https://scrapeops.io/proxy-aggregator/) as the proxy solution. ScrapeOps has a free plan that allows you to make up to 1,000 requests per month which makes it ideal for the development phase, but can be easily scaled up to millions of pages per month if needs be.

You can [sign up for a free API key here](https://scrapeops.io/app/register/main).
