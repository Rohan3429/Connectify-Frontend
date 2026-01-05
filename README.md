
Connectify is a social networking application for connecting people and sharing posts. This README includes setup, development, and deployment instructions. Replace placeholders with project-specific details where noted.

## Features

- User authentication (login / register)
- View and create posts
- Follow/unfollow users
- Real-time updates (if applicable)
- Responsive UI

## Tech stack

- JavaScript (primary)
- [Replace with framework] (e.g., React, Next.js, Vite, Create React App)
- Styling: [Replace with CSS / Tailwind / Styled-components]

## Roles & Permissions
   Admin
      Create / update / delete any user (students, faculty, proctors)
      Assign or change user roles (professor, proctor, clubLead, student)
      View all users and system data
      Bulk import/export user lists and reports (XLSX/CSV)
      Manage site configuration (env secrets, Cloudinary keys, JWT secret)
      
   Professor (Faculty)
      Login and manage own profile
      Create / update announcements
      Add / update student marks and attendance
      View students assigned to them (proctor relationships)
      Export student reports (XLSX)
      Participate in groups and real-time chat
      
   Proctor
      Add/create student accounts (bulk or individual)
      View and manage assigned students
      Nominate club leads
      Add / update marks and attendance for assigned students
      Participate in groups and real-time chat
      
   ClubLead
      Create / manage club groups and events
      Post club-level announcements
      Manage club members (invite/remove)
      Share club resources (projects, files)
      Participate in real-time group chat
      
   Student
      Register / login and manage own profile
      Upload profile photo and resumes
      View personal marks, attendance, projects, certifications
      Join and participate in groups and real-time chat
      Export own data (resume, reports)

1. Clone the repo

   ```bash
   git clone https://github.com/Rohan3429/Connectify-Frontend.git
   cd Connectify-Frontend
   ```

2. Install dependencies

   ```bash
   npm install
   # or
   # yarn install
   # pnpm install
   ```

3. Create a .env file based on .env.example and fill required variables (see below)


---

Notes: This README contains placeholders for framework, scripts, and variables. If you want me to detect exact scripts and env variables by reading the repository files (package.json, src/), make the repo public or paste the package.json and key files. Otherwise I can update the README further if you provide the specific commands and env names.
