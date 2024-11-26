### **Smart Notes App**  
**Time Limit:** 3 Hours  
**Marks:** 50  

**Problem Statement:**  

Develop a **Smart Notes App** using Flutter. The app should allow users to create, manage, and categorize notes locally using SQLite and synchronize them with Firebase for cloud backup. Additional features like search, filter, and sorting should make it easier to manage a large set of notes. The task should be completed within **3 hours**.

---

### **Features to Implement (35 Marks Total)**  

1. **Note Management with SQLite (15 Marks)**  
   - Create a local SQLite database to handle note storage.
   - Each note should include:
     - **Title** (String)
     - **Content** (String)
     - **Date Created** (Date)
     - **Category** (e.g., Work, Personal, Study, Ideas)
     - **Priority** (e.g., High, Medium, Low)
   - Implement **CRUD** operations for note management:
     - **Create a new note** (3 Marks)
     - **Read all notes** (Display in a ListView/GridView) (3 Marks)
     - **Update note details** (3 Marks)
     - **Delete a note** (3 Marks)
     - **Categorize and prioritize notes** (3 Marks)

2. **Firebase Cloud Backup & Sync (10 Marks)**  
   - Implement user authentication using Firebase (Email/Password or Google).
   - Enable syncing of notes with Firebase Firestore:
     - **Backup notes** to Firestore for secure cloud storage (5 Marks)
     - **Restore notes** from Firestore to local SQLite database (5 Marks)

3. **Enhanced Search and Advanced Filters (5 Marks)**  
   - Implement a search feature to look for notes by title, content, or category.
   - Add filter options to display notes by category or priority.

4. **Improved Sorting Functionality (5 Marks)**  
   - Allow users to sort notes by:
     - Date created (Ascending/Descending)
     - Priority (High to Low / Low to High)
     - Alphabetical order (Title)

---

### **UI & User Experience Requirements (10 Marks Total)**  

1. **User-Friendly Layout & Design (5 Marks)**  
   - Design a clean, intuitive interface with easy navigation.
   - Use Flutter widgets like `TextField`, `ListView`, `DropdownButton`, and `GridView` for better note management.
   - Implement a tab-based or bottom navigation to switch between different note categories or priority levels.

2. **Note List Visualization & Sorting Options (5 Marks)**  
   - Display notes with color coding or icons indicating priority or category.
   - Include a search bar for quick access and buttons or drop-downs to sort notes by different criteria.

---

### **Submission Requirements (5 Marks Total)**  

1. **Code Submission (3 Marks)**  
   - Submit the complete source code on a GitHub repository.
   - Ensure the code is well-documented, and include a README file with setup and usage instructions.

2. **Feature Demonstration Video (2 Marks)**  
   - Record a short demo video showcasing the app’s core features (CRUD operations, cloud sync, search, and sorting).

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - SQLite Note Management (15 Marks)  
   - Firebase Cloud Sync (10 Marks)  
   - Enhanced Search & Filtering (5 Marks)  
   - Sorting Features (5 Marks)

- **UI & Design (10 Marks)**  
   - User-Friendly Layout & Navigation (5 Marks)  
   - Note List Visualization & Sorting UI (5 Marks)

- **Submission (5 Marks)**  
   - GitHub Code Submission (3 Marks)  
   - Feature Demo Video (2 Marks)

---

**Total Marks:** 50

**Time Limit:** 3 Hours
