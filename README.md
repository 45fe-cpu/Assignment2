# Assignment 2 — Logical Data Structures in Java

##  Project Description
This project is an implementation of basic physical and logical data structures in Java without using `java.util.*` (except for `Iterator`). The assignment includes creating:

- `MyArrayList<T>` — custom dynamic array
- `MyLinkedList<T>` — custom doubly linked list
- `MyStack<T>` — stack based on list
- `MyQueue<T>` — queue based on list
- `MyMinHeap<T extends Comparable<T>>` — min-heap priority queue

##  Structure
```
/src
├── MyList.java
├── MyArrayList.java
├── MyLinkedList.java
├── MyStack.java
├── MyQueue.java
├── MyMinHeap.java
└── Main.java
```

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/assignment2.git
```
2. Open the project in IntelliJ IDEA or other Java IDE
3. Run `Main.java`

##  Features & Testing
Each class is tested in `Main.java`:
- ArrayList and LinkedList: add, remove, set, get, contains
- Stack: push, pop, peek
- Queue: enqueue, dequeue, peek
- MinHeap: insert, peek, extractMin

