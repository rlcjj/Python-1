# 快手爬虫脚本
+ 扒取快手app中的评论数、赞数、用户名等信息
+ 性别、用户id等都可以从数据结构中找到
+ 利用 `tomcat` 抓包，抓取 `json` 格式的 `http response` 
+ 在 `response` 中找到包含信息的数据结构
+ 相同的方法不能用于**抖音**，原因是快手和**抖音**的数据拉取方式不同
