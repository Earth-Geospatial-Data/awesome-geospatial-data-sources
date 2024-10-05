[English](./README.md) | [简体中文](./README_zh.md)

## Geospatial Data Sources on Roads, Buildings, and Transportation Networks

This document provides a comprehensive list of datasets related to geospatial data, including roads, buildings, transportation networks, and various environmental and demographic information for China and other regions. The datasets are provided by reputable sources such as Microsoft, Google, and various international and Chinese organizations.

---

### Table of Contents

- [Geospatial Data Sources on Roads, Buildings, and Transportation Networks](#geospatial-data-sources-on-roads-buildings-and-transportation-networks)
  - [Table of Contents](#table-of-contents)
- [Microsoft Datasets](#microsoft-datasets)
  - [1. Microsoft Building Footprints](#1-microsoft-building-footprints)
  - [2. Microsoft Maps and Bing Maps API](#2-microsoft-maps-and-bing-maps-api)
  - [3. Microsoft's Contribution to OpenStreetMap (OSM)](#3-microsofts-contribution-to-openstreetmap-osm)
- [Google Datasets](#google-datasets)
  - [1. Google Open Buildings Dataset](#1-google-open-buildings-dataset)
  - [2. Google Maps Platform and APIs](#2-google-maps-platform-and-apis)
  - [3. Google Research Datasets](#3-google-research-datasets)
- [Open-Source Geospatial Data Sources for China](#open-source-geospatial-data-sources-for-china)
  - [1. OpenStreetMap (OSM)](#1-openstreetmap-osm)
  - [2. Natural Earth](#2-natural-earth)
  - [3. GADM (Global Administrative Areas)](#3-gadm-global-administrative-areas)
  - [4. SRTM Elevation Data](#4-srtm-elevation-data)
  - [5. NASA Earth Data](#5-nasa-earth-data)
  - [6. Chinese Academy of Sciences Data Centers](#6-chinese-academy-of-sciences-data-centers)
    - [a. National Earth System Science Data Center](#a-national-earth-system-science-data-center)
    - [b. Data Sharing Infrastructure of Earth System Science](#b-data-sharing-infrastructure-of-earth-system-science)
  - [7. WorldPop Project](#7-worldpop-project)
  - [8. Global Land Cover by National Geomatics Center of China](#8-global-land-cover-by-national-geomatics-center-of-china)
  - [9. Sentinel Satellite Data](#9-sentinel-satellite-data)
  - [10. Humanitarian Data Exchange (HDX)](#10-humanitarian-data-exchange-hdx)
  - [Additional Resources](#additional-resources)
- [Considerations for Using the Data](#considerations-for-using-the-data)
- [How to Access and Use the Data](#how-to-access-and-use-the-data)
- [Summary](#summary)

---

## Microsoft Datasets

### 1. Microsoft Building Footprints

**Description:**  
High-resolution building footprint datasets generated using deep learning algorithms. Useful for urban planning, disaster response, and mapping projects.

**Coverage:**

- **United States:** Over 125 million building footprints.
- **Canada:** Over 12 million building footprints.
- **Africa:** Over 300 million building footprints across various countries.
- **South Korea and Australia:** Building footprints for these countries.

**Access:**

- **GitHub Repositories:**
  - [United States Building Footprints](https://github.com/Microsoft/USBuildingFootprints)
  - [Canada Building Footprints](https://github.com/microsoft/CanadianBuildingFootprints)
  - [Africa Building Footprints](https://github.com/microsoft/AfricaBuildingFootprints)
  - [South Korea & Australia Building Footprints](https://github.com/microsoft/BuildingFootprints)

**Data Format:**  
GeoJSON or Shapefile formats.

**License:**  
Open Data Commons Open Database License (ODbL).

---

### 2. Microsoft Maps and Bing Maps API

**Description:**  
Provides extensive mapping services through Bing Maps. Developers can access road, traffic, and transportation data via APIs.

**Access:**

- **Bing Maps API:** [Microsoft Bing Maps Platform](https://www.microsoft.com/maps)

**Documentation:**  
Guides on how to use the API for accessing various types of geospatial data.

**License & Usage:**  
Requires an API key; usage is subject to terms and conditions and may incur costs depending on request volume and type.

---

### 3. Microsoft's Contribution to OpenStreetMap (OSM)

**Description:**  
Microsoft contributes AI-generated map features to improve OSM data quality.

**Access:**

- **OpenStreetMap:** [www.openstreetmap.org](https://www.openstreetmap.org)

**Note:**  
Data contributed to OSM is freely available under the Open Database License.

---

## Google Datasets

### 1. Google Open Buildings Dataset

**Description:**  
Locations and footprints of buildings derived from satellite imagery using machine learning models.

**Coverage:**

- **Africa:** Over 500 million building footprints.
- **Asia-Pacific:** Includes countries like Bangladesh, Indonesia, and the Philippines.

**Access:**

- **Website:** [Google Open Buildings](https://sites.research.google/open-buildings/)
- **Google Cloud Storage:** [Open Buildings Data](https://console.cloud.google.com/storage/browser/open-buildings-data)

**Data Format:**  
CSV and GeoJSON formats.

**License:**  
Creative Commons Attribution 4.0 International License (CC BY 4.0).

---

### 2. Google Maps Platform and APIs

**Description:**  
Access to comprehensive road, building, and transportation data through various APIs.

**Access:**

- **Google Maps APIs:** [Google Maps Platform](https://developers.google.com/maps/documentation)
  - **Maps API**
  - **Routes API**
  - **Places API**

**License & Usage:**  
Requires an API key; services are billed based on usage with a free tier available.

**Note:**  
Bulk downloading of data from Google Maps APIs is against the terms of service.

---

### 3. Google Research Datasets

**Description:**  
Google AI and Research publish various datasets that may include geospatial data relevant to buildings and transportation.

**Access:**

- **Dataset Search:** [Google Dataset Search](https://datasetsearch.research.google.com/)

**Example Datasets:**

- **Open Images Dataset**

**License:**  
Varies by dataset; always check individual licenses.

---

## Open-Source Geospatial Data Sources for China

### 1. OpenStreetMap (OSM)

**Website:** [www.openstreetmap.org](https://www.openstreetmap.org)

**Description:**  
A collaborative project providing free and editable map data worldwide, including detailed geospatial information for China such as roads, buildings, and points of interest.

**How to Access:**

- **China-Specific Extracts:** [Geofabrik China Extracts](https://download.geofabrik.de/asia/china.html)
- **Custom Queries:** [Overpass API](https://overpass-turbo.eu/)

**License:**  
Open Database License (ODbL).

---

### 2. Natural Earth

**Website:** [www.naturalearthdata.com](https://www.naturalearthdata.com)

**Description:**  
Offers free vector and raster map data at various scales, including administrative boundaries, physical features, and cultural landmarks.

**How to Access:**  
Download data directly from their website in Shapefile or GeoPackage formats.

**License:**  
Public Domain.

---

### 3. GADM (Global Administrative Areas)

**Website:** [www.gadm.org](https://gadm.org/)

**Description:**  
Provides detailed administrative boundary data for countries worldwide, including provinces, prefectures, and counties in China.

**How to Access:**  
Data is available for free download in formats like Shapefile and GeoJSON.

**License:**  
Free for academic use; commercial use requires permission.

---

### 4. SRTM Elevation Data

**Website:** [earthexplorer.usgs.gov](https://earthexplorer.usgs.gov/)

**Description:**  
Offers global digital elevation data at 30-meter resolution, useful for terrain analysis in China.

**How to Access:**  
Use the USGS EarthExplorer portal to search and download SRTM data.

**License:**  
Public Domain.

---

### 5. NASA Earth Data

**Website:** [earthdata.nasa.gov](https://earthdata.nasa.gov/)

**Description:**  
Provides satellite imagery and geospatial datasets, including MODIS land cover data and climate data relevant to China.

**How to Access:**  
Free registration is required. Access data via the [Earthdata Search](https://search.earthdata.nasa.gov/).

**License:**  
Generally free for use with attribution.

---

### 6. Chinese Academy of Sciences Data Centers

#### a. National Earth System Science Data Center

**Website:** [www.geodata.cn](http://www.geodata.cn)

**Description:**  
Offers geospatial datasets specific to China, including environmental, ecological, and geographical data.

**How to Access:**  
Registration may be required; some datasets might need approval.

**License:**  
Varies by dataset; check individual terms.

#### b. Data Sharing Infrastructure of Earth System Science

**Website:** [www.data.cma.cn](http://www.data.cma.cn)

**Description:**  
Provides meteorological data, climate statistics, and related geospatial datasets.

**How to Access:**  
Free access with registration; some data may have usage restrictions.

**License:**  
Varies by dataset; check individual terms.

---

### 7. WorldPop Project

**Website:** [www.worldpop.org](https://www.worldpop.org/)

**Description:**  
Offers high-resolution population density maps and demographic data, useful for urban planning and public health studies in China.

**How to Access:**  
Data can be downloaded directly in GeoTIFF format.

**License:**  
Creative Commons Attribution 4.0 International License (CC BY 4.0).

---

### 8. Global Land Cover by National Geomatics Center of China

**Website:** [www.globallandcover.com](http://www.globallandcover.com/)

**Description:**  
Provides detailed land cover maps of China at a 30-meter resolution, useful for environmental and agricultural studies.

**How to Access:**  
Data is available for free download after registration.

**License:**  
Check website for specific terms and conditions.

---

### 9. Sentinel Satellite Data

**Website:** [scihub.copernicus.eu](https://scihub.copernicus.eu/)

**Description:**  
Offers free access to Sentinel satellite imagery, which can be used for land monitoring and disaster management in China.

**How to Access:**  
Free registration is required to download data.

**License:**  
Open Access; free for use with attribution.

---

### 10. Humanitarian Data Exchange (HDX)

**Website:** [data.humdata.org](https://data.humdata.org/group/chn)

**Description:**  
Managed by the United Nations OCHA, HDX provides datasets including administrative boundaries and humanitarian data for China.

**How to Access:**  
Data can be downloaded without registration.

**License:**  
Varies by dataset; check individual terms.

---

### Additional Resources

- **Asia-Pacific Data Research Center (APDRC)**
  - **Website:** [apdrc.soest.hawaii.edu](http://apdrc.soest.hawaii.edu/)
  - **Description:** Provides oceanographic and atmospheric data relevant to the Asia-Pacific region, including China.

- **FAO GeoNetwork**
  - **Website:** [www.fao.org/geonetwork](https://www.fao.org/geonetwork/)
  - **Description:** Offers geospatial data related to agriculture, forestry, and fisheries, some of which cover China.

- **United Nations Environment Programme (UNEP) Environmental Data Explorer**
  - **Website:** [geodata.grid.unep.ch](https://geodata.grid.unep.ch/)
  - **Description:** Provides datasets on environmental factors affecting China.

---

## Considerations for Using the Data

- **Licensing and Usage Rights:**
  - Always check the data usage licenses or terms of service for each dataset.
  - **Attribution:** Most datasets require proper attribution to the data provider.
  - **Commercial Use:** Some datasets may have restrictions on commercial use.

- **Data Formats:**
  - Common formats include Shapefile, GeoJSON, GeoTIFF, and KML.
  - Ensure your GIS software supports the required formats.

- **Coordinate Systems:**
  - China uses specific coordinate systems like GCJ-02 and BD-09.
  - May require transformations if integrating with global datasets.

- **Data Quality and Coverage:**
  - Coverage may vary between urban and rural areas.
  - Always review the metadata for information on data accuracy and update frequency.

- **Regulatory Compliance:**
  - Be aware of China's regulations regarding geospatial data, especially for publication or distribution.

---

## How to Access and Use the Data

1. **Download the Datasets:**

   - Visit the provided links to access datasets.
   - Register if necessary.

2. **Use GIS Software:**

   - **QGIS:** Free and open-source.
     - **Download:** [QGIS Official Site](https://www.qgis.org/)
   - **ArcGIS Pro:** Commercial software.
     - **Download:** [Esri ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview)

3. **Data Processing:**

   - Use libraries like **GDAL** or **GeoPandas** for data manipulation.
     - **GDAL Documentation:** [GDAL](https://gdal.org/)
     - **GeoPandas Documentation:** [GeoPandas](https://geopandas.org/)

4. **Coordinate Transformations:**

   - For China-specific coordinate systems, use appropriate transformation tools or libraries.

5. **Visualization:**

   - Create maps using GIS software.
   - Utilize online platforms like **Kepler.gl** for web-based visualization.
     - **Kepler.gl:** [Kepler.gl Website](https://kepler.gl/)

6. **Metadata Review:**

   - Always review the metadata associated with each dataset for detailed information.

---

## Summary

- **Microsoft:**
  - Offers detailed **Building Footprints** datasets for multiple countries.
  - Provides mapping services via **Bing Maps API**.

- **Google:**
  - Released the **Open Buildings** dataset for Africa and Asia.
  - Offers mapping data through **Google Maps Platform** APIs.

- **China-Specific Data:**
  - Numerous sources provide open-source geospatial data specific to China.
  - **OpenStreetMap (OSM):** Extensive data on roads, buildings, and transportation.
  - **National Data Centers:** Specialized datasets from Chinese organizations.

- **Access Considerations:**
  - **Licenses:** Generally allow free use with proper attribution.
  - **APIs:** Subject to terms of service; may not permit bulk data extraction.

---

**Note:** Always ensure compliance with the licensing terms and conditions of each dataset or service. When using APIs, adhere to usage policies to avoid violations.

---