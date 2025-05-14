# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**


## PROGRAM:

```
import heapq
def heaptree(H):
    heapq.heapify(H)
    print("The created Heap is",H)

```

## OUTPUT
![image](https://github.com/user-attachments/assets/dab8e6c2-79bd-4e8b-922e-5ec8589ef1cb)




## RESULT
Thus the Python program to build a heap tree using appropriate Python package and function is implemented and executed successfully.
