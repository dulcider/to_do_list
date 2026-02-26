# to_do_list
A feature-rich command-line task manager written in C++. Tasks are saved to a file automatically so nothing is lost between sessions.
How to compile & run
bash# Compile
g++ -o todo todo.cpp

# Run
./todo
Features

➕ Add tasks with a title, description, and priority (Low / Medium / High)
✅ Mark tasks as complete
🗑️ Delete tasks
🔍 Filter tasks by priority
🧹 Clear all completed tasks at once
💾 Auto-saves to tasks.dat — tasks persist between sessions
Color-coded priorities and statuses in the terminal

Concepts demonstrated

Structs to model real-world data (Task)
Enums for type-safe priority levels
Vectors and std::sort with custom comparators
File I/O — saving and loading structured data with fstream
String parsing with istringstream
Object-oriented design with a TodoList class
ANSI color codes for terminal UI

