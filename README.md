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
```python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: your name: shaik sameer
RegisterNumber: 21003881
''' 
def max_marks(marks):
    #Write your code here
    marks.sort()
    large =marks[-1]
    return(large)
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: your name: shaik sameer
RegisterNumber: 21003881
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
Developed by: your name: shaik sameer
RegisterNumber: 21003881
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
## max1
![output](https://github.com/Shaik-sameer-AIML/FindMaximum/blob/main/max1.JPG?raw=true) 
## max2
![output](https://github.com/Shaik-sameer-AIML/FindMaximum/blob/main/max2.JPG?raw=true)
## max3
![output](https://github.com/Shaik-sameer-AIML/FindMaximum/blob/main/max3.JPG?raw=true)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.