# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Programs
```
def pen(a):
    try:
        with open(a,"r")as file:
            count=0
            for line in file:
                if line.strip() and not line.strip().lower().startswith('t'):
                    count+=1
        print(f"Numberof lines not starting with 'T' in {a}: {count}")
    except FileNotFoundError:
        print(f"File '{a}' not found.")
    except Exeception as e:
        print(f"An error occurred: {e}")
a="story.txt"
pen(a)

```
## Output
<img width="1901" height="521" alt="Screenshot 2025-10-19 091311" src="https://github.com/user-attachments/assets/b0496e5a-50c9-4aa8-afeb-84c5dd75aa74" />

## Result
The File Handling in Python: Count Lines Not Starting with 'T' is executed successfully.
