# Code by PanhaPhin
# Full Stack Angular 17 + .NET 8 Library Management System
 Library Management System


 Steps:
1. Clone the Repository.
2. Create Database with any name eg. ABC
2. Open API solution in Visual Studio 2022
3. Go to appsettings.json and update the database string in "DB" section.
4. Also fill from email and email code. (optional)
5. Open Package manager console and run update-database command.
6. Now run API solution.
7. Go to UI folder and open in Visual Studio Code.
8. Run npm install, and then ng serve
9. Project will be running.




Open http://localhost:3000 in your browser to view the result.

You can start editing the page by modifying pages/index.js. The app auto-updates as you edit.

📡 API Routes
API routes live in the pages/api directory and are mapped to /api/*. For example:

http://localhost:3000/api/hello → pages/api/hello.js

Learn more about API routes here.


src/
│
├── app/                 # Core app logic and features
│   ├── components/      # Reusable UI components
│   ├── services/        # Services for business logic
│   ├── models/          # Interfaces & models
│   └── app.module.ts    # Root module
│
├── assets/              # Static assets (images, styles, etc.)
├── environments/        # Environment-specific settings
└── index.html           # Entry point HTML



Prerequisites
Node.js (v16 or higher recommended)

Angular CLI

npm install -g @angular/cli
npm install
