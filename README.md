# To-Do Web App

A beautiful, modern, and fully functional to-do list application built with vanilla HTML, CSS, and JavaScript.

## Features

- ✨ **Modern UI Design** - Beautiful gradient background with smooth animations
- ✅ **Add Tasks** - Quickly add new tasks with a clean input interface
- 🎯 **Toggle Completion** - Mark tasks as complete/incomplete with a single click
- 🗑️ **Delete Tasks** - Remove individual tasks with smooth animations
- 🔍 **Filter Tasks** - View all, active, or completed tasks
- 📊 **Task Statistics** - See how many tasks are active
- 🧹 **Clear Completed** - Remove all completed tasks at once
- 💾 **Local Storage** - Tasks persist across browser sessions
- 📱 **Responsive Design** - Works perfectly on desktop and mobile devices

## Getting Started

### Option 1: Open Directly in Browser

Simply open the `index.html` file in your web browser:

1. Navigate to the project folder
2. Double-click `index.html`
3. Start managing your tasks!

### Option 2: Use a Local Server

For a better development experience, you can use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open your browser and navigate to `http://localhost:8000`

## Usage

1. **Add a Task**: Type your task in the input field and click "Add Task" or press Enter
2. **Complete a Task**: Click the circle checkbox next to a task to mark it as complete
3. **Delete a Task**: Hover over a task and click the trash icon
4. **Filter Tasks**: Use the All/Active/Completed tabs to filter your view
5. **Clear Completed**: Click "Clear Completed" to remove all finished tasks

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Animations)
- Vanilla JavaScript (ES6+)
- Local Storage API

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## File Structure

```
to-do-web-app/
├── index.html      # Main HTML structure
├── styles.css      # All styling and animations
├── script.js       # Application logic and functionality
└── README.md       # This file
```

## License

Free to use for personal and commercial projects.
