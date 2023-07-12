# Trees Cheat Sheet

## Common Terminology

- **Node**: A component of a tree that can contain its own values and references to other nodes.
- **Root**: The topmost node of a tree.
- **K**: The maximum number of children any node can have in a k-ary tree (k = 2 for binary tree).
- **Left**: A reference to the left child node in a binary tree.
- **Right**: A reference to the right child node in a binary tree.
- **Edge**: The link between a parent and child node.
- **Leaf**: A node without any children.
- **Height**: The number of edges from the root to the furthest leaf.

## Traversals

### Depth First Traversal

- **Pre-order**: Process root, left subtree, and then right subtree.
- **In-order**: Process left subtree, root, and then right subtree.
- **Post-order**: Process left subtree, right subtree, and then root.

### Breadth First Traversal

- Process nodes at each level from left to right.

## Binary Trees

- Each node can have at most two children.
- No specific sorting order.
- Insertion and search operations have a time complexity of O(n) in the worst case.
- No structural rules for node placement.

## Binary Search Trees (BST)

- Nodes are organized in a sorted manner.
- Left child nodes have values smaller than the root, and right child nodes have values larger than the root.
- Searching a BST can be done efficiently by comparing values and traversing left or right.
- Insertion and search operations have a time complexity of O(h), where h is the height of the tree.
- In a balanced tree, the height is log(n), while in an unbalanced tree, the height can be n.

## Big O Complexity

- Binary Tree:
  - Insertion and search: O(n)
  - Space: O(w) (width of the tree)

- Binary Search Tree:
  - Insertion and search: O(h) (height of the tree)
  - Space: O(1)

### return to [Main Read Me File](./README.md)