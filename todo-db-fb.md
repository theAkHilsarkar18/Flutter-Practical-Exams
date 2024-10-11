### Practical Exam Question (50 Marks)  
**Topic:** Flutter Application with SQLite and Firebase Integration  

---

#### **Question: Build a Flutter To-Do Application using SQLite and Firebase**

**Problem Statement:**

You are tasked with developing a To-Do application using Flutter. The app should allow users to manage their tasks locally using SQLite and synchronize with Firebase for cloud storage. The following features and UI requirements must be met.

---

### **Features to Implement (35 Marks Total)**

1. **Task Management with SQLite (15 Marks)**  
   - Create a local SQLite database to store tasks.
   - Each task should have the following fields:
     - Title (String)
     - Description (String)
     - Due Date (Date)
     - Status (Pending/Completed)
   - Implement **CRUD** (Create, Read, Update, Delete) operations for managing tasks:
     - **Create a new task** (3 Marks)
     - **Read all tasks** (Display them in a ListView) (3 Marks)
     - **Update task details** (3 Marks)
     - **Delete a task** (3 Marks)
     - **Mark task as completed** (3 Marks)

2. **Firebase Integration for Cloud Synchronization (10 Marks)**  
   - Implement Firebase Authentication, allowing the user to log in or sign up using email/password.
   - Sync tasks between the local SQLite database and Firebase Firestore:
     - **Upload tasks** to Firestore when the user is online (5 Marks)
     - **Fetch tasks** from Firestore and update the local SQLite database (5 Marks)

3. **Offline Support (5 Marks)**  
   - Ensure that the app works offline using SQLite, allowing the user to manage tasks.
   - When the device regains internet connection, synchronize the local tasks with Firebase (2.5 Marks for offline mode, 2.5 Marks for synchronization).

4. **Task Prioritization (5 Marks)**  
   - Implement a system to assign priority levels (e.g., High, Medium, Low) to tasks.
   - Sort tasks by their priority in the task list, with High-priority tasks appearing first.

---

### **UI Requirements (10 Marks Total)**

1. **App Layout & Design (5 Marks)**  
   - Create a clean, intuitive, and responsive UI.
   - Use Flutter widgets like `ListView`, `TextField`, `DatePicker`, `FloatingActionButton`, etc., to build the UI for managing tasks.
   - Include clear navigation between screens (e.g., task list screen, add/edit task screen, settings, etc.).

2. **Task List UI & Prioritization (5 Marks)**  
   - Display tasks in a user-friendly manner with indicators for pending, completed, and prioritized tasks.
   - Use different colors or icons to differentiate between high, medium, and low-priority tasks.
   - Include a search bar to filter tasks by title or description, and allow sorting by due date or priority.

---

### **Submission Requirements (5 Marks Total)**

1. **Code Submission (3 Marks)**  
   - Submit the complete code on a public GitHub repository.
   - Ensure that the code is properly commented, with a clear README file explaining how to set up and run the app.

2. **Demo Video (2 Marks)**  
   - Record a short video demonstrating the main features of the app (CRUD operations, synchronization with Firebase, offline mode, and task prioritization).

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - SQLite Task Management (15 Marks)  
   - Firebase Synchronization (10 Marks)  
   - Offline Support (5 Marks)  
   - Task Prioritization (5 Marks)

- **UI Design (10 Marks)**  
   - App Layout (5 Marks)  
   - Task List UI & Prioritization (5 Marks)

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)

---

**Total Marks:** 50
