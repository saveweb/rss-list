# rss-sub-list

> 中文博客列表太多了......

本项目订阅源通过opml文件的方式发布：(包含独立博客和独立播客)

1、定期发布的opml源：https://github.com/saveweb/rss-list/releases (推荐)
> - 分类良好  
> - 订阅源与box.othing.xyz相同(发布时)  

```
总订阅源：824
文章总数：36 200
```

2、实时生成的opml订阅源：https://box.othing.xyz/realtime.opml.xml (不推荐)
> - 订阅源实时同步box.othing.xyz  
> - 部分订阅源的分类可能不正确  
> - 分类和订阅源时常变动  

```
总订阅源：实时生成，你自己数
文章总数：实时生成，你自己数
```

### opml中各分类的含义：

- 新增博客：于本次更新中增加的博客
- Blog|博客: 都是博客
- Podcast|播客：都是播客
- RSS出错：源站出现问题
- 墓场轨道：对应网站已从互联网上消失，可删除
- RSS不规范：如题，这些订阅源过不了w3c检测，部分订阅器可能会报错
- 不再提供RSS：博客本身不再提供RSS
- 不在首页显示：这些订阅源质量堪忧（不限于NSFW、币圈、淘宝客、破解软件发布、羊毛等）因此不在首页信息流中显示。
- SSL出错: 证书过期或域名绑定不正常
- 处理中：我处理出错源的暂存分类，把它当作cache就好了。

关注我们的频道 (https://t.me/blogrsslist) 或Watch本仓库以及时获取opml更新。

本项目除了我们自己主动收录的博客/播客，还包括以下上游源：
> 本仓库把下面的源的源文件放入 /srouce 文件夹是方便搜索。

----

上游源：  
https://github.com/timqian/chinese-independent-blogs 上一次同步于2021/07/07  
https://github.com/typlog/china-indie-podcasts 上一次同步于2021/06/16  
https://github.com/shidenggui/bloghub 暂未使用此源  
https://github.com/RSS-Renaissance/awesome-blogCN-feeds 已使用此源，但该源不活跃  
