# scrapy_zgNews  爬虫——爬取中国新闻网
## 目标：爬取中国新闻网，将相关字段保存到mongodb，同时按指定格式保存到文件夹
### 1：启动爬虫
终端输入：scrapy crawl zg_newsSpider
###
按照提示Enter your startTime(20181101):和Enter your endTime(20181101):输入爬取的开始时间和结束时间
###
### 2：输出
保存到D:\origin，按照爬取日期新建文件夹如D:\origin\2016年06月26日，保存为“日期-title.txt的”格式，如“2016年06月26日-《发条城市》重庆麻辣约见王宁王鸥夫妻合体秀恩爱”
###
保存到MongoDB数据库