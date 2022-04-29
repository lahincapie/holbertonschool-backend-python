# **0x00. Python - Variable Annotations**


# **Concepts**

*For this project, students are expected to look at this concept:*

- [Advanced Python](https://intranet.hbtn.io/concepts/554)

![https://i.redd.it/y9y25tefi5401.png](https://i.redd.it/y9y25tefi5401.png)

# **Resources**

**Read or watch**:

- [Python 3 typing documentation](https://docs.python.org/3/library/typing.html)
- [MyPy cheat sheet](https://fs.blog/feynman-learning-technique/)

# **Learning Objectives**

# **General**

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.hbtn.io/rltoken/1G3T7x1BAyygmeudLSp4xQ), **without the help of Google**:

- Type annotations in Python 3
- How you can use type annotations to specify function signatures and variable types
- Duck typing
- How to validate your code with `mypy`

# **Requirements**

# **General**

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the `pycodestyle` style (version 2.5.)
- All your files must be executable
- The length of your files will be tested using `wc`
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
- All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)


****************************

# **0x01. Python - Async**


![https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/4aeaa9c3cb1f316c05c4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220425%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220425T131003Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b7eaeedcb4f522bf309a12a2734d52b213df946825c7a85f414a36fb823f2cd6](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/4aeaa9c3cb1f316c05c4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220425%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220425T131003Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b7eaeedcb4f522bf309a12a2734d52b213df946825c7a85f414a36fb823f2cd6)

# **Resources**

**Read or watch**:

- [Async IO in Python: A Complete Walkthrough](https://realpython.com/async-io-python/)
- [asyncio - Asynchronous I/O](https://docs.python.org/3/library/asyncio.html)
- [random.uniform](https://docs.python.org/3/library/random.html#random.uniform)

# **Learning Objectives**

At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/), **without the help of Google**:

- `async` and `await` syntax
- How to execute an async program with `asyncio`
- How to run concurrent coroutines
- How to create `asyncio` tasks
- How to use the `random` module

# **Requirements**

# **General**

- A `README.md` file, at the root of the folder of the project, is mandatory
- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
- All your files should end with a new line
- All your files must be executable
- The length of your files will be tested using `wc`
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- Your code should use the `pycodestyle` style (version 2.5.x)
- All your functions and coroutines must be type-annotated.
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All your functions should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)


*****************************

# 0x02. Python - Async Comprehension

# **0x02. Python - Async Comprehension**

### **In a nutshell…**


![https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/ee85b9f67c384e29525b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220429%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220429T234401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=28e0c21650548d7f2ce99d360cccedb9609ecc9dcdc9da25d214906fc8f97914](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/ee85b9f67c384e29525b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220429%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220429T234401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=28e0c21650548d7f2ce99d360cccedb9609ecc9dcdc9da25d214906fc8f97914)

# **Resources**

**Read or watch**:

- [PEP 530 – Asynchronous Comprehensions](https://peps.python.org/pep-0530/)
- [What’s New in Python: Asynchronous Comprehensions / Generators](https://www.blog.pythonlibrary.org/2017/02/14/whats-new-in-python-asynchronous-comprehensions-generators/)
- [Type-hints for generators](https://stackoverflow.com/questions/42531143/how-to-type-hint-a-generator-in-python-3)

# **Learning Objectives**

At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/), **without the help of Google**:

- How to write an asynchronous generator
- How to use async comprehensions
- How to type-annotate generators

# **Requirements**

# **General**

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the `pycodestyle` style (version 2.5.x)
- The length of your files will be tested using `wc`
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All your functions should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
- All your functions and coroutines must be type-annotated.

*********

