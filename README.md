# Persistent Mini App - To-Do List

A simple yet powerful To-Do List application built with vanilla JavaScript that persists your tasks using browser localStorage. No backend required!

## 📋 Features

- ✅ **Add Tasks** - Quickly add new tasks to your to-do list
- ✓ **Mark as Complete** - Click on any task to toggle completion status
- 🗑️ **Delete Tasks** - Remove tasks by clicking the delete icon (×)
- 💾 **Auto-Save** - All tasks are automatically saved to browser storage
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices
- 🎨 **Modern UI** - Clean interface with gradient background and smooth interactions

## 🔧 Dependencies

**Zero dependencies!** This project uses only:
- HTML5
- CSS3
- Vanilla JavaScript (ES6)
- Browser's built-in localStorage API

No npm packages, build tools, or external libraries needed.

## � Clone & Setup

### Clone the Repository
```bash
git clone https://github.com/Abr-ishFatima/persistent-mini-app.git
cd persistent-mini-app
```

### Then Run It
Choose any method below to run the app on your machine.

## �🚀 How to Run

### Option 1: Direct File Opening (Quickest)
1. Navigate to the project folder
2. Right-click on `index.html`
3. Select "Open with" and choose your browser (Chrome, Firefox, Edge, Safari, etc.)
   - Or simply double-click `index.html` to open in your default browser

### Option 2: Using a Local Server (Recommended)

**Using Python:**
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

**Using VS Code Live Server Extension:**
1. Install "Live Server" extension by Ritwick Dey
2. Right-click on `index.html`
3. Select "Open with Live Server"

Then open your browser and navigate to:
- `http://localhost:8000` (Python)
- `http://localhost:5500` (VS Code Live Server)
- `http://localhost:8080` (http-server)

## 📁 Project Structure

```
persistent-mini-app/
├── index.html          # Main HTML file with app structure
├── style.css           # Styling and layout
├── script.js           # JavaScript logic and functionality
├── images/
│   └── icon.png        # To-do list icon
└── README.md           # This file
```

## 💡 Usage

1. **Add a Task**: Type text in the input field and click the "Add" button (or press Enter)
2. **Complete a Task**: Click on any task to mark it as done (strikethrough style)
3. **Delete a Task**: Click the "×" button next to the task to remove it
4. **Your Data Persists**: Close the browser and reopen - your tasks will still be there!

## 🔒 How It Works

- Tasks are stored in the browser's **localStorage** with the key `"data"`
- When you add, complete, or delete a task, the `saveData()` function saves the state
- When the page loads, `showTask()` retrieves your saved tasks from localStorage
- No server or database needed - everything happens on your device!

## 🌐 Browser Compatibility

Works on all modern browsers:
- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes

- Tasks are stored in browser localStorage and will persist even after closing the browser
- Clearing browser storage or cookies will delete saved tasks
- Each browser/device stores tasks separately
- No internet connection required to use the app

## 🎯 Future Enhancements (Ideas)

- Export/Import tasks as JSON
- Task categories or projects
- Due dates and reminders
- Dark mode toggle
- Drag & drop to reorder tasks
- Cloud sync across devices

---

**Enjoy organizing your tasks!** 📝✨
