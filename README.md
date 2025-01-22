# Book Management System

The **Book Management System** is a simple web application designed to manage a collection of books. Users can add books with relevant details such as the book name, author name, description, and the number of pages. The added books will be displayed dynamically on the page.

---

## Features

- **Add New Book**: Users can input details for a new book.
- **Display Book List**: The list of added books is displayed dynamically.
- **Input Validation**: Ensures all fields are correctly filled before adding a book.
- **Clear Input Fields**: Automatically clears input fields after adding a book.

---

## File Structure

1. **HTML (`index.html`)**
   - Provides the user interface.
   - Includes fields for entering book details and a button to add books.
   - Displays the list of added books.

2. **JavaScript (`book_system.js`)**
   - Implements the logic for adding books, displaying them, and clearing inputs.
   - Maintains an array (`books`) to store book information.

---

## How to Use

1. Open the `index.html` file in a web browser.
2. Fill in the following details for a new book:
   - **Book Name**: Title of the book.
   - **Author Name**: Name of the book's author.
   - **Book Description**: A brief description of the book.
   - **Number of Pages**: The total number of pages in the book.
3. Click on the **Add Book** button.
4. View the added books under the "Books" section.
5. Repeat the process to add more books.

---

## Validation Rules

- All fields must be filled out.
- The number of pages must be a valid number.

If any field is missing or invalid, an alert will prompt the user to correct the inputs.

---

## Example

### Input:
- **Book Name**: The Great Gatsby  
- **Author Name**: F. Scott Fitzgerald  
- **Book Description**: A novel set in the Jazz Age that explores themes of wealth, love, and the American Dream.  
- **Number of Pages**: 180  

### Output:
- **Book Number**: 1
- **Book Name**: The Great Gatsby Author Name: F. Scott Fitzgerald
- **Book Description**: A novel set in the Jazz Age that explores themes of wealth, love, and the American Dream.
- **No. of Pages**: 180 page(s)


---

## Future Enhancements

- Add functionality to edit or delete books.
- Persist the book data using local storage or a database.
- Improve the user interface with additional styling and features.

---

## License

This project is free to use and modify.
