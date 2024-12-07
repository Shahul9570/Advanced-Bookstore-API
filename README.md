						**Advanced Bookstore API**

A Django REST API designed to manage a bookstore with features like JWT-based user authentication, book management, and a user review system. The API supports filtering by genre or author, enforces secure permissions, and includes a rating system for user reviews. Thoroughly tested using Postman for seamless functionality.
________________________________________
**Features**

User Authentication
•	Register and log in using JWT tokens for secure user authentication.
•	Protect sensitive endpoints with token-based authentication.
Book Management
•	Create, update, delete, and retrieve book details.
•	Filter books by genre or author through query parameters.
Review System
•	Authenticated users can:
o	Add reviews for books.
o	Edit or delete their own reviews.
•	Includes a star rating system (1-5 stars).
•	Reviews are linked to the logged-in user, ensuring accountability.
Permissions
•	Only authenticated users are allowed to create, update, or delete reviews.
•	Books can only be managed by authorized users (e.g., admin).

________________________________________
**Technologies Used**

•	Django: A high-level Python web framework for rapid development.
•	Django REST Framework (DRF): For creating robust and scalable RESTful APIs.
•	SimpleJWT: Token-based user authentication with JSON Web Tokens.
•	Postman: For testing and validating API functionality.

