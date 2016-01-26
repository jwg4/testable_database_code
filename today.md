# Injecting 'today'

How do you develop code which relies on the current date (or time) to do something, and where results will be different on different days?
This question is like a simpler version of the problems of writing code which talks to a database.
The external dependency is much easier to specify and mock than a whole database.
It is possible to, for instance, list all possible states of the external system (the date) and test against them.
Rather than do this, we will try to develop solutions which give us an indication of how we should proceed with more complicated dependencies.
