# Arizona Mortgage Statistics 1998-2021
“The National Mortgage Database (NMDB®) is a nationally representative five percent sample of residential mortgages in the United States” (National Mortgage Database, 1). The dataset includes residential mortgages in multiple categories from 1998 to 2021. It also includes an annual census of employment numbers and wages. The Federal Housing Finance Agency “conducts a monthly mortgage market survey to collect data on the characteristics of individual mortgages, both Enterprise and non-Enterprise, and to make the data available to the public while protecting the privacy of the borrowers” (1).

## Dataset Information

Title: Bureau of Labor Statistics (BLS) Wages - Arizona

Date of Study: 2021

**Original owners:** Federal Housing Finance Agency (FHFA) and U.S. Bureau of Labor Statistics (BLS)

**Source:** https://www.fhfa.gov/DataTools/Downloads/Pages/National-Mortgage-Database-Aggregate-Data.aspx
https://www.bls.gov/cew/downloadable-data-files.htm

**Relevant Information:** https://www.bls.gov/cew/about-data/downloadable-file-layouts/annual/naics-based-annual-layout.htm

**PDF:** https://www.fhfa.gov/DataTools/Downloads/Documents/NATIONAL-MORTGAGE-DATABASE-(NMDB)-AGGREGATE-DATA/NMDB-New-Mortgage-Statistics-Data-Dictionary-Technical-Notes.pdf

## Table Columns
The table used is a simplified version of the BLS Wages in Arizona, with some columns removed or modified.

own_code - 1-character ownership code.

industry_code - 6-character industry code (NAICS, SuperSector).

agglvl_code - 2-character aggregation level code.

year - 4-character year.

area_fips - 5-character FIPS code.

annual_avg_wkly_wage - Average weekly wage based on the 12-monthly employment levels and total annual wage levels.

annual_avg_emplvl - Annual average of monthly employment levels for a given year.

avg_annual_pay - Average annual pay based on employment and wage levels for a given year.

agglvl_title - Multi-character aggregation title associated with the agglvl code (Excluded from singlefile).

industry_title - Multi-character industry title associated with the industry code (Excluded from singlefile).

own_title - Multi-character ownership title associated with the ownership code (Excluded from singlefile).

area_title - Since this is only in Arizona, all area_title values are "Arizona Statewide".

## Retrieved table from
- https://www.bls.gov/cew/downloadable-data-files.htm

# Charts Generated For This Project

## How has the typical age of all borrowers changed over the years?
![Image](https://github.com/SMarbella/New-Mortgage-Statistics-1998-2021/blob/main/Images/Typical%20Age%20of%20All%20Borrowers%20Over%20the%20Years.png)

**Figure 1.** A line graph showing the change in the typical age of all borrowers from 1998 to 2021. In 1998, the typical age of all borrowers was about 42 years old. By 2021, they were about 46 years old. During the 1998 to 2010 period, the average age of all borrowers slowly increased from 42 to 46 years old. After 2010, the average age became relatively stable, fluctuating between ages 45 and 46.

## How has the percentage of female borrowers changed over time?
![Image](https://github.com/SMarbella/New-Mortgage-Statistics-1998-2021/blob/main/Images/Female%20Borrowers%201.png)

**Figure 1.** Line plot that shows the average percentage of female residential mortgage borrowers in the United States from 1998 to 2021. Overall, the percentage of female borrowers fluctuates over time while increasing between 15% to 22% from 1998 to 2021.

![Image](https://github.com/SMarbella/New-Mortgage-Statistics-1998-2021/blob/main/Images/Female%20Borrowers%202.png)

**Figure 2.** Bar plot that shows the average percentage of female residential mortgage borrowers in the United States from 1998 to 2021. Overall, the percentage of female borrowers fluctuates over time while increasing between 15% to 22% from 1998 to 2021.

![Image](https://github.com/SMarbella/New-Mortgage-Statistics-1998-2021/blob/main/Images/Female%20Borrowers%203.png)

**Figure 3.** Scatter plot with an average line that shows the average percentage of female residential mortgage borrowers in the United States from 1998 to 2021. The line traces through the average percentage of female borrowers over the years. Overall, the percentage of female borrowers fluctuates over time between 15% to 22% from 1998 to 2021.

## How has the average loan amount of all mortgages changed through time when looked at by geographic region? How has the percentage of owner-occupied properties taking out a mortgage changed over time, and does that vary when looking at geographic region?
![Image](https://github.com/SMarbella/New-Mortgage-Statistics-1998-2021/blob/main/Images/facetted%20by%20year.png)

**Figure 1.** Scatter plots faceted by year and geographic region that shows different variations of percentage of owner-occupied property and their average mortgage loan amounts in each region in the mainland United States. The average loan amounts are simplified (e.g., 500 is $500,000, 1000 is $1,000,000). From 1998 to 2003, the average loan amount of most mortgages in all regions is below $250,000. From 1998 to 2021, the average loan amount of most mortgages in all regions slowly increased over time. From 1998 to 2003, the percentage of owner-occupied properties taking out a mortgage was above 85% in all regions. From 2004 to 2021, the percentage of owner-occupied properties taking out a mortgage in the South and the West regions had decreased more significantly than the Midwest and Northeast regions.
