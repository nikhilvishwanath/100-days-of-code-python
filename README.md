# 100-days-of-code-python
Improving python coding skills in 100 days. Most of us are coding in python but know only necessary things. This is my attempt to expand the horizons. 

# Day 1: datetimes
https://github.com/talkpython/100daysofcode-with-python-course/tree/master/days/01-03-datetimes

# Day 2 & 3: Collections 
(https://docs.python.org/2/library/collections.html)
Some powerful datastructures to make your code less buggy and simple.
 1. namedtuple: Named tuples assign meaning to each position in a tuple and allow for more readable, self-documenting code. They can be used wherever regular tuples are used, and they add the ability to access fields by name instead of position index.
 2. defaultdict: Returns a new dictionary-like object. defaultdict is a subclass of the built-in dict class. It overrides one method and adds one writable instance variable. The remaining functionality is the same as for the dict class and is not documented here.
 3. Counter: A Counter is a dict subclass for counting hashable objects. It is an unordered collection where elements are stored as dictionary keys and their counts are stored as dictionary values. Counts are allowed to be any integer value including zero or negative counts. The Counter class is similar to bags or multisets in other languages.
 4. deque: Deques are a generalization of stacks and queues (the name is pronounced “deck” and is short for “double-ended queue”). Deques support thread-safe, memory efficient appends and pops from either side of the deque with approximately the same O(1) performance in either direction.
 
# Day 4: Data structures (Classes and objects)
https://www.geeksforgeeks.org/python-classes-and-objects/

https://sahandsaba.com/python-classes-metaclasses.html (python 2)

jupyter notebook consist of basic, advanced class methods and metaclasses.

# Day 5: Iterators, Generators, itertools
https://www.geeksforgeeks.org/iterators-in-python/

# Day 6: Writing Binary Search Tree using python classes
With tree we are introducing new data structure. Each instance (point) in this newly created data structure consist of three things.
1. value at that node
2. left child. 
3. right child.

Children are again points of our newly defined datastructure. so each children will have its own value and two children.
Lets call this point a node in the tree. As per the three required things node will look like this in python.
```
class Node(object):
    def __init__(self, key = None):
        self.key = key
        self.left = None
        self.right = None 
```

# Day 7: BST operations (insertion and printing)
Introduction to Algorithms 3rd ed. page 294.

https://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/

# Day 8: Balancing the BST
https://www.geeksforgeeks.org/self-balancing-binary-search-trees-comparisons/
We will introduce new property to the class, height. Based on the difference in the heights of left and right nodes we can determine whether the tree balanced or not. We will balance the trees using right rotation and left rotation 

# Day 9: Printing (advanced)
printing and formatting in python is covered in this tutorial. There are many things in print function which are unknown to most of the people. I have compiled them with example in this notebook. 

# Day 10: Generators

# Day 11: Decorators

# Day 12: 

# Day 13:

# Day 14: 

# day 15:

# Day 16:

