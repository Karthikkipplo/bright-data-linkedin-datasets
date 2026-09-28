# Bright Data LinkedIn Datasets: Pricing, Fields and Competitors

Bright Data sells five ready-made LinkedIn datasets, Profiles, Company, Jobs, Posts and Profiles Jobs Listings, with 908.6M+ records in total. A quick reference to their fields, pricing, delivery options and competitors.

> *Not affiliated with Bright Data and not an official Kipplo repository. Maintained independently by Karthik V, who works in marketing at Kipplo. Bright Data figures are from its website, and other companies' details are from their own websites, as of 28 September 2026. They may change.*

## What are Bright Data's LinkedIn datasets?

They are pre-collected tables of public LinkedIn data. Instead of building and maintaining your own collection pipeline, you buy a prepared dataset, whole or filtered down to the records you need, once or on a refresh schedule.

Each dataset has demo data in JSON or CSV so you can see the fields before buying.

## What's inside each dataset?

| Dataset | Records | Fields | What a record includes |
|---|---|---|---|
| Profiles | 674.6M+ | 42 | Name, city, country, current position and company, about, posts, experience, education, skills and more |
| Company | 30.2M+ | 36 | ID, name, country, locations, LinkedIn followers, employees on LinkedIn, about, specialties and more |
| Jobs | 72.4M+ | Not stated | Job title, company, location, seniority level, job summary, direct application links, insights into application numbers and more |
| Posts | 130M+ | 37 | Post text, user ID, posting date, headline, likes and comments, images, videos, hashtags, embedded links and more |
| Profiles Jobs Listings | Not stated | Not stated | URL, LinkedIn ID, name, about, position, optional jobs, country code, experience and more |

## Compliance and updates

Bright Data says its data is ethically obtained and compliant with privacy laws, and its site shows GDPR, ISO and SOC badges. You can buy a dataset once or have it refreshed bi-annually, quarterly or monthly, and you can choose to receive only new or updated records.

## How much does the Bright Data LinkedIn dataset cost?

Pricing is per record and starts at $250 for 100K records. Larger orders cost less per record: 1M records cost $2,000 and 5M cost $5,000. For more than 20M records, Bright Data offers discounts of up to 90% through its marketplace.

Refresh plans cut the price of each delivery by 25% (bi-annual), 50% (quarterly) or 80% (monthly). Based on Bright Data's displayed pricing, 1M records refreshed quarterly costs $1,000 per delivery, or $4,000 a year.

## How do you receive the data?

| Category | Available options |
|---|---|
| **Formats** | JSON, NDJSON, JSON Lines, CSV, XLSX, Parquet (optional .gz compression) |
| **Delivery** | Snowflake, Amazon S3, Google Cloud, Azure, SFTP |
| **API** | Download dataset snapshots by API |
| **Code examples** | Python, Node.js, cURL, PHP, Go, Java and Ruby |

## What to check before you buy

A few things to check before ordering any LinkedIn dataset:

- How many records do you need for your own segment? A provider with hundreds of millions of records may still have far fewer for your geography, industry, company size or role.
- Check field fill rates, not just field counts. A dataset can list dozens of fields without every record having a value for each one, so download the sample and see how often the fields you need are filled.
- If you plan to email or call people, check how many records actually include a business email or phone number. Don't assume every profile has them.
- Is a one-time snapshot enough, or will you need regular updates?
- Will the files arrive in a format and location your team already uses?

## Bright Data competitors

Several other companies offer professional profile, company and job data:

- **[Kipplo](https://www.kipplo.com/datasets/linkedin-datasets/)**: LinkedIn Profile, Company and Job Posting datasets, with verified contact data attached to the rows where available. You tell Kipplo the segment you need and see the matching row count and price before you commit. You can then filter the data in Data Explorer before spending a credit, export it as CSV, Excel, JSON, XML or SQL, query it through the API, or have it delivered to your own cloud on request. Pricing is per row.
- **Coresignal**: company, employee and job posting data, available as datasets in JSONL, Parquet or CSV, or through APIs. API plans are listed on its pricing page, with a 7-day free trial.
- **Apify**: its Store lists ready-made LinkedIn scrapers built by independent developers, covering profiles, companies and job postings. You run them on Apify, and pricing depends on the scraper you choose.
- **Crustdata**: people and company data, including posts and engagement signals, delivered as bulk datasets refreshed monthly or through APIs, with business email enrichment. Samples are available on request.
- **People Data Labs**: person, company and job posting data through APIs and bulk data licences. A free plan includes up to 100 credits a month, and contact data is included on paid plans starting at $98 a month.

## Sources

- Bright Data LinkedIn datasets: [brightdata.com/products/datasets/linkedin](https://brightdata.com/products/datasets/linkedin) (and the `/profiles`, `/company`, `/jobs` and `/posts` pages)
- Kipplo LinkedIn datasets: [kipplo.com/datasets/linkedin-datasets](https://www.kipplo.com/datasets/linkedin-datasets/)
