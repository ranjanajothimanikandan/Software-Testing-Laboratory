# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212222040131

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
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Please enter valid positive numbers.")

display()

```
2.while…do
```
start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")

```
3.Switch
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
4.If else
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")
        
compare()
```
5.For
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```












### Output:
![Screenshot (225)](https://github.com/user-attachments/assets/e385faac-6515-4238-b388-5b0798a8976a)
![Screenshot (226)](https://github.com/user-attachments/assets/c12af2dc-699d-450c-93a6-916b8eac90a0)
![Screenshot (227)](https://github.com/user-attachments/assets/104bfb3b-4639-4e56-a1cf-84946dba7096)
![Screenshot (229)](https://github.com/user-attachments/assets/53ccfa29-287a-4de9-8243-540faa6d8c08)
![Screenshot (228)](https://github.com/user-attachments/assets/c481ee72-9733-47ae-9f55-d480a680d749)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


