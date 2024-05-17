# Collection in Java

The Collections Framework in Java offers a structured architecture for storing and manipulating groups of objects. This framework enables various operations such as searching, sorting, inserting, manipulating, and deleting data.

A Java Collection represents a single entity of objects. The Collections Framework includes multiple interfaces such as Set, List, Queue, and Deque, as well as numerous classes like ArrayList, Vector, LinkedList, PriorityQueue, HashSet, LinkedHashSet, and TreeSet.

## What is a Framework in Java?

A framework consists of a set of classes and interfaces that offer a pre-built architecture. When implementing a new feature or class, defining a framework is not necessary. Nevertheless, a well-designed object-oriented system typically incorporates a framework comprising a collection of classes that carry out similar tasks.

### Benefits of Using Collections
* Efficiency: Collections provide optimized implementations of data structures, which can improve performance for common operations like searching, sorting, and modifying data.
* Reusability: Using standard collections reduces code redundancy, making it easier to maintain and update code.
* Flexibility: Collections support various types of data structures and algorithms, making it easy to choose the right tool for the job.
* Interoperability: Collections work seamlessly with Java's core APIs, enhancing compatibility and ease of use.

### Real-Life Example
Consider a scenario where you have to sort the array and you want to do it multiple times in the code what do you do every time you code for the sort function or do you take code from the java lang package? Simple we will use a collection framework.

## Hierarchy of Collection Framework

Let's explore the hierarchy of the Collection framework. The java. util package includes all the classes and interfaces that make up the Collection framework.
![Alt Text](https://prepbytes-misc-images.s3.ap-south-1.amazonaws.com/assets/1682341909691-1-01%20%2878%29.png) 

### Interfaces that extend the Java Collections Interface
The collection framework contains multiple interfaces where every interface is used to store a specific type of data. The following are the interfaces present in the framework. 
* Iterable Interface
* Collection Interface
* List Interface

## Core Interfaces
1. Collection: The root interface for all collection classes.
2. List: An ordered collection that allows duplicate elements. Implementations include:
   - ArrayList
   - LinkedList
   - Vector
3. Set: A collection that does not allow duplicate elements. Common implementations are:
    - HashSet
    - LinkedHashSet
    - TreeSet
4. Queue: Designed for holding elements prior to processing, typically in FIFO order. Implementations include:
   - LinkedList
   - PriorityQueue
5. Map: An object that maps keys to values, with no duplicate keys allowed. Key implementations are:
   - HashMap
   - LinkedHashMap
   - TreeMap
  

### Implementations
Each core interface has multiple implementations to cater to different needs. For instance:

- ArrayList offers fast random access but slow insertion/removal from the middle.
- LinkedList excels at insertion/removal operations but provides slower random access.

### Conclusion
The Java Collections Framework enhances productivity by offering robust, reusable, and efficient data structures and algorithms, making it a fundamental part of Java development.

### References
- https://docs.oracle.com/javase/8/docs/technotes/guides/collections/overview.html
- https://www.geeksforgeeks.org/collections-in-java-2/
- https://www.javatpoint.com/collections-in-java


