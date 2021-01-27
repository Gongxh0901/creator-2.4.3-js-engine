## 定制引擎

参考链接： https://docs.cocos.com/creator/manual/zh/advanced-topics/engine-customization.html



进入当前文件夹，全局安装 `gulp`构建工具

~~~python
# 安装 gulp 构建工具
npm install -g gulp
~~~

安装依赖模块

```bash
# 安装依赖的模块
npm install
```

修改之后执行命令编译

~~~python
gulp build-dev
~~~

完成后重新启动creator



**注意**：如果在编译过程中出现 `JavaScript heap out of memory` 的报错，可执行以下命令解决：

```js
gulp build-dev --max-old-space-size=8192
```

