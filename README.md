# Edge的冲浪游戏
来自edge://surf 的冲浪游戏

## 版权信息

本文档翻译自英文版的[README](https://github.com/jackbuehner/MicrosoftEdge-S.U.R.F./blob/master/README.md)

感谢原作者[jackbuehner](https://github.com/jackbuehner)

原仓库地址：https://github.com/jackbuehner/MicrosoftEdge-S.U.R.F./

This document is translated from the English Version of the [README](https://github.com/jackbuehner/MicrosoftEdge-S.U.R.F./blob/master/README.md)

Thanks for [jackbuehner](https://github.com/jackbuehner)

The URL of the origin respiratory is https://github.com/jackbuehner/MicrosoftEdge-S.U.R.F./

---

![image](https://user-images.githubusercontent.com/16235094/68094282-c960d400-fe6c-11e9-8719-e3da9a5149ee.png)

我不是游戏的创造者，我只是游戏的搬运工，这个剥离出来的版本能在edge浏览器外独立运行。

## 游戏地址
在 http://surf.costg.cf 玩

## 修改
- 修改文件的位置和一些链接
- 增加了网页图标和适应不同尺寸的图标
- 增加manifest.json来让网页变成一个应用
- 把压缩的js文件复原方便编辑
- 在 surf.bundle.js 里更新了需要依赖 [WebUI](https://chromium.googlesource.com/chromium/src/+/HEAD/docs/webui_explainer.md) 函数并调用到边缘的原生代码。这些功能现在使用LocalStorage 的功能来保存游戏统计数据。
- 
## 不足
- 单击宝藏无法出现edge浏览器的新图标。

如果你知道如何修复这个图标，请到https://github.com/jackbuehner/MicrosoftEdge-S.U.R.F./pulls 开一个pull request并等待原作者的后续合并。
