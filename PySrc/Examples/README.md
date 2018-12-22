[Errors and Exceptions, Python 3.7.1 documentation](https://docs.python.org/3/tutorial/errors.html)

A `try` statement may have more than one except clause, to specify handlers for different exceptions.
- At most 1 handler will be executed.
- Handlers only handle exceptions that occur in the corresponding try clause, not in other handlers of the same `try` statement.
- An except clause may name multiple exceptions as parenthesized tuple, e.g.

