# codespaces-blank
介绍
Vant 是一个轻量、可靠的移动端组件库，于 2017 年开源。

目前 Vant 官方提供了 Vue 2 版本、Vue 3 版本和微信小程序版本，并由社区团队维护 React 版本和支付宝小程序版本。

预览
扫描下方小程序二维码，体验组件库示例：



使用之前
使用 Vant Weapp 前，请确保你已经学习过微信官方的 小程序简易教程 和 自定义组件介绍。

安装
方式一.通过 npm 安装 （推荐）
小程序已经支持使用 npm 安装第三方包，详见 npm 支持

# 通过 npm 安装
npm i @vant/weapp -S --production

# 通过 yarn 安装
yarn add @vant/weapp --production

# 安装 0.x 版本
npm i vant-weapp -S --production
方式二.下载代码
直接通过 git 下载 Vant Weapp 源代码，并将 目录拷贝到自己的项目中。dist

git clone https://github.com/youzan/vant-weapp.git
使用组件
以按钮组件为例，只需要在 json 文件中引入按钮对应的自定义组件即可

{
  "usingComponents": {
    "van-button": "/path/to/vant-weapp/dist/button/index"
  }
}
接着就可以在 wxml 中直接使用组件

<van-button type="primary">按钮</van-button>
在开发者工具中预览
# 安装项目依赖
npm install

# 执行组件编译
npm run dev
打开微信开发者工具，把目录添加进去就可以预览示例了。vant-weapp/example

PS：关于 Area 省市区选择组件，地区数据初始化可以直接在云开发环境中导入 文件使用。van-areavant-weapp/example/database_area.JSON

基础库版本
Vant Weapp 最低支持到小程序基础库 2.6.5 版本。[vant-weapp-dev.zip](https://github.com/xuling579/codespaces-blank/files/11711210/vant-weapp-dev.zip)



