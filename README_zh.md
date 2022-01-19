# 应用示例

-   [概要简介](#section1470103520301)
-   [目录](#sectionMenu)
-   [使用说明](#section17988202503116)
-   [约束与限制](#section18841871178)
-   [相关仓](#section741114082513)

## 概要简介

为帮助开发者快速熟悉HarmonyOS SDK所提供的API和应用开发流程，我们提供了一系列的应用示例，即Sample。每一个应用示例都是一个独立的DevEco Studio工程项目，开发者可以将工程导入到DevEco Studio开发工具，通过浏览代码、编译工程、安装和运行应用示例来了解应用示例中涉及API的使用方法。

## 目录<a name="sectionMenu"></a>
- AI
  - [`AIFunctionSet:` AI能力（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/AI/AIFunctionSet)
- AccessibilityService 
  - [`AccessibilityService:`无障碍服务（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/AccessibilityService/AccessibilityService)
- CompleteApps
  - [`DistributedSearch:`分布式搜索（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/CompleteApps/DistributedSearch) 
  - [`DistributedShoppingCart:`分布式购物车（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/CompleteApps/DistributedShoppingCart) 
  - [`TicTacToeGame:`井字过三关（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/CompleteApps/TicTacToeGame) 
- ETSUI
  - [`eTSBuildCommonView:`创建简单视图（eTS）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ETSUI/eTSBuildCommonView) 
  - [`eTSDefiningPageLayoutAndConnection:`页面布局和连接（eTS）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ETSUI/eTSDefiningPageLayoutAndConnection) 
  - [`eTSDrawingAndAnimation:`绘图和动画（eTS）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ETSUI/eTSDrawingAndAnimation) 
- JAVAUI
  - [`Animation:`动画（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/Animation) 
  - [`CommonLayout:`常用布局（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/CommonLayout)   
  - [`Components:`组件（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/Components) 
  - [`CustomComponent:`自定义组件（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/CustomComponent)   
  - [`CustomLayout:`自定义布局（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/CustomLayout) 
  - [`Dialog:`对话框（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/Dialog) 
  - [`List:`列表容器（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/List) 
  - [`Localization:`时区与语言（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/Localization) 
  - [`MultiModeInput:`多模输入（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/MultiModeInput) 
  - [`MultimodalEvent:`多模输入事件标准化（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/MultimodalEvent) 
  - [`PositionLayout:`位置布局（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/PositionLayout) 
  - [`ProgressBar:`进度条（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/ProgressBar) 
  - [`TriangleJava:`OpenGL绘制三角形（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JAVAUI/TriangleJava)   
- JSUI
  - [`Image:`基本动画（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/Image) 
  - [`JsAdaptivePortalList:`多设备自适应的效率型首页（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsAdaptivePortalList) 
  - [`JsAdaptivePortalPage:`多设备自适应的FA页面（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsAdaptivePortalPage) 
  - [`JsAdaptiveServiceWidget:`多设备自适应服务卡片（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsAdaptiveServiceWidget) 
  - [`JsAnimation:`动效示例应用（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsAnimation) 
  - [`JsApp:`JsApp（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsApp) 
  - [`JsCallJava:`JsCallJava（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsCallJava) 
  - [`JsComponents:`JS组件（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsComponents) 
  - [`JsFACard:`JS卡片（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsFACard) 
  - [`JsGallery:`图库示例应用（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsGallery) 
  - [`JsShopping:`购物示例应用（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsShopping) 
  - [`JsStartMode:`JS 启动模态配置（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/JsStartMode) 
  - [`UiComponents:`UiComponents（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/UiComponents) 
  - [`UserRegistration:`用户注册（JS,Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/JSUI/UserRegistration)   
- ability
  - [`AbilityConnection:`Ability连接（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/AbilityConnection)   
  - [`AbilityForm:`AbilityForm（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/AbilityForm)   
  - [`AbilityIntent:`Intent启动Ability（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/AbilityIntent)   
  - [`AbilityInteraction:`Ability交互和迁移（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/AbilityInteraction)   
  - [`CommonEvent:`公共事件（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/CommonEvent)   
  - [`CustomNotification:`自定义通知（JS）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/CustomNotification)   
  - [`DataAbility:`DataAbility（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/DataAbility)   
  - [`Delegator:`Ability测试（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/Delegator)   
  - [`DistributedMusicPlayer:`分布式音乐播放（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/DistributedMusicPlayer)   
  - [`DistributedScheduler:`分布式任务调度（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/DistributedScheduler)   
  - [`ForegroundService:`前台服务（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/ForegroundService)   
  - [`Fraction:`Fraction（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/Fraction)   
  - [`Idl:`IDL（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/Idl)   
  - [`Intent:`Intent（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/Intent) 
  - [`IntentAgent:`IntentAgent（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/IntentAgent) 
  - [`Notification:`通知（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/Notification) 
  - [`PageAbility:`PageAbility（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/PageAbility) 
  - [`Pasteboard:`剪切板（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/Pasteboard) 
  - [`ServiceAbility:`ServiceAbility（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/ability/ServiceAbility) 
- common
  - [`Download:`下载服务（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/common/Download)
  - [`HelloWorld:`HelloWorld（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/common/HelloWorld)
  - [`Resources:`资源文件（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/common/Resources)
  - [`Timer:`简单计时器（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/common/Timer)
- data
  - [`DistributedPictures:`分布式文件共享（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/data/DistributedPictures)
  - [`ORM:`对象关系映射数据库（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/data/ORM)
  - [`Preferences:`轻量级偏好数据库（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/data/Preferences)	
  - [`Search:`融合搜索（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/data/Search)	
- device
  - [`BatteryInfo:`电池信息（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/device/BatteryInfo)	
  - [`Compass:`指南针（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/device/Compass)	
  - [`Location:`位置（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/device/Location)	
  - [`Setting:`设置（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/device/Setting)	  
- media
  - [`Audio:`音频（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/media/Audio)
  - [`AudioPlayer:`媒体会话（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/media/AudioPlayer)
  - [`Camera:`相机（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/media/Camera)
  - [`PixelMap:`图像（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/media/PixelMap)
  - [`VideoPlayer:`视频播放（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/media/VideoPlayer)  
- native
  - [`JSNativeDemo:`JSNativeDemo（JS,C++）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/native/JSNativeDemo) 
  - [`NativeImage:`Native_image（Java,C++）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/native/NativeImage) 
  - [`NativeLayer:`Native_layer（Java,C++）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/native/NativeLayer)   
- network
  - [`Bluetooth:`蓝牙（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/network/Bluetooth)
  - [`DistributedAbility:`设备和服务的发现和连接（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/network/DistributedAbility)
  - [`DistributedDevices:`分布式设备（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/network/DistributedDevices)
  - [`NFC:`NFC（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/network/NFC)
  - [`NetworkManagement:`网络管理（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/network/NetworkManagement)
  - [`WLAN:`WLAN（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/network/WLAN)  
- security
  - [`DataSecurity:`数据安全（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/security/DataSecurity)  
  - [`FaceRecognition:`人脸识别（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/security/FaceRecognition)  
  - [`Permission:`应用权限（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/security/Permission)    
- thread
  - [`EventHandler:`线程间通信（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/thread/EventHandler)  
  - [`TaskDispatcher:`线程管理（Java）](https://gitee.com/harmonyos/harmonyos_app_samples/tree/master/thread/TaskDispatcher)  
  
## 使用说明

1.  将独立的应用示例工程导入DevEco Studio进行编译构建及运行调试。
2.  部分应用示例中含有多个模块，开发者可以选择对单个模块进行编译构建，生成一个HAP应用安装包，也可以对整个工程进行编译构建，生成多个HAP应用安装包。
3.  安装运行后，即可在设备上查看应用示例运行效果，以及进行相关调试。

## 约束与限制

1.  安装运行应用示例之前，请先通过config.json文件中的"deviceType"字段来确认该应用示例支持的设备类型，可尝试通过修改该字段使其可以在相应类型的设备上运行（config.json文件一般在代码的entry/src/main路径下，不同的Sample可能会有不同）。
2.  配置开发环境时，如果您想让应用示例运行到HarmonyOS上，请参考[DevEco Studio使用说明](https://developer.harmonyos.com/cn/docs/documentation/doc-guides/tools_overview-0000001053582387)。
3.  Readme中标注为“支持标准系统”或“支持小型系统”的应用示例支持在OpenHarmony上运行，标注为“支持大型系统”的应用示例仅支持在HarmonyOS上运行。
4.  所有OpenHarmony相关示例请参考OpenHarmony组织下的[app_samples仓](https://gitee.com/openharmony/app_samples)。

## 相关仓

1.  HarmonyOS场景化复杂应用示例：[HarmonyOS codelabs](https://gitee.com/harmonyos/harmonyos_codelabs)
2.  OpenHarmony基础应用示例：[OpenHarmony app_samples](https://gitee.com/openharmony/app_samples)
3.  OpenHarmony场景化复杂应用示例：[OpenHarmony codelabs](https://gitee.com/openharmony/codelabs)



