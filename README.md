# this.Name == "douyu-cleaner-plus"

一个相当于Douyu cleaner插件的东西，使用非常激进的策略清理斗鱼界面。

# 下载和安装

第一步：安装stylish

https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?utm_source=gmail

第二步：安装Douyu cleaner

https://userstyles.org/styles/132037/douyu-cleaner

第三步：安装Douyu cleaner plus

https://userstyles.org/styles/136524/

# Introduction

使用更激进的策略进一步清理直播界面和聊天框，隐藏大部分付费内容，适用于只用斗鱼看特定主播，例如星际老流氓、同卵双狗和电竞慈禧，不关注斗鱼其他活动的人。此样式只负责屏蔽**一般直播间**的东西。

此样式仅在Windows版Google chrome上测试过，更多的只为我自己考虑，也不会测试其他浏览器的兼容性。
请注意必须同时安装本体：
https://userstyles.org/styles/132037/douyu-cleaner

视频区域的礼物特效我也没办法的呀，那个是shockwave flash做的播放器并不是html做的东西stylish屏蔽不了的，估计别的chrome插件也屏蔽不了所以也不要问这个了，我相信用stylish的大部分应该有web方面鸡本功的对不对。

此css样式非原作者授权。若原作者有意将这些规则收录到清爽斗鱼中，请联系:
2917433887@qq.com

Follow me on github:
https://github.com/AozakiOrenji/douyu-cleaner-plus

[2017/2/25]
[+]清理用户面板。考虑了很久之后发现只有用户等级、用户名和‘登出’是有用的。
   毕竟是激进清理嘛。
[+]清理聊天窗口上方的按钮。仅保留2个有可能有用的按钮。

[2017/2/22]
[#]刷存在感。
[+]添加github版本控制
   (虽然一个人做这个没什么好控制的，但是还是希望能收到pull request。)

[2017/1/14]
[+]头图烦死，屏蔽掉。

[2017/1/8]
[+]屏蔽微信提示。

[2017/1/3]
[+]屏蔽掉昨天忘了屏蔽的背包提示。

[2017/1/2]
[+]屏蔽首充提示。
[#]新年快乐！

[2016/12/25]
[+]屏蔽圣诞活动按钮，估计也能屏蔽以后的所有活动，除非斗鱼改dom结构。
[#]修正一个界面元素屏蔽问题。站内信按钮和排名情况我觉得不需要显示，平时没
人关注这些东西，想看的话临时取消一下屏蔽就好了。
[#]将Release notes改为倒序(这也能写进Release notes啊)

[2016/12/23]
[#]紧急修复了不显示礼物名不是"100鱼丸"但可用鱼丸购买的礼物的问题。
现在礼物区域显示所有鱼丸可送的礼物(如果有，例如圣诞节推出的实际上还是100鱼
丸的冰淇淋球)

[2016/12/22]
[+]改进了鱼丸领取的位置。现在，鱼丸领取时间直接显示在原打开领取窗口
按钮的位置，鱼丸领取按钮直接显示在控制栏中。(css原来这么强啊)
[+]屏蔽了新出现了主播商品推荐窗口。
[#]修正了"分享了直播间"前不显示用户名的问题(技术限制未能完全屏蔽此类消息)。

[2016/12/18]
[#]更新描述，修正了屏蔽正常的聊天消息的问题