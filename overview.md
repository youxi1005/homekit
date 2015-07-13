# 简介
该文档旨在帮你编写 HomeKit app。HomeKit 库是用来沟通和控制家庭自动化配件的，这些家庭自动化配件都支持苹果的HomeKit Accessory Protocol。HomeKit应用程序可让用户发现兼容配件并配置它们。用户可以创建一些 action 来控制智能配件（例如恒温或者光线强弱），对其进行分组，并且可以通过 Siri 触发。HomeKit 对象被存储在用户 iOS 设备的数据库中，并且通过 iCloud 还可以同步到其他 iOS 设备。HomeKit 支持远程访问智能配件，并支持多个用户设备和多个用户。HomeKit 还对用户的安全和隐私做了处理。

![](images\1.png)

注意：如果你是开发设计 HomeKit 硬件的供应商，你可以去[ Hardware Developers ](https://developer.apple.com/homekit/) 下的 HomeKit 页面了解 MFi Program 相关信息，也可以阅读 [External Accessory Programming Topics](https://developer.apple.com/library/ios/featuredarticles/ExternalAccessoryPT/Introduction/Introduction.html#//apple_ref/doc/uid/TP40009502).

另请参阅

以下资源提供了更多关于创建HomeKit应用程序的信息：

- [HomeKit User Interface Guidelines](https://developer.apple.com/homekit/ui-guidelines/) 提供了用户界面设计指南

- [App Store Review Guidelines: HomeKit](http://www.cocoachina.com/ios/20150324/11411.html) 提供了加快app审核的技巧

- [HomeKit Framework Reference](https://developer.apple.com/library/ios/documentation/HomeKit/Reference/HomeKit_Framework/index.html#//apple_ref/doc/uid/TP40014519) 描述了HomeKit框架中的类和方法

- [External Accessory Framework Reference](https://developer.apple.com/library/ios/documentation/HomeKit/Reference/HomeKit_Framework/index.html#//apple_ref/doc/uid/TP40014519) 列出了系统提供的发现和配置无线智能家居产品UI

- [HomeKit Catalog](https://developer.apple.com/library/ios/samplecode/HomeKitCatalog/Introduction/Intro.html#//apple_ref/doc/uid/TP40015048) 提供示例演示HomeKit特性

- [WWDC 2014: Introducing HomeKit](https://idmsa.apple.com/IDMSWebAuth/login.html?path=%2F%2Fvideos%2Fwwdc%2F2014%2F%3Fid%3D213&appIdKey=891bd3417a7776362562d2197f89480a8547b108fd934911bcbea0110d07f757) 对 HomeKit 更高层次的分析

- [iOS Security](https://www.apple.com/business/docs/iOS_Security_Guide.pdf) 描述HomeKit如何处理iOS上的安全和隐私

