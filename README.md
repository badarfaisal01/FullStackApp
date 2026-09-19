# FullStackApp

A full-stack web application built with React and a backend API, providing a modern frontend interface with API integration, routing, data visualization, and responsive UI.


## 📌 Overview

FullStackApp is a full-stack web application designed to demonstrate the integration of a modern React frontend with a backend API.

The project separates the frontend and backend into dedicated applications, allowing the frontend to communicate with the backend through HTTP API requests.

The frontend is built with React and Vite and includes client-side routing, API communication, charts, cookie handling, reusable UI components, and responsive styling.

## 🛠️ Tech Stack

### Frontend

* React 18
* Vite
* React Router
* Axios
* Tailwind CSS
* Chart.js
* React Chart.js 2
* React Icons
* React Cookie
* ESLint

### Backend

* Backend API
* REST-style HTTP communication
* Server-side data processing

## 📂 Project Structure

```text
FullStackApp/
│
├── Web_Project_Backend/
│   └── Backend API and server-side functionality
│
├── Web_Project_Frontend_/
│   └── my-project/
│       ├── src/
│       ├── public/
│       ├── package.json
│       ├── vite.config.js
│       └── ...
│
└── README.md
```

## ✨ Frontend Features

* React-based component architecture
* Client-side routing with React Router
* REST API integration using Axios
* Interactive charts and data visualization
* Cookie-based client-side functionality
* Responsive UI
* Tailwind CSS styling
* React Icons integration
* ESLint-based code quality checks
* Vite development and production build workflow

## 🔄 Application Architecture

The application follows a separated frontend/backend architecture:

```text
              ┌─────────────────────┐
              │      React UI       │
              │   React + Vite      │
              └──────────┬──────────┘
                         │
                         │ HTTP / API
                         ▼
              ┌─────────────────────┐
              │    Backend API      │
              │  Server-side Logic  │
              └──────────┬──────────┘
                         │
                         ▼
                  Data / Services
```

The frontend communicates with the backend through API requests using Axios.

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* Git
* Backend runtime/environment required by the backend project

### 1. Clone the Repository

```bash
git clone https://github.com/badarfaisal01/FullStackApp.git
cd FullStackApp
```

### 2. Run the Frontend

Navigate to the React application:

```bash
cd Web_Project_Frontend_/my-project
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The Vite development server will provide a local URL in the terminal.

### 3. Build for Production

```bash
npm run build
```

### 4. Preview the Production Build

```bash
npm run preview
```

### 5. Run Linting

```bash
npm run lint
```

## 📦 Frontend Dependencies

The project uses several libraries to provide its frontend functionality:

| Package          | Purpose                                |
| ---------------- | -------------------------------------- |
| React            | Building the user interface            |
| Vite             | Frontend development and build tooling |
| Axios            | HTTP/API requests                      |
| React Router     | Client-side navigation                 |
| Chart.js         | Data visualization                     |
| React Chart.js 2 | React integration for Chart.js         |
| React Cookie     | Cookie management                      |
| React Icons      | Icon library                           |
| Tailwind CSS     | Utility-first styling                  |
| ESLint           | Code quality and linting               |

## 🌐 Deployment

The frontend is deployed using Vercel.

Live application:

https://full-stack-app-rosy.vercel.app/

## 🔐 Environment Variables

If the backend API URL or other environment-specific configuration is required, create an environment file in the frontend project.

For example:

```env
VITE_API_URL=your_backend_api_url
```

Then use the environment variable inside the application when configuring API requests.

> Do not commit private API keys, credentials, database passwords, or other sensitive information to GitHub.

## 🧪 Development

The frontend uses Vite's development server with Hot Module Replacement (HMR), allowing changes to be reflected quickly during development.

Available commands:

```bash
npm run dev
npm run build
npm run preview
npm run lint
```

## 📈 Project Goals

This project demonstrates practical full-stack development concepts including:

* Frontend and backend separation
* REST API communication
* React component development
* Client-side routing
* API integration
* Data visualization
* Responsive UI development
* Production frontend builds
* Deployment with Vercel

## 👨‍💻 Author

**Badar Faisal**

GitHub: https://github.com/badarfaisal01

## 📄 License

This project is available for educational and development purposes.
