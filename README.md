
#  Coffee Machine {Python program}
Here's a brief description of the Python code:

The code is for a simple console-based drink vending machine. It has several functions:

1. `print_resources(resources)`: This function prints the current resources (ingredients) available in the machine.

2. `user_choice()`: This function asks the user what drink they would like to have. It keeps asking until the user makes a valid choice or requests a report of the current resources.

3. `total_paid(quaters, dimes, nickles, pennies)`: This function calculates the total amount of money inserted by the user based on the number of each type of coin inserted.

4. `menu_cost(choice)`: This function returns the cost of the chosen drink from a predefined menu.

5. `can_make_drink(drink, menu, resources)`: This function checks if there are enough resources to make the chosen drink. If not, it informs the user which ingredient is missing or not sufficient.

6. `make_drink(drink, menu, resources)`: This function subtracts the ingredients used for making the chosen drink from the resources.

7. `cashing(cost, total_paid)`: This function checks if the user has inserted enough money for their chosen drink. If not, it informs the user and refunds their money. If yes, it calculates and informs the user about their change.

The main loop of the program keeps running until the user decides to stop. In each iteration of the loop, it first asks for the user's choice of drink and checks if there are enough resources to make it. If yes, it then asks for payment and checks if it's enough. If both checks pass, it makes the drink and serves it to the user.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Tech Stack
The program you see is written in Python, which is a high-level, interpreted programming language. Python is known for its simplicity and readability, which makes it a great choice for beginners as well as experienced developers. It's widely used in various domains like web development, data analysis, machine learning, artificial intelligence, scientific computing, etc.

In the context of this program:
- Python's built-in functions and data structures like `dict` (for storing resources and menu), `float` (for handling money), and `input` (for user interaction) are used.
- Control flow structures like `while` loops and `if` conditions are used to guide the program execution.
- Custom functions are defined and used to modularize the code and improve its readability and maintainability.

No external libraries or frameworks were used in this particular program. It's a simple console-based application that runs in a Python environment. However, Python has a rich ecosystem of libraries and frameworks that can be employed for more complex applications. For example, Flask or Django for web development, NumPy and pandas for data analysis, TensorFlow and PyTorch for machine learning, etc. But those were not needed for this simple console-based application.
## Documentation
Here are the documentations for the technologies you mentioned:

1. **Python's built-in functions and data structures**:
    - `dict`: Python's built-in dictionary is a mutable and indexed collection. It is used to store data in key-value pairs. You can find more about it in the [Python documentation](^1^).
    - `float`: This is a built-in Python function that converts a number or a string to a floating point number. More details can be found [here](^23^).
    - `input`: This function reads a line from input (usually user input), converts it to a string, and returns that string. You can learn more about it [here](^13^).

2. **Control flow structures**:
    - `while loops`: A while loop in Python repeatedly executes a target statement as long as a given condition is true. You can read more about it [here](^18^).
    - `if conditions`: The if statement in Python allows you to test a condition and perform some action based on whether the condition is true or false. More information can be found [here](^18^).

3. **Custom functions**: In Python, you can define your own functions using the `def` keyword. Custom functions help to decompose a large program into small segments which makes the program easy to understand, maintain and debug. If a specific operation is performed in several places in the program, it is good to define a function for that operation to reduce repetitive code. More details on defining your own functions can be found [here](^10^).

Remember, these are just starting points. Python's documentation and various other resources on the web provide much more comprehensive information.

Source: Conversation with Bing, 10/6/2023
(1) Built-in Functions — Python 3.10.12 documentation. https://docs.python.org/3.10/library/functions.html?highlight=reversed.
(2) 15. Floating Point Arithmetic: Issues and Limitations - Python. https://docs.python.org/3/tutorial/floatingpoint.html.
(3) 7. Input and Output — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/inputoutput.html.
(4) 4. More Control Flow Tools — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/controlflow.html.
(5) 4. More Control Flow Tools — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/controlflow.html.
(6) Defining Your Own Python Function – Real Python. https://realpython.com/defining-your-own-python-function/.
(7) builtins — Built-in objects — Python 3.12.0 documentation. https://docs.python.org/3/library/builtins.html.
(8) The Python Standard Library — Python 3.12.0 documentation. https://docs.python.org/3/library/index.html.
(9) 5. Data Structures — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/datastructures.html.
(10) Common Python Data Structures (Guide) – Real Python. https://realpython.com/python-data-structures/.
(11) Python Data Structures Cheat Sheet: The Essential Guide - StationX. https://www.stationx.net/python-data-structures-cheat-sheet/.
(12) Learn Data Structures and Algorithms with Python | Codecademy. https://www.codecademy.com/learn/learn-data-structures-and-algorithms-with-python.
(13) Intro to data structures — pandas 2.1.1 documentation. https://pandas.pydata.org/docs/user_guide/dsintro.html.
(14) Built-in Functions — Python 3.12.0 documentation. https://docs.python.org/3/library/functions.html.
(15) How to document python function parameter types?. https://stackoverflow.com/questions/7690220/how-to-document-python-function-parameter-types.
(16) GitHub - TomSchimansky/CustomTkinter: A modern and customizable python .... https://github.com/TomSchimansky/CustomTkinter.
(17) Documentation generator and online help system - Python. https://bing.com/search?q=Python+input+documentation.
(18) Documentation generator and online help system - Python. https://docs.python.org/3/library/pydoc.html.
(19) Basic Input, Output, and String Formatting in Python. https://realpython.com/python-input-output/.
(20) Documenting Python Code: A Complete Guide – Real Python. https://realpython.com/documenting-python-code/.
(21) Python Control Flow Statements and Loops – PYnative. https://pynative.com/python-control-flow-statements/.
(22) Python Control Systems Library — Python Control Systems Library 0.9.4 .... https://python-control.readthedocs.io/.
(23) Flow Control in Python: Conditional Statements and Loops. https://medium.com/geekculture/flow-control-in-python-conditional-statements-and-loops-ef6e829f4cfd.
(24) Python Basics: Conditional Logic and Control Flow (Overview). https://realpython.com/lessons/conditional-logic-control-flow-overview/.
(25) Built-in Types — Python 3.12.0 documentation. https://docs.python.org/3/library/stdtypes.html.
(26) Python float() Function - W3Schools. https://www.w3schools.com/python/ref_func_float.asp.
(27) Floating Point Objects — Python 3.12.0 documentation. https://docs.python.org/3/c-api/float.html.
(28) undefined. https://customtkinter.tomschimansky.com/documentation.
## Lessons Learned
Developing a program like the coffee machine can provide several valuable lessons:

1. **Understanding of Python Basics**: The program uses fundamental Python concepts such as functions, loops, conditionals, and data structures like dictionaries. This helps reinforce your understanding of these concepts.

2. **Problem Solving**: The process of developing the program enhances your problem-solving skills. You learn how to break down a complex problem (like managing a drink machine) into smaller, more manageable parts.

3. **Modular Programming**: The program is divided into several functions each performing a specific task. This is a good practice in programming as it improves the readability and maintainability of the code.

4. **User Interaction**: The program takes input from users and provides appropriate output. This helps you understand how to interact with users in a console environment.

5. **Error Handling**: The program checks for possible errors (like insufficient resources) and handles them gracefully. This is an important aspect of any real-world application.

6. **Real-world Application**: Finally, by creating a simulation of a real-world machine, you learn how programming can be used to solve real-world problems and automate tasks.

Remember, every coding project you undertake enhances your programming skills and problem-solving abilities. Happy coding! 😊

# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.