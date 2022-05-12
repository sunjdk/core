如果想要学习Vue的源码，比如看createApp的实现过程，应该怎么办呢?

第一步:在GitHub上搜索vue-next，下载源代码﹔这里推荐通过git clone 的方式下载;

第二步:安装Vue源码项目相关的依赖;执行yarn install

第三步:对项目执行打包操作

执行yarn dev(执行前修改脚本)

"scripts": {
"dev" : "node scripts/dev.js -sourcemap"

第四步:通过packages/vue/dist/vue.global.,js调试代码
