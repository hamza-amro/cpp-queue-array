# Generic Queue Implementation Using Dynamic Array

A template-based Queue implementation built from scratch in C++ using a custom Dynamic Array.

This project demonstrates how the Queue data structure can be implemented without relying on the C++ Standard Library (`std::queue`). Instead, it uses a custom dynamic array implementation to manage elements and provide common queue operations.

---

## Features

* Template-based implementation (`template<class T>`)
* Built on a custom Dynamic Array
* Generic design supporting any data type
* Push elements into the queue
* Remove elements using `pop()`
* Access the front element
* Access the back element
* Reverse the queue
* Update elements by index
* Insert after a specific index
* Insert at the front
* Insert at the back
* Print queue contents
* Clear the queue

---

## Technologies Used

* C++
* Object-Oriented Programming (OOP)
* Templates
* Dynamic Arrays
* Dynamic Memory Allocation
* Generic Programming

---



## Requirements

* C++11 or later
* Any C++ compiler
* Visual Studio, VS Code, Code::Blocks, or another compatible IDE

---

## Build and Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/cpp-queue-array.git
```

2. Open the project in your preferred IDE.

3. Build and run the application.

---

## Example Usage

```cpp
clsMyQueueArr<int> queue;

queue.push(10);
queue.push(20);
queue.push(30);

queue.pop();

cout << queue.front();
cout << queue.Back();
```

---

## Available Operations

| Function        | Description                   |
| --------------- | ----------------------------- |
| push()          | Insert an element             |
| pop()           | Remove an element             |
| front()         | Return the first element      |
| Back()          | Return the last element       |
| Size()          | Return the number of elements |
| Reverse()       | Reverse the queue             |
| UpdateItem()    | Update an element             |
| InsertAfter()   | Insert after a specific index |
| InsertAtFront() | Insert at the front           |
| InsertAtBack()  | Insert at the back            |
| Clear()         | Remove all elements           |

---

## Learning Objectives

This project demonstrates:

* Queue implementation using a Dynamic Array
* Generic programming with templates
* Object-oriented programming
* Dynamic memory management
* Building reusable data structures
* Separation of concerns through class composition

---

## Future Improvements

* Ensure full FIFO behavior with optimized dequeue operations
* Separate logical size from storage capacity
* Add bounds checking with exceptions
* Implement iterators
* Add copy and move semantics
* Improve performance by minimizing reallocations
* Add unit tests

---


## Author

Developed by Hamza Amro.
