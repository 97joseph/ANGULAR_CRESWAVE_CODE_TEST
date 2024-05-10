# ANGULAR_CRESWAVE_CODE_TEST

2. Project Overview

You are tasked with building a task management application using Angular. The
application should allow users to view tasks in a table format, add new tasks, edit
existing tasks, and delete tasks. Use Angular Material for UI components and
implement routing for navigating between different views.

4. Task Requirements
1. Task table View
● Display tasks in a table format using Angular Material's table component.
● Each row should display the task's title, description, status
(complete/incomplete) and actions (edit/delete).

2. Task details/edit View
   
● Implement a view to display task details in a form.
● Allow editing of task details (title, description, status).
● Provide an option to mark a task as complete/incomplete.
4. Task Service
● Create a service (TaskService) to manage tasks.
● Implement methods for fetching tasks, adding a new task, updating a
task, and deleting a task.
● Use HTTP requests (mocked or real) to communicate with a backend
(simulated using JSON-server, for example).

3. Routing
● Set up routing to navigate between the task table view (/tasks) and task
details/edit view (/tasks/:id).

6. Styling
● Use Angular Material for UI components (table, buttons, forms, etc.) or
Tailwind css for styling where applicable.
● Apply responsive design principles.

Evaluation Criteria
Candidates will be evaluated based on the following criteria:-
1) Code Quality
a) Angular best practices (components, services, modules).
b) Consistent coding style and naming conventions.
c) Error handling and validation.

3) Design Patterns
   
a) Use of Angular services for data management.
b) Separation of concerns (component logic vs. presentation).
c) Observable patterns with RxJS for async operations.

5) Functionality

3
a) Complete implementation of CRUD operations (fetch, add, update,
delete tasks).
b) Proper navigation and routing between views.
c) Responsive and intuitive user interface.
d) Ensure responsive design (mobile-friendly)

Ensure your code is well-organized, maintainable, and follows best practices.
Once you have completed the task, push your changes to your repository.
 
 ## Todo Application
 
 Developing simple to-do list app using angular and json-server as rest api:

To start the server run this command: json-server --watch db.json

The json-server starts and listens for request on port 3000, you can test it by going to http://localhost:3000/todos

