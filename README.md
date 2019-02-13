# WeekOneDailyTwo
Assignment



1.  List: Is an ordered Collections type interface. That allows users to access and insert elements by an integer index position. Lists allow duplicate elements. Two general purposes of List interfaces implementations are LinkedList and ArrayList. 


2.  ArrayList: ArrayList is a resizable class which implements interface. (Meaning it permits all elements including null.)


3.  Difference in List vs ArrayList: An ArrayList is a class.  While the List is an interface type.


4.  HashMap: Hashmap is a Java class. The implementation provides all the optional map operations. It permits null values and the null keys. The HashMap collections type is essentially unordered. There are two parameters that affect its performance: initial capacity and load factor. The capacity is the number of buckets in the hash table and the initial capacity is the capacity at the time the hash table is created. 


5.  HashTable: HashTable is a collection type that is non-ordered and is one of the two prehistoric Java collections type, the other being ArrayList. Hashtable is the sychronized counterpart to HashMap. Meaning the key methods of the class are synchronized. 


6.  Differences in HashMap and HashTable: Hashtable has synchronized methods while HashMap does not. Another big difference is that HashMap allows you to have both null keys and null values in the collection. Hashtable does not allow any null values or keys. 

7.  Set: A Set is an interface that does not allow any duplicates. Even if that value is a null value which it allows.


8.  HashSet: A HashSet is an unsorted and unordered sort collections class. It uses the hashcode of the object being inserted. The more efficient ones hashCode() implementation is the better access performance one will have. The main use of this class is to collect non-ordered data that does not allow duplicate values.


9.  CocurrentHashMap: ConcurrentHashMap is a Hash table supporting full concurrency of retrievals and high concurrency for updates. It is a class that obeys the same functional specification as Hashtable. It includes versions of methods corresponding to Hashtable. This class is fully interoperable with Hashtable in programs that rely on its thread safety but not on its synchronization details. 


10. What is hashCode and equals methods and how do the differ: Hashcodes are values that are typically used to increase the performance of large collections of data. The hashcode value of an object is mainly used by different collection classes. If you want to know if two objects themselves (not there references) are equal, you would use the equals() method. Both methods differ in regards to functionality. One compares two objects together and establishes if they are meaningfully equivalent to each other (equals()). The other method is a method from the Object class that returns the hashcode value for the object that it was called on. This method also comes with a general contract.
