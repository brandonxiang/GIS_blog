#Awesome GIS（GIS Tech Stack技术栈）

> Geomatics专栏点此：http://www.jianshu.com/collection/3fa5e8ac3fbc

****
###语言

- [Python](https://www.python.org/) 最好的快速开发语言，是一门API艺术
   - [awesome-python](https://github.com/vinta/awesome-python)
   - [1简单的入门](http://www.jianshu.com/p/a2b172049730) 
   - [2总结入门坑及基础资源](http://www.jianshu.com/p/4e04e4879c33)
   - [3Geopython GIS相关库](http://www.jianshu.com/p/378619d4bd15)
   - [4Python的常用库入门](http://www.jianshu.com/p/886cbabbfe9e)
   - [5Flask框架](http://www.jianshu.com/p/02eab28735b7)
   - [6入门爬虫坑--网页数据压缩(python deflate gzip)](http://www.jianshu.com/p/2c2781462902)
   - [7Requests爬虫技巧](http://www.jianshu.com/p/cba83709c64c)
   
- [Node.js](https://nodejs.org/) Javascript最炙手可热的网络技术源泉，可用于WebGIS
   - [awesome-javascript](https://github.com/sorrycc/awesome-javascript)
   - [1常用Global库](http://www.jianshu.com/p/f161073ed3bc) 
   - [2入门及GeoNode.js GIS相关库](http://www.jianshu.com/p/4cb1af2b3976)

****
###前段

- [Leaflet](http://leafletjs.com/) 兼容移动端，和现代的一些框架一样优先考虑移动端
   - [1leaflet入门](http://www.jianshu.com/p/57464d925e45)
   - [2简单插件编写leaflet-pip-v2](http://www.jianshu.com/p/2ab5290fd66b)
   - [3进阶插件编写geojsonFilter](http://www.jianshu.com/p/46001b6eb0a4)
   - [4vue-leaflet](http://www.jianshu.com/p/03b7893bc007)
   - [Leaflet在“莆田系医院”数据可视化的使用](http://www.jianshu.com/p/3131fb1f1255)
- [Mapbox](https://www.mapbox.com/)总有人讨论“Mapbox VS Leaflet？”这是个烂问题，Mapbox是Leaflet的超集，就像Typescript和Javascript之间的关系一样
- [Openlayer3](http://openlayers.org/) [扯淡大叔教程](http://weilin.me/ol3-primer/index.html)
- [Turf](https://www.mapbox.com/analysis/) js层面做出简单的空间分析
- [Vue.js](http://cn.vuejs.org/) 轻量级的MVVM前端框架

****
###后端

- [Geoserver](http://www.geoserver.org/) 基于Java的地理信息服务的发布，使用简单
    - [1深度入门](http://www.jianshu.com/p/144033b1b87e)
- [Mapserver](http://mapserver.org/) 基于C语言的地理信息服务的发布，内存占用小
- [GDAL](www.gdal.org/) 数据格式转换 
    - [1GDAL命令行入门](http://www.jianshu.com/p/e48d0a17628c) 
    - [2python for GDAL](http://www.jianshu.com/p/2372fe239130)
    - [3gdal CLI Cheat Sheet](http://www.jianshu.com/p/6251400d0651)

****
###数据格式

- [GeoJSON](http://www.geojson.org/) 开源地理信息JSON格式
   - [1深度入门](http://www.jianshu.com/p/144033b1b87e) 
- [TopoJSON](https://github.com/mbostock/topojson/wiki) 开源地理信息JSON格式，大小要比GeoJSON小40%
- [TileJSON](https://github.com/mapbox/tilejson-spec) 瓦片数据包装的JSON格式，用的不多
- [WKT&WKB](https://en.wikipedia.org/wiki/Well-known_text) 文本标记语言表示矢量数据
   - [1格式介绍](http://www.jianshu.com/p/0edd5c37d9db)

****
###数据库

- [Spatialite](http://www.gaia-gis.it/gaia-sins/) 空间数据的查询等处理，小项目足矣 
    - [1简单的入门](http://www.jianshu.com/p/f94d8eecc6b3)
    - [2CLI Cheat Sheet](http://www.jianshu.com/p/107962b36b38)
    - [3python for Spatialite](http://www.jianshu.com/p/5bc7d8b7b429)
    - [4NET平台使用spatilite扩展](http://www.jianshu.com/p/6cfe6cda80ad)
    - [5Spatiliate2GeoJson数据的转换](http://www.jianshu.com/p/a5ac3a399167)
- [Postgresql](http://www.postgresql.org/) 大型空间数据项目
- [MBTILES](https://github.com/mapbox/mbtiles-spec) 承载瓦片的数据，快速索引 
    - [1入门与简单应用](http://www.jianshu.com/p/a679fe351b98)

****
###瓦片渲染

- **Global Mapper** 专门用作已有栅格图像切片
- [Mapnik](http://mapnik.org/) 专门用于矢量数据的切片
- [TileMill](https://www.mapbox.com/tilemill/) 在矢量数据渲染时，运用CartoCSS对矢量数据赋予样式


****
###数据处理

- [QGIS](http://qgis.org/) 开源GIS数据处理桌面软件，其中包含[Grass](https://grass.osgeo.org/)，[SAGA](https://sourceforge.net/projects/saga-gis/)两个学术界开源GIS平台
   - [1简单的介绍](http://www.jianshu.com/p/2fb248033a31)
   - [2地图综合](http://www.jianshu.com/p/8ceefe8caaf0)
- [Mapsharper](http://www.mapshaper.org/) 数据综合神器
   - [1地图综合神器](http://www.jianshu.com/p/55401c3ffc44)

****
###数据资料

- [地理空间数据云](http://www.gscloud.cn/) 免费数据，商业数据都有，满足你不同的需要

****
###GIS 博客
- [paulbourke](http://paulbourke.net/)

****
###填坑

- [1网页端JS的缓存问题](http://www.jianshu.com/p/6bbc31475f25)
- [2Angular遇到的一些坑](http://www.jianshu.com/p/05e97bcb808d)
- [3SpatialiteSharp的使用坑](http://www.jianshu.com/p/5ba61d1152c0)

****

整个技术栈主要针对的是轻量或者小项目去考虑，运用一些流行的尽可能开源的工具去做，这是我的一些想法和笔记，详情参考[从mapbox的开源工具看Web GIS的发展](http://www.jianshu.com/p/e6af6ef1f1c4)和[乱谈Leaflet的插件在WebGIS中作用](http://www.jianshu.com/p/47ed092f6b9c)，希望能给您一点点帮助。PS：我在github上看到一个[awesome gis](https://github.com/sshuair/awesome-gis)，并非我主导的，希望各位GISer可以一起参与修改。

转载，请表明出处。[总目录Awesome GIS](http://www.jianshu.com/p/3b3efa92dd6d)
