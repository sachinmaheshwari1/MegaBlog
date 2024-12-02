# MegaBlog Documentation
[Live Link](https://megablog-5tor.onrender.com)

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Prerequisites](#prerequisites)
5. [Setup](#setup)
6. [Usage](#usage)

## Introduction
MegaBlog is a modern blogging platform that enables users to create, manage, and share blog posts. It is built using ReactJS for the frontend, TailwindCSS for styling, Redux Toolkit for state management, and Appwrite as the backend service.

## Technologies Used
- **ReactJS**: A JavaScript library for building user interfaces.
- **Appwrite**: A Backend-as-a-Service (BaaS) that provides various backend functionalities like authentication and database management.
- **TailwindCSS**: A utility-first CSS framework that allows for rapid UI development.
- **Redux Toolkit**: A powerful toolset for managing global state in React applications.

## Features
- Create, edit, and delete blog posts.
- User authentication and authorization using Appwrite.
- Responsive user interface with TailwindCSS.
- State management with Redux Toolkit.
- Integration of a rich text editor (TinyMCE) for content creation.

## Prerequisites
Before you begin, ensure that you have the following installed on your machine:
- Node.js (version 16.0.0 or higher)
- npm or yarn package manager
- An instance of Appwrite set up (refer to the [Appwrite Documentation](https://appwrite.io/docs) for details).

## Setup
To set up the project on your local machine, follow these steps:

1. Clone the repository:
```bash
    git clone https://github.com/yourusername/megablog.git
    cd megablog
```

2. Install the dependencies:
```bash
    npm install
 ```
3. Configure your Appwrite instance by setting up the necessary environment variables (e.g., project ID, API endpoint).
4. Start the development server:
```bash
npm run dev
```
## Usage
Once the application is running, you can access it in your web browser. You will be able to:

1. Sign up or log in to your account.
2. Create new blog posts using the rich text editor.
3. Edit or delete existing posts.
4. View and interact with other users' posts.



