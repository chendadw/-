flask:
   本地服务器打开:
        运行 datasend 下app文件开启
   本地打开:
      文件下 static templates 分别放着拆分的dist文件 ,包含js css等
      在js文件中 解除如下代码注释 删除第8行,点击 index.html 文件可本地打开,但非mock部分的数据无法查看
      // publicPath: './' //是否可以本地打开
        publicPath: '/static/',

vue-src
    放着前端项目的src文件
