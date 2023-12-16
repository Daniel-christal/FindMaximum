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
Developed by:Daniel.C 
RegisterNumber:23008937 
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by:Daniel.C 
RegisterNumber:23008937 
def max_marks(marks):
    max1=max(marks)
    return max1
```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by:Daniel.C 
RegisterNumber:23008937 
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Daniel-christal/FindMaximum/assets/145742847/443c5dfe-800c-4d13-9dea-4468885f4913)
![image](https://github.com/Daniel-christal/FindMaximum/assets/145742847/569de750-d035-4c41-b1cf-6e5a03f9fd29)
![image](https://github.com/Daniel-christal/FindMaximum/assets/145742847/25a00d88-37b2-48c7-a771-7a6cf3acd1e4)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
