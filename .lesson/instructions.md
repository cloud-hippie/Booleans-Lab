# Booleans

Booleans are used to store true or false values.

They help to creat boolean expressions which can be evaluated to true or false.

Python evaluates boolean expressions to `True` or `False`.

Below a value `is_admin` is assigned to a boolean expression.

```python
is_admin = True
```

Above, the value for `is_admin` is `True`.

With this value we make a decision if we are an admin or not.

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
