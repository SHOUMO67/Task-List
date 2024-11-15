


📝 Task List Application
This is a React-based Task List Application that allows users to manage their tasks effectively. The app supports adding, editing, and deleting tasks, along with features like task filtering, marking tasks as complete, and more. The UI is enhanced with animations and notifications using react-toastify.

🌟 Features
Add Task: Add new tasks with a title.
Edit Task: Update an existing task's title.
Delete Task: Remove tasks from the list.
Complete All: Mark all tasks as completed with a single click.
Delete Completed Tasks: Clear all tasks that are marked as completed.
Task Filtering: Filter tasks based on their status (All, Completed, Incompleted).
Persistent Storage: Fetch initial tasks from an API and manage the task state locally.
Notifications: Display success and error messages using react-toastify.
Loading State: Show a loading message while fetching tasks from the API.
Responsive Design: User-friendly interface with responsive design.

🛠️ Tech Stack
Framework: React
Language: JavaScript
Styling: CSS
Libraries:
react-toastify for notifications
Fetch API for data handling

📂 Project Structure
 code
src/
├── components/
│   └── TaskList.js
├── image/
│   └── task.png
├── style.css
├── App.js
└── index.js

🚀 Installation
Follow these steps to get the project running locally:

Clone the repository:

bash
cd tasklist-app
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Open the application in your browser at:


Copy code
http://localhost:3000
🖼️ Preview


📦 API Integration
The app fetches initial tasks from the JSONPlaceholder API. It also uses the API for adding and updating tasks.

Fetch Todos: Retrieves a list of tasks from the API on initial load.
Add Task: Sends a POST request to add a new task.
Edit Task: Sends a PUT request to update an existing task.

🔍 How to Use
Add a Task: Type a task title in the input box and click "Add".
Edit a Task: Click the edit icon next to a task, update the title, and click "Update".
Delete a Task: Click the delete icon next to a task.
Complete a Task: Check the checkbox next to a task title.
Filter Tasks: Use the filter options to view all, completed, or incompleted tasks.
Complete All Tasks: Click "Complete all tasks" to mark all tasks as completed.
Delete Completed Tasks: Click "Delete completed tasks" to clear completed tasks from the list.

🔔 Notifications

The app uses react-toastify for notifications:

Success messages for adding, updating, and deleting tasks.
Error messages if there is an issue with API requests.
Example Notification Code
jsx
Copy code
import { toast } from 'react-toastify';

toast.success('Task added successfully!');
toast.error('Error adding task');
🎨 Styling
The app is styled using a custom CSS file (style.css). You can modify the styles as needed to fit your design preferences.

⚙️ Configuration
Ensure that you have the following dependencies installed:

React
react-toastify
You can install missing dependencies with:

bash
Copy code
npm install react-toastify

🐛 Known Issues
API requests may fail if the JSONPlaceholder API is down or unreachable.
Task IDs from the API are not unique, which may cause issues when editing or deleting tasks.

🙌 Acknowledgments
The app uses the JSONPlaceholder API for demo purposes.
Thanks to React Toastify for the notification library.

