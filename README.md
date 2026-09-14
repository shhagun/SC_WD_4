# SC_WD_4
TO-DO Web Application - Task 4
TaskFlow 📝

Organize. Prioritize. Achieve.

TaskFlow is a simple and responsive task management web application that helps users create, organize, prioritize, search, filter, edit, complete, and delete tasks easily.

✨ Features

- ➕ Add new tasks
- ✏️ Edit existing tasks
- 🗑️ Delete tasks
- ✅ Mark tasks as completed or pending
- 🔴 High, 🟠 Medium, and 🟢 Low priority
- 📂 Task categories:
  - Work
  - Study
  - Personal
  - Shopping
  - Other
- 🔍 Search tasks
- 🎯 Filter by status, priority, and category
- 🖱️ Drag and drop tasks between priority columns
- 📅 Add a due date
- 🌙 Dark mode / ☀️ Light mode
- 💾 Tasks are saved using browser "localStorage"
- 📊 Dashboard statistics for total, pending, completed, and high-priority tasks
- 📱 Responsive design for mobile and desktop

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons
- Browser LocalStorage

The project uses Bootstrap 5.3.2 and Bootstrap Icons through CDN links.

📁 Project Structure

TaskFlow/
│
└── index.html

The complete application is contained in a single "index.html" file.

🚀 How to Run

1. Download or clone this project.
2. Open the project folder.
3. Open "index.html" in any modern web browser.
4. Start adding your tasks.

No backend, database, Node.js, npm, or server setup is required.

💾 Data Storage

TaskFlow uses the browser's LocalStorage to save tasks.

Tasks are stored under:

taskflow_tasks

The selected theme is stored under:

taskflow_theme

Therefore, your tasks remain available when you refresh or reopen the page in the same browser.

🎯 Task Management

Each task can contain:

- Task title
- Description
- Priority
- Category
- Due date
- Completion status

Task titles are validated before saving, with a minimum of 3 characters and a maximum of 100 characters.

🔎 Search & Filters

Users can search tasks by:

- Title
- Description
- Category

Tasks can also be filtered by:

- Status
- Priority
- Category

A Clear button resets all filters.

🖱️ Drag & Drop

Tasks can be dragged between:

- High Priority
- Medium Priority
- Low Priority

Dropping a task into another column automatically changes its priority.

🌙 Dark Mode

TaskFlow includes a theme toggle that allows users to switch between light and dark mode. The selected theme is saved in LocalStorage.

📊 Dashboard

The dashboard displays:

Statistic| Description
Total Tasks| Total number of tasks
Pending Tasks| Tasks that are not completed
Completed Tasks| Completed tasks
High Priority| Number of high-priority tasks

📱 Responsive Design

TaskFlow is designed to work on different screen sizes, including mobile devices, tablets, and desktops. Bootstrap's responsive grid system is used throughout the interface.

🔒 Privacy

Task data is stored locally in the user's browser using LocalStorage. No external database or backend is used.

👩‍💻 Author

Sagun Mishra

BCA Student | Web Development

📄 License

This project is created for learning and educational purposes.