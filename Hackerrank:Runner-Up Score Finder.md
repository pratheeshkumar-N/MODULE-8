# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
```py

n = int(input())
scores = sorted(set(map(int, input().split())))
print(scores[-2])
```
## OUTPUT

<img width="396" height="182" alt="447838719-6d44a408-5356-45fd-9535-cc1805cd17a1" src="https://github.com/user-attachments/assets/aab80a66-accd-41a4-8f3f-d88dea5ff1fa" />

## RESULT
Thus, the program has been successfully executed.
