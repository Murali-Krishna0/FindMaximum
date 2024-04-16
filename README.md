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
```
#Developed By: Murali Krishna S
#Register number : 212223230129

def max_marks(array):
    array.sort()
    return array[-1]



```

ii)	# To find the maximum marks using the list method max().
```
#Developed By: Murali Krishna S
#Register number : 212223230129

def max_marks(array):
    array = max(array)
    return array


```

iii) # To find the maximum marks without using builtin functions.
```
#Developed By: Murali Krishna S
#Register number : 212223230129

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
        

```



## Output:
![image](https://github.com/Murali-Krishna0/FindMaximum/assets/149054535/e5db10dd-1fcb-45e0-bb32-2f28e59ff017)
![image](https://github.com/Murali-Krishna0/FindMaximum/assets/149054535/5d4e6ae9-0b9f-4caf-9ba0-af94ac69e1e0)
![image](https://github.com/Murali-Krishna0/FindMaximum/assets/149054535/3ff2fe3c-7fd7-4edc-9770-1ad67dd0c2ff)
![image](https://github.com/Murali-Krishna0/FindMaximum/assets/149054535/bcd4d89c-89c4-493d-8d9f-46e03a7fc344)
![image](https://github.com/Murali-Krishna0/FindMaximum/assets/149054535/dd665d88-c02b-450b-9448-e33ed37abf77)
![image](https://github.com/Murali-Krishna0/FindMaximum/assets/149054535/a8dc2ddd-8fd1-489a-b0a3-182e3aff0600)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
