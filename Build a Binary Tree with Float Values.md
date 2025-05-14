# Ex. No: 15A - Build a Binary Tree with Integer Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using Integer values.


## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**


## PYTHON PROGRAM

```
from binarytree import Node
l=[]
for i in range(0,3):
    a=int(input())
    l.append(a)
root = Node(l[0])
root.left = Node(l[1])
root.right = Node(l[2])
print('List of nodes :', list(root))

```

## OUTPUT
![image](https://github.com/user-attachments/assets/38e7133c-a923-4629-8b03-30045ca71b68)



## RESULT
Thus the Python program to build a binary tree with a root, left, and right node using Integer values is implemented and executed successfully.
