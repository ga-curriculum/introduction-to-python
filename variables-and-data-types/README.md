# ![Introduction to Python - Variables and Data Types](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to create and name variables in Python, understand the rules and best practices for variable naming, and recognize and use basic data types (strings, integers, floats, and booleans) in simple Python programs.

# Variables and Data Types (15 min)

## Variables

**Variables** are names assigned to specific values or data. Python allows us to easily define and redefine variables using a simple **assignment operator** (equals sign).

`best_programming_language = "python"`

> 🍎 Variables are fundamental to making logical sense of how individual lines of code combine into complex programs. If we need the computer to "remember" anything, it should be a variable!

---

## Restrictions on Variables

Variable names cannot:

- Be **just a number** (e.g., 2, 0.01, 10000).
- Be assigned the **same name** as a default or imported function (e.g., "type", "print", "for").
- Contain **spaces**.

![Brain Image]()TKTK

---

## Best Practices for Variables

- Variable names in Python should be **lowercase**.
- A variable’s name should be **indicative of the concept it represents in your program**. Coming up with sensible variable names can take some time and thought, but this will save you a lot of confusion later on.
- If you have to include multiple words in your variable name, use an **underscore** to separate them. This is known as **snake case**.

> 🍎 Coming up with sensible variable names can take some time and thought, but this will save you a lot of confusion later on.

---

## Primitive Data Types in Python

| Data Type | Explanation                                                 | Examples                                                        |
| --------- | ----------------------------------------------------------- | --------------------------------------------------------------- |
| String    | A collection of characters representing a text-based value. | `my_planet = "earth"`<br> `secret_password = "password"`        |
| Integer   | Any whole number without decimal points.                    | `heist_members = 11`<br> `bakers_dozen = 13`                    |
| Float     | Numbers including points after the decimal.                 | `gigawatts = 1.21` <br>`low_low_price = 49.99`                  |
| Boolean   | True or false values.                                       | `python_is_readable = True`<br> `programming_is_simple = False` |

<br>

> 🍎 There are more data types to come, but these provide the fundamental building blocks for all information stored in Python programs.

---

## Knowledge Check!

### Identify the Data Types

Match each value to its correct data type:

- "Hello world"
- 6
- 7.2
- True

---

## Solo Exercise: 1.2 Introduce Yourself (10 min) TKTK

In Cell 1.2, we've already set up a message printed to the console. However, if we were to execute it right now, you’d see an error. To get this message to work, we have to define the following variables with string type values:

- `greeting`
- `name`
- `mood`

Don’t worry about fully understanding what we’ve done to have the message show up — we'll be covering that throughout this lesson!

> 🍎 This exercise allows practice with creating variables.
