
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

## 🔐 Roles & Permissions

### 🛠 Admin
- Create, update, and delete any user (students, faculty, proctors)
- Assign or change user roles (professor, proctor, clubLead, student)
- View all users and system-wide data
- Bulk import/export users and reports (XLSX / CSV)
- Manage site configuration (environment variables, Cloudinary keys, JWT secrets)

---

### 🎓 Professor (Faculty)
- Login and manage own profile
- Create and update announcements
- Add and update student marks and attendance
- View students assigned through proctor relationships
- Export student reports (XLSX)
- Participate in groups and real-time chat

---

### 👨‍🏫 Proctor
- Create student accounts (individual or bulk)
- View and manage assigned students
- Nominate and manage club leads
- Add and update marks and attendance for assigned students
- Participate in groups and real-time chat

---

### 🏫 Club Lead
- Create and manage club groups and events
- Post club-level announcements
- Manage club members (invite/remove)
- Share club resources (projects, files)
- Participate in real-time group chat

---

### 🎒 Student
- Register, login, and manage own profile
- Upload profile photo and resumes
- View personal marks, attendance, projects, and certifications
- Join and participate in groups and real-time chat
- Export personal data (resume, reports)


1. Clone the repo

   ```bash
   git clone https://github.com/Rohan3429/Connectify-Frontend.git
   cd Connectify-Frontend
   ```

2. Install dependencies

   ```bash
   npm install

3. Create a .env file based on .env.example and fill required variables (see below)
   MONGO_URI=mongodb://127.0.0.1:27017/connectify
   PORT=5000
   CLIENT_URL=http://localhost:5173
   
   ADMIN_EMAIL=admin@connectify.com
   ADMIN_PASSWORD=Admin@123
   
   JWT_SECRET=connectify_super_secret_key_123
   JWT_EXPIRES_IN=7d

---

Notes: This README contains placeholders for framework, scripts, and variables. If you want me to detect exact scripts and env variables by reading the repository files (package.json, src/), make the repo public or paste the package.json and key files. Otherwise I can update the README further if you provide the specific commands and env names.
