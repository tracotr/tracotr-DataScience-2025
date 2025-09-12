# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` int

1. What scalar type would best represent:
   - A person's name: string
   - Their age: int
   - Whether they passed a test: bool

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool
num = 3
pi = 3.14
name = "Jaxon"
is_cool = True

print(type(num))
print(type(pi))
print(type(name))
print(type(is_cool))
```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` not equal

1. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` True

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
# Your code:
grade = 70
if grade >= 70:
   print("pass")
else:
   print("fail")
```

6. What does `elif` allow you to do?

`Answer:` have an if chain that considers eachother

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise


```python
weather = str(input("What is the weather: "))
weather = weather.lower()
print(weather)
if weather == "sunny":
   print("Bring sunscreen")
elif weather == "raining":
   print("Take an umbrella")
else:
   print("Check the forecast")
```