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
def max_marks(marks):
marks.sort()
large = marks[-1]
return large
   
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
large = max(marks)
return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
max = list1[0]
for i in list1:
if i > max:
max = i
return max
```
/*
Program to find the solution for maximum marks.
Developed by: Yuvarani T
RegisterNumber: 22009033
/*
## Output:
![python 1](https://user-images.githubusercontent.com/121418522/212913177-b0561cee-3666-4a1e-bd6a-d4489abf863b.png)

![python 2](https://user-images.githubusercontent.com/121418522/212913340-3bd590c9-5b6f-439b-8b9a-94989efbbe8c.png)

![python 3](https://user-images.githubusercontent.com/121418522/212913408-93dab069-65ab-48c5-8fe0-53522ee8bb4a.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
