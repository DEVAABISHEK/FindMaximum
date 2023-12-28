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
## Output:
![Screenshot 2023-12-28 205325](https://github.com/etjabajasphin/FindMaximum/assets/150319305/30cb9c67-237a-4fa1-a682-660a741ddc64)
![Screenshot 2023-12-28 205357](https://github.com/etjabajasphin/FindMaximum/assets/150319305/87f18c90-0b2e-4889-978b-bc061a3bfe86)
![Screenshot 2023-12-28 205425](https://github.com/etjabajasphin/FindMaximum/assets/150319305/2f5f66eb-9355-4987-8158-827586af6ed6)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
