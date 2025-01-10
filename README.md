# Modern CMake for C++  
*Second Edition*  

*轻松构建前沿C++代码，提供高质量的解决方案*<a href=""><img src="cover.png" height="256px" align="right"></a>

* 作者：Rafał Świdziński  
* 译者：陈晓伟
* Packt Publishing Ltd. (出版于: 2024年5月8日)

> [!IMPORTANT]
> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

```c
/*
Note:杨小兵-2025-01-09

1、这本书的名字为：Modern CMake for C++
2、这本书存在第一版，目前学习的这本书则是第二版
3、这本书的推荐理由：轻松构建前沿C++代码，提供高质量的解决方案
4、这本书的原作者是Rafał Świdziński
5、这本书的翻译者是：陈晓伟
6、这本书的出版社是：Packt
*/
```
## 本书概述

创建顶级软件并非易事。在线研究这个主题的开发者难以确定哪些建议是当前的，哪些方法已经更新，或已经有更好的实践方式。此外，大多数资源以混乱的方式解释过程，缺乏适当的背景、上下文和结构。

《Modern CMake for C++》提供了一个端到端的指南，通过全面处理C++解决方案的构建，提供了更简单的体验。不仅介绍如何在项目中使用CMake，还强调了如何使项目保持可维护性、优雅和简洁。该指南会协助读者们自动化完成许多项目中的常见任务，包括构建、测试和打包。

本书还会介绍如何组织源目录、构建目标和创建包。随着了解的深入，将学习编译和链接可执行文件和库，详细理解这些过程，并优化每个步骤以获得最佳结果。此外，还会介绍如何将外部依赖项（如第三方库、测试框架、程序分析工具和文档生成器）整合到自己的项目中。最后，将学习如何导出、安装和打包解决方案，以供内部和外部使用。

阅读完这本书后，将能以专业水平使用CMake。
```c
/*
Note:杨小兵-2025-01-09

1、许多项目中常见的任务
  1.1 构建
  1.2 测试
  1.3 打包
2、介绍内容
  2.1 如何组织源目录？
  2.2 如何构建目标？
  2.3 如何创建包？
  2.4 如何编译、链接可执行文件、库？
  2.5 如何将外部依赖项整合到自己的项目中？
  2.6 如何导出？
  2.7 如何安装？
  2.8 如何打包？
*/
```

## 作者简介

**Rafał Świdziński**是谷歌的一名资深工程师，拥有超过12年的全栈开发经验。他领导过思科Meraki、亚马逊和爱立信等行业巨头的项目，居住在伦敦。他始终站在技术进步的前沿，参与了许多创业项目，最近转向了医疗保健领域的AI。Rafał重视顶尖的代码质量和工艺，也会通过YouTube频道和出版的书籍分享见解。

致Zoe --- 无汝，无书（如果没有你，我无法写出这本书）
```c
/*
Note:杨小兵-2025-01-10

1、这段内容对本书作者做了一个简单的介绍
*/
```


## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp-2ed

* 第一版译文地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp

* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html

  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：

    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "Modern-CMake-for-C++-2ed".tex`

  * 为了内容中表格和目录索引能正常生成，至少需要连续编译两次

  * Latex中的中文字体([思源黑体](https://github.com/adobe-fonts/source-han-sans))和英文字体([Hack](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0))，需要安装后自行配置。如何配置请参考主book/css.tex顶部关于字体的信息。

* vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016
```c
/*
Note:杨小兵-2025-01-10

1、这部分内容暂时应该用不到因为自己只是想要往译文中插入一些学习记录
*/
```