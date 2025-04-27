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
# Reg.No-
# Name-
# Add your code here

# Accept an integer N from the user
a = int(input("Enter a number N: "))

# Create an empty list to store even numbers
l = []

# Use a for loop to iterate through numbers from 1 to N-1
for i in range(1, a):
    if i % 2 == 0:  # Check if the number is even
        l.append(i)  # Append the even number to the list

# Print the list of even numbers
print("List of even numbers up to", a, ":", l)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/b11ede92-b187-4ba5-9337-7b72bf1d6e51)
### RESULT
The Python program for creating a list of even numbers up to a given number N was successfully implemented and executed.
