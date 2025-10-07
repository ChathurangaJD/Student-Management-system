# Student-Management-system
<img width="1919" height="842" alt="Screenshot 2025-10-07 112819" src="https://github.com/user-attachments/assets/6663879b-3dbb-426f-a9b0-b9e61d545c1a" />

<img width="1919" height="844" alt="Screenshot 2025-10-07 112805" src="https://github.com/user-attachments/assets/b910a9eb-f82a-4368-8e73-a2a86a7ee38b" />

<img width="1919" height="845" alt="Screenshot 2025-10-07 112753" src="https://github.com/user-attachments/assets/feaa6104-ebee-49df-a25a-0155578d718c" />

<img width="1919" height="844" alt="Screenshot 2025-10-07 112735" src="https://github.com/user-attachments/assets/d600adb4-0716-4e6a-9498-05fe6a0d2bbe" />

<img width="1919" height="843" alt="Screenshot 2025-10-07 113131" src="https://github.com/user-attachments/assets/f654ce51-f54a-4802-8d00-3c8a0d6aeef7" />

EduManage — Student Management System

A modern, responsive front-end prototype for a Student Management System (login + dashboard) built with Tailwind CSS, Font Awesome and Chart.js. The repo contains a demo login page (index.html) and a dashboard/home page (home.html) with sample data and charts. 

Demo

Open index.html in your browser to see the Login page (clicking Sign in with demo credentials redirects to the dashboard home.html). 
Demo credentials:

Email: admin@edumanage.edu
Password: Welcome123

Features

Clean login page with theme (light/dark) toggle and client-side validation. 
Dashboard with sidebar navigation (Dashboard, Students, Teachers, Courses, Settings).
Charts showing enrollment trends and department distribution (Chart.js). 
Sample data for students, teachers and courses used to populate tables and UI components.
Responsive UI built using Tailwind CSS and Font Awesome icons.

Tech / Libraries

HTML, CSS (Tailwind via CDN)
Font Awesome (icons). 
Chart.js (charts). 
Pure client-side (no backend included). 

Usage / Run locally

1. Clone this repository.
2. Open index.html in any modern browser (no build step required). 
3. Use the demo credentials (see above) to enter the dashboard.

Project structure (suggested)
```
/ (root)
├─ index.html        # Login page (demo credentials & client-side validation)
├─ home.html         # Dashboard with charts, tables & sample data
├─ assets/           # (optional) images, icons, styles if you add them
└─ README.md
```

Customization ideas / Next steps

* Replace sample data with a real API (Node/Express + MongoDB or any REST backend). 
* Extract repeated styles/scripts into separate files and add a build pipeline (Vite / Webpack).
* Add authentication (server-side), role-based access control and persistence.
* Add unit/e2e tests (Jest / Cypress) and a CI pipeline.

