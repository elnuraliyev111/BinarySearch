# BinarySearch
BINARY SEARCH: PYTHON
Iterative Binary Search
Anything recursive can be written iteratively.

As a final exercise, we’ll implement the binary search algorithm using iteration.

Our strategy remains largely the same as the recursive approach which used pointers.

Instead of recursive calls, we’ll substitute a while loop.

Instructions
1.
Complete the binary_search() skeleton.

You’ll need to:

Fill in the condition for the while loop
Calculate the middle index using pointers
Set the left_pointer when appropriate
Set the right_pointer when appropriate


# BINARY SEARCH TREES: PYTHON
Review
In this lesson, you have successfully built a Binary Search Tree (BST) data structure in Python. You have implemented:

a BinarySearchTree class containing value, depth, and left and right child nodes.
an .insert() method to place a node of a specified value at the correct location in the Binary Search Tree. The time efficiency of this operation is O(logN) for a balanced tree - if there are N nodes in the BST, the max depth of a balanced tree is log(N). So, this method makes at most log(N) value comparisons. In the worst case of an imbalanced tree (all values on one side), the performance would be O(N).
a .get_node_by_value() method to retrieve a node in the tree by its value. The time efficiency of this operation is also O(logN) for a balanced tree - if there are N nodes in the BST, the max depth of the tree is log(N), so this method makes at most log(N) value comparisons. In the worst case of an imbalanced tree (all values on one side), the performance would be O(N).
a .depth_first_traversal() method to print the inorder traversal of the Binary Search Tree. This visits every single node, so if there are N nodes, the time efficiency for traversal is O(N).
Great job! The Binary Search Tree is a dynamic data structure that provides efficient insertion and searching of data. It has the benefit of being easily expandable while maintaining a sorted order of the data. In more complex implementations, we could include:

a .delete() method
a self-balancing feature as data is inserted that maintains that two sides of the tree are even, guaranteeing a max depth of log(N)
Try these out for yourself if you are up for the challenge!

Instructions
Let’s review by verifying the correctness of our implementation.

The code provided generates ten random values that are added to the Binary Search Tree with a root value of 15.

Run the file multiple times. After each run, verify that the nodes are in the right places by paying attention to the outputs from the inorder traversal of the trees. To print the inorder traversal, uncomment the last two lines of code.
