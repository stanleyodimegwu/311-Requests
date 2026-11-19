
# Data Inspection: Winnipeg 311 Requests

## Overview
- Source: [https://data.winnipeg.ca/Contact-Centre-311/311-Requests/u7f6-5326/data_preview]
- Endpoint: https://data.winnipeg.ca/resource/u7f6-5326.json
- Rows (portal preview): 18,599,788
- Columns (12): Case ID, Interaction ID, Channel Type, Subject, Reason, Type, Open Date, Closed Date, Case Status, Neighbourhood, Ward, Geometry

## Schema
| Field (API name) | Type as returned | Notes             |     |
| ---------------- | ---------------- | ----------------- | --- |
| case_id          | text (hash)      | [repeats? nulls?] |     |
| ...              |                  |                   |     |

## Checks
### [Short title, e.g. "Row count"]
- Question: [what you were trying to find out]
- Query: [the exact URL]
- Result: [paste or summarize the numbers]
- Takeaway: [one sentence: what it means for the project]

(Repeat for each check.)

## Findings by theme
- Row grain (case_id vs interaction_id)
- Subject and status populations
- Data quality (nulls, bad dates, label variants)
- Location coverage over time
- Channel changes over time

## Unanswered
- [Checks still to run, e.g. second duplicate case, ward labels 2010 vs 2024]