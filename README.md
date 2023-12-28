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
Program to mark the maximum of marks using the list method sort
Developed by: M GAYATHIRI ROSHINI
RegisterNumber: 23006823
def max_marks(marks):
    marks.sort()
    highest=marks[-1]
    return highest
```

ii)	# To find the maximum marks using the list method max()
```
Developed by:M GAYATHIRI ROSHINI 
RegisterNumber: 23006823
def max_marks(marks):
   marks1=max(marks)
   return marks1
```

iii) # To find the maximum marks without using builtin functions.
```
Developed by:M GAYATHIRI ROSHINI 
RegisterNumber: 23006823
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
![image](https://github.com/23006823/FindMaximum/assets/138971409/a2d1fb5c-d6ce-4712-8696-8db1562fba88)
![image](https://github.com/23006823/FindMaximum/assets/138971409/6519562b-94e3-4e08-bb2e-fa3242737e23)
![image](https://github.com/23006823/FindMaximum/assets/138971409/f6d15c04-9151-4ae0-a5f5-31d0ceb69cd0)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
