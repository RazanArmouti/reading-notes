# Implementation: Trees

## ***Trees*** 
 Node - A Tree node is a component which may contain it’s own values, and references to other nodes
 Root - The root is the node at the beginning of the tree
 K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
 Left - A reference to one child node, in a binary tree
 Right - A reference to the other child node, in a binary tree
 Edge - The edge in a tree is the link between a parent and child node
 Leaf - A leaf is a node that does not have any children
 Height - The height of a tree is the number of edges from the root to the furthest leaf

 ![tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)

 raversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:
 1. Depth First
 2. Breadth First

 ## tree types:
  1. Binary Trees 
  2. Binary Search Trees
  3. K-ary Trees

Big O
The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height). In the worst case, we will have to search all the way down to a leaf, which will require searching through as many nodes as the tree is tall. In a balanced (or “perfect”) tree, the height of the tree is log(n). In an unbalanced tree, the worst case height of the tree is n.

The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space