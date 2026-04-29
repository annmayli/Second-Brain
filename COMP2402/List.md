List: an indexed sequence of elements

Operations
- `size()`: Returns the number of elements in the list
- `add(i,x)`: Adds x into index i
- `get(i)`: Returns the element at the specified position
- `set(i,x)`: Replaces the element at index i to be x 
- `remove()`Removes the element at the specified position

You cannot create a List object directly (because it is an interface)
- Must use a class that implements the `List` interface, such as:
	- [`ArrayList`](https://www.w3schools.com/java/java_arraylist.asp) : a resizable array with fast random access
	- [`LinkedList`](https://www.w3schools.com/java/java_linkedlist.asp) : a train of cars you can easily attach or remove