![Demo App](https://github.com/KasavRushikesh09/Telusko-JobPortal-1/blob/main/image.png)

This  is the combination of JobPortal-1 & JobApp

# JobApp

> **🚀 Live Demo:**
A full-stack e-commerce web application inspired by JobApp, built with React.JS, Spring-Boot.

## Table of Contents

- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Tech Stack](#tech-stack)
- [Folder Overview](#folder-overview)

## Project Structure

```
Telusko-JobPortal-1
├── frontend/                  # React frontend (App\my-app)
│   ├── public/
│   │   ├── index.html
│   │   ├── favicon.ico
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   ├── robots.txt
│   │   └── sitemap.xml       # Optional: Add for SEO
│   ├── src/
│   │   ├── components/
│   │   │   ├── Search.jsx    # Job search and display component

│   │   ├── App.jsx
│   │   ├── App.css
│   │   ├── index.css
│   │   ├── index.js
│   │   └── reportWebVitals.js
│   ├── .gitignore
|   |--- db.json            #sample data
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   └── setupTests.js         # Optional: Testing setup
├── backend/                   # Spring Boot backend (JobApp)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── project/
│   │   │   │           └── jobApp/
│   │   │   │               ├── JobAppApplication.java  # Main application class
│   │   │   │               ├── model/
│   │   │   │               │   └── JobPost.java
│   │   │   │               ├── repo/
│   │   │   │               │   ├── JobRepo.java
│   │   │   │               ├── service/
│   │   │   │               │   ├── JobService.java
│   │   │   └── resources/
│   │   │       ├── application.properties            # App config (DB, server port)
│   │   └── test/
│   │       ├── java/
│   │       │   └── com/
│   │       │       └── project/
│   │       │           └── jobApp/
│   │       │               └── JobAppApplicationTests.java
│   │       └── resources/
│   ├── .gitignore
│   ├── pom.xml               # Maven dependencies (Spring Boot, JPA, etc.)
│   ├── README.md
│   └── mvnw                   # Maven wrapper
├── docs/                      # Optional: Documentation
│   ├── api.md                 # API endpoints
│   └── deployment.md          # Deployment guide
├── .gitignore                 # Root-level gitignore
├── docker-compose.yml         # Optional: For containerization
└── README.md                  # Overall project README
```

---

## Getting Started

### Prerequisites

- ReactJs
- npm, yarn, or pnpm

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KasavRushikesh09/Telusko-JobPortal-1.git
   cd Telusko-JobPortal-1
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server:**
   ```bash
   npm start
   ```

4. **Open your browser:**
   Visit [http://localhost:3000](http://localhost:3001) to view the app.

---

## Tech Stack

- **Frontend:** React.
- **State Management:** React Context API
- **Package Management:** npm.

---

- Built with [Next.js](https://nextjs.org/), [React](https://react.dev/), and [Tailwind CSS](https://tailwindcss.com/) 
