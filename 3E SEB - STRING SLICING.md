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
# Reg.No: 212223060161
# Name: Mohammed Ali.S
# Program to reverse and slice alternate characters from position 4 to 10

def custom_slice_reverse(s):
    sliced = s[2:10]       # characters from index 2 to 9
    reversed_sliced = sliced[::-1]  # reverse the slice
    result = reversed_sliced[::2]   # take alternate characters
    return result

# Main Program
input_str = input("Enter a string: ")
output = custom_slice_reverse(input_str)
print("Processed string:", output)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/6026c3f7-d2cb-430c-968e-00b9af6b1767)

### RESULT
Thus, the Python program to reverse and extract alternate characters from a string slice was executed successfully.
