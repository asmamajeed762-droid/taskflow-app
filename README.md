# TaskFlow App

## Project Description
TaskFlow is a simple task management web application that helps users organize their daily tasks efficiently. It allows users to add and view tasks through a clean and responsive interface. The application uses Supabase as a serverless backend, removing the need for custom server-side code.

## Key Features
- Add new tasks easily
- View all saved tasks instantly
- Delete unwanted tasks
- Responsive and user-friendly interface
- Serverless backend using Supabase
- Real-time data storage and retrieval

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Supabase (Database & API)
- **Hosting:** GitHub Pages

## Project Objective
The main objective of this project is to learn how a frontend application can communicate directly with a serverless backend using Supabase. It also demonstrates CRUD operations, API integration, and cloud-based data storage without writing a custom backend server.

## Database Setup
1. Create a `tasks` table in Supabase with the following columns:
   - `id` (int8, primary key)
   - `task` (text)
   - `created_at` (timestamptz)

2. Add your `SUPABASE_URL` and `SUPABASE_ANON_KEY` in your `index.html` file before running the project.

## Project Screenshot
![TaskFlow App](screenshot.png)

## Author
**Asima Majeed**
