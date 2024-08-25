# vBlog-Springboot-API
This is a Spring Boot application designed for managing a blog platform. It supports features like managing blog posts, categories, tags, users, comments, and likes. The backend is powered by Spring Boot, with PostgreSQL as the database for storing blog data.

# Features:
The Blog API provides the following key features:
User Management.
•	Create and manage user accounts, including roles, passwords, and profiles.
•	Users can create blog posts, leave comments, and like posts.
Blog Posts.
•	Full CRUD (Create, Read, Update, Delete) functionality for blog posts.
•	Each post includes a title, content, summary, publication date, and author.
Categories.
•	Organize blog posts by categories.
•	Categories include a name and description and can be linked to multiple posts.
Tags.
•	Tag posts with keywords.
•	Tags include a name and description and can be applied to multiple posts.
Comments.
•	Users can leave comments on blog posts.
•	Each comment includes content, a creation date, and is linked to a specific post and author.
Likes.
•	Users can like blog posts.
•	Each like is linked to a specific post and user, with a record of the creation date.

# Technologies
The following technologies are used in this application:
•	Spring Boot: Main framework for building the application.
•	Spring Data JPA: For database interactions and persistence.
•	Spring Security: To handle authentication and authorization.
•	PostgreSQL: Database management system used for storing data.
•	Lombok: Reduces boilerplate code through annotations.
•	JWT (JSON Web Token): For securing API endpoints.
•	Maven: For dependency management and project build lifecycle.

# Running the Application
To run the Blog API locally:
1.	Clone the repository.
2.	Import the project into your preferred Java IDE (IntelliJ, Eclipse).
3.	Build the project to resolve dependencies.
4.	Run the application using your IDE or through the command line using mvn spring-boot:run.
