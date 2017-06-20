## 需求功能
1. 某个网站某个系列的内容追踪订阅。如：http://dota2.uuu9.com/，每日屌报http://dota2.uuu9.com/201706/546989.shtml
   app订阅，游戏内容，uuu9，每日屌报系列；每天早上更新
2. 某个网站某个比赛的比分抓取。如：http://www.gosugamers.net/dota2/gosubet，http://www.gosugamers.net/dota2/events/661-the-summit-7
   app订阅，游戏内容，某个比赛，每小时更新数据，可手动更新
3. 热点新闻，weibo的时时热点。

## 一些设计
1. app，选择网址+tag的交互、现实内容的webview、或者语音阅读tts
2. 存储，存储用户的tag，爬取的内容等
3. webserver
4. spider

## plan
1. 需求的3个case务必完成。
2. 开始写spider，定时触发，多线程，多进程。一个个爬取。
3. 注意存储，注意效率。
4. tag_db->spider->content_db->webserver->app
