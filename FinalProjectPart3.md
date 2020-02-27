## Final Project Part III

### [Link to Final Project](https://carnegiemellon.shorthandstories.com/---chicago-s-fastly-gentrifying-neighborhoods---/index.html)

## Intended Audience
My primary audience for this project is individuals who may consider themselves as “gentrifiers” in Chicago. Other audiences include, but are not limited to, activists moving to Chicago and deciding where to live, policymakers trying to understand which neighborhoods are severely gentrified/are gentrifying to stop displacement, and those who are generally curious about what gentrification in Chicago looks like. When I first thought of this project, I thought it would be difficult to narrow on one intended audience, especially given the interconnectedness of gentrification to urban development, etc.  Several people can pick up different information from my project and try to understand what the statistics on gentrification reveal. 

## Research Methods & Design Processes:
When I first researched this topic, I came across the wonderful research done by Governing on gentrification. They used data from decennial census as well, but their visualizations are at the tract-level. As a Chicagoan, I realized that using tract-level is more detailed and accurate, but what if I focused on neighborhoods instead? That’s more intuitive to most Chicago residents and most of them already know something about each neighborhood. Therefore, I used data from the decennial census as well:

#### Median Value of Home:
[Median Value of Home, by Census Tract (2010 ACS 5-Year Estimate)](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_10_SF4_B25077&prodType=table)

[Median Value of Home, by Census Tract (2000 SF-4)](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=DEC_00_SF4_HCT066&prodType=table)

#### Percentage of the population 25+ years of age holding a Bachelor’s Degree:
[Bachelor’s Degree for Population 25+ Years Old (2010 ACS 5-Year Estimate)](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_10_5YR_S1501&prodType=table)

[Bachelor’s Degree for Population 25+ Years Old (2000 SF-3)](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=DEC_00_SF3_QTP20&prodType=table)

#### Median Household Income (Inflation-Adjusted):
[Median Household Income, by Census Tract (2010 ACS 5-Year Estimate)](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_10_5YR_B19013&prodType=table)

[Median Household Income, by Census Tract (2000 SF-3)](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=DEC_00_SF3_P053&prodType=table)

I used ArcGIS for all of my map visualizations. I created several joins, used ArcGIS tools such as Summarize Within, Clip, and Table to Excel, etc. to get aggregate data at the neighborhood-level instead of tract-level. However, I did encounter a missing data problem, especially with data from 2000, but I marked neighborhoods with “missing data” on the map. I also relied on Excel to calculate my z-scores for each of the three features I used: median household income, percentage of bachelor’s degrees, and median home value. Calculating z-scores allowed me to not normalize my data, but also come up with an index to compare across neighborhoods. This especially became helpful when creating my final gentrification index, which used relatively higher weights on median household income and percentage of bachelor’s degree, to determine the neighborhoods with statistically significant, or highest prevalence of gentrification. 

I wanted to make sure that my maps were overlaid to show trends across the three features (percentage change in median income, percentage of bachelor's degrees, and median home value). This was highly intentional and cropping exact dimensions took a lot longer than I expected. However, my maps are now overlaid and one can easily the change in all three features in one window instead of having to scramble for that information.

I added in a brief neighborhood analysis at the end because, unfortunately, data on Pilsen was missing in my original data sources. This was because Pilsen is located inside the boundaries of the Lower West Side neighborhood, but it's often referred to Pilsen by many Chicagoans. Because of this, I found data on Pilsen on [DNAInfo](https://www.dnainfo.com/chicago/20160413/pilsen/pilsen-gets-whiter-as-10000-hispanics-families-move-out-study-finds/) and created visualizations for a neighborhood that everyone knows about. This gives my analysis credibility while also acknowledging that Census data can sometimes be biased and underreport on predominantly minority neighborhoods.

Lastly, I made a very intentional choice to use lots of pictures in my story. When I first shared my ideas with my four friends, they all immediately said they loved the idea of incorporating pictures. It’s hard to visualize the tensions and effects of gentrification without highlighting the important work that community activists do to keep their communities intact, and by showcasing these images, I think my message is a lot clearer. Additionally, it’s always good to mix data with pictures to balance it all out.

## Limitations
Another analysis I would have loved to conduct, if I had the time, would have been to look at the change in racial demographics over time. This is something that came up in my research, but it is extremely time-consuming and complicated to measure change in racial demographics. I am hoping to explore this as my next challenge! 

## Sources:

#### Articles:

#### Images Used:
[Title Photo](https://upload.wikimedia.org/wikipedia/commons/2/26/Cabrini_green_demolition_2.jpg)

[“Get Out Photo” by Ariel Cheung](http://www.arielcheung.net/photos.html)

[“Luxury=Displacement” phot by Harry Huggins](https://news.medill.northwestern.edu/chicago/logan-square-protesters-fear-gentrification/)

[“Transition from 2000 to 2010” photo by James & Karla Murray](https://www.facebook.com/jamesandkarlamurrayphotography/photos/a.633202406731377.1073741832.225024807549141/638703149514636/?type=3&theater)

[“Vacant Buildings” photo by Library of Congress](https://journalistsresource.org/studies/economics/real-estate/gentrification-urban-displacement-affordable-housing-overview-research-roundup/)

[“Chicago Skyline” photo by Muzammil Soorma](https://unsplash.com/@muzammilo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

[“Pilsen is not for Sale” Photo](https://interactive.wttw.com/my-neighborhood/pilsen/gentrification)

[“Stop Gentrification” photo](https://www.chicagoreader.com/chicago/transit-oriented-development-cta-displacement-logan-square/Content?oid=21780147)

