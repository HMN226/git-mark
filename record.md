# 工具与资源记录
下面这些工具都是我围绕自己的项目「C 语言学习中心」去找的，来源分别是 GitHub、官网和插件市场。
---
## 一、开源项目
|名称|链接|是干啥的|我为啥选它|
|:--:|:--:|:--:|:--:|
|JSCPP|https://github.com/felixhao28/JSCPP|用纯 JavaScript 写的 C 语言解释器，能让 C 代码在浏览器里跑起来，还能防死循环卡死页面	|我项目的核心就是「在线写 C 代码 + 判分」，跟它思路一样；它的库函数和防卡死做法能直接拿来参考|
|Prism.js|https://prismjs.com|让代码显示彩色的小插件，压缩后才 2KB	|C 代码要上色，它比 highlight.js（约 129KB）轻太多，适合单文件网页|
|Monaco Editor|https://github.com/microsoft/monaco-editor|把 VS Code 编辑器搬到网页，能高亮、自动补全，支持 C 语言	|看过但没用：打包 5MB，跟「单文件要轻」冲突；记下来当以后升级输入框的备选|
## 二、插件
|名称	|链接	|是干啥的	|我为啥选它|
|:--:|:--:|:--:|:--:|
|Live Server（VS Code 插件）|	https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer|	装在 VS Code 里，存一次盘网页就自动刷新	|不用手动按 F5，边写边看效果，调试快很多|
## 三、开发工具
|名称|	链接|	是干啥的	|我为啥选它|
|:--:|:--:|:--:|:--:|
|Chrome DevTools	|https://developer.chrome.com/docs/devtools/	|浏览器自带的调试器，按 F12 打开，能打断点、看报错	|免费、内置、前端必备——我查判分逻辑的 bug 全靠它|
|GitHub Pages|	https://pages.github.com/	|免费把静态网页挂到网上，给你一个网址	|我项目是纯静态单文件，零后台，天生适合；正好满足「能上线」的要求|
|Gitee Pages|	https://gitee.com/help|	国产同类服务，国内访问更快	|GitHub Pages 的国内备选，访问更稳|