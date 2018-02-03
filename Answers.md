1. What are the order of insertions/removals for the following data structures?
Stack
Stack data structures are last in, first out.  For both insertions and deletions, only the last item added to the stack can be accessed.  

Insertions: stack[stack.length]
Deletions: stack[stack.length - 1]

Queue
Queue data structures are first in, first out.  When you insert an object, it goes to the back of the queue.  When an object is deleted from a queue, the first item added will be the first deleted.

Insertions: queue[stack.length]
Deletions: queue[0]

2.  What is the retreival time complexity for the following data structures?
Linked List
A linked list is linear time complexity - O(n).  Since it can only see the next object on the list, one has to search object by object in order to find a value.  

Hash Table
A hash table is is also linear time complexity.  A hash table makes use of a hash function, but it is essentially an array.  If you have the key, hash tables have an O(1) lookup time. 

Binary Search Trees
A binary search tree is logarithmic time complexity - O(log (n)).  For each step in the search, the resulting search area is reduced by half.

3.  What are some advantages to using a Hash Tables over an array in JavaScript?
An array is linear time complexity and as is a hash table.  A hash table, however is more secure since it encodes the key/value pairs with a hash function.  There is not a direct connection from key to value without putting it through the hash function.  Hash tables can also be automatically resized, so the values don't become too deeply nested.  This keeps the lookup time smaller, even as the amount of data grows. 