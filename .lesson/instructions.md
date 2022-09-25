# Booleans

Booleans are a different kind of datatype. Compared to other data types, booleans only have two values

```python
True
```
and
```python
False
```

Below a value `is_admin` is assigned to a boolean expression.

```python
is_admin = True
```

Above, the value for `is_admin` is `True`.

We can use these values to make decisions in programming though `if` statements.

```python
if is_admin:
    print("You are an admin")
else:
    print("You are not an admin")
```

We can combine values with `and` and `or` to make more complex boolean expressions.

Below we check if the user is an admin and a staff memeber.

```python
is_admin = True
is_staff = True
if is_admin and is_staff:
    print("You are an admin and a staff member")
else:
    print("You are not an admin and a staff member")
```

These values do not always have to be explicit. Let's say we want to check if the user makes over $100,000.

```python
user {
    "salary": 100000
    "is_admin": True
}
if 100000 < user["salary"]:
    print("You make over $100,000")
else:
    print("You make less than $100,000")
```

The `<` sign returns a boolean value. Here are other boolean operators: 

    `>`: greater than
    `<`: less than
    `>=`: greater than or equal to
    `<=`: less than or equal to
    `==`: equal to
    `!=`: not equal to

## Getting Started

On the left hand side of your browser, find the `main.py`.

Within this `main.py` file, you will see a function that checks for a vowel

  ```python
  def contains_letter(word, letter):
    for l in word:
        if l == letter:
            return True
    return False
```

The function checks to see if the letter is in the word you give as an argument.

If you click on the checkmark on the right hand side, you can run the tests.

The `test_contains_letter` passes on the bottom of the list of tests. The others do not pass

### Your Mission

Get the tests to pass and then submit it!

Reach out if you need help!

