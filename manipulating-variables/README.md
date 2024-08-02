<div id="hero">
  <h1>
    <span class="headline">Introduction to Python</span>
    <span class="subhead">Manipulating Variables</span>
  </h1>
</div>

**Learning objective:** By the end of this lesson, students will be able to use various operators to manipulate variable values, perform string concatenation and interpolation, update variables dynamically, and understand the importance of using comments to document their code effectively.

## Manipulating Variables (25 min)

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

There’s a good chance that our first solution will end up being:

`"grapefruitsparkling water"`

How can we fix that awkward combination of words?

```python
beverage_type = "sparkling water"

flavor = "grapefruit"
```

> 🍎 Think about adding a space in the middle as a separate string, not stored in any variable. There are multiple solutions.

```python
favorite_drink = flavor + " " + beverage_type
```

---

## Concatenation vs. String Interpolation

You can imagine that concatenating multiple strings might result in some complex, hard-to-read statements.

However, Python provides another way to directly inject, or **_interpolate_**, a variable directly into a string using `f-strings`.

```python
greeting = "Hello there"

person = "Professor Park"

message = f"{greeting}, {person}."
```

When the f is placed directly before a string's opening quote (single or double), it makes a "formatted string" or _f-string_ for short.

The message variable equates to:

```python
Hello there, Professor Park.
```

> 🍎 F-strings make your code cleaner and easier to read.

---

## Math operations

Python also has several math operators.

All work as you would expect. However, there are a few special operations worth mentioning.

### Integer division

By default, when you divide two numbers (whether they are ints, floats, or a combination of the two), the result is a float, even if there is no remainder:

```python
result = 4 / 2

print(result)

# prints: 2.0
```

You're able to force the result of division to an integer by using `//` instead of `/`:

```python
result = 4 // 2

print(result)

# prints: 2 because the decimal ".0" is truncated
```

Everything after the decimal is removed.

---

## Shortcut Assignment Operators

Reassigning the result of an operation on a variable to the same variable is common. It is so common that several shortcut operators exist to make these types of operations easier to write.

Examples

```python
# this line of code:
num = num + 1
# can be written with this shortcut operator:
num += 1

# it also works for any of the other math operations:
num = num / 5
# can be rewritten like this:
num /= 5

# this:
num = num * 3
# can be rewritten like this:
num *= 3
```

## A Quick Comment on Comments

You’ve also seen that our Jupyter Notebook contains some lines of text that start with a hashtag (#). These are known as comments.

**Comments** are used to provide explanations and guidance throughout a program; Python will not try to execute these as code.

Single-line comments in Python start with the `#` character and continue to the end of the line.

```python
# This is a comment and will not cause errors!
```

To make multiline comments, use three quotes (either as """ double quotes or ''' single quotes) wrapped around your comments, or use the # character at the start of each line:

```python
"""
this is a
multiline comment
"""

'''
this is also a multiline comment
you can use either set of quotes
'''

# this is a
# multiline comment
```

Multiline comments are often used to document what a function or module does; therefore, they are sometimes referred to as _docstrings_.

> 🍎 Comments are crucial for understanding and maintaining code.
> Well-commented code makes life easier for anyone reading your programs in the future, including yourself!
> There will be times when you have to return to your old code and you’ll have no idea how it works or why you wrote it the way you did unless you added comments at the time.

---

## Solo Exercise: 1.3 Operators and Updating Variables (10 min) TKTK

Let’s practice with a birthday calculator trick in the Jupyter Notebook by following the instructions in the comments.

![Calculator Image]() TKTK

> 🍎 Use this exercise to solidify your understanding of operators and variable re-assignment.

---

## Printing to the Console

We’ve seen a few examples using the `print()` function so far. The `print()` function is an important tool for debugging by displaying variable values in the `console`.

If something isn’t working, we can always use some `print()` statements to investigate whether or not our variables contain the values we expect.

```python
print(favorite_drink)
```

---

## Group Exercise: 1.4 Python Mad Libs (10 min) TKTK

In this exercise, we’ll practice combining strings together and including variables in string messages.

![Paper and Pen Image]() TKTK
