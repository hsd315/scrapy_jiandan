# scrapy_jiandan
项目是一个使用Scrapy完成网络资源爬取的工程。目前抓取的是煎蛋网的最新资源信息。

语言版本：Python2.7
数据库：MySQL5.5

程序运行：
	python getdata.py

程序会每小时抓取一次数据，开始由于煎蛋网图片资源保护，外网无法访问，只能将图片资源存在本地。

具体细节，请自行研究。