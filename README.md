# Hashing
In this section we will attempt to go one step further by building a data structure that can be searched in O(1) time. This concept is referred to as hashing.  In order to do this, we will need to know even more about where the items might be when we go to look for them in the collection. If every item is where it should be, then the search can use a single comparison to discover the presence of an item. 
http://interactivepython.org/runestone/static/pythonds/SortSearch/Hashing.html

# Binary Tree
Like linked lists, trees are made up of nodes. A common kind of tree is a binary tree, in which each node contains a reference to two other nodes (possibly None). 
The top of the tree (the node tree refers to) is called the root. In keeping with the tree metaphor, the other nodes are called branches and the nodes at the tips with null references are called leaves. It may seem odd that we draw the picture with the root at the top and the leaves at the bottom, but that is not the strangest thing.

To make things worse, computer scientists mix in another metaphor: the family tree. The top node is sometimes called a parent and the nodes it refers to are its children. Nodes with the same parent are called siblings.

Finally, there is a geometric vocabulary for talking about trees. We already mentioned left and right, but there is also up (toward the parent/root) and down (toward the children/leaves). Also, all of the nodes that are the same distance from the root comprise a level of the tree.
