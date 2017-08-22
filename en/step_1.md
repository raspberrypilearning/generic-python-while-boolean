The purpose of a **while** loop is to repeat code over and over while a condition is `True`. This is why while loops are sometimes referred to as **condition-controlled** loops.

In this example, the condition is a boolean variable we gave the name `keep_looping`. Its value is set as `True` at the top. The value can become `False`, which will make the condition of the while loop `False`. When this happens, the loop stops running.

```python
keep_looping = True

while keep_looping:
    print("I am in a loop")
    command = input("Shall I keep looping?")
    if command == "no":
        keep_looping = False
```

This kind of loop is useful in situations where you want to repeat code until a specific event happens. For example, you may want a program to continue running until someone types something to tell it to quit.
