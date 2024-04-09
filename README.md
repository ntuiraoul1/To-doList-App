# To-doList-App

**Imports and Main Function:**

 import 'dart:io': This line imports the dart:io library, which provides functions for interacting with the console (standard input and output).
 main(): This is the entry point of the program. Everything inside this function gets executed when you run the code.
 Todo List Management:

todoList: This variable is a list of strings, where each string represents a task in the todo list.
 while (true): This loop keeps the program running until the user decides to exit.
 Menu and User Input:

 Inside the loop, the code displays a menu with five options:
 Add Task
 Mark Task as Completed
 View Todo List
 Remove Task
 Exit
It prompts the user to enter their choice and stores it in the choice variable.
 A switch statement handles different choices based on the user input.
 **Menu Functions:**

**addTask:** This function prompts the user for a new task and adds it to the todoList. (Currently, the commented line todoList.add(task); is missing, so adding functionality needs to be uncommented.)

**markTaskAsCompleted:** This function first checks if the list is empty. If not, it displays the current todo list and prompts the user for the index of the task to mark complete. It validates the index and updates the corresponding item in the list with a "[✓]" mark.

**viewTodoList:** This function simply iterates through the todoList and prints each item with its index.
 
 **removeTask:** Similar to markTaskAsCompleted, it checks for an empty list, displays the current list, prompts for the index to remove, validates the index, and removes the task from the list.
 exit(0): This exits the program with a successful exit code (0).
 Error Handling:

Each function that interacts with the todoList checks for an empty list and displays a message if there are no tasks.

 The markTaskAsCompleted and removeTask functions validate the user-provided index to ensure it's within the valid range of the list.

This code provides a basic structure for a command-line todo list. You can further enhance it by adding features like saving the todo list to a file, marking tasks as uncompleted, or prioritizing tasks.



