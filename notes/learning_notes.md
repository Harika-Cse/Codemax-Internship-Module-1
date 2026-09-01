# CODEMAX INTERNSHIP

## Module 1 – Introduction to AI & Python

### Learning Notes

---

# 1. Introduction to Artificial Intelligence

## What is Artificial Intelligence?

Artificial Intelligence (AI) is a branch of computer science that focuses on creating machines and computer systems that can perform tasks that normally require human intelligence.

AI systems can learn from information, recognize patterns, understand language, make decisions, and solve problems.

### Examples of AI

* Voice assistants such as Siri and Alexa
* Chatbots
* Face recognition
* Self-driving vehicles
* Recommendation systems
* Medical diagnosis systems
* Fraud detection systems
* Image and speech recognition

### Main Goals of AI

The main goals of AI are:

1. To make machines intelligent.
2. To solve complex problems.
3. To automate repetitive tasks.
4. To help humans make better decisions.
5. To enable machines to learn from data.

---

# 2. What is Machine Learning?

Machine Learning (ML) is a subset of Artificial Intelligence.

It allows computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every situation.

### Simple Example

Suppose we provide a machine learning system with many emails labeled:

* Spam
* Not Spam

The system studies the patterns in the emails. Later, when it receives a new email, it can predict whether the email is spam or not.

### Basic Machine Learning Process

```text
Collect Data
     ↓
Clean Data
     ↓
Train Model
     ↓
Test Model
     ↓
Make Predictions
```

### Types of Machine Learning

1. **Supervised Learning**

   * Uses labeled data.
   * Example: Predicting house prices.

2. **Unsupervised Learning**

   * Uses unlabeled data.
   * Example: Grouping customers based on their behavior.

3. **Reinforcement Learning**

   * Learns through rewards and penalties.
   * Example: Training an AI agent to play a game.

---

# 3. What is Deep Learning?

Deep Learning is a subset of Machine Learning.

It uses artificial neural networks with multiple layers to learn complex patterns from large amounts of data.

Deep Learning is inspired by the way the human brain processes information.

### Neural Network

A neural network contains connected units called neurons.

A simple structure is:

```text
Input Layer
     ↓
Hidden Layer
     ↓
Hidden Layer
     ↓
Output Layer
```

### Applications of Deep Learning

* Image recognition
* Speech recognition
* Natural language processing
* Self-driving vehicles
* Face recognition
* Medical image analysis
* Generative AI

### Example

A deep learning model can be trained using thousands of pictures of cats and dogs. After learning their patterns, it can classify a new image as either a cat or a dog.

---

# 4. AI vs ML vs Deep Learning

AI, Machine Learning, and Deep Learning are related concepts.

```text
Artificial Intelligence
        │
        └── Machine Learning
                │
                └── Deep Learning
```

### Artificial Intelligence

AI is the broad field of creating machines that can perform tasks requiring human-like intelligence.

### Machine Learning

ML is a method of achieving AI by allowing machines to learn patterns from data.

### Deep Learning

DL is a type of ML that uses multi-layer neural networks to learn complex patterns.

### Comparison

| Feature          | AI                                  | Machine Learning      | Deep Learning                        |
| ---------------- | ----------------------------------- | --------------------- | ------------------------------------ |
| Meaning          | Broad field of intelligent machines | Learning from data    | Learning using deep neural networks  |
| Relationship     | Main field                          | Subset of AI          | Subset of ML                         |
| Data requirement | Can vary                            | Usually requires data | Often requires large amounts of data |
| Example          | AI assistant                        | Spam detection        | Image recognition                    |
| Technique        | Rules, ML, reasoning, etc.          | Algorithms            | Neural networks                      |

### Easy way to remember

**AI → ML → DL**

AI is the broadest concept, ML is a part of AI, and DL is a part of ML.

---

# 5. Real-World Applications of AI

Artificial Intelligence is used in many industries.

### 1. Healthcare

AI can help analyze medical images, predict diseases, and assist doctors in decision-making.

### 2. Banking

AI is used for fraud detection, risk analysis, and customer support.

### 3. Education

AI can provide personalized learning, automated evaluation, and educational chatbots.

### 4. E-Commerce

AI recommends products based on a user's interests and previous activities.

### 5. Transportation

AI is used in navigation systems, traffic prediction, and autonomous vehicles.

### 6. Agriculture

AI can help monitor crops, detect diseases, and predict agricultural conditions.

### 7. Entertainment

Streaming platforms use AI to recommend movies, shows, and music.

### 8. Security

AI can be used for face recognition, anomaly detection, and cybersecurity.

### 9. Customer Service

AI chatbots can answer questions and provide customer support.

### 10. Manufacturing

AI can help with quality inspection, predictive maintenance, and automation.

---

# 6. Introduction to Python

Python is a high-level, general-purpose programming language.

It is popular because its syntax is simple and easy to understand.

Python is widely used in:

* Artificial Intelligence
* Machine Learning
* Data Science
* Web Development
* Automation
* Software Development
* Cybersecurity

### Advantages of Python

1. Easy to learn.
2. Simple syntax.
3. Large number of libraries.
4. Open-source.
5. Large developer community.
6. Widely used in AI and Machine Learning.

### Example

```python
print("Hello World")
```

Output:

```text
Hello World
```

---

# 7. Python Variables

A variable is a name used to store a value in a program.

### Example

```python
name = "Harika"
age = 21
marks = 85.5
```

Here:

* `name` stores a string.
* `age` stores an integer.
* `marks` stores a floating-point value.

### Rules for Naming Variables

* Variable names can contain letters, numbers, and underscores.
* A variable name cannot start with a number.
* Variable names are case-sensitive.
* Python keywords cannot be used as variable names.

### Example

```python
student_name = "Harika"
student_age = 21
```

---

# 8. Python Data Types

A data type defines the type of value stored in a variable.

### Common Python Data Types

| Data Type | Description             | Example              |
| --------- | ----------------------- | -------------------- |
| int       | Integer numbers         | `10`                 |
| float     | Decimal numbers         | `10.5`               |
| str       | Text                    | `"Hello"`            |
| bool      | True or False           | `True`               |
| list      | Collection of values    | `[1, 2, 3]`          |
| tuple     | Ordered collection      | `(1, 2, 3)`          |
| set       | Unordered unique values | `{1, 2, 3}`          |
| dict      | Key-value pairs         | `{"name": "Harika"}` |

### Example

```python
age = 21
height = 5.6
name = "Harika"
is_student = True
```

The `type()` function can be used to check the data type.

```python
age = 21
print(type(age))
```

Output:

```text
<class 'int'>
```

---

# 9. Input and Output

Python uses `input()` to receive information from the user.

### Taking Input

```python
name = input("Enter your name: ")
print(name)
```

### Output

The `print()` function is used to display information.

```python
print("Welcome to Python")
```

### Numeric Input

The `input()` function normally returns a string, so we can convert it to an integer using `int()`.

```python
age = int(input("Enter your age: "))
print("Age =", age)
```

### Example

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Sum =", a + b)
```

---

# 10. Operators

Operators are symbols used to perform operations on values.

## Arithmetic Operators

| Operator | Meaning        | Example   |
| -------- | -------------- | --------- |
| `+`      | Addition       | `10 + 5`  |
| `-`      | Subtraction    | `10 - 5`  |
| `*`      | Multiplication | `10 * 5`  |
| `/`      | Division       | `10 / 5`  |
| `%`      | Modulus        | `10 % 3`  |
| `**`     | Exponent       | `2 ** 3`  |
| `//`     | Floor division | `10 // 3` |

### Example

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
```

## Comparison Operators

These operators compare two values.

```text
==    Equal to
!=    Not equal to
>     Greater than
<     Less than
>=    Greater than or equal to
<=    Less than or equal to
```

Example:

```python
a = 10
b = 5

print(a > b)
```

Output:

```text
True
```

## Logical Operators

Python provides:

* `and`
* `or`
* `not`

Example:

```python
age = 20

print(age >= 18 and age <= 60)
```

---

# 11. Conditional Statements

Conditional statements are used to make decisions in a program.

Python mainly uses:

* `if`
* `elif`
* `else`

### if Statement

```python
age = 20

if age >= 18:
    print("Eligible to vote")
```

### if-else Statement

```python
number = 10

if number % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### if-elif-else Statement

```python
marks = 85

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
```

Indentation is very important in Python because it defines blocks of code.

---

# 12. Loops

Loops are used to execute a block of code repeatedly.

Python mainly provides:

1. `for` loop
2. `while` loop

## For Loop

A `for` loop is commonly used when we know the range or sequence of values.

```python
for i in range(1, 6):
    print(i)
```

Output:

```text
1
2
3
4
5
```

## While Loop

A `while` loop executes as long as a condition is true.

```python
i = 1

while i <= 5:
    print(i)
    i += 1
```

Output:

```text
1
2
3
4
5
```

### Loop Control Statements

Python provides:

* `break` – stops the loop.
* `continue` – skips the current iteration.
* `pass` – does nothing and acts as a placeholder.

---

# 13. Lists

A list is a collection that can store multiple values.

Lists are:

* Ordered
* Changeable
* Able to contain duplicate values

### Creating a List

```python
numbers = [10, 20, 30, 40, 50]
```

### Accessing Elements

```python
print(numbers[0])
print(numbers[2])
```

Output:

```text
10
30
```

Python uses zero-based indexing, meaning the first element has index `0`.

### Adding an Element

```python
numbers.append(60)
```

### Removing an Element

```python
numbers.remove(20)
```

### Finding Length

```python
print(len(numbers))
```

### Loop Through a List

```python
numbers = [10, 20, 30, 40]

for number in numbers:
    print(number)
```

---

# 14. Functions

A function is a reusable block of code designed to perform a specific task.

Functions help make programs:

* Reusable
* Organized
* Easier to understand
* Easier to maintain

### Creating a Function

```python
def greet():
    print("Hello!")

greet()
```

### Function with Parameters

```python
def add(a, b):
    return a + b

result = add(10, 20)

print(result)
```

Output:

```text
30
```

### Function Structure

```python
def function_name(parameters):
    # statements
    return result
```

---

# 15. Beginner Python Programs

## Program 1 – Hello World

```python
print("Hello World")
```

### Output

```text
Hello World
```

---

## Program 2 – Add Two Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Sum =", a + b)
```

---

## Program 3 – Check Even or Odd

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print("Even")
else:
    print("Odd")
```

---

## Program 4 – Find Largest of Two Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

if a > b:
    print("Largest =", a)
else:
    print("Largest =", b)
```

---

## Program 5 – Multiplication Table

```python
number = int(input("Enter a number: "))

for i in range(1, 11):
    print(number, "*", i, "=", number * i)
```

---

## Program 6 – Sum of Numbers from 1 to N

```python
n = int(input("Enter a number: "))

total = 0

for i in range(1, n + 1):
    total += i

print("Sum =", total)
```

---

## Program 7 – Count Vowels in a String

```python
text = input("Enter a string: ")

count = 0

for character in text:
    if character.lower() in "aeiou":
        count += 1

print("Number of vowels =", count)
```

---

## Program 8 – Simple Calculator

```python
a = float(input("Enter first number: "))
operator = input("Enter operator (+, -, *, /): ")
b = float(input("Enter second number: "))

if operator == "+":
    print("Result =", a + b)
elif operator == "-":
    print("Result =", a - b)
elif operator == "*":
    print("Result =", a * b)
elif operator == "/":
    if b != 0:
        print("Result =", a / b)
    else:
        print("Cannot divide by zero")
else:
    print("Invalid operator")
```

---

# 16. Learning Summary

In this module, I learned the fundamentals of Artificial Intelligence and Python programming.

I learned that Artificial Intelligence focuses on creating intelligent systems, while Machine Learning allows computers to learn patterns from data. Deep Learning is a subset of Machine Learning that uses multi-layer neural networks.

I also explored several real-world applications of AI, including healthcare, banking, education, transportation, agriculture, security, and customer service.

In Python, I learned about variables, data types, input and output, operators, conditional statements, loops, lists, and functions.

I also practiced writing beginner-level Python programs such as adding numbers, checking even or odd numbers, finding the largest number, generating multiplication tables, calculating sums, counting vowels, and creating a simple calculator.

### Key Learning Outcomes

After completing this module, I am able to:

* Explain the basic concepts of Artificial Intelligence.
* Differentiate between AI, Machine Learning, and Deep Learning.
* Identify real-world applications of AI.
* Understand Python fundamentals.
* Create and use variables.
* Work with different Python data types.
* Take input and display output.
* Use arithmetic, comparison, and logical operators.
* Implement conditional statements.
* Use `for` and `while` loops.
* Create and manipulate lists.
* Define and use functions.
* Write basic Python programs.
