# Australia-Fires
This repository contains all the elements (jupyter notebook, data,...) in order to reproduce the paper entitled "The Economic and Environmental Impact of the 2019–2020 Black Summer Fires in Australia." The purpose of this repository is to allow full transparency and reproducibility for this study. 

---

# Setting up locally  
1) clone the repository with the following command in the terminal:
    git clone https://github.com/jamieebrennan/Australia-Fires.git
   cd Australia-Fires
2) Download the necessary packages (the ones at the start of the uae.ipynb notebook)

---
# Downloading the data for Australia Shapefile:
1) To obtain the country level shapefile we use the same shapefile we used in class which was found here: https://github.com/wri/wri-bounds
2) We selected the shapefile for all primary countries

# Downloading the data for NTL:
1. Shapefiles have been included in the repository for your convenience. In order to download the relevent NTL data used in the study, you'll need to go to the Payne Institute Database (https://payneinstitute.mines.edu/eog/) and download the data for the following months from the 60E00N tile:
      June 2018
      June 2019
      December 2019
      March 2020
      March 2021
      March 2023
      March 2024
      March 2025
  For each folder you download, extract the data, take out the relevent tif. file (a file of this form: SVDNB_npp_20180601-20180630_000N060E_vcmcfg_v10201904251200.tgz

# Downloading the data for Fires:
To obtain the fire specific data we utilized data from nasa from their archive
link: https://www.earthdata.nasa.gov/data/tools/firms
You have to create an earth data account to access the files and request permission to access the MODIS satellite data for fires in australia for the month of june in 2018 to assess what the area was like before the fires began. We then also downloaded Modis data for june of 2019, December of 2019 and data for March of 2020 and 2021.
We did not gather data for 2023 or 2025 because these years are directed towards recovery
and are no longer assessing the presence of a fire

# Downloading the data for Vegetation:
We used NASA MODIS data for the vegetation indices:
link: https://www.earthdata.nasa.gov/data/catalog/lpcloud-mod13c2-006
# Downloading the data for Aerosol:
We used NASA areosol data from this link: https://www.earthdata.nasa.gov/data/tools/appeears
It should take you here: https://appeears.earthdatacloud.nasa.gov/task/area
