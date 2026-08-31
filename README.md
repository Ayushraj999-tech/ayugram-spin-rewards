# Todo List Application

A clean and efficient Flutter todo list application with local storage functionality using SharedPreferences.

## ✨ Features

✅ **Add Tasks** - Create new todos with title and description  
📅 **Due Dates** - Set and manage task due dates  
✏️ **Edit Tasks** - Update existing todos  
❌ **Delete Tasks** - Remove completed or unwanted tasks  
☑️ **Mark Complete** - Check off tasks as you complete them  
🎯 **Filter Tasks** - Filter by All, Active, or Completed status  
💾 **Local Storage** - All tasks are saved locally using SharedPreferences  
📱 **Material Design 3** - Modern and responsive UI  
⚠️ **Overdue Alerts** - Visual indicators for overdue tasks  

## Getting Started

### Prerequisites
- Flutter SDK (3.0.0 or higher)
- Dart SDK

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ayushraj999-tech/ayugram-spin-rewards.git
cd ayugram-spin-rewards
```

2. Get dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## How It Works

### Local Storage
- Uses `shared_preferences` package for persistent storage
- Todos are serialized to JSON and stored as strings in SharedPreferences
- Data persists even after app restart

### TodoItem Model
- `id`: Unique identifier (timestamp-based)
- `title`: Task title
- `description`: Task details
- `isCompleted`: Completion status
- `createdAt`: Creation timestamp
- `dueDate`: Optional due date for the task

### Operations
- **Add Todo**: Creates new todo with unique ID and saves to storage
- **Update Todo**: Modifies existing todo and updates storage
- **Delete Todo**: Removes todo from list and storage
- **Toggle Complete**: Marks todo as complete/incomplete
- **Set Due Date**: Add optional due date to tasks
- **Filter Tasks**: View All, Active, or Completed tasks

## Dependencies

- **flutter**: Core Flutter framework
- **shared_preferences**: ^2.2.2 - For local data persistence
- **intl**: ^0.19.0 - For date formatting

## Usage

1. **Add a Task**: Press the FAB (+) button and enter title, description, and optional due date
2. **Edit a Task**: Tap on a task or use the menu option to edit
3. **Complete a Task**: Check the checkbox next to the task
4. **Delete a Task**: Use the menu option to delete a task
5. **Filter Tasks**: Use filter chips to view All, Active, or Completed tasks
6. **Set Due Date**: Click calendar icon when adding/editing to set due date

## APK Build

### Build Release APK:
```bash
flutter build apk --release
```

APK file location: `build/app/outputs/flutter-apk/app-release.apk`

### Install on Device:
```bash
flutter install
```

## Project Structure

```
lib/
├── main.dart           # Main app entry point
├── TodoApp             # Root widget
├── TodoItem            # Model class with JSON serialization
└── TodoHomePage        # Todo list UI and state management
```

## Screenshot Features

- Clean Material Design 3 interface
- Task list with checkboxes
- Filter chips for status filtering
- Due date display with overdue warnings
- Add/Edit dialogs with date picker
- Popup menu for edit/delete options
- Empty state with helpful message

## Future Enhancements

- [ ] Categories and tags
- [ ] Search functionality
- [ ] Sort options (by date, priority)
- [ ] Dark mode support
- [ ] Cloud backup
- [ ] Push notifications for due tasks
- [ ] Recurring tasks
- [ ] Task priority levels

## License

This project is open source and available under the MIT License.

## Author

**Ayushraj999-tech**

---

**Repository:** https://github.com/Ayushraj999-tech/ayugram-spin-rewards
