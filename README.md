# 爬虫全书网的一些记录
# 主要思想
#1、遍历每个类，得到每个类的最大页
#2、遍历每个类的每一页，得到该网页所有“马上阅读”连接
#3、遍历每个“马上阅读”连接，得到“开始阅读”连接
#4、若“开始阅读”连接存在，解码存入book，正则匹配各章连接和章名，存入该chapters
#5、对每一个章节，解码存入chapter，正则匹配正文，存入该txt，txt叫章名
#6、每次访问网页，停顿一段时间
