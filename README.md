[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15343005&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a programming language that emphasizes code readability and a concise syntax that lets you write applications using fewer lines of code than any other programming languages. Python is a versatile language meaning that you can write python on one platform and be able to use it on other platforms that you need to support. Python is also special because it has a large and very diverse community, making it easy for beginners and even experienced programmers to tackle any challenges they may face in thier python projects. 

   One use case that I could think of right now is the use of python in data analysis. Python has quite a number of built-in packages that are very useful in data analysis such as, pandas, numpy, matplotlib etc. These packages they make python a good tool to analyse data, for example with pandas we can manipulate, clean and prepare data. With matplotlib we can create data visualizations. With numpy we can perform some linear algebra operations, and random number generations.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Python Installation Guide on Windows
         
         Step 1: Download Python Installer
                 Visit the official Python website.
                 Click on the “Downloads” tab and select "Download Python" for Windows.
         
         Step 2: Run the Installer
                 Run the downloaded executable file.
                 Make sure to check the box “Add Python to PATH”.
                 Select "Install Now" for default settings or customize as needed.
                 Wait for the installation to complete.
         
         Step 3: Verify Installation
                 Open Command Prompt.
                 Type python --version or python -V and press Enter. This should display the installed Python version.
         
         Step 4: Set Up a Virtual Environment
                 Open Command Prompt.
                 Navigate to your project directory: cd path\to\your\project
         
         Create a virtual environment: python -m venv venv
                 Activate the virtual environment: venv\Scripts\activate
                 To deactivate the virtual environment, type: deactivate


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, world!")

   The print function is a built-in function in Python used to display output to the console. In this program, we use double quotes to define the string, but single quotes would work as well: print('Hello, World!').Parentheses are used to pass arguments to functions in Python. In this case, the string "Hello, World!" is an argument passed to the print function.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   
         1. Integers are whole numbers that you can use to perform operations. Here is an example of an integer assigned to variable 'x':
   
               x = 45
               print(x)

         2. Float are numbers with decimal points. Here is an example of float data type assigned to  variable 'salary': 
   
               salary = 1456.8
               print(salary)

         3. String is simply a series of characters. Anything inside quotes is considered a string in Python, and you can use single or double quotes around your strings. Here is an example of a string assigned to variable 'name':
    
               name = "John"
               print(name)

         4. Boolean (bool) represents one of two values: True or False. It is used for conditional statements and logical operations.

               x = 5
               y = 5
               print(x == y)

         5. List (list) represents ordered collections of items, which can be of any type.
   
               nums = [1, 2, 3]
               fruits =  ["apple", "banana", "cherry"]

         6. Tuple (tuple) represents ordered collections of items, similar to lists, but are immutable (cannot be changed).
   
               nums = (1, 2, 3)
               fruits = ("apple", "banana", "cherry")
   
         7. Dictionary (dict) represents collections of key-value pairs, where each key is unique.
   
               user = {"name": "Alice", "age": 25}


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   The if statement alone tells us that if a condition is true it will execute a block of statements and if the 
   condition is false it won’t. But if we want to do something else if the condition is false, we can use the else 
   statement with the if statement to execute a block of code when the if condition is false.

         i = 20
         if (i == 10):  
            print("i is 10")  
         elif (i == 15):  
            print("i is 15")  
         elif (i == 20):  
            print("i is 20")  
         else:  
            print("i is not present")  

   Python For loop is used for sequential traversal i.e. it is used for iterating over an iterable like String, 
   Tuple, List, Set, or Dictionary.

         for i in range(0, 10, 2):  
            print(i) 

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Python Functions is a block of statements that return the specific task. The idea is to put some commonly or 
   repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.

   Built-in library function: These are Standard functions in Python that are available to use.
   User-defined function: We can create our own functions based on our requirements.

         def add_num(a, b):
            return a + b

         add_num(3, 4)      

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   List is a collection of items in a particular order, python represent list with square brackets[] and the items inside a list are seperated with a comma (,). While dictionary in python is a collection of key-value pairs, meaning that each key has a value connected to it. dictinaries are represented by curly brackets{}.  

      In this example we are retrieving an item from ages list that is associated with index 0.
         
         ages = [12, 16, 23, 34, 20]
         print(ages[0])  

      This example demonstrate how we can add an item into a list, e.g. 45
         
         ages.append(45)
         print(ages)

   
      In this example we are retrieving the value from user dictionary that is associated with the key called 'name'
         
         user = {'name':'John', 'age': 65, 'gender': 'Male'}
         print(user['name'])      
   
      This example demonstrate how we can add key-value pairs into a dictionary, e.g. 'lastname':'Doe'
         
         user['lastname'] = 'Doe'   


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

      Exceptions are object modules of python that are used to handle errors during code execution. Whenever an error occurs that makes Python unsure what to do next, it creates an exception object. If you write code that handles the exception, the program will continue running. If you don’t handle the exception, the program will halt and show a traceback, which includes a report of the exception that was raised. Try-except blocks, they are used to tell python what to do when the exception is raised. So whenever there is a error encountered during execution, instead of returning a coonfusing traceback, python will return a message that you have asked to be returned whenever the exception is raised. This message will be easily understood by nontechnical users than a traceback.

      Here is an example of try-except block, this example demostrate handling of a 'zero-division-error', which occurs in python whenever we are dividing a number by zero:

            try:
               print(2/0)
            except ZeroDivisionError:
               print("You can't divide by zero!!") 

      finally block: Contains the code that will always execute, regardless of whether an exception occurred or not. It's typically used for cleanup actions.

            def divide(a, b):
               try:
            # Code that might raise an exception
                  result = a / b
                  print("The result is:", result)
               except ZeroDivisionError:
            # Code to handle the exception
                  print("Error: Division by zero is not allowed.")
               except TypeError:
            # Code to handle the exception
                  print("Error: Both arguments must be numbers.")
               finally:
            # Code that will always execute
                  print("Execution of the 'try except finally' block is complete.")

            # Test cases
               divide(10, 0)   # ZeroDivisionError
               divide(10, 'a') # TypeError
     


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

      Python Packages and Frameworks: Python has a rich ecosystem of libraries and frameworks tailored for various domains. Depending on your interests, you can explore web development with frameworks like Django or Flask, data analysis and visualization with libraries like Pandas and Matplotlib, machine learning and artificial intelligence with TensorFlow or PyTorch, or automation with libraries like Selenium or BeautifulSoup.

      Importing the Entire Module:
               # Importing the entire math module
                  import math

               # Using functions from the math module
                  print("Pi:", math.pi)
                  print("Square root of 16:", math.sqrt(16))
                  print("Cosine of 0 degrees:", math.cos(math.radians(0)))
                  print("Logarithm base 10 of 1000:", math.log10(1000))
            # Importing specific functions from the math module
               from math import factorial, gcd
            # Using the imported functions directly
               print("Factorial of 5:", factorial(5))
               print("GCD of 48 and 180:", gcd(48, 180))


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
   
      Python offers built-in functions for file operations, including opening, reading, writing, and closing files. These methods allow for easy access to content, data writing, and file closure. 

      Opening a File: Use the open() function to open a file.

      Reading from a File: Use methods like read(), readline(), or readlines() to read the file's content.

      Writing to a File: Use methods like write() or writelines() to write data to the file.

      Closing a File: Use the close() method to close the file.
      
      Script that reads a content of a file:

            # Script to read from a file and print its contents
               def read_file(file_path):
                  try:
            # Open the file in read mode
               with open(file_path, 'r') as file:
            # Read the content of the file
               content = file.read()
            # Print the content to the console
               print(content)
            except FileNotFoundError:
               print(f"The file {file_path} does not exist.")

            # Example usage
            read_file('example.txt')

      Script that write a list of strings to a file         

            # Script to write a list of strings to a file
            def write_to_file(file_path, lines):
               try:
            # Open the file in write mode
            with open(file_path, 'w') as file:
            # Write each line to the file
            for line in lines:
                file.write(line + '\n')
               except Exception as e:
                  print(f"An error occurred: {e}")

            # Example usage
            lines_to_write = ["Hello, World!", "Python is great!", "File I/O is easy."]
            write_to_file('output.txt', lines_to_write)


   References
   
               JP. Mueller (2018) Beginning Programming with Python For Dummies, 2nd Edition, John Wiley & Sons, Inc.
               https://www.geeksforgeeks.org/python-programming-language-tutorial/
               chatGPT.com
               copilot.com




# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


