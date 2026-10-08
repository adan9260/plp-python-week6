# PLP Python Week 6

This assignment practices using `try` / `except` to handle errors safely.

* `safe_tools.py` — Contains three functions for safely handling division, number conversion, and dictionary lookups.
* `README.md` — Describes the assignment and explains why an `if` check cannot catch `abc` on its own.

The `if` check cannot catch `abc` on its own because `abc` causes a `ValueError` when Python tries to convert it to an integer with `int()`. The error happens during the conversion, so `try` / `except` is needed to catch it safely.
