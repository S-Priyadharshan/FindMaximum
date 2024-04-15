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
```
"""
Description: Program to find the max marks in a list using sorted method
Developed By:Priyadharshan S
Reference No.:212223240127
"""
def max_marks(list1):
    list1.sort()
    return list1[-1]


```

ii)	# To find the maximum marks using the list method max().
```
"""
Description: Program to find max marks using the list method max()
Developed By:Priyadharshan S
Reference No.:212223240127
"""
def max_marks(list1):
    return max(list1)


```

iii) # To find the maximum marks without using builtin functions.
```
"""
Description: Program to find the max marks in a list without using built-in functions
Developed By:Priyadharshan S
Reference No.:212223240127
"""
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```

## Output:

![image](https://github.com/S-Priyadharshan/FindMaximum/assets/145854138/33035b75-50d5-4cbf-bbfe-ee126f02cbb7)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
