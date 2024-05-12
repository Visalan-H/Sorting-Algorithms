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
a = eval(input())
for i in range(len(a)-1):
    s = i
    for j in range(i+1,len(a)):
        if(a[j]<a[s]):
            s = j
    a[i],a[s] = a[s],a[i]
print(a)
```
ii)	#Insertion Sort
```
a = eval(input())
lst = []
for i in range(1,len(a)):
    k = a[i]
    j = i-1
    while(j>=0 and a[j]>k):
        a[j+1] = a[j]
        j -= 1
    a[j+1] = k
print(a)
```

## Output:
### Selection Sort:
![image](https://github.com/Visalan-H/Sorting-Algorithms/assets/152077751/6ec25387-8f71-4e9a-943a-06a261648c7f)

### Insertion Sort
![image](https://github.com/Visalan-H/Sorting-Algorithms/assets/152077751/548af81d-474d-4ee7-8257-7fd49fc44957)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
