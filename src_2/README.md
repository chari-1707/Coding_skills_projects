# 📋 Task Chain - Linked List Simulator

A beautiful, interactive web application that demonstrates and visualizes linked list data structures through a task management interface.

## 🎯 Overview

Task Chain is an educational tool that combines practical task management with data structure visualization. Users can perform various linked list operations while seeing real-time visual feedback of how nodes are connected and manipulated.

## ✨ Features

### Core Operations
- **Add Task at End**: Automatically adds tasks with auto-incrementing priority
- **Insert at Priority**: Insert tasks at specific priority positions
- **Complete First Task**: Remove the first node (O(1) operation)
- **Delete by Priority**: Remove specific tasks by their priority number
- **Search Task**: Find tasks by name with visual highlighting
- **Clear All**: Remove all tasks from the list

### Visualization
- **Real-time Linked List Visualization**: See nodes connected with pointers
- **Task List Display**: View all tasks in traversal order
- **Node Highlighting**: Found nodes are highlighted during search operations
- **Statistics**: Track total tasks and operation count

### User Experience
- **Modern Dark Theme**: Beautiful gradient-based UI
- **Responsive Design**: Works on desktop and mobile devices
- **Interactive Animations**: Smooth transitions and visual feedback
- **Keyboard Support**: Press Enter to add tasks quickly

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required - runs directly in the browser!

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start managing tasks and exploring linked lists!

## 📁 Project Structure

```
src_2/
├── index.html      # Main HTML structure
├── styles.css      # Styling and animations
├── linkedList.js   # Linked List data structure implementation
├── app.js          # Application logic and UI interactions
└── README.md       # This file
```

## 🔧 Technical Details

### Linked List Implementation

The `LinkedList` class in `linkedList.js` provides:

- **Node Class**: Each node contains:
  - `data`: The task name
  - `priority`: Priority number for ordering
  - `next`: Pointer to the next node

- **Operations**:
  - `addFirst(data, priority)`: O(1) - Add at head
  - `addLast(data, priority)`: O(n) - Add at tail
  - `insertAtPriority(data, priority)`: O(n) - Insert at specific position
  - `removeFirst()`: O(1) - Remove head node
  - `removeByPriority(priority)`: O(n) - Remove by priority
  - `search(data)`: O(n) - Search by task name
  - `clear()`: O(1) - Clear entire list
  - `toArray()`: O(n) - Convert to array for display
  - `getSize()`: O(1) - Get list size
  - `isEmpty()`: O(1) - Check if empty

### Key Features

- **Priority System**: Tasks can be inserted at specific priority positions
- **Auto-incrementing Priority**: When adding at the end, priority automatically increments
- **Operation Counter**: Tracks all operations performed
- **Case-insensitive Search**: Search works regardless of case

## 🎨 Design

The application features:
- Dark theme with gradient accents
- Smooth animations and transitions
- Responsive grid layout
- Modal dialogs for search operations
- Visual node representation with pointers

## 📖 Usage Guide

1. **Adding Tasks**:
   - Enter a task name in the input field
   - Click "Add Task (at End)" to append with auto-incrementing priority
   - Or click "Add at Priority" to insert at a specific position

2. **Removing Tasks**:
   - Click "Complete First Task" to remove the head node
   - Use "Delete by Priority" to remove a specific task

3. **Searching**:
   - Click "Search Task" to open the search modal
   - Enter the task name to find
   - The found node will be highlighted in the visualization

4. **Viewing**:
   - The linked list visualization shows nodes with their pointers
   - The task list shows all tasks in order
   - Statistics display total tasks and operation count

## 🎓 Educational Value

This project demonstrates:
- Linked list data structure concepts
- Time complexity of different operations
- Node connections and pointer traversal
- Real-world application of data structures

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and responsive design
- **Vanilla JavaScript**: No frameworks - pure JavaScript implementation

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork this project and experiment with:
- Different data structures (stacks, queues, trees)
- Additional operations
- Enhanced visualizations
- Performance optimizations

## 📧 Contact

For questions or suggestions, feel free to open an issue or contribute to the project.

---

**Happy Coding!** 🚀

