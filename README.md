
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
Developed by: JANARTHANAN B
RegisterNumber: 212223100014
'''

def max_marks(array):
    array.sort()
    return array[-1]

```

ii)	# To find the maximum marks using the list method max().
```Python
'''
Developed by: JANARTHANAN B
RegisterNumber: 212223100014
'''

def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.
```Python
'''
Developed by: JANARTHANAN B
RegisterNumber: 212223100014
'''

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1  



```

## Output:
### To find the maximum of marks using the list method sort.
![image](https://github.com/jokerjana/FindMaximum/assets/147173630/8eb2062c-af47-4666-bfd5-bf99f65f9a20)

### To find the maximum marks using the list method max().
![image](https://github.com/jokerjana/FindMaximum/assets/147173630/ede5ecb3-9585-4dfc-8183-66eb766399d2)

### To find the maximum marks without using builtin functions.
![image](https://github.com/jokerjana/FindMaximum/assets/147173630/308e2e32-b929-471c-9510-9de3e6129dd1)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
