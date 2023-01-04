# Python for Beginners

Python is a popular, easy-to-learn, and very powerful programming language, which is used in software and web development, data science, machine learning, and many other fields. In this course, we’ll cover the basic concepts of Python, as well as build real-life projects and solve different coding challenges. Python for Beginners requires no prior programming experience, so let’s dive right in!

## Basic Concepts

### 1.1 Lesson
#### Introduction

Welcome to Python!\
Want to build a slick website? Develop a video game? Or maybe create an artificial intelligence? Python’s got you covered, and then some. Python is a high-level programming language, with a ton of applications.
It’s seriously flexible and accessible, which makes it popular with some of the world's biggest (and coolest) organizations–think Google, NASA, Disney...*whispers* even the CIA.
In this course, we’ll cover the basic concepts of Python, as well as build real-life projects and solve different coding challenges!

> We will be learning **Python version 3**, which is the most recent major version of Python.

### 2.1 Lesson
#### Hello World

Let's kick things off by creating a simple program that displays the text "Hello world!".
In Python, we use the **print** function to output text.
So to generate our message, the code would look like this:
``` Python
print('Hello world!')
```

Nice work! You’ve just written your first Python program. Easy, right? You’ll be triggering the singularity in no time!

> The **print** statement is always followed by parentheses containing the output we want to generate.

Drag & drop the correct option to output "Learning Python"
 ('Learning Python')
print
output
write

#### Printing Text

More to say? Of course you do!
You can use the print statement to output multiple lines of text.

For Example:
``` Python
print('Hello world!')
print('Hello world!')
print('Spam and eggs...')
```

Each print statement will output its text on a new line.

> Python code contains lots of references to **Monty Python**. So you’ll see "spam" and "eggs" used as placeholder variables.

Rearrange the code to generate the following output:
A
B
C

### 3.1 Lesson
#### Simple Operations

So Python can spell, but can it count? Let’s talk about calculations.
Doing a calculation in Python is simple, just enter it into the print statement (don’t forget the parentheses!):
``` Python
print(2 + 2)
print(5 + 4 - 3)
```

> See the spaces around the plus and minus signs? The code would work without them–but they make it a lot easier to read.

What does this code output?
``` Python
print(1 + 2 + 3)
```

Multiplication and division in Python are also pretty simple. We use an __asterisk *__ to multiply and a forward slash / to divide.
Again, we just enter it straight into the print statement. Like this:
``` Python
print(10 / 2)
```

Just like in regular math, we can use **parentheses** to indicate the operations we want performed first (but we still need to include the ones around the statement too!). Like this:
``` Python
print(2 * (3 + 4))
```

> Using a single slash to divide numbers produces a decimal (or **float**, as it’s known in programming). We'll dive into **floats** in the next lesson.

Which option is the output of this code?
``` Python
print((4 + 8) / 2)
```

### 3.2 Pratice
#### Time is precious!

Ever wondered how many seconds are there in a month (30 days)?
Write a program to calculate and output the answer.

> Remember, there are 24 hours in a day, 60 minutes in an hour and 60 seconds in a minute.\
Use the print() statement to output the result.

#Your code goes here
#Seconds in 30 days

### 4.1 Lesson
#### Data Types

Before we go any further, it’s a good idea to introduce the main types of data that we use in Python. Each value in Python has a **type**.

Text, like "Hello world", is called a **string**.
Whole numbers are called **integers**.
And numbers with a decimal point are called **floats**.

Now, we’ve already encountered strings and integers, so you know what that means...Time to float!

> Some examples of numbers that are represented as floats are 0.5 and -7.8237591.

Which of these will be stored as a float?
42
"hey"
7.4

#### Floats

So we know what **floats** are, they’re numbers with a decimal, but how do we produce them?

Well, we can produce a float by dividing any two integers.
Or we can also run an operation on two floats, or on a float and an integer.

Like this:
``` Python
print(8 / 2)
print(6 * 7.0)
print(4 + 1.65)
```

> A float can be added to an integer, because Python automatically converts the integer to a float. Clever Python!

What is the output of this code?
``` Python
print(1 + 2 + 3 + 4.0 + 5)
```
14.0
15.0
15
13