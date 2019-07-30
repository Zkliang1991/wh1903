## wh1903 


## 微信小程序   


## author zuozuomu 


## 电商类小程序   每日购  


##  小组分工 选好组长 确定小程序 类型  3天开发完毕  4-5-6  

##  自由分组  人数最多4人    最少2人  





## 移动端适配   等比缩放  


## rem    100px 

## 媒体查询  @media  查询屏幕的大小 宽度和高度  


## 100% 布局  bootstrap 栅格系统  


## 弹性盒子布局  display:flex 

## px     rem(指的当前根节点HTML的字体大小font-size);   

## vw    1vw = 屏幕宽度的 1/100                 1 vh   = 1vw = 屏幕高度的 1/100 

## 假如 设计稿 屏幕宽度  750px  图片 ==>  200px  

## 假定当前 设计稿的 rem  = 100px;      width:2rem 

## 计算出 当前设备的 宽度 

## 100vw      document.documentElement.clientWidth 

##  设计稿width:设备width = 100px:x     x=>>  100*设备宽度 / 设计稿width  当前设备的rem   
##  当前设备的宽度 : X(当前设备的REM)  = 设计稿的宽度 : 设计稿假定的REM


## x  =  100*100vw/750  = 100vw/7.5

## x  =  100*100vw / 640 = 100vw/6.4


## x =   75*100vw / 750 = 10vw ;



## 微信小程序  新的 单位  rpx  等比缩放
## dpr 像素密度比 
## px = 1px 像素  绝对
## pt = ?   物理像素   相对   当前设备可以识别的最小的硬件单位 (像素单位) 分辨率越高 物理像素越小 

## rpx 只跟 750px 的设计稿有关  在750设计稿   
## iphone6 基准 375px = 750pt   1rpx = 0.5px 



## 320px:375px = x:0.5px x==> 0.42px;  
## 750px:375px = x:0.5px x==> 1px 

##  等比缩放

## iphone6  375px  dpr=2  750pt  750rpx   rpx ==> 走的物理像素  

1px = 2pt  = 2rpx  ==> 1rpx = 0.5px  

750px  : 375px = ? : rpx(0.5px)   ？ ===>   1px 
320px : 375px = ? :rpx(0.5)    ?===>  320*0.5/375 =  0.426px
414px : 375px = ? :rpx(0.5px)  ? ===> 414*0.5/375 = 0.552px 



