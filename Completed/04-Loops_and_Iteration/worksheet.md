# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` 0, 1, 2, 3, 4

1. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
# Your code:
for i in range(1, 11):
    if i != 5:
        print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:` for loops have a preset condition before they start usually, while loops continue going as long
as the condition given is true

1. What happens if a `while` loop's condition never becomes `False`?

`Answer:` the program goes on infinitely until force-stopped

---

### ✏️ Task: Countdown with While

```python
# Use a while loop to count down from 5 to 1.
num = 5
while(num > 0):
    print(num)
    num -= 1
```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:` it opens a file as a variable in the code. for example
with ('data.txt', 'r') as file
opens data.txt and assigns it to the variable file

1. How do you loop over each line in a file?

`Answer:` for line in file

---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
# Your code here
for line in file:
    if line == "error":
        print(line)
```
