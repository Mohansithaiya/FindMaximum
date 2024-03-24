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
    sorted_marks = sorted(marks)
    return sorted_marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(m):
    large=max(m)
    return large
    
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```



## Output:

![Screenshot 2024-03-24 185439](https://github.com/Mohansithaiya/FindMaximum/assets/154211682/e1d2da42-765e-4f17-ac78-36dbb1a1adbf)
**![Screenshot 2024-03-24 185500](https://github.com/Mohansithaiya/FindMaximum/assets/154211682/da6fadcf-c8ab-48b5-8806-6ef1bfbc7688)
**![Screenshot 2024-03-24 185519](https://github.com/Mohansithaiya/FindMaximum/assets/154211682/2ba6562f-9c89-4e29-95c8-f84127842187)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
