# Flutter_Good_Pro_List
`Flutter_好的优秀的_项目_集合`

> 这个项目的初衷就是罗列网上的关于Flutter的开源项目以此来帮助帮助大家快速提升

> 项目会持续保持跟新，同时希望大家把自己觉得不错的项目，PR到该项中，或者直接Issue

> 学无先后，达者为师 => Flutter Go!

### 文档持续跟新，持续淘汰不合格的项目，最终目的，本项目只收录百星项目

> qq交流群 付费 可加

![qq交流群 付费 可加](https://github.com/TopGuo/Flutter_Good_Pro_List/blob/master/doc/qqQun.jpg?raw=true)

## 目录索引结构大致如下

>- |--Root
>    - |-- Flutter项目
>    - |-- 纯dart包
>    - |-- 插件包
>    - |-- 优秀blog/简书/掘金...推荐

![](https://github.com/TopGuo/Flutter_Good_Pro_List/blob/master/doc/1.jpg?raw=true)

## Flutter 项目

### flutter影视APP
> github base
[flutter影视APP](https://github.com/onemengxin/FlutterMovieApp?tdsourcetag=s_pctim_aiomsg)

`萌新的第一个flutter应用，仿的一个叫neets的应用`，
没在iOS上测试过（买不起苹果系，你打我？）播放页可能会有问题，没啥技术含量，因为第一次写，代码写的有点蠢，大佬别笑emmm

目前完成了首页，类别，我的，播放页，关于，免责。

个人中心，登录/注册，设置，反馈，搜索，播放记录还没做，播放页切换集数还没写完（完全没动力，瘫痪在天桥底下）

![flutter影视APP](https://camo.githubusercontent.com/0b0b2a0c9de0e52d102117ce50aabc0bdb950e59/687474703a2f2f696d672e6d6f7669652e6170702e62746565652e636f6d2f686f6d652e6a7067)
### fluwx 
>github base
[fluwx](https://github.com/TopGuo/fluwx)

`微信全家桶`
文本分享。
网站分享。
图片分享。
音乐分享。
视频分享。
小程序分享。
发送Auth认证（登录）。
支付。
拉起小程序。

### sy_flutter_alipay
>github base
[sy_flutter_alipay](https://github.com/TopGuo/sy_flutter_alipay)

`支付宝flutter插件`

### sy_flutter_widgets
>github base
[sy_flutter_widgets](https://github.com/lishuhao/sy_flutter_widgets)

`纯flutter Widget组件库，不依赖Native及其它第三方package。`
包括省市区选择器，Rate评分，Stepper步进器，照片墙，地址编辑，自带加载更多的ListView和GridView

![sy_flutter_widgets](https://raw.githubusercontent.com/lishuhao/sy_flutter_widgets/master/example/images/edit_address.jpg)

### Widget flutter 开源项目集合
>base 
[Widget flutter](https://itsallwidgets.com/)


### flutter_boss_v1.0
>GitHub地址
[flutter_boss_v1](https://github.com/TopGuo/flutter_boss_v1.0)

`该项目是基于网上大佬9个月前公布的仿boss直聘app进行的v1.0版本的重构`

,原项目版本过旧，新项目重构后，可以完美运行

![](https://github.com/TopGuo/flutter_boss_v1.0/blob/master/bossapp/doc/shothot/4.gif?raw=true)

### flutter_study 
> githubaddress
[flutter_study](https://github.com/luhenchang/flutter_study)

`啥也不多说，这位大佬号称三天学会flutter开发`

![flutter_study](https://github.com/luhenchang/IMAGE/blob/master/program_ios1.gif?raw=true)

### PullToRefresh
>githubaddress
[PullToRefresh](https://github.com/TopGuo/PullToRefresh)

`本功能只实现基本的上下拉刷新，可在这个基础上进行改进、优化、封装，`

如果只是使用，可在build方法中修改ListView控件和List数组的泛型,已经兼容IOS，已经支持对下拉和上拉的分别控制

![githubaddress](https://raw.githubusercontent.com/baoolong/PullToRefresh/master/demonstrationgif/20181023_90359.gif)

`模仿的京东潮男模块的广告滑动切换，本人做的比较粗糙，大家可以在此基础上改进，`

比如滞后滑动，底层图片缩小等，由于没有进行屏幕适配，所以可能不同的手机会显示很丑，这是由于我在设计图片之间的Magin是用屏幕宽度减去两边距屏幕的宽度，再除以3计算的，大家可以根据需要去设定图片之间的Magin，最好固定值

![githubaddress](https://raw.githubusercontent.com/baoolong/PullToRefresh/master/demonstrationgif/20180814_142135.gif)

`采用ListView绘制，将ListView设置为不可`

手动滑动，然后启动Timer来回拖动，造成跑马灯的错觉 

![githubaddress](https://raw.githubusercontent.com/baoolong/PullToRefresh/master/demonstrationgif/20180814_142220.gif)

### flutter_easyrefresh 
> github base
[flutter_easyrefresh](https://github.com/xuelongqy/flutter_easyrefresh)

> 这个项目文档比较工整，看来作者想好好玩一下

`正如名字一样，EasyreFresh很容易就能在Flutter应用上实现下拉刷新以及上拉加载操作，它支持几乎所有的Flutter控件，但前提是需要包裹成ScrollView。它的功能与Android的SmartRefreshLayout很相似，同样也吸取了很多三方库的优点。EasyreFresh中集成了多种风格的Header和Footer，但是它并没有局限性，你可以很轻松的自定义。使用Flutter强大的动画，甚至随便一个简单的控件也可以完成。EasyreFresh的目标是为Flutter打造一个强大，稳定，成熟的下拉刷新框架`

支持Andorid(光晕)，ios(越界回弹)效果
支持任意的ScrollView控件，如果不是进行简单封装即可(所以理论是所有控件)
支持自定义并且已经集成了很多炫酷的 Header 和 Footer
支持下拉刷新、上拉加载(可自动)
支持 Header 和 Footer 列表嵌入以及视图浮动两种形式

![flutter_easyrefresh](https://raw.githubusercontent.com/xuelongqy/flutter_easyrefresh/master/art/image/float.gif)

### cool_ui 
> github base 
[cool_ui](https://github.com/TopGuo/cool_ui)

> 吐槽，作者给这套东西起名叫cool ui，那是不是很酷呢？

`用flutter实现一些我认为好看的UI控件希望大家提一些觉得不错的控件,我自己一个人想有时候想到的比较有限`

仿iOS的UIPopover效果的
用于弹窗的按钮

![CupertinoPopoverButton]
(https://github.com/TopGuo/cool_ui/raw/master/documents/images/popover_demo.gif)

仿Weui的Toast效果

![仿Weui的Toast效果](https://github.com/TopGuo/cool_ui/raw/master/documents/images/toast_demo.gif)

自定义键盘使用方法快速入门

![自定义键盘使用方法快速入门](https://github.com/TopGuo/cool_ui/raw/master/documents/images/custom_keyboard.gif)

### flutter_news
>GitHub地址
[flutter_news](https://github.com/RafaelBarbosatec/flutter_news)

`新闻应用程序开发用于实践,学习和测试Flutter框架的潜力。`

News application developed for practice, learning and testing the potential of this powerful Framework.
![](https://github.com/RafaelBarbosatec/flutter_news/raw/master/imgs/print1_ios.png)

### flutter_layout
>GitHub地址
[flutter_layout](https://github.com/nb312/flutter_layout)

`Page view	SliverPersistentHeader	Row,Column,CrossAxisAlignment	InkWell`

ListView	SliverGrid	Stack	Shadow
CustomScrollView	SliverFixedExtentList,SliverList	Expanded,Padding	Image.asset
Nested ListView	SliverFillViewport	SizedBox	
GridView	--	Center

![](https://github.com/nb312/flutter_layout/raw/master/screenshots/flutter_layout.gif)




## 纯dart件包

### common_utils
>github 地址
[common_utils](https://github.com/Sky24n/common_utils)

> 推荐语：有人为我们开源出一些常用类库省的我们自己造轮子，且行切珍惜，如果有需要的地方，包里没有，
> 可以pr,让大家一起来维护

`Dart常用工具类库 common_utils`

1、TimelineUtil : 时间轴.(新)
2、TimerUtil : 倒计时，定时任务.(新)
3、MoneyUtil : 精确转换，元转分，分转元，支持格式输出.(新)
4、LogUtil : 简单封装打印日志.(新)
5、DateUtil : 日期转换格式化输出.
6、RegexUtil : 正则验证手机号，身份证，邮箱等等.
7、NumUtil : 保留x位小数, 精确加、减、乘、除, 防止精度丢失.
8、ObjectUtil : 判断对象是否为空(String List Map),判断两个List是否相等.

### flustars
>githubadress
[flustars](https://github.com/Sky24n/flustars)

> 该库的源码我没有详细看，只是做启动页的时候用到了SpUtil 在这里也给大家推荐

`ScreenUtil不依赖context获取屏幕数据,新增MyAppBar,不需要GlobalKey就能openDrawer`

1、SpUtil : SharedPreferences 工具类.
2、ScreenUtil : 获取屏幕宽、高、密度，AppBar高，状态栏高度，屏幕方向.
3、WidgetUtil : 获取Widget宽高，在屏幕上的坐标.

### lpinyin 
> GitHubadress
[lpinyin](https://github.com/flutterchina/lpinyin)

`lpinyin是一个汉字转拼音的Dart package.`

①准确、完善的字库
②拼音转换速度快
③支持多种拼音输出格式：带音标、不带音标、数字表示音标以及拼音首字母输出格式
④支持常见多音字的识别，其中包括词组、成语、地名等
⑤简繁体中文转换
⑥支持添加用户自定义字典

### flukit 
> githubadress
[flukit](https://github.com/flutterchina/flukit)

> 这里我只是将其中的swiper源码抽出来放到项目里

`flukit （Flutter UI Kit）是一个Flutter Widget库。`

注意:
本项目正在开发中，目前没有稳定版，我们暂时不建议您在生产中使用，欢迎大家贡献代码。

## 插件包



### video_player
>pubbase
[video_player](https://pub.dartlang.org/packages/video_player)

`Flutter官方的视频库（也可以用于直播），用于在Android和iOS上与其他`

Flutter窗口小部件一起显示内嵌视频。支持主流直播流。该库底层使用的ExoPlayer播放器。更多关于ExoPlayer播放器支持的视频格式资料请看官方文档ExoPlayer播放器支持的视频格式


### video_launcher	0.3.0	
>pubbase
[pubbase](https://pub.dartlang.org/packages/video_launcher)

`视频播放器`
	
### flute_music_player	0.0.6	
>pub base
[flute_music_player](https://pub.dartlang.org/packages/flute_music_player)

`基于Flutter的材料设计音乐播放器与音频插件播放本地音乐文件.`

### audioplayer	0.5.0	
>pubbase 
[](https://pub.dartlang.org/packages/audioplayer)

`一个播放远程或本地音频文件Flutter音频插件`	

## 优秀blog/简书/掘金...推荐

### Flutter | 状态管理拓展篇
> 掘金地址
[状态管理拓展篇](https://juejin.im/post/5bcea438e51d4536c65d2232)

`作者详细介绍了Flutter中状态管理的知识，不懂可以去拜读一下..`


### Flutter的需要与原生交互的一些常用库
>github base
[Flutter的需要与原生交互的一些常用库](https://github.com/AweiLoveAndroid/Flutter-learning/blob/master/readme/)

`这个readme真是太详细了 强烈推荐`

### flutter-study
>github 地址
 [flutter-study](https://github.com/yang7229693/flutter-study)

`Flutter - 不一样的跨平台解决方案`

Flutter Plugin开发流程
Flutter 布局详解
现有项目中集成Flutter
Flutter 布局（一）- Container详解
Flutter 布局（二）- Padding、Align、Center详解
Flutter 布局（三）- FittedBox、AspectRatio、ConstrainedBox详解
Flutter 布局（四）- Baseline、FractionallySizedBox、IntrinsicHeight、IntrinsicWidth详解
Flutter 布局（五）- LimitedBox、Offstage、OverflowBox、SizedBox详解
Flutter 布局（六）- SizedOverflowBox、Transform、CustomSingleChildLayout详解
Flutter 布局（七）- Row、Column详解
Flutter 布局（八）- Stack、IndexedStack、GridView详解
Flutter 布局（九）- Flow、Table、Wrap详解
Flutter 布局（十）- ListBody、ListView、CustomMultiChildLayout详解
Flutter 布局控件完结篇
Flutter 动画详解（一）
Flutter 动画详解（二）

### Sky24n
>简书地址 
[简书地址](https://www.jianshu.com/p/9e5cc4ba3a8e)

`一个完整的Flutter APP项目`

Flutter 启动页+闪屏广告页+引导页  
Flutter 圆形/圆角头像
Dart    常用工具类库common_utils  
Flutter 汉字转拼音库lpinyin
Flutter 城市列表 索引&悬停
Flutter 时间轴工具类TimelineUtil
Flutter 国际化/多语言库 fluintl
Flutter 单例"同步"SharedPreferences工具类 SpUtil
Flutter 常用工具类库flustars


### Flutter 一些常用库 

> 博客园地址
[Flutter 一些常用库 ](https://www.cnblogs.com/yangyxd/articles/9232308.html)

` 注：版本号会随时间更新，请自行修改。本文集合了 Flutter-learning 中的内容，感谢原作者阿韦(https://github.com/AweiLoveAndroid/Flutter-learning)。转载请注明出处。`

### Flutter-learning
>github base
[Flutter-learning](https://github.com/AweiLoveAndroid/Flutter-learning)

`这个库主要是一些Flutter学习资料，个人总结，项目示例代码。如果你想快速学习Flutter，欢迎查看这个库，对你很有帮助的。喜欢的话就给个Star，谢谢。欢迎大家多提意见，帮忙完善这个库。如果有问题，欢迎提issue。想与我联系请看文档最后的联系方式。感谢大家支持！`

### 咸鱼技术说 
>简书地址
[咸鱼技术说](https://www.jianshu.com/u/cf5c0e4b1111)

`flutter 提升看的好文章`





