# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
n={'b':2,'a':1,'c':3}
m=dict(sorted(n.items()))
o=dict(sorted(n.items(),key=lambda item: item[1]))
print("Original Dictionary:",n)
print("Sorted by Keys:",m)
print("Sorted by Values:",o)
```
## Sample Output
<img width="1034" height="528" alt="Screenshot 2025-10-19 000620" src="https://github.com/user-attachments/assets/5ed838a4-53fc-42a2-9a26-0319ac9ac428" />

## Result
The Dictionary-Python Program to Sort a Dictionary by Keys and Values is executed successfully.

