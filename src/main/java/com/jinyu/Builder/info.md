## 建造者模式
建造者模式将一个复杂的对象的构建与它的表示相分离，使得同样的构建过程可以创建不同的表示
都创建对象，类似于工厂模式，区别:
  工厂模式是自己完成对象构建（属性设置）并提供获取接口
  建造者模式是构建过程被从工厂里单独出来到director里实现，工厂只提供获取接口.而且director里可以提供各种不同的构建方法，这样同样的工厂方法可以获取到不同的product

