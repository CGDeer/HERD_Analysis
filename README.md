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
-1. Geocode data from https://nces.ed.gov/programs/edge/Geographic/SchoolLocations
-- Used 2016-2017 Post-secondary data
- Merge list #25 from nsf website to the geocode data
- Use Heatmap for funding ranges seperated by arbitrary increments (likely in $100M)
- Geocodes are too tightly packed or use color glyph at zoom (Bokeh Datashader for region with glyphs)
- NEED to consider edge cases such as UA MED PHX or UA MED TUCSON are split 
- 



## Data Structure Notes
### Files of Interest 
- Data files are split across years (1992 - 2016)

## Notes on scripts
- Fun with Mapping CBH ver.ipynb (versions since 11/27/18 require Python 3.5, (Py35), to work properly).  
--The warning present does not pose a problem (just need to go back and shorten column name 'Institution' to something shorter in the data set to clear the warning. It did affect 'All Federal R&D' negatively so that column name has been changed to TOT_Fed.  The code doesnt seem to mind continuing use of 'Institution' later on in the script.  
--HERD Survey NSF Colormap.ipynb is a descendant of this version also uses Py35

-Joining HERD has not been tested under Py35 as I was still using Python 2.7, (Py27).
