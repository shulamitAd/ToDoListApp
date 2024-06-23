# ToDoListApp

Todo List App with ASP.NET Core 6 and Angular 16
This project is a simple todo list application built using ASP.NET Core 6 on the backend and Angular 16 on the frontend. It allows users to create, view, edit, and delete todo items.

Features
Create new todo items: Users can add new tasks to their todo list with a title ,description and planned date.
View existing todo items: The application displays a list of all currently saved todo items.
Edit existing todo items: Users can modify the details of existing tasks.
Delete todo items: Users can remove unwanted tasks from their todo list.

Prerequisites
Node.js and npm (or yarn): Download and install Node.js (https://nodejs.org/en) which includes npm. Alternatively, you can use a package manager like yarn (https://classic.yarnpkg.com/lang/en/docs/install/).
.NET 6 SDK: Download and install the .NET 6 SDK from the official Microsoft website (https://dotnet.microsoft.com/en-us/download).

Installation
Clone this repository or download the source code.
Open a terminal or command prompt and navigate to the project directory.
Run npm install (or yarn install) to install the required dependencies for both the frontend and backend.

Running the Application
Start the backend:
Open a separate terminal window and navigate to the backend folder (e.g., backend).
Run dotnet run to start the ASP.NET Core 6 backend server. The default port is usually 5000, so you can access the API at http://localhost:5000/api/todos (assuming no configuration changes).

Start the frontend:
Navigate back to the main project directory.
Run ng serve to start the Angular development server. The default frontend development server usually runs at http://localhost:4200.

Usage
Open http://localhost:4200 in your web browser.
You should see the todo list application interface.
Existing todo items will be displayed in a list.
Click on an item to edit it, modify its details, and click "Update".
Use the "Delete" button next to an item to remove it from the list.
Click on "Add ToDo Item", enter a title, description and planned date for a new todo item and click "Add" to create it.


Built with
Backend: ASP.NET Core 6
Frontend: Angular 16
License
This project is licensed under the MIT License (see the LICENSE file for details).

Feel free to customize and extend this project further based on your needs!
