##### TODO : 汉化

# Awesome Android

A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java).


- [库列表](#Libraries)
    - [图标类](#charts)
    - [依赖注入类](#dependency-injection)
    - [游戏开发类](#game-development)
    - [图形界面类](#gui)
        - [功能条ActionBar](#actionbar)
        - [导航](#navigation)
        - [动画](#animations)
        - [图像](#images)
        - [输入](#inputs)
        - [图片载入](#loading-images)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [网络](#networking)
    - [数据库](#database)
        - [对象关系映射ORM](#orm)
    - [REST](#rest)
    - [测试类](#testing)
    - [Tracking](#tracking)
    - [工具类](#utility)
    - [无线类](#wireless)
    - [其他类](#other)
- [资源](#resources)
    - [More lists of libraries](#more-lists-of-libraries)
- [开发备选方案](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#Lua)
    - [Scala](#scala)
    - [Groovy](#Groovy)
    - [Kotlin](#Kotlin)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Libraries

### Charts

- [AChartEngine](http://code.google.com/p/achartengine/) - Charting Engine.
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - Chart and graph library.
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - Chart library with good motion capabilities.

### Dependency Injection

- [RoboGuice](https://github.com/roboguice/roboguice) - 安卓依赖注入框架
- [Dagger](https://github.com/square/Dagger) - Java和安卓依赖注入框架
- [Butter Knife](http://jakewharton.github.io/butterknife) - Android视图(view)注入功能库.

### Game Development

- [AndEngine](http://www.andengine.org/) - 免费，快速又萌萌达的Android 2D OpenGL游戏引擎.
- [Vuforia](https://www.vuforia.com) - 现实增强功能库.
- [Unity](http://unity3d.com/unity/multiplatform/mobile) - 跨平台游戏创作系统.

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) -一个V4 support library支持的拉动刷新布局(layout)控件.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - 用于构造UI卡片的安卓库.
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - 支持多列行可变的网格视图(View）控件，
- [AQuery](https://code.google.com/p/android-query/) - 轻量级安卓库，用来执行异步任务和操纵界面元素.
- [Flow](https://github.com/square/flow) - 通过一系列相对独立的截屏来辅助描述App的功能库.
- [Crouton](https://github.com/keyboardsurfer/Crouton) - 安卓上下文相关的通知控件
- [DragSortListView](https://github.com/bauerca/drag-sort-listview) - 支持拖拽排序的安卓ListView扩展控件(不再维护).

#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - 为老版本安卓设计的ActionBar.
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Play Music App同款渐变效果action bar.

#### Navigation
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - 提供划入式菜单支持的项目库.
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - 用在指示ViewPager页面之间导航的交互式标识器.
- [Page View indicator](https://github.com/JakeWharton/Android-ViewPagerIndicator) - ViewPager水平滚动页面位置标识器.

#### Animations
- [NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids) - Library for using the Honeycomb animation API on all versions of the platform back to 1.0.
- [Rebound](https://github.com/facebook/rebound) - 引入弹簧动态模型(spring dynamics model)的Java动画库.
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - 卡哇伊视图动画集合.

#### Images

- [android-crop](https://github.com/jdamcd/android-crop) - 用于图片裁剪的项目库.
- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - 安卓高性能圆形图片视图.

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - 输入框悬浮提示项目库(Star 101). *不支持Gradle或者Maven.*
- [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - 符合Material Design的UI控件库，支持浮动标签，底部省略号，字符数限制和自定义error color等

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
- [DbInspector](https://github.com/infinum/android_dbinspector) - 为调试目的，提供的一种查看in-app数据库的简单方式(Star 307).
- [Realm](https://github.com/realm/realm-java) - SQLite和ORMs之外的另一个选择, 简单，新颖快速！面向对象的API和多平台支持(Star 1227).

#### ORM

- [GreeDAO](http://greendao-orm.com) - 安卓SQLite对象数据映射解决方案.
- [ormLight](http://ormlite.com/sqlite_java_android_orm.shtml) - 面向JDBC和安卓的轻量级对象关系映射库.
- [ActiveAndroid](http://www.activeandroid.com) - 活动记录(Active record)风格的对象关系映射库.
- [Sugar ORM](http://satyan.github.io/sugar/) - 为与安卓数据库交互提供一种轻松便捷的方式(Star 758).

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
- [Google Play Services](http://developer.android.com/google/play-services/index.html) - 提供Goolge服务的访问的库，例如帐户同步,Google+(共享,单点登录)，Google地图，位置API，Google Play游戏，云消息，Android的设备管理器，和其他.
- [Tape](https://github.com/square/tape) - 为Java/安卓打造的一个轻量，快速，基于文件的FIFO，同时提供会话支持(Star 896).
- [Android Annotation framework](https://github.com/excilys/androidannotations) - 使用Java注解(annotation), 开发者能够展示意图, 并能够在编译期间使用AndroidAnnotations产生衔接代码(plumbing code)(Star 4468).
- [Google Core Libraries](https://code.google.com/p/guava-libraries/) - 集合,缓存,原语支持,并发库,通用注解,字符串处理,I/O等等.
- [Android Scripting](http://code.google.com/p/android-scripting/) - Android脚本语言支持.
- [Android Priority Job Queue](https://github.com/path/android-priority-jobqueue) - 优先级工作队列库，可以用来简化后台作业调度，提高UX和App稳定性(Star 1288).
- [RateMeMaybe](https://github.com/Kopfgeldjaeger/RateMeMaybe) - 提示用户是否愿意到PlayStore对App打分的功能库(star 57).
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - 该函数库提供简便方式，向用户展现一个提示App打分的对话框(Star 22).
- [ZXing Android-Integration](https://github.com/zxing/zxing) - 提供1维/2维条形码支持的函数库(Star 3958).
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - 安卓Java 8 Lambdas支持库(Star 668)

## Resources

- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - 来自Lars Vogel的高质量教程.
- [Android Design in Action Video series] (https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) Google安卓设计团队带来的Android Design in Action视频教程系列.
- [Android Design in Action slides] (https://play.google.com/store/apps/details?id=com.astuetz.android.adia&feature=md)- Google的Android Design in Action系列教程的ppt.
- [Android DevBytes Video Series] (https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - 与Android Design in Action旗鼓相当的技术视频教程.
- [Android Hive Tutorials](http://www.androidhive.info) - 高质量初学者教程.
- [Android Weekly](http://androidweekly.net) - 安卓新闻周刊.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - 图标和其他小固件产生器(Star 670).
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/). ActionBar风格产生器(已经不推荐).
- [Device Art Generator](http://developer.android.com/distribute/tools/promote/device-art.html) - 用App截屏制作设作品插图.
- [Android UI design resources] (http://androiduiux.com/free-design-resources/) - 提供来自于UI/UX领域google专家的各种设计资源.
- [Pencil Project] (http://pencil.evolus.vn/) - 开源原型设计软件.

### More lists of libraries
- [The Android Arsenal](http://android-arsenal.com) - Large list of android libraries
- [DevAppsDirect - Demo Market](https://play.google.com/store/apps/details?id=com.inappsquared.devappsdirect) - App that demonstrates different libraries.
- [Square libraries](http://square.github.io/#android) - Multiple high quality libraries by square.
- [Android.hew.io](http://android.hew.io) - Yet another list of android libraries.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](http://xamarin.com) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](http://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/titanium/) - Open-source framework to create 'native' cross platform apps using JavaScript.

### Lua
- [Corona SDK](http://coronalabs.com/products/corona-sdk/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scala on Android](http://macroid.github.io/ScalaOnAndroid.html) - Introduction to Scala on Android.
- [Scaloid](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala.
- [Macroid](https://github.com/macroid/macroid) - A modular functional UI language for Android.

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android](https://github.com/melix/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android.
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations.

### Kotlin
- [Koan](https://github.com/yanex/koan) - DSL for Android written in Kotlin.

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
