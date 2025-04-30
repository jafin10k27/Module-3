
# Exp.No:3b  
## REGEX - For the given list, filter all elements that do not contain e.items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

### AIM  
Filter out all elements from the list that do not contain the letter 'e'.

### ALGORITHM

1.Initialize the list of items.

2.Create an empty list, b.

3.Loop through each element of the list.

4.For each element, check if the letter 'e' is not present.

5.If the element does not contain 'e', append it to the list b.

6.Finally, print the resulting list b.

### PROGRAM

```
# Reg.No-212223020018
# Name-Mohamed Jafin S
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
b=[i for i in items if 'e' not in i]
print(b)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/bd2f46f7-25c6-4eba-82c3-667e258e4d3e)

### RESULT
Given the list ['goal', 'new', 'user', 'sit', 'eat', 'dinner'], after filtering out the elements that do not contain 'e', the result will be:
