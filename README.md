# 📘 Student Management System – Attendance Tracking (Group 16)

This repository contains UI mockups for the Attendance Tracking module of a student management ERP system. It showcases both *Admin desktop views* and *Student mobile views*, designed to support real-time attendance logging, gate access control, and feedback handling.

## 🧩 Module Overview

The system is divided into five core functional areas:

### 1. 🚪 Gate Entry
- Student presents ID card at entry gate.
- System verifies active status.
- ✅ If active: entry allowed and logged in database.
- ❌ If inactive: entry denied and student notified.

### 2. 📚 Course Attendance
- Student scans QR code displayed by lecturer.
- System verifies:
  - Identity (username & password)
  - Active status
  - Course/module enrollment
  - Time validity (within lecture hours)
  - Location validity (on campus)
- ✅ If valid: attendance recorded and student notified.
- ❌ If invalid: attendance denied and student/admin notified.

### 3. 🚪 Gate Exit
- Student taps ID card at exit gate.
- Exit time recorded and updated in database.

### 4. ⚠ Special Handling
- Attendance attempts outside premises → denied and student notified.
- Multiple failed attempts → flagged and reported to admin.

### 5. 🧑‍💼 Admin Activities
- Monitor student entry/exit logs.
- Review attendance records.
- Handle invalid attempt reports.
- Generate summaries for course attendance and gate access.

## 🖼 UI Screenshots

The UI is split into two folders:

### 📂 Admin Desktop View
- Admin dashboard.png
- Attendance.png, Attendance 2.png, Attendance 3.png
- Login.png
- Report generate.png, Report generate 2.png
- Student dashboard.png

### 📂 Student Mobile View
- Student login.png
- Home.png
- Mark attendance.png
- My Attendance.png
- Qr scanner.png
- Feedbacks.png, Feedbacks (success, errors).png
- exit feedback.png

## 🧠 References Links

A User interfaces are available via figma.com:
🔗 [View Figma design](https://www.figma.com/design/HcKIRhzZZ0mae88WuyF0vj/ERP-System?node-id=0-1&t=Qg0TPhNDyfBPIGvQ-1)

A visual representation of the system logic and flow is available via Draw.io:
🔗 [View Diagram](https://drive.google.com/file/d/1eWsV5bDUciUfio4m6PstDrV4HuboIOzJ/view?usp=sharing)


## 👥 Team Members – Group 16

| Name                  | Index   |
|-----------------------|---------|
| A.V.I.G Akmeemana     | 34187   |
| J.T.D Mendis          | 34230   |
| D.G.P.K Karunasena    | 34173   |
| A.S Ruwanpura         | 34177   |
| R.D.I.M Ranasinghe    | 34217   |
| R.D.C Akalanka        | 34176   |
| P.H.J Chandrathilaka  | 33645   |
| R.P.C.N Gimhani       | 34237   |
| M.A.M Kalpana         | 34238   |

---
