## Variables

Let's try to store some values!

Open a terminal

```shell
Windows: Click Start -> Type cmd
Mac: Open Applications folder -> Utilities folder
```

After opening the terminal/command prompt(cmd), type the following command to run the Python shell:

```shell
python
```

Type the following codes to create variables and to print their values!

```python
# Let's store values/data to variables
num = 88
dec = 99.99
is_wwc_great = True
has_forever = False
movie_title = 'superwoman'
# Let's print out their values
print(num, dec, is_wwc_great, has_forever, movie_title)
```

Magic? Nope. Let's explain what happened.

### Definition

Variables are like `containers` that allows us to store values/data.

### Data types
We have different types of data in Python! Some are:
* Integer - positive/negative whole numbers

```python
# We declare a variable named num
# We assign/store the number 88 to our variable num
num = 88
```

* Float/Decimal - positive/negative numbers with decimal

```python
# We declare a variable named dec
# We assigned a decimal value of 99.99 to dec
dec = 99.99
```

* Boolean - `True` or `False`

```python
# We declare a variable named is_wwc_great and has_forever
# We assign/store Boolean values to these
is_wwc_great = True
has_forever = False
```

* String - series of characters enclosed in single/double quotes

```python
# We declared a variable named movie_title
# We store a string value to it
movie_title = 'superwoman'
```

* Lists/Dictionaries - Meh. Just keep in mind you heard it here. We will discuss it on succeeding sessions :)

### Re-assignment
Now, let's try if we can re-assign values for these variables.

```python
num = 100
has_forever = True
print(num, has_forever)

# Let's change the value of our variable num
num = 500
print(num)

# Let's change the value of our variable has_forever
has_forever = False
print(has_forever)
```

## Arithmetic Operations

Let's try to do some arithmetic operations using Python!

Still using the Python shell, type the following codes and check their results.

```python
# Addition: result is 30
20 + 10

# Subtraction: result is 10
20 - 10

# Multiplication: result is 200
20 * 10

# Division: result is 2
20 / 10

# Floor divsion: can you explain what it's different with normal division?
9 // 2
10 // 3

# Exponent: result is 16
4 ** 2

# Modulo: can you explain what module is?
10 % 3
99 % 33
```

## Keyboard Input

Let's ask user's for an input!

Still using the Python shell, type the following codes, answer the input and see the output!

```python
name = input('Your name:')
tweet = input('Tweet your day:')
print('{} tweeted {}'.format(name, tweet))  # String formatting replaces {} with variable values
# print(f'{name} tweeted {tweet}')  # New string formatting added on Python3.6
```

### Definition
* Keyboard input will stop the program flow and asks the user for an input.
* Keyboard input has the ff. syntax: `input()`
* It can have an optional prompt string: `input('Enter your age:')`

## Challenge

Let's apply what you have learned! For this topic's challenge:

Aling Nena’s Sari-sari store wants a robot that will ask the
customer their total bill and payment amount and tell them their change
(for now, we can allow negative change). For example:

```shell
>> How much is your total bill? 150
>> How much is your payment? 200
>> Hi! Your change is 50.00
```

!> Please use below template

[filename](exercises/variables/variables01.py ':include :type=code python')

[challenge_partial](../challenge_partial.md ':include')



## Put your thinking cap on!

- Does a variable really holds values?
- How to know/print a variable's type?
- What is `floor divison`?
- What does the `modulo` operation do?
- Explain the magic of `input()`?
