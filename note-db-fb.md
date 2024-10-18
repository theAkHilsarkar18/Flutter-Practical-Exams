### Practical Exam Question (50 Marks)  
**Topic:** Flutter Application with SQLite and Firebase Integration  

---

#### **Question: Build a Flutter Note-Taking Application using SQLite and Firebase**

**Problem Statement:**

You are tasked with developing a basic Note-Taking application using Flutter. The app should allow users to store their notes locally in SQLite and synchronize them with Firebase for backup. Users should be able to categorize their notes and search through them. The task should be completed within **3 hours**.

---

### **Features to Implement (35 Marks Total)**

1. **Note Management with SQLite (15 Marks)**  
   - Create a local SQLite database to store notes.
   - Each note should have the following fields:
     - Title (String)
     - Content (String)
     - Date Created (Date)
     - Category (e.g., Work, Personal, Miscellaneous)
   - Implement **CRUD** (Create, Read, Update, Delete) operations for managing notes:
     - **Create a new note** (3 Marks)
     - **Read all notes** (Display them in a ListView) (3 Marks)
     - **Update note details** (3 Marks)
     - **Delete a note** (3 Marks)
     - **Categorize notes** (3 Marks)

2. **Firebase Integration for Cloud Backup (10 Marks)**  
   - Implement Firebase Authentication for user login/signup using email/password.
   - Backup notes to Firebase Firestore and allow restoring them:
     - **Upload notes** to Firestore for backup (5 Marks)
     - **Fetch notes** from Firestore and restore to local SQLite when needed (5 Marks)

3. **Search and Filter Notes (5 Marks)**  
   - Implement a search feature that allows users to search notes by title or content.
   - Provide filtering options to display notes by category.

5. **Basic Sorting (5 Marks)**  
   - Add functionality to sort notes either by creation date or by category.

---

### **UI Requirements (10 Marks Total)**

1. **App Layout & Design (5 Marks)**  
   - Design a simple, intuitive, and responsive UI.
   - Use Flutter widgets like `TextField`, `ListView`, `DropdownButton`, etc., for managing and displaying notes.
   - Include basic navigation between the note list and note editor screens.

2. **Note List UI & Sorting Options (5 Marks)**  
   - Display a list of notes with clear separation by category.
   - Include a search bar to search through notes and an option to sort them by date or category.

---

### **Submission Requirements (5 Marks Total)**

1. **Code Submission (3 Marks)**  
   - Submit the complete code on a public GitHub repository.
   - Ensure the code is properly commented, with a clear README file explaining how to set up and run the app.

2. **Demo Video (2 Marks)**  
   - Record a short video demonstrating the main features of the app (CRUD operations, cloud backup, and search/filter functionality).

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - SQLite Note Management (15 Marks)  
   - Firebase Cloud Backup (10 Marks)  
   - Search and Filter Notes (5 Marks)  
   - Basic Sorting (5 Marks)

- **UI Design (10 Marks)**  
   - App Layout & Design (5 Marks)  
   - Note List UI & Sorting Options (5 Marks)

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)

---

**Total Marks:** 50

**Time Limit:** 3 Hours
