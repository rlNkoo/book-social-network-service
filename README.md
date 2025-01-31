# Book-Social-Network

A social network application for book lovers to share, borrow, and manage books efficiently. The platform ensures secure user interactions and robust book management features.

## Features

### User Management
- **User Registration**: Users can create a new account with basic details.
- **Email Validation**: Activation of accounts using secure validation codes sent to registered email addresses.
- **User Authentication**: Secure login for existing users using encrypted credentials.

### Book Management
- **Create, Update, Share, and Archive Books**: Users can manage books by adding new ones, updating details, sharing them within the network, and archiving books when necessary.
  
### Book Sharing and Borrowing
- **Book Borrowing**: Implements necessary checks to determine if a book is available for borrowing.
- **Book Returning**: Users can return books they have borrowed.
- **Book Return Approval**: Functionality to allow the book owner or administrator to approve the return of books.

## Technologies Used

### Backend (book-network)
- **Spring Boot 3**: Main backend framework for developing the application.
- **Spring Security 6**: Provides secure authentication and authorization mechanisms.
- **JWT Token Authentication**: Ensures secure and stateless communication using JSON Web Tokens.
- **Spring Data JPA**: For interacting with the database in a clean and simple way.
- **JSR-303 and Spring Validation**: Ensures that the user and book data meet required standards and constraints.
- **OpenAPI and Swagger UI Documentation**: For generating interactive API documentation.
- **Docker**: For containerizing the application, making deployment easier and more consistent.
