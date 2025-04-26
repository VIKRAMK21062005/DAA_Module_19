# EX 1A Reverse a String
## DATE: 
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. Read a string s from the user.
2. Define a recursive function reverse(n) to reverse the string.
3. In the base case, if the string has length ≤ 1, return it as is.
4. Otherwise, return reverse(n[1:]) + n[0] (i.e., reverse the rest and add the first character at the end).
5. Call the reverse function on s and print the result.
## Program:
```
Program to implement Reverse a String
Developed by: Vikram K
Register Number:  212222040180
```
```
def reverse(n):
    if len(n)<=1:
        return n
        
    return reverse(n[1:])+n[0]
    
s = str(input())
print(reverse(s))
```
## Output:
![image](https://github.com/user-attachments/assets/277ced46-40f5-40ca-9760-e41bdac3ca2f)
## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
