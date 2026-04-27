# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

## 🎯 Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---


## 🧪 Program
```py

def wrap(text, width):
    result = []
    for i in range(0, len(text), width):
        result.append(text[i:i+width])
    return '\n'.join(result)

print(wrap(input(), int(input())))
```
## Output

<img width="942" height="299" alt="447826553-462faa14-fa4e-4589-a34a-b22c5b16d6d0" src="https://github.com/user-attachments/assets/380f4114-75f4-4d37-ac5a-eb4f59869eca" />

## Result
Thus, the program has been successfully executed.
