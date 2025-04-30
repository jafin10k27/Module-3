
# Exp.No:3d  
## TUPLES - Write a python program to create the tuple by the multiples of 9 up to N and the print length of the tuple. Get the N value from the user.

### AIM  
To create a tuple containing multiples of 9 up to a given number N and print the length of the tuple.

### ALGORITHM

1.Get the value of N (the upper limit) from the user.

2.Initialize an empty tuple t.

3.Loop through the range from 9 to N in steps of 9 (to get multiples of 9).

4.For each multiple of 9, add it to the tuple t.

5.Print the resulting tuple.

6.Print the length of the tuple using the len() function.


### PROGRAM

```
# Reg.No-212223020018
# Name-Mohamed Jafin S
t=tuple()
n=int(input())
for i in range(9,n,9):
    t=t+(i,)
print(t)
print("Length of the tuple is",len(t))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/3f83ca02-26e6-435b-9ded-7b80022c6846)

### RESULT
For N = 50, the tuple contains the multiples of 9: (9, 18, 27, 36, 45) and its length is 5.
