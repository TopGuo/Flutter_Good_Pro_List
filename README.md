# Flutter_Good_Pro_List
`Flutter_好的优秀的_项目_集合`

> 这个项目的初衷就是罗列网上的关于Flutter的开源项目以此来帮助帮助大家快速提升

> 项目会持续保持跟新，同时希望大家把自己觉得不错的项目，PR到该项中，或者直接Issue

> 学无先后，达者为师 => Flutter Go!
## 目录索引结构大致如下

>- |--Root
>    - |-- Flutter项目
>    - |-- 纯dart包
>    - |-- 插件包
>    - |-- 优秀blog/简书/掘金...推荐

![](https://github.com/TopGuo/Flutter_Good_Pro_List/blob/master/doc/1.jpg?raw=true)

## Flutter 项目

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

## 优秀blog/简书/掘金...推荐

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





