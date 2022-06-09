# hud_usps_crosswalk_files

- source:
    - https://www.huduser.gov/portal/datasets/usps_crosswalk.html

- notes: 
    - if you have ZIP codes and want to get fips, you will want ZIP-COUNTY 

## from HUD website
 
### Understanding ZIP Code Crosswalk Files
Though often used for mapping, spatial analysis, and data aggregation careful attention is required when interpreting ZIP Code data relative to other administrative geographies. The following article demonstrates how to more effectively use the U.S. Department of Housing and Urban Development (HUD) United States Postal Service ZIP Code Crosswalk Files when working with disparate geographies.

Wilson, Ron and Din, Alexander, 2018. “Understanding and Enhancing the U.S. Department of Housing and Urban Development’s ZIP Code Crosswalk Files,” Cityscape: A Journal of Policy Development and Research, Volume 20 Number 2, 277 – 294. https://www.huduser.gov/portal/periodicals/cityscpe/vol20num2/ch16.pdf

 

### Using a GIS to Geoprocess ZIP Code Crosswalk Files
This article demonstrates how to use a GIS to process ZIP Code Crosswalk Files. In this article, calls for service from New York City's Open Data Portal are estimated at the county-level and census tract-level. This article also includes an accuracy analysis.

Din, Alexander and Wilson, Ron, 2020. "Crosswalking ZIP Codes to Census Geographies: Geoprocessing the U.S. Department of Housing & Urban Development’s ZIP Code Crosswalk Files," Cityscape: A Journal of Policy Development and Research, Volume 22, Number 1, https://www.huduser.gov/portal/periodicals/cityscpe/vol22num1/ch12.pdf


### How to Read the HUD-USPS ZIP Crosswalk Files:
- There are six types of crosswalk files available for download. The first 3 crosswalk files are used to allocate ZIP codes to Census tracts, counties or Core Based Statistical Areas (CBSA). The last three are used to allocate Census tracts, counties or Core Based Statistical Areas to ZIP codes. It is important to note that the relationship between the two types of crosswalk files is not a perfectly inverse one. That is to say, you cannot use the ZIP to Tract crosswalk to allocate Census tract data to the ZIP code level. For that you would have to use the Tract to ZIP crosswalk file.

