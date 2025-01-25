# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that incorrectly iterates over an array, leading to this exception.  The `bugSolution.java` file provides the corrected code.

**How to Reproduce:**

1. Compile and run `bug.java`. You'll observe an `ArrayIndexOutOfBoundsException`.
2. Compile and run `bugSolution.java`.  This version correctly iterates and avoids the exception.

This example showcases the importance of carefully checking loop conditions when working with arrays in Java.  Off-by-one errors are a frequent cause of this type of exception.