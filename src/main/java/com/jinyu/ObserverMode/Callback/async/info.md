回调：就是A类中调用B类中的某个方法C，然后B类中反过来调用A类中的方法D，D这个方法就叫回调方法

Class A实现接口CallBack callback——背景1
class A中包含一个class B的引用b ——背景2
class B有一个参数为callback的方法f(CallBack callback) ——背景3


A的对象a调用B的方法 f(CallBack callback) ——A类调用B类的某个方法 C
然后b就可以在f(CallBack callback)方法中调用A的方法 ——B类调用A类的某个方法D