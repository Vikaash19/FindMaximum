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
~~~
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
def max_marks(marks):
    marks.sort()
    m=marks[-1]
    return m
~~~

ii)	# To find the maximum marks using the list method max().
~~~
''' 
Program to find the maximum marks using the list method max().
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
def max_marks(marks):
    m=max(marks)
    return m


~~~

iii) # To find the maximum marks without using builtin functions.
~~~
''' 
Program to the maximum marks without using builtin functions.
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
def max_marks(list1):
    m=list1[0]
    for i in list1:
        if i>m:
            m=i
    return m


~~~
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2023-11-26 145110](https://github.com/Vikaash19/FindMaximum/assets/148514589/aae40c2a-8196-4d95-90ed-4c7cb711cf34)
ii)	# To find the maximum marks using the list method max().
![Screenshot 2023-11-26 145236](https://github.com/Vikaash19/FindMaximum/assets/148514589/546c3221-57ed-4458-96b9-e77c0f4ade45)
iii) # To find the maximum marks without using builtin functions.
![Screenshot 2023-11-26 145319](https://github.com/Vikaash19/FindMaximum/assets/148514589/466114d7-38e5-46b5-bd00-af0cd5643522)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
