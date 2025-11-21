# 🧬 Day 01: Python Basics (Quick Reference Guide)

## 📝 Exercise 1: Conditional Logic with Multiplication & Addition

**Concept:** If-else statements with arithmetic

```python
num1 = int(input("Number1 : "))
num2 = int(input("Number2 : "))

m = num1 * num2      # Multiply
s = num1 + num2      # Add

if m > 1000:
    print("Result is: ", s)  # Print sum if product > 1000
else:
    print("Result is: ", m)  # Print product otherwise
```

💡 **Remember:** Multiply first, then decide what to print based on the product!

---

## 🔢 Exercise 2: Even or Odd Checker

**Concept:** Using modulo operator (%)

```python
n1 = int(input("Number1 : "))

if n1 % 2 == 0:
    print("Number is even.")
else:
    print("number is odd.")
```

💡 **Remember:** `n % 2 == 0` means EVEN (remainder is 0)

---

## 📊 Exercise 3: Find Average of List

**Concept:** Loop through list and calculate average

```python
arr = [1, 2, 3, 4, 5, 6, 7, 8]

sum = 0
for x in arr:
    sum += x          # Add each element

avg = sum / len(arr)  # Divide by total count
print("Sum is: ", sum)
print("Average is: ", avg)
```

💡 **Remember:** Average = Sum ÷ Count

---

## 🎤 Exercise 4: Count Vowels in Word

**Concept:** Nested loops to find matching characters

```python
word = str(input("Enter a word: "))
count = 0
vowel = 'aeiouAEIOU'

for x in word:
    for y in vowel:
        if x == y:
            count += 1

print("Number of vowels in the word is: ", count)
```

💡 **Remember:** Check each letter against all vowels!

---

## 🌡️ Exercise 5: Celsius to Fahrenheit Conversion

**Concept:** Simple temperature formula

```python
c = int(input("Enter temperature in Celsius: "))
f = (c * 9/5) + 32
print("Temperature in Fahrenheit is: ", f)
```

💡 **Remember:** °F = (°C × 9/5) + 32

---

## ⭐ Exercise 6: Print Triangle Pattern

**Concept:** Loop to print increasing pattern

```python
x = int(input("Enter a number: "))

for i in range(1, x+1):
    print("*" * i)
```

💡 **Remember:** `"*" * i` prints i asterisks in a row!

**Output Example (x=5):**

```
*
**
***
****
*****
```

---

## 🎯 Quick Tips

- 🔄 **For loops:** Use `range(start, end+1)` to include end number
- ➕ **Operators:** `+` add, `-` subtract, `*` multiply, `/` divide, `%` modulo (remainder)
- ❓ **If-else:** Test conditions with `==`, `>`, `<`, `>=`, `<=`, `!=`
- 📋 **Strings:** Use quotes for text, f-strings for variables
- 🔢 **Input:** Use `int()`, `str()`, `float()` to convert input types
