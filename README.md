
# 🚀 TaskCLI - Command Line Task Manager

**TaskCLI** is a simple, fast, and efficient command-line Task Manager built using Node.js.  
Easily add, list, and remove your daily tasks directly from the terminal! 🧑‍💻

---

## ✨ Features

- ✅ Add tasks from terminal
- 📋 View all tasks with index
- ❌ Remove tasks by number
- 💾 Saves tasks in `tasks.json`
- ⚙️ Built using core Node.js only

---

## 📦 Requirements

- Node.js (v12+ recommended)

---

## ⚙️ Setup Instructions

1. **Clone this repository**  
   ```bash
   git clone https://github.com/ANKITKUMARBARIK/TaskCLI.git
   cd TaskCLI
   ```

2. **Create an empty task file**  
   ```bash
   echo "[]" > tasks.json
   ```

3. **Run TaskCLI**  
   ```bash
   node index.js <command> <argument>
   ```

---

## 📚 Available Commands

| Command         | Description                         | Example                          |
|-----------------|-------------------------------------|----------------------------------|
| `add`           | ➕ Add a new task                    | `node index.js add "Learn JS"`   |
| `list`          | 📜 Show all saved tasks             | `node index.js list`             |
| `remove <no>`   | 🗑️ Remove task by number (1-based)  | `node index.js remove 2`         |

---

## 🗂️ Folder Structure

```
TaskCLI/
├── index.js        # Main script
├── tasks.json      # Task storage (auto-generated)
└── README.md       # Project documentation
```

---

## 💡 Future Improvements

- [ ] Task status (✔️ done / ❌ pending)
- [ ] Due dates or reminders ⏰
- [ ] Fancy CLI using `chalk` 🎨
- [ ] Search and sort features 🔍

---

## 👤 Author

Created with ❤️ by **ankit**(https://github.com/ANKITKUMARBARIK)  

---

## 📜 License

Licensed under the GPU License.

