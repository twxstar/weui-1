#weui+移动开发组件
---
#### 最新版本3.0    基于weui官方0.44开发

#### 简介  
weui+ 是在weui基础上开发而来,采用了和原来框架分离,所以不影响升级weui的css.组件中采用了js分离,按需要加载相应的文件,一般只需要加载zepto.min.js就包含基础功能,php.js是常用自定义函数
<pre>
lrz.min.js 图片上传前压缩
picker.js  包含picker相关的选择 地址 时间 
qrcode.js  二维码生成
updown.js  下拉与上拉
sound.js     音乐播放
zepto.js     包含example,picker,zepto.min 
zepto.min.js  基础库+扩展
example.js    包含
swipe.js swipe库
swiper,tab,search,select,popup样式
video.js 音视频播放
iscroll.js 滚动,只在横向导航用到
weui.css  微信官方css,未压缩
weui.min.css 压缩
weui2.css   未压缩扩展包
weui2.min.css  压缩
weuix.min.css  压缩的weui和weui2合并
php.js 包含分离出来的自定义函数
</pre>

####  已使用公众号或移动网站
- 公众号: 勉县小江南
![](http://weixin.yoby123.cn/attachment/headimg_1.jpg?time=1463681994)
- 待增加

#### [更新日志](http://weixin.yoby123.cn/weui/c/r.html)
- 2016-10-1 V3.0 修复提示和底部导航同时用不能点击bug.九宫格演示显示不正确,新增红色数字徽标,分离常用函数为php.js,本函数不使用任何库,名称采用php同函数名.
- 2016-9-4 V2.9  新增手风琴,支持独立和组合调用 
- 2016-7-26 v2.8  升级weui为0.43,微信weui官方修复了已知bug.
- 2016-6-18 v2.7  新增15个新图标,上传图片新增提示删除,修复已知bug.
- 2016-6-6 v2.6   替换swipe为更小函数,新版的支持是否自动播放,这个更好用,重写此css,是否使用标题,超链接自己根据例子修改 
- 2016-6-5  v2.5  新增认证头像,新增tab切换红色和绿色导航条,loading动画,旋转180度和360度,新增上拉加载更多下拉刷新,新增图片懒加载只需要载入zepto即可使用   
- 2016-6-3  v2.4  新增音视频播放器,新增横向可滚动导航,新增iscroll移动版库,新增9种常见颜色值;修复已知问题.   
- 2016-4-1 V1.0 weui是很棒的微信端UI,但是组件太少了,在微信开发很多组建都没有,所以根据此问题,收集网络上优秀的代码片段,组合开发出了这一套增强版weui-plus,目前还在不断增多组件,修复bug,目标是做最好的微信端移动端UI.

#### 已知bug列表和修复  
1. 部分华为荣耀V4反映不能上传图片,目前没找到原因,可以使用微信jssdk上传来代替.
2. swiper滚动,手动滑动后不能自动滚动,目前已修复. 

#### 演示连接  
- 最新国内演示地址   <http://weixin.yoby123.cn/weui/>
![](http://7xr193.com1.z0.glb.clouddn.com/weui.png?time=1463681994)
- github演示地址 [http://logoove.github.io/weui2](http://logoove.github.io/weui2)

#### 赞助我 支付宝和微信支付
![](http://7xr193.com1.z0.glb.clouddn.com/weixin-v.jpg?time=1463681994)  ![](http://7xr193.com1.z0.glb.clouddn.com/zhi-v.jpg?time=1463681994)

#### 友情感谢(不完全列出,谢谢你们的付出)
- weui <https://github.com/weui/weui>
- Vux<https://github.com/airyland/vux>
- jquery-weui<https://github.com/lihongxun945/jquery-weui>
- 腾讯手机Q frozen<https://github.com/frozenui/frozenui>
- 淘宝SUI<https://github.com/sdc-alibaba/SUI-Mobile>
- swipe <https://github.com/thebird/Swipe>
- 图片压缩localResizeIMG <https://github.com/think2011/localResizeIMG>
- jquery-qrcode <https://github.com/jeromeetienne/jquery-qrcode>
- zepto <https://github.com/madrobby/zepto>
