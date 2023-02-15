# Task_Manager

**Task Manager**

This is a task management program that allows users to add, view and manage tasks as well as generate various reports for the tasks and users.

**Features**

The program has the following features:

Add a new task
View all tasks
View tasks specific to a particular user
Edit or mark tasks as complete
Register a new user
Generate reports of tasks and users

**Implementation**

The program uses a text file to store user information and task information for persistence. Each task is represented as a dictionary object in Python. User login functionality is not implemented, but the program allows the user to specify whether they are an admin or not. The program uses datetime to set task start and end dates.

**Table of Contents**

Installation
Usage
Credits

**Installation**

Clone the repository or download the source code. No additional libraries are required to run this program.

**Usage**

After running the program, the user is prompted to log in as an admin or not. Admin users have additional options in the program such as registering a new user, adding a new task and generating reports.

Once logged in, the user can select from the following menu options:

va - View all tasks: Displays all tasks stored in the tasks.txt file.
vm - View my tasks: Displays tasks assigned to the currently logged-in user.
a - Add task: Allows the user to add a new task to the tasks.txt file.
e - Exit: Exits the program.
r - Register user: Allows the admin to add a new user to the user.txt file.
gr - Generate reports: Allows the admin to generate various reports on users and tasks.

**Credits**

This program was created by 0x_CodeReaper.
