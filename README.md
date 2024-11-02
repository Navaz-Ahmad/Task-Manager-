Here’s a well-structured README file content for your **Task Manager** project, detailing the project overview, features, prerequisites, installation steps, usage, and more. This will help users understand and use your application effectively.

---

# Task Manager - To-Do List Application

## Project Overview
**Task Manager** is a Python-based To-Do List application that allows users to manage their tasks efficiently. Users can add, edit, delete, and mark tasks as complete, as well as set due dates, categorize tasks, and assign priorities. This project also includes a GUI built with Tkinter, making it user-friendly and visually accessible.

## Features
- **Add, Edit, and Delete Tasks**: Easily manage tasks through the intuitive interface.
- **Mark Tasks as Complete**: Track task completion status.
- **Category Selection**: Organize tasks under categories like "Personal," "Work," "School," etc.
- **Due Date Selection**: Set due dates using a calendar picker for better deadline management.
- **Priority Setting**: Assign priority levels to tasks (High, Medium, Low).
- **Data Persistence**: Save and load tasks to/from a JSON file for persistent task storage.

## Prerequisites
To run this application successfully, you need the following:
- **Python 3.6 or higher**: Ensure that Python is installed and added to your system’s PATH.
- **Tkinter**: This is included with Python, but for some distributions, you may need to install it separately.
- **tkcalendar**: A Python library used to provide a date picker widget.

### Install `tkcalendar`
To install `tkcalendar`, run the following command:
```bash
pip install tkcalendar
```

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Navaz-Ahmad/Task-Manager.git
   cd Task-Manager
   ```

2. **Install the necessary packages**:
   Install `tkcalendar` if you haven't done so yet.
   ```bash
   pip install tkcalendar
   ```

3. **Run the Application**:
   Launch the application by running:
   ```bash
   python task_manager.py
   ```

## Usage
1. **Adding a Task**: 
   - Enter the task name, select a category, set a due date, and assign a priority.
   - Click **Add Task** to save the new task.

2. **Editing a Task**:
   - Select a task from the list, modify the details as needed, and click **Edit Task**.

3. **Marking as Complete**:
   - Select a task and click **Mark Task Complete** to update its status.

4. **Deleting a Task**:
   - Select a task from the list and click **Delete Task** to remove it.


## Contributing
Feel free to open issues and submit pull requests for new features, bug fixes, or improvements.

## License
This project is licensed under the MIT License.

---
