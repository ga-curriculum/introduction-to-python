# ![Introduction to Python - Changing Data Types](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to identify data types using the `type()` function, perform type casting to convert variables between compatible data types, and troubleshoot common type-related errors in Python code.

# Changing Data Types (30 min)

## You’re Just Not My `type()`

One significant cause of errors in Python occurs when you’re trying to perform an operation on variables of different types:

```python
2 + "apple"

# This will give you an unsupported operand error!
```

If you’re unsure what data type a variable contains, you can use the `type()` function to investigate, especially in combination with `print()`.

```python
print( type(mystery_variable) )
```

> 🍎 Using `type()` and `print()` helps identify data types and avoid type errors.

---

## ...But I Can Change!

We can overcome incompatible data types by **type casting** or changing the data type of a variable:

```python
str(2) + "apple"

# This turns 2 into a string
```

This technique has its limits, however. If we tried converting `"apple"` to an integer, we’d get another error as that just doesn’t make sense.

> 🍎 Type casting allows conversion between compatible data types.

---

## Discussion: Compatible Types TKTK

Of the four data types we’ve learned so far, **which do you think can be converted into each other and which cannot?**

- Strings
- Integers
- Floats
- Booleans

![Question Mark Image]()TKTK

---

## Solo Exercise: 1.5 Code Fast and Break Things (15 min) TKTK

Dealing with errors is part of everyday life in Python. Let’s explore some common mistakes in Section 1.5 of the Jupyter Notebook.

![Exclamation Mark Image]()TKTK

---

## Group Exercise: 1.6 How Many Ways to Print With Variables? (15 min) TKTK

Researching how to do something new is an irreplaceable skill in programming. Even if you don’t totally understand what’s going on, you still need to be able to find code snippets in documentation and use them to solve problems!

Section 1.6 of the Jupyter Notebook challenges us to find four distinct methods of achieving the same objective — save us, Stack Overflow!

> 🍎 This exercise emphasizes the importance of research in programming. Complete this exercise as homework if needed.

---
