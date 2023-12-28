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
Developed by: Sanjai S
RegisterNumber: 23003393
def max_marks(marks):
    marks.sort()
    highest=marks[-1]
    return highest
```

ii)	# To find the maximum marks using the list method max()
```
Developed by:Sanjai S
RegisterNumber: 23003393
def max_marks(marks):
   marks1=max(marks)
   return marks1
```

iii) # To find the maximum marks without using builtin functions.
```
Developed by:Sanjai 
RegisterNumber: 23003393
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
![Screenshot 2023-12-28 160503](https://github.com/Sanjaikee/FindMaximum/assets/150231888/ffa76743-147e-41fa-b082-85533a5c0a22)
![Screenshot 2023-12-28 160520](https://github.com/Sanjaikee/FindMaximum/assets/150231888/b61d3d93-4244-47a1-b886-1dd7458db721)
![Screenshot 2023-12-28 160539](https://github.com/Sanjaikee/FindMaximum/assets/150231888/89883353-6a43-476f-bd22-75b8385f354b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
