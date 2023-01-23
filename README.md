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
Developed by: R Manoj karthik
RegisterNumber: 22003728
'''
def max_marks(marks):
    large=max(marks)
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: R Manoj karthik
RegisterNumber: 22003728
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: R Manoj karthik
RegisterNumber: 22003728
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![max1](https://user-images.githubusercontent.com/119560395/214062496-490a9a53-5e2f-43ca-b753-dcd798453e0a.png)
![max2](https://user-images.githubusercontent.com/119560395/214062546-198fa02f-430b-410c-90fe-e79d10de0cee.png)
![max3](https://user-images.githubusercontent.com/119560395/214062654-a27712ad-d27d-46aa-8b62-625b2c96f86c.png)

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
