[ ![Download](https://api.bintray.com/packages/7heaven/maven/iosswitch/images/download.svg) ](https://bintray.com/7heaven/maven/iosswitch/_latestVersion)

##IOS7 风格的Switch开关  
###IOS7 Style Switch Widget
*****



![art1](./arts/art1.gif)

![art3](./arts/art3.gif)

![art4](./arts/art4.gif)

![art5](./arts/art5.gif)



##添加到你的项目中
###add to your project
*****

在gradle脚本的dependencies中加入

add follow line to your dependencies in gradle script

```
compile 'com.7heaven.ioswidget:iosswitch:0.5'
```

##使用
###usage
*****

**通过setOn(boolean on)方法设置switch状态,setOn(boolean on, boolean animated)的animated参数决定是否以动画方式切换switch状态**

**using setOn(boolean on) method to set switch state,pass animated to setOn(boolean on, boolean animated) to switch state animated or not**

**通过isOn()获取switch状态**

**using isOn() method to get switch state**

**通过setOnSwitchStateChangeListener方法增加状态改变回调**

**using setOnSwitchStateChangeListener method to add a callback for switch state change



可在xml文件内通过tintColor标签改变颜色

change tint color using attribute show as follow

![art2](./arts/art2.png)

