# Rxjava

### Rxjava 实现的小demo 参考被人的demo
...  RxJava 是一个 基于事件流、实现异步操作的库
Rxjava 的四个角色

角色	                作用
被观察者（Observable）	产生事件
观察者（Observer）	    接收事件，并给出响应动作
订阅（Subscribe）	    连接 被观察者 & 观察者
事件（Event）	        被观察者 & 观察者 沟通的载体

Rxjava 2.x更新之后出现了两种观察者模式：
Observable ( 被观察者 ) ---subcribe(订阅)--- Observer ( 观察者 )--不支持背压
Flowable （被观察者）---subcribe(订阅)--- Subscriber （观察者） --支持背压

使用方法:
** 第一步：初始化 Observable **
** 第二步：初始化 Observer **
** 第三步：建立订阅关系 **



