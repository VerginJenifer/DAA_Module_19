# EX 1B Merge Sort
## DATE:
## AIM:
To write a python program to sort the first half of the list using merge sort.

## Algorithm
1. Read the no. of elements and array from the user.
2. Until the elements of the array are at size one call the merge sort function recursively, this is the divide part of the function.
3. Compare the left half and right half of the list.
4. Add elements in the sorted order.
5. Print the sorted list.

## Program:
```
/*
Program to implement Merge Sort
Developed by: D Vergin Jenifer
Register Number: 212223240174
def merge_sort(inp_arr):
    if len(inp_arr)>1:
        mid=len(inp_arr)//2
        left_half=inp_arr[:mid]
        right_half=inp_arr[mid:]
        
        merge_sort(left_half)
        merge_sort(right_half)
        
        left_size=len(left_half)
        right_size=len(right_half)
        
        i = j = k = 0
        
        while i<left_size and j<right_size:
            if left_half[i]<right_half[j]:
                inp_arr[k]=left_half[i]
                i+=1
            else:
                inp_arr[k]=right_half[j]
                j+=1
            k+=1
        while i<left_size:
            inp_arr[k]=left_half[i]
            i+=1
            k+=1
        while j<right_size:
            inp_arr[k]=right_half[j]
            j+=1
            k+=1
n=int(input())
inp_arr=[]
for i in range(n):
    inp_arr.append(int(input()))
print("Input Array:\n")
print(inp_arr)
merge_sort(inp_arr)
print("Sorted Array:\n")
print(inp_arr)
*/
```

## Output:
![output](img/mergesort.png)

## Result:
The program successfully sorts the first half of the given array using merge sort. where only the first half is sorted, and the second half remains unchanged.
