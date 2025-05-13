# EX 1A Reverse a String
## DATE:
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1.Check if the string is empty or has only one letter — if yes, return it.

2.Take the rest of the string except the first letter.

3.Call the reverse function on the smaller string.

4.Add the first letter to the end of the reversed smaller string.

5.Return the new string.

## Program:
~~~
Program to implement Reverse a String
Developed by: D Vergin Jenifer
Register Number: 212223240174

def rev_string(s):
    if len(s)==0:
        return " "
    return s[-1] + rev_string(s[:-1])
st=input()
print(rev_string(st))
 
~~~

## Output:

![image](https://github.com/user-attachments/assets/e472bde1-e068-414f-b40b-b732a7715de6)


## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
