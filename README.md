flask文件下 static templates 分别放着拆分的dist文件 ,包含js css等
在js文件中 去掉如下代码注释 删除第5行可本地打开,但非mock部分的数据无法查看
// publicPath: './' //标记:1  是否可以本地打开
  publicPath: '/static/',

