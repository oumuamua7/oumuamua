# 自我介绍



我是*谭吉祥*，来自计算机学院信安2001.
我最喜欢的游戏是**Dont Starve**。

# 生命周期函数



+ Awake:当游戏对象被唤醒的时候执行，不管你身上的脚步组件是否禁用该函数都会执行

+ OnEnable:当组件或者游戏对象可用的时候执行
+ Start:当程序启动的时候执行，可应用与初始化
+ FixedUpdate:固定帧更新，默认每帧0.02秒
+ Update:每帧执行一次
+ LateUpdate:在Update每帧执行完之后执行，用于摄像机跟随
+ OnGUI:渲染或处理GUI界面时调用
+ OnDisable:当组件或者游戏对象禁用的时候执行
+ OnDestroy:当游戏对象销毁的时候执行
+ OnApplicationQuit:应用程序退出的时候执行，作用于应用程序退出的时候将消息发送给所有的游戏对象
+ OnApplicationFocus:当玩家获取或失去焦点的时候发送给所有游戏对象
+ OnBecameInvisible:当游戏对象不在摄像机照射的范围内执行
+ OnBecameVisible:当游戏对象在摄像机照射的范围内执行