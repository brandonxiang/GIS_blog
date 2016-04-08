##Awesome GIS（GIS Tech Stack技术栈）##

****

**语言**

- [python](https://www.python.org/) 最好的快速开发语言，是一门API艺术 
   - [1简单的入门](http://www.jianshu.com/p/a2b172049730) 
   - [2总结入门坑及基础资源](http://www.jianshu.com/p/4e04e4879c33)
   - [3Geopython GIS相关库](http://www.jianshu.com/p/378619d4bd15)
   - [4Python的常用库入门](http://www.jianshu.com/p/886cbabbfe9e)
   - [5Flask框架](http://www.jianshu.com/p/02eab28735b7)
   - [6入门爬虫坑--网页数据压缩(python deflate gzip)](http://www.jianshu.com/p/2c2781462902)
   - [7Requests爬虫技巧]()
   
- [Node.js](https://nodejs.org/) 最炙手可热的网络技术源泉，可用于WebGIS 
   - [1常用Global库](http://www.jianshu.com/p/f161073ed3bc) 

****

**前段**

- [Leaflet](http://leafletjs.com/) 兼容移动端，和现代的一些框架一样优先考虑移动端
   - [1leaflet入门](http://www.jianshu.com/p/57464d925e45)
   - [2简单插件编写leaflet-pip-v2](http://www.jianshu.com/p/2ab5290fd66b)
   - [3leaflet插件filter]()
- [Mapbox](https://www.mapbox.com/)总有人讨论“Mapbox VS Leaflet？”这是个烂问题，Mapbox是Leaflet的超集，就像Typescript和javascript一样
- [Turf](https://www.mapbox.com/analysis/) js层面做出简单的空间分析

****

**后端**

- [Geoserver](http://www.geoserver.org/) 基于Java的地理信息服务的发布，使用简单
- [Mapserver](http://mapserver.org/) 基于C语言的地理信息服务的发布，内存占用小
- [GDAL](www.gdal.org/) 数据格式转换 
    - [1GDAL命令行入门](http://www.jianshu.com/p/e48d0a17628c) 
    - [2pyGDAL](http://www.jianshu.com/p/2372fe239130)
    - [3gdal CLI Cheat Sheet](http://www.jianshu.com/p/6251400d0651)

****

**数据格式**

- [GeoJSON](http://www.geojson.org/) 开源地理信息JSON格式
- [TopoJSON](https://github.com/mbostock/topojson/wiki) 开源地理信息JSON格式，大小要比GeoJSON小40%
- [TileJSON](https://github.com/mapbox/tilejson-spec) 瓦片数据包装的JSON格式，用的不多
- [WKT&WKB](https://en.wikipedia.org/wiki/Well-known_text) 文本标记语言表示矢量数据
   - [WKT&WKB 笔记一：格式介绍](http://www.jianshu.com/p/0edd5c37d9db)

****

**数据库**

- [Spatialite](http://www.gaia-gis.it/gaia-sins/) 空间数据的查询等处理，小项目足矣 
    - [1简单的入门](http://www.jianshu.com/p/f94d8eecc6b3)
    - [2CLI Cheat Sheet](http://www.jianshu.com/p/107962b36b38)
    - [3pySpatialite](http://www.jianshu.com/p/5bc7d8b7b429)
    - [4.NET平台使用spatilite扩展](http://www.jianshu.com/p/6cfe6cda80ad)
    - [5.Spatiliate2GeoJson数据的转换](http://www.jianshu.com/p/a5ac3a399167)
- [postgresql](http://www.postgresql.org/) 大型空间数据项目
- [MBTILES](https://github.com/mapbox/mbtiles-spec) 承载瓦片的数据，快速索引 
    - [1入门与简单应用](http://www.jianshu.com/p/a679fe351b98)

****

**瓦片渲染**

- **Global Mapper** 专门用作已有栅格图像切片
- [mapnik](http://mapnik.org/) 专门用于矢量数据的切片
- [TileMill](https://www.mapbox.com/tilemill/) 在矢量数据渲染时，运用CartoCSS对矢量数据赋予样式

****

**移动端**

- [Cordova](http://cordova.apache.org/) 基于H5的快速跨平台开发

****

**数据处理**

- QGIS 开源GIS软件
   - [1简单的介绍](http://www.jianshu.com/p/2fb248033a31)

****

整个技术栈主要针对的是轻量或者小项目去考虑，运用一些流行的尽可能开源的工具去做，这是我的一些想法，详情参考[从mapbox的开源工具看Web GIS的发展](http://www.jianshu.com/p/e6af6ef1f1c4)，希望能给您一点点帮助。

转载，请表明出处。[总目录Awesome GIS](http://www.jianshu.com/p/3b3efa92dd6d)
