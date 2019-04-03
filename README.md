# Binary_trees_lesson

## Binary Tree vs tries concept
A tree is a general structure of recursive nodes.
There are many types of trees such as binary tree and balanced tree.
Each kind of tree has a different purpose, structure and behaviour. 
A binary tree stores a collection of comparable items (e.g. numbers) and its structure is sorted so it can be searched quickly to find a single item. (balanced tree is similar in principle). The recursive structure yields a recursive algorithm. A binary tree compares the single searched value to each node.
	Searching has O(h) worst-case runtime complexity, where h is the height of the tree. Since s binary search tree with n nodes has a minimum of O(log n) levels, it takes at least O(log n) comparisons to find a particular node. Therefore the time complexity is O(log(n)) for insertion, deletion and searching. 

A trie stores sequences of values rather than individual single values in its structure. Each level of recursion says what is the value of item 1 of the input list' and does not compare the single searched value to each node as binary trees do.
	
## Examples
	
### Binary Tree example

### Trie example
Why Trie Data Structure?
- Searching trees in general favor keys which are of fixed size since this leads to efficient storage management.• However in case of applications which are retrieval based and which call for keys varying length, tries provide better options.• Tries are also called as Lexicographic Search trees.

![Screenshot of Successful code](../https://image.slidesharecdn.com/datastructuretries-160408155555/95/data-structure-tries-9-638.jpg?cb=1460131130) 

The following picture explains construction of trie using keys given in the example below,

                       root
                    /   \    \
                    t   a     b
                    |   |     |
                    h   n     y
                    |   |  \  |
                    e   s  y  e
                 /  |   |
                 i  r   w
                 |  |   |
                 r  e   e
                        |
                        r
In the picture, every character is of type trie_node_t. For example, the root is of type trie_node_t, and it’s children a, b and t are filled, all other nodes of root will be NULL. Similarly, “a” at the next level is having only one child (“n”), all other children are NULL. The leaf nodes are in blue.



An article when to use tries for the front-end applications.
https://hackernoon.com/practical-data-structures-for-frontend-applications-when-to-use-tries-5428a565eba4

## Binary Tree concept

## Binary Tree examples

### example 1.
- Trees: Unlike Arrays, Linked Lists, Stack and queues, which are linear data structures, trees are hierarchical data structures.
- Tree Vocabulary: The topmost node is called root of the tree. The elements that are directly under an element are called its children. The element directly above something is called its parent. For example, ‘a’ is a child of ‘f’, and ‘f’ is the parent of ‘a’. Finally, elements with no children are called leaves.


tree
      ----
       j    <-- root
     /   \
    f      k  
  /   \      \
 a     h      z    <-- leaves 

### example 2.


## Questions that could be asked on binary trees

## links to relevant resources



