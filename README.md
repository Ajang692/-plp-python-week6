# PLP Python Week 6

`safe_tools.py` - Contains three safe functions that handle division by zero, invalid numbers, and missing dictionary fields without crashing.

The `if` check cannot catch `abc` on its own because `abc` is text and must first be converted to an integer. The `int()` conversion raises a `ValueError`, so `try` and `except` are needed to handle the error safely.
