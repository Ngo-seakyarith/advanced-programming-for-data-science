# TP-01: Week 1 Class Activities and Lesson Summary

**Course:** Advanced Programming for Data Science

**Topic:** Introduction, Clean Code, PEP 8, and Debugging

## 1. Activities in Class

During the first week, our teacher asked all students to create a GitHub repository with three branches: `main`, `course`, and `tp`. This activity helped us practice organizing our course materials and practical assignments using Git and GitHub.

The teacher used slides to review programming concepts, including classes, functions, methods, and debugging. We also practiced coding in class to connect the explanations with practical examples.

The teacher selected students to answer coding questions. The question I received was: **"What is a function?"**

**My suggested answer:** A function is a reusable block of code that performs a specific task. It can accept inputs called parameters and return a result. In Python, we define a function using the `def` keyword and run it by calling its name with parentheses.

## 2. Lesson Summary

### Introduction and Programming Review

The lesson reviewed basic programming concepts that provide a foundation for more advanced work in data science:

- **Function:** A reusable block of code that performs a specific task. It can receive inputs and return a result.
- **Class:** A blueprint that groups related data and behavior together.
- **Object:** An instance of a class with its own data.
- **Method:** A function defined inside a class that describes behavior associated with the class or its objects.

The following example illustrates these concepts:

```python
class Student:
    def __init__(self, name):
        self.name = name

    def introduce(self):
        return f"Hello, my name is {self.name}."


student = Student("Alex")
print(student.introduce())
```

Here, `Student` is a class, `student` is an object, `name` is an instance attribute, and `introduce()` is a method. The `__init__()` method initializes the object's data.

### Clean Code

Clean code is easy to read, understand, and maintain. Useful practices include choosing meaningful names, keeping functions focused on one task, avoiding unnecessary repetition, and adding comments when they explain the purpose of the code.

### PEP 8

PEP 8 is the style guide for Python code. Following consistent conventions makes code easier to read and share with other people. Key guidelines include:

- Use four spaces for each indentation level.
- Use `snake_case` for function and variable names, such as `calculate_average`.
- Use `CapWords` for class names, such as `StudentRecord`.
- Use `UPPER_CASE` for constants, such as `MAX_ATTEMPTS`.
- Use appropriate spaces around operators and after commas.
- Keep imports at the top of the file and organize them clearly.
- Normally limit code lines to 79 characters.

### Debugging

Debugging is the process of finding and fixing errors in a program. Common errors include syntax errors, runtime errors, and logic errors.

A useful debugging process is to reproduce the problem, read the error message or traceback, locate the cause, correct the code, and run it again to check the result. Printing intermediate values or stepping through the code with a debugger can help explain what the program is doing.

### Tips for Following PEP 8

To apply the lesson, I can configure my editor to use four spaces, choose consistent names, review long lines, and check formatting before submitting my work. A Python linter or formatter can help identify style issues, but I still need to check that the program produces the correct result.

## 3. What I Learned

This lesson helped me review the differences between classes, objects, functions, and methods. I also learned why readable code, consistent Python style, and systematic debugging matter. Creating the repository and its branches gave me practice organizing my work for future assignments.

## 4. Lesson Material

- The teacher's Week 1 slides: Introduction; Clean Code, PEP 8, and Debugging; Tips and Tricks to Help Ensure Your Code Follows PEP 8; and References.
- Classroom coding practice and questions.
