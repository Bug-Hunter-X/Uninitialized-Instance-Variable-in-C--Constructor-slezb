# Uninitialized Instance Variable in C# Constructor

This example demonstrates a common error in C#: forgetting to initialize instance variables within a class constructor.  Uninitialized variables can result in unpredictable program behavior, such as exceptions or incorrect calculations.

**Bug:** The `MyProperty` variable in `MyClass` is declared but not initialized in the constructor.  Accessing this variable before assignment will lead to undefined values.

**Solution:**  Initialize `MyProperty` to a default value (0 in this case) within the constructor to avoid this issue.
