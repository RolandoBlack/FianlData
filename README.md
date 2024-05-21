# Final Project [201781678]<br>
## Background<br>
Fuel is closely related to people’s travel, life, work and many other aspects. Fuel poverty has always been an issue that affects public good to a large extent.
Previous studies have pointed out that fuel poverty may not only cause concerns about an increase in winter deaths, but also reflect today's energy challenges (Robinson, C., Bouzarovski, S. and Lindley, S., 2018).
Developed countries often receive close attention in academic and promotional fields due to fuel poverty (Bouzarovski, S. and Petrova, S., 2015).
As an important unit of regional population composition, the relationship between families and fuel poverty is one of the key research directions (Burlinson, A., Giulietti, M. and Battisti, G., 2018).
This project mainly studies the correlation and spatial distribution of fuel poverty in Leeds with car availability and household composition (whether households with disability have depended children or not). <br>
## Data<br>
### GitHub Repository Contains<br>
Two CSV tables of census data for Leeds.<br>
A CSV table of LSOA-scale fuel poverty in England.<br>
A .zip archive containing the Leeds LSOA shp files.<br>
Two .zip archives containing Leeds Census raw data (including citations and metadata).<br>
Two folders extracted from .zip archive of Leeds Census raw data.<br>
### Data Explanation<br>
***BoundaryData.zip*** A compressed archive (.zip) containing the Leeds census boundary (LSOA) file (.shp)<br>
***202451622130240_CARVAN_UNIT.zip*** A compressed archive (.zip) of raw Census data for Leeds on "households with disability with or without depended children", including metadata and citations.<br>
***202451621246377_CARVAN_UNIT.zip*** A compressed archive (.zip) containing raw Census data on car availability in Leeds, including metadata and citations.<br>
***202451622130240_CARVAN_UNIT*** Folder, extracted from the "202451622130240_CARVAN_UNIT.zip" compressed package.<br>
***202451621246377_CARVAN_UNIT*** Folder, extracted from the "202451621246377_CARVAN_UNIT.zip" compressed package.<br>
***car_avai.csv*** A .csv table containing Leeds car availability data read in by Python code written in the notebook.<br>
***depended_chd_with_unable.csv*** A .csv table containing "households with disability with or without depended children" data of Leeds read in by Python code written in the notebook.<br>
***fuel_poverty_by_LSOA.csv*** A .csv table containing fuel poverty data for England at the LSOA scale read in by Python code written in the notebook.<br>
### Data Sources<br>
Leeds Census boundary data: https://ukdataservice.ac.uk/learning-hub/census/other-information/census-boundary-data/<br>
Leeds Census data (households competition and car avalability): http://infuse.ukdataservice.ac.uk/<br>
England fuel poverty data: https://datamillnorth.org/dataset/2j70l/fuel-poverty-by-lsoa-england<br>
## Code Aim<br>
This code investigates the correlation and spatial distribution between household composition, car availability, and fuel poverty at the Leeds LSOA scale by implementing both non spatial and spatial visualizations.<br>
The final generated image of the code is a scatter plot classified based on different household composition and car availability, and a Leeds spatial clustering map using K-means for spatial clustering.<br>
## Refernce<br> 
[1]  Bouzarovski, S. and Petrova, S. 2015. A global perspective on domestic energy deprivation: Overcoming the energy poverty–fuel poverty binary. Energy research & social science. 10, pp.31–40.<br>
[2]  Burlinson, A., Giulietti, M. and Battisti, G. 2018. The elephant in the energy room: Establishing the nexus between housing poverty and fuel poverty. Energy economics. 72, pp.135–144.
[3]  Robinson, C., Bouzarovski, S. and Lindley, S. 2018. ‘Getting the measure of fuel poverty’: The geography of fuel poverty indicators in England. Energy research & social science. 36, pp.79–93.<br>
