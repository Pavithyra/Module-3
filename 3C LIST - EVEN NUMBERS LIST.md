# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To Write a python program to display the product of all the values which are ending with 2 from a list.

---

### ALGORITHM

Begin the program.
Use eval() to get a list l from the user.
Initialize sum to 1.
Use a for loop to iterate through each element of the list l:
If the current element l[i] has a last digit of 2 (i.e., l[i] % 10 == 2), multiply sum by l[i].
Print the product of the elements that meet the condition.
Terminate the program.

---

### PROGRAM

```
Reg N0-212222060174
Name-Pavithra.S

l=eval(input())
sum=1
for i in range(0,len(l)):
    if l[i]%10==2:
        sum*=l[i]
print("Product= {}".format(sum))
```

### OUTPUT
<img width="932" height="214" alt="image" src="https://github.com/user-attachments/assets/4ed89d55-4ce7-4506-a095-215d46c74217" />


### RESULT
Thus a python program to display the product of all the values which are ending with 2 from a list has been successfully implemented.
