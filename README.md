Hybrid-AVL-Tree
===============
Data structure that maintains AVL tree structure with the addition of an ArrayList of objects referenced to each tree node.

Methods:
insert( ) :  Inserts an object into the tree. Second insertion to the same node ads the next object to an ArrayList within the node.
remove( ) : Lazy deletes the tree node. Doesn't Effect second insertions to the same tree node.
findMin( ) : finds the least Comparable object.
findMax( ) : finds the greatest Comparable object.
findMode( ) : finds the active node with the most occurrence.
printTree( ) : prints the tree and doesn't show lazy deleted objects.
printBalTree(boolean x): false: Prints to the console the full tree including the lazy deleted objects with information regarding the height and banance of every node and their children.
writeBalTree(boolean x) : Same as above, but outputs the information to a text file in the default directory.
