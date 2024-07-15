# Library-App

## Description

This project is a Library Management App built using React.

## Features

- Display list of books with details (title, author, ISBN).

## Technologies Used

- React
- JavaScript (ES6+)
- HTML5
- CSS3 (Bootstrap for styling)

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the development server using `npm start`.
5. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Part 2

### Components to Create

- **Navbar Component:**
  - This component should contain links to Home, About, Contact, and Sign-up pages.

- **About Us Component:**
  - This component should provide information about the project or team.

- **Contact Us Component:**
  - This component should include a form or details for users to contact support or provide feedback.

- **Sign-up Component:**
  - Implement a sign-up form in this component.
  - Save user data in localStorage upon successful registration.
  - If the user is logged in, display a logout button and a welcome message with the username.

## Part 3

### Book Catalog Component with Firebase Integration

#### Overview
In this part, we will integrate Firebase to manage a catalog of books. This includes fetching books from Firebase, adding new books, editing existing ones, and implementing soft delete.

#### Features to Implement

- **Fetch Books:**
  - Retrieve the list of books from Firebase and display them in the app.
  
- **Add New Book:**
  - Provide a form to add a new book to the catalog. Store the book details in Firebase.
  
- **Edit Book:**
  - Allow users to edit the details of existing books. Update the changes in Firebase.
  
- **Soft Delete Book:**
  - Implement a soft delete feature to mark a book as deleted without removing it from Firebase. Soft-deleted books should not be displayed in the main catalog.

#### Steps to Implement

1. **Setup Firebase:**
   - Create a Firebase project.
   - Add Firebase configuration to your React app.
   - Initialize Firebase in your app.

2. **Create Book Catalog Component:**
   - Build a component to display the list of books.
   - Fetch books from Firebase and display them in this component.

3. **Add Book Form:**
   - Create a form to add new books.
   - On form submission, save the book details to Firebase.

4. **Edit Book Functionality:**
   - Add functionality to edit book details.
   - Update the book details in Firebase upon submission.

5. **Soft Delete Functionality:**
   - Implement a soft delete feature to mark books as deleted.
   - Ensure soft-deleted books are not displayed in the main catalog.

