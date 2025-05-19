# LinkedListDeque
Java deque implementation using a doubly-linked list 

LinkedListDeque

**A doubly-linked-list based Deque implementation**  

## Overview

- **`Deque61B<T>` interface** defines:
  - `addFirst(T item)`, `addLast(T item)`
  - `isEmpty()`, `size()`
  - `get(int index)`
  - `removeFirst()`, `removeLast()`
  - `printDeque()`

- **`LinkedListDeque61B<T>`** implements `Deque61B` with a circular sentinel node:
  - Constant-time additions/removals at both ends
  - Returns `null` for out-of-bounds `get` or removes on empty
  - Throws `IllegalArgumentException` if `addFirst(null)` or `addLast(null)` is called

- **Testing**  
  - `LinkedListDeque61BTest.java` covers core functionality.  
  - `PreconditionTest.java` ensures proper exception behavior on invalid arguments.


