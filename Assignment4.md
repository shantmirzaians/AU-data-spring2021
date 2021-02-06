# Assignment 4 Steps

* I decided to use the data for our group project and filter by property location.
* I downloaded full dataset of all DC Basic Business Licenses from https://opendata.dc.gov/datasets/basic-business-licenses
* I filtered the data by LICENSE_CATEGORY_TEXT to only include “Housing: Residential”.
* I filtered the data by LICENSECATEGORY to only include: “One Family Rental”, “Two Family Rental”, and “Apartment”.
* I filtered the data by LICENSESTATUS to only include active licenses.
* I removed columns that were not necessary in identifying location specifics leaving only:
  * BILLING_ADDRESS_CITY_STATE_ZIP - to identify if there are owners with multiple properties
  * SITE_ADDRESS
  * LICESNSECATEGORY - to identify the type of property
  * ZIP
  * WARD
  * ANC
  * DISTRICT
  * NEIGHBORHOODCLUSTER

**NOTE:** The original dataset is too be too large for me to upload to Github. I can email the original file seperately. The clean data is also fairly large, but I was able to upload it and it is downloadable as a .csv file.
