安装npm install

运行npm serve

1.使用 Vue-cli + ES6 来开发项目

列表页展示
底部 Tab 切换类别
顶部搜索框功能
点击 item 展示详情页
返回列表页等功能。


2. 通过JSONP 拉取豆瓣数据

通过 JSONP 方式解决豆瓣api跨域问题


3.豆瓣接口说明


图书相关


【拉取图书列表和搜索图书列表】


http://git.imweb.io/imweb-teacher/douban-api/blob/master/book.md


音乐相关


【拉取音乐列表和搜索音乐列表】


http://git.imweb.io/imweb-teacher/douban-api/blob/master/music.md


电影相关

由于拉取电影列表接口有点特殊，涉及接口需要有两条：


【拉取电影 top 250 列表】


http://git.imweb.io/imweb-teacher/douban-api/blob/master/movie_top.md


【搜索电影】


http://git.imweb.io/imweb-teacher/douban-api/blob/master/movie.md


4.列表页实现下拉刷新以及拉到底部加载更多的功能

