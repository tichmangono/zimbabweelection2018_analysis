# zimbabweelection2018_analysis
Collaborative project using multiple sources of data to identify any anomalies and variance in election data released for Zimbabwe's July 2018 elections.

## Main Files
There main files are the Excel files in the root folder as well as a JupyterLap Notebook. These have the following functions
1. ***Election Data Transformation JupyterLab NoteBook** - for the python code to transform source files into convenient, clean format ready for analysis*
2. ***Election Results Main Citizen Excel file** - looks at anomalies e.g. extremely high and obviously impossible voter turnout rates like >90%, >95%, >100%.It also compares the official data from the Zimbabwe Electoral Commission with data from Citizen's Manifesto collation, crowdsourced. One of the data files imports data from a googlesheet and needs a regular update process, following which all pivot tables must be refreshed. The tabs in the file are color-coded into 3 groups:*
      - ***Green tabs** indicate source data*
      - ***Orange tabs** indicate aggregated data e.g by polling station, constituency, ward, province etc.*
      - ***Blue tabs** indicate analysis data e.g. high turnnout poling stations and comparison with independent findings when applicable*
3. ***Election Results 2018 By Polling Station** - This is the clean, collated, transofrmed version of the source data files for presidential elections*

## Source Files
- These are located in the folders for presidential, parliamentary etc.
- The files contain the source data which was tranformed using python and analyzed/explored using excel 

## Preliminary Findings:
1. About 36 polling stations may have had over 100% voter turnout
2. About 86 polling stations may have had over 95% voter turnout
3. About 750 polling stations may have had over 90% voter turnout
4. Some preliminary application of Benford's Law show some irregular distribution of the leading digits of total votes cast per polling station, but not in the individual candidates total votes. While this may highlight some anomalies, some statisticians actually discourage the use of Benford's law to detect Electoral anomalies. See here https://en.wikipedia.org/wiki/Benford%27s_law
### Please check all this for yourself before using!! These are NOT OFFICIAL RESULTS and none of the parties involved in this analysis, nor the sources mentioned will take responsibility for any wrong or inappropriate conclusions drawn from this data and associated analysis



## Limitations of this Analysis:
- NOTE: This analysis is only preliminary and needs to be checked!
- Some files are incomplete, especailly the indepedent data being collected by Citizens Manifesto currently only covers a little over 1350 polling stations, only 12% of the almost 11,000 polling stations
- Still need to check and validate data sources, and rule out any errors in transforming the data
- Still need to transform and collate Parliamentary results and compare voting numbers to presidential at the same polling station

## Collaborate for public good 
This project is an analytic and intellectual exercise for the public good and builds on the dilligent work started by Citizen's Manifesto Zimbabwe, so feel free to download anything and point out errors as well as any additional anomalies found

## Data Sources/Credit:
1. Citizens' Manifesto Zimbabwe: http://www.citizens-manifesto.org/
2. Zimbabwe Electoral Commission: https://www.zec.org.zw/
3. Pindula News: https://news.pindula.co.zw
4. Wikipedia: https://en.wikipedia.org/wiki/Zimbabwean_general_election,_2018
5. Youtube.com & South African Brodcasting Corporation : https://www.youtube.com/watch?v=4iyhagIulCU
