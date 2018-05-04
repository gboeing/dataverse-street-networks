# OSMnx street networks to Dataverse

### Python environment

Create the anaconda environment with:

```
conda env create -f environment.yml
```

### Data inputs

The boundary shapefile data inputs are:

  - `input_data/neighborhoods`: Zillow neighborhoods shapefiles (March 2018 release) from https://www.zillow.com/howto/api/neighborhood-boundaries.htm (with states in subfolders)
  - `input_data/places`: 2017 census places shapefiles via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Places) or [FTP](ftp://ftp2.census.gov/geo/tiger/TIGER2017/PLACE) (with states in subfolders)
  - `input_data/urbanized_areas`: 2017 census urban areas shapefile via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Urban+Areas) or [FTP](ftp://ftp2.census.gov/geo/tiger/TIGER2017/UAC)
  - `input_data/counties`: 2017 census counties shapefile via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Counties+%28and+equivalent%29) or [FTP](ftp://ftp2.census.gov/geo/tiger/TIGER2017/COUNTY)
