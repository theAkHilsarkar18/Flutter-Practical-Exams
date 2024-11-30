

## Task Overview
Develop a Flutter application that integrates with an eCommerce API and utilizes Shared Preferences to store and retrieve user data, such as shopping cart details. The app should meet the specified feature and UI requirements outlined below.

API URL: https://fakestoreapi.com/products

### Marking Criteria

### 1. **Features (35 Marks)**

| **Feature**                        | **Description** | **Marks** |
|------------------------------------|-----------------|-----------|
| **API Integration (10 marks)**     | Integrate an eCommerce API to fetch product data and manage shopping cart operations. Ensure the app handles loading states and error handling. | 10 |
| **Data Parsing (5 marks)**         | Parse the JSON response from the eCommerce API and display it in a structured format (e.g., product lists, product details). | 5 |
| **Shared Preferences Implementation (5 marks)** | Use Shared Preferences to store shopping cart items and ensure they persist between app launches. | 5 |
| **Product Display and Filtering (5 marks)** | Display product lists and allow basic filtering or search by product categories, prices, etc. | 5 |
| **Shopping Cart Management (10 marks)** | Implement shopping cart functionality (add, remove, view cart items, and update quantities). | 10 |

### 2. **UI (10 Marks)**

| **UI Component**                   | **Description** | **Marks** |
|------------------------------------|-----------------|-----------|
| **User Experience (5 marks)**      | Provide an intuitive and user-friendly interface with clear navigation and user interactions. Ensure that elements like buttons, lists, and forms are easily tappable and functional. | 5 |
| **Consistent Styling (3 marks)**   | Apply consistent colors, fonts, and layout styles throughout the app for a cohesive look. Ensure the design aligns with standard eCommerce app expectations. | 3 |
| **Product Display Layout (2 marks)** | Display products in a visually appealing and organized manner (e.g., grid or list view). | 2 |

### 3. **Submission (5 Marks)**

| **Submission Component**           | **Description** | **Marks** |
|------------------------------------|-----------------|-----------|
| **Video Demonstration (3 marks)**  | A video walkthrough of the app, showcasing the main features (e.g., viewing products, adding to the cart). The video should be clear and organized, highlighting the core functionality. | 3 |
| **Screenshots (2 marks)**          | Provide at least 3 screenshots of the app showcasing different sections (e.g., product listing, product details, shopping cart). Screenshots should be clear and represent the main features. | 2 |

---

### Detailed Breakdown

#### 1. **API Integration (10 Marks)**
- **API Calls**: Implement HTTP requests to interact with the eCommerce API. Use packages like `http` or `dio` for handling GET and POST requests.
- **Loading and Error States**: Display a simple loading state while data is being fetched (e.g., a spinner) and handle errors gracefully within the app (no detailed error messages required).
- **Data Handling**: Parse JSON data from the API into Dart models and display it appropriately in the app (e.g., using `ListView.builder` for product listings).

#### 2. **Shared Preferences Implementation (5 Marks)**
- **Data Storage and Retrieval**: Implement Shared Preferences to store cart data and ensure it is persistent across app launches.
- **Cart Persistence**: Verify that the cart items remain stored in Shared Preferences and are retrievable when the app is reopened.

#### 3. **Product Display and Filtering (5 Marks)**
- **Product Listing**: Create a UI that displays a list of products fetched from the API, with relevant details like product names, prices, and images.
- **Filtering/Search**: Implement basic filtering functionality to allow users to search for products by categories, price range, or keywords.

#### 4. **Shopping Cart Management (10 Marks)**
- **Cart Functionality**: Implement features to add, remove, and modify quantities of items in the cart.
- **Cart Display**: Provide a clear view of cart contents and total price.
- **Data Persistence**: Store and retrieve cart data using Shared Preferences so that items added to the cart persist across app restarts.

### **UI Components**
- **User Experience**: The app should be user-friendly, with clear navigation and interaction points for adding and viewing items.
- **Consistent Styling**: Maintain a cohesive look throughout the app using uniform colors, fonts, and layout styles.
- **Product Display Layout**: Use a grid or list view to display products in a clear and organized way.

### **Submission**
- **Video**: The video should cover a demonstration of the app's main functionality, including viewing products, adding items to the cart, and viewing the cart page.
- **Screenshots**: Include at least 3 screenshots that capture different parts of the app, such as the product listing page, product detail page, and the shopping cart.

---

### **Grading Notes**
- Ensure each feature is fully implemented to earn full marks.
- The UI should be practical, easy to use, and visually consistent throughout the app.
- The video should demonstrate key features clearly and be easy to follow.
- Screenshots should be of high quality and show relevant portions of the app's interface.

---
