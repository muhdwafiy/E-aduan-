# E-Aduan Kolej: Hostel Maintenance and Repair System

A role-based web application designed for managing hostel maintenance and facility repair complaints across residential blocks, built for **CSC584 (Enterprise Programming)** at **Universiti Teknologi MARA (UiTM)**[cite: 2, 3, 4, 5, 6, 7].

---

## Course & Team Information

- **Course:** CSC584 – Enterprise Programming[cite: 2]
- **Programme:** Bachelor of Information Technology (Hons.), College of Computing, Informatics, and Mathematics, UiTM[cite: 2]
- **Project Title:** E-Aduan Kolej: Hostel Maintenance and Repair[cite: 2]
- **Team Members:**
  - Alif Imran Bin Thaffawi (`2025164661`)[cite: 2]
  - Muhammad Arif Fitri Bin Suhaimi (`2025508407`)[cite: 2]
  - Muhammad Wafiy Bin Mohd Nasir (`2025152221`)[cite: 2]
  - Muhammad Danial Bin Abdul Kadir (`2025397075`)[cite: 2]
  - Muhammad Izzat Hakimi Bin Khairudin (`2025124107`)[cite: 2]

---

## Key Features & Role Views

### 1. Authentication (`Login` / `Register`)
- Email and password sign-in with **Remember me**, **Forgot password?**, and account registration support[cite: 4].

### 2. Student View
- **Student Dashboard & Submit New Complaint:** Overview of recent complaints and a submission form capturing complaint title, issue category, location/room number, detailed description, and an optional photo upload[cite: 5].
- **My Complaints History:** Track submitted tickets and current statuses (such as *In Progress* or *Pending*)[cite: 5, 6].
- **Notifications:** Real-time updates on complaint milestones (e.g., *Technician Assigned*, *Complaint Received*, *Complaint Resolved*)[cite: 6].
- **Student Profile:** View student details, contact info, and college/ID records[cite: 6].

### 3. Technician View
- **Assigned Complaints & Completed Jobs:** Searchable job queue (by ID, category, or location) with tabs for *Assigned Complaints* and *Completed Jobs* to inspect reported issues (such as corridor/study area lighting or room repairs) and update progress[cite: 7].
- **Technician Profile:** Manage technician details, staff ID, specialization (e.g., *Electrical & Plumbing*), assigned college, and contact information.

### 4. Administrator View
- **Administrator Dashboard:** High-level summary of total complaints and status breakdowns (*Pending*, *In Progress*, *Resolved*, *Rejected*)[cite: 3].
- **Complaint Management:** Filter/search complaints by ID or complainant, review block/location and dates, and update complaint statuses[cite: 3].
- **Complaint Calendar:** Monthly calendar view (e.g., October 2026) to monitor complaint activity and schedules[cite: 3].

---

## Project Structure

```text
e-aduan-kolej/
├── docs/
│   └── CSC584-ENTERPRISE PROGRAMMING E-ADUAN KOLEJ OUTPUT.pdf
├── src/
│   ├── auth/
│   ├── student/
│   ├── technician/
│   └── admin/
└── README.md
```

*(Update `src/` folders above to match your exact web framework, backend/database files, and setup commands.)*

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd e-aduan-kolej
   ```
2. **Configure environment & database**
   - Set up your database connection and environment variables (e.g., database host, credentials, and authentication config) before running the server.
3. **Run the application**
   - Start your application server/container and open the login screen in your browser[cite: 4].

---

## License

Academic coursework project prepared for **CSC584 (Enterprise Programming)** at UiTM[cite: 2].
