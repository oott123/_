# FF14 收藏夹[休闲自闭向]

【萌新入坑】[萌新招待](https://actff1.web.sdo.com/20190315Zhaodai/index.html#/index) 招待码 `019w-e5xe-rodk-7344` ・ [萌新手册](https://ff14.org)

【官网资讯】[新闻中心](http://ff.sdo.com/web8/index.html#/newstab/newslist) ・ [更新笔记](http://ff.sdo.com/web8/index.html#/patchnote) ・ [最新活动](https://urn.cx/ff14huodong)

【充值氪金】[点月卡充值](https://pay.sdo.com/item/GWPAY-100001900) ・ [点券充值](https://pay.sdo.com/item/GWPAY-0) ・ [商城](http://act.ff.sdo.com/20170918Shop/mall.html#/mall) ・ [转服](https://actff1.web.sdo.com/project/141028dgf/Index.asp) ・ [改名](http://ff14bjz.sdo.com/changeName) ・ [雇员](http://ff14bjz.sdo.com/buyEmployee)

【玩家回馈】[陆行鸟礼物站](https://ffpay.sdo.com/pc/giftsStation/index.html#/index) ・ [道具仓库](https://qu.sdo.com/personal-center?merchantId=1#itemindex-100001900-1) ・ [积分商城](https://actff1.web.sdo.com/20180707jifen/index.html#/exchange/exmall)

----

【玩家社区】[NGA](https://bbs.nga.cn/thread.php?fid=-362960) ・ [维基](https://ff14.huijiwiki.com/wiki/%E9%A6%96%E9%A1%B5) ・ [贴吧](https://tieba.baidu.com/ff14)

【图鉴收集】[坐骑](https://ff14.huijiwiki.com/wiki/%E5%9D%90%E9%AA%91%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F) ・ [宠物](https://ff14.huijiwiki.com/wiki/%E5%AE%A0%E7%89%A9) ・ [幻卡](https://ff14.huijiwiki.com/wiki/%E4%B9%9D%E5%AE%AB%E5%B9%BB%E5%8D%A1%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F) ・ [探索2.0](https://annangela.github.io/FFXIVSightseeingGuide/#/) ・ [探索4.0](https://bbs.nga.cn/read.php?tid=11861705)

----

【官网活动】<span id="huodong"></span>

<style>
#huodong span::after {
  content: ' ・ ';
}
#huodong span:last-of-type::after {
  content: '';
}
</style>

<script>
b = document.createElement('base');
b.target = '_blank';
document.head.appendChild(b);
function listhFun(data) {
  const els = data.Data.map(d => {
    const el = document.createElement('a')
    el.href = d.OutLink
    el.textContent = d.Title
    const w = document.createElement('span')
    w.appendChild(el)
    return w
  })
  const parent = document.body.querySelector('#huodong')
  for (const e of els) {
    parent.appendChild(e)
  }
}
</script>
<script defer src="https://ff.web.sdo.com/inc/newdata.ashx?url=List?gameCode=ff&category=7141&pageIndex=0&pageSize=5&callback=listhFun"></script>
