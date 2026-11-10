# 2024 African country indicators

This compilation aligns nine 2024 World Development Indicators extracts over the same 54 countries. The 486 rows include 466 reported values and 20 missing values. The World Bank source vintage is 8 October 2026. Each archived extract has its own DOI.

- [Download the CSV](AfricaCountryIndicators2024.csv)
- [Download the Excel workbook](AfricaCountryIndicators2024.xlsx)
- [Provenance and checksums](provenance.json)

## Coverage and sources

| Measure | Unit | Reported | Missing | Archive | Publisher explainer |
| --- | --- | ---: | ---: | --- | --- |
| [Personal remittances received](https://data.worldbank.org/indicator/BX.TRF.PWKR.DT.GD.ZS) | % of GDP | 41 | 13 | [Zenodo](https://doi.org/10.5281/zenodo.24098357) | [Read the explainer](https://infographicsafrica.com/s/remittances/) |
| [Electricity access](https://data.worldbank.org/indicator/EG.ELC.ACCS.ZS) | % of population | 54 | 0 | [Zenodo](https://doi.org/10.5281/zenodo.24098507) | [Read the explainer](https://infographicsafrica.com/s/energy-access/) |
| [Under-five mortality](https://data.worldbank.org/indicator/SH.DYN.MORT) | Deaths per 1,000 live births | 54 | 0 | [Zenodo](https://doi.org/10.5281/zenodo.24098510) | [Read the explainer](https://infographicsafrica.com/s/child-mortality/) |
| [GDP in current US dollars](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD) | Current US dollars | 52 | 2 | [Zenodo](https://doi.org/10.5281/zenodo.24098513) | [Read the explainer](https://infographicsafrica.com/s/largest-economies/) |
| [People using the internet](https://data.worldbank.org/indicator/IT.NET.USER.ZS) | % of population | 51 | 3 | [Zenodo](https://doi.org/10.5281/zenodo.24099738) | [Read the explainer](https://infographicsafrica.com/s/internet/) |
| [Life expectancy at birth](https://data.worldbank.org/indicator/SP.DYN.LE00.IN) | Years | 54 | 0 | [Zenodo](https://doi.org/10.5281/zenodo.24099742) | [Read the explainer](https://infographicsafrica.com/s/life-expectancy/) |
| [Urban population share](https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS) | % of population | 54 | 0 | [Zenodo](https://doi.org/10.5281/zenodo.24099744) | [Read the explainer](https://infographicsafrica.com/s/urbanization/) |
| [Total population](https://data.worldbank.org/indicator/SP.POP.TOTL) | People | 54 | 0 | [Zenodo](https://doi.org/10.5281/zenodo.24099746) | [Read the explainer](https://infographicsafrica.com/s/population/) |
| [Net foreign direct investment inflows](https://data.worldbank.org/indicator/BX.KLT.DINV.WD.GD.ZS) | % of GDP | 52 | 2 | [Zenodo](https://doi.org/10.5281/zenodo.24099748) | [Read the explainer](https://infographicsafrica.com/s/fdi/) |

## How to use the files

Each row represents one country, one indicator and one year. Join on `iso3`, `indicator_code` and `year`. Filter by indicator before comparing values. Units vary across the nine measures.

Use `value_exact` in the CSV or **Value as published** in the workbook to retain the source precision. The workbook’s **Numeric value** column supports calculations using Excel’s numeric precision. Blank value cells with a `missing` status indicate an unreported value. A reported zero remains zero.

The country list follows the [UN African States group](https://www.un.org/dgacm/en/content/regional-groups). The publisher aligned the archived columns into one table, retaining each original country label, indicator code, vintage, value and availability status.

## Attribution and reuse

Source data are from the [World Bank World Development Indicators](https://datacatalog.worldbank.org/search/dataset/0037712/world-development-indicators). Each indicator and archived release links to its provenance. For reuse, consult the [World Bank data licence and terms](https://datacatalog.worldbank.org/public-licenses), including any source-specific terms. Credit the World Bank and any original providers identified for an indicator. Credit Infographics Africa for combining the extracts. The compilation is independently published.

See the [publisher’s chart catalogue](https://infographicsafrica.com/charts/#datasets) and the [editorial method](https://infographicsafrica.com/methodology/).
