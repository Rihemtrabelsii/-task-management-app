# Task Management Application

## Overview

This is a simple Task Management Application built with Angular, designed to help users create, track, and manage their tasks efficiently. The application provides features like user registration, task creation, filtering, and basic task management.

## Features

- User Registration
- Create, Edit, and Delete Tasks
- Task Filtering by Category and Priority
- Responsive Design
- Simple and Intuitive Interface

## Technologies Used

- Angular
- TypeScript
- RxJS
- Tailwind CSS
- Angular Reactive Forms

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (version 16.x or later)
- npm (version 8.x or later)
- Angular CLI (version 14.x or later)

## Installation

1. Clone the repository
```bash
git clone 
cd task-management-app
```

2. Install dependencies
```bash
npm install
```

3. Run the development server
```bash
ng serve
```

4. Open your browser and navigate to `http://localhost:4200`

## Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── signup/
│   │   ├── task-list/
│   │   └── task-form-dialog/
│   ├── services/
│   │   ├── user.service.ts
│   │   ├── task.service.ts
│   │   ├── category.service.ts
│   │   └── priority.service.ts
|   |   └── auth.guard.ts
│   │   
│   └── models/
│       ├── user.model.ts
│       ├── task.model.ts
│       └── ...
├── environments/
│   └── environment.ts
└── ...
```

## Authentication

The application uses a simple local storage-based authentication mechanism. Users can sign up and are automatically logged in, with routes protected by an AuthGuard.

## API Integration

The application integrates with a backend API for:
- User registration
- Task CRUD operations
- Category and Priority management

```



