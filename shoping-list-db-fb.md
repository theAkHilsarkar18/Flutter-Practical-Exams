
---

### Practical Exam Question (50 Marks)  
**Topic:** Flutter Application with SQLite and Firebase Integration  

---

#### **Question: Build a Flutter Grocery List Application with SQLite and Firebase**

**Time Limit:** The task should be completed within **3 hours**.

**Problem Statement:**

You are required to build a Grocery List application using Flutter. The app should manage grocery items locally with SQLite, categorize them, and back up the data using Firebase. Users should have the ability to search, filter, and sort items based on various criteria.

---

### **Features to Implement (35 Marks Total)**

1. **Grocery List Management with SQLite (15 Marks)**  
   - Create a local SQLite database to store grocery list items.  
   - Each item should have the following fields:  
     - Item Name (String)  
     - Quantity (Number)  
     - Category (e.g., Vegetables, Dairy, Household)  
     - Expiration Date (Date)  
     - Purchased Status (Boolean - True/False)  
   - Implement **CRUD** (Create, Read, Update, Delete) operations for managing grocery items:  
     - **Add a new item with category selection** (3 Marks)  
     - **Display all items** in a categorized ListView (3 Marks)  
     - **Update item details** including quantity and expiration date (3 Marks)  
     - **Delete an item from the list** (3 Marks)  
     - **Mark items as purchased/unpurchased** (3 Marks)

2. **Firebase Integration for Cloud Backup (10 Marks)**  
   - Implement Firebase Authentication for user sign-in/up using email/password.  
   - Sync grocery items with Firebase Firestore:  
     - **Upload grocery items** to Firestore for cloud backup (5 Marks)  
     - **Fetch and sync items** from Firestore to update the local SQLite database (5 Marks)

3. **Sorting and Filtering Items (5 Marks)**  
   - Implement sorting options (e.g., by category, expiration date, or quantity).  
   - Add filtering options to show items based on their category (e.g., Vegetables, Dairy).  
   - Provide an option to display only purchased or unpurchased items.

4. **Offline Data Management (5 Marks)**  
   - Ensure the app is fully functional offline using SQLite for data storage.  
   - Automatically synchronize with Firebase Firestore when the internet connection is restored.

---

### **UI Requirements (10 Marks Total)**

1. **User Interface Design (5 Marks)**  
   - Design an easy-to-navigate UI using Flutter widgets like `ListView`, `DatePicker`, `DropdownButton`, and `CheckBox` for managing grocery items.  
   - Include clear navigation between grocery list, item details, and user settings.

2. **Grocery List Visualization (5 Marks)**  
   - Use distinct visual cues like icons or colors to differentiate between item categories (e.g., green for Vegetables, blue for Dairy).  
   - Implement a search bar to quickly locate items.  
   - Display item expiration dates and highlight those close to expiration.

---

### **Submission Requirements (5 Marks Total)**

1. **Code Submission (3 Marks)**  
   - Submit the full source code to a public GitHub repository.  
   - Ensure the code is documented, with a README file explaining how to set up and use the application.

2. **Demo Video (2 Marks)**  
   - Record a video that demonstrates the app’s core features, including CRUD operations, Firebase sync, filtering/sorting, and offline capabilities.

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - Grocery List Management with SQLite (15 Marks)  
   - Firebase Cloud Backup (10 Marks)  
   - Sorting and Filtering Items (5 Marks)  
   - Offline Data Management (5 Marks)

- **UI Design (10 Marks)**  
   - User Interface Design (5 Marks)  
   - Grocery List Visualization (5 Marks)

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)

---

**Total Marks:** 50
