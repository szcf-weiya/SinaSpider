# SinaSpider
动态IP解决新浪的反爬虫机制，快速抓取微博内容。

## Background
抓取1000个公司（在companyList.py文件中）五年内相关的微博，进而统计评论数、转发数、点赞数等等。

## Environment
- Python2.7
- winxp服务器（通过某宝购买，关键是ADSL拨号功能，不然无法实现动态IP，也就解决不了新浪的反爬虫机制）

## Results
- 每个公司五年内的微博（通过sqlite3存储）

  下面截图为company0000.db的微博。

  ![](db.png)

- 所有公司微博评论数、转发数、点赞数的统计（excel形式呈现）
  ![](results.png)

## References

刚刚(Sun Sep 10 07:51:46 CST 2017)在整理浏览器的书签，因为自己习惯性会把觉得有用的网页存储为书签，所以日积月累，书签的数量已经十分庞大，决定清理一下。清理之前把那些与此项目的网页书签贴在这里吧

1. [模拟登录新浪微博（Python)](https://www.douban.com/note/201767245/)
2. [Python验证码识别处理实例 - Python - 伯乐在线](http://python.jobbole.com/83945/)
3. [Python验证码识别处理实例 - 林炳文Evankaka的专栏 - CSDN博客](http://blog.csdn.net/evankaka/article/details/49533493)
4. [爬虫怎么解决封IP？ - 知乎](https://www.zhihu.com/question/26018679)
5. [爬虫ip代理服务器的简要思路 - 京东放养的爬虫 - CSDN博客](http://blog.csdn.net/djd1234567/article/details/51741557)
6. [关于使用动态轮训切换ip防止爬虫被封杀](http://xiaorui.cc/2015/01/12/%E5%85%B3%E4%BA%8E%E4%BD%BF%E7%94%A8%E5%8A%A8%E6%80%81%E8%BD%AE%E8%AE%AD%E5%88%87%E6%8D%A2ip%E9%98%B2%E6%AD%A2%E7%88%AC%E8%99%AB%E8%A2%AB%E5%B0%81%E6%9D%80/)
7. [python爬虫-爬取代理IP并通过多线程快速验证](http://www.oschina.net/code/snippet_2463131_51169)
8. [OpenCV-Python教程（5、初级滤波内容）](http://blog.csdn.net/sunny2038/article/details/9155893)
9. [字符型图片验证码识别完整过程及Python实现](http://www.cnblogs.com/beer/p/5672678.html)
10. [Linux IP代理筛选系统（shell+proxy）](http://blog.csdn.net/ithomer/article/details/7639385)
11. [SQLite 连接两个字符串](http://www.cnblogs.com/AngelLee2009/p/3208223.html)
12. [取得sqlite数据库里所有的表名 &复制表](http://blog.csdn.net/vlily/article/details/9096909)
13. [python - Beautifulsoup and AJAX-table problem - Stack Overflow](https://stackoverflow.com/questions/5913280/beautifulsoup-and-ajax-table-problem)
14. [python - How to enable digits only in pytesser? - Stack Overflow](https://stackoverflow.com/questions/9466694/how-to-enable-digits-only-in-pytesser)
15. [Python 文件读写操作实例详解](http://www.jb51.net/article/47999.htm)
