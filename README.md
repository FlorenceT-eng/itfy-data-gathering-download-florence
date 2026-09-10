# Life Expectancy in Ghana: A Comparative Analysis

## Research Question
How has life expectancy in Ghana changed between 1952 and 2007 compared with 
Kenya, Nigeria, and South Africa?

## Data Source
- **Dataset:** Gapminder five-year country indicators
- **Publisher:** Gapminder Foundation, distributed in the Plotly datasets collection
- **URL:** https://raw.githubusercontent.com/plotly/datasets/master/gapminderDataFiveYear.csv
- **Documentation:** https://www.gapminder.org/data/documentation/
- **Retrieved:** September 8, 2026
- **Coverage used:** 1952–2007, every 5 years, for Ghana, Kenya, Nigeria, and South Africa

## Findings

Life expectancy rose steadily in Ghana across the whole period, reaching 
60.0 years by 2007, a gain of 16.9 years from its 1952 starting point of 
43.1 years — the largest percentage improvement of the four countries at 
39.1%. Kenya and South Africa, by contrast, both peaked mid-period before 
falling back by 2007: South Africa dropped from a high of 61.9 years to 
just 49.3 years, and Kenya fell from a peak of 59.3 to 54.1 years. Nigeria 
had the lowest life expectancy throughout, rising only from 36.3 to 46.9 
years over the full 55-year period.

A scatter plot of GDP per capita against life expectancy across all four 
countries showed a positive relationship — higher GDP per capita generally 
coincided with higher life expectancy — though this does not establish 
that one causes the other.

**Most surprising finding:** the late-period decline in South Africa and 
Kenya, despite the general global trend of rising life expectancy. This is 
consistent with the known impact of the HIV/AIDS epidemic in southern and 
eastern Africa during the 1990s and early 2000s.

## Limitations
1. **Recency:** the most recent data point is 2007, so the dataset does 
   not reflect any changes in life expectancy or GDP per capita over the 
   past two decades.
2. **Sampling interval:** data is recorded only every 5 years, so any 
   sharper rises or falls between recorded years are not captured.
3. **Correlation, not causation:** the relationship observed between GDP 
   per capita and life expectancy shows the two move together, but this 
   data cannot establish that either one causes the other.

## What I'd Gather Next
Life expectancy data for the wider African continent compared with other 
world regions, sourced from Gapminder or the World Bank, to see whether 
these four countries' patterns are typical or unusual for the continent 
as a whole.

## Repository Contents
- `topic19_assignment_file_download.ipynb` — the completed notebook
- `data/raw/` — the unmodified downloaded file
- `data/clean/` — the cleaned dataset used for analysis
- `charts/` — the line and bar charts produced
- `manifest.json` — full provenance record: source, checksum, retrieval 
  date, and cleaning steps