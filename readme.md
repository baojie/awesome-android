
# Awesome Android

一个超级棒的安卓资源库列表[libraries](#libraries) and [resources](#resources). 对于通用Java库，请参考 [awesome-java](https://github.com/akullpp/awesome-java).


- [库列表(Libraries)](#libraries)
    - [图表(Charts)](#charts)
    - [依赖注入(Dependency Injection)](#dependency-injection)
    - [游戏开发(Game Development)](#game-development)
    - [图形界面(GUI)](#gui)
        - [功能条(ActionBar)](#actionbar)
        - [导航(Navigation)](#navigation)
        - [动画(Animations)](#animations)
        - [图像(Images)](#images)
        - [输入(Inputs)](#inputs)
        - [图片载入(Loading images)](#loading-images)
    - [JSON](#json)
    - [宕机监控(Crash monitoring)](#crash-monitoring)
    - [网络(Networking)](#networking)
    - [数据库(Database)](#database)
        - [对象关系映射ORM](#orm)
    - [REST](#rest)
    - [测试(Testing)](#testing)
    - [追踪(Tracking)](#tracking)
    - [工具(Utility)](#utility)
    - [无线(Wireless)](#wireless)
    - [其他(Other)](#other)
- [资源(Resources)](#resources)
    - [更多库列表](#more-lists-of-libraries)
- [开发备选方案(Development Alternatives)](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#Lua)
    - [Scala](#scala)
    - [Groovy](#Groovy)
    - [Kotlin](#Kotlin)
- [其他超棒库类表](#other-awesome-lists)
- [投稿](#contributing)

## Libraries

各种好用的库

### Charts

- [AChartEngine](http://code.google.com/p/achartengine/) - 图表引擎.
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - 图表图形库(Star 711).
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - 具有良好的动态特性的图表库(Star 608).

### Dependency Injection

- [RoboGuice](https://github.com/roboguice/roboguice) - 安卓依赖注入框架(Star 2699).
- [Dagger](https://github.com/square/Dagger) - Java和安卓依赖注入框架(Star 2899).
- [Butter Knife](http://jakewharton.github.io/butterknife) - Android视图(view)注入功能库(Star 2811).

### Game Development

- [AndEngine](http://www.andengine.org/) - 免费, 快速, 萌萌达的Android 2D OpenGL游戏引擎.
- [Vuforia](https://www.vuforia.com) - 现实增强功能库.
- [Unity](http://unity3d.com/unity/multiplatform/mobile) - 跨平台游戏创作系统.

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) -一个V4 support library支持的拉动刷新布局(layout)控件.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - 用于构造UI卡片的安卓库(Star 3016).
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - 支持多列行可变的网格视图(View）控件(Star 3051)
- [AQuery](https://code.google.com/p/android-query/) - 轻量级安卓库，用来执行异步任务和操纵界面元素.
- [Flow](https://github.com/square/flow) - 通过一系列相对独立的截屏来辅助描述App的功能库(Star 675).
- [Crouton](https://github.com/keyboardsurfer/Crouton) - 安卓上下文敏感的通知控件(Star 2260).
- [DragSortListView](https://github.com/bauerca/drag-sort-listview) - 支持拖拽排序的安卓ListView扩展控件(不再维护)(Star 2052).

#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - 兼容老版本安卓设计的ActionBar(不再维护)(Star 6625).
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Play Music App同款渐变效果action bar(Star 1990).

#### Navigation
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - 提供滑入式菜单支持的项目库(Star 7054).
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - 用在指示ViewPager页面之间导航的交互式标识器(Star 2858).
- [Page View indicator](https://github.com/JakeWharton/Android-ViewPagerIndicator) - ViewPager水平滚动页面位置标识器(Star 4970).

#### Animations
- [Rebound](https://github.com/facebook/rebound) - 引入弹簧动态模型(spring dynamics model)的Java动画库(Star 1631).
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - 漂亮的动画效果集合(Star 2180).

#### Images

- [android-crop](https://github.com/jdamcd/android-crop) - 用于图片裁剪的项目库(Star 910).
- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - 安卓高性能圆形图片视图(Star 660).

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - 输入框悬浮提示项目库(Star 101). *不支持Gradle或者Maven.*
- [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - 符合Material Design的UI控件库，支持浮动标签，底部省略号，字符数限制和自定义error color等(Star 839).

#### Loading Images

- [Picasso](https://github.com/square/picasso) - 强劲的图像下载和缓存安卓库(Star 4936).
- [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - 异步开箱即用型图像载入和缓存库(Star 7395).

### JSON

- [Gson](https://code.google.com/p/google-gson/) - 基于JSON的对象序列化和反序列化Java库.
- [Jackson JSON Processor](http://jackson.codehaus.org) - 高性能JSON处理器.

### Crash monitoring

- [Crashlytics](https://crashlytics.com) - 简洁crash报告方案.
- [HockeyApp](http://hockeyapp.net) - 提供分布，崩溃报告，反馈和分析方案

### Networking

- [Ion](https://github.com/koush/ion) - 安卓异步网络和图像载入库(Star 2734).
- [OkHttp](https://github.com/square/okhttp) - 安卓和Java的HTTP + SPDY客户端库(Star 3354).
- [Asynchronous Http Client](https://github.com/loopj/android-async-http) - 异步HTTP项目库(Star 5370).
- [RoboSpice](https://github.com/stephanenicolas/robospice) - 用于简化异步网络请求的安卓模块库(Star 2114).
- [IceNet](https://github.com/anton19/IceNet) - 简单快速的安卓网络库(Star 33).
- [Android Volley](http://developer.android.com/training/volley/index.html) - 官方发布的，简化网络操作的http库.

### Database
- [Cupboard](https://bitbucket.org/qbusict/cupboard) - 通过ContentProvider框架或者直接数据库访问来简化sqlite操作.
- [DbInspector](https://github.com/infinum/android_dbinspector) - 为调试目的，提供的一种简单的查看in-app数据库的方式(Star 307).
- [Realm](https://github.com/realm/realm-java) - SQLite和ORMs之外的另一个选择, 简单，新颖快速！面向对象的API和多平台支持(Star 1227).

#### ORM

- [GreeDAO](http://greendao-orm.com) - 安卓SQLite对象数据映射解决方案.
- [ormLight](http://ormlite.com/sqlite_java_android_orm.shtml) - 面向JDBC和安卓的轻量级对象关系映射库.
- [ActiveAndroid](http://www.activeandroid.com) - 活动记录(Active record)风格的对象关系映射库.
- [Sugar ORM](http://satyan.github.io/sugar/) - 提供一种轻松便捷的方式来与安卓数据库进行交互(Star 758).

### REST

- [Retrofit](http://square.github.io/retrofit/) - 将REST API转换成Java接口(Star 4242).

### Testing

- [Robotium](https://code.google.com/p/robotium/) - 为UI黑箱测试提供的自动化测试框架.
- [Roboletric](http://robolectric.org/) - 提供一套单元测试框架， 将测试运行在工作站PC的JVM上，而不是模拟器上.
- [AssertJ Android](https://github.com/square/assertj-android) - 提供与安卓匹配的aseertion框架(Star 791).

### Tracking

- [MobileAppTracking](http://mobileapptracking.com/) - 通过多路广告渠道网络，跟踪你的营销活动.
- [Mixpanel](https://mixpanel.com/) - 用户分析平台.

### Utility

- [EventBus](http://greenrobot.github.io/EventBus/) - 帮助简化Activities, Fragments, Threads, Services之间的通信（Star 3512).
- [Otto](https://github.com/square/otto) - 为安卓定制的事件总线(Event Bus)(Star 2242).

### Wireless

- [SmartGattLib](https://github.com/movisens/SmartGattLib) - 简化与蓝牙智能设备(比如蓝牙低功耗设备BLE)的通信(Star 64).

### Other

- [Android Support library](http://developer.android.com/tools/support-library/index.html) - 安卓支持库(Support Library)是一个核心库集合，提供安卓framework API反向兼容版本.
- [Google Play Services](http://developer.android.com/google/play-services/index.html) - 提供Goolge服务的访问的库，例如帐户同步,Google+(共享,单点登录)，Google地图，位置API，Google Play游戏，云消息，Android的设备管理器等.
- [Tape](https://github.com/square/tape) - 为Java/安卓打造的一个轻量，快速，基于文件的FIFO，同时提供会话支持(Star 896).
- [Android Annotation framework](https://github.com/excilys/androidannotations) - 基于Java注解(annotation), 开发者能够给出定义, 并在编译期间使用AndroidAnnotations产生衔接代码(plumbing code)(Star 4468).
- [Google Core Libraries](https://code.google.com/p/guava-libraries/) - 集合,缓存,原语支持,并发库,通用注解,字符串处理,I/O等等.
- [Android Scripting](http://code.google.com/p/android-scripting/) - Android脚本语言支持.
- [Android Priority Job Queue](https://github.com/path/android-priority-jobqueue) - 优先级工作队列库，可以用来简化后台作业调度，提高UX和App稳定性(Star 1288).
- [RateMeMaybe](https://github.com/Kopfgeldjaeger/RateMeMaybe) - 提示用户是否愿意到PlayStore对App打分(star 57).
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - 该函数库提供简便方式，向用户展现一个提示App打分的对话框(Star 22).
- [ZXing Android-Integration](https://github.com/zxing/zxing) - 提供1维/2维条形码支持的函数库(Star 3958).
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - 安卓Java 8 Lambdas支持库(Star 668)

## Resources

- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - 来自Lars Vogel的高质量教程.
- [Android Design in Action Video series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) Google安卓设计团队带来的Android Design in Action系列视频教程.
- [Android Design in Action slides](https://play.google.com/store/apps/details?id=com.astuetz.android.adia&feature=md)- Google的Android Design in Action系列教程的PPT.
- [Android DevBytes Video Series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - 与Android Design in Action旗鼓相当的系列技术视频教程.
- [Android Hive Tutorials](http://www.androidhive.info) - 高质量初学者教程.
- [Android Weekly](http://androidweekly.net) - 安卓新闻周刊.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - 图标和其他小固件产生器(Star 670).
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/). ActionBar风格产生器(已经不推荐).
- [Device Art Generator](http://developer.android.com/distribute/tools/promote/device-art.html) - 用App截屏制作设作品插图.
- [Android UI design resources](http://androiduiux.com/free-design-resources/) - 提供来自于UI/UX领域google专家的各种设计资源.
- [Pencil Project](http://pencil.evolus.vn/) - 开源原型设计软件.

### More lists of libraries
- [The Android Arsenal](http://android-arsenal.com) - 大量安卓项目库列表.
- [DevAppsDirect - Demo Market](https://play.google.com/store/apps/details?id=com.inappsquared.devappsdirect) - 展示不同函数库的App.
- [Square libraries](http://square.github.io/#android) - Square提供的多种高质量的功能库.
- [Android.hew.io](http://android.hew.io) - 另外一个安卓库列表.

## Development Alternatives

目前来说，个人推荐采用安卓API来构建一个本机(native)应用程序. Scala能够以一种更简洁的代码方式来帮助构建这种本机应用. 但是也会有例外出现，在这些案例中，采用一些跨平台开发的替代方案可能会更有帮助.

### C&#35;

- [Xamarin](http://xamarin.com) - 采用C#来创建iOS, 安卓和Window应用的框架.

### HTML, CSS and Javascript

- [PhoneGap](http://phonegap.com) - Adobe开发的，采用HTML, CSS和JavaScript技术来构建跨平台移动App的开源框架.
- [Titanium](http://www.appcelerator.com/titanium/) - 采用JavaScript来创建跨平台"本机“应用的开源框架.

### Lua
- [Corona SDK](http://coronalabs.com/products/corona-sdk/) - 创建本机(native)iOS和安卓应用的框架(特别是游戏应用).

### Scala
- [Scala on Android](http://macroid.github.io/ScalaOnAndroid.html) - 运行在安卓上的Scala介绍.
- [Scaloid](https://github.com/pocorall/scaloid) - Scaloid使你的安卓代码跟容易理解和维护(Star 1343).
- [Macroid](https://github.com/macroid/macroid) - 安卓模块化函数式UI语言(Star 172).

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - 运行在安卓上的Groovy介绍.
- [Groovy Language Support for Android](https://github.com/melix/groovy-android-gradle-plugin) - 用于为安卓平台编译Groovy的Gradle插件(Star 320).
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - 基于注解(Annotation)的安卓多用途函数库，包括视图注入和多线程(Star 136).

### Kotlin
- [Koan](https://github.com/yanex/koan) - Kotlin编写的安卓领域特定语言(DSL)(Star 21).

# Other Awesome Lists
可以在这里找他其他吊爆的项目列表[awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) .

## Contributing
欢迎贡献你的力量!请先阅读[contribution guidelines](contributing.md)
