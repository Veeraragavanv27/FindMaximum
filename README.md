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
Developed by: VEERARAGAVAN V
RegisterNumber:23004739 
'''
def max_marks(marks):
    marks.sort()
    a=marks[-1]
    return a
```
ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: VEERARAGAVAN V
RegisterNumber: 23004739
'''
def max_marks(marks):
    # write your code here
    a=max(marks)
    return a
```
iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:VEERARAGAVAN V 
RegisterNumber: 23004739
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
![Screenshot 2023-12-21 214438](https://github.com/veerargavanv27/FindMaximum/assets/138955645/e6776e7a-0280-4d68-bad4-fe86ed96f201)
![Screenshot 2023-12-21 214459](https://github.com/veerargavanv27/FindMaximum/assets/138955645/12af92dc-6e54-45c1-a6f2-b8c91fdb7d9f)
![Screenshot 2023-12-21 214516](https://github.com/veerargavanv27/FindMaximum/assets/138955645/a522d948-5998-4795-a0c1-985460cfe845)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
