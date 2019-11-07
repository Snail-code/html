# vue-cli 的安装

```shell
npm install vue-cli -g
 npm  set registry=https://registry.npm.taobao.org
 npm install vue-cli -g
 vue init webpack baoge
 npm install -g npm-install-peers
 npm install --ignore-scripts
 cd  baoge 
 npm install	
 
 安装其他库
 npm install --save-dev bootstrap
 在main.js中添加
发布
npm run build

```





引入其他库

```
 npm install --save-dev bootstrap
 npm install jquery
```

在main.js中引入

```
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.min.js'
```

然后运行，结果按照提示让执行这样的命令

```
npm install --save popper.js
```

然后，再运行 就能成功使用bootstrap了