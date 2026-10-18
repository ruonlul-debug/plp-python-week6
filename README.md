# plp-python-week6

## Files
- **safe_tools.py**: Contains error-handling functions (`safe_divide`, `safe_number`, and `get_field`) using `try` and `except` blocks to prevent program crashes.

## Reflection
**Why can the `if` check not catch `"abc"` on its own?**
An `if` check relies on pre-determining the condition or type before an operation, but in Python, converting a random string like `"abc"` into an integer using `int()` raises a runtime exception (`ValueError`) rather than failing a conditional check beforehand. The `try/except` block lets Python attempt the operation and cleanly catch the resulting error if the input format is invalid.
