# Ex. No: 15A - Build a binary tree consist of a root, left and right node

## AIM:
To write a Python program to build a binary tree consist of a root, left and right node.

---

## ALGORITHM:

1. **Start the program.**
2. Start
3. Define a Node class with:
      - data
      - left pointer
      - right pointer
4. Create a function buildTree():
      a) Read root_value
      b) Create root = Node(root_value)
      c) Read left_value
         If left_value is not None:
             root.left = Node(left_value)
      d) Read right_value
         If right_value is not None:
             root.right = Node(right_value)
      e) Return root

5. **End the program.**

---

## PROGRAM:

```
from  binarytree      import Node
l=[]
for i in range(0,3):
    a=input()
    l.append(a)
root=Node(l[0])
root.left=Node(l[1])
root.right=Node(l[2])
print("Binary Tree :")
for i in root.values:
    print(i,"--> ",end="")
```

## OUTPUT

<img width="887" height="193" alt="image" src="https://github.com/user-attachments/assets/137c9c89-de6a-4493-a377-ebcf881181a0" />


## RESULT
Thus the Python program to  Build a binary tree consist of a root, left and right node has been implemented and executed successfully.
