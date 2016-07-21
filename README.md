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
butterknife好用不解释，除掉google推出的supportv4 design包引入项目最多的包，使用量说明一切问题<br/>
[butterknife](https://github.com/JakeWharton/butterknife)<br/>
dagger2 google依赖注入亲儿子，不需要解释了，快上车吧
[dagger2]()

---------
##数据库相关
主要就是几个包 GreenDAO OrmLite LiteOrm。

没有横向对比，其中最快的应该是greendao，使用稍微复杂，使用最简单的liteorm。

LiteOrm使用反射


