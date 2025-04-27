# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
import re

# Reg.No-
# Name-
# Add your code here

# Accept a string from the user
str1 = input("Enter the string: ")

# Define the regular expression pattern
pattern = r"[a]+b{2,3}"

# Use the re.match() function to check if the string matches the pattern
if re.match(pattern, str1):
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/29c086ed-e158-4665-b51b-55a6e9b073e6)

### RESULT
The program for matching a string containing an 'a' followed by two to three 'b' characters using regular expressions was successfully implemented and executed.

