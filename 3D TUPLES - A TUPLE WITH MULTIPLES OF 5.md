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
# Reg.No: 212223060161
# Name: Mohammed Ali.S
# Program to create a tuple with multiples of 5 up to a given number N

def generate_multiples_of_5(n):
    return tuple(i for i in range(5, n, 5))

# Main Program
N = int(input("Enter the value of N: "))
multiples_of_5 = generate_multiples_of_5(N)
print("Multiples of 5 up to", N, "are:", multiples_of_5)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/0febd5eb-f9fa-4dd4-b4b4-6f19f7b9a8f0)

### RESULT
Thus, the Python program to create a tuple with multiples of 5 up to a given number N was executed successfully.
