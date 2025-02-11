<h2 align="center">H5-Editor </h2>
<p align="center">可视化操作，拖拽生成页面，导出html文件</p>
<p align="center" style="color:#0366d6;">针对开发人员具有编辑器插件系统，支持和现有项目继承，支持二次开发</p>
<p align="center">H5-Editor是一个纯前端项目，基于 Vue2 开发、通过拖拽生成页面，类似于 <a href="http://www.eqxiu.com">易企秀</a>、<a href="https://h5.baidu.com">百度 H5</a>等</p>


### Demo

> [点击此处访问在线demo](http://122.51.255.70/poster)

                                                      
## Usage

```bash
git clone https://github.com/a7650/h5-editor.git

cd h5-editor

#如果你已经安装了nodejs，vue-cli等环境，可直接执行下列命令，否则需先安装环境

npm install

npm run dev
```

## 技术栈

主要基于Vue2，Element-ui（少部分使用），Vuex

## 编辑器主要功能

   - 元素自由拖拽，放大，缩小，旋转
   - 可添加图片，文本，矩形，背景。多种编辑功能（字体，背景，大小，边距等）
   - 组件自动吸附，实时参考线（组件可以和画布，自定义参考线以及其他组件进行自动吸附对齐，并显示实时参考线，拖动过程中按下alt键可暂时关闭）
   - 标尺，参考线，可自定义参考线（在标尺上点击即可生成参开线，可拖动参考线更改位置，双击删除参考线）
   - 撤销，重做（支持快捷键，可配置撤销的步数）
   - 组件复制，粘贴，锁定，隐藏等
   - ctrl + 拖动组件可快速复制组件
   - 右键菜单，菜单可配置，可针对组件当前状态灵活生成（即不同的组件可产生不同的菜单）
   - 图层面板，可拖拽更改组件图层，可重命名，可在图层面板快速锁定，删除，隐藏组件
   - 同时选中多组件（按ctrl + 左键），可进行多组件对齐
   - 数据备份，通过indexDB数据库保存在本地（可自动备份，手动备份），并可从备份中恢复数据
   - 一键生成h5代码
   - 编辑画布大小
   - 多种快捷键
   - 设置中心，可设置撤销功能，备份功能等
   - 针对开发人员具有插件系统，可通过插件系统二次开发（教程会稍后写），组件各种属性可灵活配置。

