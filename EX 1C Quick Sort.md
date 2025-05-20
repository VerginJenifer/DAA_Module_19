# EX 1C Quick Sort
## DATE:
## AIM:
To write a python program to implement quick sort using tha last element as pivot on the list of float values.

## Algorithm:

1. Choose a pivot element from the array.
2. Partition the array into two sub-arrays: elements less than pivot and elements greater than pivot.
3. Recursively apply Quick Sort to the left sub-array.
4. Recursively apply Quick Sort to the right sub-array.
5. Combine the sorted sub-arrays and pivot to form the final sorted array..

## Program:
```
/*
Program to implement implement quick sort using the last element as pivot on the list of float values.
Developed by: D Vergin Jenifer
Register Number: 212223240174
def partition(l,r,nums):
    pivot=nums[l]
    print("pivot: ",pivot)
    low=l+1
    high=r
    while True:
        while low<=high and nums[low]<=pivot:
            low+=1
        while low<=high and nums[high]>pivot:
            high-=1
        if low<=high:
            nums[low],nums[high]=nums[high],nums[low]
        else:
            break
    nums[l],nums[high]=nums[high],nums[l]
    return high
def quick_sort(l,r,nums):
    if l<r:
        pi=partition(l,r,nums)
        quick_sort(l,pi-1,nums)
        quick_sort(pi+1,r,nums)
    return nums
ex=[]
n=int(input())
for i in range(n):
    ex.append(int(input()))
print("Input List\n",ex)
quick_sort(0,len(ex)-1,ex)
print("Sorted List\n",ex)
*/
```

## Output:
![image](https://github.com/user-attachments/assets/65e95a07-58b0-463f-9d2b-bcb67267ec8c)



## Result:
The program successfully sorts the input array using the QuickSort algorithm, arranging the elements in ascending order.
