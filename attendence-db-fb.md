
---

## **Attendance Tracker App**  
**Time Limit:** 3 Hours  
**Marks:** 50  

**Problem Statement:**  
Develop an **Attendance Tracker App** that allows teachers to manage student attendance records efficiently. The app should save attendance data locally using **SQLite** and offer cloud backup with **Firebase**. Additionally, the app should include the ability to filter by student names and dates and support offline functionality.

---

### **Features (35 Marks Total)**  

1. **Attendance Management with SQLite (15 Marks Total)**  
   - Fields: Student Name, Class, Date, and Attendance Status (Present/Absent).  
   - Implement **CRUD operations** for managing attendance records:  
     - **Create** new attendance entries (4 Marks)  
     - **Read** and display all attendance records (4 Marks)  
     - **Update** existing attendance status (4 Marks)  
     - **Delete** records if necessary (3 Marks)

2. **Firebase Cloud Backup (10 Marks Total)**  
   - Implement Firebase Authentication for login/signup using email and password.  
   - Sync all attendance records to Firebase Firestore:  
     - **Upload records** to Firestore (5 Marks)  
     - **Fetch records** from Firestore and update the local SQLite database (5 Marks)  

3. **Advanced Filtering (5 Marks)**  
   - Implement a **filter option** to search by student name and/or class.  
   - Provide date filtering to easily review attendance records for a specific time period.  

4. **Offline Data Support (5 Marks)**  
   - Ensure the app functions without an internet connection using SQLite.  
   - Sync the locally stored data to Firebase when the device regains internet access.

---

### **UI Requirements (10 Marks Total)**  

1. **Clean Layout & Navigation (5 Marks)**  
   - Design a user-friendly interface with navigation between attendance records, filter options, and settings.  
   - Use a ListView to display the attendance records.  

2. **Visual Indicators (5 Marks)**  
   - Use a **toggle switch** for marking students as Present/Absent.  
   - Apply different colors to the list based on the attendance status (e.g., green for Present, red for Absent).

---

### **Submission (5 Marks Total)**  

1. **Code Submission (3 Marks)**  
   - Submit the code on a public GitHub repository with proper instructions in a README file.  
   - Ensure the code is well-documented with comments explaining the logic.

2. **Demo Video & Screenshots (2 Marks)**  
   - Create a short demo video showcasing the app’s features, including CRUD operations, filtering, and Firebase sync.  
   - Provide screenshots of the app’s UI, showing key features like attendance records and filter functionality.

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - SQLite Attendance Management (15 Marks)  
   - Firebase Cloud Backup (10 Marks)  
   - Advanced Filtering by Date & Name (5 Marks)  
   - Offline Support (5 Marks)  

- **UI Design (10 Marks)**  
   - Clean Layout & Navigation (5 Marks)  
   - Visual Indicators (5 Marks)  

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video & Screenshots (2 Marks)  

---

**Total Marks:** 50
