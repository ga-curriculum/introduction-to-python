<h1>
  <span class="headline">Introduction to Python</span>
  <span class="subhead">Variables and Data Types</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create and name variables in Python, understand the rules and best practices for variable naming, and recognize and use basic data types (strings, integers, floats, and booleans) in simple Python programs.

| Lesson                   | Duration |
| ------------------------ | -------- |
| Variables and Data Types | 15 min   |

## Variables

**Variables** are names assigned to specific values or data. Python allows us to easily define and redefine variables using a simple **assignment operator** (equals sign).

```python
best_programming_language = "python"
```

![Code Image]() TKTK

> 💡 Variables are fundamental to making logical sense of how individual lines of code combine into complex programs. If we need the computer to "remember" anything, it should be a variable!

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

> 💡 Use re-assignment to update variables dynamically based on program logic.

## Restrictions on Variable Names

Variable names cannot:

- Be **just a number** (e.g., 2, 0.01, 10000).

- Be assigned the **same name** as a default or imported function (e.g., "type", "print", "for").

- Contain **spaces**.

![Brain Image]() TKTK

> 💡 Variables are case sensitive - `num` and `Num` would be two different variables.

## Naming Conventions and Best Practices

- Variable names in Python should be **lowercase**.

- A variable’s name should be **indicative of the concept it represents in your program**. Coming up with sensible variable names can take some time and thought, but this will save you a lot of confusion later on.

- If you have to include multiple words in your variable name, use an **underscore** to separate them. This is known as **snake case**.

```python
# in Python, we use snake_case
my_number = 10
```

> 💡 Coming up with sensible variable names can take some time and thought, but this will save you a lot of confusion later on.

## Primitive Data Types in Python

| Data Type | Explanation                                                 | Examples                                                        |
| --------- | ----------------------------------------------------------- | --------------------------------------------------------------- |
| String    | A collection of characters representing a text-based value. | `my_planet = "earth"`<br> `secret_password = "dN&e84$3j%dbF"`   |
| Integer   | Any whole number without decimal points.                    | `students = 11`<br> `bakers_dozen = 13`                         |
| Float     | Numbers including points after the decimal.                 | `gigawatts = 1.21` <br>`low_low_price = 1.99`                   |
| Boolean   | True or false values.                                       | `python_is_readable = True`<br> `programming_is_simple = False` |

<br>

> 💡 There are many more data types to come, but these provide the fundamental building blocks for all information stored in Python programs. Refer to [Python's built-in types documentation](https://docs.python.org/3/library/stdtypes.html) for a comprehensive list and to see the attributes and methods available to all of them.

<br>

<div class="activity knowledge-check">
  <h2 class="title">Identify the Data Types</h2>
  <span class="minutes">1 min</span>
</div>

Match each value to its correct data type:

- "Hello world"
- 6
- True
- 7.2

<br>

<div class="activity solo-exercise">
  <h2 class="title">1.2 Introduce Yourself</h2>
  <span class="minutes">10 min</span>
</div>

In Cell 1.2, we've already set up a message printed to the console. However, if we were to execute it right now, you’d see an error. To get this message to work, we have to define the following variables with string type values:

- `greeting`
- `name`
- `mood`

Don’t worry about fully understanding what we’ve done to have the message show up — we'll be covering that throughout this lesson!

> 💡 This exercise allows practice with creating variables.
