
---

## **Daily Habit Tracker App**  
**Time Limit:** 3 Hours  
**Marks:** 50  

**Problem Statement:**  
Create a **Daily Habit Tracker App** that helps users track their daily habits. The app should store habits in **SQLite**, sync them with **Firebase**, and allow users to view their progress over time. Users should be able to set reminders for each habit and categorize them.

---

### **Features (35 Marks Total)**  

1. **Enhanced Habit Management with SQLite (15 Marks Total)**  
   - Fields: Habit Name, Category (e.g., Health, Work, Personal), Target Days, Reminder Time, and Progress (e.g., Completed/Not Completed).  
   - Implement **CRUD operations** for managing habits:  
     - **Create** a new habit with categories and reminders (4 Marks)  
     - **View** all habits grouped by category (3 Marks)  
     - **Update** habit details, including target days and reminder time (4 Marks)  
     - **Delete** habits when needed (4 Marks)

2. **Firebase Sync and Backup (10 Marks Total)**  
   - Implement Firebase Authentication using email and password for user accounts.  
   - Sync all habit data with Firestore:  
     - **Upload and update** habit information to Firestore (5 Marks)  
     - **Retrieve habits** from Firestore and sync with the local SQLite database (5 Marks)

3. **Progress and Reminders (5 Marks Total)**  
   - Track daily habit progress and display completion status (e.g., X/7 days completed).  
   - Send **local notifications** to remind users of pending habits (if reminders are set).

4. **Offline Data Management & Sync (5 Marks Total)**  
   - Ensure the app functions fully offline using SQLite.  
   - Sync the local data with Firebase when the device goes online.

---

### **UI Requirements (10 Marks Total)**  

1. **User-Friendly Interface (5 Marks)**  
   - Design a clean layout with habits displayed in a ListView, categorized by habit type.  
   - Use a Floating Action Button (FAB) to add new habits.

2. **Visual Progress Indicators (5 Marks)**  
   - Use progress bars or percentage indicators to visually show habit completion.  
   - Differentiate completed and pending habits with colors or icons.

---

### **Submission (5 Marks Total)**  

1. **Code Submission (3 Marks)**  
   - Upload the code to a GitHub repository with clear setup instructions.  
   - Provide code comments and documentation as needed.

2. **Demo Video (2 Marks)**  
   - Create a short video demonstration covering app features like adding, tracking, and syncing habits.

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - Enhanced Habit Management with SQLite (15 Marks)  
   - Firebase Sync and Backup (10 Marks)  
   - Progress and Reminders (5 Marks)  
   - Offline Data Management & Sync (5 Marks)  

- **UI Design (10 Marks)**  
   - User-Friendly Interface (5 Marks)  
   - Visual Progress Indicators (5 Marks)  

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)  

---

**Total Marks:** 50
