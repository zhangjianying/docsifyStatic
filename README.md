# docsifyStatic
docsify静态版

网上大多数使用docsify都是引用在线资源.有时候会因为被墙等原因导致打不开.故保留一份全静态版本.

## 开发环境:

先安装
npm i docsify-cli -g

安装完以后 回到上一层目录 执行
docsify serve doc

## 生产环境:

可以使用Express
也可以直接使用http-server 启动. 整个已经是静态网站



## FAQ

* 修改整个文档名称?

  > index.html中 window.$docsify.name='XXXXX'

* 修改默认首页内容?

  >doc目录下的readme.md

* 修改目录?

  > _sidebar.md



