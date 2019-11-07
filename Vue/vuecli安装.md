- Vue CLI 的包名称由 vue-cli 改成了 @vue/cli。 如果你已经全局安装了旧版本的 vue-cli(1.x 或 2.x)，你需要先卸载，卸载vue-cli3.x命令也是这个

```undefined
npm uninstall vue-cli -g
```

- 安装vue-cli3.X版本

```css
npm install -g @vue/cli
```

vue-cli2.x的安装命令是`npm install -g vue-cli`

- 查看是否安装成功

```undefined
vue --version
```

- 创建vue项目的方式不同了
   vue-cli3.x

```undefined
vue create hello-world
```

vue-cli2.x创建项目是`vue init hello-world`

- 安装完Vue cli3 之后，还想用vue-cli2.x 版本
   Vue CLI 3 和旧版使用了相同的 vue 命令，所以 Vue CLI 2 (vue-cli) 被覆盖了。如果你仍然需要使用旧版本的 vue init 功能，你可以全局安装一个桥接工具：

```kotlin
npm install -g @vue/cli-init
//安装完后 就还可以使用 vue init 命令初始化项目模板了
vue init webpack my_project
```



![img](https:////upload-images.jianshu.io/upload_images/13511312-3b8dadeff0b24613.png?imageMogr2/auto-orient/strip|imageView2/2/w/584/format/webp)

image.png

安装http://www.cnblogs.com/h2zZhou/p/9881534.html
 区别https://blog.csdn.net/qq_37818095/article/details/82351479
 vue-cli3.x目录简介https://www.cnblogs.com/XCWebLTE/p/9546756.html
 官网https://cli.vuejs.org/zh/guide/installation.html