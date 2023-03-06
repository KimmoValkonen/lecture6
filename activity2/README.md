# Activities

## Task 1

- Refer to the following link. Discuss how Binary Search Trees work:
  https://www.cs.usfca.edu/~galles/visualization/BST.html

  A Binary Search Tree is a data structure that is used to organize elements in a hierarchical manner. The key property of a BST is that it maintains an ordered structure where the left subtree of any node contains only nodes with keys that are less than the node's key, and the right subtree contains only nodes with keys that are greater than the node's key.

  The visualization allows the user to add, remove, and search for nodes in the tree. When a node is added to the tree, it is placed in the appropriate location based on its key value, such that the left subtree only contains nodes with smaller key values and the right subtree only contains nodes with larger key values. Similarly, when a node is removed from the tree, the tree is restructured to maintain the ordering property.

  The BST allows for efficient search, insertion, and deletion operations, with a time complexity of O(log n) for each operation in the average case. This is because the height of the tree is minimized through the ordering property, allowing for the tree to be traversed efficiently.


## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-binary-search-tree/

Discuss the Time and Space complexity of Binary Search Tree (BST) operations (Searching, Insertion, Deletion) in the Best case, average case and worst case.

The time and space complexity of Binary Search Tree (BST) operations can vary based on the input data and the specific implementation of the BST. Generally, the time complexity of searching, insertion, and deletion operations in a BST is dependent on the height of the tree, which is affected by the ordering of the input data.

Searching: In the best case, where the tree is perfectly balanced, the time complexity of searching is O(log n), where n is the number of nodes in the tree. In the average case, the time complexity is also O(log n), assuming the input data is randomly ordered. However, in the worst case, where the tree is completely unbalanced (i.e., the tree is essentially a linked list), the time complexity of searching becomes O(n), as all nodes must be visited.

Insertion: In the best case, where the tree is perfectly balanced, the time complexity of insertion is also O(log n). In the average case, the time complexity is also O(log n), assuming the input data is randomly ordered. However, in the worst case, where the tree is completely unbalanced, the time complexity of insertion becomes O(n), as all nodes must be visited to insert a new node.

Deletion: The time complexity of deletion also depends on the height of the tree. In the best case, where the node to be deleted has no children, the time complexity is O(1). In the average case, the time complexity is O(log n), assuming the input data is randomly ordered. However, in the worst case, where the node to be deleted has two children, the time complexity becomes O(n), as all nodes must be visited to find the node with the next largest value to replace the deleted node.

In terms of space complexity, the space required for a BST is proportional to the number of nodes in the tree. Therefore, the space complexity of a BST is O(n), where n is the number of nodes in the tree.

It's worth noting that there are variations of BSTs that attempt to address the worst-case scenario, such as AVL trees and Red-Black trees, which maintain the ordering property while keeping the height of the tree balanced. These structures can improve the worst-case time complexity of search, insertion, and deletion to O(log n).


## Task 3

- Explain how the code in ./src/bst.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/introduction-to-binary-search-tree-data-structure-and-algorithm-tutorials/

  Code implements the insertion of nodes in a Binary Search Tree (BST), and then prints the BST in inorder traversal. The code defines a struct node to represent a node in the BST, which has a key value and two child pointers, one for the left child and one for the right child.

  The newNode function creates a new node with a given key value and initializes its child pointers to NULL. The insert function takes in a node pointer and a key value, and recursively inserts a new node with the key value at the appropriate position in the BST. The inorder function performs an inorder traversal of the BST and prints out the key values of each node in ascending order.

  In the main function, a BST is created by inserting a series of nodes with various key values. The inorder function is then called to print out the BST in order. Finally, the program returns 0, indicating successful execution.

## Task 4: Individual (at home)

- Refer to te following link. Explain how In-order Traversal is used to print a binary search tree.
  https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html#inorder-traversal

  In-order traversal is a method of visiting all nodes of a binary tree, including a binary search tree (BST), in a specific order. The order of traversal is as follows: first visit the left subtree, then the root node, and finally the right subtree.

  To print a BST using in-order traversal, we visit all nodes of the tree in the above order and print the value of each node as we visit it. Since a BST is organized in such a way that the values in the left subtree of a node are always less than the node's value, and the values in the right subtree are always greater than the node's value, visiting the left subtree before the root node will print out all values smaller than the root node's value, and visiting the right subtree after the root node will print out all values greater than the root node's value.

  Therefore, performing an in-order traversal of a BST will print the values in ascending order. This property of BST makes it very useful for searching and sorting data.

## Link(s)

- https://cpp.sh/
- https://www.geeksforgeeks.org/binary-search-tree-data-structure/