
##Android知识点

##比较牛的分享库

#最新的控件[awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)


#最新的库[awesome-android-libraries](https://github.com/wasabeef/awesome-android-libraries)


#使用的一些框架
-----
##网络连接

此处推荐使用okhttp＋retrofit联合使用，square大礼包

[okhttp](https://github.com/square/okhttp)

[retrofit](retrofit)

volley google亲儿子不好用一样会被抛弃。在某些情况下比较好用，虽然我不知道这个某些情况具体是哪种情况

xutils


-------
##图片缓存
首发推荐fresco，facebook推出，支持gif以及webp支持度高，缺点jar包比较大<br/>
###[fresco](https://github.com/facebook/fresco)<br/>
picasso square大礼包之一，对gif支持不好，对webp支持不好<br/>
[picasso](https://github.com/square/picasso)<br/>
glide google工程师私人项目，在google项目中有用到。<br/>
[glide](https://github.com/bumptech/glide)<br/>

------
##依赖注入
butterknife好用不解释，除掉google推出的supportv4 design包引入项目最多的包，使用量说明一切问题

[butterknife](https://github.com/JakeWharton/butterknife)

dagger2 google依赖注入亲儿子，不需要解释了，快上车吧

[dagger2](https://github.com/google/dagger)

dagger2的教程推荐[教程](https://github.com/luxiaoming/dagger2Demo)

---------
##数据库相关
主要就是几个包

 [GreenDAO](https://github.com/greenrobot/greenDAO) 出了名的快，不是那么容易使用，所有和数据库相关的类都需要提前生成
 
 OrmLite 
 
 [LiteOrm](https://github.com/litesuits/android-lite-orm)

我没有横向对比，其中最快的应该是greendao，**使用稍微复杂**，使用最简单的liteorm。

LiteOrm使用反射

------------
#其他相关

##[RxAndroid](https://github.com/ReactiveX/RxAndroid)

响应式编程,看完以下[教程](http://gank.io/post/560e15be2dca930e00da1083)绝对就会了

##下拉刷新

[pulltoRefresh](https://github.com/chrisbanes/Android-PullToRefresh)最老的下拉刷新的控件，现在已经不更新了，缅怀一下

[Ultra](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)不知道为什么他的配图老是显示不全

[BGARefreshLayout](https://github.com/bingoogolapple/BGARefreshLayout-Android)没有实际用过

##侧滑返回上一界面

[SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout)

##仿ios的pickerview控件

[PickerView](https://github.com/saiwu-bigkoo/Android-PickerView)

##头部广告位的viewpager

[ConvenientBanner](https://github.com/saiwu-bigkoo/Android-ConvenientBanner)

[AndroidImageSlider](https://github.com/daimajia/AndroidImageSlider)

[DecentBanner](https://github.com/chengdazhi/DecentBanner)

##滚动标题

[StickyHeaders](https://github.com/ShamylZakariya/StickyHeaders)

##标题栏变色

[SystemBarTint](https://github.com/jgilfelt/SystemBarTint)


##图片库

[CircleImageView](https://github.com/hdodenhof/CircleImageView)

放大缩小图片的控件

[PhotoView](https://github.com/chrisbanes/PhotoView)

facebook出品

[rebound](https://github.com/facebook/rebound)

图片压缩库

[Luban](https://github.com/Curzibn/Luban)

图片的模糊效果库

[Blurry](https://github.com/wasabeef/Blurry)

图片剪切

[uCrop]()

加载大图

[LargeImage]()

添加倾斜标签

[SimpleTagImageView]()

图片移动

[MovingImageView]()

##recyclerview相关

仿galley能够使一个布局居中显示
[CleverRecyclerView](https://github.com/luckyandyzhang/CleverRecyclerView)

快速构建recycler的adapter

[BaseRecyclerViewAdapter](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)

标题居于上方的recyclerview

[StickyRecyclerView](https://github.com/timehop/sticky-headers-recyclerview)

##输入框相关

发帖专用

[richeditor-android](https://github.com/wasabeef/richeditor-android)


##WebView相关
js和native互相调用，基础知识

[基础](https://github.com/zhonghangIT/MyWebView)

框架webViewjavascripBridge

[webViewjavascripBridge](https://github.com/lzyzsd/JsBridge)

## 快速打包工具

号称100个签名包只用5秒

[PackerNgPlugin](https://github.com/mcxiaoke/packer-ng-plugin)


