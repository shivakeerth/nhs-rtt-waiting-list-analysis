# NHS Referral-to-Treatment Waiting List Performance Analysis

## Project status
In progress — Day 1 project setup completed.

## Project overview
This project analyses NHS England consultant-led Referral to Treatment (RTT)
waiting-time data to identify waiting-list pressure across hospital providers
and treatment specialties.

## Business problem
NHS operational and performance teams need reliable reporting that shows:

- the size of the elective-care waiting list;
- the proportion of pathways within the 18-week standard;
- providers and specialties under the greatest pressure;
- changes in waiting-list performance over time; and
- where operational attention may be required.

## Main analytical question
How effectively are NHS providers managing elective-care waiting lists, and
which providers or treatment specialties show the greatest backlog and
long-wait pressure?

## Planned analysis
1. Inspect and document the source data.
2. Clean and validate the data using Python.
3. Create reporting tables and KPI queries using SQL.
4. Build provider, specialty and time-trend analysis.
5. Develop a Tableau dashboard.
6. Produce a stakeholder briefing with evidence-based recommendations.

## Planned KPIs
- Total incomplete pathways
- Percentage of pathways within 18 weeks
- Pathways waiting more than 18 weeks
- Long-wait volume
- Provider ranking
- Treatment-specialty ranking
- Monthly waiting-list change
- Backlog-pressure indicator

## Data sources
NHS England, Consultant-led Referral to Treatment Waiting Times Data 2026–27:

- https://www.england.nhs.uk/statistics/statistical-work-areas/rtt-waiting-times/rtt-data-2026-27/
- Incomplete Provider May 2026
- RTT Overview Time Series May 2026

## Tools
- Python
- Pandas
- SQL
- Tableau
- Excel
- GitHub

## Repository structure
```text
data/
  raw/          Original NHS England files
  processed/    Cleaned and analysis-ready files
notebooks/      Python notebooks
sql/            SQL schema, cleaning and analysis queries
tableau/        Tableau workbook or published-dashboard details
reports/        Data dictionary and stakeholder briefing
images/         Dashboard screenshots and charts
README.md
requirements.txt
.gitignore
```

## Current limitations
- The analysis is based on published aggregate data, not patient-level records.
- Published figures may include suppression, estimates or revisions.
- Provider comparisons must be interpreted with service mix and reporting
  differences in mind.

## Author
Shivakeerthi Bharathapu
