# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE:                                                                            
### REGISTER NUMBER : 212222040131
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:

```
def Palindrome(number):
    for i in range(0, int(len(num) / 2)):
        if number[i] != number[len(number) - i - 1]:
            return False
    return True

s = input("Enter the string: ")

is_valid = True
for i in s:
    if not i.isalpha():
        is_valid = False
        break

if not is_valid:
    print("Enter a valid string")
else:
    if Palindrome(s):
        print("The given string is a palindrome")
    else:
        print("The given string is not a palindrome")
```
### Output:
![exp 6](https://github.com/user-attachments/assets/e24e8791-11e3-40e0-89d0-f51b8c069657)

### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
