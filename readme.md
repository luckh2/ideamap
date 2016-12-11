#About this application

This is a small application building on top of Linked Data Clouds. It reads in user's keywords (about research ideas) and executes a SPARQL query againest DBLP endpoint. Spatial and temporal information is extracted and parsed from the query results and is further passed to SIMILE/EXHIBIT to show a spatiotemporal map for the research ideas.

#关于该应用

在Idea-map系统中，用户可以输入自己感兴趣领域的查询关键字，Idea-map将基于该关键字构造一个针对DBLP数据端系统的SPARQL查询。在返回的查询结果中，非结构化/半结构化的时间和空间信息被自动标注并抽取出来，这些时空信息经过格式转换，呈现在SIMILE/EXHIBIT 语义界面上。

在Idea-map系统内部，时间和空间语义信息通过正则表达式和自然语言处理技术被自动标注处理，其中的原始空间信息只包括国家和行政区划的名称，这些原始的空间信息不能直接显示在空间地图上，我们使用YQL(Yahoo! Query Language)语言对这些空间信息进行转换，将其转换到经纬度格式并将查询结果标注在地图上。

#截图
[snap1](ideamap2.jpg 系统截图1)
[snap2](ideamap3.jpg 系统截图2)
