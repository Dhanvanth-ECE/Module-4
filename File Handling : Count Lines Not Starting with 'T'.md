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
```p
count = 0

with open("story.txt", "r") as f:
    for line in f:
        if line[0] != 'T':
            count += 1

print(count)
```
## Output
<img width="1325" height="225" alt="image" src="https://github.com/user-attachments/assets/d20dc372-a84f-4e64-8638-6f82c42fc411" />

## Result
Thus, the Python program to count the number of lines in story.txt that do not start with the letter 'T' was implemented and executed successfully.
