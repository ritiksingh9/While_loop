# While_loop
# 🔁 While Loop in Python

## 📌 Description

A `while` loop in Python is used to repeatedly execute a block of code **as long as a given condition is true**. It is especially useful when the number of iterations is not known beforehand and depends on a condition.

---

## ⚙️ Syntax

```python
while condition:
    # code block
```

---

## 🧠 How It Works

1. The condition is evaluated first.
2. If the condition is **True**, the loop body executes.
3. After execution, the condition is checked again.
4. The loop continues until the condition becomes **False**.

---

## ✅ Example

```python
i = 1

while i <= 5:
    print(i)
    i += 1
```

### 🔹 Output

```
1
2
3
4
5
```

---

## ⚠️ Important Notes

* Always update the loop variable to avoid **infinite loops**.
* Use `break` to exit the loop early.
* Use `continue` to skip the current iteration.

---

## 🚀 Use Cases

* Repeating tasks until a condition is met
* User input validation
* Games and simulations
* Data processing loops

---

## 🎯 Conclusion

The `while` loop is a powerful control structure that allows flexible and condition-based repetition, making it essential for problem-solving in Python programming.
