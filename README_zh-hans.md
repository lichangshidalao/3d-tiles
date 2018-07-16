<p align="center"><img src="figures/Cesium3DTiles.png" /></p>

Specification for streaming massive heterogeneous **3D** geospatial datasets.

3D Tiles has entered the Open Geospatial Consortium (OGC) [Community Standard](https://cesium.com/blog/2016/09/06/3d-tiles-and-the-ogc/) process.

---

Created by the <a href="http://cesiumjs.org/">Cesium team</a> and built on <a href="https://www.khronos.org/gltf">glTF</a>.<br/>

<a href="http://cesiumjs.org/"><img src="figures/cesium.jpg" height="40" /></a> <a href="https://www.khronos.org/gltf"><img src="figures/gltf.png" height="40" /></a>

Editor: Patrick Cozzi, [@pjcozzi](https://twitter.com/pjcozzi), [pcozzi@agi.com](mailto:pcozzi@agi.com).

## 谁在使用 3D Tiles?

![](figures/users/composer.jpg) [Cesium Composer](https://www.cesium.com/) converters | ![](figures/users/AGI.jpg) [Cesium](http://cesiumjs.org/) |
|:---:|:---:|
![](figures/users/CC3D.jpg) [CyberCity3D](http://www.cybercity3d.com/) | ![](figures/users/virtualcitySYSTEMS.jpg) [virtualcitySYSTEMS](http://www.virtualcitysystems.de/en/)  |
![](figures/users/Cityzenith.jpg) [Cityzenith](http://www.cityzenith.com/) | ![](figures/users/Fraunhofer.jpg) [Fraunhofer](http://www.fraunhofer.de/en.html)  |
![](figures/users/Vricon.jpg) [Vricon](http://www.vricon.com/) | ![](figures/users/swisstopo.jpg) Federal Office of Topography <br/> [swisstopo](https://map.geo.admin.ch)  |
![](figures/users/BentleyContextCapture.jpg) [Bentley ContextCapture](https://www.linkedin.com/pulse/contextcapture-web-publishing-cesium-aude-camus) | ![](figures/users/microstation.jpg) [Bentley MicroStation](https://www.bentley.com/en/products/brands/microstation) (in progress) |
![](figures/users/aero3dpro.jpg) [aero3Dpro](http://aero3dpro.com.au/) | ![](figures/users/entwine.jpg) [Entwine](http://cesium.entwine.io/) |
![](figures/users/3dps.jpg) [GeoRocket](https://georocket.io/) 3DPS | ![](figures/users/osgjs.jpg) [OSGJS](http://osgjs.org/) (in progress) |
![](figures/users/data61.jpg) [CSIRO Data61](https://www.data61.csiro.au/) | ![](figures/users/gamesim.jpg) [GameSim Conform](https://www.gamesim.com/3d-geospatial-conform/) |
![](figures/users/sitesee.jpg) [SiteSee](http://www.sitesee.com.au/) (using three.js) | [Safe FME](https://www.safe.com/how-it-works/) |
[Peaxy](https://peaxy.net/) | ![](figures/users/pointcloudconverter.jpg) [Prototype Point Cloud Converter](https://github.com/mattshax/cesium_pnt_generator) |
![](figures/users/virtualgis.jpg) [VirtualGIS](https://www.virtualgis.io/) | ![](figures/users/grandlyon.jpg) [LOPoCS ](https://github.com/Oslandia/lopocs) and [py3dtiles](https://github.com/Oslandia/py3dtiles)
![](figures/users/itowns.jpg) [iTowns 2](https://github.com/iTowns/itowns) | ![](figures/users/osm-cesium-3d-tiles.jpg) [osm-cesium-3d-tiles](https://github.com/kiselev-dv/osm-cesium-3d-tiles) |
![](figures/users/geopipe.jpg) [geopipe](https://geopi.pe/) | ![](figures/users/poulain.jpg) [3D Digital Territory Lab](https://cesiumjs.org/demos/grandlyon/) |  
![](figures/users/cesme.jpg) [Çeşme 3D City Model](https://cesiumjs.org/demos/Cesme3DCityModel/) |

## 在线应用

* [NYC](https://cesiumjs.org/NewYork/index.html) by AGI
* [3D Swiss Federal Geoportal with 3 million buildings](https://map.geo.admin.ch/?topic=ech&lang=en&bgLayer=ch.swisstopo.pixelkarte-farbe&layers_visibility=false,false,false,false&layers_timestamp=18641231,,,&lon=8.82169&lat=47.21822&elevation=1213&heading=20.819&pitch=-37.770&layers=ch.swisstopo.zeitreihen,ch.bfs.gebaeude_wohnungs_register,ch.bav.haltestellen-oev,ch.swisstopo.swisstlm3d-wanderwege) by Swisstopo and AGI
* Bentley **ContextCapture**
   * [Orlando](https://d3h9zulrmcj1j6.cloudfront.net/Orlando_Cesium/App/index.html)
   * [Marseille](https://d3h9zulrmcj1j6.cloudfront.net/Marseille_Cesium/App/index.html)
* **aero3Dpro**
   * [Impact Of Coastal Erosion in NightCliff, Darwin](https://sample.aero3dpro.com.au/NightCliffe_2016/App/index.html), [Adelaide](https://adelaide.aero3d.com.au/App/index.html)
   * [Future buildings in Melbourne](https://sample.aero3dpro.com.au/Melbourne/App/index_kml.html)
* **virtualcityMAP** by virtualcitySYSTEMS
   * [10.1 million buildings](http://nrw.virtualcitymap.de/) in North Rhine-Westphalia (34.098 km²)
   * [Textured buildings](http://demo.virtualcitymap.de/?lang=en&layerToActivate=buildings&layerToDeactivate=buildings_untextured)
   * [Textured buildings + point clouds](http://demo.virtualcitymap.de/?lang=en&layerToActivate=buildings&layerToActivate=pointcloud&layerToDeactivate=buildings_untextured&cameraPosition=13.36091%2C52.50023%2C1614.17078&groundPosition=13.36085%2C52.51388%2C33.22668&distance=2192.72&pitch=-46.14&heading=359.84&roll=360.00)
   * [building solar potential](https://t.co/o2P6FXcW7L)
   * [Berlin Atlas of Economy](http://www.businesslocationcenter.de/wab/maps/main/) (switch to 3D and zoom in)
* [Downtown Miami](http://cybercity3d.s3-website-us-east-1.amazonaws.com/?city=Miami) by CyberCity3D and AGI
* [Entwine demos](http://cesium.entwine.io/), including [~4.7 billion points in NYC](http://cesium.entwine.io/?resource=nyc)
* AEROmetrex
   * [Impact Of Coastal Erosion in NightCliff, Darwin](https://sample.aero3dpro.com.au/NightCliffe_2016/App/index.html)
   * [10cm Melbourne, Australia metro](http://sample.aero3dpro.com.au/Melbourne/App/index.html)
   * [Gold Coast, Australia](http://sample.aero3dpro.com.au/Gold_Coast_Cesium/App/index.html)
   * [10cm Sydney, Australia](http://sample.aero3dpro.com.au/Sydney/App/index.html)
   * [Philadelphia](https://sample.aero3dpro.com.au/PHL_Cesium/App/index.html)
   * [10cm Brisbane](https://sample.aero3dpro.com.au/BrisbaneCBD/App/index.html)
* **VirtualGIS**: [2200 Miles of Pipeline](http://kxldemo.virtualgis.io)
* [UrbISOnline: 230,000 buildings Brussels](https://urbisonline.brussels/) ([article](http://bric.brussels/en/news_publications/news/urbis-adm-3d?set_language=en))

Also see the [3D Tiles Showcases video on YouTube](https://youtu.be/KoGc-XDWPDE).

---

## 目录

* [资源](#资源)
* [Spec status](#spec-status)
* [介绍](#介绍)
* [瓦片元数据](#瓦片元数据)
   * [坐标系和单位](#坐标系和单位)
   * [瓦片变换](#瓦片变换)
   * [Viewer request volume](#viewer-request-volume)
* [tileset.json](#tilesetjson)
   * [外部瓦片集](#外部瓦片集)
   * [包围体的空间相干性](#包围体的空间相干性)
   * [创建空间数据结构](#创建空间数据结构)
      * [K-d trees](#k-d-trees)
      * [四叉树](#四叉树)
      * [四叉树](#四叉树)
      * [网格](#网格)
* [瓦片格式](#瓦片格式)
* [声明式样式](#声明式样式)
* [问答导航](#问答导航)
* [鸣谢](#鸣谢)
* [Data credits](#data-credits)

## 资源

* [3D Tiles 介绍](https://cesium.com/blog/2015/08/10/introducing-3d-tiles/) - the motivation for and principles of 3D Tiles.  Read this first if you are new to 3D Tiles.
* [下一代 3D Tiles](https://cesium.com/blog/2017/07/12/the-next-generation-of-3d-tiles/) - future plans for 3D Tiles.
* **Cesium implementation**
   * Download [Cesium 1.35 or later](https://cesiumjs.org/downloads/) and check out the [Sandcastle examples labeled '3D Tiles'](http://cesiumjs.org/Cesium/Apps/Sandcastle/index.html?src=3D%20Tiles%20BIM.html&label=3D%20Tiles).
   * [Roadmap](https://github.com/AnalyticalGraphicsInc/cesium/issues/3241).
* **范例数据**
   * [3d-tiles-samples](https://github.com/AnalyticalGraphicsInc/3d-tiles-samples) - sample tilesets for learning how to use 3D Tiles
   * [Simple 3D tilesets](https://github.com/AnalyticalGraphicsInc/cesium/tree/master/Specs/Data/Cesium3DTiles) used in the Cesium unit tests.
* **工具**
   * [3d-tiles-tools](https://github.com/AnalyticalGraphicsInc/3d-tiles-tools) - upcoming tools for debugging, analyzing, and validating 3D Tiles tilesets.
* **精选演讲**
   * _3D Tiles in Action_ ([pdf](https://cesium.com/presentations/files/3DTilesInAction.pdf)) at FOSS4G 2017.
   * _Point Clouds with 3D Tiles_ ([pdf](https://cesium.com/presentations/files/PointCloudsWith3DTiles.pdf)) at the OGC Technical Committee Meeting (June 2017).
   * _The Open Cesium 3D Tiles Specification: Bringing Massive Geospatial 3D Scenes to the Web_ ([pptx](https://cesium.com/presentations/files/Web3D-2016-3DTilesTutorial.pptx), [example tilesets](https://github.com/AnalyticalGraphicsInc/3d-tiles-samples)) at Web3D 2016.  90-minute technical tutorial.
   * _3D Tiles: Beyond 2D Tiling_ ([pdf](https://cesium.com/presentations/files/FOSS4GNA2016/3DTiles.pdf), [video](https://www.youtube.com/watch?v=I1vYCrMKKEE)) at FOSS4G NA 2016.
   * _3D Tiles motivation and ecosystem update_ ([pdf](https://cesium.com/presentations/files/3D-Tiles-OGC-DC.pdf)) at the OGC Technical Committee Meeting (March 2016).
   * _3D Tiles intro_ ([pdf](https://cesium.com/presentations/files/SIGGRAPH2015/Cesium3DTiles.pdf)) at the Cesium BOF at SIGGRAPH 2015.
* **精选文章**
   * [Millimeter Precision Point Clouds with Cesium and 3D Tiles](https://cesium.com/blog/2018/06/27/millimeter-precision-point-clouds/). June 2018
   * [OneSky Using Cesium / 3D Tiles For Volumetric Airspace Visualization](https://onesky.blog/2018/04/16/onesky-using-cesium-3dtiles-for-volumetric-airspace-visualization/). April 2018.
   * [Draco Compressed Meshes with glTF and 3D Tiles](https://cesium.com/blog/2018/04/09/draco-compression/). April 2018.
   * [OGC Testbed-13: 3D Tiles and I3S Interoperability and Performance ER](http://docs.opengeospatial.org/per/17-046.html). March 2018.
   * [Historic Pharsalia Cabin Point Cloud Using Cesium & 3D Tiles](https://cesium.com/blog/2018/02/05/historic-pharsalia-cabin-point-cloud/). February 2018.
   * [Cesium's Participation in OGC Testbed 13](https://cesium.com/blog/2018/02/06/citygml-testbed-13/). February 2018.
   * [Adaptive Subdivision of 3D Tiles](https://cesium.com/blog/2017/08/11/Adaptive-Subdivision-of-3D-Tiles/). August 2017.
   * [Aerometrex and 3D Tiles](https://cesium.com/blog/2017/07/26/aerometrex-melbourne/). July 2017.
   * [Duke Using 3D Tiles for Excavation in Vulci](https://cesium.com/blog/2017/05/22/duke-vulci-photogrammetry/). May 2017.
   * [GERST Engineers, Agisoft PhotoScan, and 3D Tiles](https://cesium.com/blog/2017/05/19/gerst-engineers/). May 2017.
   * [Skipping Levels of Detail](https://cesium.com/blog/2017/05/05/skipping-levels-of-detail/). May 2017.
   * [Infrastructure Visualisation using 3D Tiles](http://www.sitesee.com.au/news/3dtiles). April 2017.
   * [SiteSee Photogrammetry and 3D Tiles](https://cesium.com/blog/2017/04/12/site-see-3d-tiles/). April 2017.
   * [Optimizing Spatial Subdivisions in Practice](https://cesium.com/blog/2017/04/04/spatial-subdivision-in-practice/). April 2017.
   * [Optimizing Subdivisions in Spatial Data Structures](https://cesium.com/blog/2017/03/30/spatial-subdivision/). March 2017.
   * [What's new in 3D Tiles?](https://cesium.com/blog/2017/03/29/whats-new-in-3d-tiles/) March 2017.
   * [Streaming 3D Capture Data using 3D Tiles](https://cesium.com/blog/2017/03/06/3d-scans/). March 2017.
   * [Visualizing Massive Models using 3D Tiles](https://cesium.com/blog/2017/02/21/massive-models/). February 2017.
   * [Bringing City Models to Life with 3D Tiles](https://medium.com/@CyberCity3D/bringing-city-models-to-life-with-3d-tiles-620d5884edf3#.mqxuj7kqd). September 2016.
   * [Using Quantization with 3D Models](https://cesium.com/blog/2016/08/08/cesium-web3d-quantized-attributes/). August 2016.
* **新闻**
   * [3D Tiles thread on the Cesium forum](https://groups.google.com/forum/#!topic/cesium-dev/tCCooBxpZFU) - get the latest 3D Tiles news and ask questions here.

## Spec status

The 3D Tiles spec is pre-1.0 (indicated by `"version": "0.0"` in tileset.json).  We expect a draft 1.0 version and the Cesium implementation to stabilize in 2017; see the [remaining items](https://github.com/AnalyticalGraphicsInc/3d-tiles/issues?q=is%3Aissue+is%3Aopen+label%3A%22draft+1.0%22).

**Draft 1.0 Plans**

Topic  | Status
---|---
[tileset.json](#tilesetjson)<br /><br />The tileset's spatial hierarchy  | :white_check_mark: **Solid base**, will add features as needed
[Batched 3D Model](TileFormats/Batched3DModel/README.md) (*.b3dm)<br /><br />Textured terrain and surfaces, 3D building exteriors and interiors, massive models, ...  | :white_check_mark: **Solid base**, only minor, if any, changes expected
[Instanced 3D Model](TileFormats/Instanced3DModel/README.md) (*.i3dm)<br /><br />Trees, windmills, bolts, ... | :white_check_mark: **Solid base**, only minor, if any, changes expected
[Point Cloud](TileFormats/PointCloud/README.md) (*.pnts)<br /><br />Massive number of points | :white_check_mark: **Solid base**, only minor, if any, changes expected
[Vector Data](TileFormats/VectorData/README.md) (*.vctr)<br /><br />Polygons, polylines, and placemarks | :white_circle: **In progress**, [#124](https://github.com/AnalyticalGraphicsInc/3d-tiles/pull/124/files)
[Composite](TileFormats/Composite/README.md) (*.cmpt)<br /><br />Combine heterogeneous tile formats | :white_check_mark: **Solid base**, only minor, if any, changes expected
[声明式样式](Styling/README.md)<br/><br/>Style features using per-feature metadata  | :white_check_mark: **Solid base**, will add features/functions as needed, [#2](https://github.com/AnalyticalGraphicsInc/3d-tiles/issues/2)

**Post Draft 1.0 Plans**

Topic  | Status
---|---
Terrain v2  | :white_circle: **Not started**, [quantized-mesh](https://cesiumjs.org/data-and-assets/terrain/formats/quantized-mesh-1.0.html) is a good starting point; in the meantime, folks are using [Batched 3D Model](TileFormats/Batched3DModel/README.md)
[OpenStreetMap](TileFormats/OpenStreetMap/README.md)  | :white_circle: **Not started** Currently folks are using [Batched 3D Model](TileFormats/Batched3DModel/README.md)
Stars  | :white_circle: **Not started**

For spec work in progress, [watch this repo](https://github.com/AnalyticalGraphicsInc/3d-tiles/subscription) and browse the [issues](https://github.com/AnalyticalGraphicsInc/3d-tiles/issues).

## 介绍

在 3D Tiles 中，_瓦片集_ 是组织在空间数据结构 _树_ 中的一组 _瓦片_。每个瓦片包括一个包围体，包裹着它的内容。树具有空间相干性：子瓦片的内容完全包含在父瓦片的包围盒中。为了保持灵活性，树可以是任何具有空间相干性的空间数据结构，包括K-D树、四叉树、八叉树和网格。

![](figures/tree.png)

为了支持各种数据集（从规则划分的地形，到不与经线或纬线对齐的城市，或任意点云）的紧密贴合，包围体可以是定向的包围盒，包围球，或者由最大最小经纬度、高度定义的地理范围。

_TODO：添加各种包围体的截屏图片。_

瓦片引用了一个或一组 _特征_，例如建筑物或树的 3D 模型，点云中的点，矢量数据集中的多边形、多段线和点。为了减少客户端的加载时间和 WebGL 绘制的请求时间，这些特征有可能被处理成单一的基本特征。

## 瓦片元数据

瓦片的元数据（不是实际的内容）使用 JSON 定义。例如：
```json
{
  "boundingVolume": {
    "region": [
      -1.2419052957251926,
      0.7395016240301894,
      -1.2415404171917719,
      0.7396563300150859,
      0,
      20.4
    ]
  },
  "geometricError": 43.88464075650763,
  "refine" : "ADD",
  "content": {
    "boundingVolume": {
      "region": [
        -1.2418882438584018,
        0.7395016240301894,
        -1.2415422846940714,
        0.7396461198389616,
        0,
        19.4
      ]
    },
    "url": "2/0/0.b3dm"
  },
  "children": [...]
}
```
`boundingVolume.region` 是一个由6个数字组成的数组，通过地理范围定义了包围体，坐标系为WGS84 / EPSG:4326，按照`[west, south, east, north, minimum height, maximum height]`的顺序进行排序。经纬度的单位是弧度，高度的单位是米（以 [WGS84 ellipsoid](http://earth-info.nga.mil/GandG/publications/tr8350.2/wgs84fin.pdf) 为高程原点）。除了 `region` 以外, 也可以使用其他包围体（如 `box` 和 `sphere`）。

`geometricError` 属性为一个单位为米的非负数，定义了误差，在瓦片渲染但是其子元素未渲染时引入。在运行时，几何误差被用来计算 _Screen-Space Error_ (SSE)，即以像素度量的误差。SSE 决定 _Hierarchical Level of Detail_ (HLOD) refinement, 即瓦片对于当前视图而言是否已经足够详细，是否需要加载子元素。

可选属性 `viewerRequestVolume` （前例中未使用）定义了一个体，该属性与 `boundingVolume` 属性采用了相同的结构。在该瓦片被请求和根据 `geometricError` refine 之前，视点必须在该范围内。参见 [Viewer request volume](#viewer-request-volume) 部分。

`refine` 属性为 string 属性，可为 `"REPLACE"`（表示替代优化）或 `"ADD"`（表示增加优化）。该属性在根瓦片中是必须的，在其他瓦片中是可选的。如果未指定 `refine` 属性，它将从它的父瓦片中继承。

`content` 属性为 object 属性，包含该瓦片内容的元数据和一个指向内容的链接。`content.url` 属性为 string 属性，内容是一个指向瓦片内容的绝对或相对 url。在上面的例子中, url `2/0/0.b3dm` 采用了 TMS 拼接方案 `{z}/{y}/{x}.extension`，但这不是必须的。参见 [问答导航](#我应该如何请求第-`n`-级瓦片？)。

url 可以是另一个 tileset.json 文件，瓦片集可以嵌套瓦片集。参见 [外部瓦片集](#外部瓦片集)。

扩展名对 `content.url` 属性而言不是必须的。内容的 [瓦片格式](#瓦片格式) 可以被其文件头部的 `magic` 字段识别，或者当其内容为JSON时，可作为外部瓦片引用。

`content.boundingVolume` 定义了一个与顶层 `boundingVolume` 属性类似的可选包围体。但与顶层 `boundingVolume` 不同的是，`content.boundingVolume` 是一个紧密包围的包围体，刚好将它的内容包在其中。它的使用是为了替代优化，`boundingVolume` 提供了空间相关性，`content.boundingVolume` 使紧凑视图的视截体裁剪成为可能。以下截图展示了 [Canary Wharf](http://cesiumjs.org/CanaryWharf/) 根节点的包围体。`boundingVolume`（显示为红色），包含了瓦片集的整个区域； `content.boundingVolume`（显示为蓝色），仅仅包含了根目录下的四个特征（模型）。

![](figures/contentsBox.png)

`content.boundingVolume` 是可选属性。当不指定该属性时，使用瓦片的包围体来进行裁剪（参见[网格](#网格)）。

可选属性 `transform` （前面的例子中未使用）定义了一个 4×4 的仿射变换矩阵，用来变换瓦片的`content`、`boundingVolume` 和 `viewerRequestVolume`，参见 [瓦片变换](#瓦片变换)。

`children` 是一组用来定义子瓦片的对象。参见 [tileset.json section below](#tilesetjson)。

![](figures/tile.png)

### 坐标系和单位

3D Tiles 采用右手笛卡尔坐标系。_x_ 和 _y_ 的叉乘为 _z_。在局部坐标系中，3D Tiles 将 _z_ 轴指定为上方向。（参见 [瓦片变换](#瓦片变换)）。瓦片集的全局坐标系通常是 [WGS84 coordinates](http://earth-info.nga.mil/GandG/publications/tr8350.2/wgs84fin.pdf)，但非必须。例如，电厂可以在其局部坐标系中完全定义，以便在没有地理环境的情况下与建模工具一起使用。

`b3dm` 和 `i3dm` 瓦片内嵌了 glTF。根据 [glTF 细则](https://github.com/KhronosGroup/glTF/tree/master/specification/1.0#coordinate-system-and-units), glTF 使用的是 _y_ 轴为上的右手笛卡尔坐标系。默认情况下，内嵌模型被认为是 _y_ 轴向上的，但是为了支持各种各样的源数据，包括使用 `asset.gltfUpAxis` WGS84 坐标系直接定义的模型，内嵌 glTF 模型可以通过设置 tileset.json 中的 `asset.gltfUpAxis` 属性来指定 _x_ 轴向上，_y_ 轴向上或者 _z_ 轴向上。通常，程序在运行时应当将 glTF 资源变换成 _z_ 轴向上以与层次包围体保持一致。

所有线性距离的单位都是米。

所有角的单位都是弧度。

3D Tiles 没有明确地储存地图坐标（经度、纬度和高程）。这些值在 WGS84 笛卡尔坐标系中是隐式存在的，这可以提高 GPU 运行效率，因为其中不涉及非仿射坐标转换。3D Tiles 瓦片集可以包括适用于特定程序的元数据，例如地图坐标，但这并非 3D Tiles 规范的一部分。

### 瓦片变换

为了支持局部坐标系（例如：城市瓦片集中的一个建筑瓦片集可以使用自身的坐标系，建筑瓦片集中的一个点云瓦片集可以使用自身的坐标系），每个瓦片可以包含一个可选属性 `transform`。

`transform` 属性是一个以列主序方式储存的 4x4 仿射变换矩阵，用来从瓦片局部坐标系转换至父瓦片坐标系，当父瓦片为根瓦片时，则转换至瓦片集坐标系。

`transform` 的应用范围有
* `tile.content`
   * 每个特征的位置。
   * 为了考虑 [带有缩放时的正确矢量变换](http://www.realtimerendering.com/resources/RTNews/html/rtnews1a.html#art4)，每个特征的法线应当使用 `transform` 矩阵的逆转置矩阵的左上 3×3 矩阵进行变换。
   * `content.boundingVolume`，`content.boundingVolume.region` 已定义的情况除外，在 [WGS84 / EPSG:4326 coordinates](http://spatialreference.org/ref/epsg/wgs-84/) 中进行了明确定义。
* `tile.boundingVolume`，`tile.boundingVolume.region` 已定义的情况除外，在 WGS84 / EPSG:4326 coordinates 中进行了明确定义。
* `tile.viewerRequestVolume`，`tile.viewerRequestVolume.region` 已定义的情况除外，在 WGS84 / EPSG:4326 coordinates 中进行了明确定义。

`transform` 属性不适用于 `geometricError` 属性，`transform` 定义的缩放不会缩放几何误差，几何误差的单位始终是米。

当未指定 `transform` 属性时，默认为单位矩阵：
```json
[
1.0, 0.0, 0.0, 0.0,
0.0, 1.0, 0.0, 0.0,
0.0, 0.0, 1.0, 0.0,
0.0, 0.0, 0.0, 1.0
]
```

像计算机图形学中传统的场景树或节点层次结构一样，从每个瓦片局部坐标到瓦片集的全局坐标系的变换是通过从顶至底遍历整个瓦片集，将子元素的变换矩阵右乘至父元素的变换矩阵来实现的。

下面的 JavaScript 代码展示了如何使用 Cesium 的 [Matrix4](https://github.com/AnalyticalGraphicsInc/cesium/blob/master/Source/Core/Matrix4.js) 和 [Matrix3](https://github.com/AnalyticalGraphicsInc/cesium/blob/master/Source/Core/Matrix3.js) 类进行上述计算。

```javascript
function computeTransforms(tileset) {
    var t = tileset.root;
    var transformToRoot = defined(t.transform) ? Matrix4.fromArray(t.transform) : Matrix4.IDENTITY;

    computeTransform(t, transformToRoot);
}

function computeTransform(tile, transformToRoot) {
    // Apply 4x4 transformToRoot to this tile's positions and bounding volumes

    var inverseTransform = Matrix4.inverse(transformToRoot, new Matrix4());
    var normalTransform = Matrix4.getRotation(inverseTransform, new Matrix3());
    normalTransform = Matrix3.transpose(normalTransform, normalTransform);
    // Apply 3x3 normalTransform to this tile's normals

    var children = tile.children;
    var length = children.length;
    for (var k = 0; k < length; ++k) {
        var child = children[k];
        var childToRoot = defined(child.transform) ? Matrix4.fromArray(child.transform) : Matrix4.clone(Matrix4.IDENTITY);
        childToRoot = Matrix4.multiplyTransformation(transformToRoot, childToRoot, childToRoot);
        computeTransform(child, childToRoot);
    }
}
```

举例说明一个瓦片集的变换矩阵（上面代码中的 `transformToRoot`）：

![](figures/tileTransform.png)

每个瓦片的变换矩阵是：
* `TO`: `[T0]`
* `T1`: `[T0][T1]`
* `T2`: `[T0][T2]`
* `T3`: `[T0][T1][T3]`
* `T4`: `[T0][T1][T4]`

瓦片内容中的位置和法向可能还包含特定的变换矩阵，这些变换矩阵在瓦片的 `transform` 应用 _之前_ 应用（指仿射变换中的右乘操作）。以下是一些例子：
* `b3dm` 和 `i3dm` 瓦片中嵌有 glTF，glTF 定义了自身的节点层次结构，每个节点都有变换矩阵。这些变换矩阵会在 `tile.transform` 应用前应用。
* `i3dm`' 的特征表定义了每个实例的位置、法向和缩放比例，这些参数是为了生成每个实例的 4×4 仿射变换矩阵。这些变换矩阵会在 `tile.transform` 应用前应用。
* 压缩过的属性，例如 `i3dm`、`pnts` 和 `vctr` 特征表中的 `POSITION_QUANTIZED`，以及 `pnts` 中的 `NORMAL_OCT16P`，应当在其他变换应用前先行解压。

因此，上述例子中的完整计算变换矩阵为：
* `TO`: `[T0]`
* `T1`: `[T0][T1]`
* `T2`: `[T0][T2][pnts-specific Feature Table properties-derived transform]`
* `T3`: `[T0][T1][T3][b3dm-specific transform, including the glTF node hierarchy]`
* `T4`: `[T0][T1][T4][i3dm-specific transform, including per-instance Feature Table properties-derived transform and the glTF node hierarchy]`

### Viewer request volume

瓦片的 `viewerRequestVolume` 可以被用来结合多种数据集，并且可以与 [外部瓦片集](#外部瓦片集) 相结合。

下面这个例子中包括一个 `b3dm` 格式的建筑瓦片和一个在建中的 `pnts` 格式的点云瓦片。点云瓦片的 `boundingVolume` 是一个半径为 `1.25`的球体。它还有一个更大的半径为15的球体作为 `viewerRequestVolume`。因为 `geometricError` 为0，当视点在 `viewerRequestVolume` 定义的大球体内时，点云的内容始终被渲染（初始请求时被请求）。

```javascript
"children": [{
  "transform": [
     4.843178171884396,   1.2424271388626869, 0,                  0,
    -0.7993325488216595,  3.1159251367235608, 3.8278032889280675, 0,
     0.9511533376784163, -3.7077466670407433, 3.2168186118075526, 0,
     1215001.7612985559, -4736269.697480114,  4081650.708604793,  1
  ],
  "boundingVolume": {
    "box": [
      0,     0,    6.701,
      3.738, 0,    0,
      0,     3.72, 0,
      0,     0,    13.402
    ]
  },
  "geometricError": 32,
  "content": {
    "url": "building.b3dm"
  }
}, {
  "transform": [
     0.968635634376879,    0.24848542777253732, 0,                  0,
    -0.15986650990768783,  0.6231850279035362,  0.7655606573007809, 0,
     0.19023066741520941, -0.7415493329385225,  0.6433637229384295, 0,
     1215002.0371330238,  -4736270.772726648,   4081651.6414821907, 1
  ],
  "viewerRequestVolume": {
    "sphere": [0, 0, 0, 15]
  },
  "boundingVolume": {
    "sphere": [0, 0, 0, 1.25]
  },
  "geometricError": 0,
  "content": {
    "url": "points.pnts"
  }
}]
```

_TODO: 添加 request volume 和 bounding volume 的对比截图_

更多关于 request volumes 的内容, 参见 [示例瓦片集](https://github.com/AnalyticalGraphicsInc/3d-tiles-samples/tree/master/tilesets/TilesetWithRequestVolume) 和 [示例视频](https://www.youtube.com/watch?v=PgX756Yzjf4).

## tileset.json

_tileset.json_ 定义了一个瓦片集。下面是  [Canary Wharf](http://cesiumjs.org/CanaryWharf/) tileset.json 的一个子瓦片（完整的 [tileset.json](examples/tileset.json)）：
```json
{
  "asset" : {
    "version": "0.0",
    "tilesetVersion": "e575c6f1-a45b-420a-b172-6449fa6e0a59",
    "gltfUpAxis": "Y"
  },
  "properties": {
    "Height": {
      "minimum": 1,
      "maximum": 241.6
    }
  },
  "geometricError": 494.50961650991815,
  "root": {
    "boundingVolume": {
      "region": [
        -0.0005682966577418737,
        0.8987233516605286,
        0.00011646582098558159,
        0.8990603398325034,
        0,
        241.6
      ]
    },
    "geometricError": 268.37878244706053,
    "content": {
      "url": "0/0/0.b3dm",
      "boundingVolume": {
        "region": [
          -0.0004001690908972599,
          0.8988700116775743,
          0.00010096729722787196,
          0.8989625664878067,
          0,
          241.6
        ]
      }
    },
    "children": [..]
  }
}
```
tileset.json 的第一级对象包含四个属性：`asset`、`properties`、`geometricError` 和 `root`。

`asset` 是一个包含整个瓦片集元数据属性的对象。它的 `version` 是一个字符串属性，定义了 3D Tiles 版本。version 定义了 tileset.json 的
JSON schema 和瓦片格式的基本设置。`tilesetVersion` 是一个可选字符串属性，定义了瓦片集的程序特定版本，如对一个已经存在的瓦片集进行更新。`gltfUpAxis` 是一个可选字符串属性，定义了瓦片集所含 glTF 模型的 up-axis 属性。

`properties` 是一个对象属性包含了瓦片集中每个 per-feature 属性的对应属性。这段 tileset.json 片段是对应的是 3D 建筑群，因此每个瓦片都包含一栋建筑，每个建筑包含一个 `Height`属性（参见 [Batch Table](TileFormats/BatchTable/README.md)）。`properties` 中每个对象的名字与 per-feature 属性的名字相对应，每个对象的值定义了 `minimum` 和 `maximum` 值，这对于创建渐变颜色样式而言是非常有用的。

`geometricError` 是一个非负数，定义了瓦片集何时不被渲染的误差，单位为米。

`root` 是一个对象属性，使用 JSON（如 [瓦片元数据](#瓦片元数据) 所描述）定义了根瓦片。`root.geometricError` 与 tileset.json 顶级中定义的 `geometricError` 不同。tileset.json 中的 `geometricError` 是整个瓦片集不被渲染时的误差；`root.geometricError` 是仅根瓦片显示时的误差。

`root.children` 是一个对象数组，定义了子瓦片。每个子瓦片都包含一个 `boundingVolume`（被父瓦片的 `boundingVolume` 完全包围）和一个 `geometricError` （小于父瓦片的 `geometricError`）。对于最底层瓦片而言，这个数组的长度为0，并且 `children` 可能未被定义。

tileset.json 文件 JSON schema 的细节参见 [schema](schema) 章节。

想要了解 tileset.json 是如何扩展成大量瓦片的，参见 [Q&A below](#Will-tileset.json-be-part-of-the-final-3D-Tiles-spec) 

### 外部瓦片集

为了创建嵌套树结构，瓦片的 `content.url` 属性可以指向一个外部的瓦片集（另一个 tileset.json）。例如，每个瓦片集存有一个城市，合在一起组成一个全球瓦片集。

![](figures/tilesets.jpg)

当一个瓦片指向一个外部的瓦片集时，该瓦片

* 不能含有任何子元素；`tile.children` 必须是 `undefined` 或者空数组。
* 含有数个与外部瓦片集的根瓦片相对应的属性：
    * `root.geometricError === tile.geometricError`，
    * `root.refine === tile.refine`，和
    * `root.boundingVolume === tile.content.boundingVolume` (或当 `tile.content.boundingVolume` 是 `undefined` 时，`root.boundingVolume === tile.boundingVolume` )。
    * `root.viewerRequestVolume === tile.viewerRequestVolume` 或 `root.viewerRequestVolume` 为 `undefined`。
* 不能循环引用，例如，指向含有该瓦片的相同 tileset.json 或指向另一个 tileset.json 然后再次指向含有该瓦片的 tileset.json。
* 会受到瓦片的 `transform` 和根瓦片的 `transform` 的共同作用。例如，下面的瓦片集引用了一个外部瓦片集，`T3` 的计算变换矩阵为 `[T0][T1][T2][T3]`。

![](figures/tileTransformExternalTileset.png)

### 包围体的空间相干性

如上所述，树具有空间相干性；每个瓦片包含一个包围体，瓦片的内容都包含在包围体中，并且子瓦片的内容都包含在父瓦片的包围体中。但这并不意味着子瓦片的包围体完全在父瓦片的包围体中。例如：

<p align="center">
  <img src="figures/parentBoundingSphere.jpg" /><br />
  一个地形瓦片的包围球。
</p>

<p align="center">
  <img src="figures/childBoundingSphere.jpg" /><br />
  四个子瓦片的包围球。子瓦片的内容完全在父瓦片的包围体中，但是子瓦片的包围体不在父瓦片的包围体中，因为子瓦片的包围体不是仅仅贴合的。
</p>

### 创建空间数据结构

tileset.json 中定义的树由 `root` 和 `children` 递归得到，可以定义不同种类的空间数据结构。此外，任何瓦片格式和优化方法（替代或添加）的组合都被接受，为支持多样化的数据提供了便利。

生成 tileset.json 的转换工具决定了数据最理想的树。运行时引擎，如 Cesium，是通用程序，可以渲染由 tileset.json 渲染的任何树。以下是 3D Tiles 如何表示不同数据空间结构的一个简短描述。

#### K-d 树
创建 k-d 树的场景是，每个瓦片包含两个子对象，被一个平行于 _x_、_y_ 或 _z_ 轴（或经度、纬度、高程）的分隔平面分隔开。分隔轴经常随着层级变深交替旋转，分隔平面可选用中面、使用表面积启发式算法计算或采用其他算法。

<p align="center">
  <img src="figures/kdtree.png" /><br />
  k-d 树范例。注意分割不是平均的。
</p>

注意，不同于传统的 2D 地理空间瓦片方案，k-d 树不需要平均分割。因此 k-d 树可以为稀疏和不均匀分布的数据创建更均衡的树。

3D Tiles 支持 k-d 树的变种，例如 [multi-way k-d trees](http://www.crs4.it/vic/cgi-bin/bib-page.cgi?id=%27Goswami:2013:EMF%27)。在这种变种中，树的每个底部节点沿着坐标轴分为了若干块。它含有多个子节点而不是两个。

#### 四叉树

与传统的 2D 地理空间瓦片方案类似，四叉树适用于每个瓦片包含四个平均分布的子瓦片（例如，使用中心位置的经线和纬线进行分割）。空子瓦片可被省略。

<p align="center">
  <img src="figures/quadtree.png" /><br />
  经典四叉树分割。
</p>

3D Tiles 支持四叉树变种，如非平均分割的四叉树和紧密包围体（与包围体相对应，包围体占据整个父瓦片的25%，这对于稀疏数据而言是浪费的）。

<p align="center">
  <img src="figures/quadtree-tight.png" /><br />
  子元素采用紧密包围体的四叉树。
</p>

例如，以下是金丝雀码头的根瓦片以及他的子节点。注意左下角的子瓦片，包围体不包含左侧的水域因为该位置没有建筑物：

![](figures/nonUniformQuadtree.png)

3D Tiles 还支持其他四叉树变种，如 [loose quadtrees](http://www.tulrich.com/geekstuff/partitioning.html)，子瓦片由重叠，但仍然保留空间相干性（如父瓦片完全包含子瓦片）。该方法可被用来避免分割 3D 模型、跨区域瓦片等特征。

<p align="center">
  <img src="figures/quadtree-overlap.png" /><br />
  非均匀分割且子瓦片有重叠的四叉树。
</p>

下图中，绿色的建筑在左边子瓦片中，紫色的建筑在右边子瓦片中。注意子瓦片之间有重叠，这样中部的2栋绿色建筑和1栋紫色建筑就不会被切割开。

![](figures/looseQuadtree.png)

#### 八叉树

八叉树是四叉树的扩展，将一个瓦片使用三个相互正交的分割平面分成八个子瓦片。与四叉树类似，3D Tiles 支持八叉树的变种，如非均匀分割，紧密包围体和子瓦片重叠。

<p align="center">
  <img src="figures/octree.png" /><br />
  传统八叉树分割。
</p>

<p align="center">
  <img src="figures/pointcloud-octree.png" /><br />
  使用添加修正点云，采用非均匀分割八叉树划分。<a href="http://robotics.cs.columbia.edu/~atroccol/ijcv/chappes.html">the Church of St Marie at Chappes, France</a> 点云，作者 Prof. Peter Allen，Columbia University Robotics Lab。 扫描： Alejandro Troccoli and Matei Ciocarlie.
</p>

#### 网格

3D Tiles 通过支持任意数量的子瓦片来实现均匀分布、非均匀分布和相互重叠的网格。例如，下图为从自上向下视角看到的剑桥市非均匀分布重叠网格。

![](figures/grid.png)

3D Tiles 充分利用了空瓦片（含有包围体但是不含内容）的优势。由于瓦片的 `content` 属性可以不被定义，空的非底层瓦片可被用来加速带有层次遮挡裁剪算法的非均匀分布网格。这本质上等同于创建了没有分层层次细节模型（HLOD）的四叉树和八叉树。

## 瓦片格式

每个瓦片的 `content.url` 属性指向一个瓦片，该瓦片的格式为上文 [Status section](#spec-status) 所列出格式中的一种。

瓦片集可以包含任意瓦片格式的组合。3D Tiles 也可以通过 [Composite](TileFormats/Composite/README.md) 瓦片在同一个瓦片中支持不同瓦片格式。

## 声明式样式

<p align="center">
  <img src="figures/style.jpg" /><br />
  通过色彩表示高度的建筑物，色彩通过声明式样式指定。
</p>

3D Tiles 包含了一个简洁的声明式样式功能，通过 JSON 或表达式（一个用于修改样式的 JavaScript 小分支）进行声明。

样式一般通过基于特征属性的表达式定义一个特征的 `show` 和 `color`（RGB 和 半透明度），例如
```json
{
    "color" : "(${Temperature} > 90) ? color('red') : color('white')"
}
```

这条语句将温度高于 90 的特征着色为红色，其他的着色为白色。

完整细节参见 [声明式样式](Styling/README.md) 细则。

## 问答导航

- [谁在使用 3D Tiles?](#谁在使用-3D-Tiles?)
- [在线应用](#在线应用)
- [目录](#目录)
- [资源](#资源)
- [Spec status](#spec-status)
- [介绍](#介绍)
- [瓦片元数据](#瓦片元数据)
  - [坐标系和单位](#坐标系和单位)
  - [瓦片变换](#瓦片变换)
  - [Viewer request volume](#viewer-request-volume)
- [tileset.json](#tilesetjson)
  - [外部瓦片集](#外部瓦片集)
  - [包围体的空间相干性](#包围体的空间相干性)
  - [创建空间数据结构](#创建空间数据结构)
    - [K-d 树](#k-d-树)
    - [四叉树](#四叉树)
    - [八叉树](#四叉树)
    - [网格](#网格)
- [瓦片格式](#瓦片格式)
- [声明式样式](#声明式样式)
- [问答导航](#问答导航)
  - [一般问答](#一般问答)
    - [Can I use 3D Tiles today?](#can-i-use-3d-tiles-today)
    - [3D Tiles 是为 Cesium 特别设计的吗？](#3D-Tiles-是为-Cesium-特别设计的吗？)
    - [3D Tiles 和 glTF 之间的关系是什么？](#3D-Tiles-和-glTF-之间的关系是什么？)
    - [3D Tiles 支持运行时编辑吗？](#3D-Tiles-支持运行时编辑吗？)
    - [3D Tiles 将来会包含地形吗？](#3D-Tiles-将来会包含地形吗？)
    - [3D Tiles 将来会包含地理影像吗？](#3D-Tiles-将来会包含地理影像吗？)
    - [3D Tiles 将来代替 KML 吗？](#3D-Tiles-将来代替-KML-吗？)
  - [技术问答](#技术问答)
    - [3D Tiles 是如何支持多种数据格式的？](#3D-Tiles-是如何支持多种数据格式的？)
    - [tileset.json 将来会成为最终 3D Tiles 标准的一部分吗？](#tileset.json-将来会成为最终-3D-Tiles-标准的一部分吗？)
    - [我应该如何请求第 `n` 级瓦片？](#我应该如何请求第-`n`-级瓦片？)
    - [3D Tiles 将来会支持 horizon culling 吗?](#3D-Tiles-将来会支持-horizon-culling-吗?)
    - [Is screen space error the only metric used to drive refinement?](#is-screen-space-error-the-only-metric-used-to-drive-refinement)
    - [How are cracks between tiles with vector data handled?](#how-are-cracks-between-tiles-with-vector-data-handled)
    - [When using replacement refinement, can multiple children be combined into one request?](#when-using-replacement-refinement-can-multiple-children-be-combined-into-one-request)
    - [How can additive refinement be optimized?](#how-can-additive-refinement-be-optimized)
    - [3D Tiles 采用了哪种材质压缩算法？](#3D-Tiles-采用了哪种材质压缩算法？)
- [鸣谢](#鸣谢)
- [Data credits](#data-credits)

### 一般问答

#### 我现在可以使用 3D Tiles 吗？

我们预计 3D Tiles 的初版标准会在 2016 年秋季完成。如果你可以接受一直变更的话，现在就可以开始。

#### 3D Tiles 是为 Cesium 特别设计的吗？

不，3D Tiles 是为传输大量多种 3D 地理空间数据而设计的通用规范。Cesium 团队起草了该规范的原因是我们需要一个开放格式来向 Cesium 传输数据。[AGI](http://www.agi.com/)，Cesium 的创建者，也在开发创建 3D Tiles 的工具。我们期待其他图形引擎和转换工具使用 3D Tiles。

#### 3D Tiles 和 glTF 之间的关系是什么？

[glTF](https://www.khronos.org/gltf) 为 WebGL 的运行资源格式，是由 Khronos（WebGL 和 COLLADA 的创立者）建立的三维模型开放标准。Cesium 使用 glTF 作为它的三维模型格式，Cesium 团队对 glTF 标准和开源格式转换工具 COLLADA2GLTF 贡献巨大。我们建议选用 glTF 作为 Cesium 单独资源（如一架飞机、一个角色或一栋三维建筑）的格式。

我们创建 3D Tiles 的目的是传输单个 glTF 模型无法承载的大体量地理空间数据。考虑到 glTF 是为渲染进行优化的，Cesium 有一个经过充分测试的 glTF 加载器，并且包括 glTF 转换工具，3D Tiles 在某些瓦片格式如 [b3dm](TileFormats/Batched3DModel/README.md)（为三维建筑物设计）中使用 glTF 格式。为了将 glTF 嵌入二进制文件并且避免 base64 编码或多文件开销，我们为 glTF 创建了一个二进制扩展（[KHR_binary_glTF](https://github.com/KhronosGroup/glTF/tree/master/extensions/Khronos/KHR_binary_glTF)）。

采用这种方法使我们可以同时提升 Cesium、glTF 和 3D Tiles。例如，当我们在 glTF 中加入网格压缩时，使 Cesium 中的 3D 模型、glTF 生态和 3D Tiles同时受益。

#### 3D Tiles 支持运行时编辑吗？

A common use case for 3D buildings is to stream a city dataset, color each building based on one or more properties (e.g., the building's height), and then hide a few buildings and replace them with high-resolution 3D buildings.  With 3D Tiles, this type of editing can be done at runtime.

The general case runtime editing of geometry on a building, vector data, etc., and then efficiently saving those changes in a 3D Tile will be possible, but is not the initial focus.  However, styling is much easier since it can be applied at runtime without modification to the 3D Tiles tree and is part of the initial work.

#### 3D Tiles 将来会包含地形吗？?

Yes, a [quantized-mesh](https://cesiumjs.org/data-and-assets/terrain/formats/quantized-mesh-1.0.html)-like tile would fit well with 3D Tiles and allow Cesium to use the same streaming code (we say _quantized-mesh-like_ because some of the metadata, e.g., for bounding volumes and horizon culling, may be organized differently or moved to tileset.json).

However, since Cesium already streams terrain well, we are not focused on this in the short-term.

#### 3D Tiles 将来会包含地理影像吗？

Yes, there is an opportunity to provide an optimized base layer of terrain and imagery (similar to how a 3D model contains both geometry and textures).  There is also the open research problem of how to tile imagery for 3D.  In 2D, only one LOD (`z` layer) is used for a given view.  In 3D, especially when looking towards the horizon, tiles from multiple LODs are adjacent to each other.  How do we make the seams look good?  This will likely require tool and runtime support.

As with terrain, since Cesium already streams imagery well, we are not focused on this in the short-term.

#### 3D Tiles 将来代替 KML 吗？

In many cases, yes.  KML regions and network links are a clunky approach to streaming massive 3D geospatial datasets on the web.  3D Tiles is built for the web and optimized for streaming; uses true HLOD; does not need to triangulate polygons; and so on.

### 技术问答

#### 3D Tiles 是如何支持多种数据格式的？

Geospatial datasets are heterogeneous: 3D buildings are different from terrain, which is different from point clouds, which are different from vector data, and so on.

3D Tiles supports heterogeneous data by allowing different tile formats in a tileset, e.g., a tileset may contain tiles for 3D buildings, tiles for instanced 3D trees, and tiles for point clouds, all using different tile formats.

3D Tiles also supports heterogeneous datasets by concatenating different tile formats into one tile using the [Composite](TileFormats/Composite/README.md) tile format.  In the example above, a tile may have a short header followed by the content for the 3D buildings, instanced 3D trees, and point clouds.

Supporting heterogeneous datasets with both inter-tile (different tile formats in the same tileset) and intra-tile (different tile formats in the same Composite tile) options allows conversion tools to make trade-offs between number of requests, optimal type-specific subdivision, and how visible/hidden layers are streamed.

#### tileset.json 将来会成为最终 3D Tiles 标准的一部分吗？

Yes.  There will always be a need to know metadata about the tileset and about tiles that are not yet loaded, e.g., so only visible tiles can be requested.  However, when scaling to millions of tiles, a single tileset.json with metadata for the entire tree would be prohibitively large.

3D Tiles already supports trees of trees. `content.url` can point to another tileset.json, which enables conversion tools to chunk up a tileset into any number of tileset.json files that reference each other.

There's a few other ways we may solve this:
* Moving subtree metadata to the tile payload instead of tileset.json.  Each tile would have a header with, for example, the bounding volumes of each child, and perhaps grandchildren, and so on.
* Explicit tile layout like those of traditional tiling schemes (e.g., TMS's `z/y/x`).  The challenge is that this implicitly assumes a spatial subdivision, whereas 3D Tiles is general enough to support quadtrees, octrees, k-d trees, and so on.  There is likely to be a balance where two or three explicit tiling schemes can cover common cases to complement the generic spatial data structures. 

#### 我应该如何请求第 `n` 级瓦片？

More generally, how do 3D Tiles support the use case for when the viewer is zoomed in very close to terrain, for example, and we do not want to load all the parent tiles toward the root of the tree; instead, we want to skip right to the high-resolution tiles needed for the current 3D view?

This 3D Tiles topic needs additional research, but the answer is basically the same as above: either the skeleton of the tree can be quickly traversed to find the desired tiles or an explicit layout scheme will be used for specific subdivisions.

#### 3D Tiles 将来会支持 horizon culling 吗?

Since [horizon culling](https://cesium.com/blog/2013/04/25/horizon-culling/) is useful for terrain, 3D Tiles will likely support the metadata needed for it.  We haven't considered it yet since our initial work with 3D Tiles is for 3D buildings where horizon culling is not effective.

#### Is screen space error the only metric used to drive refinement?

At runtime, a tile's `geometricError` is used to compute the screen space error (SSE) to drive refinement.  We expect to expand this, for example, by using the [_virtual multiresolution screen space error_](http://www.dis.unal.edu.co/profesores/pierre/MyHome/publications/papers/vmsse.pdf) (VMSSE), which takes occlusion into account.  This can be done at runtime without streaming additional tile metadata.  Similarly, fog can also be used to tolerate increases to the SSE in the distance.

However, we do anticipate other metadata for driving refinement.  SSE may not be appropriate for all datasets; for example, points of interest may be better served with on/off distances and a label collision factor computed at runtime.  Note that the viewer's height above the ground is rarely a good metric for 3D since 3D supports arbitrary views.

See [#15](https://github.com/AnalyticalGraphicsInc/3d-tiles/issues/15).

#### How are cracks between tiles with vector data handled?

Unlike 2D, in 3D, we expect adjacent tiles to be from different LODs so, for example, in the distance, lower resolution tiles are used.  Adjacent tiles from different LODs can lead to an artifact called _cracking_ where there are gaps between tiles.  For terrain, this is generally handled by dropping _skirts_ slightly angled outward around each tile to fill the gap.  For 3D buildings, this is handled by extending the tile boundary to fully include buildings on the edge; [see above](#四叉树).  For vector data, this is an open research problem that we need to solve.  This could invole boundary-aware simplification or runtime stitching. 

#### When using replacement refinement, can multiple children be combined into one request?

Often when using replacement refinement, a tile's children are not rendered until all children are downloaded (an exception, for example, is unstructured data such as point clouds, where clipping planes can be used to mask out parts of the parent tile where the children are loaded; naively using the same approach for terrain or an arbitrary 3D model results in cracking or other artifacts between the parent and child).

We may design 3D Tiles to support downloading all children in a single request by allowing tileset.json to point to a subset of a file for a tile's content similiar to glTF [buffer](https://github.com/KhronosGroup/glTF/blob/master/specification/buffer.schema.json) and [bufferView](https://github.com/KhronosGroup/glTF/blob/master/specification/bufferView.schema.json).  [HTTP/2](http://chimera.labs.oreilly.com/books/1230000000545/ch12.html#_brief_history_of_spdy_and_http_2) will also make the overhead of multiple requests less important.

See [#9](https://github.com/AnalyticalGraphicsInc/3d-tiles/issues/9).

#### How can additive refinement be optimized?

Compared to replacement refinement, additive refinement has a size advantage because it doesn't duplicate data in the original dataset.  However, it has a disadvantage when there are expensive tiles to render near the root and the view is zoomed in close.  In this case, for example, the entire root tile may be rendered, but perhaps only one feature or even no features are visible.

3D Tiles can optimize this by storing an optional spatial data structure in each tile.  For example, a tile could contain a simple 2x2 grid, and if the tile's bounding volume is not completely inside the view frustum, each box in the grid is checked against the frustum, and only those inside or intersecting are rendered.

See [#11](https://github.com/AnalyticalGraphicsInc/3d-tiles/issues/11).

#### 3D Tiles 采用了哪种材质压缩算法？

3D Tiles will support the same texture compression that glTF [will support](https://github.com/KhronosGroup/glTF/issues/59).  In addition, we need to consider how well GPU formats compress compared to, for example, jpeg.  Some desktop game engines stream jpeg, then decompress and recompress to a GPU format in a thread.  The CPU overhead for this approach may be too high for JavaScript and Web Workers.

## 鸣谢

* [Erik Andersson](https://github.com/e-andersson)
* [Sarah Chow](https://cesium.com/team/SarahChow/)
* [Kevin Ring](http://www.kotachrome.com/kevin/)
* [Dylan Brown](http://www.github.com/Dylan-Brown)
* [Leesa Fini](http://www.github.com/LeesaFini)

## Data credits

The screenshots in this spec use awesome [CyberCity3D](http://www.cybercity3d.com/) buildings and the [Bing Maps](https://www.microsoft.com/maps/choose-your-bing-maps-API.aspx) base layer.
