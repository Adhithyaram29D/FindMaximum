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
Developed by: ADHITHYARAM D
RegisterNumber: 212222230008
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: AdhithyaRam
RegisterNumber: 212222230008
'''
def max_marks(marks):
    marks=max(marks)
    return marks


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: AdhithyaRam D
RegisterNumber: 212222230008
'''
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
![Screenshot 2023-06-03 214608](https://github.com/Adhithyaram29D/FindMaximum/assets/119393540/f4d62b31-a807-4fe8-8eca-76963cfde4bd)

![Screenshot 2023-06-03 214801](https://github.com/Adhithyaram29D/FindMaximum/assets/119393540/e7817ffc-1008-4f39-bed8-0aeafb86aa42)

![Screenshot 2023-06-03 214814](https://github.com/Adhithyaram29D/FindMaximum/assets/119393540/77a896ac-d2e5-4dda-b5cb-20b04835b50b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
