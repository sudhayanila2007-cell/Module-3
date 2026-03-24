# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = input("Enter a string: ")

start = 0
end = len(s) - 1
is_palindrome = True

while start < end:
    if s[start] != s[end]:
        is_palindrome = False
        break
    start += 1
    end -= 1

if is_palindrome:
    print("Palindrome")
else:
    print("Not Palindrome")
```

## Output
```
madam
```
```
Palindrome
```

## Result
the code is verified.
