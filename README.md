# TaskPulse

TaskPulse is an intuitive application designed to help users register personalized tasks and efficiently track them based on their status. Whether you're managing personal projects, work tasks, or daily chores, TaskPulse provides a streamlined solution for keeping your tasks organized and ensuring nothing slips through the cracks.

## Features

- **Task Registration**: Easily register new tasks with detailed information, including task name, description, due date, and priority.

- **Status Tracking**: Categorize tasks based on their status (e.g., To-Do, In Progress, Completed) to monitor progress at a glance.

- **Priority Sorting**: Prioritize tasks by assigning different priority levels, ensuring that important tasks are given the attention they deserve.

- **User-Friendly Interface**: The application boasts an intuitive and user-friendly interface, making task management a seamless and enjoyable experience.

- **Notification System**: Receive timely reminders and notifications for approaching due dates, helping you stay on top of your tasks.

## Installation

To get started with TaskPulse, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/TaskPulse.git
   cd TaskPulse
2. **Backend Setup**:

   - Create a `.env` file in the `backend` folder.
   - Add the following variables to the `.env` file:
     ```env
     PORT=8080
     MONGODB_URL=<Your MongoDB Connection URL>
     ENCRYPTION_REF=<Your Encryption Reference>
     ```
   - Open a terminal and navigate to the `backend` folder:
     ```bash
     cd backend
     ```
   - Run the backend server with the following command:
     ```bash
     npm run dev
     ```

   Ensure that you have a MongoDB instance running and replace `<Your MongoDB Connection URL>` with the appropriate connection URL. The `ENCRYPTION_REF` is a reference used for encryption; replace it with a secret key for your application.
3. **Frontend Setup**:

   - Open a new terminal and navigate to the `frontend` folder:
     ```bash
     cd frontend
     ```
   - Install the required dependencies:
     ```bash
     npm install
     ```
   - Run the frontend development server with the following command:
     ```bash
     npm run dev
     ```

   The frontend development server will start, and you can access the application at `localhost server` by default. Make sure to complete the backend setup (as mentioned in step 2) before running the frontend to ensure proper communication between the frontend and backend.
