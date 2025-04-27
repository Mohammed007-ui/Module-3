# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No-
# Name-
# Add your code here

# Accept a string from the user
input_string = input("Enter a string: ")

# Slice the string from 4th position (index 3) to 10th position (index 9)
substring = input_string[3:10]

# Reverse the sliced substring and take alternate characters
new_string = substring[::-1][::2]

# Print the final processed string
print("The new string is:", new_string)


```

### OUTPUT
![image](https://github.com/user-attachments/assets/c4d5fc85-fc69-495b-9488-743cde837e7a)


### RESULT
RESULT
The Python program to slice a string and reverse characters with alternate characters from the 4th to the 10th position has been successfully implemented and executed.
