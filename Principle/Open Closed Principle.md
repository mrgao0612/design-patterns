## 开闭原则定义
> * **开闭原则（Open Closed Principle,OCP）** 软件实体应当对外扩展开放，对修改关闭。（Software entities should be open for extension,but closed for modification.）
> * 软件实体包括以下几个部分：
1. 项目中划分出的模块
2. 类与接口
3. 方法
## 开闭原则的作用
> * 开闭原则是面向对象软件设计的终极目标。
1. 对软件测试的影响
软件遵守开闭原则的话，软件测试只需要对扩展的代码进行测试就可以了
2. 可以提高代码的可复用性
粒度越小，被复用的可能性就越大；在面向对象的程序设计中，根据原子和抽象编程可以提高代码的可复用性
3. 可以提高代码的可维护性
遵守开闭原则的软件其稳定性高，延续性强。从而易于扩展和维护。
## 开闭原则的实现方法
> * 可以通过***“抽象约束，封装变化”*** 来实现开闭原则，即通过接口或者抽象类为软件实体定义一个相对稳定的抽象层，而将相同的可变因素封装在相同的具体实现类中。
> * 因为抽象灵活性好，适应性广，只要抽象的合理，可以基本保持软件架构的稳定。而软件中易变的细节可以从抽象派生来的实现类来进行扩展，当软件需要发生变化时，只需要根据需求重新派生一个实现类来扩展就好了。
