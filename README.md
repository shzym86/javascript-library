
## Javascript常用封装函数

> 汇总了一些可能比较常用的JS封装函数，用于快速实现一些简单的页面功能。封装的函数在jQuery的基础上实现。


#### 功能索引：


```
	
1. Countdown(obj,classname,num)
  - 倒计时  1.点击的对象  2.类  3.数值
	
2. autotop(obj,ops,valt)
  - 垂直翻滚 1.li集合  2.距离  3.个数
	
3. click_cgimg(obj,index,imgname)
  - 切换图片  1.对象  2.索引值  3.图片名称
	
4. click_addname(obj,className,allt)
  - 给对象添加类  1.点击的对象  2.类名  3.是否清除所有-非零[可选]
	
5. slideshow(click_show,obj_open,class_name)
  - 三级菜单展开  1.点击的对象  2.展开的对象  3.添加类名旋转图标
	
6. suspension(click_obj,move_obj,distance,className)
  - 悬浮  1.点击的对象  2.移动的对象  3.距离右边的数值 4.类名
	
7. full_screen(number,click_left,click_right,click_cirl)
  - 全屏左右滚动轮播 1.数量  2.左点击  2.右点击  3.小圆点点击
	
8. autobox(obj,oble,value,pase)
  - 居中 1.对象  2. 0-[左边] 1-[右边]  3.宽度  4.偏移量
	
9. Cutimg(obj)
  - 裁图后 垂直水平居中  1.图片对象
	
10. eject(hover_obj,hide_obj)
  - 弹出菜单  1.移上去的对象  2.隐藏的对象
	
11. replaimg(obj)
  - HOVER变颜色的图标 1.移上去的对象
	
12. scrollTop(obj_fixed,ClassName,value)
  - 当元素滚动到一定时就固定定位  1.定位的对象  2.加入一个类  3.默认值不可更改
	
13. tabs_cg(Oobj,Otabch,event,ClassName,Find,level){
  - 选项卡切换  1.点击的对象  2.切换的的对象  3.事件   4.类名  5.查找下一级   6.如果Find实参存在,缺少值是为 1
	
14. two_scroll(number,cli_left,cli_right,click_cirl,textp,ovalue,ots){
  - 滚动轮播 1.元素的个数	2.左点击对象	3.右点击对象	4.小圆点对击对象[可选项] 5.文字变化 6.滚动的距离[必选项] 7.滚动的个数[必选项] 8.最外层高度
	
15. down_drop(a,b,c)
  - 下拉列表	1.点击获取文本内容  2.点击对像显示下拉  3.下拉这个Div对像
	
16. fade(banner,cirl,timer,click_left,click_right)
  - 淡入淡出轮播  1.切换的对像	2.小圆点控制的对像	 3.时间值[必选]  4.左点击  5.右点击 6.文字部分切换
	
17. cli_cgimg(obj)
  - 点击图标状态切换  1.点击的对象
	
18. checkbox(obj,findbel){
  - 复选框
	
19. cli_cgpic(obj) 
  - 按下图标切换
	
20. getFileUrl(sourceId) {
  - 获取File上传图片
	
21. seamless(obj,next,prev,title){
  - 无缝滚动轮播
	
22. myScroll()
  - 返回顶部
	
23. newRoll
  - 新闻滚动
	
24. copy
  - 复制textarea里面的内容
	
25. alertbox
  - 弹窗js
	
26. upimg
  - 加载结构

27. numadd
  - 数量加减
	
28. shoutext
  - 点击展开text
	
29. slide_nav(obj,class_name,iname)
  - slide展开
	
30. CountDown(element,divtype)
  - 活动倒计时
	
31. enlarge(click_,cg_obj)
  - 小图换成大图
	
32. dropmove(down,move,direction,obj_hei)
  - 拖动进度条
	
32. auto_subMenu(obj,find_obj)
  - 子菜单自适应大小
	
33. radio_pic(obj)
  - 单选
	
34. zoom()
  - 整体缩小
	
35. input_bd	
  - 焦点获取
	
36. roll_picture(oLi)
  - 图片列表向左滚动
	
37. levelwith(obj_fr,obj_fl)
  - 左右等高
	
38. hover_down_menu(oli_obj,showDiv)
  - 下拉菜单效果
	
39. typing(textp)
  - 打字效果
	
40. paint_cirl(obj_default_class,obj_change_class,start_color,end_color,main_class)
  - 画圆

```
> 注：不同的函数之间可能存在依赖关系！