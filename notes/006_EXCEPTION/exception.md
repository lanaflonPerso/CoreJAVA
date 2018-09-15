[home](https://www.javamadesoeasy.com/2015/05/exceptions-tutorial-in-java-in-detail_14.html)

Java Exception handling provides a mechanism to handle compile and runtime errors.
![](https://github.com/lekhrajdinkar/CoreJAVA/blob/master/notes/003_EXCEPTION/1.PNG)

[ **checked exceptions** ](https://www.javamadesoeasy.com/2015/11/what-are-checked-compile-time.html)
- checked exceptions are also known as compileTime exceptions.
- Checked exceptions are those which need to be taken care at compile time.
- Most common and frequently occurring checked (compile time)
1. IOException [more]()
2. FileNotFoundException[more]()
3. EOFException [more](https://www.javamadesoeasy.com/2016/08/why-eofexception-occurs-and-how-to.html)
4. SQLException [more](https://www.javamadesoeasy.com/2015/05/sqlexception-in-java.html)
5. java.lang.InterruptedException [more]()
6. java.lang.ClassNotFoundException [more](https://www.javamadesoeasy.com/2015/12/when-javalangclassnotfoundexception.html)
7. InvalidClassException [more](https://www.javamadesoeasy.com/2016/10/solve-invalidclassexception-in-java.html)

[ **unchecked exceptions** ](https://www.javamadesoeasy.com/2015/11/what-are-unchecked-runtimeexceptions-in.html)
- unchecked exceptions are also known as runtime exceptions.
- Unchecked exceptions are those which need to be taken care at runtime.
- The class RuntimeException and all its subclasses are unchecked exceptions.Likewise,The class Error and all its subclasses are unchecked exceptions.
- Example:
1. java.lang.NullPointerException [more](https://www.javamadesoeasy.com/2016/01/what-is-javalangnullpointerexception-in.html)
2. NumberFormatException [more]()
3. IndexOutOfBoundsException [more]()
4. java.lang.ArrayIndexOutOfBoundsException occurs in java [more]()
5. java.lang.StringIndexOutOfBoundsException occurs in java [more]()
6. java.lang.ArithmeticException in java - Divide number by zero [more]()
7. ArithmeticException in java [more]()
8. java.lang.IllegalStateException [more](https://www.javamadesoeasy.com/2015/12/when-javalangillegalstateexception.html)
9. java.lang.IllegalMonitorStateException [more](https://www.javamadesoeasy.com/2015/12/when-javalangillegalmonitorstateexcepti.html)
10. java.lang.UnsupportedOperationException [more](https://www.javamadesoeasy.com/2015/12/solve-javalangunsupportedoperationexcep.html)
 

[ **java.lang.Error** ](https://www.javamadesoeasy.com/2015/05/javalangerror-in-exception-handling-in.html)
- Error is a subclass of Throwable 
- Error indicates some serious problems that our application should not try to catch. 
- Errors are abnormal conditions in application. 
- Error and its subclasses are regarded as unchecked exceptions 
- Example 
1. StackOverflowError [more]()
2. OutOfMemoryError in java [more]()
3. Java.lang.NoClassDefFoundError [more](https://www.javamadesoeasy.com/2015/12/how-to-solve-javalangnoclassdeffounderr.html) 
4. java.lang.ExceptionInInitializerError [more]()

[Checked vs Unchecked Exception](https://www.javamadesoeasy.com/2015/05/checked-compile-time-exceptions-and.html)
ClassNotFoundException vs NoClassDefFoundError:
[JavaRevisted](https://javarevisited.blogspot.com/2011/07/classnotfoundexception-vs.html)
[dzone](https://dzone.com/articles/java-classnotfoundexception-vs-noclassdeffounderro)
[JMSE](https://www.javamadesoeasy.com/2015/05/checked-compile-time-exceptions-and.html)

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
11. simple example of [User defined Exceptions](https://www.javamadesoeasy.com/2015/05/creating-user-defined-checked-and.html)
12. Java 7 : [Automatch resource mgt](https://www.javamadesoeasy.com/2015/05/try-with-resources-in-java.html)
13. Exception chaining /wrapping
14. [Method Overoading with Exception](https://www.javamadesoeasy.com/2015/05/method-overloading-on-basis-of.html)

***
Key points:
1. throw keyword allows us to throw checked or unchecked exception.
2. unchecked exceptions are automatically propagated in java. no need to throw them using Throws keyword in method definition.
3. When catch and finally block both return value, method will ultimately return value returned by finally block irrespective of value returned by catch block. [more](https://www.javamadesoeasy.com/2015/05/what-will-happen-when-catch-and-finally.html)
4. Avoid null pointer - null check using if-else, instanceOf, ternary operator or "abc".equals(null)