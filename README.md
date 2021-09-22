# JAVA

Syntax of Creating an ArrayList:

// create Integer type arraylist

## ArrayList arrayList = new ArrayList<>() 
In the above program, we have used Integer not int. It is because we cannot use primitive types while creating an arraylist. Instead, we have to use the corresponding wrapper classes.

Basic syntax:

ArrayListName.size() : use this to get the size of arraylist.

ArrayListName.add(x) : Use this to append an element x to the ArrayList.

ArrayListName.get(i) : use this to access the ith index element in the ArrayList. Remember ArrayList uses 0 based indexing.

# Syntax to create an Stack:

// Create Integer type stack
Stack < Integer > myStack = new Stack<>();
The above code create an stack named myStack which can store integers.

Some more functions which we can use with stack:

 

 

 

 

myStack.push(x) : Use push() to push an element into the stack.

myStack.pop() : To remove an element from the top of the stack, we use the pop() method.

myStack.peek() : The peek() method returns an object from the top of the stack.

myStack.empty() : To check whether a stack is empty or not, we use the empty() method.


# Queue
The Queue interface of the Java collections framework provides the functionality of the queue data structure. It extends the Collection interface.

Classes that Implement Queue:

Since the Queue is an interface, we cannot provide the direct implementation of it. In order to use the functionalities of Queue, we need to use classes that implement it:

ArrayDeque

LinkedList

PriorityQueue
In queues, elements are stored and accessed in First In, First Out manner. That is, elements are added from the behind and removed from the front.

In Java, we must import java.util.Queue package in order to use Queue.

Syntax:

 Queue<String> names= new ArrayDeque<>();
The above statement creates a Queue of Strings, we can now push and remove Strings from this queue easily.

Methods of Queue:

add() - Inserts the specified element into the queue. If the task is successful, add() returns true, if not it throws an exception.
 
offer() - Inserts the specified element into the queue. If the task is successful, offer() returns true, if not it returns false.
 
element() - Returns the head of the queue. Throws an exception if the queue is empty.
 
peek() - Returns the head of the queue. Returns null if the queue is empty.
 
remove() - Returns and removes the head of the queue. Throws an exception if the queue is empty.
 
poll() - Returns and removes the head of the queue. Returns null if the queue is empty.
 
size() - Return an integer denoting the total number of elements in the queue at present.
