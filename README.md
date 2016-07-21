![长点心吧](https://github.com/zhonghangIT/catalogue/blob/master/img/2135203850.jpg?raw=true)
##Android知识点
#基础知识
[Intent使用](https://github.com/zhonghangIT/IntentUse)
<br/>
[基础控件](https://github.com/zhonghangIT/MyView)
<br/>
#使用的一些框架
-----
##网络连接<br/>
此处推荐使用okhttp＋retrofit联合使用，square大礼包

[okhttp](https://github.com/square/okhttp)

[retrofit](retrofit)

volley google亲儿子不好用一样会被抛弃。在某些情况下比较好用，虽然我不知道这个某些情况具体是哪种情况

xutils


-------
##图片缓存
首发推荐fresco，facebook推出，支持gif以及webp支持度高，缺点jar包比较大<br/>
[fresco](https://github.com/facebook/fresco)<br/>
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

##滚动标题

[StickyHeaders](https://github.com/ShamylZakariya/StickyHeaders)

##标题栏变色

[SystemBarTint](https://github.com/jgilfelt/SystemBarTint)



