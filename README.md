# Coursera_Capstone
IBM Data Science Coursera Capstone Project

A. Introduction
A.1. Description and Discussion of the Background 
The San Francisco bay area, aptly named, “Silicon Valley,” has long been synonymous with the US software and technology industry which has been fueled by the startup culture that has developed in the region over the past three decades. However, for the next big startup deciding on an ideal location to establish its base, other cities and metropolitan regions in the country offer an attractive alternative. Business Insider’s “Top 15 Cities to launch a startup” reflects the changing landscape of the startup environment in the United States. 
Based on the analysis by a software company, Volusion that used the 2017 US Census Bureau Annual Survey of the Entrepreneurs, the list is dominated by startup friendly cities distributed throughout the country. The cities on the list were rated on five metrices: Entrepreneurship score, startup density, percentage of firms receiving venture capital investment, percentage of self-employed workers, and the percentage of respondents who reported that the reason for starting business isn’t lack of work. Although the Silicon Valley’s San Jose-Sunnyvale-Santa Clara metropolitan area made it into the list, it was topped by Seattle and Austin. 
When deciding between the cities on this list, a startup must, not only consider the governmental incentives and the tax framework for a business in early stages, but also the amenities and resources that will help attract its most precious resource, early career employees. To convince employees to lend their talents to help innovate and build up the company, the startup must, in addition to offering a financial incentive such as an equity stake, consider other factors that are likely to be important to young professionals. 
These include the city’s cost of living, top rated restaurants and other cultural venues, good schools, and the price for single family houses. Having all of this information at the appropriate city and neighborhood levels in the form of both maps and charts will help a startup make an effective decision regarding where to invest its resources. 
A.2. Data Description
The data that will be used in this analysis include:
1. The cities on the “Business Insider Top 15 cities to launch a startup” tabulated and then mapped using their corresponding latitudes and longitudes that will be retrieved using the Google Maps V3 API.
2. Numbeo Cost of Living index for the cities above which will be scrapped from publicly available webpage using Beautiful Soup.
3. GreatSchools and parents’ ratings for schools within 20 miles of the city center accessed using the greatschools.org API. 
4. Zillow Home Value Index (ZHVI) in USD for single family homes for neighborhoods in the US between November 2019 and November 2020 for the cities above that will be downloaded as a CSV file from the openly available Zillow research database. 
5. Latitudes and longitudes for each of the neighborhoods of the cities above retrieved using the Google Maps V3 API.  
6. Most common venues in each of the neighborhoods of the cities above retrieved using the Foursquare API. 
7. The Choropleth map at both the neighborhood and the city level will be created using the GeoJSON file downloaded from AlexMotz Github repository (https://github.com/AlexMotz/us-neighborhood-geojson) based on the publicly available Zillow neighborhood data. 
