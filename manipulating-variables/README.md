# ![Introduction to Python - Manipulating Variables](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to use various operators to manipulate variable values, perform string concatenation and interpolation, update variables dynamically, and understand the importance of using comments to document their code effectively.

# Manipulating Variables (25 min)

## Operators

We've seen the **assignment operator** in action, but there are other operators that can modify variable values:

| Symbol | Name           | Explanation                                                |
| ------ | -------------- | ---------------------------------------------------------- |
| `+`    | Addition       | Adds numbers or strings.                                   |
| `-`    | Subtraction    | Subtracts numbers.                                         |
| `*`    | Multiplication | Multiplies numbers or strings.                             |
| `/`    | Division       | Divides numbers.                                           |
| `%`    | Modulus        | Produces the remainder from division.                      |
| `**`   | Exponent       | Raises the first number to the power of the second number. |

> 🍎 Understanding these operators is crucial for manipulating variable values effectively.

---

## Concatenating Strings

You may have noticed that some of the operators, especially the addition operator, work on strings as well as numbers.

Adding two or more strings together is called **concatenation**.

```python
beverage_type = "sparkling water"
flavor = "grapefruit"
favorite_drink = flavor + beverage_type
```

---

## Discussion: A Problem With Concatenation TKTK

How could we concatenate these two variables into a single variable named `favorite_drink`?

```python
beverage_type = "sparkling water"
flavor = "grapefruit"
```

There’s a good chance that our first solution will end up being `"grapefruitsparkling water"`. How can we fix that awkward combination of words?

> 🍎 Think about adding a space in the middle as a separate string, not stored in any variable. There are multiple solutions.

---

## Concatenation vs. String Interpolation

You can imagine that concatenating multiple strings might result in some complex, hard-to-read statements. However, Python provides a way to directly inject, or **interpolate**, a variable directly into a string using `f-strings`.

```python
greeting = "Hello there"
person = "Professor Park"
message = f"{greeting} {person}."
```

The message variable equates to **“Hello there, Professor Park.”**

> 🍎 F-strings make your code cleaner and easier to read.

---

## Updating Variables

Variables wouldn’t be very useful if their values couldn’t vary or change. You can use the assignment operator to re-assign values to an existing variable.

```python
favorite_language = "SQL"
favorite_language = "python"
```

You can even use the previous value when re-assigning!

```python
my_current_age = my_current_age + 1
```

> 🍎 Use re-assignment to update variables dynamically based on program logic.

---

## A Quick Comment on Comments

You’ve also seen that our Jupyter Notebook contains some lines of text that start with a hashtag (#). These are known as comments.

**Comments** are used to provide explanations and guidance throughout a program; Python will not try to execute these as code.

```python
# This is a comment and will not cause errors!
```

> 🍎 Comments are crucial for understanding and maintaining code.
> Well-commented code makes life easier for anyone reading your programs in the future, including yourself! 
> There will be times when you have to return to your old code and you’ll have no idea how it works or why you wrote it the way you did unless you added comments at the time.

---

## Solo Exercise: 1.3 Operators and Updating Variables (10 min) TKTK

Let’s practice with a birthday calculator trick in the Jupyter Notebook by following the instructions in the comments.

![Calculator Image]()TKTK

> 🍎 Use this exercise to solidify your understanding of operators and variable re-assignment.

---

## All the Values That Are Fit to `print()`

We’ve seen a few examples using the `print()` function so far. The `print()` function is an important tool for debugging by displaying variable values in the console.

If something isn’t working, we can always use some `print()` statements to investigate whether or not our variables contain the values we expect.

```python
print(favorite_drink)
```

> 🍎 `print()` helps in debugging by displaying variable values in the console.

---

## Group Exercise: 1.4 Python Mad Libs (10 min) TKTK

In this exercise, we’ll practice combining strings together and including variables in string messages.

![Paper and Pen Image]()TKTK
