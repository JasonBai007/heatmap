# heatmap
generate a heatmap with baidu map api.

## Baidu Map API Features

1. 支持HTTP和HTTPS
2. 免费使用
3. 接口使用无次数限制
4. 使用前，您需先申请密钥（ak）

## techs one（推荐）

1. [百度地图API](http://lbsyun.baidu.com/index.php?title=jspopular)
2. [Heatmap_min.js](http://lbsyun.baidu.com/index.php?title=open/library)

推荐理由：
1. 逻辑简单
2. 依赖少

数据结构：

```javascripte
[{
  "lng": 116.42076,  // 经度
  "lat": 39.915251,  // 维度
  "count": 67  // 热度值
},{
  "lng": 113.64533,
  "lat": 37.75675,
  "count": 70
}]
```

## techs two（可供参考）

1. [百度地图API](http://lbsyun.baidu.com/index.php?title=jspopular)
2. [echarts](http://echarts.baidu.com/)
2. [百度地图扩展bmap.min.js](https://github.com/apache/incubator-echarts/tree/master/extension/bmap)

不推荐理由：
1. 逻辑复杂
2. 依赖多

## How to use

1. 注册百度账号
2. 申请成为百度开发者
3. 创建应用（同时会获得密钥AK）
4. 替换html页面中的ak值
5. 看文档撸码

## screenshot
![image](https://github.com/jasonBai007/heatmap/raw/master/screenshot.jpg)

