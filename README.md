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

## Output:
![3a python prem](https://github.com/premkumarkarthikeyan/FindMaximum/assets/119476243/26ced738-9b20-4c42-a116-b3db2e18ed6d)
![3b python prem](https://github.com/premkumarkarthikeyan/FindMaximum/assets/119476243/197e2dc0-8304-4408-b689-4d0cd68c2551)
![3c python prem](https://github.com/premkumarkarthikeyan/FindMaximum/assets/119476243/cad2c4c1-595f-4167-8e0f-b8c04f4c1da2)

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
