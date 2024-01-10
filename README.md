## Github-Script-BLOG
### config.json
> 文件就是配置文件，在创建的仓库内可以找到，默认填写的是我的信息
>> 以下是 必填 字段，可以自定义字段的描述
```
{
    "title":"Meekdai",
    "displayTitle":"eekdai",
    "subTitle":"描述而已",
    "homeUrl":"http://xxx.com",
    "avatarUrl":"http://xxx/images/avatar.jpg",
    "faviconUrl":"http://xxx/images/favicon.ico",
    "singlePage":[],
    "VERSION":"last"
}
```
>> 以下是 非必填 字段，勇于页面展示
```
{
    "email":"email@qq.com",
    "startSite":"02/16/2024",
    "filingNum":"网站备案号",
    "onePageListNum":15,
    "commentLabelColor":"#006b75",
    "yearColorList":["#bc4c00", "#0969da", "#1f883d", "#A333D0"],
    "i18n":"CN",
    "dayTheme":"light",
    "nightTheme":"dark_colorblind",
    "urlMode":"pinyin",
    "style":"",
    "script":"",
}
```
----
>> 如需修改发布时间，在issues文章最后一行添加如下代码,时间是采用时间戳
```
<!-- ##{"timestamp":1490764800}## -->
```
----

>> 自定义单篇文章页面的style和script,在issues文章中添加如下代码
```
<!-- ##{"style":"<style>#postBody{font-size:20px}</style>"}## -->
<!-- ##{"script":"<script async src='//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js'></script>"}## -->
```

>> 添加全局文章页面的style和script, 在config.json文件中添加
```
"style":"<style>#postBody{font-size:20px}</style>",
"script":"<script async src='//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js'></script>",
```

>> 置顶博客文章,只需要Pin issue即可

>> 如果在评论里面登录后评论报错，可直接按照提示安装 utteranc app
```
Error: utterances is not installed on xxx/xxx.github.io. If you own this repo, install the app. Read more about this change in the PR.
```

### 如果有朋友想修改博客的主题，或者添加一些东西，这个框架是支持魔改的。所有的UI都在templates文件中