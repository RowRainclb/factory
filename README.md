# factory
工厂模式



## 简单工厂
通过手动输入参数，来让工厂决定创建哪个实体类。  
违背了开闭原则

## 工厂方法
不再需要手动输入参数，创建不同的类，就调用对应的工厂，每个工厂都有相同的实现方法    
避免了违背开闭原则

## 抽象工厂
每个工厂都有创建实体店方法，只是有你选择由哪一个工厂来创建   
缺点是，如果需要增加一个实体的创建方法，则每个工厂都要增加一个方法，违背了开闭原则 


参考：uml图
https://www.processon.com/view/5c8252a2e4b02ce2e887388e
