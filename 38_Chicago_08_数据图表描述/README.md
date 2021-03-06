# 38_Chicago_08_数据图表描述
数据获取，读取，处理，分析，可视化，发现关系是利用数据发现问题的一个基本流程。其中可视化部分，python提供了丰富的多样库，主要包括，并极力推荐的有：plotly、bokeh、seaborn、matplotlib、lightning等，其中不仅存在多种图表表达，帮助发现数据隐藏的关联所揭露的现实问题，而且还包括动态的图表操作，互动性的表达方式，可以更加方便变化变量来观察图形变化，强化问题揭示，以及团队间的交流。推荐使用Python来处理可视化数据，可以让问题的分析更加自由，并可以自行调整图表表达的方式。

本次实验以芝加哥城可获取的公园信息为待处理的数据，主要包括：

| 序号           | 数据内容      | 数据类型           | 数据来源  |
| ------------- |:-------------:| --------------:| -----------:|
| 1    | 公园边界及基本属性（名称、位置、类别等）| Shapefile | 	Chicago Data Portal |
| 2      | 公园设施(类标、位置等)      |   Shapefile|	Chicago Data Portal |
| 3 | 土地覆盖      |    IMAGINE Image (1m) | Chicago Metropolitan Agency for Planning |
| 4 | 三维点云数据      |    LAS(1m) | Illinois State Geological Survey Prairie research institute |
| 5 | 人口普查街区边界      |    Shapefile | Chicago Data Portal |
| 6 | 人口普查      |  CSV | Chicago Data Portal |

## 1 基本信息
* 公园类型
![](https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_00.jpg)

* pie 百分比
<img src="https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_01.jpg" width="300" align="right">

## 2 形状指数
* Shape Idx 和FRAC
![](https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_02.jpg)
* 比较两个指数的数据分布。 violin
<img src="https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_03.jpg" width="300" align="right">

## 3 土地覆盖
* box
![](https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_04.jpg)
* 冠层高度分布
<img src="https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_05.jpg" width="300" align="right">

## 4 设施统计
* line
<img src="https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_07.jpg" width="300" align="right">

## 5 天空视域因子 SVF
* 3m高空分辨率，DSM大栅格SVF计算。
![](https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_08.jpg)
* SVF数值统计
![](https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_09.jpg)

## 6 相关关系及结构
![](https://github.com/richieBao/python-urbanPlanning/blob/master/images/38_10.png)
