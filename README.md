<h1> Day 1 - Getting Starting with Python </h1>


<h3>This repository was created in multiple part you can learn and practice python code. </h3>

- Cover Basic introduction of python
- Comments
- Data type (numeric and bool and text type)
- Operators
- String and string indexing, string slicing

<h2>Interview 15 + question on python basic</h2>

The biggest strength of Python is huge collection of standard library which can be used for the following:

- Machine Learning
- GUI Applications (like [Kivy](https://www.geeksforgeeks.org/kivy-tutorial/), Tkinter, PyQt etc. )
- Web frameworks like [Django](https://www.geeksforgeeks.org/django-tutorial/) (used by YouTube, Instagram, Dropbox)
- Image processing (like [OpenCV](https://www.geeksforgeeks.org/opencv-python-tutorial/), Pillow)
- Web scraping (like Scrapy, BeautifulSoup, Selenium)
- Test frameworks
- Multimedia
- Scientific computing
- Text processing and many more..

## What is Python?

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

## What can Python do?

- Python can be used on a server to create web applications.
- Python can be used alongside software to create workflows.
- Python can connect to database systems. It can also read and modify files.
- Python can be used to handle big data and perform complex mathematics.
- Python can be used for rapid prototyping, or for production-ready software development.

## Why Python?

- Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
- Python has a simple syntax similar to the English language.
- Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
- Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
- Python can be treated in a procedural way, an object-oriented way or a functional way.

## Good to know

- The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
- In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

## Interview Quetions on python introduction

### 1. What is Python?

- Python is a **high-level**, **interpreted**, interactive, and **object-oriented** scripting language. It uses English keywords frequently. Whereas, other languages use punctuation, Python has fewer syntactic constructions.
- Python is designed to be highly **readable** and **compatible** with different platforms such as Mac, Windows, Linux, Raspberry Pi, etc.

### 2. **Python is an interpreted language. Explain.**

An interpreted language is any programming language that executes its statements line by line. Programs written in Python run directly from the source code, with no intermediary compilation step.

### 3. **What is pep 8?**

PEP in Python stands for Python Enhancement Proposal. It is a set of rules that specify how to write and design Python code for maximum readability.

### 4. What are the Key features of Python?

The key features of Python are as follows:

![https://intellipaat.com/blog/wp-content/uploads/2015/09/Python-3.jpg](https://intellipaat.com/blog/wp-content/uploads/2015/09/Python-3.jpg)

- Python is an interpreted language, so it doesn’t need to be compiled before execution, unlike [languages such as C](https://intellipaat.com/blog/tutorial/c-tutorial/).
- Python is dynamically typed, so there is no need to declare a variable with the data type. Python Interpreter will identify the data type on the basis of the value of the variable.

### 5. How is Memory managed in Python?

- Memory in Python is managed by Python private heap space. All Python objects and data structures are located in a private heap. This private heap is taken care of by Python Interpreter itself, and a programmer doesn’t have access to this private heap.
- Python memory manager takes care of the allocation of Python private heap space.
- Memory for Python private heap space is made available by Python’s in-built garbage collector, which recycles and frees up all the unused memory.

### 6. What is PYTHONPATH?

**PYTHONPATH** has a role similar to PATH. This variable tells Python Interpreter where to locate the module files imported into a program. It should include the Python source library directory and the directories containing Python source code. PYTHONPATH is sometimes preset by Python Installer.

### 7. What are Python Modules?

Files containing Python codes are referred to as **[Python Modules](https://intellipaat.com/blog/tutorial/python-tutorial/python-modules/)**. This code can either be classes, functions or variables and saves the programmer time by providing the predefined functionalities when needed. It is a file with “.py” extension containing an executable code.

Commonly used built modules are listed below:

- os
- sys
- data time
- math
- random
- JSON

### 8. What are python namespaces?

A Python namespace ensures that object names in a program are unique and can be used without any conflict. Python implements these namespaces as dictionaries with ‘name as key’ mapped to its respective ‘object as value’.

Let’s explore some examples of namespaces:

- **Local Namespace** consists of local names inside a function. It is temporarily created for a function call and gets cleared once the function returns.
- **Global Namespace** consists of names from various imported modules/packages that are being used in the ongoing project. It is created once the package is imported into the script and survives till the execution of the script.
- **Built-in Namespace** consists of built-in functions of core Python and dedicated built-in names for various types of exceptions.



### 9. Explain Inheritance in Python with an example?

As Python follows an **object-oriented** programming paradigm, classes in Python have the ability to inherit the properties of another class. This process is known as inheritance. Inheritance provides the **code reusability feature**. The class that is being inherited is called a **superclass** or the parent class, and the class that inherits the superclass is called a **derived** or child class. The following types of inheritance are supported in Python:

![https://intellipaat.com/blog/wp-content/uploads/2015/09/Python-2.jpg](https://intellipaat.com/blog/wp-content/uploads/2015/09/Python-2.jpg)

- **Single inheritance**: When a class inherits only one superclass
- **Multiple inheritance**: When a class inherits multiple superclasses
- **Multilevel inheritance**: When a class inherits a superclass, and then another class inherits this derived class forming a ‘parent, child, and grandchild’ class structure
- **Hierarchical inheritance**: When one superclass is inherited by multiple derived classes

### 10. What is scope resolution?

A scope is a block of code where an object in Python remains relevant.Each and every object of python functions within its respective scope.As Namespaces uniquely identify all the objects inside a program but these namespaces also have a scope defined for them where you could use their objects without any prefix. It defines the accessibility and the lifetime of a variable.

Let’s have a look on scope created as the time of code execution:

- A local scope refers to the local objects included in the current function.
- A global scope refers to the objects that are available throughout execution of the code.
- A module-level scope refers to the global objects that are associated with the current module in the program.
- An outermost scope refers to all the available built-in names callable in the program.

### 11. What are the common built-in data types in Python?

Python supports the below-mentioned built-in data types:

**Immutable data types:**

- Number
- String
- Tuple

**Mutable data types:**

- List
- Dictionary
- set

### 12. How to comment with multiple lines in Python?

To add a multiple lines comment in python, all the line should be prefixed by #.

### 13. What type of language is python? Programming or scripting?

Generally, Python is an all purpose Programming Language ,in addition to that Python is also Capable to perform scripting.

### 14. How to comment with multiple lines in Python?

To add a multiple lines comment in python, all the line should be prefixed by #.

### 15. What type of language is python? Programming or scripting?

Generally, Python is an all purpose Programming Language ,in addition to that Python is also Capable to perform scripting.

### 16. What are the advantages of Python?

Advantages of Python are:

- Python is **Interpreted** language

Interpreted: Python is an interpreted language. It does not require prior compilation of code and executes instructions directly.

- It is Free and open source

Free and open source: It is an open-source project which is publicly available to reuse. It can be downloaded free of cost.

- It is **Extensible**

Extensible: It is very flexible and extensible with any module.

- Object-oriented

Object-oriented: Python allows to implement the Object-Oriented concepts to build application solution.

- It has Built-in data structure

Built-in data structure: Tuple, List, and Dictionary are useful integrated data structures provided by the language.

- Readability
- High-Level Language
- Cross-platform

Portable: Python programs can run on cross platforms without affecting its performance.

![https://static.javatpoint.com/interview/images/advantages-of-python.png](https://static.javatpoint.com/interview/images/advantages-of-python.png)

### 17. What are the differences between Python 2.x and Python 3.x?

Python 2.x is an older version of Python. Python 3.x is newer and latest version. Python 2.x is legacy now. Python 3.x is the present and future of this language.

The most visible difference between Python2 and Python3 is in print statement (function). In Python 2, it looks like print "Hello", and in Python 3, it is print ("Hello").

String in Python2 is ASCII implicitly, and in Python3 it is Unicode.

The xrange() method has removed from Python 3 version. A new keyword as is introduced in Error handling.



For more interview que follow this link

[Top 50+ Python Interview Questions (2022) - javatpoint](https://www.javatpoint.com/python-interview-questions)

[Top 100 Python Interview Questions and Answers 2021 - Intellipaat](https://intellipaat.com/blog/interview-question/python-interview-questions/#1)

[Top 40 Python Interview Questions & Answers - GeeksforGeeks](https://www.geeksforgeeks.org/top-40-python-interview-questions-answers/)

[Top Python Interview Questions (2022) - InterviewBit](https://www.interviewbit.com/python-interview-questions/)

[Top 44 Python Interview Questions & Answers: Ultimate Guide 2021 | upGrad blog](https://www.upgrad.com/blog/python-interview-questions-answers/)
