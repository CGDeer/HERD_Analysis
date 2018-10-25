# Higher Education Research and Development (HERD) Survey Analysis
Data source from HERD Higher Edu Survey: https://www.nsf.gov/statistics/srvyherd/#tabs-2&tools&micro&profiles&tabs-2

## Intent:
1. Determine useful comparisons for analysis and inform UA community clientel
2. Determine Univ. Arizona Research Computing investment comparision to peer institutions

## Hypotheses

Bias localized to Federal Research Institutions for Federal NSF Dollars allocated to R&D where a positive correlation means closer ties
- H0: There is no bias in Federal Dollars allocated to R&D 
- HA: Expectation: See bias toward increased expenditures for DoD/DoE et al affiliated Universities 

Methods:
- Create geocoded plot of US with institutions and NSF funding received
- Use Heatmap for funding ranges seperated by arbitrary increments (likely in $100M)
- Geocodes are too tightly packed or use color glyph at zoom (Bokeh Datashader for region with glyphs)
- NEED to consider edge cases such as UA MED PHX or UA MED TUCSON are split 
- 



## Data Structure Notes
### Files of Interest 
- Data files are split across years (1992 - 2016)

## Notes
