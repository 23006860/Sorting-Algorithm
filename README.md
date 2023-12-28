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
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: RAHUL.V
RegisterNumber: 23006860
'''
def selection_sort(array,size):
    for ind in range(size):
        min_index= ind
        for j in range(ind+1,size):
            if array[j] < array[min_index]:
               min_index=j
        (array[ind],array[min_index]) = (array[min_index],array[ind])
arr = eval(input())
size=len(arr)
selection_sort(arr,size)
print(arr)

```
ii)	#Insertion Sort
```
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: RAHUL.V
RegisterNumber: 23006860
'''
def selection_sort(array,size):
    for ind in range(size):
        min_index= ind
        for j in range(ind+1,size):
            if array[j] < array[min_index]:
               min_index=j
        (array[ind],array[min_index]) = (array[min_index],array[ind])
arr = eval(input())
size=len(arr)
selection_sort(arr,size)
print(arr)
```

## Output:

![Screenshot 2023-12-28 154109](https://github.com/23006860/Sorting-Algorithm/assets/139841752/81987641-2ead-49a4-b1fa-e4817ce31df0)
![Screenshot 2023-12-28 154131](https://github.com/23006860/Sorting-Algorithm/assets/139841752/41840553-f7f8-4c03-a908-7883c05f6127)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
