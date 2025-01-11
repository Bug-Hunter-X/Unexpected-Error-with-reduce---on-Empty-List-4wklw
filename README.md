# Dart reduce() Error with Empty List

This repository demonstrates an uncommon error that can occur when using the `reduce()` method in Dart with an empty list.  The `reduce()` method requires at least one element to perform the reduction; otherwise, it throws a `StateError`.

The `bug.dart` file shows the problematic code, and `bugSolution.dart` provides a solution using a check for an empty list.