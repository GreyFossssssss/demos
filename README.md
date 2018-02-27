## 仓库说明

这个仓库是放上自己业余时间做的demos，时不时更新，链接地址请戳 http://reng99.cc/demos/  如果喜欢本仓库，给颗星🌟支持下了 :rocket:

本地运行说明：

```bash
# 进入桌面（建议放在桌面，比较好查找，或者放在你喜欢的地方）
$ cd desktop

# 克隆本项目
$ git clone https://github.com/reng99/demos.git

# 安装依赖
$ npm install

# 本地运行，运行后在浏览器上打开地址http://localhost:9000
$ npm run dev

# 线上环境
$ npm run build

```

⚠️ 注意

1. 在src上进行修改。我做了处理-->您在src文件夹内添加的文件保存后，在本地运行的时候会进行自动刷新的，以提高你的开发效率。添加新文件时候得中断控制台运行`ctrl+c`

2. vendor文件夹存放的是第三方插件，我这里是对同一个文件进行不同命名，方便两个环境的引用，开发环境引用非`.min`的文件啦。可以根据实际情况引用第三方库，命名规范--`filename.min.js & filename.js || filename.min.css & filename.css`

3. html和css文件中图片引用请用相对路径（css文件中的imgs引用有点问题，请在运行npm run dev前加多一层`../`）


## 目录

[1. 循环轮播图](http://reng99.cc/demos/dist/html/carousel/)线上地址

![carousel_demo.gif](./images/carousel_demo.gif)

[2. 模态框弹出层](http://reng99.cc/demos/dist/html/modal/)线上地址

![modal_demo.gif](./images/modal_demo.gif)

[3. 查看图片](http://reng99.cc/demos/dist/html/scaleImg/)线上地址

![scaleImg_demo.gif](./images/scaleImg_demo.gif)

[4. 地区三级联动](http://reng99.cc/demos/dist/html/area/)线上地址

![area_demo.gif](./images/area_demo.gif)

## 遗留的问题

1. npm run dev 的css文件的背景图的路径不正确，待改正
