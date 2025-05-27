# EX 1D Linear search
## DATE:
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1. Start from the first element of the list.
2. Compare each element with the target value.
3. If an element matches the target, return "Found".
4. If the end of the list is reached without a match, return "Not Found".
5. Print the result accordingly. 

## Program:
```
/*
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: D Vergin Jenifer
Register Number: 212223240174
def search(List,n):
    for i in range(len(List)):
        if List[i]==n:
            return 1
    return -1
List=[]
x=int(input())
for i in range(x):
    List.append(input())
n=input()
result=search(List,n)
if result==-1:
    print("Not Found")
else:
    print("Found")

*/
```

## Output:

![search](https://github.com/user-attachments/assets/65c3f24a-7cd2-4d9d-88a5-599e6f0310f5)


## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
