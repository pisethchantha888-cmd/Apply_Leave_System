# HR Leave Management System

A professional leave management system for HR departments, deployed on Netlify.

## Features

- User authentication (login/logout)
- Apply for leaves (Annual Leave, Sick Leave)
- Leave approval workflow for managers
- Dashboard with leave statistics
- Calendar view for approved leaves
- User management (add/delete users)
- Telegram notifications for leave approvals/rejections

## Default Login Credentials

- **Admin**: ID: `admin`, Password: `admin123` (Manager role)
- **User**: ID: `piseth`, Password: `123456` (User role)

## Deployment on Netlify

1. Push this repository to GitHub
2. Log in to [Netlify](https://netlify.com)
3. Click "Add new site" > "Import an existing project"
4. Select your GitHub repository
5. Build settings:
   - Build command: (leave empty)
   - Publish directory: `.` (root)
6. Click "Deploy site"

The site will be live instantly!

## Local Development

Simply open `index.html` in a browser, or use:
```bash
npx serve .
```

## Data Storage

This system uses browser localStorage for data persistence. Data is stored locally in the browser, making it perfect for demo purposes and small teams.

## Technologies Used

- HTML5, CSS3, JavaScript (Vanilla)
- Tailwind CSS (CDN)
- FullCalendar.js (CDN)
- Font Awesome icons (CDN)
- localStorage for data persistence
