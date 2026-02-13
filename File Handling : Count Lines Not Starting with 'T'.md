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

## 🧾 Program
Add code here
```
try:
    count = 0
    with open("story.txt", "r") as file:
        for line in file:
            if not line.startswith('T'):
                count += 1
    print("Number of lines not starting with 'T':", count)
except FileNotFoundError:
    print("Error: 'story.txt' not found. Please make sure the file exists in the same folder.")


```
## Output
<img width="803" height="189" alt="image" src="https://github.com/user-attachments/assets/a5979334-ffa7-4ff5-82d6-5c3a184a2e47" />

## Result
The program successfully reads a text file and counts the number of lines that do not begin with the letter 'T', demonstrating basic file handling and conditional checks in Python.
