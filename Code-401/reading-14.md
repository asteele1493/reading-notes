# Trees

[Reading](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

## Notes on Trees

### Types of Traversal

Depth First is where we go through the depth, or height, first. There are three methods for depth first traversal: 
- Pre-order: ```javascript root >> left >> right```
- In-order: ```javascript left >> root >> right```
- Post-order: ```javascript left >> right >> root```

Breadth First is where we iterate through the tree by going through each level, node by node.

- Most commonly uses a queue to traverse the tree

### Binary Tree Vs. K-ary Tree

- binary trees limit the number of children each node can have to two

- k-ary trees are trees in which nodes can have more than two children
  - in these instances, k is in reference to the max number of children each node is able to have

When traversing a k-ary tree, the breadth first approach is utilized.
  - Instead of checking for the presence of a left and right child, we will be moving down a list of children of length k

In regards to adding nodes to binary trees, there's really no rules. They can be placed pretty much anywhere. General rule of thumb is to add nodes where there are empty children nodes.

In the instance you'd like to place a node in a specific place, you will need to reference both the new node and the parent node.

### Big O

- Inserting a new node - time of O(n)

- Searching for a specific node - time of O(n)

- Inserting a node - space of O(w)

### Binary Search Trees

Binary search trees have a predetermined structure. All node values that are smaller than the root are placed to the left. All node values that are larger than the root are placed to the right.

Searching a binary search tree is a streamlined process because you would first compare the node you are searching for with the root node. If the value of the node to be searched is smaller, traverse to the left, else right.

  - Best way to search a binary search tree is with a while loop.

  - Big O of BST insertion and search operations is time O(h)

  - Big O of a BST search would be space O(1)

### Trees Fill in the Blank

You can approach tree traversal one of two ways: ___________ or ___________.

The most common way to traverse through a tree is to use _______. 

Preorder means that the ____ has to be looked at first.

A k-ary tree is a tree in which the nodes can have more than two _______.

Binary search trees have nodes with _____ values to the right of the root node.

The h in big O notation refers to a binary tree's ________.