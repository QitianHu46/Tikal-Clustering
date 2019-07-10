## Intro

The jupyter notebook Tikal_clustering contains 3 clustering algorithms for the Tikal map. The boundaries for each cluster are also drawn in order to better compare it with the original neighborhoods.





## Mar 25 Video Call

### Evaluating clusters

The general consensus was to produce <u>several clustering solutions</u>, and compare them against several lines of archaeological data to see how they compare to independently generated divisions within the city. Possible lines of independent evidence include the locations of known ethnic and/or craftworking neighborhoods/zones at the site, the distribution of plazas, and the distribution of other public architecture, and possibly Ian Robertson's artifact-based classes. I have attached a GIS shapefile with our revised (not the original TMP) plaza locations, and an article by Linda Manzanilla with a map showing possible ethnic and crafting locations. Do you already have the shapefile(s) with other public architecture?

### Neighborhood homogeneity

Apartment compounds are multi-household dwellings. While Mike and Angela are working on a way to extrapolate the range of variability in individual household dwelling units from excavated cases to the city as a whole, there aren't enough excavated apartment compounds to do this for individual neighborhood clusters. We can generate estimates of what proportion of each cluster belong to different wealth/status levels, based on the original TMP classifications of high/intermediate/low status residences. The version of the insubstantial structures file I sent a while ago includes all the low status residences, with instructions on how to separate them from other structure types in the same layer. Did the version of the apartment compounds shapefile that got sent around (by Tim?) have a ID (not FID) column in the associated data? If yes, it can that field can be used to link it to the same excel sheet that I sent with the insubstantial structures/low status residences files. If not, I'll include the version of the shapefile with the IDs tomorrow.







## Apr 16 Meeting with Luis

* Teo
  * unit
  * (+) linear fit loglog, area vs. area
  * Insubstantial or building type?
  * heat map of the density
* Tikal
  * unit
  * do the area analysis the same as Teo
  * insubstantial structure
  * mark special buildings (status classification)
  * DBSCAN unit
  * heat map of the density
* eventually
  * status classification
    * draw histogram





* pyramid problem
  * 

