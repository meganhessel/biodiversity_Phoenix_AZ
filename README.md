# Reduction in Biodiversity Intactness Index in Phoenix, AZ

## Purpose

Study how the urban spaw in Phoenix, AZ is disrubiting the biodiversity and ecosystem health by comparing 2017 and 2020  Biodiversity Intactness Index (BII). 

-  Pull 2017 and 2020 BII information from the Microft Planetary computer catalog
-  Clip and mask BII rasters to the Phoenix, AZ perimeters 
-  Manipulate rasters with logisticals 
-  Create multi-component professional plot of BII change from 2017-2020 in Phoenix, AZ 

## Housed in Repository

Within the repo is the README, anazlysis notebook, and the gitinore. 

```{python}
repo-name
│   README.md
|   task2_biodiversity.ipynb  
└── .gitignore
```

**The data...**
-  The Arizona county subdivision dataset contains all county geometries. The dataset is from [U.S. Census Buraeu](https://catalog.data.gov/dataset/tiger-line-shapefile-2023-state-arizona-az-county-subdivision) and accessed on December 6, 2025. 

-  The Biodiversity Intactness Index (BII) Time Series data is from the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity), and accessed on December 6,2025. The BII measures the health of the ecosystem by looking at species abundance and diversity. 

## References

United States Census Bureau. (2025). *TIGER/Line Shapefile, 2023, State, Arizona, AZ, County Subdivision*. Data.gov. https://catalog.data.gov/dataset/tiger-line-shapefile-2023-state-arizona-az-county-subdivision 

Microsoft. (2025). *Biodiversity Intactness* [Dataset]. Microsoft Planetary
Computer. https://planetarycomputer.microsoft.com/dataset/io-biodiversity#overview

## Acknowledgment 
 I would like to thank Dr. Carmen Galaz García and Dr. Annie Adams for helping in the creation and development of this project.


