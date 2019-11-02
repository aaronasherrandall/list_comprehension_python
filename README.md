# list_comprehension_python
Very simple example of list comprehension in python using a for loop. Note, the word "array" is used instead of "list" for ease of understanding - python does not use arays, but lists instead.

Let's say we want to initialize and emtpy array ```y``` that will be populated by data which is derived from another array ```x``` via some operator.

First we can initialize our array of known data ```x``` along with an empty array which will be modified later ```y```

```Python
x = [1,2,3,4,5]
y = []
```

We can then use **list comprehension** and a ```for loop``` to iterate over every item in the list ```x``` and perform some operation to it. In this case, we simply multiply by 2. Then, we can populate our empty list ```y``` with the new values using the ```.append``` method:
```Python
for i in x:
    y.append(i * 2)
```
```Python
print(y)
```

Output
```
[2, 4, 6, 8, 10]
```
