# List
(ArrayList)[https://www.javamadesoeasy.com/2015/04/arraylist-in-java.html?m=1]

1. ArrayList is more like array with dynamic length.
2. ordered collection of objects - maintaines insertion order.
3. LinkedList is efficient for manipulation. LinkedList does not provide random access like Arraylist by index.
4. LinkedList takes more memory overhead, as it stores the object as well as the address of that object.
5. Custom Arraylist : https://www.javamadesoeasy.com/2015/02/arraylist-custom-implementation.html?m=1
6. getting unmodifiable list --> List<String> unmodifiableList = Collections.unmodifiableList(arrayList);

(linkedList)[https://www.javamadesoeasy.com/2015/04/linkedlist-in-java.html?m=1]

***

# Set:
1. implementations: HashSet, TreeSet, and LinkedHashSet. 
2. Set interface doesn’t allow random-access to an element in the Collection. You can use iterator or foreach loop to traverse the elements of a Set.
	
## HASHSET :
1. Java HashSet is the basic implementation the Set interface that is backed by a HashMap
2. permits the null element
3. We can set the initial capacity and load factor for this collection
(**load factor** is a measure of how full the hash map is allowed to get before its capacity is automatically increased)
	
## TREESET
1. A Navigable Set implementation.
2. The elements are ordered using their natural ordering, or by a Comparator provided at set creation time.


***

# key points:
1. Generic in java5 collection --> type-checking the Objects at compile-time.
2. UnsupportedOperationException.
3. String [] listtoArray = new String[list4.size()];list4.toArray(listtoArray) ;  **//list >  Array**
4. List<String> list5 = Arrays.asList(listtoArray); **// Array >  list**
5. CopyOnWriteArrayList, ConcurrentHashMap, CopyOnWriteArraySet. These classes are in java.util.concurrent package
6. Arrays are always of fixed. Arrays can only store homogeneous or similar type objects.

***
Handmade notes
![002_collection_1](https://github.com/lekhrajdinkar/CoreJAVA/blob/master/notes/002_COLLECTION/1.jpg)
![002_collection_2](https://github.com/lekhrajdinkar/CoreJAVA/blob/master/notes/002_COLLECTION/2.jpg)