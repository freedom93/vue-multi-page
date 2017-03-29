# vue-multi-page

打开package.json可以看到没有一些style-loader,sass-loader或者less-loader,
因此在vue里直接import样式的预编译模块在编译的时候就会报错。
因此fork，clong后还需要做些配置和修改一下才能满足自己的项目开发。

## 构建步骤
``` bash
# 安装依赖
npm install
# 本地测试
npm run dev
# 打包
npm run build
```

##引入样式预编译，以sass为例
``` bash
npm install --save-dev style-loader
npm install --save-dev node-sass
npm install --save-dev sass-loader
```

