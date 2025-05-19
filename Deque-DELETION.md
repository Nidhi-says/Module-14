# Exp.No:14d
## Deque - DELETION

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

### PROGRAM  

```
import collections
a=int(input())
b=int(input())
c=int(input())
de=collections.deque([a,b,c])
de.popleft()
print("The deque after deleting is :")
print(de)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/a3973958-87ee-4047-9910-a922fe07486e)

### RESULT
Thus a Python program to delete elements at FRONT END of deque using a collection built-in function is implemented successfully.
