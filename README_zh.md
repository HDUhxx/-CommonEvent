# 应用示例

-   [概要简介](#section1470103520301)
-   [使用说明](#section17988202503116)
-   [约束与限制](#section18841871178)
-   [相关仓](#section741114082513)

## 概要简介

为帮助开发者快速熟悉HarmonyOS SDK所提供的API和应用开发流程，我们提供了一系列的应用示例，即Sample。每一个应用示例都是一个独立的DevEco Studio工程项目，开发者可以将工程导入到DevEco Studio开发工具，通过浏览代码、编译工程、安装和运行应用示例来了解应用示例中涉及API的使用方法。

## 使用说明

1.  将独立的应用示例工程导入DevEco Studio进行编译构建及运行调试。
2.  部分应用示例中含有多个模块，开发者可以选择对单个模块进行编译构建，生成一个HAP应用安装包，也可以对整个工程进行编译构建，生成多个HAP应用安装包。
3.  安装运行后，即可在设备上查看应用示例运行效果，以及进行相关调试。

## 约束与限制

1.  安装运行应用示例之前，请先通过config.json文件中的"deviceType"字段来确认该应用示例支持的设备类型，可尝试通过修改该字段使其可以在相应类型的设备上运行（config.json文件一般在代码的entry/src/main路径下，不同的Sample可能会有不同）。
2.  配置开发环境时，如果您想让应用示例运行到HarmonyOS上，请参考[DevEco Studio使用说明](https://developer.harmonyos.com/cn/docs/documentation/doc-guides/tools_overview-0000001053582387)。


## 相关仓

1.  OpenHarmonyOS 系统下的应用示例：[OpenHarmonyOS_app_sample](https://gitee.com/openharmony/app_samples)
