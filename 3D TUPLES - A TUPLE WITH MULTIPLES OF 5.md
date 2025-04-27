# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No-
# Name-
# Add your code here

# Accept an integer N from the user
N = int(input("Enter a number N: "))

# Create a tuple with multiples of 5 up to N
multiples_of_5 = tuple(i for i in range(5, N, 5))

# Print the resulting tuple
print("Tuple with multiples of 5 up to", N, ":", multiples_of_5)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/ec18fccf-a31a-46d8-9bd8-32ff2e0b2799)

### RESULT
The Python program to create a tuple containing all multiples of 5 up to the given number N was successfully implemented and executed.

