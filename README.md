# OSMnx street networks to Dataverse repository

### Process

  1. Create the OSMnx Python environment (see below)
  2. Download and un-zip the data inputs (see below)
  3. Run the Jupyter notebooks in order

### Python environment

Create the OSMnx environment with:

```
conda env create -f environment.yml
```

### Data inputs

The boundary shapefile data inputs are:

  - `input_data/neighborhoods`: Zillow neighborhoods shapefiles (March 2018 release, with states in subfolders) from [Zillow](https://www.zillow.com/howto/api/neighborhood-boundaries.htm).
  - `input_data/places`: 2017 census places shapefiles (with states in subfolders) via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Places) or [FTP](ftp://ftp2.census.gov/geo/tiger/TIGER2017/PLACE).
  - `input_data/tracts`: 2017 census tracts shapefiles (with states in subfolders) via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Census+Tracts) or [HTTP](https://www2.census.gov/geo/tiger/TIGER2017/TRACT/).
  - `input_data/urbanized_areas`: 2017 census urban areas shapefile via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Urban+Areas) or [FTP](ftp://ftp2.census.gov/geo/tiger/TIGER2017/UAC).
  - `input_data/counties`: 2017 census counties shapefile via [HTTP](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=Counties+%28and+equivalent%29) or [FTP](ftp://ftp2.census.gov/geo/tiger/TIGER2017/COUNTY).
