[Oops](https://www.javamadesoeasy.com/2015/06/4-oops-object-oriented-programming.html?m=1)

## 1.polymorphism
### 1.1. Runtime polymorphism
Runtime polymorphism can be achieved by using Method overriding 
Method of superclass is overridden in subclass to provide more specific implementation.

**Rules:**

**Access modifier** - Overriding method must not have more restrictive access modifier in java.

**Return type** - Java allow method overriding by changing the return type, but only Covariant return type are allowed. (see Program 4)

**Number of parameters** - Overriding method must have same number of parameters in java.

**Exception thrown** -
Overriding method must not throw new or broader checked exception in java,
though Overriding method may throw new narrower(subclass) of checked exception or
Overriding method can throw any runtime exception in java.

### 1.2 Complile time : method overloading

***
## Others
1. [Difference between Abstract class and interface](https://www.javamadesoeasy.com/2015/06/10-differences-between-interface-and.html?m=1)