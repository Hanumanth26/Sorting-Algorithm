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
i)	#Selection Sort
```
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by:Hanumanth rao
RegisterNumber:22005234
'''
def selection_sort(list_of_nums):
    n = len(list_of_nums)
    for i in range(n): 
        min_idx = i 
        for j in range(i+1, n): 
            if list_of_nums[min_idx] > list_of_nums[j]: 
                min_idx = j 
        list_of_nums[i], list_of_nums[min_idx] = list_of_nums[min_idx], list_of_nums[i] 
    return list_of_nums
list_of_nums = eval(input())
print(selection_sort(list_of_nums))
```
ii)	#Insertion Sort
```
''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: your name
RegisterNumber: 
'''
def selection_sort(list_of_nums):
    n = len(list_of_nums)
    for i in range(n): 
        min_idx = i 
        for j in range(i+1, n): 
            if list_of_nums[min_idx] > list_of_nums[j]: 
                min_idx = j 
        list_of_nums[i], list_of_nums[min_idx] = list_of_nums[min_idx], list_of_nums[i] 
    return list_of_nums
list_of_nums = eval(input())
print(selection_sort(list_of_nums))
```

## Output:
![Screenshot (17)](https://user-images.githubusercontent.com/121033192/214801355-cccab9ef-853f-4ee9-b9a1-94cb6b4462cf.png)

![Screenshot (16)](https://user-images.githubusercontent.com/121033192/214801161-671d098b-9957-4b7a-b8c5-ec3ddd7229f5.png)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
