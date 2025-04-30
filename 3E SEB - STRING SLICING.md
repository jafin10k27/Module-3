# Exp.No:3e
## SEB -Write a Python program to find sequences of Upper case letters joined with a underscore.

### AIM  
To find sequences of uppercase letters joined with an underscore in a given string using regular expressions.

### ALGORITHM

1.Take the input string s from the user.

2.Use the re.search() function to search for a pattern of uppercase letters followed by an underscore and then more uppercase letters (e.g., ABC_DEF).

3.If the pattern is found, print "Found a match!".

4.If the pattern is not found, print "Not matched!".

### PROGRAM

```
# Reg.No-212223020018
# Name-Mohamed Jafin S
import re
s=input()
result=re.search('[A-Z]+_[A-Z]',s)
if result:
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/3ec5e89d-9770-4a24-a84f-3f74346fc918)

### RESULT
The program successfully finds and matches sequences of uppercase letters joined with an underscore. If such a sequence is found, it prints "Found a match!", otherwise "Not matched!".
