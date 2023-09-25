In Factory method deisgn pattern we have an abstract class or interface
which helps in creating an object but the subclasses which are 
extending or implementing the abstract class or interface decides
which class to be instantiated.




When to use Factory Design Pattern

When a class doesn’t know which sub-class should create the instance.    
When a class wants that its sub-classes should specify the objects to be created.  
When the parent classes choose the creation of objects to its sub-classes.  
when you want to offer your library’s users the ability to extend its internal components  




Real-world examples where Factory Method design pattern is used

This design pattern is commonly utilized in JDK.  
for example: getInstance() method of java.util.Calendar, NumberFormat, and ResourceBundle use factory method design pattern.