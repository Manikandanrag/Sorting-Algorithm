# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
```
''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: Manikandan
RegisterNumber: 23004754
'''
def insertion_sort(nums):
    for i in range(1,len(nums)):
        item=nums[i]
        j=i-1
        while j>=0 and nums[j]>item:
            nums[j+1]=nums[j]
            j-=1
        nums[j+1]=item
    return nums
    
list_of_nums = eval(input())
value=insertion_sort(list_of_nums)
print(value)
```
i)	#Selection Sort
```
<img width="559" alt="1" src="https://github.com/Manikandanrag/Sorting-Algorithm/assets/138849491/86a995a0-da24-474d-89fd-73ff1bc982e2">





```
ii)	#Insertion Sort
```

<img width="533" alt="2" src="https://github.com/Manikandanrag/Sorting-Algorithm/assets/138849491/d4943c9e-16fe-48b0-9fb2-307416150ac1">





```

## Output:


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
