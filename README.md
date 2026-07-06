# Hi, I'm Daniil

Data Analytics student at University of Gdańsk (Computer Science, BSc), based in Gdynia, Poland.

Most of what I do comes down to taking something people redo by hand every week and writing a script that does it instead.

---

## Tech Stack

| Category | Tools |
|---|---|
| Languages | Python, SQL, JavaScript |
| Data & Analytics | Pandas, NumPy, Matplotlib, Seaborn, Statsmodels |
| Databases | PostgreSQL, relational databases |
| Spreadsheets | Excel (Power Query, Pivot Tables) |
| AI Tools | ChatGPT, Claude — mostly for prompt engineering and automating workflows |
| Other | Git, VS Code |

---

## Work Experience

**Technical Specialist, Media Buying Department** — [Zorka Agency](https://zorka.com/), Gdańsk (Sep 2024 – present)
- Built a Python + Excel (Power Query) pipeline that puts out 20+ weekly reports with almost no manual work
- Set up dynamic generation for 15–20 individual client reports, which cut prep time by roughly 80%
- Dug through advertising campaign data to track KPIs
- Used Claude to double-check my work and bounce ideas off of for tasks

---

## Featured Project

### [Media Buying Report Automation](https://github.com/Danaka123/media-buying-report-automation)
Python, openpyxl, Pandas — internal reporting tool

Built a set of scripts that turn raw daily exports from multiple ad networks and partners into ready-to-send client reports, replacing what used to be manual copy-pasting across a dozen partners every day.

What I did:
- Wrote parsers for each partner's raw export format, since every source had its own column layout and file-naming conventions
- Automatically split combined reports by agency, partner, or campaign, then generated a separate Excel file per one with consistent sheet structure (Overview, P360, In-app, Fraud)
- Handled cases where the same campaign has separate iOS/Android exports by matching them into a single grouped report
- Preserved formatting (column widths, fonts, cell styles) when copying data into the output files, so reports stayed visually consistent with the originals
- Built a mapping system to match raw data source IDs to partner names for reports that didn't include partner names directly
- Ran the whole batch daily, generating 20+ per-partner reports in the time it used to take to prepare one manually

---

### [Telegram Ads CPV Benchmark Analysis](https://github.com/Danaka123/Data-Analytics)
Python, Pandas, Seaborn — real advertising data

Looked at a dataset of Telegram channel ad placements for a performance marketing agency and built a Cost Per View (CPV) benchmark across categories, formats, and audience tiers.

What I did:
- Pulled together dozens of raw tables from different sources into one dataset with Pandas (`merge`, `concat`)
- Cleaned up messy data: stripped currency symbols, fixed data types, and recovered 86% of missing CPV values by recalculating `CPV = spend / actual_reach`
- Split channels into four audience tiers (Low, Medium, Large, Very Large) so comparisons were fair
- Charted median vs. best CPV by format, category, and tier
- Wrote up findings with recommendations for the media buying team

Medium-sized channels (32k–317k subscribers) with ERR above 12% had the lowest CPV, by a decent margin.

---

### [Google Sheets to Database ETL Pipeline](https://github.com/Danaka123/google-sheets-etl-pipeline)
Python, Google Sheets API, PostgreSQL

Built a daily pipeline that pulls raw data from a Google Sheet, parses it in Python, and loads it into a database, replacing a manual copy-paste routine that used to eat up time every morning.

What I did:
- Connected to Google Sheets via API to pull fresh data on a schedule
- Parsed and cleaned the raw sheet data (types, formatting, missing fields) before loading it further
- Loaded the processed data into PostgreSQL, with the pipeline re-running daily to keep reports current
- Set it up so the whole thing runs unattended once scheduled

---

### [Unity Ads Performance Data Collector](https://github.com/Danaka123/unity-ads-api-collector)
Python, Unity Ads API

Wrote a script that pulls campaign performance data directly from Unity Ads via API key instead of exporting it manually from the dashboard.

What I did:
- Authenticated and queried the Unity Ads API for impressions, clicks, installs, and CPI
- Parsed the API responses into a structured format for further analysis
- Set up the collector to run on a schedule so the data stays up to date without manual pulls

---

## Education & Courses

- BSc in Computer Science — University of Gdańsk (Sep 2025 – present)
- IT Technician diploma — ZSChiE, Gdańsk (2020 – 2025)
- Statistics in Python — Stepik workshop (Jan–Feb 2026)

---

## Languages

Russian — native | Polish — B2 | English — B1

---

## Let's connect

[LinkedIn](https://www.linkedin.com/in/daniil-zayats-aabb01403/) · [Email](mailto:daniilzayatss@gmail.com)

---

Looking for a Data Analyst internship around Trójmiasto (Gdańsk, Gdynia, Sopot). Open to remote too.
