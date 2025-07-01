# Todo List App

A intuitive desktop todo list application built with Java Swing. This application allows users to manage their daily tasks with a clean, user-friendly interface.

## Features

- ✅ Add new tasks to your todo list
- 🗑️ Delete completed or unwanted tasks
- 📝 Clean and minimalist user interface
- 🖥️ Cross-platform desktop application
- ⚡ Lightweight and fast performance

## Requirements

- Java 8 or higher
- No additional dependencies required (uses built-in Swing library)

## Installation

### Option 1: Clone and Compile

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   ```

2. Compile the Java file:
   ```bash
   javac -d . src/com/elevateLabs/TodoApp.java
   ```

3. Run the application:
   ```bash
   java com.elevateLabs.TodoApp
   ```

### Option 2: Download JAR (if available)
1. Run the JAR file:
   ```bash
   java -jar todo-app.jar
   ```

## Usage

1. **Adding Tasks**: 
   - Type your task in the text field at the top
   - Click "Add Task" button or press Enter
   - The task will appear in the list below

2. **Deleting Tasks**:
   - Select a task from the list by clicking on it
   - Click the "Delete Task" button at the bottom
   - The selected task will be removed from the list

3. **Task Management**:
   - Tasks are displayed in the order they were added
   - Select any task to highlight it before deletion
   - Empty tasks cannot be added to the list

## Project Structure

```
todo-app/
├── src/
│   └── com/
│       └── elevateLabs/
│           └── TodoApp.java
├── README.md
└── LICENSE
```

## Technical Details

- **Language**: Java
- **GUI Framework**: Swing
- **Architecture**: Single-class desktop application
- **Data Storage**: In-memory (tasks are not persisted between sessions)

### Key Components

- `JFrame` - Main application window
- `JTextField` - Task input field
- `JList` with `DefaultListModel` - Task display and management
- `JButton` - Add and delete functionality
- `JScrollPane` - Scrollable task list for many items

## Future Enhancements

- [ ] Persistent storage (save tasks to file)
- [ ] Task completion status (checkboxes)
- [ ] Task editing functionality
- [ ] Task priority levels
- [ ] Due dates and reminders
- [ ] Search and filter capabilities
- [ ] Dark mode theme
- [ ] Export tasks to different formats


### Development Guidelines

- Follow Java naming conventions
- Add comments for complex logic
- Test your changes thoroughly
- Update README if adding new features

## Acknowledgments

- Built with Java Swing framework
- Inspired by the need for simple, effective task management
- Thanks to the Java community for excellent documentation and resources

---
