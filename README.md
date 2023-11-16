# EXP-3a Find the maximum of a list of numbers
## Date: 05.09.2023
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
Developed by: Richardson A
RegisterNumber: 23000803
'''
def max_marks(list1):
    #Write your code here
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Richardson A
RegisterNumber: 23000803
'''
def max_marks(marks):
    # write your code here
    max_marks=max(marks)
    return max_marks


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: RICHARDSON A
RegisterNumber:23000803 
'''
def max_marks(list1):
    # write your code here
    list1.sort()
    max=list1[-1]
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://github.com/Richard01072002/FindMaximum/assets/141472248/d899dd2c-e3e0-460b-8b56-612c9c826783)

![image](https://github.com/Richard01072002/FindMaximum/assets/141472248/4953daff-52ad-4956-9393-bc7e5ac0aae0)

![image](https://github.com/Richard01072002/FindMaximum/assets/141472248/f6c208f3-c25a-4c28-a0e4-62de1f349073)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
