
---

## **Inventory Tracker App**  
**Time Limit:** 3 Hours  
**Marks:** 50  

**Problem Statement:**  
Create an **Inventory Tracker App** to manage stock levels and track inventory items. Use **SQLite** for local storage and **Firebase** for cloud backup. Users should be able to categorize items, get alerts for low stock, and access data offline.

---

### **Features (35 Marks Total)**  

1. **Enhanced Inventory Management with SQLite (15 Marks Total)**  
   - Fields: Item Name, Quantity, Category (e.g., Electronics, Furniture, Clothing), Supplier, and Last Updated Date.  
   - Implement **CRUD operations** for inventory management:  
     - **Add** new items with category selection and supplier info (4 Marks)  
     - **Display** items categorized in a ListView (3 Marks)  
     - **Update** item details, including stock quantity and category (4 Marks)  
     - **Delete** items from the inventory (4 Marks)

2. **Firebase Cloud Sync (10 Marks Total)**  
   - Implement Firebase Authentication using email and password.  
   - Sync inventory data with Firebase Firestore:  
     - **Upload inventory data** to Firestore (5 Marks)  
     - **Fetch and update data** from Firestore to the local SQLite database (5 Marks)

3. **Stock Alerts & Sorting (5 Marks Total)**  
   - Implement a **low stock alert** for items with quantities below a user-defined threshold (e.g., less than 5 units).  
   - Provide sorting options to sort items by quantity or category.

4. **Offline Functionality & Auto-Sync (5 Marks Total)**  
   - Ensure the app operates fully offline using SQLite for data storage.  
   - Automatically sync data to Firebase when the internet connection is restored.

---

### **UI Requirements (10 Marks Total)**  

1. **Organized Layout (5 Marks)**  
   - Design an intuitive interface with a categorized ListView for inventory items.  
   - Use a Floating Action Button (FAB) for adding new items.

2. **Visual Stock Indicators (5 Marks)**  
   - Display items with low stock in a distinct color (e.g., red for low stock, green for sufficient stock).  
   - Use icons or badges to indicate the item’s category.

---

### **Submission (5 Marks Total)**  

1. **Code Submission (3 Marks)**  
   - Submit the project to a public GitHub repository with clear setup instructions in a README file.  
   - Ensure code is properly documented with comments.

2. **Demo Video (2 Marks)**  
   - Create a demo video showcasing key features like adding items, low stock alerts, and Firebase sync.

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - Enhanced Inventory Management with SQLite (15 Marks)  
   - Firebase Cloud Sync (10 Marks)  
   - Stock Alerts & Sorting (5 Marks)  
   - Offline Functionality & Auto-Sync (5 Marks)  

- **UI Design (10 Marks)**  
   - Organized Layout (5 Marks)  
   - Visual Stock Indicators (5 Marks)  

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)  

---

**Total Marks:** 50
