# vBlog-Springboot-API
This is a Spring Boot application designed for managing a blog platform. It supports features like managing blog posts, categories, tags, users, comments, and likes. The backend is powered by Spring Boot, with PostgreSQL as the database for storing blog data.

# Features:
The Blog API provides the following key features:

1. User Management
    a.  Create and manage user accounts, including roles, passwords, and profiles.
    b.  Users can create blog posts, leave comments, and like posts.

2. Blog Posts
    a.  Full CRUD (Create, Read, Update, Delete) functionality for blog posts.
    b.  Each post includes a title, content, summary, publication date, and author.

3. Categories
    a.  Organize blog posts by categories.
    b.  Categories include a name and description and can be linked to multiple posts.

4. Tags
    a.  Tag posts with keywords.
    b.  Tags include a name and description and can be applied to multiple posts.

5. Comments
    a.  Users can leave comments on blog posts.
    b.  Each comment includes content, a creation date, and is linked to a specific post and author.

6. Likes
    a.  Users can like blog posts.
    b.  Each like is linked to a specific post and user, with a record of the creation date.

# Technologies
The following technologies are used in this application:

1. Spring Boot: Main framework for building the application.
2. Spring Data JPA: For database interactions and persistence.
3. Spring Security: To handle authentication and authorization.
4. PostgreSQL: Database management system used for storing data.
5. Lombok: Reduces boilerplate code through annotations.
6. JWT (JSON Web Token): For securing API endpoints.
7. Maven: For dependency management and project build lifecycle.

# Running the Application
To run the Blog API locally:
1.	Clone the repository.
2.	Import the project into your preferred Java IDE (IntelliJ, Eclipse).
3.	Build the project to resolve dependencies.
4.	Run the application using your IDE or through the command line using mvn spring-boot:run.
