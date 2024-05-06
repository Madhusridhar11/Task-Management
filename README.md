# Tasks Management App

This is a task management application built with Laravel and Livewire. It allows you to create, assign, and track tasks within your organization. The app comes with features such as user management, task creation with due dates, task assignment to employees, task completion tracking, and administrative task tracking.

## Features

- User Management: The app allows you to create users with different roles. You can assign roles to users based on their responsibilities within the organization.

- Task Creation: The admin can create tasks and specify a due date for each task. This helps in organizing and prioritizing tasks effectively.

- Task Assignment: Tasks can be assigned to specific employees. By assigning tasks to individuals, you can ensure clear ownership and streamline task distribution.

- Task Completion: Users can mark tasks as complete once they finish working on them. This provides a visual indicator of the progress made on each task.

- Administrative Task Tracking: Admin users have access to a task tracking feature. This allows them to monitor the tasks assigned to different users and track their progress. It helps in identifying bottlenecks, ensuring timely completion, and balancing workload among team members.

## Installation

To install and run the Task Management App locally, follow these steps:

1. Clone the project
2. Go to the project root directory and run composer install and npm install
3. Create .env file and copy content from .env.example
4. Run php artisan key:generate from terminal
5. Change database information in .env
6. Run migrations by executing php artisan migrate , Then Run  php artisan db:seed if you want use faker database records,
7. Start the project by running php artisan serve then npm run dev

8. Access the application in your web browser at http://localhost:8000/admin, with this credentials

`
userName: madhu@gmail.com
Pswd    :password
