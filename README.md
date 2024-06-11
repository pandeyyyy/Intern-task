# Intern-task


Project Aim:
The goal of the project is to build a backend system that supports user management, authentication, and social media functionalities, including posting, viewing posts, and interacting with other users.

Achievements:
User Management:
Registration and Login: Implemented user registration and login functionality using email and password.
Profile Management: Enabled users to update their profiles, including username, bio, and profile picture.
Password Security: Implemented password hashing using bcrypt for secure storage.
Posts:

Post Creation: Users can create posts with text, images, and timestamps.
Post Interaction: Users can like, dislike, update, and delete posts.
Timeline: Implemented functionality to view posts from the user and those they follow.
Middleware:

Helmet: Integrated Helmet for setting various HTTP headers to enhance security.
Morgan: Utilized Morgan for logging HTTP requests to the console for monitoring and debugging.
Database Integration:

MongoDB: Connected the application to MongoDB using Mongoose.
Schemas: Defined schemas for users and posts to ensure data consistency and integrity.
Routes:

Authentication Routes: Configured routes for user registration and login.
User Routes: Managed user-related endpoints for updating and deleting profiles, as well as following and unfollowing users.
Post Routes: Managed post-related endpoints for creating, updating, deleting, liking, and viewing posts.
Security:

Password Hashing: Used bcrypt to hash passwords before storing them in the database.
JWT Authentication: Ensured secure session management through JSON Web Token (JWT) authentication.
Authorization Checks: Implemented checks to ensure users can only update or delete their own posts and profiles.
Helmet Middleware: Used Helmet to secure HTTP headers and protect against common web vulnerabilities.
Input Validation: Ensured validation and sanitation of user inputs to prevent injection attacks.
Error Handling:

Provided appropriate error messages and status codes for various scenarios, such as invalid inputs, failed operations, and unauthorized access attempts.
Server Initialization:



