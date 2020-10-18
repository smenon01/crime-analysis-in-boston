# Crime Analysis in Boston

## Summary
This project looks at examining the distribution of crime incidences in the city of Boston to provide some more context into how crime actually manifests in the city and interacts with other factors. 

We wanted to look into crime trends and patterns in the city and see if there is a relationship (geographically and perhaps through statistical measures such as correlation, or even regression) between crime in Boston and demographic factors, such as race, education level, or income level. Examining these additional factors may help better explain the spatial patterns of crime incidences that are observed in the city. Since much of the relevant available data includes measures across multiple years, we were also interested in looking into how crime occurrences have evolved over time as the city has changed. 

Examining crime patterns alongside demographics may give us a better understanding of how public safety in Boston has evolved. Analyzing crime incidents can inform us about which areas of the city are experiencing the most crime incidents, what types of crimes are most prevalent, how these patterns may have changed across years, and which populations are most vulnerable to crime incidents in the city. With more clarity on how crime is occurring in the city and which areas and populations are at highest risk, the city can develop policies that better target these issues and more effectively allocate resources to law enforcement agencies. Furthermore, by identifying potentially relevant factors (i.e. demographics, location) that contribute to crime occurrences, we could additionally create some sort of prediction model to identify areas in which crimes may occur. In general, better understanding crime distribution in the city can help in designing initiatives that improve the overall security and safety in the city<sup>1</sup>. 

This analysis is focused on spatial analysis and research, utilizing mutliple GIS tools (ArcGIS Pro and QGIS). 

## Datasets
In Boston’s open data hub, [Analyze Boston](https://data.boston.gov/), the Boston Police Department (BPD) has created datasets for [Crime Incident Reports](https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system), ranging from 2012-2019, which describe preliminary details regarding incidents in which the BPD was called to respond. Potentially relevant fields include: incident classification, date of incident, district, and the X and Y coordinates for the location of the incident.  This dataset can be used to conduct initial analyses regarding crime incidences in the city (i.e. distribution of types of crimes) and also has spatial information that can link with other relevant data and spatial files. 

We also utilized other related spatial datasets in this analysis: 2010 Census tracts for Boston, Boston Planning and Development Agency (BPDA) Neighborhoods, 2017 American Community Survey (ACS) Demographics for Boston, Boston Police Station locations. 

## References
1. How Can Crime Analysis Help Police Reduce Crime? (2014, August 19). Retrieved November 10, 2019, from https://bjatta.bja.ojp.gov/media/blog/how-can-crime-analysis-help-police-reduce-crime.
