### Practical Exam Question (50 Marks)  
**Topic:** Flutter Application with SQLite and Firebase Integration  

---

#### **Question: Build a Flutter Shopping List Application using SQLite and Firebase**

**Time Limit:** The task should be completed within **3 hours**.

**Problem Statement:**

You are required to build a Shopping List application using Flutter. The app should store items locally in SQLite, allow users to categorize items, and synchronize the list with Firebase for cloud backup. Users should also be able to search and filter items.

---

### **Features to Implement (35 Marks Total)**

1. **Shopping List Management with SQLite (15 Marks)**  
   - Create a local SQLite database to store shopping list items.
   - Each item should have the following fields:
     - Item Name (String)
     - Quantity (Number)
     - Category (e.g., Groceries, Electronics, Clothing)
     - Purchased Status (Boolean - True/False)
   - Implement **CRUD** (Create, Read, Update, Delete) operations for managing shopping list items:
     - **Add a new item** (3 Marks)
     - **Read all items** (Display them in a ListView) (3 Marks)
     - **Update item details** (3 Marks)
     - **Delete an item** (3 Marks)
     - **Mark item as purchased** (3 Marks)

2. **Firebase Integration for Cloud Backup (10 Marks)**  
   - Implement Firebase Authentication to allow users to log in or sign up using email/password.
   - Sync the shopping list with Firebase Firestore:
     - **Upload shopping list items** to Firestore for backup (5 Marks)
     - **Fetch items** from Firestore and update the local SQLite database (5 Marks)

3. **Search and Filter Items (5 Marks)**  
   - Implement a search feature that allows users to search items by name.
   - Provide filtering options to show items by category (e.g., Groceries, Electronics).
   - Add a filter to show only purchased or unpurchased items.

4. **Offline Support (5 Marks)**  
   - Ensure the app works offline using SQLite, allowing the user to manage items.
   - Synchronize the list with Firebase when the device regains internet connection.

---

### **UI Requirements (10 Marks Total)**

1. **App Layout & Design (5 Marks)**  
   - Design a clean and simple UI using Flutter widgets like `ListView`, `TextField`, `DropdownButton`, and `CheckBox` for managing shopping items.
   - Include clear navigation between the shopping list, item details, and settings.

2. **Shopping List Display (5 Marks)**  
   - Display the shopping list with indicators for purchased and unpurchased items.
   - Use color coding or icons to differentiate between categories (e.g., a cart icon for groceries).
   - Provide a search bar and filters to organize the shopping list effectively.

---

### **Submission Requirements (5 Marks Total)**

1. **Code Submission (3 Marks)**  
   - Submit the complete code on a public GitHub repository.
   - Ensure the code is well-commented and includes a README file with instructions on how to set up and run the app.

2. **Demo Video (2 Marks)**  
   - Record a short video demonstrating the main features of the app (CRUD operations, cloud sync, search/filter, and offline mode).

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - SQLite Shopping List Management (15 Marks)  
   - Firebase Cloud Backup (10 Marks)  
   - Search and Filter Items (5 Marks)  
   - Offline Support (5 Marks)

- **UI Design (10 Marks)**  
   - App Layout & Design (5 Marks)  
   - Shopping List Display (5 Marks)

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)

---

**Total Marks:** 50
