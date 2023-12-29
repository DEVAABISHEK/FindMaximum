# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: DEVA ABISHEK P
RegisterNumber: 23012976
'''
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: DEVA ABISHEK P
RegisterNumber: 23012976
'''
def max_marks(marks):
    a=max(marks)
    return a

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: DEVA ABISHEK P
RegisterNumber: 23012976
'''
def max_marks(list1):
    for i in list1:
        if i>94:
            return i


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-28 205325](https://github.com/DEVAABISHEK/FindMaximum/assets/150319305/b6a5e908-d967-4828-9aa4-9503ff2b711b)
![Screenshot 2023-12-28 205357](https://github.com/DEVAABISHEK/FindMaximum/assets/150319305/23bd95b2-c1d7-418a-9ca2-4d307550ecab)
![image](https://github.com/DEVAABISHEK/FindMaximum/assets/150319305/58f899e2-f599-4899-9145-fed8ed8c8114)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
