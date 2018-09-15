## Im-mutable Class
1. [How to create immutable class](https://www.journaldev.com/129/how-to-create-immutable-class-in-java)
* Declare the **class as final** so it can’t be extended.
* Make all fields **private** so that direct access is not allowed.
* **Don’t provide setter** methods for variables
* Make all mutable fields **final** so that it’s value can be assigned only once.
* **Initialize** all the fields via a constructor performing deep copy.
* Perform **cloning** of objects in the getter methods to return a copy rather than returning the actual object reference.
* Example : https://www.javamadesoeasy.com/2015/05/creating-immutable-class-in-java.html

2. [Mutable vs Immutable]()

***
## STRING

1. String is Im-mutable in java. Reason:
* String pool helps in saving a lot of space for Java Runtime although it takes more time to create the String. hence less garbage collection.
* security threats

Like other prg lang java also concept of string interning - store only one copy of string. thats why java comes with [String pool](
https://www.journaldev.com/797/what-is-java-string-pool)
[String-Literal](https://www.javamadesoeasy.com/2015/05/string-pool-string-literal-pool-string.html)

- Use string literal to get string from pool.
- However using new operator, we force String class to create a new String object in heap space. 
- Example to understand
public class ImmutableString {
    public static void main(String[] args) {
           String str="ab";
           System.out.println(str.concat("cd")); //abcd
           System.out.println(str); //ab
    }
}

2. String Buffer

3. String Builder