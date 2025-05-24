# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No: 212223060161
# Name: Mohammed Ali.S
# Program to create a list of even numbers up to N

def even_numbers_upto_n(n):
    l = []
    for i in range(1, n):
        if i % 2 == 0:
            l.append(i)
    return l

# Main Program
a = int(input("Enter the value of N: "))
even_list = even_numbers_upto_n(a)
print("Even numbers up to", a, "are:", even_list)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/0692a121-1bab-4271-8910-136d54b9a167)

### RESULT
Thus, the Python program to generate a list of even numbers up to a given number N was executed successfully.
