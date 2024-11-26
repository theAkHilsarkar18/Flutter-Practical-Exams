
---

## **Book Tracker App**  
**Time Limit:** 3 Hours  
**Marks:** 50  

**Problem Statement:**  
Develop a **Book Tracker App** that allows users to manage their reading list, track their progress, and back up data to Firebase. Users should be able to rate books, search for them by genre, and access their data offline.

---

### **Features (35 Marks Total)**  

1. **Book Management with SQLite (15 Marks Total)**  
   - Fields: Book Title, Author, Genre, Status (To Read/Reading/Completed), and Rating (1-5 stars).  
   - Implement **CRUD operations** for managing the book list:  
     - **Add** new books to the list (3 Marks)  
     - **View** and display all book details (4 Marks)  
     - **Update** book status and rating (4 Marks)  
     - **Delete** books from the list (4 Marks)

2. **Firebase Cloud Sync (10 Marks Total)**  
   - Integrate Firebase Authentication for user login/signup using email and password.  
   - Sync book data with Firebase Firestore:  
     - **Upload and update records** to Firestore (5 Marks)  
     - **Download records** from Firestore and synchronize them with local SQLite data (5 Marks)

3. **Genre Filtering and Rating (5 Marks Total)**  
   - Search books by title or filter them by genre.  
   - Include the ability to sort books based on user ratings.

4. **Offline Access and Data Sync (5 Marks Total)**  
   - Ensure the app operates without an internet connection using SQLite.  
   - Sync data automatically when the device regains internet connectivity.

---

### **UI Requirements (10 Marks Total)**  

1. **User-Friendly Layout (5 Marks)**  
   - Create a visually appealing interface with sections for books that are "To Read," "Reading," and "Completed."  
   - Use a ListView to display books, with clear navigation for adding and editing books.

2. **Visual Book Status and Ratings (5 Marks)**  
   - Use icons or color indicators to differentiate between book statuses (e.g., blue for "To Read," yellow for "Reading," and green for "Completed").  
   - Display ratings with star icons beside each book title.

---

### **Submission (5 Marks Total)**  

1. **Code Submission (3 Marks)**  
   - Submit the project to a public GitHub repository with a detailed README file explaining how to set up and use the app.  
   - Ensure code is organized and commented.

2. **Demo Video (2 Marks)**  
   - Provide a short demo video showcasing the app’s functionality, including adding a new book, filtering, rating, and syncing with Firebase.

---

### **Mark Distribution Summary:**

- **Features (35 Marks)**  
   - SQLite Book Management (15 Marks)  
   - Firebase Cloud Sync (10 Marks)  
   - Genre Filtering and Rating (5 Marks)  
   - Offline Access and Sync (5 Marks)  

- **UI Design (10 Marks)**  
   - User-Friendly Layout (5 Marks)  
   - Visual Book Status and Ratings (5 Marks)  

- **Submission (5 Marks)**  
   - Code Submission (3 Marks)  
   - Demo Video (2 Marks)  

---

**Total Marks:** 50
