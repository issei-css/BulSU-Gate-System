# Web-Based Student Gate Restriction System Based on Student Schedule

## (with Mobile Application)

**Website Link:** https://bulsugatesystem.byethost6.com/

**APK Link:** [Download Mobile App](https://drive.google.com/file/d/1QV0_-nUcGocQmiV9cfnbk-5nEvnh1Yy8/view?usp=sharing)

---

## 🔑 Default Login Credentials

### 1. Admin

- **Email:** mainadmin@gmail.com
- **Password:** admin123
- **Access:** Full system administration

### 2. Staff

- **Email:** kahlilquiambao@staff.com
- **Password:** staff123
- **Access:** Schedule and student management

### 3. Guard

- **Main Campus - Gate 2:**
- **Password:** password123
- **Access:** Gate monitoring and student verification

### 4. Student

- **Student Email:** johnkahlil23@gmail.com
- **Password:** password123
- **Access:** Mobile app for schedule viewing and profile info

---

## 📖 System Overview

The **Web-Based Student Gate Restriction System** is a comprehensive solution designed to manage and monitor student entry and exit at campus gates based on their academic schedules. The system integrates a web-based admin panel with a mobile application to provide real-time gate access control.

## 👥 User Roles & Features

### 🔹 Administrator

**Access Level:** Full System Control

**Main Features:**

1. **Dashboard**

   - View real-time statistics (currently inside, today's entries, average stay time)
   - User distribution charts
   - Recent activity logs
   - Quick actions panel

2. **User Management** (`manage_users.php`)

   - Add, edit, and delete users (Admin, Staff, Guard)
   - Assign campus and gate access
   - Manage user roles and permissions
   - View user details and activity

3. **Department Management** (`manage_departments.php`)

   - Create and manage academic departments
   - Assign departments to specific campuses
   - Update department information
   - View department statistics

4. **Schedule Management** (`manage_schedules.php`)

   - Create class schedules for sections
   - View schedules in calendar format (Monday-Saturday)
   - Edit and delete schedules
   - Assign schedules to specific sections
   - Set schedule status (Active/Inactive)

5. **Request Management** (`manage_requests.php`)

   - Review special access requests from students
   - Approve or deny requests
   - View request history and details

6. **Reports** (`reports.php`)

   - Generate comprehensive reports
   - Entry/Exit logs
   - User activity reports
   - Campus-wise statistics
   - Download reports in various formats

7. **View Logs** (`view_logs.php`)
   - Monitor real-time gate activities
   - Filter logs by date, campus, gate, or user
   - Export log data
   - Track student entry/exit times

---

### 🔹 Staff

**Access Level:** Department-Specific Management

**Main Features:**

1. **Schedule Management**

   - Add schedules for sections within their department
   - View and edit existing schedules
   - Delete schedules
   - Set schedule status

2. **Student Management**

   - Add new students to the system
   - Update student information
   - Assign students to sections
   - Delete student records
   - View student schedules

3. **Section Management**
   - View sections within their department
   - Manage section assignments

**Key Pages:**

- `add_schedule.php` - Create new class schedules
- `view_schedules.php` - View all schedules
- `manage_students.php` - Student database management

---

### 🔹 Guard

**Access Level:** Gate Monitoring and Verification

**Main Features:**

1. **Student Verification**

   - Scan student QR codes
   - Verify student schedules in real-time
   - Check if student has class at the current time
   - View student information and photo

2. **Guest Verification**

   - Verify guest access codes
   - Check guest validity and purpose
   - Log guest entry/exit

3. **Dashboard**

   - Real-time entry/exit monitoring
   - View currently inside students
   - Today's statistics
   - Recent activity feed

4. **Manual Entry**
   - Log student entry/exit manually
   - Handle emergency situations
   - Add notes to logs

**Key Pages:**

- `guard-dashboard.php` - Main monitoring interface
- `gate-selection.php` - Select assigned gate

---

### 🔹 Student

**Access Level:** Mobile Application

**Main Features:**

1. **QR Code Access**

   - Generate personal QR code for gate entry
   - Dynamic QR code updates
   - Quick scan verification

2. **Schedule Viewing**

   - View daily class schedules
   - Weekly schedule overview
   - Upcoming classes notification

3. **Profile Management**

   - View personal information
   - Update contact details
   - Change password

4. **Access History**
   - View entry/exit logs
   - Track campus visits
   - Download attendance reports

---

**Handling Special Cases:**

- **Student forgot QR code:** Manual ID search
- **System shows no schedule:** Contact staff/admin
- **Guest without code:** Verify identity, contact admin
- **Emergency situations:** Allow entry, log manually with notes

---

## 🔧 Troubleshooting

### Common Issues

**1. Cannot Login**

- Verify credentials are correct
- Check if account is active
- Contact administrator

**2. QR Code Not Working**

- Ensure mobile app is updated
- Check internet connection
- Try manual ID entry

**3. Schedule Not Showing**

- Verify schedule is set to "Active"
- Check if assigned to correct section
- Contact staff or admin

**4. Reports Not Generating**

- Check date range is valid
- Ensure data exists for selected period
- Try different browser

**5. Mobile App Issues**

- Update to latest version
- Clear app cache
- Reinstall if necessary

---

## 📊 System Architecture

### Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP, node.js
- **Database:** Firebase Realtime Database
- **Hosting:** InfinityFree Web Hosting
- **Mobile:** Android (APK)

### Security Features

- Session-based authentication
- Role-based access control
- Password encryption
- Secure Firebase rules
- Input validation and sanitization

---

## 📞 Support & Contact

For technical support or inquiries, please contact:

- **Department:** College of Information and Communications Technology
- **Institution:** Bulacan State University

---

## 👨‍💻 Developers

**Submitted by:**

- **Section:** BSIT 3H - Group 3

**Members:**

- Quiambao, John Kahlil E.
- Landayan, John Louie A.
- Rieza, Micke Laurence.
- Sipagan, Jansenn Isee.

**Submitted to:**

- Alex P. Caparas, D.Eng.

**Institution:**

- College of Information and Communications Technology
- Bulacan State University

**Date:** November 17, 2025

---

## 📄 License

This system is developed as a final project for academic purposes.

---

## 🔄 Version History

- **Version 1.0** (November 2025) - Initial release
  - Admin, Staff, Guard, and Student modules
  - Schedule-based gate restriction
  - QR code verification
  - Mobile application
  - Comprehensive reporting

---

## 📝 Additional Notes

### System Limitations

- Requires stable internet connection
- Mobile app currently supports Android only
- QR codes expire after certain period for security
- Maximum file upload size for imports: 5MB

### Best Practices

1. **Admins:** Regularly backup user and schedule data
2. **Staff:** Keep student information up-to-date
3. **Guards:** Report system issues immediately
4. **Students:** Keep mobile app updated and QR code ready

### Future Enhancements

- iOS mobile application
- Biometric authentication
- Advanced analytics dashboard
- SMS notifications
- Parent portal access
- Integration with school LMS

---

**For the complete system documentation and source code, please refer to the project repository.**

---

_Last Updated: November 17, 2025_
