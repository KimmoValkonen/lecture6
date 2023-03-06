# Activities

## Task 1: Tree Definition

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/DefSumm.html
  # Which statement is false?: Every binary tree has at least one node
  # Suppose T is a binary tree with 14 nodes. What is the minimum possible height of T?: 3
  # What is the minimum number of nodes in a full binary tree with height 3?: 7
  # What is the minimum number of internal nodes in a binary tree with 8 nodes?: 4
  # What is the minimum number of nodes in a complete binary tree with height 3? 8

## Task 2

- Explain how the code in ./src/bt.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-tree-array-implementation/

  # Answer:
  root('A') sets root as 'A'
  set_left('B', 0) sets left children as 'B' for root 'A'
  set_right('C', 0) sets right children as 'C' for root 'A'
  set_left('D', 1) sets left child as 'D' for child 'B'
  set_right('E', 1) sets right child as 'E' for child 'B'
  set_right('F', 2) sets right child as 'F' for child 'C'
  print_tree() prints ABCDE-F---


## Task 3: Tree Traversal

Refer to te following links. Discuss the difference between the different ways binary trees can be traversed.

- [Pre-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPreorderPRO.html)
- [Post-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPostorderPRO.html)
- [In-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravInorderPRO.html)

Pre-order traversal: Visit the root node, then recursively visit the left subtree, then recursively visit the right subtree.
          
Post-order traversal: Recursively visit the left subtree, then recursively visit the right subtree, then visit the root node.

In-order traversal: Recursively visit the left subtree, then visit the root node, then recursively visit the right subtree.

## Task 4: Individual (at home)

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.

  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/TravSumm.html
- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
1.If you are given the order of the nodes as visited by a postorder traversal and the order of the nodes as visited by an inorder traversal, do you have enough information to reconstruct the original tree? Assume that the nodes all have unique values: True

2.Why does function preorder2() presented in the Traversal module make only half as many recursive calls as function preorder()?: Because only internal nodes get called

3.The nn nodes in a binary tree can be visited in: Θ(n)Θ(n) time.

In order to visit all nn nodes in a binary tree, we must traverse each node exactly once. Therefore, the time complexity for visiting all nodes in a binary tree is linear in terms of the number of nodes, i.e., Θ(n)Θ(n) time.

4.When you print out the nodes of binary tree, the leaf nodes appear in the same relative order for the preorder, inorder, and postorder traversals: False

5.Visiting each element in a tree is known as: Traversing


https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/Treeprobs.html
1.How many descendents does the root of this tree have?
  There was 8. Need to count all other than the top one.


2.What is the depth of this tree?
  Trees have height -- they do not have depth

3.How many nodes in the tree have at least one sibling?
  6 (Siblings must have the same parent. If a node has two children, then each such child has a sibling.)


4.Which statement is correct?
  The tree was neither full nor complete

5.How many leaf nodes does this tree have?
  there was 4 (Last individuals counted)


## Links

- https://cpp.sh/
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTree.html
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html
