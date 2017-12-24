# binary-search-tree
Binary Search Tree


## Introduction

Lists, stacks and queues are `linear data structures` (i.e., `sequences)`. A tree is a nonlinear, two-dimensional data 
 structure with special properties. Tree nodes contain two or more links. We discusses binary trees—trees whose nodes 
 each contain two links (one or both of which may be null). The root node is the first node in a tree. Each link in the 
 root node refers to a child. The left child is the first node in the left subtree (also known as the root node of the 
 left subtree), and the right child is the first node in the right subtree (also known as the root node of the right 
 subtree). The children of a specific node are called siblings. A node with no children is called a leaf node. 
 Computer scientists normally draw trees from the root node down—the opposite of the way most trees grow in nature.
 
A binary search tree (with no duplicate node values) has the characteristic that the values in any left subtree are 
 less than the value in that subtree’s parent node, and the values in any right subtree are greater than the value in 
 that subtree’s parent node. The shape of the binary search tree that corresponds to a set of data can vary, depending 
 on the order in which the values are inserted into the tree.

The binary search tree facilitates `duplicate elimination`. While building a tree, the insertion operation recognizes 
 attempts to insert a duplicate value, because a duplicate fol- lows the same “go left” or “go right” decisions on each
 comparison as the original value did. Thus, the insertion operation eventually compares the duplicate with a node 
 containing the same value. At this point, the insertion operation can decide to discard the duplicate value (as we do
 in our example).
 
Searching a binary tree for a value that matches a key value is fast, especially for `tightly packed` (or `balanced`) 
 `trees`. In a tightly packed tree, each level contains about twice as many elements as the previous level. A tightly 
 packed binary search tree with n elements has log2n levels. Thus, at most log2n comparisons are required either to 
 find a match or to determine that no match exists. Searching a (tightly packed) 1000-element binary search tree 
 requires at most 10 comparisons, because 2^10 > 1000. Searching a (tightly packed) 1,000,000-element binary search tree
 requires at most 20 comparisons, because 2^20 > 1,000,000.
 
We present algorithms for several binary tree operations, such as inserting, deleting an item from a binary tree, 
 printing a binary tree in a two-dimensional tree format and performing a `level-order traversal of a binary tree`. The 
 level-order traversal visits the nodes of the tree row by row, starting at the root node level. On each level of the 
 tree, a level-order traversal visits the nodes from left to right.
 
[Application source code]()


Exercises we consider:
* [Preorder Traversal of a Binary Tree (Exercise)](https://github.com/AlbertHambardzumyan/binary-search-tree/blob/master/src/preorder_traversal/PREORDER_TRAVERSAL.md)
* [Inorder Traversal of a Binary Tree (Exercise)](https://github.com/AlbertHambardzumyan/binary-search-tree/blob/master/src/inorder_traversal/INORDER_TRAVERSAL.md)
* [Postorder Traversal of a Binary Tree (Exercise)](https://github.com/AlbertHambardzumyan/binary-search-tree/blob/master/src/postorder_traversal/POSTORDER_TRAVERSAL.md)
* [Provide traversals of the binary search tree (Exercise)]()