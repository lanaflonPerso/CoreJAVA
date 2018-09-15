[home](https://www.javamadesoeasy.com/2015/05/exceptions-tutorial-in-java-in-detail_14.html)

Java Exception handling provides a mechanism to handle compile and runtime errors.
![](https://github.com/lekhrajdinkar/CoreJAVA/blob/master/notes/003_EXCEPTION/1.PNG)

[ **checked exceptions** ](https://www.javamadesoeasy.com/2015/11/what-are-checked-compile-time.html)
- checked exceptions are also known as compileTime exceptions.
- Checked exceptions are those which need to be taken care at compile time.
- Most common and frequently occurring checked (compile time)
1. IOException
2. FileNotFoundException
3. EOFException
4. SQLException
5. java.lang.InterruptedException
6. java.lang.ClassNotFoundException
7. InvalidClassException

[ **unchecked exceptions** ] (https://www.javamadesoeasy.com/2015/11/what-are-unchecked-runtimeexceptions-in.html)
- unchecked exceptions are also known as runtime exceptions.
- Unchecked exceptions are those which need to be taken care at runtime.
- The class RuntimeException and all its subclasses are unchecked exceptions.Likewise,The class Error and all its subclasses are unchecked exceptions.
- Example:
1. java.lang.NullPointerException
2. NumberFormatException
3. IndexOutOfBoundsException
4. java.lang.ArrayIndexOutOfBoundsException occurs in java
5. java.lang.StringIndexOutOfBoundsException occurs in java
6. java.lang.ArithmeticException in java - Divide number by zero
7. ArithmeticException in java
8. java.lang.IllegalStateException
9. java.lang.IllegalMonitorStateException
10. java.lang.UnsupportedOperationException
 

[ **java.lang.Error** ](https://www.javamadesoeasy.com/2015/05/javalangerror-in-exception-handling-in.html)
- Error is a subclass of Throwable 
- Error indicates some serious problems that our application should not try to catch. 
- Errors are abnormal conditions in application. 
- Error and its subclasses are regarded as unchecked exceptions 
- Example 
1. StackOverflowError 

[Checked vs Unchecked Exception](https://www.javamadesoeasy.com/2015/05/checked-compile-time-exceptions-and.html)
***
Table of Content
1. Exception definition in java 
2. checked, unchecked Exceptions and Error 
3. 5 keywords - try, catch, finally, throw and throws
4. User defined Exceptions
5. Exception propagation
6. Exception chaining /wrapping tutorial
7. Exception stack trace and debugging it in java tutorial 
8. best practices
9. differences 
* Differences between Exception and Error 
* Differences between throw and throws 
* Final, Finally and Finalize - difference and similarity
* Difference between multiple catch block and multi catch syntax
10. Java 7 : [Multiple Catch block](https://www.javamadesoeasy.com/2015/05/catch-block-and-automatic-resource.html)
11. [User defined Exceptions](User defined Exceptions)
12. Java 7 : [Automatch resource mgt](https://www.javamadesoeasy.com/2015/05/try-with-resources-in-java.html)

***
Key points:
1. throw keyword allows us to throw checked or unchecked exception.
2. unchecked exceptions are automatically propagated in java. no need to throw them using Throws keyword in method definition.
3. When catch and finally block both return value, method will ultimately return value returned by finally block irrespective of value returned by catch block. [more](https://www.javamadesoeasy.com/2015/05/what-will-happen-when-catch-and-finally.html)
4. 