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
```
f=open("story.txt","r") 
count=0 
for lines in f: 
if lines [0] not in 'T': 
count+=1 
print(count)
```

## Output


![441158420-a81bdc6c-a6eb-4b15-a5d3-2b1a17aa1505](https://github.com/user-attachments/assets/2ddb68a9-b34f-472d-b6b8-5b3b211d1ec4)

## Result
