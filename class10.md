# Stacks and Queues

This repository provides a JavaScript implementation of Stacks and Queues. Stacks and Queues are fundamental data structures in computer science, commonly used to manage data in various algorithms and applications.

## Why use Stacks and Queues?

Stacks and Queues offer specific benefits in different scenarios:

- **Stacks** are useful for managing function calls, storing undo/redo operations, and solving problems that require a last-in-first-out (LIFO) approach. They help in maintaining the order of elements and can be used for recursive algorithms, backtracking, and depth-first search.

- **Queues** are designed for situations where you need to manage elements in a first-in-first-out (FIFO) manner. They are commonly used for process scheduling, breadth-first search, and managing network requests.

By understanding and utilizing Stacks and Queues, you can enhance your ability to design efficient algorithms, solve problems, and optimize your code.

## What's included in this repository?

This repository includes the following JavaScript files:

- `Stack.js`: Implements the Stack data structure with methods for pushing, popping, and peeking elements.
- `Queue.js`: Implements the Queue data structure with methods for enqueueing, dequeueing, and getting the front element.

Each file contains detailed comments explaining the purpose and usage of the respective data structure.

## How to use Stacks and Queues?

Here's an example of using the Stack class:

```javascript
const stack = new Stack();
stack.push(1);
stack.push(2);
stack.push(3);
console.log(stack.peek());  // Output: 3
console.log(stack.pop());   // Output: 3
console.log(stack.pop());   // Output: 2
console.log(stack.pop());   // Output: 1
console.log(stack.pop());   // Output: null (empty stack)

const queue = new Queue();
queue.enqueue('apple');
queue.enqueue('banana');
queue.enqueue('orange');
console.log(queue.peek());     // Output: 'apple'
console.log(queue.dequeue());  // Output: 'apple'
console.log(queue.dequeue());  // Output: 'banana'
console.log(queue.dequeue());  // Output: 'orange'
console.log(queue.dequeue());  // Output: null (empty queue)
```

### return to [Main Read Me File](./README.md)
