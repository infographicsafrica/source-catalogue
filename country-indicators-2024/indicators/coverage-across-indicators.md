# Which countries have all nine 2024 indicators?

Forty of the 54 countries have a reported value for every indicator in this edition. A comparison that requires all nine measures uses 40 countries. A comparison that uses fewer measures can have a different country count. [Download coverage by country (CSV)](CoverageByCountry2024.csv).

## Where values are missing

| Coverage pattern | Countries |
| --- | ---: |
| All nine values reported | 40 |
| Remittances only missing | 11 |
| Internet use only missing | 1 |
| Four values missing | 2 |

Sudan is the one country missing only internet use. Eritrea and South Sudan are missing remittances, internet use, GDP in current US dollars and net foreign direct investment. These patterns account for 20 blank observations across 14 countries. [View each indicator’s coverage](README.md).

## Reproduce the counts

Use the combined CSV for 2024. Group by `iso3`, count the nine indicator rows and count the rows where `value_status` is `missing`. The country file gives those counts and separates multiple missing indicator codes with a vertical bar. Reported zeroes count as available.

State the measure and country count beside any comparison. For example, the remittances series alone has 41 countries with a reported value. Requiring an internet-use value as well leaves 40. [Combined CSV](../AfricaCountryIndicators2024.csv).

This edition covers the UN African States group and uses the World Bank source vintage of 8 October 2026. [Country scope](https://www.un.org/dgacm/en/content/regional-groups) · [World Bank dataset](https://datacatalog.worldbank.org/search/dataset/0037712/world-development-indicators) · [Source checksums](../provenance.json) · [Infographics Africa chart catalogue](https://infographicsafrica.com/charts/#datasets).
