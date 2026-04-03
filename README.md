# EduParul — College Student Management System

A dark-themed, single-page student portal web application built with pure HTML, CSS, and JavaScript. Designed for Parul University students to access academic information in one place.

---

## 📋 Overview

EduParul is a frontend-only student dashboard that simulates a college management portal. It features a fixed sidebar navigation with multiple page sections, all rendered within a single HTML file — no backend or framework required.

**Demo Student:** Ritesh Dhaka | B.Tech Information Technology | Semester 5 | Parul University

---

## ✨ Features

### 📊 Dashboard
- Summary stat cards (CGPA, attendance %, pending fees, upcoming exams)
- Subject-wise grade bar chart (DSA, DBMS, OS, Math, Physics, English)
- Recent activity feed
- Quick-access overview of upcoming events

### 🗓 Attendance
- Monthly calendar view with color-coded days (Present / Absent / Holiday)
- Subject-wise attendance progress bars with percentage indicators
- Circle progress indicators per subject
- Overall attendance summary

### 📝 Results
- Semester-wise result table with subject codes, marks, and grades
- Visual grade chart
- CGPA display and grade summary

### 💰 Fee Management
- Fee payment timeline (Paid / Pending / Overdue)
- Installment-wise breakdown with due dates and amounts
- Payment status badges

### 💬 Feedback
- Star-rating system per subject/faculty
- Feedback form with subject selector and text input
- Submit confirmation with visual feedback

### 🕐 Timetable
- Weekly timetable grid (Monday–Saturday)
- Color-coded subjects with room numbers
- Time slots from morning to afternoon

### 📢 Notice Board
- Urgent and general announcements
- Color-coded notice cards (Alert / Warning / Info)
- Date and department metadata per notice

### 👤 Profile
- Student personal information (Name, DOB, Gender, Aadhar, Blood Group, Contact)
- Academic details (Programme, Semester, Section, Roll No., Batch, CGPA, Advisor, HOD)
- Downloadable document buttons (Bonafide, Character Certificate, Marksheet, ID Card, etc.)

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and content |
| CSS3 | Styling, animations, responsive grid |
| Vanilla JavaScript | Navigation, dynamic rendering, interactivity |
| Google Fonts | Space Mono (monospace) + DM Sans (UI) |

No frameworks, no libraries, no build tools required.

---

## 🎨 Design System

The UI uses a dark, terminal-inspired design with a consistent CSS variable system:

| Variable | Color | Usage |
|---|---|---|
| `--bg` | `#0a0e1a` | Page background |
| `--surface` | `#111827` | Card backgrounds |
| `--accent` | `#00d4ff` | Primary cyan accent |
| `--accent2` | `#7c3aed` | Purple accent |
| `--accent3` | `#10b981` | Green / success |
| `--accent4` | `#f59e0b` | Amber / warning |
| `--accent5` | `#ef4444` | Red / danger |

---

## 🚀 Getting Started

Since this is a pure static HTML file, no installation is needed.

1. Download or clone the file `web_2_.html`
2. Open it in any modern web browser:

```bash
# Simply double-click the file, or open via terminal:
open web_2_.html        # macOS
start web_2_.html       # Windows
xdg-open web_2_.html    # Linux
```

That's it — no server, no dependencies, no setup required.

---

## 📁 File Structure

```
web_2_.html          # Single self-contained HTML file
│
├── <style>          # All CSS (variables, components, layout, responsive)
├── <body>           # Sidebar, topbar, and all page sections
└── <script>         # Navigation logic, chart rendering, interactivity
```

---

## 🔧 Customization

To adapt this portal for a different student or institution, update the following in the HTML:

- **Student name/ID:** Search for `Ritesh Dhaka` and `2403031080059`
- **Institution name:** Change `EduParul` in the logo and title tag
- **Subjects:** Update the `subjects` array in the `<script>` section
- **Color theme:** Modify CSS variables in the `:root` block
- **Notices/Timetable/Fees:** Edit the corresponding HTML sections directly

---

## 📱 Responsive Behavior

- The 4-column stat grid collapses to 2 columns below `1100px`
- Sidebar is fixed-width (`240px`) and always visible
- The main content area adjusts with `margin-left: 240px`

> Note: Full mobile responsiveness (hamburger menu, collapsed sidebar) is not implemented in this version.

---

## 📄 License

This project is a frontend prototype/demo. All student data shown is fictional and for demonstration purposes only.
