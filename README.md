# srtm30-parser
A framework to work with SRTM30 near-global digital elevation data, i.e., a combination of data from the Shuttle Radar Topography Mission and the U.S. Geological Survey's GTOPO30 data set. 

This package is work in progress and currently updated frequently.

A documentation of the data is found here: https://dds.cr.usgs.gov/srtm/version2_1/SRTM30/srtm30_documentation.pdf

# Installation

This package only works with `python3`. To install just type:
```
git clone git@github.com:marcwie/srtm30-parser.git
cd srtm30-parser
python setup.py install
```

# Usage

1. Create a working directory and download the necessary raw input files:
    ```
    mkdir workdir
    cd workdir
    download-srtm30-data.sh
    ```
    Afterwards your working directory should look like this:
    
    ```
    workdir/
    └── srtm30
        ├── E020N40.DEM
        ├── e020n40.dem.zip
        ├── E020N40.HDR
        ├── e020n40.hdr.zip
        ├── ...
        ├── W180S10.HDR
        └── w180s10.hdr.zip
    ```

