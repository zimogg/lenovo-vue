<template lang='pug' src='./index.pug'></template>
<style lang='less' src='./index.less'></style>
<script lang='ts' src='./index.ts'></script>

node
webpack
npm 
vue 不支持小于等于IE8以下的浏览器，因为object.definePrepty不兼容ie8以下的浏览器，

1、安装vue全局环境：npm install vue-cli -g(安装在全局，也就是在cmd命令窗口安装)
2、打开你需要安装的具体存放本地项目的文件夹 
	vue init webpack admin-xiaohuahua(项目名称)
	注意：unit e2e 步骤no就行  不需要安装
3、cd admin-xiaohuahua(项目名称)
4、npm install 安装vue中需要的依赖包或者插件以及语法转化插件
4、npm run dev/npm start 启动服务器