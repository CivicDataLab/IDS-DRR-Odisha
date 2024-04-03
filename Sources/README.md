# IDS-DRR-Odisha

## Directory Tree
├── assets: Common assets required to run the data pipeline. <br>
│   ├── Odisha_Maps <br>

├── Sources: Data Sources. <br>
│   ├── SENTINEL <br>


## Data Sources for Odisha Flood Management 

| Source  | Variables | Temporal Resolution | Remarks |
| ------------- | -------------  | ------------- | ------------- |
| BHARATMAPS  | `Number of schools`<br>`Number of heath centers`<br>`Rail Length`<br>`Road Length`<br>  | Static | - |
| SENTINEL  | `NDVI`<br>`NDBI`  | Monthly | Unable to run Pipeline for 2018. GEE Error B11, B8 not available <br> If download fails for any month, run at different scale (300) for those months |
| GCN250  | `Surface runoff`  | Static | - |

## References

1. [Odisha District, Block and Village Layer](https://github.com/justinelliotmeyers/Odisha_2021_Official_Boundaries) by Justin Meyers
2. [Odisha Village layer (with Sub-district feature)](https://projects.datameet.org/indian_village_boundaries/or/) by dataMeet
3. [Odisha OGD](https://odisha.data.gov.in/)
4. [Odisha Districts Map](https://data.opencity.in/dataset/district-maps-for-states-of-india/resource/odisha-districts-map)
5. [LGD](https://lgdirectory.gov.in/welcome.do)
6. [OSM Subdistricts](https://wiki.openstreetmap.org/wiki/Subdistricts_in_Odisha)

## State GIS Portals
1. [Odisha GEO-PORTAL](http://gisodisha.nic.in/)
    - Has all administrative maps (District-Block-Police Station) as PDFs
2. [ODISHA MAPS - State GIS Portal](https://stategisportal.nic.in/stategisportal/Home/State/21)