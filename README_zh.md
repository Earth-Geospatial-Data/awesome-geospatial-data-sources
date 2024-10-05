[English](./README.md) | [简体中文](./README_zh.md)



## 道路、建筑物和交通网络的地理空间数据源

本文档提供了与地理空间数据相关的数据集的综合列表，包括道路、建筑物、交通网络以及中国和其他地区的各种环境和人口信息。这些数据集由微软、谷歌以及各个国际和中国组织提供。

---

### 目录

- [道路、建筑物和交通网络的地理空间数据源](#道路建筑物和交通网络的地理空间数据源)
  - [目录](#目录)
- [微软数据集](#微软数据集)
  - [1. 微软建筑物轮廓](#1-微软建筑物轮廓)
  - [2. 微软地图和必应地图 API](#2-微软地图和必应地图-api)
  - [3. 微软对 OpenStreetMap（OSM）的贡献](#3-微软对-openstreetmaposm的贡献)
- [谷歌数据集](#谷歌数据集)
  - [1. 谷歌开放建筑物数据集](#1-谷歌开放建筑物数据集)
  - [2. 谷歌地图平台和 API](#2-谷歌地图平台和-api)
  - [3. 谷歌研究数据集](#3-谷歌研究数据集)
- [中国的开源地理空间数据源](#中国的开源地理空间数据源)
  - [1. OpenStreetMap（OSM）](#1-openstreetmaposm)
  - [2. Natural Earth](#2-natural-earth)
  - [3. GADM（全球行政区划数据库）](#3-gadm全球行政区划数据库)
  - [4. SRTM 高程数据](#4-srtm-高程数据)
  - [5. NASA 地球数据](#5-nasa-地球数据)
  - [6. 中国科学院数据中心](#6-中国科学院数据中心)
    - [a. 国家地球系统科学数据中心](#a-国家地球系统科学数据中心)
    - [b. 地球系统科学数据共享平台](#b-地球系统科学数据共享平台)
  - [7. WorldPop 项目](#7-worldpop-项目)
  - [8. 中国国家测绘地理信息局全球土地覆盖](#8-中国国家测绘地理信息局全球土地覆盖)
  - [9. 哨兵卫星数据](#9-哨兵卫星数据)
  - [10. 人道主义数据交换（HDX）](#10-人道主义数据交换hdx)
  - [附加资源](#附加资源)
- [使用数据的注意事项](#使用数据的注意事项)
- [如何获取和使用数据](#如何获取和使用数据)
- [总结](#总结)

---

## 微软数据集

### 1. 微软建筑物轮廓

**描述：**  
使用深度学习算法生成的高分辨率建筑物轮廓数据集。适用于城市规划、灾害响应和制图项目。

**覆盖范围：**

- **美国：** 超过 1.25 亿个建筑物轮廓。
- **加拿大：** 超过 1200 万个建筑物轮廓。
- **非洲：** 超过 3 亿个建筑物轮廓，涵盖多个国家。
- **韩国和澳大利亚：** 包含这些国家的建筑物轮廓。

**获取方式：**

- **GitHub 仓库：**
  - [美国建筑物轮廓](https://github.com/Microsoft/USBuildingFootprints)
  - [加拿大建筑物轮廓](https://github.com/microsoft/CanadianBuildingFootprints)
  - [非洲建筑物轮廓](https://github.com/microsoft/AfricaBuildingFootprints)
  - [韩国和澳大利亚建筑物轮廓](https://github.com/microsoft/BuildingFootprints)

**数据格式：**  
GeoJSON 或 Shapefile 格式。

**许可：**  
Open Data Commons Open Database License (ODbL)。

---

### 2. 微软地图和必应地图 API

**描述：**  
通过必应地图提供广泛的地图服务。开发者可以通过 API 访问道路、交通和运输数据。

**获取方式：**

- **必应地图 API：** [微软必应地图平台](https://www.microsoft.com/maps)

**文档：**  
提供了如何使用 API 访问各种类型地理空间数据的指南。

**许可与使用：**  
需要 API 密钥；使用受条款和条件约束，根据请求量和类型可能产生费用。

---

### 3. 微软对 OpenStreetMap（OSM）的贡献

**描述：**  
微软通过提供 AI 生成的地图特征来改善 OSM 数据质量。

**获取方式：**

- **OpenStreetMap：** [www.openstreetmap.org](https://www.openstreetmap.org)

**注意：**  
贡献给 OSM 的数据可根据 Open Database License 免费获取。

---

## 谷歌数据集

### 1. 谷歌开放建筑物数据集

**描述：**  
使用机器学习模型从卫星图像中提取的建筑物位置和轮廓。

**覆盖范围：**

- **非洲：** 超过 5 亿个建筑物轮廓。
- **亚太地区：** 包括孟加拉国、印度尼西亚、菲律宾等国家。

**获取方式：**

- **网站：** [谷歌开放建筑物](https://sites.research.google/open-buildings/)
- **谷歌云存储：** [开放建筑物数据](https://console.cloud.google.com/storage/browser/open-buildings-data)

**数据格式：**  
CSV 和 GeoJSON 格式。

**许可：**  
Creative Commons Attribution 4.0 International License (CC BY 4.0)。

---

### 2. 谷歌地图平台和 API

**描述：**  
通过各种 API 访问全面的道路、建筑物和交通数据。

**获取方式：**

- **谷歌地图 API：** [谷歌地图平台](https://developers.google.com/maps/documentation)
  - **Maps API**
  - **Routes API**
  - **Places API**

**许可与使用：**  
需要 API 密钥；服务根据使用量计费，提供免费额度。

**注意：**  
从谷歌地图 API 批量下载数据违反服务条款。

---

### 3. 谷歌研究数据集

**描述：**  
谷歌 AI 和研究部门发布的各种数据集，可能包含与建筑物和交通相关的地理空间数据。

**获取方式：**

- **数据集搜索：** [谷歌数据集搜索](https://datasetsearch.research.google.com/)

**示例数据集：**

- **开放图像数据集**

**许可：**  
根据具体数据集而定；请务必查看各自的许可协议。

---

## 中国的开源地理空间数据源

### 1. OpenStreetMap（OSM）

**网站：** [www.openstreetmap.org](https://www.openstreetmap.org)

**描述：**  
一个提供全球免费、可编辑地图数据的协作项目，包括中国的详细地理空间信息，如道路、建筑物和兴趣点。

**获取方式：**

- **中国特定数据提取：** [Geofabrik 中国数据提取](https://download.geofabrik.de/asia/china.html)
- **自定义查询：** [Overpass API](https://overpass-turbo.eu/)

**许可：**  
Open Database License (ODbL)。

---

### 2. Natural Earth

**网站：** [www.naturalearthdata.com](https://www.naturalearthdata.com)

**描述：**  
提供各种比例的免费矢量和栅格地图数据，包括行政边界、自然特征和文化地标。

**获取方式：**  
可直接从其网站以 Shapefile 或 GeoPackage 格式下载数据。

**许可：**  
公共领域。

---

### 3. GADM（全球行政区划数据库）

**网站：** [www.gadm.org](https://gadm.org/)

**描述：**  
提供全球各国的详细行政边界数据，包括中国的省、市和县。

**获取方式：**  
可免费下载 Shapefile 和 GeoJSON 等格式的数据。

**许可：**  
免费供学术使用；商业用途需获得许可。

---

### 4. SRTM 高程数据

**网站：** [earthexplorer.usgs.gov](https://earthexplorer.usgs.gov/)

**描述：**  
提供全球 30 米分辨率的数字高程数据，适用于中国的地形分析。

**获取方式：**  
使用 USGS EarthExplorer 门户搜索并下载 SRTM 数据。

**许可：**  
公共领域。

---

### 5. NASA 地球数据

**网站：** [earthdata.nasa.gov](https://earthdata.nasa.gov/)

**描述：**  
提供卫星影像和地理空间数据集，包括 MODIS 土地覆盖数据和与中国相关的气候数据。

**获取方式：**  
需要免费注册。通过 [Earthdata Search](https://search.earthdata.nasa.gov/) 访问数据。

**许可：**  
通常免费使用，需注明出处。

---

### 6. 中国科学院数据中心

#### a. 国家地球系统科学数据中心

**网站：** [www.geodata.cn](http://www.geodata.cn)

**描述：**  
提供特定于中国的地理空间数据集，包括环境、生态和地理数据。

**获取方式：**  
可能需要注册，某些数据集可能需要批准。

**许可：**  
根据具体数据集而定；请查看各自的使用条款。

#### b. 地球系统科学数据共享平台

**网站：** [www.data.cma.cn](http://www.data.cma.cn)

**描述：**  
提供气象数据、气候统计和相关地理空间数据集。

**获取方式：**  
注册后可免费访问；某些数据可能有使用限制。

**许可：**  
根据具体数据集而定；请查看各自的使用条款。

---

### 7. WorldPop 项目

**网站：** [www.worldpop.org](https://www.worldpop.org/)

**描述：**  
提供高分辨率的人口密度地图和人口统计数据，适用于中国的城市规划和公共卫生研究。

**获取方式：**  
可直接下载 GeoTIFF 格式的数据。

**许可：**  
Creative Commons Attribution 4.0 International License (CC BY 4.0)。

---

### 8. 中国国家测绘地理信息局全球土地覆盖

**网站：** [www.globallandcover.com](http://www.globallandcover.com/)

**描述：**  
提供中国 30 米分辨率的详细土地覆盖图，适用于环境和农业研究。

**获取方式：**  
注册后可免费下载数据。

**许可：**  
请查看网站上的具体条款和条件。

---

### 9. 哨兵卫星数据

**网站：** [scihub.copernicus.eu](https://scihub.copernicus.eu/)

**描述：**  
免费提供哨兵卫星影像，可用于中国的土地监测和灾害管理。

**获取方式：**  
需要免费注册才能下载数据。

**许可：**  
开放访问；免费使用，需注明出处。

---

### 10. 人道主义数据交换（HDX）

**网站：** [data.humdata.org](https://data.humdata.org/group/chn)

**描述：**  
由联合国人道主义事务协调厅管理，提供包括中国行政边界和人道主义数据的数据集。

**获取方式：**  
无需注册即可下载数据。

**许可：**  
根据具体数据集而定；请查看各自的使用条款。

---

### 附加资源

- **亚太数据研究中心（APDRC）**
  - **网站：** [apdrc.soest.hawaii.edu](http://apdrc.soest.hawaii.edu/)
  - **描述：** 提供与亚太地区（包括中国）相关的海洋和大气数据。

- **粮农组织 GeoNetwork**
  - **网站：** [www.fao.org/geonetwork](https://www.fao.org/geonetwork/)
  - **描述：** 提供与农业、林业和渔业相关的地理空间数据，其中一些涵盖中国。

- **联合国环境规划署（UNEP）环境数据浏览器**
  - **网站：** [geodata.grid.unep.ch](https://geodata.grid.unep.ch/)
  - **描述：** 提供影响中国的环境因素数据集。

---

## 使用数据的注意事项

- **许可和使用权：**
  - 始终检查每个数据集的使用许可或服务条款。
  - **署名：** 大多数数据集要求对数据提供者进行适当的署名。
  - **商业用途：** 某些数据集可能对商业用途有限制。

- **数据格式：**
  - 常见格式包括 Shapefile、GeoJSON、GeoTIFF 和 KML。
  - 确保您的 GIS 软件支持所需的格式。

- **坐标系统：**
  - 中国使用特定的坐标系统，如 GCJ-02 和 BD-09。
  - 如果与全球数据集集成，可能需要进行转换。

- **数据质量和覆盖范围：**
  - 城市和农村地区的覆盖范围可能有所不同。
  - 始终查看元数据以获取数据准确性和更新频率的信息。

- **法规遵从性：**
  - 了解中国关于地理空间数据的法规，特别是在涉及发布或分发时。

---

## 如何获取和使用数据

1. **下载数据集：**

   - 访问提供的链接获取数据集。
   - 如有必要，进行注册。

2. **使用 GIS 软件：**

   - **QGIS：** 免费和开源。
     - **下载：** [QGIS 官方网站](https://www.qgis.org/)
   - **ArcGIS Pro：** 商业软件。
     - **下载：** [Esri ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview)

3. **数据处理：**

   - 使用 **GDAL** 或 **GeoPandas** 等库进行数据操作。
     - **GDAL 文档：** [GDAL](https://gdal.org/)
     - **GeoPandas 文档：** [GeoPandas](https://geopandas.org/)

4. **坐标转换：**

   - 对于中国特定的坐标系统，使用适当的转换工具或库。

5. **可视化：**

   - 使用 GIS 软件创建地图。
   - 利用 **Kepler.gl** 等在线平台进行基于网络的可视化。
     - **Kepler.gl：** [Kepler.gl 网站](https://kepler.gl/)

6. **元数据审查：**

   - 始终查看每个数据集的元数据以获取详细信息。

---

## 总结

- **微软：**
  - 为多个国家提供详细的 **建筑物轮廓** 数据集。
  - 通过 **必应地图 API** 提供地图服务。

- **谷歌：**
  - 发布了针对非洲和亚洲的 **开放建筑物** 数据集。
  - 通过 **谷歌地图平台** API 提供地图数据。

- **中国特定数据：**
  - 许多来源提供特定于中国的开源地理空间数据。
  - **OpenStreetMap（OSM）：** 提供有关道路、建筑物和交通的广泛数据。
  - **国家数据中心：** 中国机构提供的专业数据集。

- **访问注意事项：**
  - **许可：** 一般允许在适当署名的情况下免费使用。
  - **API：** 受服务条款约束；可能不允许批量数据提取。

---

**注意：** 始终确保遵守每个数据集或服务的许可条款和条件。使用 API 时，遵守使用政策以避免违规。

---