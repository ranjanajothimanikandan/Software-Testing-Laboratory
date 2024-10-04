# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
1.do…while
```
def display():
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
while True:
start=int(start)
end=int(end)
print(start,end=‘ ‘)
if start<end:
start+=1
else:
break
else:
print("Enter a valid positive number.")display()
```
2.while…do
```
start=input("Enter a positive value for START: ")end=input("Enter
a positive value for END: ")
if start.isnumeric() and end.isnumeric():
start=int(start)
end=int(end)
while start<end:
print(start)
start+=1
else:
print("Enter a valid positive number.")
```












### Output:
![Screenshot (225)](https://github.com/user-attachments/assets/e385faac-6515-4238-b388-5b0798a8976a)
![Screenshot (226)](https://github.com/user-attachments/assets/c12af2dc-699d-450c-93a6-916b8eac90a0)







### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


