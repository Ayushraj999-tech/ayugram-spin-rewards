# Todo List Application

A clean and efficient Flutter todo list application with local storage functionality using SharedPreferences.

## Features

✅ **Add Tasks** - Create new todos with title and description
✏️ **Edit Tasks** - Update existing todos
❌ **Delete Tasks** - Remove completed or unwanted tasks
☑️ **Mark Complete** - Check off tasks as you complete them
💾 **Local Storage** - All tasks are saved locally using SharedPreferences
📱 **Material Design 3** - Modern and responsive UI

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

### Operations
- **Add Todo**: Creates new todo with unique ID and saves to storage
- **Update Todo**: Modifies existing todo and updates storage
- **Delete Todo**: Removes todo from list and storage
- **Toggle Complete**: Marks todo as complete/incomplete

## Dependencies

- **flutter**: Core Flutter framework
- **shared_preferences**: ^2.2.2 - For local data persistence

## Usage

1. **Add a Task**: Press the FAB (+) button and enter title and description
2. **Edit a Task**: Tap on a task or use the menu option to edit
3. **Complete a Task**: Check the checkbox next to the task
4. **Delete a Task**: Use the menu option to delete a task

## APK Download

### Build APK Release:
```bash
flutter build apk --release
```

APK file location: `build/app/outputs/flutter-apk/app-release.apk`

### Install on Device:
```bash
flutter install
```

## GitHub Releases

Download pre-built APK from [Releases](https://github.com/Ayushraj999-tech/ayugram-spin-rewards/releases)

## Future Enhancements

- [ ] Add due dates and reminders
- [ ] Categories and tags
- [ ] Search functionality
- [ ] Sort and filter options
- [ ] Dark mode support
- [ ] Cloud backup
- [ ] Push notifications

## License

This project is open source and available under the MIT License.

## Author

**Ayushraj999-tech**
