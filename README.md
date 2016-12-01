##BWProjectFramework

####Content  
* Xcode项目架构
* 项目文件结构
* 项目代码架构
* 针对不同类型的项目做架构调整
* 待完善
* Focus On Me

##Xcode项目架构
* 掌握Xcode管理项目文件的机制；  
* 除了Xcode作为开发iOS应用的IDE以外，也有JetBrains的AppCode，因此在此讨论的项目架构是基于Xcode作为IDE来讨论的；  
* 使用CocoaPods对第三方库类进行管理，善于使用稳定可靠的开发工具，有助于提高开发效率；

##项目文件结构

文件结构概览  

* AppDelegate Class
* MVC
  * BaseViewController
  * Home
  * Login
  * Register
  * OtherFunctionEntries
* Global
  * Global Class
  * User Class
* Network
  * NetworkConfiguration.h
  * NetworkKit Class
* Common
  * LocationManager
  * ScanBarManager
  * SelectTimeManager
  * SomeFunctionalView
* Utility
  * DataUtility Class
  * UIUtility Class
* Category
* Library
* Resource
  * Image
  * Configuration
  * Database
  * Sound
  * Vedio
* Assets.xcassets
* Supporting Files
  * main.m
  * Info.plist
  * LaunchScreen.storyboard
  * BWProjectFrameworkPrefixHeader.pch

文件结构说明  
MVC    
Global  
Network  
Common  
Utility  
Category  
Library  
Resource

##项目代码架构  

MVC  
Model-View-Controller  
MVVM  
Model-View-ViewModel  

##针对不同类型的项目做架构调整
* 在此的项目架构为一个常规的架构，通常我们都是需要根据我们App产品具体的需求和业务来做更加合适、合理的架构；  
* 总之，灵活的为具体的项目做好架构；

##待完善
* 文件结构根据复杂业务进行进一步地扩展；
* 如何为MVC做好职责分配，以让复杂业务也能有很好的可维护性；
* MVVM如何融入到项目架构中；

####Focus On Me
* 如果觉得此资源能够帮助到你，那么可以毫不吝啬的Star这个Repository，后续也会做持续的更新；
* 假如你是大神，那么可以指点迷津，引导一下后人，留下你对本资源宝贵的建议；如果你是和我一样，乃至是新手，在Github上互粉，那么可以和我共同进步；