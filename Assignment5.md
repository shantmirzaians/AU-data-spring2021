# Assignment 5: Interview a dataset

1. I wanted to examine Parks & Recreational facilities and resources available throughout the City of Los Angeles
    * I downloaded the dataset from [Los Angeles Open Data](https://data.lacity.org/Parks-Recreation/Department-of-Recreation-and-Parks-Facility-and-Pa/dei3-2kfm).
    * I had the following Questions & Answers:
        * What types of Parks & Recreation resources/facilities are abundantly available across all Districts?
            * I found that public parks and recreation centers overall are abundant across all districts. 
            * Senior centers and tennis courts were also available across all districts. Though the highest concentration of Tennis Courts was in a higher income district, District 11 with nine.
            * Public swimming pools (summer and year around) were mostly available across all districts, except for district 13 which had zero.
        * Are “luxury facilities” only available in higher income areas?
            * I considered Dog Parks and Golf Courses as “luxury facilities”, facilities that I don’t expect have high priority, necessity, or demand from the public.
            * I was surprised to find dog parks, though few in number overall, were spread across high, middle, and low income districts.
            * I found that only two of the four higher income districts had golf courses while one of the lower income districts had a single golf course. Ten of the 15 total golf courses in Los Angeles were in the middle income districts.
        * Are Outdoor Fitness Equipment sites more common in lower income areas?
            * My guess was that higher income district residents would not have much need for these facilities as they could likely afford and prefer membership at private gym facilities.
            * I found that this was true, there very few Outdoor Fitness Equipment sites in higher income districts, many more in lower income districts, and a decent spread in the middle income districts.          

2. Cleaning and analyzing the data:
    * I downloaded the dataset.
    * I kept the original dataset as the first sheet in the workbook and created a copy in another sheet.
    * I removed columns not relevant to my analysis, keeping only:
        * Location Type
        * Location Name
        * City
        * Council District
     * I created a pivot table:
        * Row Labels: Location Type
        * Column Labels: Council District
        * Values: Count of Location Type
        * This gave me a spread of the types of park and recreation facilities throughout the city and how many of each were available in each district.
        * To make sure I did the pivot table correctly, I checked the grand total count to be sure it matches the count of the original dataset.
      * Defining higher, middle, and lower income districts:
        * I referred to a 2018 [report](https://lachamber.com/clientuploads/pdf/2018/18_BeaconReport_LR.pdf) by the Los Angeles Chamber of Commerce.
        * I found a graph that listed Median Household Income by Council District.
        * I found that the overall Median Household Income across Los Angeles is around $68,000.
        * I considered "higher income districts" as those with a Median Household Income of over $75,000.
          * This included Districts 11, 5, 3, and 12.
        * I considered "middle income districts" as those with a Median Household Income of $46,000 - $75,000.
          * This included districts 4, 2, 7, 6, 15, 10, and 13.
        * I considered "lower income districts" as those with a Median Household Income of below $46,000.
          * This included districts 1, 14, 8, and 9.
          
3. Headline, Lead, Nut Graf:

## Health and Economic Equity: Do Working People Have a Chance at a Healthy Lifestyle?

Most outdoor fitness equipment available to Los Angeles residents lie in lower income neighborhoods. 

However, working people may have difficulty regularly accessing these sites before or after work since most of them are closed after sundown.

Meanwhile, higher income neighborhoods may have fewer of these sites available because they can afford to pay for a private gym membership.

Regular exercise is an essential part of maintaining good health and studies have shown that greater economic equity leads to a healthier lifestyle. 
