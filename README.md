# 📝 To-Do List Application

Welcome to the **To-Do List Application**! This project is a simple console-based application for managing tasks using C#. It allows you to add, view, mark tasks as completed, and remove tasks from your list. Your tasks are saved to a file so that they persist between sessions.

## 🚀 Features
- **Add Task**: Add new tasks to your to-do list.
- **View All Tasks**: View all tasks, including completed ones.
- **Mark Task as Completed**: Mark tasks as completed to keep track of what’s done.
- **Remove Task**: Remove tasks that are no longer needed.
- **Persistent Storage**: Tasks are saved in a text file (`tasks.txt`), allowing you to access them after closing the application.

## 💡 How It Works
The application uses a simple console interface where you can choose actions based on the following options:
1. Add a new task to the list.
2. View all tasks.
3. Mark a task as completed.
4. Remove a task.
5. Exit the application (and save tasks).

Each task is stored in a list and written to a file (`tasks.txt`) on disk to ensure data is not lost between program executions.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR-GITHUB-USERNAME/Todo-List-App.git
Navigate to the project directory:

bash
Copy code
cd Todo-List-App
Run the application (requires .NET SDK):

bash
Copy code
dotnet run
📂 File Structure
bash
Copy code
├── Program.cs        # Main application logic
├── tasks.txt         # Task storage file (auto-generated)
└── README.md         # Project documentation
🧑‍💻 Usage
Add a Task: Enter the task's title and press enter. The task will be added to your list.
View Tasks: Displays all tasks with their respective numbers. If a task is completed, it will be marked as -- COMPLETED.
Mark Task as Completed: Enter the task number you wish to mark as completed.
Remove a Task: Enter the task number you wish to remove from the list.
Exit: Exits the application, saving the tasks to tasks.txt.
🌟 Example Output
markdown
Copy code
Welcome to my To Do List
---------------------------
Choose one of the following options:
1. Add Task
2. View All Tasks
3. Mark Task As Completed
4. Remove Task
5. Exit
🗃️ Data Persistence
All tasks are saved to a file called tasks.txt located in the project directory. When you run the application again, the tasks from the previous session will be loaded automatically.

🛡️ Error Handling
Validates task numbers to prevent invalid selections.
Handles scenarios where the task list is empty.
Prevents adding empty or duplicate task titles.
📖 Future Enhancements
Add priority levels for tasks.
Allow editing tasks.
Support for categories and deadlines.
🛠️ Tech Stack
Language: C#
Platform: .NET Core
