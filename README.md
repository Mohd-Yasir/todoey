# Todoey

A task management app built with Flutter and the Provider package, based on the Todoey project from Angela Yu's Flutter course. This app allows users to add tasks, check them off when completed, and remove tasks via long press.

## Features

- **Add Tasks**: Users can input new tasks using a bottom sheet dialog.
- **Mark Tasks as Complete**: Tasks can be checked off, and completed tasks will be visually indicated with a strikethrough.
- **Remove Tasks**: Long-pressing a task allows users to delete it.
- **Real-time UI Updates**: Tasks added or removed are updated in real-time using the `Provider` package.
  
## Technologies Used

- **Flutter**: For building the cross-platform UI.
- **Provider**: For state management.
- **Dart**: The programming language used by Flutter.
  
## How It Works

1. **Task Addition**: When users tap the floating action button, a modal bottom sheet appears allowing them to enter a new task. Upon pressing 'Add', the task gets added to the list.
  
2. **Task Completion**: A checkbox is available next to each task, and when checked, the task text is struck through.
  
3. **Task Deletion**: Users can delete tasks by long-pressing on the task.

## App Structure

- `TaskScreen`: The main screen displaying the list of tasks.
- `AddTaskScreen`: The modal used to add a new task.
- `TasksList`: Displays the list of tasks using a `ListView.builder`.
- `TaskTile`: Represents each individual task with a checkbox and a delete action.
- `TaskData`: Handles the business logic for task management and notifies listeners of changes.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/todoey.git
    ```

2. Navigate to the project folder:
    ```bash
    cd todoey
    ```

3. Get the required dependencies:
    ```bash
    flutter pub get
    ```

4. Run the app:
    ```bash
    flutter run
    ```

## Screenshots

| Task List                         | Add Task                       |
|-----------------------------------|-------------------------------|
| ![task_screen](https://github.com/user-attachments/assets/15fd25b9-d2ec-4f77-b011-d268233131ef)  | ![add_screen](https://github.com/user-attachments/assets/0a0f16bc-d021-441a-9f8c-43730e98f425) |

## Future Improvements

- Add persistence for tasks (e.g., using SQLite or Firebase).
- Implement task categories or deadlines.
- Provide theme customization options.

## License

This project is licensed under the MIT License.

---

You can modify the text, add screenshots, and include links as needed for your GitHub repository.
