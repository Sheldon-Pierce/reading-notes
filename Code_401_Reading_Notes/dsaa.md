# Data Structures and Algoirithms

1. One of the more important things to consider when deicding on what is best suited to solve a particular problem, you need to consider what are the operations we are going to perform and how often they are going to be executed. Since each data structure is essentially based on this information , determining that from the start will be a good step in the right direction when solving problems.

2. Infinite recursion is avoided by ensuring that progress is made toward the base case or cases in every recursive call.

## Basic Data Structures

1. Arrays

    An array is a structure of fixed-size, which can hold items of the same data type. It can be an array of integers, an array of floating-point numbers, an array of strings or even an array of arrays (such as 2-dimensional arrays). Arrays are indexed, meaning that random access is possible.

### Array operations

    - Traverse: Go through the elements and print them.
    - Search: Search for an element in the array. You can search the element by its value or its index
    - Update: Update the value of an existing element at a given index

2. Linked Lists

    A linked list is a sequential structure that consists of a sequence of items in linear order which are linked to each other. Hence, you have to access data sequentially and random access is not possible. Linked lists provide a simple and flexible representation of dynamic sets.

### Linked list operations

    - Search: Find the first element with the key k in the given linked list by a simple linear search and returns a pointer to this element
    - Insert: Insert a key to the linked list. An insertion can be done in 3 different ways; insert at the beginning of the list, insert at the end of the list and insert in the middle of the list.
    - Delete: Removes an element x from a given linked list. You cannot delete a node by a single step. A deletion can be done in 3 different ways; delete from the beginning of the list, delete from the end of the list and delete from the middle of the list.

3. Stacks

    A stack is a LIFO (Last In First Out — the element placed at last can be accessed at first) structure which can be commonly found in many programming languages. This structure is named as “stack” because it resembles a real-world stack — a stack of plates.

### Applications of stacks

    - Used for expression evaluation (e.g.: shunting-yard algorithm for parsing and evaluating mathematical expressions).
    - Used to implement function calls in recursion programming.

4. Queues

    A queue is a FIFO (First In First Out — the element placed at first can be accessed at first) structure which can be commonly found in many programming languages. This structure is named as “queue” because it resembles a real-world queue — people waiting in a queue.

### Applications of queues

    - Used to manage threads in multithreading.
    - Used to implement queuing systems (e.g.: priority queues).

5. Hash Tables

    A Hash Table is a data structure that stores values which have keys associated with each of them. Furthermore, it supports lookup efficiently if we know the key associated with the value. Hence it is very efficient in inserting and searching, irrespective of the size of the data.

### Applications of hash tables

    - Used to implement database indexes.
    - Used to implement associative arrays.
    - Used to implement the “set” data structure.

6. Trees

    A tree is a hierarchical structure where data is organized hierarchically and are linked together. This structure is different from a linked list whereas, in a linked list, items are linked in a linear order.

    Various types of trees have been developed throughout the past decades, in order to suit certain applications and meet certain constraints. Some examples are binary search tree, B tree, treap, red-black tree, splay tree, AVL tree and n-ary tree.

### Applications of trees

    - Binary Trees: Used to implement expression parsers and expression solvers.
    - Binary Search Tree: used in many search applications where data are constantly entering and leaving.
    - Heaps: used by JVM (Java Virtual Machine) to store Java objects.
    - Treaps: used in wireless networking.

7. Heaps

    A Heap is a special case of a binary tree where the parent nodes are compared to their children with their values and are arranged accordingly.

### Applications of heaps

    - Used in heapsort algorithm.
    - Used to implement priority queues as the priority values can be ordered according to the heap property where the heap can be implemented using an array.
    - Queue functions can be implemented using heaps within O(log n) time.
    - Used to find the kᵗʰ smallest (or largest) value in a given array.

8. Graphs

    A graph consists of a finite set of vertices or nodes and a set of edges connecting these vertices.

    The order of a graph is the number of vertices in the graph. The size of a graph is the number of edges in the graph.

    Two nodes are said to be adjacent if they are connected to each other by the same edge.

### Applications of graphs

    - Used to represent social media networks. Each user is a vertex, and when users connect they create an edge.
    - Used to represent web pages and links by search engines. Web pages on the internet are linked to each other by hyperlinks. Each page is a vertex and the hyperlink between two pages is an edge. Used for Page Ranking in Google.
    - Used to represent locations and routes in GPS. Locations are vertices and the routes connecting locations are edges. Used to calculate the shortest route between two locations.