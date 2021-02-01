# Bilibili_API
哔哩哔哩API合集
UP主、视频API (所有标明此颜色的需替换)

http://api.bilibili.com/archive_stat/stat?aid=AV号&type=jsonp

视频基本信息(AV号、观看、弹幕、评论、收藏、硬币、分享、喜欢、版权[1自制2转载])

https://api.bilibili.com/x/space/upstat?mid=UUID&jsonp=jsonp

UP主信息(视频总播放数、文章总浏览数)

https://api.bilibili.com/x/relation/stat?vmid=UUID&jsonp=jsonp

UP主信息2(UUID、关注数、黑名单、粉丝数)

http://api.bilibili.com/x/elec/show?aid=AV号

视频充电

http://api.bilibili.com/x/tag/archive/tags?aid=AV号&jsonp=jsonp

视频标签Tag

http://api.live.bilibili.com/bili/living_v2/UUID?callback=liveXhrDone

UP主直播间地址

http://api.bilibili.com/x/v2/reply?jsonp=jsonp&pn=1&type=1&oid=AV号

视频评论

http://space.bilibili.com/ajax/member/getSubmitVideos?mid=UUID&;pagesize=单页显示数&page=页数

UP主视频列表(分页)

https://api.bilibili.com/x/web-interface/archive/desc?&aid=AV号

视频简介(\n为换行符)



主站API

https://api.bilibili.com/x/web-interface/online?&jsonp=jsonp

在线人数(网页在线、未知[play_online])

https://api.bilibili.com/x/web-show/res/locs?pf=0&ids=142%2C2837%2C2836%2C2870%2C2953%2C2954%2C2955%2C2956&jsonp=jsonp
