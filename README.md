# LinkedListTemplateClass
An implementation of a C++ template class for a linked list using a node class

## Explanation:
1. `node<T>` class: This is a simple class with a generic data type `T` and a pointer to the next node in the list.

2. `LinkedList<T>` class:
  - `append(T value)`: Adds a new node at the end of the list.
  - `prepend(T value)`: Adds a new node at the beginning of the list.
  - `remove(T value)`: Removes the first node that contains the given value.
  - `print()`: Prints the entire list.
  - `Destructor`: Cleans up all nodes when the list is destroyed to prevent memory leaks.

## Activities:
1. Add `First` - remove tand return forst element in list
2. Add `Last` - remove and return last element in list
3. Add `AddOrder` - add element in sorted order (must not use with `append` and `prepend`)
