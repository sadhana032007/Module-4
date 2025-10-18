# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1=[1,2,3,4]
try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
print("Program executed")
```

## Output
<img width="1035" height="343" alt="Screenshot 2025-10-19 001017" src="https://github.com/user-attachments/assets/ee59ba2d-58e9-485e-9382-3019b46dc513" />

## Result
The Exception Handling in Python: Avoiding Index Errors is executed successfully.
