# AIDA search strategy and export

Database: AIDA (Bureau van Dijk, Moody's), accessed through the University of Bologna library.
Export date: [date]. Data update: [number and date shown in AIDA].

## Search steps (Boolean: 1 And 2 And 3 And 4)

| Step | Criterion | Setting | Step result | Search result |
|---|---|---|---|---|
| 1 | Date of incorporation | 01/01/2016 to 31/12/2018 |  |  |
| 2 | Legal status | All 11 statuses (3 active, 8 inactive) |  |  |
| 3 | Legal form | SRL, one-person SRL, simplified SRL, SRL with reduced capital |  |  |
| 4 | Years with available accounts | 2019 (absolute year) |  | 211,098 |

No filter on legal events, procedures or financial values was used, so the outcome does not
select the sample. An earlier search filtered on legal events was discarded for this reason.

## Columns exported (all financial values for absolute year 2019)

Company name, Province, Accounting closing date, Revenues from sales and services (th EUR),
Tax code number, CCIAA number, Legal status, Legal form, Company category, Incorporation year,
Foundation date, Procedure/cessazione, Date of open procedure/cessazione, Date of closure procedure,
Innovative start-up company, Innovative PMI, Import/export, BvD independence indicator,
ATECO 2007 code, Liquidity ratio, Return on asset (ROA) (%), Solvency ratio (%), Leverage,
Total assets turnover (times), Total assets (th EUR), Profit (loss) (th EUR).

Multi-valued fields (procedure, dates): all values displayed.

## Export settings

- One company per line, search strategy included, Excel 2007 (.xlsx).
- Export limit: 37,037 companies per file, so six batches:

| Batch | From | To |
|---|---|---|
| 1 | 1 | 37,037 |
| 2 | 37,038 | 74,074 |
| 3 | 74,075 | 111,111 |
| 4 | 111,112 | 148,148 |
| 5 | 148,149 | 185,185 |
| 6 | 185,186 | 211,098 |

- Same search, same saved column list and same sort order for every batch.

## Checks after stacking

- Total rows equal 211,098.
- No duplicate tax code and CCIAA number pairs.
