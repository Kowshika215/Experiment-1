# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program

## 1.Do-while

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
        print("Enter a valid positive number.")
display()
```

## 2.While do

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
## 3.Switch

```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    n = input("Enter a value for N: ")  
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")
switch()
```
## 4.if-else

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
## 5.for
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")
iterate()
```
## Output

## 1.Do-while
<img width="547" height="142" alt="Screenshot 2025-09-01 101925" src="https://github.com/user-attachments/assets/bfa036a6-707d-4b48-a342-d0dcc534ea88" />

## 2.While do
<img width="590" height="243" alt="image" src="https://github.com/user-attachments/assets/c04b3ab0-8f64-4982-96cb-4609daaa70b5" />


## 3.Switch
<img width="517" height="107" alt="image" src="https://github.com/user-attachments/assets/047eda43-b78b-4459-b709-05963f99c4dc" />


## 4.if-else
<img width="432" height="177" alt="image" src="https://github.com/user-attachments/assets/c958809b-efe1-4b03-827e-d7a999986660" />


## 5.for
<img width="681" height="143" alt="image" src="https://github.com/user-attachments/assets/b2c8ec48-3625-4ce5-aa1a-1d6562d2cb13" />


## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



