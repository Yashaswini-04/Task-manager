# Task-manager
# Overview
This C++ console-based application serves as a simple To-Do List Manager. It allows users to manage tasks by adding new tasks, viewing the list of tasks, marking tasks as completed, and removing tasks from the list. The program operates through a menu-driven interface and continues running until the user chooses to exit.

# Features
Add Task: Users can add new tasks to the list by providing a task description.
View Tasks: Users can view all the tasks in the list, including which tasks have been completed.
Mark Task as Completed: Users can mark tasks as completed, and the list will reflect this status.
Remove Task: Users can remove tasks from the list.
Exit: Users can exit the program when they are done.
# How It Works
Data Structure
Task Structure:
A task is represented by a Task structure that contains a description (std::string) and a boolean flag (isCompleted) indicating whether the task is completed.
Task List:
Tasks are stored in a std::vector<Task>, which allows dynamic management of the list of tasks.
Menu Options
The program displays a menu with five options: Add Task, View Tasks, Mark Task as Completed, Remove Task, and Exit.
The user inputs a choice, and the corresponding action is performed.
# Functions
addTask(): Prompts the user to enter a description for a new task and adds it to the list.
viewTasks(): Displays all tasks, indicating which ones are completed.
markTaskAsCompleted(): Marks a task as completed based on the user's input.
removeTask(): Removes a task from the list based on the user's input.
