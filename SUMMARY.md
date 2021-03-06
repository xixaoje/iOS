# Summary

* [Introduction](README.md)
* [c](c.md)
* [学习资源](资源地质.md)
* [单词积累](单词积累.md)
* [犯错总结](自己犯过的错误.md)
* [Xcode配置](xcode配置.md)
* [xcode调试技巧](xcode调试技巧.md)
* [OC与 Xcode](oc.md)
  * [继承](继承.md)
  * [运算符](运算符.md)
  * [initialize和load方法](多控制器管理第一天.md)
  * [info.plist文件](infoplist文件.md)
  * [pch文件](pch文件.md)
  * [\#if、\#ifdef、\#if define区别](if、ifdef、if-define区别.md)
  * [自动提示宏](自动提示宏.md)
  * [xcode5 和6的区别](xcode5-和6的区别.md)
  * [日历类](日历类.md)
  * [位移枚举](位移枚举.md)
  * [NSString](nsstring.md)
    * [地址路径](地址路径.md)
  * [分类](分类.md)
    * [字典数组打印中文分类](字典数组打印中文分类.md)
  * [给插件添加功能](给插件添加功能.md)
  * [block](block.md)
* [runtime](run-time.md)
  * [runtime消息机制](runtime消息机制.md)
  * [runtime交换方法](runtime交换方法.md)
  * [runtime动态添加方法](动态添加方法.md)
  * [runtime动态添加属性](动态添加属性.md)
  * [runtime字典转模型](runtime字典转模型.md)
    * [自动生成属性代码](自动生成属性代码.md)
    * [KVC内部实现原理](kvc内部实现原理.md)
* [基础UI](chapter1.md)
  * [UIApplication](uiapplication.md)
    * [可以干什么](管理状态栏.md)
    * [UIApplicationDelegate](uiapplicationdelegate.md)
    * [UIApplicationMain](uiapplicationmain.md)
  * [UIView的事件传递与循环](uiview的事件传递.md)
    * [UIRespond](uirespond.md)
    * [UITouch](uitouch.md)
    * [UIEvent](uievent.md)
    * [手势](手势.md)
  * [UIView+StoryBoard](第一天.md)
    * [frame和size](frame和size.md)
    * [项目中常见的文件\(LaunchScreen\) LaunchScreen](项目中常见的文件launchscreen-launchscreen.md)
  * [UILabel](uilabel.md)
  * [UIImageView](uiimageview.md)
    * [动画](动画.md)
  * [UIButton](uibutton.md)
    * [解决与手势的冲突](解决与手势的冲突.md)
  * [UITableView](uitableview.md)
    * [cell](cell.md)
      * [等高的](等高的.md)
      * [不等高的](不等高的.md)
        * [1.1 纯代码](纯代码.md)
          * [frame](frame.md)
          * [layoutSubviews](layoutsubviews.md)
        * [1.2 storyboard、xib](storyboard.md)
        * [自定义Cell的优化](自定义cell的优化.md)
  * [屏幕方向](device.md)
* [UI提高](ui提高.md)
  * [NSAttributedString描述](at.md)
  * [多控制器管理](多控制器管理.md)
    * [UIWindow](uiwindow.md)
    * [UIScreen](uiscreen.md)
    * [UIViewController](uiviewcontroller.md)
    * [代码创建控件](代码创建控件.md)
    * [xib](xib.md)
    * [UIStoryBoard](uistoryboard.md)
    * [抽屉效果使用](抽屉效果使用.md)
    * [父子控制器](父子控制器.md)
    * [导航控制器](导航控制器.md)
    * [UITabBarController](uitabbarcontroller.md)
  * [渐变动画](渐变动画.md)
    * [transform](transform.md)
  * [Quartz2D](quartz2d.md)
    * [Layer Graphics Context\(图层上下文\)](layer-graphics-context.md)
      * [基本线条的绘制](基本线条的会址.md)
      * [画饼图](画饼图.md)
      * [下载进度条](下载进度条.md)
      * [模仿系统的UIImageView的实现](模仿系统的uiimageview的实现.md)
      * [定时器雪花效果](定时器雪花效果.md)
      * [图形上下文栈\(熟悉\)](10-图形上下文栈熟悉.md)
      * [图片上下文的矩阵操作\(形变位移之类\)](图片上下文的矩阵操作.md)
      * [手势解锁](手势解锁.md)
    * [Bitmap Graphics Context\(位图上下文\)](bitmap-graphics-context位图上下文.md)
      * [带有边框的圆形图片裁剪](带有边框的圆形图片裁剪.md)
      * [截屏](截屏.md)
      * [擦除](擦除.md)
    * [UIKit绘图演练](uikit绘图演练.md)
    * [核心动画](核心动画.md)
      * [01-CALayer](calayer.md)
        * [02-CATransform3D](catransform3d.md)
        * [03-position和anchorPoint](03-position和anchorpoint.md)
        * [04-隐式动画自定义层才有](04-隐式动画.md)
        * [05-时钟旋转](时钟旋转.md)
        * [06-渐变层CAGradientLayer](cagradientlayer.md)
        * [07-复制层CAReplicatorLayer](07-careplicator.md)
        * [08-形状层CAShapeLayer](08-cashapelayer.md)
      * [02-CAAnimation](02caanimation.md)
        * [01-CABasicAnimation](cabasicanimation.md)
        * [02-帧动画CAKeyframeAnimation](02-cakeyframeanimation.md)
        * [03-转场动画CATransition](catransition.md)
        * [04-CAAnimationGroup](04-caanimationgroup.md)
        * [核心动画代理](核心动画代理.md)
  * [自定义过度效果和类型](aaaaaa.md)
* [UI补充](ui补充.md)
  * [Stack View](stack-view.md)
* [源代码管理和终端命令](源代码管理.md)
  * [GIT源代码管理](git源代码管理.md)
  * [SVN源代码管理](svn源代码管理.md)
  * [Cocoapods](cocoapods.md)
* [Json序列化](json序列化.md)
* [Swift](swift入门.md)
  * [0.1.常量&变量](常量变量.md)
  * [0.2.逻辑分支](02逻辑分支.md)
  * [0.3.循环](03循环.md)
  * [0.4.数组](04数组.md)
  * [0.5.字典](05字典.md)
  * [0.6.字符串](06字符串.md)
  * [0.7.函数](07函数.md)
  * [0.8.闭包](08闭包.md)
  * [0.9.懒加载](09.md)
  * [0.10.getter&setter](010gettersetter.md)
  * [0.11.ATS](011ats.md)
* [runtime](run-time.md)
  * [runtime消息机制](runtime消息机制.md)
  * [runtime交换方法](runtime交换方法.md)
  * [runtime动态添加方法](动态添加方法.md)
  * [runtime动态添加属性](动态添加属性.md)
  * [runtime字典转模型](runtime字典转模型.md)
    * [自动生成属性代码](自动生成属性代码.md)
    * [KVC内部实现原理](kvc内部实现原理.md)
* [xcode调试技巧](xcode调试技巧.md)
* [Xcode配置](xcode配置.md)
* [C语言](c.md)
* [more](more.md)
* [iOSThread](thread.md)
  * [GCD](网络.md)
  * [NSOperation｜单例模式](网络/more2.md)
  * [Runloop](more.md)
* [three](three.md)
  * [SDWebImage](three/sdwebimage.md)
* [iOSNetData](iosnetdata.md)
  * [Data](iosnetdata/data.md)
* [swift 新特性](swift-xin-te-xing.md)
* [Swift4](swift4.md)

