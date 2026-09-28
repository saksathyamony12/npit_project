# University Website Project Structure

This is the complete directory structure for the University Website project as specified.

## Structure Overview

- **public/**: Public-facing pages (about, faculties, projects, contact, register, login, logout)
- **admin/**: Admin dashboard and management modules
  - registrations/, students/, teachers/, majors/, batches/, classes/, courses/, sessions/, attendance/, exams/, scores/, uploads/, telegram/
- **teacher/**: Teacher portal (dashboard, classes, students, upload, attendance, scores, sessions, comments)
- **elearning/**: Student e-learning portal
- **telegram/**: Telegram bot integration (webhook, API, commands, cron jobs)
- **includes/**: Shared PHP includes (config, database, auth, permissions, functions, headers, sidebars)
- **assets/**: CSS, JS, images, fonts
- **uploads/**: User-uploaded files (profiles, lessons, scores, projects)
- **database/**: SQL schema and seed data

## Root Files
- index.php: Entry point
- .htaccess: Apache configuration
- .env: Environment variables

All PHP files are currently empty stubs ready for implementation.
