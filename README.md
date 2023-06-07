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
Developed by: prem kumar k
RegisterNumber:212222230111 
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large 
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: prem kumar k 
RegisterNumber:21222230111 
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: prem kumar k 
RegisterNumber: 212222230111
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
   
    return max
```

## Sample Input and Output
![output]![3a python prem](https://github.com/premkumarkarthikeyan/FindMaximum/assets/119476243/347e8e32-d358-432d-8287-99cf6c8289c2)
(./img/max_marks1.j!
[3b python prem](https://github.com/premkumarkarthikeyan/FindMaximum/assets/119476243/61e3ae90-302a-4413-8c25-d40a07456e3a)
pg) 
![3c python prem](https://github.com/premkumarkarthikeyan/FindMaximum/assets/119476243/81b6ab68-e146-401e-8cd9-07acff117d11)

## Output:

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
