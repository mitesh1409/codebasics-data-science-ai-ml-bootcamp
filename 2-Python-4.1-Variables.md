# Python > Variables

## How variables are declared?

We can directly start using variables by initializing them.
No declaration is required.

```Python
score = 150

print(score)

type(score)
```

Use `print()` function to print data on the screen.

Use `type()` function to get type of a variable.

Python is "Dynamically Typed" language.
Variables are not bound to any specific type, they can contain values of any type.

```Python
score = 200
print(score) # 200
type(score) # int

score = 'Two Hundred and Fifty'
print(score) # Two Hundred and Fifty
type(score) # str
```

> In Python, everything is an object.

Use `id()` function to get unique identifier of an object.

```Python
actor = 'Keanu Reeves'
fav_actor = actor

print(actor)
print(fav_actor)

# id of actor and fav_actor will be the same
# actor and fav_actor both point to the same object -> Keanu Reeves
id(actor)
id(fav_actor)

fav_actor = 'Tom Holland'
# id of actor and fav_actor will be different
# actor points to Keanu Reeves
# fav_actor points to Tom Holland
```
