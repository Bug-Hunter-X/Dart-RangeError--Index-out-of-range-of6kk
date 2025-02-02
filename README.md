# Dart RangeError: Index out of range

This repository demonstrates a common error in Dart: the `RangeError` exception caused by accessing an index outside the bounds of a list. The `bug.dart` file shows the erroneous code, while `bugSolution.dart` provides a corrected version.

The error occurs because Dart's lists are zero-indexed, meaning the first element is at index 0, the second at index 1, and so on. Attempting to access an index greater than or equal to the list's length (or less than 0) will result in a `RangeError`.  Safeguards should always be in place to avoid this.