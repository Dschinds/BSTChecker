# Practice problem creating a Java function that is able to determine if a function is a BST 

## The first common idea is to just check to see if the right and left nodes are greater and less then the root 
## This does not work since say a root 10 has two children 9 and 12, if 9 had two children 7 and 14 this would pass the   ## function but be an invalid tree

### The java fucntion I wrote was recursive, but It can also be done iteratively with a stack, both take O(n) time for all ### nodes and O(n) space for the call stack or the physical stack