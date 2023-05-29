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
Developed by: MAHESWARAN.K
RegisterNumber: 212222110023
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: MAHESWARAN.K
RegisterNumber: 212222110023
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: MAHESWARAN.K
RegisterNumber: 212222110023
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Output:
i) # To find the maximum of marks using the list method sorts.
![Screenshot (6)](https://github.com/MAHESWARAN2004/FindMaximum/assets/119478181/9a84cb22-2e3d-465c-a459-90e41d8ec053)

ii) # To find the maximum marks using the list method max().
![Screenshot (7)](https://github.com/MAHESWARAN2004/FindMaximum/assets/119478181/7f48f528-ed56-426b-a6cc-f7a3d78f6062)

iii) # To find the maximum marks without using builtin functions.
![Screenshot (8)](https://github.com/MAHESWARAN2004/FindMaximum/assets/119478181/592fd0b0-32d6-452a-bbe9-d6d4fe56ee43)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
