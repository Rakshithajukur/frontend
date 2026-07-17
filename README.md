# UniVerse ERP - Student Management System

A premium University Student Management System and SaaS Dashboard designed with glassmorphic aesthetics, soft drop shadows, custom scrollbars, and fluid navigation paths. 

Built using **React (Vite)**, **Chart.js**, and vanilla **CSS variables**, supporting real-time theme swapping (Light and Dark mode) and localized storage.

## Folder Directory Structure

```text
Student-Management-System/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Sidebar/          # Collapsible main navigation
│   │   ├── Navbar/           # Global quick-actions and notifications center
│   │   ├── Charts/           # Line & Bar chart visualization (Chart.js)
│   │   ├── Calendar/         # Interactive monthly July 2026 calendar cell tracker
│   │   ├── AIAssistant/      # Floating chatbot assistant (mock context-aware AI replies)
│   │   └── Notifications/    # Global interactive toast elements
│   ├── context/
│   │   └── AppContext.jsx    # Unified React Context State management
│   ├── data/
│   │   ├── students.json      # Profile, batch info, and classmates list
│   │   ├── attendance.json    # Weekly/monthly attendances and detailed logs
│   │   ├── assignments.json   # High/Medium/Low priority homework assignments
│   │   ├── courses.json       # Syllabuses, room numbers, and faculty details
│   │   ├── timetable.json     # Slot hours and weekly schedules
│   │   ├── exams.json         # Exam schedules and Hall Ticket details
│   │   ├── fees.json          # Tuition invoices and payments history
│   │   ├── books.json         # Borrowed/Catalog library listings
│   │   ├── events.json        # Hackathon contest details and club memberships
│   │   ├── placement.json     # Placement drive metrics and resume metadata
│   │   └── certificates.json  # Badge claims and course certificates
│   ├── pages/
│   │   ├── Login/
│   │   ├── Signup/
│   │   ├── ForgotPassword/
│   │   ├── Dashboard/
│   │   ├── Profile/
│   │   ├── Attendance/
│   │   ├── Academics/
│   │   ├── Assignments/
│   │   ├── Courses/
│   │   ├── Timetable/
│   │   ├── Exams/
│   │   ├── Fees/
│   │   ├── Library/
│   │   ├── Certificates/
│   │   ├── Placement/
│   │   ├── Events/
│   │   ├── Calendar/
│   │   ├── Notifications/
│   │   └── Settings/
│   ├── styles/
│   │   └── global.css        # Premium SaaS tokens, variable definitions, and themes
│   ├── App.jsx               # Routes tree routing configurations
│   └── main.jsx              # React mount entrypoint
├── package.json
└── README.md
```

## Features List

1. **Authentication:** Completed floating labels, animated button submits, remember me, and password visibility toggles.
2. **Dashboard Overview:** Comprehensive GPA stand, course timeline tracks, quick action dashboard triggers, and dynamic time/date trackers.
3. **Attendance Tracker:** Graphical logs, warnings if percentages drop below 75%, and table logs.
4. **Academic Grading Matrix:** Dropdowns to switch semesters (1 to 6) updating grade lists, SGPAs, and Line charts.
5. **Careers & Placement Cell:** CGPA clearances check, resume uploaders, and job application registers.
6. **AI Bot Assistant:** Context-aware responses on GPA, attendance alerts, fees, and exam dates, with voice button triggers and suggestion chips.
7. **Syllabus & Receipt Modals:** Modal triggers for printing mock invoices and previewing syllabus units.

## Installation and Execution

To run this application locally:

1. Clone or navigate into the project workspace root:
   ```bash
   npm install
   ```
2. Run the developer local server:
   ```bash
   npm run dev
   ```
3. Open `http://localhost:5173` in your browser.
