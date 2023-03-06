# Activities

## Task 1

- Refer to the following link. Discuss how Min Heap data structure works:
  https://www.cs.usfca.edu/~galles/visualization/Heap.html


A min heap is a binary tree data structure in which every parent node has a value less than or equal to its children nodes.

In a min heap, the root node always has the minimum value in the tree. The left and right subtrees of a node are also min heaps, so the entire tree is recursively a min heap.

Here's how min heap works:

Initialization: To initialize a min heap, we start with an empty binary tree. We then add elements to the tree one by one, such that each new element is added as a new leaf node.

Insertion: When a new element is inserted into the min heap, it is added as a new leaf node. The min heap property is then maintained by repeatedly comparing the value of the new leaf node with its parent node. If the value of the new leaf node is less than its parent node, the two nodes are swapped. This process is repeated until the new node is in its correct position and the min heap property is restored.

Removal: To remove the minimum value from a min heap, we remove the root node of the tree. We then replace the root node with the last leaf node in the tree, and remove the last leaf node. The min heap property is then maintained by repeatedly comparing the value of the new root node with its children nodes. If the value of the root node is greater than either of its children nodes, the two nodes are swapped. This process is repeated until the root node is in its correct position and the min heap property is restored.

Peek: To get the minimum value from a min heap, we simply return the value of the root node.

The time complexity of insertion and removal operation is O(log n) since the height of a min heap is logarithmic to the number of nodes in the heap. The space complexity of a min heap is O(n) since it requires memory proportional to the number of nodes in the heap.

## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-heap/

Discuss the Time and Space Complexity of Heap data structure operations, in the Best case, average case and worst case.

The time and space complexity of heap data structure operations in the best case, average case, and worst case are as follows:

Insertion:

Best case: O(1). This occurs when the inserted element is the smallest or largest element in the heap, and it is inserted as the first or last element in the array representing the heap, respectively.
Average case: O(log n). This is the expected time complexity for inserting a new element in the heap.
Worst case: O(log n). This occurs when the inserted element violates the heap property, and we need to swap it with its parent recursively until the heap property is restored.

Removal (extracting the minimum or maximum element):

Best case: O(1). This occurs when the heap has only one element.
Average case: O(log n). This is the expected time complexity for removing the minimum or maximum element from the heap.
Worst case: O(log n). This occurs when we need to swap the removed element with its child recursively until the heap property is restored.

Peek (getting the minimum or maximum element without removing it):

Best case: O(1). This occurs when the minimum or maximum element is the root of the heap.
Average case: O(1).
Worst case: O(1).

Space complexity:

The space complexity of a heap is O(n), where n is the number of elements in the heap. This is because we need to store the elements in an array or a tree-like structure to maintain the heap property. However, the actual space used may be less than O(n) if the heap is implemented as an array with a few empty slots, or if the heap is a binary tree with some missing nodes.