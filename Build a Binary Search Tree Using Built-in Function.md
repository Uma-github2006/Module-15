# Ex. No: 15B - Build a Binary Search Tree Using Built-in Function

## AIM:
To write a Python program to build a binary search tree using a built-in function.


## ALGORITHM:

1. **Start the program.**
2. Define `_build_bst_from_sorted_values(sorted_values)` to recursively build a binary search tree (BST) from a sorted list.
3. Define `left_subtree(l)` to print the left subtree of the BST.
4. Take user input for the number of elements and store the values in a list `a`.
5. Sort the list and pass it to `_build_bst_from_sorted_values()` to construct the BST.
6. Print the postorder traversal of the BST.
7. Call `left_subtree(l)` to print the left subtree.
8. Check whether the tree is a binary search tree using the `is_bst` property.
9. **End the program.**


## PROGRAM:

```
from binarytree import Node
def _build_bst_from_sorted_values(sorted_values):
    if not sorted_values:
        return None
    else:
        mid=len(sorted_values)//2
        root=Node(sorted_values[mid])
        root.left = _build_bst_from_sorted_values(sorted_values[:mid])
        root.right = _build_bst_from_sorted_values(sorted_values[mid+1:])
    return root
        
size=int(input())
a=[int(input()) for i in range(size)]
t=_build_bst_from_sorted_values(sorted(a))
print(t.postorder)
print(t.is_bst)

```

## OUTPUT
![image](https://github.com/user-attachments/assets/5c344dde-1852-46e7-ac12-0b6c68e689bb)


## RESULT
Thus the Python program to build a binary search tree using a built-in function is executed successfuly.

