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

i) To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by:P. Aravind samy
RegisterNumber: 22005040
def max_marks(marks):
    marks.sort()
    a = (marks[-1])
    return a
```

ii)	To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:P. Aravind samy
RegisterNumber: 22005040
'''
def max_marks(marks):
    a = max(marks)
    return a



```

iii) To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by:P.Aravind samy
RegisterNumber: 22005040
'''
def max_marks(a):
    max1 = a[0]
    for i in a:
        if i > max1:
            max1 =i
    return max1


```
## Input:
![output](./img/max_marks1.jpg) 

## Output:
To find the maximum of marks using the list method sort.

![output](/img/output.png)

To find the maximum marks using the list method max()

![output](/img/output1.png)

To find the maximum marks without using builtin functions.

![output](/img/output2.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
