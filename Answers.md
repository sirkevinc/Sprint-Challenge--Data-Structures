## Questions

**1.** The order of insertions/removals for the following data structures is as follows:
- **Stack:** Last In First Out. New insertions are pushed to the end of the stack. Removals are taken off of the end of the stack.
- **Queue** First In First Out. New insertions are placed at the end of the queue. Removals are taken off of the front of the queue.

**2.** The retreival time compelxity for the following data structures are: 
- **Linked List:** O(N) - Linear time complexity 
- **Hash Table:** O(1) - Constant time complexity
- **Binary Search Tree:** O(logN) - Logarithmic time complexity

**3.** Some advantages of using Hash Tables over an array in JavaScript are that with Hash Tables, it takes a constant time to find the destination for a key and to place a value there. Retrieving a value is the same. The hash function helps ensure that for the same key, the same location of the bucket is returned.

Arrays are great if you know the index position of your item. However, that is typically not the case. In these situations, you must scan through every item in the array which takes a linear amount of time depending on how many items are in the array.