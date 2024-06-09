# GoldScope

**金价可视化大屏**

访问地址：https://outlier9.github.io/GoldScope/

演示视频：[echarts可视化大屏 | 四天拿下计算机设计大赛省三的可视化作品长什么样_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV12m421N7nB/?spm_id_from=333.999.0.0&vd_source=df847770af0ac774745e4b26af56f1d6)

博客地址：[四天肝个echarts实现金价可视化大屏（计算机设计大赛省三）](https://blog.csdn.net/m0_63596031/article/details/138226722?csdn_share_tail=%7B%22type%22%3A%22blog%22%2C%22rType%22%3A%22article%22%2C%22rId%22%3A%22138226722%22%2C%22source%22%3A%22m0_63596031%22%7D)

![image](https://img-blog.csdnimg.cn/direct/a018f66509ef4a7a9a251491876b322c.png)

## **GoldScope——金价可视化大屏**简介

### **项目名称**

GoldScope——金价可视化大屏

### **项目概述**

GoldScope——金价可视化大屏是一款综合性的金价分析与可视化工具，旨在为用户提供全面、直观的金价信息，帮助用户洞察金价走势，把握投资机遇。

### **核心功能**

1.金价相关词云：展示金价相关社会热搜词条，直观地识别出哪些词汇在公众讨论、新闻报道或专业分析中被提及得最多，从而揭示出市场对金价的关注点和情绪倾向。

2.影响因素分析：深入分析影响金价的各种因素，包括全球经济状况、货币政策、地缘政治事件等，通过数据可视化展示这些因素与金价之间的关系。

3.金店价格比较：汇集各大金店的金价信息，通过比较图表直观展示不同金店的价格差异，帮助用户做出购买决策。

4.金价与主要货币汇率关系：分析金价与主要货币（如美元、欧元等）汇率之间的相互作用，通过相关性图表揭示汇率变动对金价的影响。

5.金价的季节性波动：研究金价的季节性变化规律，通过季节性图表展示金价在不同季节的表现，为用户揭示季节性投资机会。

6.跌涨情况：展示金价的涨跌信息，通过颜色编码和数字变化直观展示金价的动态，为短线交易者提供快速反应的依据。

7.上证指数：将金价走势与上证指数进行关联分析，通过对比图表展示两者之间的相关性，帮助用户理解股市与金市的联动效应。



## 可视化大屏共分为七个板块

### 1.**金价相关词云**：词云图

- 展示金价相关社会热搜词条，直观地识别出哪些词汇在公众讨论、新闻报道或专业分析中被提及得最多，从而揭示出市场对金价的关注点和情绪倾向。

- **词云图**：展示金价相关的信息的社会关注度。

![image](https://img-blog.csdnimg.cn/img_convert/80237df2372188c2efb94965d14616b1.png)

### 2.**影响因素分析**：雷达图

- 展示金价受到影响的各种因素，比如供求关系的影响、世界经济周期发展趋势的影响、通货膨胀与利率对比关系的影响、外汇价格变动的影响、政治局势与事件的影响等，以图表形式呈现它们对金价的影响程度和趋势。
- **雷达图**：以图表形式展示不同因素对金价的影响程度，让用户一目了然地了解各个因素的相对重要性。
- echarts链接：<https://echarts.apache.org/examples/zh/editor.html?c=radar-custom>

![image](https://img-blog.csdnimg.cn/img_convert/65a3871d127086066aa87bea3ff61358.png)

### 3.**金店价格比较**：柱状图

- 将不同金店的金价进行对比，以地图或条形图等形式展示金价的变化情况，帮助用户了解金店金价的差异。
- **柱状图**：地图可以直观地展示不同金店的金价情况，而并列柱状图则可以更直观地比较不同金店的金价水平。
- echarts链接：<https://echarts.apache.org/examples/zh/editor.html?c=watermark>

![image](https://img-blog.csdnimg.cn/img_convert/b86c405df14cfe520fb5a97581ebfa29.png)

### 4.**金价与主要货币汇率关系**：渐变折线图

- 展示金价与主要货币（如美元、欧元）的汇率关系。
- **折线图**：X轴为日期，Y轴为货币汇率。
- echarts链接：<https://echarts.apache.org/examples/zh/editor.html?c=line-gradient>

![image](https://img-blog.csdnimg.cn/img_convert/7cb60a88c8cb491c5cecae1c5954576f.png)

### 5.**金价的季节性波动:**大数据量面积图

- 展示金价在一年中不同季节的波动趋势。
- **大数量面积图：**每个季节的金价波动面积展示波动情况
- echarts链接：https://echarts.apache.org/examples/zh/editor.html?c=area-simple

![image](https://img-blog.csdnimg.cn/img_convert/78cbad04ede1e6d5387547a7cb830322.png)

### 6.**每月跌涨情况:虚线柱状图**

- 展示金价在一个月内每天的跌涨情况。
- **虚线柱状图：**当月每天的金价跌涨
- echarts链接：<https://echarts.apache.org/examples/zh/editor.html?c=pictorialBar-dotted>

![image](https://img-blog.csdnimg.cn/img_convert/18673db5f557fc38bb3534b333ff8b82.png)

### 7.**上证指数:**

- 展示黄金期货上证指数
- echarts链接：<https://echarts.apache.org/examples/zh/editor.html?c=candlestick-sh>

![image](https://img-blog.csdnimg.cn/img_convert/e1f6a777131f6a5f2cff5a30c702f62f.png)

## 写在最后

当初选择的时候想了很多种可以做的方向和思路，在这里也提供给大家，我挑了其中七个角度实现，感兴趣的也可以自己试试其他的

![image](https://img-blog.csdnimg.cn/direct/31669bf993024864ac9f9ceff6d2799c.png)











