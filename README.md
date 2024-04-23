
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
'''program to mark the maximum of marks using the list method sort.
Developed by: JANARTHANAN B
RegisterNumber: 212223100014
'''

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
'''program to find the maximum marks using the list method max().
Developed by: JANARTHANAN B
RegisterNumber: 212223100014
'''

def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
'''program to find the maximum marks without using builtin functions.
Developed by: JANARTHANAN B
RegisterNumber: 212223100014
'''

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark



```

## Output:
### To find the maximum of marks using the list method sort.
![image](https://github.com/jokerjana/FindMaximum/assets/147173630/8eb2062c-af47-4666-bfd5-bf99f65f9a20)

### To find the maximum marks using the list method max().
![image](https://github.com/jokerjana/FindMaximum/assets/147173630/ede5ecb3-9585-4dfc-8183-66eb766399d2)

### To find the maximum marks without using builtin functions.
![image](https://github.com/jokerjana/FindMaximum/assets/147173630/6861b24a-0d44-4073-9194-b423135f5494)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
