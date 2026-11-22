# E-Aduan Kolej: Hostel Maintenance and Repair System

A role-based web application designed for managing hostel maintenance and facility repair complaints across residential blocks, built for **CSC584 (Enterprise Programming)** at **Universiti Teknologi MARA (UiTM)**.

---

## Course & Team Information

- **Course:** CSC584 – Enterprise Programming
- **Programme:** Bachelor of Information Technology (Hons.), College of Computing, Informatics, and Mathematics, UiTM
- **Project Title:** E-Aduan Kolej: Hostel Maintenance and Repair
- **Team Members:**
  - Alif Imran Bin Thaffawi (`2025164661`)
  - Muhammad Arif Fitri Bin Suhaimi (`2025508407`)
  - Muhammad Wafiy Bin Mohd Nasir (`2025152221`)
  - Muhammad Danial Bin Abdul Kadir (`2025397075`)
  - Muhammad Izzat Hakimi Bin Khairudin (`2025124107`)

---

## Key Features & Role Views

### 1. Authentication (`Login` / `Register`)
- Email and password sign-in with **Remember me**, **Forgot password?**, and account registration support.

### 2. Student View
- **Student Dashboard & Submit New Complaint:** Overview of recent complaints and a submission form capturing complaint title, issue category, location/room number, detailed description, and an optional photo upload.
- **My Complaints History:** Track submitted tickets and current statuses (such as *In Progress* or *Pending*).
- **Notifications:** Real-time updates on complaint milestones (e.g., *Technician Assigned*, *Complaint Received*, *Complaint Resolved*).
- **Student Profile:** View student details, contact info, and college/ID records.

### 3. Technician View
- **Assigned Complaints & Completed Jobs:** Searchable job queue (by ID, category, or location) with tabs for *Assigned Complaints* and *Completed Jobs* to inspect reported issues (such as corridor/study area lighting or room repairs) and update progress.
- **Technician Profile:** Manage technician details, staff ID, specialization (e.g., *Electrical & Plumbing*), assigned college, and contact information.

### 4. Administrator View
- **Administrator Dashboard:** High-level summary of total complaints and status breakdowns (*Pending*, *In Progress*, *Resolved*, *Rejected*).
- **Complaint Management:** Filter/search complaints by ID or complainant, review block/location and dates, and update complaint statuses.
- **Complaint Calendar:** Monthly calendar view (e.g., October 2026) to monitor complaint activity and schedules.

---

## Project Structure

```text
e-aduan-kolej/
├── src/
│   ├── student/
│   ├── technician/
│   └── admin/
└── README.md
```

## How to Run

1. **Download or clone the project files**
   - Place `index.html` (and any related CSS/JS/assets) in a project folder on your computer.

2. **Open in a web browser**
   - Double-click `index.html` to open it directly in Chrome, Edge, Firefox, or Safari.

3. **Run with a local development server (recommended)**
   - If you use **VS Code**, install the **Live Server** extension, right-click `index.html`, and select **Open with Live Server**.
   - Or run a quick local server from your terminal inside the project folder.
