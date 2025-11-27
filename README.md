TASK 2 — To-Do List API (Basic
CRUD – Mini Version)
Objective
Implement minimal CRUD with an in-memory array.
Requirements
Use an array:
let todos = [
{ id: 1, task: "Learn Node", done: false }
];
Routes
1. GET /todos → List all tasks
2. POST /todos → Add a new task
Body example:
{ "task": "Practice Express" }
3. PATCH /todos/:id → Update
4. done to true
