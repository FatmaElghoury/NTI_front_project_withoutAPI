# Devora — Frontend 🎓

> Angular frontend for Devora, an e-learning platform teaching programming courses to high-school & baccalaureate students.

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![Angular](https://img.shields.io/badge/Angular-21-red)

## 📖 About

Devora is the student-facing and admin-facing web app for an e-learning system teaching programming. Students work through structured courses and lessons, take quizzes and exams, and track their progress and achievements. Admins manage courses, quizzes, and students from a dedicated dashboard. Built with Angular as part of the NTI program.

> ⚠️ **Frontend only** — this repo currently has no backend/API. All data is handled on the frontend for now; backend integration is planned for a later phase.

## ✨ Features

**Student**
- 🔐 Authentication (Sign up, Sign in, Forgot/Reset password)
- 📚 Course & lesson browsing
- 📝 Quizzes & exams with results
- 📊 Progress tracking & achievements
- 👤 Profile & settings

**Admin**
- 🛠️ Dashboard overview
- 📖 Add / manage / delete courses
- ❓ Quiz management
- 🧑‍🎓 Student management
- ⚙️ Admin profile & settings

**Design**
- 🎨 Devora design system (Figma-based UI)

## 🧱 Tech Stack

Angular 21 · TypeScript · HTML · SCSS

## 🚀 Getting Started

**Prerequisites:** Node.js and the Angular CLI (`npm install -g @angular/cli`)

```bash
git clone https://github.com/DEVORA-LEARNING-PROGRAMMING/Devora.git
cd Devora
npm install
ng serve
```

Navigate to `http://localhost:4200/` — the app reloads automatically on file changes.

## 🏗️ Building

```bash
ng build
```

Build artifacts are output to the `dist/` directory, optimized for production by default.

## 📁 Project Structure

```
src/app/                # Guards, interceptors, services, models
├── features/
│   ├── REGISTER/           # Sign up, sign in, password reset
│   ├── student-section/    # Landing, dashboard, courses, lessons, exams, quizzes, progress, achievements, profile, settings
│   └── admin/               # Dashboard, course/quiz/student management, admin profile & settings
└── shared/                 # Sidebar(s), search header, shared services
```

## 🤝 Contributing

1. Create a branch off `main`
2. Make your changes
3. Open a pull request for review

## 📌 Status

🚧 Actively in development. No backend/API yet — planned for a future phase.
