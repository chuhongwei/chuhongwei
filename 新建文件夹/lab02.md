<center><font color="#00dddd" size="6">用Construct 2制作2D射击小游戏的指南(1)</font><br /> </center> 


---  
预期效果
![]()
---
准备工作 ：安装Construct 2。  [点击此处下载](https://www.scirra.com/construct2)
  
    
## 1.新建一个布局。  
![](https://wx2.sinaimg.cn/mw690/007mB6ally1fvybqbtthsj30jg0gdmyj.jpg)   


![](https://wx1.sinaimg.cn/mw1024/007mB6ally1fvybqbt9dej30k00k1my9.jpg)    

  
***点击白色区域，在左侧调节布局的大小***  

![](https://wx2.sinaimg.cn/mw1024/007mB6ally1fvybqbt2mgj30dc0g8dgz.jpg)    
  

## 2.为你的游戏设置背景。  
(1)双击空白区域，跳出页面,选择背景  
![](https://wx1.sinaimg.cn/mw690/007mB6ally1fvyc5snnmsj30od0krab3.jpg)
(2)在空白布局中点击鼠标，在弹出页面中选择文件夹图标。  
![](https://wx3.sinaimg.cn/mw690/007mB6ally1fvyc5so08pj30kv0foq3p.jpg)
(3)打开你选择的背景  
![](https://wx2.sinaimg.cn/mw690/007mB6ally1fvyc5t0iihj30q40jqdli.jpg)  
(4)调整背景使其覆盖布局  
![](https://wx4.sinaimg.cn/mw690/007mB6ally1fvyc5totjyj314y0lcay5.jpg)  
  
    
## 3.添加图层。  
在右上方切换到Layers,并修改背景图层名并上锁，在新建一个main图层。  
  
gif动画演示  
![](http://wx1.sinaimg.cn/large/007mB6ally1fvychhp75gg30c20blacg.gif)  
  
## 4.添加游戏对象。  
(1)双击背景插入Mouse,Keyboard,player,monster,bullet,explosion.等对象。并在左侧修改后面四个对象的名字。  
~双击空白——>选择Mouse,Keyboard插入  
~双击空白——>选择Sprite—>选择要插入的四个对象，并在左侧重命名
(2)为对象设置行为。  
选中所设置对象，在左侧选中Behaviors,在弹窗中点加号添加行为。  
player~~~~:  8 Directions   +   scroll To  +  Bound to layout     
  
![](http://wx2.sinaimg.cn/large/007mB6ally1fvyda3qmyeg30tn0ak7oo.gif)

monster~~~: bullet    

explosion~: fade      

bullet~~~~: bullet   +  destroy  outside layout    
  
(3)改变对象的一些动作设定     
为了游戏体验，我们需要增加子弹射速，怪物移速，以及爆炸火花时间。          
gif演示
![](http://wx1.sinaimg.cn/large/007mB6ally1fvydh2okmtg30m50d6jvz.gif)  
  
    
<font color="#00dddd" size="6">第一部分结束，看一下自己的演示效果如何吧！</font><br />