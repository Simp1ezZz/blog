---
title: 哔哔点啥
date: 2021-05-22 20:52:38
type: talks
aside: false
---

<div id='speak'></div>
<!-- 使用markdown渲染 -->
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/nanshen/js/blog/bb/ispeak-bber.min.js" charset="utf-8" ></script>
<!-- 不使用markdown渲染 -->
<!-- <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/ispeak-bber/ispeak-bber.min.js" charset="utf-8" ></script> -->
<!-- 解析微信表情（参考：https://github.com/buddys/qq-wechat-emotion-parser） -->
<!-- <script src="https://cdn.jsdelivr.net/gh/buddys/qq-wechat-emotion-parser@master/dist/qq-wechat-emotion-parser.min.js"></script> -->
<script>
ispeakBber
    .init({
      el: '#speak', // 容器选择器
      name: 'SimpleZzz', // 显示的昵称
      envId: 'env-4gbdlb5292de1c4b', // 环境id
      region: 'ap-shanghai', // 腾讯云地址，默认为上海
      limit: 10, // 每次加载的条数，默认为5
      avatar: 'https://gitee.com/SimpleZzz/pic/raw/master/img/04b7cc3274fff0b4f37b7e35ed91db6.jpg', // 头像地址
      fromColor:'rgb(245, 150, 170)', // 下方标签背景颜色 默认 rgb(245, 150, 170)
      loadingImg: 'https://7.dusays.com/2021/03/04/d2d5e983e2961.gif', // 自定义loading的图片，示例值为默认值
      dbName:'talks' // 数据的名称，默认talks，避免有人的命名不是这个，所以加入此配置字段。
    })
    .then(function() {
      // 哔哔加载完成后的回调函数，你可以写你自己的功能
      console.log('哔哔 加载完成')
    })
</script>