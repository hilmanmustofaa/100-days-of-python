## 1. Notes during the first day
- We can print a string just simply using command 
  `print("yourString")`
- A string is a sequence of characters enclosed in quotation marks. The quotation marks can be single (` ' `) or double (` “ `)
- We can use triple quotes (`""" """`) in Python to define a long string that spans multiple lines. This syntax is particularly useful when we have a string that contains multiple line breaks or special characters.

## 2. Errors
One of the most common errors when using the `print()` function in Python is the SyntaxError. This error typically occurs when there's a mistake in the syntax of the `print()` statement. Here are a few common scenarios:
- **Missing Parentheses:** # Missing parentheses`<br>
  To fix it, we need to add parentheses:<br>
  `print("Hello, World!")`
- **Mismatched Quotes:** If you're using quotes within the `print()` statement, ensure they're properly matched.<br>
  `print('Hello, World!")  # Mismatched quotes`<br>
  Fix it by using consistent quotes:<br>
  `print('Hello, World!')`
- **Incorrect Usage of Escape Characters:** Incorrectly using escape characters can lead to errors.<br>
  `print("This is a backslash: \")  # Incorrect usage of escape character`<br>
  You should either escape the backslash or use a different method:<br>
  `print("This is a backslash: \\")  # Escaping the backslash`<br>
  Or:<br>
  `print("This is a backslash: '")`<br>
- **Invalid Syntax Within the print() Statement:** Ensure that all the syntax within the `print()` statement is correct.<br>
  `print("Hello, World!"  # Missing closing parenthesis`<br>
  To fix it, we need to add the closing parenthesis:<br>
  `print("Hello, World!")`


