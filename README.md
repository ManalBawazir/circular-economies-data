As part of the Town+Gown: NYC Project titled Building Circular Economies in NYC's Industrial Business Zones.
The NYU Wagner team conducted a siting analysis to identify an ideal site for the development of interim processing facilities in each of the five chosen IBZs for the research:
  North Brooklyn IBZ in Brooklyn, Maspeth IBZ, and Long Island City IBZ  in Queens, Port Morris IBZ in the Bronx, and West Shore IBZ in StatenIsland.
Below is a detailed methodology of how the team produced the datasets in this repository. 
1. Download NYC City Owned and Leased Properties (COLP), Facilities Database, and MapPLUTO into ArcGiS and clip these layers to their respective IBZ using the IBZ shapefile. 
COLP:https://data.cityofnewyork.us/City-Government/City-Owned-and-Leased-Property-COLP-/fn4k-qyk2/data 
Facilities Database: https://www.nyc.gov/site/planning/data-maps/open-data.page#city_facilities 
MapPLUTO: https://www.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page 
IBZs Shapefile: https://edc.nyc/industry/industrial-and-manufacturing 
2. Using the MapPLUTO layer that is clipped to their respective  IBZ Shapefiles, Government-Owned Facilities were classified  into the three categories, fully tax exempt land, owned by the city and owned by either a Public Authority or State or Federal government, under the ‘Ownertype’ column. Using symbology features, identify each respective category using a different color.
3. Identify Vacant land by selecting land use: 11 in the MapPLUTO layer. This type of land has been labeled vacant by the government usually due to reasons that prevent development such as contamination. 
4. Identify Non CDW Related Industrial Facilities provided by MAPPLUTO under the section 'land use.’ Industrial Facilities are Land Use: 6.  
5. Using a combination of google maps and Simply Analytics Database, the team identified privately owned CDW Related Facilities, grouping them into 4 categories of Concrete and cement, Fabricators and metal scrap, Recycling and garbage, and Miscellaneous.

